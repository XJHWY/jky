<template>
  <div>
    <van-tabbar route>
      <van-tabbar-item replace to="/home">
        <template #icon>
          <i class="toutiao toutiao-shouye"></i> </template
        >首页
      </van-tabbar-item>
      <van-tabbar-item replace to="/video">
        <template #icon>
          <i class="toutiao toutiao-shipin"></i> </template
        >视频
      </van-tabbar-item>
      <van-tabbar-item replace to="/question">
        <template #icon>
          <i class="toutiao toutiao-wenda"></i>
        </template>
        问答
      </van-tabbar-item>
      <van-tabbar-item replace to="/my">
        <template #icon>
          <i class="toutiao toutiao-wode"></i>
        </template>
        我的
      </van-tabbar-item>
    </van-tabbar>
    <router-view></router-view>
  </div>
</template>

<script>
export default {
}
</script>

<style scoped lang="less">
  .toutiao{
    font-size: 40px;
    /deep/.van-tabbar-item__text{
      font-size: 20px;
    }
  }
</style>
