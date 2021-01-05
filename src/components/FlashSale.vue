<template>
  <div class="mod_sale">
    <img src="http://jdc.jd.com/img/750x286?color=eeeeee" />
    <div class="mod_sale_countdown">
      倒计时
      <span class="mod_sale_countdown_num">0</span
      ><span class="mod_sale_countdown_num">0</span>分
      <span class="mod_sale_countdown_num">0</span
      ><span class="mod_sale_countdown_num">0</span>秒 结束
    </div>
  </div>
</template>

<style lang="scss" scoped>
.mod_sale {
  position: relative;
  height: 0;
  overflow: hidden;
  padding-top: 38.13333%;

  img {
    width: 100%;
    height: auto;
    position: absolute;
    left: 0;
    top: 0;
  }

  .mod_sale_countdown {
    position: absolute;
    bottom: rem(10);
    font-size: rem(12);
    line-height: rem(24);
    width: 100%;
    text-align: center;
    color: #333;

    .mod_sale_countdown_num {
      display: inline-block;
      vertical-align: middle;
      margin-top: -2px;
      width: rem(18);
      height: rem(24);
      font-size: rem(14);
      line-height: rem(24);
      text-align: center;
      color: #fff;
      background-color: #000;
      border-radius: rem(2);
      margin-right: rem(2);
    }
  }
}
</style>