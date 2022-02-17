<template>
  <div class="m-4 mt-4 mx-6 flex justify-between">
    <div class="text-3xl inline-flex">
      <div class="font-extralight">
        CORK
      </div>
      <div>
        LOG
      </div>
    </div>
    <div v-if="auth == true">
      <nuxt-link to="/signup">
        회원가입
      </nuxt-link>
      <nuxt-link to="/login" class="ml-3 px-4 py-2 rounded-md text-white shadow-md bg-blue-500 hover:bg-blue-400 focus:ring focus:ring-blue-300">
        로그인
      </nuxt-link>
    </div>
  </div>
</template>

<script>
export default {
  name: 'NavBar',
  props: {
    auth: {
      type: Boolean,
      default: true
    }
  }
}
</script>

<style>

</style>
