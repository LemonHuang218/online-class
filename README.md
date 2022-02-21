后端技术栈：SpringBoot + Mybatis + MD5加密 + JWT鉴权 + Guava缓存 + Jmeter压测；
前端技术栈：Vue2.6 + VueX + Axios + CUBE-UI；
开发后端视频轮播图，视频列表、用户登录、订单详情等接口，以及前端对应页面。通过JWT对用户登录进行鉴权，并对于热点接口，如视频轮播图列表，引入Guava缓存，QPS提升五倍。

后续改进方向：
1.引入redis分布式缓存
2.开发微信支付接口
