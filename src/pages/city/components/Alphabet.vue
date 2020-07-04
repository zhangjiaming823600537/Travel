<template>
  <ul class="list" ref="wrapper">
      <li class="item">A</li>
  </ul>

</template>

<script>
import Bscroll from 'better-scroll'

export default {
  name: 'cityAlphabet',
  mounted () {
    this.scroll = new Bscroll(this.$refs.wrapper)
  }
}
</script>

<style lang="stylus" scoped>
  @import '~styles/varibles.styl'
  .list
    display: flex
    flex-direction: column
    justify-content: center
    position: absolute
    top: 1.58rem
    right: 0
    bottom: 0
    width: .4rem
    .item
      text-direction:none
      line-height: .4rem
      text-align: center
      color: $bgColor
</style>
