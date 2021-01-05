<template>
  <div class="mod_bbs">
    <div class="mod_bbs_msg">
      <ul class="mod_bbs_msg_list">
        <li class="mod_bbs_msg_item">
          <p class="mod_bbs_msg_text">
            <i class="mod_sign">拼便宜</i>海南木瓜最低价 富含维生素C抗氧化
            <small class="mod_bbs_msg_text_em">4人成团 9.9包邮</small>
          </p>
        </li>
        <li class="mod_bbs_msg_item">
          <p class="mod_bbs_msg_text">
            <i class="mod_sign">拼便宜</i>海南木瓜最低价 富含维生素C抗氧化
            <small class="mod_bbs_msg_text_em">4人成团 9.9包邮</small>
          </p>
        </li>
        <li class="mod_bbs_msg_item">
          <p class="mod_bbs_msg_text">
            <i class="mod_sign">拼便宜</i>海南木瓜最低价 富含维生素C抗氧化
            <small class="mod_bbs_msg_text_em">4人成团 9.9包邮</small>
          </p>
        </li>
      </ul>
    </div>
    <div class="mod_bbs_banner">
      <img src="http://jdc.jd.com/img/710x90" />
    </div>
  </div>
</template>

<style lang="scss" scoped>
.mod_bbs {
  margin-bottom: rem(10);
  background-color: #fff;
  overflow: hidden;

  .mod_bbs_msg {
    position: relative;
    margin: rem(10);
    border-radius: rem(15);
    padding: rem(5) rem(10) rem(5) rem(61);
    background-color: #f5f5fa;

    &::before {
      position: absolute;
      left: rem(10);
      content: "";
      width: rem(46);
      height: rem(38);
      background: url('~@/assets/images/headline.png') center no-repeat;
      background-size: 100%;
    }

    .mod_bbs_msg_list {
      height: rem(38);
      overflow: hidden;

      .mod_bbs_msg_text {
        color: #333;
        font-size: rem(14);

        .mod_bbs_msg_text_em {
          display: block;
          font-size: rem(12);
          color: #e4393c;
        }
      }
    }
  }

  .mod_bbs_banner {
    margin: rem(10);
    position: relative;
    height: 0;
    overflow: hidden;
    padding-top: 12.67606%;

    img {
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: auto;
    }
  }
}
</style>