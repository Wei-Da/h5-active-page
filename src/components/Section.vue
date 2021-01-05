<template>
  <div class="mod_section">
    <a href="#" class="mod_section_title">
      <h2 class="mod_section_title_name">趣好货</h2>
      <p class="mod_section_title_desc">
        <span class="mod_section_title_desc_img">
          <img src="http://jdc.jd.com/img/100x70?color=eeeeee" />
        </span>
        今日上新90个特价商品
        <i class="mod_section_title_desc_arrow"></i>
      </p>
    </a>
    <div class="mod_qu">
      <div class="mod_qu_head">
        <span class="mod_qu_head_name">最好货</span>
      </div>
      <ul class="mod_qu_list">
        <li class="mod_qu_item">
          <a href="#" class="mod_qu_item_url">
            <i class="mod_qu_item_tag">四字文案</i>
            <div class="mod_qu_item_cover">
              <img src="http://jdc.jd.com/img/260" />
            </div>
            <p class="mod_qu_item_name">三星笔记本散热快超级薄什么都好好</p>
            <p class="mod_qu_item_desc">
              描述描述描述描述描述描述描述描述描述描述描述描述
            </p>
            <div class="mod_qu_item_sale">
              <i class="mod_sign bor">可领券</i>
              <i class="mod_sign bor">可领取</i>
            </div>
            <p class="mod_qu_item_price">
              ¥ <b class="mod_qu_item_price_int">2999</b>.00
            </p>
            <p class="mod_qu_item_like">129999人说好</p>
          </a>
        </li>
        <li class="mod_qu_item">
          <a href="#" class="mod_qu_item_url">
            <i class="mod_qu_item_tag">四字文案</i>
            <div class="mod_qu_item_cover">
              <img src="http://jdc.jd.com/img/260" />
            </div>
            <p class="mod_qu_item_name">三星笔记本散热快超级薄什么都好好</p>
            <p class="mod_qu_item_desc">
              描述描述描述描述描述描述描述描述描述描述描述描述
            </p>
            <div class="mod_qu_item_sale">
              <i class="mod_sign bor">可领券</i>
              <i class="mod_sign bor">可领取</i>
            </div>
            <p class="mod_qu_item_price">
              ¥ <b class="mod_qu_item_price_int">2999</b>.00
            </p>
            <p class="mod_qu_item_like">129999人说好</p>
          </a>
        </li>
        <li class="mod_qu_item mod_qu_more">
          <a href="#" class="mod_qu_item_url"> 查看更多 </a>
        </li>
      </ul>
    </div>
    <div class="mod_group">
      <a href="#" class="mod_group_item">
        <dl class="mod_group_item_info">
          <dt class="mod_group_item_name">趣主题</dt>
          <dd class="mod_group_item_desc">上班必买神器</dd>
          <dd class="mod_group_item_desc">每满千减百</dd>
        </dl>
        <div class="mod_group_item_img">
          <img src="http://jdc.jd.com/img/180?color=ffe8e3" />
        </div>
      </a>
      <a href="#" class="mod_group_item">
        <dl class="mod_group_item_info">
          <dt class="mod_group_item_name">趣主题</dt>
          <dd class="mod_group_item_desc">上班必买神器</dd>
          <dd class="mod_group_item_desc">每满千减百</dd>
        </dl>
        <div class="mod_group_item_img">
          <img src="http://jdc.jd.com/img/180?color=ffe8e3" />
        </div>
      </a>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.mod_section {
  position: relative;
  margin-bottom: rem(10);
  overflow: hidden;
  background-color: #fff;

  .mod_section_title {
    position: relative;
    display: block;
    padding: 0 rem(10);
    height: rem(40);
    line-height: rem(40);

    .mod_section_title_name {
      font-size: rem(14);
      display: inline-block;
    }

    .mod_section_title_desc {
      float: right;
      font-size: rem(12);
      color: #999;

      .mod_section_title_desc_img {
        display: inline-block;
        vertical-align: middle;
        margin-top: -2px;
        width: rem(50);

        img {
          display: block;
          margin: 0 auto;
          max-width: 100%;
        }
      }
    }
  }
}
</style>