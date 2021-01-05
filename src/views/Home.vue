<template>
  <div class="home">
    <!-- S 轮播 -->
    <Slide />
    <!-- E 轮播 -->
    <!-- S 广告坑位 -->
    <Banner />
    <!-- E 广告坑位 -->
    <!-- S 二级入口导航 -->
    <Navigation />
    <!-- E 二级入口导航 -->
    <!-- S 秒杀坑位 -->
    <FlashSale />
    <!-- E 秒杀坑位 -->
    <!-- S 促销公告 -->
    <SalesPromotion />
    <!-- E 促销公告 -->
    <!-- S 频道楼层 -->
    <Section />
    <!-- E 频道楼层 -->
  </div>
</template>

<script>
// @ is an alias to /src
import Slide from "@/components/Slide";
import Banner from "@/components/Banner";
import Navigation from "@/components/Navigation";
import FlashSale from "@/components/FlashSale";
import SalesPromotion from "@/components/SalesPromotion"
import Section from "@/components/Section"

export default {
  name: "Home",
  components: {
    Slide,
    Banner,
    Navigation,
    FlashSale,
    SalesPromotion,
    Section
  },
};
</script>

<style lang="scss" scoped>
</style>
