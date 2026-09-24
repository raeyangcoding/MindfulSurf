<--
域名 www.bilibili.com
域名 space.bilibili.com
域名 message.bilibili.com
域名 search.bilibili.com
-->


@-moz-document domain("bilibili.com"),
domain("search.bilibili.com"),
domain("space.bilibili.com"),
domain("message.bilibili.com") {
    .right-entry .v-popover-wrap:nth-child(3) {
        /*         opacity: 0; */
        visibility: hidden;
    }
    .right-entry .v-popover-wrap:nth-child(4) {
        visibility: hidden;
    }
}