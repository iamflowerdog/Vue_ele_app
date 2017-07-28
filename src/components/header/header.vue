<template>
    <div class="header">
      <div class="content-wrapper">

        <div class="avatar">
          <img src="http://static.galileo.xiaojukeji.com/static/tms/seller_avatar_256px.jpg" width="64" height="64">
        </div>

        <div class="content">
          <div class="title">
            <span class="brand"></span>
            <span class="name">粥品香坊（回龙观）</span>
          </div>

          <div class="description">
            <span>蜂鸟专送/38分钟必达</span>
          </div>

          <div class="supports">
            <span class="icon discount"></span>
            <span class="text">在线支付 满28送范冰冰</span>
          </div>
        </div>

        <div class="supports-count">
          <span class="count">5个</span>
          <span class="icon-keyboard_arrow_right"></span>
        </div>

      </div>

      <div class="bulletin-wrapper">
        <span class="bulletin-title"></span>
        <span class="bulletin-text">
          粥品香坊其烹饪粥料的秘方源于中国千年古法，在融和现代制作工艺，由世界烹饪大师屈浩先生领衔研发。坚守纯天然、0添加的良心品质深得消费者青睐，发展至今成为粥类的引领品牌。是2008年奥运会和2013年园博会指定餐饮服务商。
        </span>
        <span class="icon-keyboard_arrow_right"></span>
      </div>

      <div class="background">
        <img src="http://static.galileo.xiaojukeji.com/static/tms/seller_avatar_256px.jpg"
          width="100%" height="100%">
      </div>
    </div>
</template>

<script>
    export default {}
</script>

<style lang="stylus" rel="stylesheet/stylus">

  @import "../../common/stlyus/mixin.styl"

  .header
    position relative
    color #ffffff
    background-color rgba(7,17,27,.5)
    .content-wrapper
      padding  24px 12px 18px 24px
      font-size 0
      position relative
      .avatar
        display inline-block
        vertical-align top
      .content
        display inline-block
        margin-left 16px
        .title
          margin 2px 0 8px 0
          .brand
            vertical-align top
            display inline-block
            width 30px
            height 18px
            bg-image(brand)
            background-size 30px 18px
            background-repeat no-repeat
          .name
            font-size 16px
            font-weight bold
            line-height 16px
            margin-left 6px


        .description
          font-size 12px
          font-weight 200
          line-height 12px

        .supports
          margin 10px 0 2px 0
          .icon
            vertical-align top
            display inline-block
            width 12px
            height 12px
            background-size 12px 12px
            background-repeat no-repeat
            &.decrease
              bg-image(decrease_1)
            &.discount
              bg-image(discount_1)
            &.guarantee
              bg-image(guarantee_1)
            &.invoice
              bg-image(invoice_1)
            &.special
              bg-image(special_1)
          .text
            margin-left 4px
            font-size 10px
            font-weight 200
            line-height 12px

      .supports-count
        position absolute
        bottom 15px
        right 12px
        height 10px
        line-height 10px
        padding 7px 8px
        border-radius 10px
        background-color: rgba(0,0,0,.2)
        .count
          font-size 10px
          font-weight 200
          line-height 12px
        .icon-keyboard_arrow_right
          font-size 10px
          font-weight 200
          line-height 12px


    .bulletin-wrapper
      position relative
      line-height 28px
      height 28px
      padding 0 26px 0 12px
      text-overflow ellipsis
      white-space nowrap
      overflow hidden
      background-color rgba(7,17,27,.2)
      .bulletin-title
        bg-image(bulletin)
        display inline-block
        width 22px
        height 12px
        background-size 22px 12px
        background-repeat no-repeat
      .bulletin-text
        vertical-align top
        line-height 28px
        font-size 10px
        font-weight 200
        margin-right 20px
      .icon-keyboard_arrow_right
        position absolute
        right 12px
        bottom 0
        font-size 10px
        line-height 28px
        font-weight 200


    .background
      position absolute
      width 100%
      height 100%
      top 0
      left 0
      z-index -1
      filter blur(10px)

</style>
