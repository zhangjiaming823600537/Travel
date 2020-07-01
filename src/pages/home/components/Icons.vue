<template>
  <div class="icons">
    <div class="icon">
      <div class="icon-img">
        <img src="http://img1.qunarzz.com/piao/fusion/1611/54/ace00878a52d9702.png" class="icon-img-content"/>
      </div>
      <p class="icon-desc">热门景点</p>
    </div>
     <div class="icon">
      <div class="icon-img">
        <img src="http://img1.qunarzz.com/piao/fusion/1611/54/ace00878a52d9702.png" class="icon-img-content"/>
      </div>
      <p class="icon-desc">热门景点</p>
    </div>
     <div class="icon">
      <div class="icon-img">
        <img src="http://img1.qunarzz.com/piao/fusion/1611/54/ace00878a52d9702.png" class="icon-img-content"/>
      </div>
      <p class="icon-desc">热门景点</p>
    </div>
     <div class="icon">
      <div class="icon-img">
        <img src="http://img1.qunarzz.com/piao/fusion/1611/54/ace00878a52d9702.png" class="icon-img-content"/>
      </div>
      <p class="icon-desc">热门景点</p>
    </div>
     <div class="icon">
      <div class="icon-img">
        <img src="http://img1.qunarzz.com/piao/fusion/1611/54/ace00878a52d9702.png" class="icon-img-content"/>
      </div>
      <p class="icon-desc">热门景点</p>
    </div>
     <div class="icon">
      <div class="icon-img">
        <img src="http://img1.qunarzz.com/piao/fusion/1611/54/ace00878a52d9702.png" class="icon-img-content"/>
      </div>
      <p class="icon-desc">热门景点</p>
    </div>
     <div class="icon">
      <div class="icon-img">
        <img src="http://img1.qunarzz.com/piao/fusion/1611/54/ace00878a52d9702.png" class="icon-img-content"/>
      </div>
      <p class="icon-desc">热门景点</p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HomeIcons'
}
</script>

<style lang="stylus" scoped>
 @import '~styles/varibles.styl'
  @import '~styles/mixins.styl'
.icons
  height: 0;
  padding-bottom: 50%;
  overflow: hidden;
  .icon
    position relative
    overflow: hidden;
    width: 25%;
    height:0;
    float: left;
    padding-bottom: 25%;
    .icon-img
      box-sizing: border-box
      padding 0.1rem
      position:absolute
      top:0
      left:0
      right:0
      bottom:.44rem
      .icon-img-content
        height:100%
        display:block
        margin: 0 auto
    .icon-desc
        position: absolute
        left: 0
        right: 0
        bottom: 0
        height: .44rem
        line-height: .44rem
        text-align: center
        color: $darkTextColor
        ellipsis()
</style>
