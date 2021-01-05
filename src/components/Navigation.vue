<template>
  <div class="mod_nav">
    <nav class="mod_nav_list">
      <a v-for="(item, index) in 5" :key="index" href="#" class="mod_nav_list_item">
        <span class="mod_nav_list_item_logo">
          <img src="http://jdc.jd.com/img/80" />
        </span>
        <p class="mod_nav_list_item_name">导航入口</p>
      </a>
    </nav>
  </div>
</template>

<style lang="scss" scoped>
.mod_nav {
  background-color: #fff;

  .mod_nav_list {
    display: flex;
    padding: rem(15) rem(10);

    .mod_nav_list_item {
      flex: 1;
      text-align: center;
      font-size: 10px;

      .mod_nav_list_item_logo {
        display: block;
        margin: 0 auto;
        width: rem(40);
        height: rem(40);

        img {
          display: block;
          margin: 0 auto;
          max-width: 100%;
        }
      }

      .mod_nav_list_item_name {
        margin-top: rem(2)
      }
    }
  }
}
</style>