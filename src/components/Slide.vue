<template>
  <div class="mod_slide">
    <div class="mod_slide_inner">
      <ul class="mod_slide_list">
        <li class="mod_slide_list_item">
          <img src="http://jdc.jd.com/img/750x340" />
        </li>
      </ul>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.mod_slide {
  position: relative;

  .mod_slide_inner {
    overflow: hidden;

    .mod_slide_list {
      font-size: 0;
      font-family: none;
      white-space: nowrap;
      -webkit-overflow-scrolling: touch;
      overflow: hidden;
      overflow-x: auto;

      .mod_slide_list_item {
        display: inline-block;
        vertical-align: top;
        position: relative;
        width: 100%;
        height: 0;
        overflow: hidden;
        padding-top: 45.33333%;

        img {
          width: 100%;
          height: auto;
          position: absolute;
          left: 0;
          top: 0;
        }
      }
    }
  }
}
</style>