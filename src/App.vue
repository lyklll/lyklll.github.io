<template>
    <div id="app">
      
        <van-tabbar v-model="active">
            <van-tabbar-item icon="home">首页</van-tabbar-item>
            <van-tabbar-item icon="play" dot>游乐指南</van-tabbar-item>
            <van-tabbar-item icon="search" info="5">发现</van-tabbar-item>
            <van-tabbar-item icon="contact" info="20">我的</van-tabbar-item>
        </van-tabbar>
    </div>
</template>
<script>
export default {
    data() {
        return {
            active: 2
        }

    }

}
</script>
<style>
</style>