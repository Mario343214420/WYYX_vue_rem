<template>
  <div>
    <div class="newUserTop">新人专享礼</div>
    <div class="newUserBottom">
      <div class="left">
        <i>新人专享礼包</i>
        <img src="./images/1.png" alt="专享红包">
      </div>
      <div class="right">
        <div class="r-top">
          <div class="l-txt">
            <div>福利社</div>
            <div>今日特价</div>
          </div>
          <img class="r-img" src="./images/2.png" alt="福利社">
        </div>
        <div class="r-bottom">
          <div class="">
            <span>新人拼团</span>
            <span>1元起包邮</span>
          </div>
          <img src="./images/3.png" alt="新人拼团">
        </div>
      </div>
    </div>
  </div>
</template>

<script>
  export default {}
</script>

<style lang="stylus" rel="stylesheet/stylus" scoped>
  @import '../../../common/stylus/mixins.styl'
  .newUserTop
    height px2rem(90)
    line-height px2rem(90)
    font-size px2rem(35)
    text-align center
    &::before
      display inline-block
      content '—'
      margin-right 10px
    &::after
      display inline-block
      content '—'
      margin-left 10px

  .newUserBottom
    height px2rem(435)
    background-color: yellowgreen
    .left
      float left
      width 50%
      text-align center
      i
        height px2rem(80)
        line-height pe2rem(80)
        display block
        font-style normal
        font-size px2rem(35)
        text-align left
      img
        display inline-block

    .right
      float right
      width 50%
      .r-top

        height 50%
        .l-txt
          display inline-block
          width 40%
          div
            float left
            font-size px2rem(35)
        .r-img
          box-sizing border-box
          padding px2rem(15)
          display inline-block
          float right
          width 60%
      .r-bottom
        height 50%


</style>
