# POLARDB产品升级公告 {#concept_220869 .concept}

## 背景 {#section_5f3_ko2_8qh .section}

为了提供更稳定的服务和更好的性能，POLARDB将会在近期进行一次存储模块升级。

## 时间 {#section_k97_ejs_myy .section}

-   各地域升级时间（北京时间）如下：
    -   香港：2019.05.06 02:00:00 ~ 06:00:00
    -   北京：2019.05.08 02:00:00 ~ 06:00:00, 2019.05.10 02:00:00 ~ 06:00:00
    -   深圳：2019.05.10 02:00:00 ~ 06:00:00
    -   杭州：2019.05.14 02:00:00 ~ 06:00:00, 2019.05.16 02:00:00 ~ 06:00:00
    -   上海：2019.05.21 02:00:00 ~ 06:00:00
-   由于本次升级涉及底层存储集群，因此可能无法在您设置的可维护时间内进行升级，也不支持单独调整升级日期，而是统一安排在凌晨2:00 ~ 6:00，具体升级时间请您关注近期的短信提醒。

## 影响 {#section_0li_3zz_2gv .section}

-   会造成连接闪断或部分SQL无法响应（持续20~60秒），整个影响时间不超过60秒。
-   主地址和集群地址均会受到影响。

## 注意事项 {#section_2fq_p1s_4uh .section}

数据库SQL响应时间突增，可能会影响应用程序，请确保应用程序具备自动重连机制。

