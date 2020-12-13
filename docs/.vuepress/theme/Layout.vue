<template>
  <div class="main-layout">
    <header>
      <div class="header-left">
      Cheatsheets by&nbsp;<a href="https://github.com/edwardcxyz">@edwardcxyz</a>
      </div>
      <SearchBox/>
    </header>
    <Content />
  </div>
</template>

<script>
import SearchBox from "@SearchBox";

export default {
  components: {
    SearchBox
  }
};
</script>

<style lang="stylus">
body
  background #333
.main-layout
  display flex
  max-width 1024px
  height 100vh
  margin 0 auto
  background-color #fff
  padding 0 64px 0 64px
  overflow auto
  flex-flow column nowrap
  header
    display flex
    align-items center
    height 64px
    .header-left
      height 100%
      display flex
      align-items center
      min-width 400px
      a
        color unset
    .search-box
      margin-left auto

code
  background #ccc
  font-weight bold
  padding 2px 8px
  border-radius 4px
  box-shadow 0px 4px 8px rgba(0,0,0,0.2)

</style>
