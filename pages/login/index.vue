<template>
  <div class="h-screen flex justify-center items-center w-full">
    <form>
      <div class="px-8 py-6 w-screen max-w-sm">
        <div class="space-y-5">
          <nuxt-link to="/" class="text-4xl inline-flex">
            <div class="font-extralight">
              CORK
            </div>
            <div>
              LOG
            </div>
          </nuxt-link>
          <div>
            <label for="email" class="block mb-1 text-gray-600 font-semibold">이메일</label>
            <input type="text" class="bg-blue-50 px-4 py-2 outline-none rounded-md w-full">
          </div>
          <div>
            <label for="password" class="block mb-1 text-gray-600 font-semibold">비밀번호</label>
            <input type="password" class="bg-blue-50 px-4 py-2 outline-none rounded-md w-full">
          </div>
        </div>
        <button class="mt-8 py-2 w-full text-white rounded-md shadow-md bg-blue-500 hover:bg-blue-400 focus:ring focus:ring-blue-300">
          로그인
        </button>
      </div>
    </form>
  </div>
</template>

<script>

export default {
  name: 'IndexLogin'
}
</script>

<style>

</style>
