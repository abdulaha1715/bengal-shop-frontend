<template>
  <div>
    <div class="container">
      <div class="py-6 flex justify-between items-center">
        <nuxt-link to="/" class="flex font-size-32 font-medium items-center">
          <img src="~/assets/img/logo.png" alt=""> Bengal shop
        </nuxt-link>

        <div class="w-96">
          <div class="border border-gray-100 p-1 flex rounded-full items-center">
            <div class="min-w-max px-3">
              <img src="~/assets/img/search.png" alt="">
            </div>
            <input type="text" class="w-full px-3 pxy-1 focus:outline-none" placeholder="Search here...">

            <button class="bg-gray bs-button-bg px-6 rounded-full py-2 text-white" type="submit">Search</button>
          </div>
        </div>

        <div class="min-w-max flex items-center">
          <nuxt-link to="/">
            <span class="bs-icon-box rounded-full hover:bg-gray-200 inline-block flex items-center justify-center"><img src="~/assets/img/heart.png" alt="heart"></span>
          </nuxt-link>
          <nuxt-link to="/" class="relative mx-4">
            <span class="bs-icon-box rounded-full hover:bg-gray-200 inline-block flex items-center justify-center"><img src="~/assets/img/u_shopping-bag.png" alt="shopping-bag"><span class="absolute bg-red-600 w-4 h-4 top-0 right-0 rounded-full text-xs flex justify-center items-center text-white">0</span></span>
          </nuxt-link>
          <nuxt-link to="/" class="flex items-center">
            <span class="bs-icon-box rounded-full hover:bg-gray-200 inline-block flex items-center justify-center"><img src="~/assets/img/user.png" alt="user"></span><span>Account</span>
          </nuxt-link>
        </div>
        </div>
      </div>
    </div>

  </div>
</template>

<script>
export default {
  name: 'Header'
}
</script>

<style>

</style>
