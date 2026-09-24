<--
域名 www.bilibili.com
域名 space.bilibili.com
域名 message.bilibili.com
域名 search.bilibili.com
-->


@-moz-document domain("www.bilibili.com"),
domain("space.bilibili.com"),
domain("message.bilibili.com"),
domain("search.bilibili.com") {
    /*  右上广告  */
    .video-page-special-card-small .card-box[data-v-2d115d3e] {
        display: none;
    }
    div.paybar_payBarImageWrap__Mh0Of{
        display: none;
    }
    /*  评论区上方广告  */
    .activity-m-v1,
    div.ad-floor-cover.b-img {
        display: none
    }
    /*  右下广告    */
    .video-card-ad-small,
    a.ad-report.ad-floor-exp.right-bottom-banner {
        display: none
    }

    /*  新出现的广告    */
    #slide_ad,
    .ad-report {
        display: none
    }
    /*  直播推荐  */
    .pop-live-small-mode {
        display: none
    }


    /*  header    */
    /*  header左列除了logo，全都隐藏   */
    .left-entry .v-popover-wrap:nth-child(n+2) {
        visibility: hidden;
    }
    /*  大会员button  */
/*     div.vip-wrap */
    .right-entry__item:nth-child(2){
        visibility: hidden;
    }
    
    /* 创作中心、投稿button     */
    .right-entry__item:nth-child(7),
    .right-entry__item:nth-child(8)
    {
        visibility: hidden;
    }
}