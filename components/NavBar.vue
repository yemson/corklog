<template>
  <div class="m-4 mt-4 mx-6 flex justify-between">
    <nuxt-link to="/" class="text-3xl inline-flex">
      <div class="font-extralight">
        CORK
      </div>
      <div>
        LOG
      </div>
    </nuxt-link>
    <div v-if="auth == true">
      <nuxt-link to="/signup">
        회원가입
      </nuxt-link>
      <nuxt-link to="/login">
        <button class="ml-3 px-4 py-2 rounded-md text-white shadow-md bg-blue-500 hover:bg-blue-400 focus:ring focus:ring-blue-300">
          로그인
        </button>
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
