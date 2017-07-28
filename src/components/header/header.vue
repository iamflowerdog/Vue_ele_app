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
            <span class="icon decrease"></span>
            <span class="text">在线支付 满28送范冰冰</span>
          </div>
        </div>
      </div>
      <div class="bulletin-wrapper">

      </div>
    </div>
</template>

<script>
    export default {}
</script>

<style lang="stylus" rel="stylesheet/stylus">

  @import "../../common/stlyus/mixin.styl"

  .header
    color #ffffff
    background-color pink
    .content-wrapper
      padding  24px 12px 18px 24px
      font-size 0
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

</style>
