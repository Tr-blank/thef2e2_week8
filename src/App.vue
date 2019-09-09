<template lang="pug">
  .app
    header
      img(src="@/assets/images/logo.svg")
      a.header__botton 上傳檔案
      nav.nav
        a.nav__item 上傳資料夾
        a.nav__item 新資料夾
        a.nav__item 共享資料夾
        a.nav__item 已標記星號
        a.nav__item 垃圾桶
    main.folder
      .folder__header
        .breadcrumbs
          a.breadcrumbs__item 我的雲端硬碟
          span.breadcrumbs__item.breadcrumbs__item--now The F2E 2nd UI 設計資源
</template>

<script>

import './assets/style/normalize.css'
import './assets/style/reset.css'

export default {
  name: 'App',
  components: {
  },
  data () {
    return {
    }
  },
  created () {

  },
  mounted () {
  },
  computed: {

  },
  methods: {
  }
}
</script>

<style lang="stylus">
body
  background: #25272C;
  color: #F3F2EF;
  font: Regular 16px/24px Noto Sans TC Regular;
  letter-spacing: 1.6px;
  font-size: 16px;

</style>

<style lang="stylus" scoped>
.app
  display: flex;
  height: 100vh;
header
  width: 20%;
  padding: 80px 45px 0
  text-align: center;
  background: #2F3136;
.folder
  width: 80%;
  padding: 30px;
.header__botton
  display: block;
  background: #FFD46E;
  border-radius: 30px;
  color: #25272C;
  line-height: 52px;
  margin: 40px 0;
.nav__item
  display: block;
  margin-bottom: 12px;

</style>
