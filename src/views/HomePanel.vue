<template>
  <div>
    <TopBar></TopBar>
    <SideBar></SideBar>
    <router-view class="right-area"></router-view>
  </div>
</template>
<script>
  import TopBar from '@/views/Layouts/TopBar'
  import SideBar from '@/views/Layouts/SideBar'
  export default {
    components: {SideBar, TopBar}
  }
</script>
