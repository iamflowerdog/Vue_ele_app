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

      <div class="mask">
        <div class="mask-wrapper">
          <div class="mask-main">

            <h1 class="title">野外商店 (天辉上路)</h1>

            <div class="star-wrapper">
              <div class="stars star-48">
                <span class="star on"></span>
                <span class="star on"></span>
                <span class="star on"></span>
                <span class="star half"></span>
                <span class="star off"></span>
              </div>
            </div>

            <div class="info">
              <div class="line"></div>
              <div class="text">优惠信息</div>
              <div class="line"></div>
            </div>

            <ul class="list">
              <li class="item">
                <span class="icon decrease"></span>
                <span class="text">在线支付满10送2个小飞张</span>
              </li>
              <li class="item">
                <span class="icon discount"></span>
                <span class="text">VC无限橙果汁全场8折</span>
              </li>
              <li class="item">
                <span class="icon invoice"></span>
                <span class="text">单人精彩套餐</span>
              </li>
              <li class="item">
                <span class="icon guarantee"></span>
                <span class="text">该商家支持发票,请下单写好发票抬头</span>
              </li>
              <li class="item">
                <span class="icon special"></span>
                <span class="text">已加入“外卖保”计划,食品安全保障</span>
              </li>
            </ul>

            <div class="info">
              <div class="line"></div>
              <div class="text">商家公告</div>
              <div class="line"></div>
            </div>

            <div class="bulletin">
              <p class="text">
                粥品香坊其烹饪粥料的秘方源于中国千年古法，在融和现代制作工艺，由世界烹饪大师屈浩先生领衔研发。坚守纯天然、0添加的良心品质深得消费者青睐，发展至今成为粥类的引领品牌。是2008年奥运会和2013年园博会指定餐饮服务商。
              </p>
            </div>
          </div>
        </div>

        <div class="mask-footer">
          <span class="icon-close"></span>
        </div>
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

    .mask
      position fixed
      width 100%
      height 100%
      z-index 10
      left 0
      top 0
      background-color rgba(7,17,28,.8)
      .mask-wrapper
        min-height 100%
        .mask-main
          padding 64px 36px
          .title
            font-size 16px
            font-weight 700
            line-height 16px
            text-align center
          .star-wrapper
            margin 16px auto 28px auto
            background-color rgba(255,0,0,.2)
            .stars
              height 24px
              text-align center
              .star
                display inline-block
                background-repeat no-repeat
                background-position 0 0
              &.star-48
                .star
                  width 20px
                  height 19px
                  margin-right 15px
                  background-size 20px 19px
                  &.on
                    bg-image("../star/star48_on")
                  &.off
                    bg-image("../star/star48_off")
                  &.half
                    bg-image("../star/star48_half")
              &.star-36
                .star
                  width 15px
                  height 15px
                  margin-right 12px
                  background-size 15px 15px
                  &.on
                    bg-image("../star/star36_on")
                  &.off
                    bg-image("../star/star36_off")
                  &.half
                    bg-image("../star/star36_half")
              &.star-24
                .star
                  width 10px
                  height 10px
                  margin-right 8px
                  background-size 10px 10px
                  &.on
                    bg-image("../star/star24_on")
                  &.off
                    bg-image("../star/star24_off")
                  &.half
                    bg-image("../star/star24_half")

        .info
            display flex
            width 80%
            margin 0 auto
            .line
              flex 1
              background-color rgba(255,255,255,.2)
              height 1px
              position relative
              top 8px
            .text
              margin 0 12px
              font-size 14px
              font-weight 700
              line-height 14px

          .list
            padding 24px 12px 28px 12px
            background-color rgba(0,255,0,.2)
            .item
              margin-bottom 12px
              line-height 12px
              &:last-child
                margin-bottom 0
              .icon
                background-size 16px 16px
                background-repeat no-repeat
                width 16px
                height 16px
                display inline-block
                vertical-align top
                &.decrease
                  bg-image(decrease_2)
                &.discount
                  bg-image(discount_2)
                &.invoice
                  bg-image(invoice_2)
                &.guarantee
                  bg-image(guarantee_2)
                &.special
                  bg-image(special_2)
              .text
                font-size 12px
                font-weight 200
                line-height 12px


          .bulletin
            margin 24px 12px auto 12px
            .text
              font-size 12px
              font-weight 200
              line-height 24px
      .mask-footer
        background-color pink
        margin-top -64px
        text-align center
        font-size 32px
        line-height 32px


</style>
