# Awesome-Selfhosted

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![](https://camo.githubusercontent.com/3d659054abd6ce21c0e47cf3b83a51bda69ca282/68747470733a2f2f64656d6f2e726f636b65742e636861742f696d616765732f6a6f696e2d636861742e737667)](https://chat.awesh.unknownplus.com/channel/awesome-selfhosted)

Selfhosting is the process of locally hosting and managing applications instead of renting from SaaS providers.

This is a list of [Free](https://en.wikipedia.org/wiki/Free_software) Software [network services](https://en.wikipedia.org/wiki/Network_service) and [web applications](https://en.wikipedia.org/wiki/Web_application) which can be hosted locally. Non-Free software is listed on the [Non-Free](non-free.md) page.

See [Contributing](.github/CONTRIBUTING.md).

--------------------

  - [Analytics](#analytics)
  - [Automation](#automation)
  - [Blogging Platforms](#blogging-platforms)
  - [Bookmarks & Link Sharing](#bookmarks--link-sharing)
  - [Calendar and Address Books](#calendar-and-address-books)
  - [Communication systems](#communication-systems)
    - [Custom](#custom)
    - [Email](#email)
      - [Complete solutions](#complete-solutions)
      - [Mail Transfer Agents](#mail-transfer-agents)
      - [Mail Delivery Agents](#mail-delivery-agents)
      - [Mailing lists and newsletters](#mailing-lists-and-newsletters)
      - [Webmail clients](#webmail-clients)
    - [IRC](#irc)
    - [SIP](#sip)
    - [IPBX](#ipbx)
    - [Social Networks and Forums](#social-networks-and-forums)
    - [XMPP](#xmpp)
      - [XMPP Servers](#xmpp-servers)
      - [XMPP Web Clients](#xmpp-web-clients)
  - [Conference Management](#conference-management)
  - [Content Management Systems (CMS)](#content-management-systems-cms)
    - [E-commerce](#e-commerce)
  - [DNS](#dns)
  - [Document Archiving](#document-archiving)
  - [Enterprise Resource Planning](#enterprise-resource-planning)
  - [Federated Identity/Authentication](#federated-identityauthentication)
  - [Feed Readers](#feed-readers)
  - [File Sharing and Synchronization](#file-sharing-and-synchronization)
      - [Distributed filesystems](#distributed-filesystems)
      - [File transfer/synchronization](#file-transfersynchronization)
      - [Peer-to-peer filesharing](#peer-to-peer-filesharing)
      - [Single-click/drag-n-drop upload](#single-clickdrag-n-drop-upload)
      - [Web based file managers](#web-based-file-managers)
  - [Games](#games)
  - [Gateways](#gateways)
  - [Groupware](#groupware)
  - [Human Resources Management (HRM)](#human-resources-management-hrm)
  - [Learning and Courses](#learning-and-courses)
  - [Maps & GPS](#maps--gps)
  - [Media Streaming](#media-streaming)
      - [Audio Streaming](#audio-streaming)
      - [Video Streaming](#video-streaming)
  - [Misc/Other](#miscother)
  - [Money, Budgeting and Management](#money-budgeting-and-management)
  - [Monitoring](#monitoring)
  - [Note-taking & Editors](#note-taking--editors)
  - [Office Suites](#office-suites)
  - [Password Managers](#password-managers)
  - [Pastebins](#pastebins)
  - [Personal Dashboards](#personal-dashboards)
  - [Photo and Video Galleries](#photo-and-video-galleries)
  - [Polls and Events](#polls-and-events)
  - [Proxy](#proxy)
  - [Read it Later Lists](#read-it-later-lists)
  - [Search Engines](#search-engines)
  - [Software Development](#software-development)
    - [Project Management](#project-management)
    - [Bug Trackers](#bug-trackers)
    - [IDE/Tools](#idetools)
    - [Continuous Integration](#continuous-integration)
    - [API Management](#api-management)
    - [Documentation Generators](#documentation-generators)
    - [Localization](#localization)
  - [Static site generators](#static-site-generators)
  - [Task management/To-do lists](#task-managementto-do-lists)
  - [Ticketing](#ticketing)
  - [URL Shorteners](#url-shorteners)
  - [VPN](#vpn)
  - [Web servers](#web-servers)
  - [Wikis](#wikis)
  - [Self-hosting Solutions](#self-hosting-solutions)
  - [List of Licenses](#list-of-licenses)
  - [External links](#external-links)
  - [Contributing](#contributing)
  - [License](#license)


-----------------------------------------------------------------------------

<!-- BEGIN SOFTWARE LIST -->

## Analytics 数据分析
For personal analytics/dashboards, see [Personal Dashboards](https://github.com/Kickball/awesome-selfhosted#personal-dashboards)

**[`^        back to top        ^`](#)**

_Web Analytics_

  * [AWStats](http://www.awstats.org/) - 产生 web, streaming, ftp or mail server 统计分析数据 ([Source Code](https://github.com/eldy/awstats)) `GPLv3` `Perl`
  * [Countly](https://count.ly) - 适时移动端和web分析，崩溃报告和推送消息平台. ([Source Code](https://github.com/countly)) `AGPLv3` `Javascript`
  * [Druid](http://druid.io/) - 分布式、面向列的实时分析数据存储([Source Code](https://github.com/druid-io/druid/)) `Apache` `Java`
  * [GoAccess](http://goaccess.io/) - 在终端上实时分析网络日志和交互式查看数据. ([Source Code](https://github.com/allinurl/goaccess)) `GPLv2` `C`
  * [Open Web Analytics](http://www.openwebanalytics.com/) - Google Analytics and Piwik alternative. ([Source Code](https://github.com/padams/Open-Web-Analytics/)) `GPLv2` `PHP`
  * [Piwik](https://piwik.org/) - 领先的开源分析平台，能带给你不仅是有力的分析能力. ([Source Code](https://github.com/piwik/)) `GPLv3` `PHP`
  * [Rakam](https://rakam.io/) - 自助分析平台允许你创建自己的数据分析服务。整合任意数据源(web, mobile, IoT etc.), 使用SQL分析数据和创建大盘。([Source Code](https://github.com/rakam-io/rakam)) `Apache` `Java`
  * [Serposcope](https://serposcope.serphacker.com/) - 是一个免费开源的网站排名跟踪器，能够监控在google上的排名，进行seo优化。([Source Code](https://github.com/serphacker/serposcope)) `MIT` `Java`
  * [Snowplow](http://snowplowanalytics.com/) - 保存你网站，移动应用，桌面应用和服务端系统的每一个事件，存储在你自己的数仓中，而且具有实时能力。([Source Code](https://github.com/snowplow/)) `Apache` `Scala`
  * [Suet](https://suet.co/) `⚠` - 详细的分析和报告Mailgun交易邮件([Source Code](https://github.com/kehers/suet)) `GPLv3` `Nodejs`

_Business Intelligence_ 商业智能

  * [Metabase](http://www.metabase.com/) - 简单的大盘和GUI查询工具，每晚发邮件和slack集成PostgreSQL, MySQL, Redshift and other DBs. ([Source Code](https://github.com/metabase/metabase)) `AGPLv3` `Clojure`
  * [Redash](http://redash.io) - 连接超过18种数据库 (SQL and "NoSQL"), 查询数据，虚拟化然后生成大盘，所有的东西都有url可以分享，集成slack和hipchat ([Demo](https://demo.redash.io), [Source Code](https://github.com/getredash/redash)) `BSD` `Python`
  * [Superset](http://superset.apache.org/) - 现代化，为企业准备的商业智能web应用. ([Source Code](https://github.com/apache/incubator-superset)) `Apache` `Python`


## Automation 自动化

**[`^        back to top        ^`](#)**

  * [Alltube](http://www.alltubedownload.net) - 一个提供[youtube-dl](https://github.com/rg3/youtube-dl)下载的web页面 [more than 100 websites](https://rg3.github.io/youtube-dl/supportedsites.html). ([Demo](http://www.alltubedownload.net), [Source Code](https://github.com/Rudloff/alltube)) `GPL` `PHP`
  * [AmIUnique](https://amiunique.org/) - 通过浏览器指纹工具，学习在互联网上如何识别你. ([Source Code](https://github.com/DIVERSIFY-project/amiunique)) `MIT` `Java`
  * [Beehive](https://github.com/muesli/beehive) - 一个灵活的事件代理系统，允许你创建自己的代理，通过事件和触发器来自动化执行任务。 `AGPLv3` `Go`
  * [CouchPotato](https://couchpota.to/) - 沙发土豆是一个自动化的电影视频库管理器，自动化搜索种子，下载和处理你想要的视频质量. ([Source Code](https://github.com/CouchPotato/CouchPotatoServer/)) `GPLv3` `Python`
  * [Episodes](https://github.com/guptachetan1997/Episodes) - `⚠` 用django自搭建电视剧集追踪和推荐器Self Hosted TV show Episode tracker and recommender built using django, bootstrap4. `MIT` `Python`
  * [FHEM](https://fhem.de/fhem.html) - 用于自动化家居常用任务，比如开关灯，加热，另外也可以用户记录事件，比如温度和耗电，你可以通过web和智能前端设备，telnet和tcp/ip来控制。 ([Source Code](https://svn.fhem.de/trac)) `GPLv3` `Perl`
  * [Gekko](https://gekko.wizb.it/) - 是一个比特币交易和回溯检验机器人用户支持大量的交易和加密货币([Source Code](https://github.com/askmike/gekko)) `MIT` `Nodejs`
  * [Headphones](https://github.com/rembo10/headphones) - python写的自动化音乐下载器，支持 SABnzbd, NZBget, Transmission, µTorrent, Deluge and Blackhole. `GPLv3` `Python`
  * [Healthchecks](https://healthchecks.io/) - cron的任务报警器([Source Code](https://github.com/healthchecks/healthchecks)) `BSD` `Python`
  * [Home Assistant](https://home-assistant.io/) - 开源的家居自动化平台. ([Demo](https://home-assistant.io/demo/), [Source Code](https://github.com/home-assistant/home-assistant)) `MIT` `Python`
  * [homebank-converter](https://github.com/Binnette/homebank-converter) - 一个web应用用于转换bankfile成兼容的homeback csv文件([Demo](http://binnette.github.io/homebank-converter/)) `AGPLv3` `HTML5`
  * [Huginn](https://github.com/cantino/huginn) - 以你的名义构建代理  `MIT` `Ruby`
  * [Http2pic](https://http2pic.haschek.at/) - 网站截图生成器，使用wkhtmlto，有不同的选项渲染网站 ([Source Code](https://github.com/chrisiaut/http2pic)) `Apache 2.0` `PHP/Javascript`
  * [Kibitzr](https://kibitzr.github.io) - 集成了很多工具的轻量级个人网站助理  ([Source Code](https://github.com/kibitzr/kibitzr/)) `MIT` `Python`
  * [Medusa](https://github.com/pymedusa/SickRage) - 自动化的电视节目视频库管理器，帮你关注你最爱的新剧集 `GPLv3` `Python`
  * [Node RED](http://nodered.org/) - 基于浏览器的流编辑器，帮你打通硬件设别，有api和线上服务创建IOT方案， ([Source Code](https://github.com/node-red/node-red)) `Apache` `Nodejs`
  * [openHAB](http://www.openhab.org) - 开源的家居自动化 ([Source Code](https://github.com/openhab/openhab)) `EPLv1` `Java`
  * [PolitePol](https://github.com/taroved/pol) - 任意网页的rss流创建器 ([Demo](http://politepol.com)) `MIT` `Python`
  * [Poffer](http://poffer.gabinaureche.com) `⚠` - 一个轻松分享你喜欢的内容的工具 ([Source Code](https://github.com/Zhouzi/Poffer)) `MIT` `Nodejs`
  * [pyLoad](https://pyload.net/) - 轻量级的，自定义的远程管理下载器，一键部署。 ([Source Code](https://github.com/pyload/pyload)) `GPLv3` `Python`
  * [Radarr](https://radarr.video/) - Radarr 是独立form自Sonarr的项目，重新加工用于下载电影 ([Source Code](https://github.com/Radarr/Radarr)) `GPLv3` `C#`
  * [RSS-Bridge](https://github.com/sebsauvage/rss-bridge) - rss-bridge用于产生atom feeds的工具。 `Public domain` `PHP`
  * [RSS Merger](https://github.com/taophp/rss-merger) - 合并多个rss feeds流到一个 `GPLv2` `PHP`
  * [SickRage](http://sickrage.github.io/) - SickRage是自动化的电视节目下载器。 ([Source Code](https://github.com/SickRage/SickRage/)) `GPLv3` `Python`
  * [Sonarr](https://sonarr.tv/) - 电视节目视频下载 ([Source Code](https://github.com/Sonarr/Sonarr)) `GPLv3` `C#`
  * [TriggerHappy](http://trigger-happy.eu/) - 类iFFFT的工具 ([Source Code](https://github.com/foxmask/django-th)) `BSD` `Python`
  * [WebUI-aria2](https://github.com/ziahamza/webui-aria2) - aria2的web端下载。 ([Demo](http://ziahamza.github.io/webui-aria2/)) `MIT` `HTML5`
  * [WTFDYUM](https://github.com/jchampemont/WTFDYUM) `⚠` - 在twiter上找到不再follow你的人。好邪恶 ([Demo](https://www.wtfdyu.me/), [Source Code](https://github.com/jchampemont/WTFDYUM)) `Apache` `Java`
  * [Zenbot 3](https://github.com/carlos8f/zenbot) - 轻量级，可扩展的，用于 Bitcoin, Ether, Litecoin等等的AI交易机器人 `MIT` `Node.js`


## Blogging Platforms 博客平台

**[`^        back to top        ^`](#)**

See also [Static Site Generators](#static-site-generators), [Content Management Systems](#content-management-systems-cms) and [WeblogMatrix](http://www.weblogmatrix.org/)

  * [Anchor CMS](https://anchorcms.com/) - Anchor是一款免费，轻量级，比子弹还快的，监控单博客系统，面向艺术的博文  ([Source Code](https://github.com/anchorcms/anchor-cms)) `GPLv3` `PHP`
  * [Antville](https://antville.org) - Antville开源免费，具有高性能和丰富功能([Source Code](https://github.com/antville/antville)) `Apache` `Javascript`
  * [Blogotext](http://lehollandaisvolant.net/blogotext/) - 简单博客平台，安装过程提供了无可比拟的简单和高性能 ([Source Code](https://github.com/timovn/blogotext)) `MIT` `PHP`
  * [Bludit](https://www.bludit.com/) `⚠` - 秒级构建网站博客，使用json存储博文 ([Demo](http://demo-bludit.rhcloud.com/), [Source Code](https://github.com/dignajar/bludit)) `MIT` `PHP`
  * [Chyrp](https://github.com/chyrp/chyrp) - 超赞的轻量级博客引擎。 `MIT` `PHP`
  * [Dotclear](http://dotclear.org/) - 管理你的blog ([Source Code](https://hg.dotclear.org/dotclear)) `GPLv2` `PHP`
  * [Formtools](https://formtools.org/) - 强有力的，灵活管理表单数据([Source Code](https://github.com/formtools)) `GPLv2` `PHP`
  * [Ghost](https://ghost.org/) -  一个博客平台 ([Source Code](https://github.com/TryGhost/Ghost)) `MIT` `Nodejs`
  * [Hexo](https://hexo.io/) -  nodejs写的快速简单有力的博客框架 ([Source Code](https://github.com/hexojs/hexo)) `MIT` `Nodejs`
  * [Hotglue](https://hotglue.me/) - 允许在网页上构建网站，用轻文本存储，提供了一个直观的ui. ([Demo](https://hotglue.me/demo/), [Source Code](https://github.com/k0a1a/hotglue2)) `GPLv3` `PHP`
  * [htmly](https://www.htmly.com/) - 无db的博客平台. ([Demo](https://www.htmly.com/demo/), [Source Code](https://github.com/danpros/htmly)) `GPLv2` `PHP`
  * [Known](https://withknown.com/) - 一个简单网站 ([Source Code](https://github.com/idno/idno)) `Apache` `PHP`
  * [Noddity](http://noddity.com/) - 它是一个博客，一个wiki，一个快速的cms. ([Source Code](https://github.com/TehShrike/noddity)) `WTFPL` `Nodejs`
  * [PluXml](http://www.pluxml.org/) - 基于XML博客平台([Source Code](https://github.com/pluxml/PluXml)) `GPL` `PHP`
  * [Postleaf](https://www.postleaf.org/) - 一个优美的博客平台([Source Code](https://github.com/Postleaf/postleaf)) `MIT` `Nodejs`
  * [Solo](http://b3log.org/) - java写的博客平台 ([Demo](http://88250.b3log.org/), [Source Code](https://github.com/b3log/solo)) `Apache` `Java`
  * [WordPress](https://wordpress.org/) - 这个无需多言. ([Source Code](https://github.com/WordPress/WordPress)) `GPLv2` `PHP`


## Bookmarks & Link Sharing 书签和链接分享

**[`^        back to top        ^`](#)**

  * [Bookie](https://github.com/bookieio/Bookie) - 替代delicious.com的书签管理器. `AGPLv3` `Python`
  * [dyu/bookmarks](https://github.com/dyu/bookmarks) - 单线程/进程的书签app，使用leveldb和uWebSockets.支持从Delicious和Chrome导入。([Demo](https://dyuproject.com/bookmarks/)) `Apache` `Java`
  * [Firefox Auth Server](https://docs.services.mozilla.com/howtos/run-fxa.html) - 实现了firefox账户核心的api。 ([Source Code](https://github.com/mozilla/fxa-auth-server/)) `MPLv2` `Nodejs`
   * [Firefox Content Server](https://docs.services.mozilla.com/howtos/run-fxa.html) - 静态服务用于账户注册，邮件确认等 ([Source Code](https://github.com/mozilla/fxa-content-server/)) `MPLv2` `Java`
   * [Firefox Sync Server](https://docs.services.mozilla.com/howtos/run-sync-1.5.html) - 同步 Firefox bookmarks, passwords, history, tabs, preferences. ([Source Code](https://github.com/mozilla-services/syncserver)) `MPLv2` `Python`
  * [golinks](https://github.com/prologic/golinks) - 用于创建智能书签 ([Demo](https://search.mills.io)) `MIT` `Go`
  * [Lobsters](https://lobste.rs) - 允许你自己的书签聚合网站. ([Source Code](https://github.com/jcs/lobsters)) `BSD` `Ruby`
  * [No Fuss Bookmarks](http://nofussbm.herokuapp.com/signup.html) - 简单存储书签 ([Source Code](https://github.com/mapio/nofussbm)) `GPLv3` `Python`
  * [Pinry](http://getpinry.com/) - 一个用户保存，打标签，分享图片视频网站的图片面板系统 ([Source Code](https://github.com/pinry/pinry)) `BSD` `Python`
  * [saveto](https://save.duyet.net/) - 书签之家 ([Source Code](https://github.com/saveto-co/saveto)) `MIT` `Nodejs`
  * [SemanticScuttle](http://semanticscuttle.sourceforge.net/) - 可以对书签打tag的工具。([Source Code](https://sourceforge.net/p/semanticscuttle/code/ci/master/tree/)) `GPLv2` `PHP`
  * [Shaarli](https://github.com/shaarli/Shaarli) - 个人书签和连接分享平台([Demo](https://demo.shaarli.org)) `Zlib` `PHP`
  * [unmark](https://github.com/plainmade/unmark) - todo app. `MIT` `PHP`

## Calendar and Address Books 日历和地址簿

**[`^        back to top        ^`](#)**

Some [Groupware](#groupware) solutions also feature calendar/address book editing and synchronization.

  * [AgenDAV](http://agendav.org/) - 多语言的日历支持。 ([Source Code](https://github.com/agendav/agendav)) `GPLv3` `PHP`
  * [Baïkal](http://baikal-server.com/) - 轻量级的日历和电话本服务器. ([Source Code](https://github.com/fruux/Baikal)) `GPLv3` `PHP`
  * [CalendarServer](http://trac.calendarserver.org/) - 标准兼容时间日历和电话本协议的服务. `Apache` `Python`
  * [calypso](http://keithp.com/calypso/) - 基于python CalDAV/CardDAV server. ([Source Code](https://keithp.com/git/calypso.git)) `GPLv3` `Python`
  * [DAViCal](http://www.davical.org/) - 日历分享服务 (CalDAV). ([Source Code](https://gitlab.com/davical-project/davical)) `MIT` `PHP`
  * [EteSync](https://www.etesync.com) - 安全的端到端加密的个人星辰信息，同步到安卓和桌面应用 ([Source Code](https://github.com/etesync/)) `AGPLv3` `Python/Django`
  * [Radicale](http://radicale.org/) - 简单日历和联系人服务 ([Source Code](https://github.com/Kozea/Radicale)) `GPLv3` `Python`
  * [sabre/dav](http://sabre.io/) - 开源CardDAV, CalDAV and WebDAV server. ([Source Code](https://github.com/fruux/sabre-dav)) `MIT` `PHP`
  * [InfCloud](https://www.inf-it.com/open-source/clients/infcloud/) - An open source CalDAV/CardDAV 客户端 ([Demo](https://www.inf-it.com/infcloud/), [Source Code](https://www.inf-it.com/InfCloud_0.13.1.zip)) `AGPLv3` `Javascript`


## Communication systems 通信系统

**[`^        back to top        ^`](#)**

### Custom

  * [Actor](https://actor.im/) - 快捷开源包含丰富移动和桌面客户端的消息平台([Demo](https://app.actor.im), [Source Code](https://github.com/actorapp/actor-platform)) `AGPLv3` `Scala`
  * [Broid](https://broid.ai) - Broid使用W3C标准，具有单模式多消息通道的丰富会话 ([Demo](https://www.broid.ai), [Source Code](https://github.com/broidHQ/integrations)) `AGPLv3` `Nodejs`
  * [Centrifugo](https://github.com/centrifugal/centrifugo) - 语言无关的消息服务(Websocket or SockJS) server. ([Demo](https://github.com/centrifugal/centrifugo#demo)) `MIT` `Go`
  * [Cherry](https://github.com/rafael-santiago/cherry) - 微小的消息服务 . `GPLv2` `Go`
  * [Freenet](https://freenetproject.org/index.html) - 匿名分享文件，浏览订阅自由网站，论坛闲聊 ([Source Code](https://github.com/freenet/fred)) `GPLv2` `Java`
  * [Friends](http://moose-team.github.io/friends/) - P2P chat . ([Source Code](https://github.com/moose-team/friends)) `MIT` `Nodejs`
  * [GNUnet](https://gnunet.org/) - 去中心化的自由软件框架 ([Source Code](https://gnunet.org/git/)) `GPLv3` `C`
  * [hack.chat](https://hack.chat/) - 微小的聊天应用 ([Source Code](https://github.com/AndrewBelt/hack.chat)) `GPLv3` `Nodejs`
  * [Hawkpost](https://hawkpost.co) - HawkPost是一个web app允许你创建独一无二的连接，你想把它分享给谁任何人，并不需要关心怎么加密的 ([Source Code](https://github.com/whitesmith/hawkpost)) `MIT` `Python`
  * [Hubl.in](https://hubl.in/) - WebRTC提供视频会议和多人协作编辑 ([Source Code](https://github.com/linagora/hublin)) `AGPLv3` `Nodejs`
  * [Jitsi Meet](https://jitsi.org/Projects/JitsiMeet) - Jitsi Meet是一个开源WEBRTC的js应用，你能用它提供高质，可扩展视频会议 ([Source Code](https://github.com/jitsi/jitsi-meet)) `MIT` `Javascript`
  * [Jitsi Video Bridge](https://jitsi.org/Projects/JitsiVideobridge) - 可以多用户视频沟通 ([Source Code](https://github.com/jitsi/jitsi-videobridge)) `Apache` `Java`
  * [Kandan](http://getkandan.com/) - Kandan是 HipChat的开源版本. ([Source Code](https://github.com/kandanapp/kandan)) `AGPLv3` `Ruby`
  * [KChat](https://github.com/php-kchat/kchat) - 聊天应用. `Apache` `PHP`
  * [Lets-Chat](http://sdelements.github.io/lets-chat/) - node写的聊天组件 ([Source Code](https://github.com/sdelements/lets-chat)) `MIT` `Nodejs`
  * [Live Helper Chat](http://livehelperchat.com/) - 聊天软件. ([Source Code](https://github.com/LiveHelperChat/livehelperchat)) `Apache` `PHP`
  * [Mattermost](http://www.mattermost.org/) - 开源。slack的替代，集成了 [Gitlab](https://about.gitlab.com/). ([Source Code](https://github.com/mattermost/platform)) `AGPLv3/Apache` `Go`
  * [MiAOU](https://dystroy.org/miaou/login) - 多房间持续聊天服务([Source Code](https://github.com/Canop/miaou)) `MIT` `Nodejs`
  * [Mibew](https://mibew.org) - 网站一对一的聊天助理 ([Demo](https://mibew.org/demo2), [Source Code](https://github.com/Mibew/mibew)) `Apache` `PHP`
  * [Mumble](http://wiki.mumble.info/wiki/Main_Page) - 低延迟高质量语音文字聊天应用 ([Source Code](https://github.com/mumble-voip/mumble)) `BSD` `C++`
    * [Mumblecop](https://bitbucket.org/Flandoo/mumblecop) - 语音流. `MIT` `Ruby`
  * [Niltalk](http://niltalk.com/) - 简单私密持久免费的多房间聊天应用 ([Source Code](https://github.com/knadh/niltalk)) `AGPLv3` `Go`
  * [Node-Chat](https://github.com/IgorAntun/node-chat) - 具有管理功能的聊天应用 `MIT` `Nodejs`
  * [Pushjet](https://pushjet.io/) - 一个消息推送服务，具有简单发送通知的功能 ([Source Code](https://github.com/Pushjet/Pushjet-Server-Api)) `BSD` `Python`
  * [Rallly](http://rallly.co) - Rallly具有协调调度的服务 ([Source Code](https://github.com/lukevella/Rallly)) `CCBYSA` `Nodejs`
  * [RetroShare](http://retroshare.org) - 安全去中心化的通信系统 提供去中心化的聊天，论坛，消息和文件传输([Source Code](https://github.com/RetroShare/RetroShare)) `GPLv2` `С++`
  * [Ring](https://ring.cx/) - 通用的通讯软件，尊重自由和用户隐私 ([Source Code](https://github.com/savoirfairelinux/ring-project)) `GPLv3` `C++`
  * [Rocket.Chat](https://rocket.chat/) - 类似Gitter.im or Slack.团队聊天软件 ([Source Code](https://github.com/RocketChat/Rocket.Chat)) `MIT` `Nodejs`
  * [Spectrum 2](http://spectrum.im/) - Spectrum开源即时传输，即使使用不用的IM网络也能一起聊天  ([Source Code](https://github.com/hanzz/spectrum2)) `GPLv3` `C++`
  * [Spreed](https://www.spreed.me/) - WebRTC音视频调用，会议服务，和web客户端  ([Source Code](https://github.com/strukturag/spreed-webrtc)) `AGPLv3` `Go`
  * [Synapse](http://matrix.org/docs/projects/server/synapse.html) - A server for [Matrix](https://matrix.org/), 开放标准对于去中心化持久通信([Source Code](https://github.com/matrix-org/synapse)) `Apache` `Python`
    * [Matrix Console Web](http://matrix.org/docs/projects/client/matrix-console.html) - A web client meant to be a showcase of Matrix capabilities, and reference implementation of the Matrix standard. ([Source Code](https://github.com/matrix-org/matrix-angular-sdk)) `Apache` `Javascript`
    * [RIOT](http://riot.im) - A glossy Matrix web client with an emphasis on performance and usability. ([Source Code](https://github.com/vector-im/riot-web)) `Apache` `Javascript`
  * [Syndie](https://www.syndie.de) - Syndie是一个运营分布式论坛的开源软件. `CC0` `Java`
  * [TextBelt](https://github.com/typpo/textbelt) `⚠` - 一个对人友好的短信API ，能够免费发短信. `MIT` `Javascript`
  * [Tox](https://tox.chat/) - 一个分布式的安全消息中心，能够处理音视频聊天 ([Source Code](https://github.com/irungentoo/toxcore)) `GPLv3` `C`
  * [Tuber](https://blog.trailofbits.com/2015/12/15/self-hosted-video-chat-with-tuber/) - p2p视频聊天 ([Source Code](https://github.com/trailofbits/tubertc)) `MIT` `Javascript`
  * [ZeroNet](https://zeronet.io/) `⚠` - Open, free, and uncensorable websites, using Bitcoin cryptography and BitTorrent network. ([Source Code](https://github.com/HelloZeroNet/ZeroNet)) `GNU` `Python`
  * [Zulip](https://zulip.org) - Zulip 有力的开源小组聊天应用 ([Source Code](https://github.com/zulip/zulip)) `Apache/Other` `Python`

### Email 邮件系统

**[`^        back to top        ^`](#)**

#### Complete solutions

_simple deployment of a mail server, e.g. for inexperienced or impatient admins._

  * [Citadel](http://www.citadel.org/) - Feature packed, easy, versatile, and powerful mail server, thanks to exclusive "rooms" based architecture. ([Source Code](http://code.citadel.org/?p=citadel.git;a=summary)) `GPLv3` `C`
  * [docker-mailserver](https://github.com/tomav/docker-mailserver) - A fullstack but simple mail server (smtp, imap, antispam, antivirus, etc.). Only configuration files, no SQL database. Keep it simple and versioned. Easy to deploy and upgrade. `MIT` `Docker`
  * [Inboxen](https://inboxen.org) - 提供无限的独立的inboxes ([Source Code](https://github.com/Inboxen/Inboxen)) `GPLv3` `Python`
  * [iRedMail](http://www.iredmail.org/) - 基于Postfix and Dovecot的全功能邮件服务 ([Source Code](https://bitbucket.org/zhb/iredmail/commits/)) `GPLv3` `Shell`
  * [Mailcow](https://mailcow.email/) - 基于Dovecot, Postfix和其他开源软件的邮件服务，提供了一个管理平台的webui ([Source Code](https://github.com/andryyy/mailcow)) `GPLv2` `PHP`
  * [Mailu](https://mailu.io/) - Mailu是一个简单的全功能邮件服务，有一系列的docker镜像 ([Demo](https://github.com/Mailu/Mailu/wiki/Demo-server), [Source Code](https://github.com/Mailu/Mailu)) `MIT` `Docker/Python`
  * [Mail-in-a-Box](https://mailinabox.email/) - Turns any Ubuntu server into a fully functional mail server with one command. ([Source Code](https://github.com/mail-in-a-box/mailinabox)) `CC0` `Shell`
  * [Modoboa](http://modoboa.org/en/) - Modoboa是一个现代，简单webui接口的管理平台  ([Source Code](https://github.com/tonioo/modoboa)) `MIT` `Python`
  * [Postal](https://github.com/atech/postal) - Postal是一个完全，全功能的邮件服务 `MIT` `Ruby`
  * [Qmailtoaster](http://www.qmailtoaster.com/) - 稳定，全功能，基于qmail的容易安装的邮件服务([Source Code](https://github.com/QMailToaster/)) `Multiple` `Linux`

#### Mail Transfer Agents 邮件传输代理

_MTAs / SMTP servers_

* [Courier MTA](http://www.courier-mta.org/) - 快速可扩展，企业级邮件服务，提供ESMTP, IMAP, POP3, webmail, mailing list,基本的基于wbe的日历和调度服务([Source Code](http://www.courier-mta.org/repo.html)) `GPLv3` `C`
* [Exim](https://www.exim.org/) - 剑桥大学开发的MTA ([Source Code](http://git.exim.org/exim.git)) `GPLv3` `C`
* [Haraka](http://haraka.github.io/) - 高性能可扩展的SMTP服务([Source Code](https://github.com/haraka/Haraka)) `MIT` `Javascript`
* [MailCatcher](http://mailcatcher.me/) - 部署简单的SMTP MTA网关，接收所有的邮件和展示web接口， 对于开发和调试很有帮助. ([Source Code](https://github.com/sj26/mailcatcher)) `MIT` `Ruby`
* [Maildrop](https://github.com/m242/maildrop) - 一次性邮件SMTP服务 ，也用于开发 `MIT` `Scala`
* [MailHog](https://github.com/mailhog/MailHog) - Small Golang executable which runs an SMTP MTA gateway that accepts all mail and displays in web interface. Useful for debugging or development. `MIT` `Go`
* [OpenSMTPD](https://opensmtpd.org/) - Secure SMTP server implementation from the OpenBSD project. ([Source Code](http://cvsweb.openbsd.org/cgi-bin/cvsweb/src/usr.sbin/smtpd/)) `ISC` `C`
* [Postfix](http://www.postfix.org/) - 快速，容易管理的，安全的sendmail替代 `IPL` `C`
* [Qmail](http://www.qmail.org/top.html) - 安全的Sendmail替代. ([Source Code](https://sources.debian.net/src/netqmail/1.06-5/)) `CC0` `C`
* [Sendmail](http://www.sendmail.com/sm/open_source/) - 无需多言 (MTA). `SENDMAIL` `C`
* [Slimta](http://slimta.org) - 基于python的邮件传输库([Source Code](https://github.com/slimta/python-slimta)) `MIT` `Python`

#### Mail Delivery Agents

_MDAs - IMAP/POP3 software_

* [Cyrus IMAP/POP3](http://cyrusimap.org/) - 用于运行在封闭的server中，正常用户不允许登录。 ([Source Code](https://github.com/cyrusimap/cyrus-imapd )) `BSD` `C`
* [Dovecot](http://www.dovecot.org/) - 主要考虑到安全写的一个IMAP and POP3 服务 ([Source Code](https://github.com/dovecot/core)) `MIT/LGPLv2` `C`
* [Piler](http://www.mailpiler.org/wiki/start) - 多功能的邮件归档方案([Source Code](https://bitbucket.org/jsuto/piler)) `GPLv3` `C`

#### Mailing lists and Newsletters

_Mailing lists servers and mass mailing software - one message to many recipients._

  * [Dada Mail](http://dadamailproject.com/) - 基于web的用于通知列表和讨论列表的管理系统 ([Source Code](https://github.com/justingit/dada-mail)) `GPLv2` `Perl`
  * [Mail For Good](https://github.com/freeCodeCamp/mail-for-good) `⚠` - 开源的邮件管理系统，不为盈利 `BSD` `Javascript`
  * [Mailman](https://www.gnu.org/software/mailman/) -  Gnu邮件列表server. `GPL` `Python`
  * [Mailtrain](https://mailtrain.org/) - 新闻应用([Source Code](https://github.com/andris9/mailtrain)) `GPLv3` `Nodejs`
  * [MailyHerald](http://mailyherald.org/) - 自部署的可替代Mailchimp的方案，能够方便集成到你的网站 ，帮你发送和管理应用邮件，支持邮件市场，管理每日通知流到用户 ([Source Code](https://github.com/Sology/maily_herald)) `LGPLv3` `Ruby`
  * [Mautic](https://www.mautic.org/) - 营销自动化软件 ([Source Code](https://github.com/mautic/mautic)) `GPLv3` `PHP`
  * [phpList](https://phplist.org) - 新闻和邮件市场，具有高级管理功能，包括订阅，弹性和插件 ([Source Code](https://github.com/phpList/)) `AGPLv3` `PHP`
  * [postal](https://github.com/atech/postal) - 全功能的开源邮件分发平台，包括收发邮件 `MIT` `Ruby`
  * [Schleuder](https://schleuder.nadir.org/) - 开启GPG功能的邮件列表管理器，具有重发功能 ([Source Code](https://0xacab.org/schleuder/schleuder/tree/master)) `GPLv3` `Ruby`
  * [Sympa](https://www.sympa.org/) - 邮件列表管理器 `GPLv2` `Perl`

#### Webmail clients 

  * [Cypht](http://cypht.org/index.html) - 邮件流管理器([Source Code](https://github.com/jasonmunro/hm3)) `GPLv2` `PHP`
  * [IMP](https://www.horde.org/apps/imp/) - webmail提供IMAP and POP3 accounts接入. ([Demo](http://demo.horde.org/), [Source Code](https://www.horde.org/download/imp)) `GPLv2` `PHP`
  * [Mailpile](https://www.mailpile.is/) - Webmail客户端具有搜索，过滤，加密等特性 ([Source Code](https://github.com/mailpile/Mailpile)) `AGPLv3` `Python`
  * [RainLoop](http://www.rainloop.net/) - 简单，现代，快速的web邮件，具有IMAP/SMTP 支持和多用户管理([Demo](http://demo.rainloop.net/), [Source Code](https://github.com/RainLoop/rainloop-webmail)). `AGPLv3` `PHP`
  * [Roundcube](https://roundcube.net) - 基于浏览器的邮件客户端([Source Code](https://github.com/roundcube/roundcubemail/)) `GPLv3` `PHP`
  * [SquirrelMail](http://squirrelmail.org) -另一个web邮件客户端. ([Source Code](https://sourceforge.net/p/squirrelmail/code/HEAD/tree/)) `GPLv2` `PHP`
  * [WebMail Lite](http://www.afterlogic.org/webmail-lite) . ([Source Code](https://github.com/afterlogic/webmail-lite)) `GPLv3` `PHP`

### IRC

**[`^        back to top        ^`](#)**

_[IRC](https://en.wikipedia.org/wiki/Internet_Relay_Chat) communication software_

  * [Convos](http://convos.by/) - 保持在线的IRC客户端. ([Demo](http://demo.convos.by), [Source Code](http://github.com/nordaaker/convos)) `ARTv2` `Perl`
  * [IRCAnywhere](http://ircanywhere.com/) - 开源替代IRCCloud的替代 ([Source Code](https://github.com/ircanywhere/ircanywhere)) `GPLv2` `Nodejs`
  * [Quassel IRC](http://quassel-irc.org/) - 分布式的IRC客户端 ([Source Code](https://github.com/quassel/quassel)) `GPLv2` `C++`
  * [Robust IRC](https://robustirc.net/) - RobustIRC没有网络分割，分布式，基于RobustSession protocol. ([Source Code](https://github.com/robustirc/robustirc)) `BSD` `Go`
  * [The Lounge](https://thelounge.github.io/) -  自部署的IRC client. ([Demo](https://demo.thelounge.chat/), [Source Code](https://github.com/thelounge/lounge)) `MIT` `Nodejs`
  * [Weechat](https://weechat.org/) - 轻量可扩展的 chat client. `GPLv3` `C`
  * [ZNC](http://wiki.znc.in/ZNC) - 高级IRC保镖. ([Source Code](https://github.com/znc/znc)) `Apache` `C++`

### SIP

**[`^        back to top        ^`](#)**

_[SIP](https://en.wikipedia.org/wiki/Session_Initiation_Protocol) telephony software_

  * [Asterisk](http://www.asterisk.org/) - 易用高级 IP PBX system, VoIP gateway and 会议服务. `GPLv2` `C`
  * [FreeSWITCH](https://freeswitch.org/) - 可扩展开源跨平台通信平台 ([Source Code](https://freeswitch.org/stash/projects/FS/repos/freeswitch/browse)) `MPLv2` `C`
  * [Kamailio](http://www.kamailio.org/w/) - 模块化的SIP server (registrar/proxy/router/etc). ([Source Code](https://github.com/kamailio/kamailio)) `GPLv2` `C`
  * [Ostel](https://dev.guardianproject.info/projects/ostel/wiki/Server_Documentation) - 安全的SIP基于ZRTP加密 `GPLv3` `Ruby`

### IPBX

**[`^        back to top        ^`](#)**

_[IPBX](https://en.wikipedia.org/wiki/IP_PBX) telephony software_

  * [Freepbx](http://www.freepbx.org) - 基于web的开源GUI，管理Asterisk. ([Source Code](http://git.freepbx.org/projects/FREEPBX)) `GPLv2` `PHP`
  * [FusionPBX](https://www.fusionpbx.com/) - 开源项目用于提供一个自定义和灵活的web接口，用于非常强大高扩展的多平台语音切换  ([Source Code](https://github.com/fusionpbx/fusionpbx)) `MPLv1.1` `PHP`
  * [Kazoo](http://2600hz.org/) - KAZOO开源，高扩展平台，用于提供载波级VOIP开关功能([Source Code](https://github.com/2600hz/KAZOO)) `MPLv1.1` `Erlang`

### Social Networks and Forums 社交网络和论坛

**[`^        back to top        ^`](#)**

  * [Abilian SBE](https://github.com/abilian/abilian-sbe) - Open Source Collaboration and Social Networking framework & platform. `LGPLv2` `Python`
  * [Anahita](https://www.getanahita.com/) - Open Source Social Networking Framework & Platform. ([Source Code](https://github.com/anahitasocial)) `GPLv3` `PHP`
  * [Bootcamp](http://trybootcamp.vitorfs.com) -企业级社交网络. ([Source Code](https://github.com/vitorfs/bootcamp)) `MIT` `Python`
  * [Buddycloud](http://buddycloud.com/) - Tools, libraries, services and a community to build user-to-user, group and social messaging into your app. Saves time. Scales up. Supports you. ([Source Code](https://github.com/buddycloud)) `Apache` `Java`
  * [BuddyPress](https://buddypress.org/about/) - A powerful plugin that takes your WordPress.org powered site beyond the blog with social-network features like user profiles, activity streams, user groups, and more. ([Source Code](https://buddypress.svn.wordpress.org/trunk/)) `GPLv2` `PHP`
  * [cartulary](https://github.com/daveajones/cartulary) - RSS reader, readability tool, article archiver, microblogger, social graph manager and reading list manager. `CDDL` `PHP`
  * [diaspora*](https://diasporafoundation.org/) - Distributed social networking server. ([Demo](https://podupti.me/go.php), [Source Code](https://github.com/diaspora/diaspora)) `AGPLv3` `Ruby`
  * [Discourse](http://www.discourse.org/) - 高级论坛和社区管理 . ([Demo](https://try.discourse.org/), [Source Code](https://github.com/discourse/discourse)) `GPLv2` `Ruby`
  * [dyu/comments](https://github.com/dyu/comments/) - A real-time, markdown-enabled comment engine powered by leveldb. ([Demo](https://dyu.github.io/comments/real-time/)) `Apache` `Java`
  * [Elgg](https://elgg.org/) - A powerful open source social networking engine. ([Source Code](https://github.com/Elgg/Elgg)) `GPLv2` `PHP`
  * [Flarum](http://flarum.org) - Delightfully simple forums. Flarum is the next-generation forum software that makes online discussion fun again. ([Source Code](https://github.com/flarum/flarum)) `MIT` `PHP`
  * [flaskbb](https://flaskbb.org/) - FlaskBB is forum software written in Python using the microframework Flask. You can easily create new topics, posts and send other users private messages. It also includes basic administration and moderation tools. ([Source Code](https://github.com/sh4nks/flaskbb)) `BSD` `Python`
  * [FluxBB](http://fluxbb.org/) - Fast, light, user-friendly forum software for your website. ([Source Code](https://github.com/fluxbb/fluxbb)) `GPLv2` `PHP`
  * [Friendica](http://friendica.com/) - Social Communication Server. ([Source Code](https://github.com/friendica/friendica)) `AGPLv3` `PHP`
  * [GNU social](https://gnu.io/social/) - Social communication software for both public and private communications. ([Source Code](https://git.gnu.io/gnu/gnu-social)) `AGPLv3` `PHP`
  * [Hubzilla](https://hubzilla.org) - Decentralized identity, privacy, publishing, sharing, cloud storage, and communications/social platform. ([Source Code](https://github.com/redmatrix/hubzilla)) `MIT` `PHP`
  * [HumHub](https://www.humhub.org/) - A flexible kit for private social networks. ([Source Code](https://github.com/humhub/humhub)) `AGPLv3` `PHP`
  * [Isso](http://posativ.org/isso/) - A lightweight commenting server written in Python and Javascript. It aims to be a drop-in replacement for Disqus. ([Source Code](https://github.com/posativ/isso)) `MIT` `Python`
  * [Jappix](https://jappix.com/) - Jappix is an open social platform, that let's you easily get or keep in touch with everyone. ([Source Code](https://github.com/jappix/jappix)) `AGPLv3` `PHP`
  * [Loomio](https://www.loomio.org/) - Loomio is a collaborative decision-making tool that makes it easy for anyone to participate in decisions which affect them. ([Source Code](https://github.com/loomio/loomio)) `AGPLv3` `Ruby`
  * [Mastodon](https://joinmastodon.org/) - Federated microblogging server, an alternative to GNU social. ([Source Code](https://github.com/tootsuite/mastodon)) `AGPLv3` `Ruby`
  * [MyBB](http://www.mybb.com/) - Free, extensible forum software package. ([Source Code](https://github.com/mybb/mybb)) `LGPLv3` `PHP`
  * [Newebe](http://newebe.org/) - A Distributed Social Network. ([Source Code](https://github.com/gelnior/newebe)) `AGPLv3` `Python`
  * [NodeBB](https://nodebb.org/) - Node.js based forum software built for the modern web. ([Source Code](https://github.com/NodeBB/NodeBB)) `GPLv3` `Nodejs`
  * [OSSN](https://www.opensource-socialnetwork.org/) - Open Source Social Network (OSSN) is a social networking software written in PHP. It allows you to make a social networking website and helps your members build social relationships, with people who share similar professional or personal interests. ([Source Code](https://github.com/opensource-socialnetwork/opensource-socialnetwork)) `GPLv2` `PHP`
  * [Oxwall](http://www.oxwall.org/) - Oxwall is used for a wide range of projects starting from family sites and custom social networks to collaboration tools and enterprise community solutions. ([Source Code](https://bitbucket.org/oxwall/public)) `CPALv1` `PHP`
  * [phpBB](https://www.phpbb.com/) - Flat-forum bulletin board software solution that can be used to stay in touch with a group of people or can power your entire website. ([Source Code](https://github.com/phpbb/phpbb)) `GPLv2` `PHP`
  * [PPnet](https://github.com/pixelpark/ppnet) - Create and host your own social network. `MIT` `Javascript`
  * [Pump.io](http://pump.io/) - Stream server that does most of what people really want from a social network. ([Source Code](https://github.com/e14n/pump.io)) `Apache` `Nodejs`
  * [Socialhome](https://socialhome.network) - Federated and decentralized profile builder and social network engine. ([Demo](https://socialhome.network/public/), [Source Code](https://github.com/jaywink/socialhome)) `AGPLv3` `Python`
  * [Symphony](https://hacpai.com/) - A modern community (forum/SNS/blog) platform written in Java. ([Source Code](https://github.com/b3log/symphony)) `GPLv3` `Java`
  * [Telescope](http://www.telescopeapp.org/) - An open-source social news app built with Meteor. ([Demo](http://demo.telescopeapp.org/), [Source Code](https://github.com/TelescopeJS/Telescope)) `MIT` `Nodejs`
  * [Tokumei](https://tokumei.co/) - Anonymous microblogging platform. ([Demo](https://demo.tokumei.co/), [Source Code](https://kfarwell.org/projects/tokumei/git/)) `ISC` `rc`
  * [twister](http://twister.net.co/) - Fully decentralized P2P microblogging platform leveraging  the free software implementations of Bitcoin and BitTorrent protocols. ([Source Code](https://github.com/miguelfreitas/twister-core)) `BSD/MIT` `C++`
  * [Vanilla Forums](https://vanillaforums.org/) - Simple and flexible forum software. ([Source Code](https://github.com/vanilla/vanilla)) `GPLv2` `PHP`

### XMPP

**[`^        back to top        ^`](#)**

_[Extensible Messaging and Presence Protocol](https://en.wikipedia.org/wiki/XMPP) software_

#### XMPP Servers 可扩展消息和存在协议

  * [ejabberd](https://www.ejabberd.im/) - XMPP instant messaging server. ([Source Code](https://github.com/processone/ejabberd)) `GPL` `Erlang`
  * [Kontalk](http://kontalk.org/) - Kontalk is an Open Source Messenger, similar to WhatsApp (app for android only currently), including end-to-end encryption, server is based on Tigase XMPP Server. ([Source Code](https://github.com/kontalk)) `GPLv3` `Java`
  * [Metronome IM](https://metronome.im/) - Fork of Prosody IM. ([Source Code](https://github.com/maranda/metronome/)) `MIT` `Lua`
  * [MongooseIM](https://www.erlang-solutions.com/products/mongooseim.html) - Mobile messaging platform with a focus on performance and scalability. ([Source Code](https://github.com/esl/MongooseIM)) `GPLv2` `Erlang`
  * [Openfire](http://www.igniterealtime.org/projects/openfire/) - Real time collaboration (RTC) server. ([Source Code](https://github.com/igniterealtime/Openfire)) `Apache` `Java`
  * [Prosody IM](http://prosody.im/) - Feature-rich and easy to configure XMPP server. ([Source Code](http://hg.prosody.im/)) `MIT` `Lua`
  * [Tigase](http://www.tigase.net/content/tigase-xmpp-server) - XMPP server implementation in Java. `GPLv3` `Java`

#### XMPP Web Clients

  * [Candy](http://candy-chat.github.io/candy/) - Multi user XMPP client written in Javascript. ([Source Code](https://github.com/candy-chat/candy)) `MIT` `Javascript`
  * [Converse.js](https://conversejs.org/) - A free and open-source XMPP chat client in your browser. ([Source Code](https://github.com/jcbrand/converse.js)) `MPLv2` `Javascript`
  * [JSXC](https://jsxc.org) - A Real-time XMPP web chat application with video calls, file transfer and encrypted communication. There are also versions for Nextcloud/Owncloud and SOGo. ([Source Code](https://github.com/jsxc/jsxc)) `MIT` `Javascript`
  * [Kaiwa](http://getkaiwa.com/) - Web based chat client in the style of common paid alternatives. ([Source Code](https://github.com/digicoop/kaiwa)) `MIT` `Nodejs`
  * [Movim](https://movim.eu/) - A modern, federated social network based on XMPP, with a fully featured group-chat, subscriptions and microblogging. ([Source Code](https://github.com/movim/movim)) `AGPLv3` `PHP`
  * [Salut à Toi](http://www.salut-a-toi.org/) - Multipurpose, multi frontend, libre and decentralised communication tool. ([Source Code](http://repos.goffi.org/sat)) `AGPLv3` `Python`
    * [Libervia](http://wiki.goffi.org/wiki/Libervia/en) - Web frontend from Salut à Toi. ([Source Code](http://repos.goffi.org/libervia)) `AGPLv3` `Python`


## Conference Management 会议管理

**[`^        back to top        ^`](#)**

  * [Conference Organizing Distribution (COD)](http://usecod.com/) - 创建会议和事件 ([Source Code](http://cgit.drupalcode.org/cod)) `GPL` `PHP`
  * [frab](https://frab.github.io/frab/) - 会议计划和管理 ([Source Code](https://github.com/frab/frab)) `MIT` `Ruby`
  * [Open Conference Systems (OCS)](https://pkp.sfu.ca/ocs/) - 发布工具([Demo](https://pkp.sfu.ca/ocs/ocs_demo/), [Source Code](https://github.com/pkp/ocs)) `GPL` `PHP`
  * [OpenCFP](https://github.com/opencfp/opencfp) - 会议沟通 `MIT` `PHP`
  * [OpenConferenceWare](http://openconferenceware.org/) - . ([Source Code](https://github.com/osbridge/openconferenceware)) `MIT` `Ruby`
  * [osem](http://osem.io/) - 量身定做的事件管理 conferences. ([Demo](http://demo.osem.io/), [Source Code](https://github.com/openSUSE/osem)) `MIT` `Ruby`


## Content Management Systems (CMS)内容管理系统

**[`^        back to top        ^`](#)**

CMS are a practical way to setup a website with many features. CMS often come with third party plugins, themes and functionality that is easy to add and customize to your needs. See also [Blogging Platforms](#blogging-platforms) and [Static Site Generators](#static-site-generators)

  * [APIQ CMS](https://www.apiq.io/) - Simple and powerful Ruby on Rails CMS for developers. ([Demo](http://demo.apiq.io/), [Source Code](https://github.com/apiqcms/kms)) `MIT` `Ruby`
  * [Apostrophe](http://apostrophecms.org/) - A node.js CMS with a focus on extensible in-context editing tools. ([Demo](http://demo.apostrophecms.org/), [Source Code](https://github.com/punkave/apostrophe)) `MIT` `Nodejs`
  * [Backdrop CMS](https://backdropcms.org/) - The comprehensive CMS for small to medium sized businesses and non-profits. ([Source Code](https://github.com/backdrop/backdrop)) `GPLv2` `PHP`
  * [Baun](https://bauncms.com/) - A modern, lightweight, extensible CMS for PHP. ([Source Code](https://github.com/BaunCMS/Baun)) `MIT` `PHP`
  * [BigTree CMS](https://www.bigtreecms.org/) - Straightforward, well documented, and capable written with PHP and MySQL. ([Source Code](https://github.com/bigtreecms/BigTree-CMS)) `LGPLv2` `PHP`
  * [Bolt CMS](https://bolt.cm/) - Open source Content Management Tool, which strives to be as simple and straightforward as possible. ([Demo](https://try.bolt.cm/), [Source Code](https://github.com/bolt/bolt)) `MIT` `PHP`
  * [CMS Made Simple](http://www.cmsmadesimple.org/) - Open source content management system, faster and easier management of website contents, scalable for small businesses to large corporations. ([Source Code](http://svn.cmsmadesimple.org/svn/cmsmadesimple/trunk/)) `GPL` `PHP`
  * [Concrete 5 CMS](http://www.concrete5.org/) - An open source content management system. ([Source Code](https://github.com/concrete5/concrete5)) `MIT` `PHP`
  * [CouchCMS](http://www.couchcms.com/) - Simple Open-Source CMS for designers. ([Source Code](https://github.com/CouchCMS/CouchCMS)) `CPALv1` `PHP`
  * [Directus](http://getdirectus.com/) - Directus is a powerful and intuitive headless CMS for managing SQL databases with custom architectures. Built around a robust and extensible API, this decoupled content management framework is perfect for websites, apps, or multi-client projects. ([Source Code](https://github.com/directus/directus)) `GPL` `PHP`
  * [Drupal](https://www.drupal.org/) - Advanced open source content management platform. ([Source Code](http://cgit.drupalcode.org/drupal)) `GPL` `PHP`
  * [eLabFTW](http://www.elabftw.net) - An online lab notebook for research labs. Store experiments, use a database to find reagents or protocols, use trusted timestamping to legally timestamp an experiment, export as pdf or zip archive, share with collaborators…. ([Demo](https://demo.elabftw.net), [Source Code](https://github.com/elabftw/elabftw)) `AGPLv3` `PHP`
  * [GetSimple CMS](http://get-simple.info/) - The Simplest Content Management System. Ever. ([Source Code](https://github.com/GetSimpleCMS/GetSimpleCMS)) `GPLv3` `PHP`
  * [ImpressPages CMS](https://www.impresspages.org/) - Easy code meets easy admin. ([Demo](https://www.impresspages.org/demo), [Source Code](https://github.com/impresspages/ImpressPages)) `GPLv3/MIT` `PHP`
  * [Joomla!](https://www.joomla.org/) - Advanced Content Management System (CMS). ([Source Code](http://joomlacode.org/gf/project/joomla/scmsvn/)) `GPL` `PHP`
  * [KeystoneJS](http://keystonejs.com/) - CMS & Web Application Platform. ([Demo](http://demo.keystonejs.com/), [Source Code](https://github.com/keystonejs/keystone)) `MIT` `Nodejs`
  * [MODX](http://modx.com/) - MODX is an advanced content management and publishing platform. The current version is called 'Revolution'. ([Source Code](https://github.com/modxcms/revolution)) `GPLv2` `PHP`
  * [Neos](https://www.neos.io) - Neos or TYPO3 Neos (for version 1) is a modern, open source CMS. ([Source Code](https://git.typo3.org/Packages/TYPO3.Neos.git)) `GPLv3` `PHP`
  * [Noosfero](http://noosfero.org/) - Noosfero is a web platform for social and solidarity economy networks with blog, e-Portfolios, CMS, RSS, thematic discussion, events agenda and collective intelligence for solidarity economy in the same system. ([Source Code](https://gitlab.com/noosfero/noosfero)) `AGPLv3` `Ruby`
  * [october](http://octobercms.com/) - Free, open-source, self-hosted CMS platform. ([Source Code](https://github.com/octobercms/october)) `MIT` `PHP`
  * [Omeka](http://omeka.org) - Create complex narratives and share rich collections, adhering to Dublin Core standards with Omeka on your server, designed for scholars, museums, libraries, archives, and enthusiasts. ([Demo](http://omeka.org/showcase/), [Source Code](https://github.com/omeka/Omeka)) `GPLv3` `PHP`
  * [Pagekit](https://pagekit.com/) - A new modern CMS to create and share. ([Source Code](https://github.com/pagekit/pagekit)) `MIT` `PHP`
  * [Pico](http://picocms.org/) - A stupidly simple, blazing fast, flat file CMS. ([Source Code](https://github.com/picocms/Pico)) `MIT` `PHP`
  * [Pimcore](https://www.pimcore.org/) - Multi-Channel Experience and Engagement Management Platform. ([Source Code](https://github.com/pimcore/pimcore)) `BSD` `PHP`
  * [Plone](https://plone.org/) - Powerful open-source CMS system. ([Source Code](https://github.com/plone)) `Zope` `Python`
  * [ProcessWire](https://processwire.com/) - ProcessWire is an open source content management system (CMS) and web application framework aimed at the needs of designers, developers and their clients. ([Source Code](https://github.com/ryancramerdesign/ProcessWire)) `MPLv2` `PHP`
  * [PropertyWebBuilder](http://propertywebbuilder.com) - The ultimate Ruby on Rails engine for creating real estate websites. ([Demo](https://propertywebbuilder.herokuapp.com), [Source Code](https://github.com/etewiah/property_web_builder)) `MIT` `Ruby`
  * [Publify](http://publify.co/) - A simple but full featured web publishing software. ([Source Code](https://github.com/publify/publify)) `MIT` `Ruby`
  * [REDAXO](https://www.redaxo.org) - A simple, flexible and useful content management system (documentation only available in German). ([Source Code](https://github.com/redaxo/redaxo)) `MIT` `PHP`
  * [Redaxscript](https://redaxscript.com) - Ultra lightweight CMS for MySQL, SQLite and PostgreSQL. ([Demo](https://demo.redaxscript.com/demo/login), [Source Code](https://github.com/redaxmedia/redaxscript)) `GPLv3` `PHP`
  * [Roadiz](https://www.roadiz.io/) -  Modern CMS based on a node system which can handle many types of services. ([Source Code](https://github.com/roadiz/roadiz/)) `MIT` `PHP`
  * [SilverStripe](https://www.silverstripe.org) - Easy to use CMS with powerful MVC framework underlying. ([Demo](http://demo.silverstripe.org/), [Source Code](https://github.com/silverstripe)) `BSD` `PHP`
  * [Sphido](http://www.sphido.org/) - A fast, lightweight, flat file CMS for PHP. ([Source Code](https://github.com/sphido/cms)) `MIT` `PHP`
  * [SPIP](http://www.spip.net/fr) - Publication system for the Internet aimed at collaborative work, multilingual environments, and simplicity of use for web authors. ([Source Code](https://core.spip.net/projects/spip/repository)) `GPLv2` `PHP`
  * [Subrion](http://www.subrion.org) - Subrion is a free open source content management system that allows you to build websites for any purpose. Yes, from blog to corporate mega portal. ([Demo](http://demos.subrion.com), [Source Code](https://github.com/intelliants/subrion)) `GPLv3` `PHP`
  * [Textpattern](http://textpattern.com/) - A flexible, elegant and easy-to-use CMS. ([Demo](http://textpattern.co/demo), [Source Code](https://github.com/textpattern/textpattern)) `GPLv2` `PHP`
  * [TYPO3](https://typo3.org/) - A powerful and advanced CMS with a large community. ([Source Code](https://github.com/TYPO3/TYPO3.CMS)) `GPLv2` `PHP`
  * [Umbraco](https://umbraco.com/) - The friendly CMS. Free and open source with an amazing community. ([Source Code](https://github.com/umbraco/Umbraco-CMS)) `MIT` `.NET`
  * [Wagtail](https://wagtail.io/) - A Django content management system focused on flexibility and user experience. ([Source Code](https://github.com/wagtail/wagtail)) `BSD` `Python`
  * [WonderCMS](http://www.wondercms.com) - WonderCMS is the smallest flat file CMS since 2008. ([Demo](https://www.wondercms.com/demo), [Source Code](https://github.com/robiso/wondercms)) `MIT` `PHP`
  * [WordPress](https://wordpress.org/) - The worlds most-used blogging and CMS engine. ([Source Code](https://github.com/WordPress/WordPress)) `GPLv2` `PHP`

_Recipe management_

  * [OpenEats](https://github.com/RyanNoelk/OpenEats) - A recipe management site that allows users to create, store, share and rate recipes, create grocery lists, and more. ([Demo](https://food.ryannoelk.com/)) `MIT` `Python`

### E-commerce 电子商务

  * [Attendize](https://www.attendize.com/) - 售票和事件管理系统. ([Demo](https://www.attendize.com/documentation.php#demo), [Source Code](https://github.com/attendize/attendize)) `AAL` `PHP`
  * [CoreShop](https://www.coreshop.org) - CoreShop是 Pimcore的电子商务插件. ([Source Code](https://github.com/coreshop/CoreShop)) `GPLv3` `PHP`
  * [Drupal Commerce](https://drupalcommerce.org) - 电子商务插件 ([Source Code](https://github.com/drupalcommerce/commerce)) `GPLv2` `PHP`
  * [Magento](https://magento.com/) - omnichannel首席供应商. ([Demo](https://magento.com/schedule-a-demo), [Source Code](https://github.com/magento/magento2)) `OSLv3` `PHP`
  * [Microweber](https://microweber.com/) - 在线商店. ([Demo](http://demo.microweber.org/), [Source Code](https://github.com/microweber/microweber)) `Apache` `PHP`
  * [OpenCart](https://www.opencart.com) -开源购物车系统. ([Source Code](https://github.com/opencart/opencart)) `GPLv3` `PHP`
  * [Open Classifieds](http://open-classifieds.com/) - 分类站点. ([Source Code](https://github.com/open-classifieds/openclassifieds2)) `GPL` `PHP`
  * [Open eShop](https://open-eshop.com/) - 售卖你的电子商品 ([Source Code](https://github.com/open-classifieds/open-eshop)) `GPL` `PHP`
  * [Osclass](https://osclass.org/) - 构建分类市场的一站式商店  ([Source Code](https://github.com/osclass/Osclass)) `Apache` `PHP`
  * [OXID eShop](http://oxidforge.org) - OXID eShop灵活开源的电子商务软件，具有广泛的功能, [Source Code](https://github.com/OXID-eSales/oxideshop_ce)) `GPLv3` `PHP`
  * [Open Food Network](https://openfoodnetwork.org/) - 食品商务网站 ([Source Code](https://github.com/openfoodfoundation/openfoodnetwork)) `AGPLv3` `Ruby`
  * [PrestaShop](https://www.prestashop.com/) - PrestaShop 可扩展的电子商务网站 ([Demo](http://demo.prestashop.com/), [Source Code](https://github.com/PrestaShop/PrestaShop)) `OSLv3` `PHP`
  * [Pretix](https://pretix.eu/) - 活动售票网站  ([Source Code](https://github.com/pretix)) `Apache` `Python`
  * [Saleor](http://getsaleor.com/) - 电子商务网站前端  ([Demo](https://demo.getsaleor.com/), [Source Code](https://github.com/mirumee/saleor)) `BSD` `Python`
  * [Shuup](https://www.shuup.com/) - 完全自定义的电子商务网站 . ([Demo](https://www.shuup.com/en/demo/), [Source Code](https://github.com/shuup/shuup)) `AGPLv3` `Python`
  * [Sylius](http://sylius.org/) - 电子商务全栈平台 ([Demo](http://sylius.org/demo), [Source Code](https://github.com/Sylius/Sylius)) `MIT` `PHP`
  * [Thelia](http://thelia.net/) - 灵活的商务网站 ([Demo](http://demo.thelia.net/), [Source Code](https://github.com/thelia/thelia)) `LGPL` `PHP`
  * [WooCommerce](https://www.woothemes.com/woocommerce/) - wp的电子商务网站. ([Source Code](https://github.com/woothemes/woocommerce)) `GPL` `PHP`


## DNS

**[`^        back to top        ^`](#)**

See https://github.com/n1trux/awesome-sysadmin#dns

  * [CoreDNS](https://coredns.io/) - 插件化的dns ([Source Code](https://github.com/coredns/coredns)) `Apache` `Go`
  * [nsupdate.info](https://www.nsupdate.info/) - 动态dns ([Demo](https://www.nsupdate.info/account/register/), [Source Code](https://github.com/nsupdate-info/nsupdate.info)) `BSD` `Python`
  * [SPF Toolbox](http://spftoolbox.charlesabarnes.com) - dns查询. ([Source Code](https://github.com/bulbajackel/SPFtoolbox)) `MIT` `PHP`

## Document Archiving 文件归档

**[`^        back to top        ^`](#)**

  * [CUPS](https://www.cups.org/) - 打印([Source Code](https://www.cups.org/software.php)) `GPLv2` `C`
  * [EdPaper](https://github.com/Edraens/EdPaper) - 用户管理. `MIT` `PHP`
  * [Paperless](https://github.com/danielquinn/paperless) - 扫描索引所有文档. `GPLv3` `Python`
  * [SANE Network Scanning](http://sane-project.org/) - 允许远端用户扫描. ([Source Code](http://www.sane-project.org/cvs.html)) `GPLv2` `C`


## Enterprise Resource Planning 企业资源计划

**[`^        back to top        ^`](#)**

* [ERPNext](https://erpnext.com) - . ([Demo](https://demo.erpnext.com), [Source Code](https://github.com/frappe/erpnext)) `GPLv3` `Python`
* [LedgerSMB](https://ledgersmb.org/) - 集成账户 ERP系统，对于小型的企业， ([Demo](https://demo.cloud.efficito.com/erp/1.5/login.pl), [Source Code](https://github.com/ledgersmb/LedgerSMB)) `GPLv2` `Perl`
* [Odoo](http://odoo.com) - Free open source ERP system. ([Demo](https://demo.odoo.com/), [Source Code](https://github.com/odoo/odoo)) `LGPLv3` `Python`
* [Tryton](http://www.tryton.org/) - Free open source business solution. ([Demo](http://www.tryton.org/download.html), [Source Code](https://hg.tryton.org/)) `GPLv3` `Python`

_Agriculture Resource Planning_

  * [farmOS](http://farmos.org/) - A web-based farm record keeping application. ([Source Code](https://github.com/farmOS/farmOS)) `GPLv2` `PHP`
  * [tania](https://github.com/Tanibox/tania/) - A PHP based, free, and open source farming management system. `Apache` `PHP`

## Federated Identity/Authentication

**[`^        back to top        ^`](#)**

See https://github.com/n1trux/awesome-sysadmin#identity-management


## Feed Readers 阅读器

**[`^        back to top        ^`](#)**

  * [CommaFeed](https://www.commafeed.com/) - 发源于Google Reader. ([Source Code](https://github.com/Athou/commafeed)) `Apache` `Java`
  * [Creaky Coot](http://bugs.derivoile.fr/Creaky-Coot/dashboard) - 响应式的RSS reader ([Source Code](https://github.com/piero-la-lune/Creaky-Coot)) `MIT` `PHP`
  * [Feedbin](https://feedbin.com/) -简单美好的 RSS reader. ([Source Code](https://github.com/feedbin/feedbin)) `MIT` `Ruby`
  * [FeedHQ](https://feedhq.org/) - 基于web的feed reader. ([Source Code](https://github.com/feedhq/feedhq)) `BSD` `Python`
  * [FreshRSS](http://freshrss.org/) - 自部署的RSS feed aggregator. ([Demo](http://demo.freshrss.org/i/), [Source Code](https://github.com/FreshRSS/FreshRSS), [Mobile app](https://github.com/Alkarex/EasyRSS)) `AGPLv3` `PHP`
  * [JARR](http://1pxsolidblack.pl/jarr-en.html) -  reader. ([Demo](https://jarr.info/login?next=%2F), [Source Code](https://github.com/jaesivsm/JARR)) `AGPLv3` `Python`
  * [Kriss Feed](http://tontof.net/kriss/feed/) - 简单智能的 feed reader. ([Demo](http://tontof.net/feed/), [Source Code](https://github.com/tontof/kriss_feed/)) `CC0` `PHP`
  * [Leed](http://leed.idleman.fr) - 轻量 RSS aggregator. ([Source Code](https://github.com/ldleman/Leed)) `AGPLv3` `PHP`
  * [Leselys](https://github.com/socketubs/leselys) - 优雅的 RSS reader. `AGPLv3` `Python`
  * [Lite-Reader](http://cubny.com/lite-reader/) - 简单 ([Source Code](https://github.com/cubny/lite-reader)) `BSD` `PHP`
  * [Moonmoon](http://moonmoon.org/) - 简单. ([Source Code](https://github.com/mauricesvay/moonmoon)) `BSD` `PHP`
  * [Miniflux](https://miniflux.net/) - 开源新闻reader. ([Source Code](https://github.com/miniflux/miniflux)) `AGPLv3` `PHP`
  * [RSSPBRRY](http://jasoncomely.com/rss-tastemaker/) - new. ([Source Code](https://github.com/rsspbrry/rsspbrry)) `AGPLv3` `PHP`
  * [NewsBlur](http://www.newsblur.com/) - NewsBlur is a personal news reader that brings people together to talk about the world. A new sound of an old instrument. ([Source Code](https://github.com/samuelclay/NewsBlur)) `MIT` `Python`
  * [Nunux Reader](http://reader.nunux.org/) - A simple, fast and reactive RSS reader. ([Source Code](https://github.com/ncarlier/nunux-reader)) `GPLv3` `Nodejs`
  * [Reader-Self](http://readerself.com/) - Self-hosted rss reader (php / mysql or sqlite) - Google Reader alternative. ([Source Code](https://github.com/readerself/readerself)) `GPLv3` `PHP`
  * [RSS2EMail](http://www.allthingsrss.com/rss2email/) - Fetches RSS/Atom-feeds and pushes new Content to any email-receiver, supports OPML. ([Source Code](https://github.com/wking/rss2email)) `GPLv2` `Python`
  * [RSS Monster](https://github.com/pietheinstrengholt/rssmonster) - RSS Monster is an easy to use web-based RSS aggregator and reader compatible with the Fever API, created as an alternative for Google Reader. `MIT` `PHP`
  * [Screaming Liquid Tiger](https://github.com/herrbischoff/screaming-liquid-tiger) - Simple script to automatically generate valid RSS and Atom feeds from a list of media files in the same folder. `MIT` `PHP`
  * [Selfoss](http://selfoss.aditu.de/) - The new multipurpose rss reader, live stream, mashup, aggregation web application. ([Source Code](https://github.com/SSilence/selfoss)) `AGPLv3` `PHP`
  * [Sismics Reader](https://github.com/sismics/reader) - Free and open source feeds reader, including all major Google Reader features. `GPLv2` `Java`
  * [Stringer](https://github.com/swanson/stringer) - A work-in-progress self-hosted, anti-social RSS reader. `MIT` `Ruby`
  * [Temboz](https://github.com/fazalmajid/temboz) - A two-column feed reader emphasizing filtering capabilities to manage information overload. `MIT` `Python`
  * [Tiny Tiny RSS](https://tt-rss.org/gitlab/fox/tt-rss) - Open source web-based news feed (RSS/Atom) reader and aggregator. ([Demo](http://framanews.org/)) `GPLv3` `PHP`
    * [gritttt-rss](http://gritttt-rss.nicolashoening.de/) - More features for Tiny Tiny RSS. ([Source Code](https://github.com/nhoening/gritttt-rss)) `BSD` `Python`
    * [ttrss-mobile](https://github.com/mboinet/ttrss-mobile) - A mobile webapp for Tiny Tiny RSS. `AGPLv3` `Javascript`
    * [ttrss-reader](https://github.com/kucrut/ttrss-reader) - Light and responsive client for TTRSS. `GPLv2` `Javascript`
  * [Winds](https://github.com/GetStream/Winds) `⚠` - An open source & beautiful RSS reader built using React/Redux/Sails/Node and Stream. It showcases personalized feeds powered by the Stream API. ([Demo](https://winds.getstream.io/)) `BSD` `Nodejs`


## File Sharing and Synchronization 文件分享和同步

**[`^        back to top        ^`](#)**

Some [Groupware](#groupware) solutions also feature file sharing and synchronization.

#### Distributed filesystems 分布式文件系统

**[`^        back to top        ^`](#)**

See https://github.com/n1trux/awesome-sysadmin#distributed-filesystems

#### File transfer/synchronization

  * [Git Annex](http://git-annex.branchable.com) - 文件同步 ([Source Code](https://github.com/joeyh/git-annex)) `GPLv3` `Haskell`
  * [Kinto](https://kinto.readthedocs.org) - 基于json的存储同步 ([Source Code](https://github.com/Kinto)) `Apache` `Python`
  * [Nextcloud](https://nextcloud.com/) - 分享文件 & [more](https://apps.nextcloud.com/) from any device, on your terms. ([Demo](https://demo.nextcloud.com/), [Source Code](https://github.com/nextcloud/server)) `AGPLv3` `PHP`
  * [OpenSSH/SFTP](http://www.openssh.com/) - Secure File Transfer Program. ([Source Code](http://cvsweb.openbsd.org/cgi-bin/cvsweb/src/usr.bin/ssh)) `BSD` `C`
  * [ownCloud](https://owncloud.org/) - All-in-one solution for saving, synchronizing, viewing, editing and sharing files, calendars, address books and more. ([Source Code](https://github.com/owncloud/core)) `AGPLv3` `PHP`
  * [Pydio](https://pydio.com/) - Turn any web server into a powerful file management system and an alternative to mainstream cloud storage providers. ([Source Code](https://github.com/pydio/pydio-core)) `AGPLv3` `PHP`
  * [Samba](https://www.samba.org/) - Samba is the standard Windows interoperability suite of programs for Linux and Unix. It provides secure, stable and fast file and print services for all clients using the SMB/CIFS protocol. ([Source Code](https://git.samba.org/samba.git/)) `GPLv3` `C`
  * [Seafile](https://www.seafile.com/en/home/) - File hosting and sharing solution primary for teams and organizations. ([Demo](https://seacloud.cc/demo), [Source Code](https://github.com/haiwen/seafile)) `GPLv2` `C`
  * [SparkleShare](http://sparkleshare.org/) - Self hosted, instant, secure file sync. ([Source Code](https://github.com/hbons/SparkleShare)) `GPLv3` `C#`
  * [Syncany](https://www.syncany.org/) - Secure file sync software for arbitrary storage backends - An open-source cloud storage and filesharing application. Securely synchronize your files to any kind of storage. `GPLv3` `Java`
  * [Syncthing](https://syncthing.net/) - Syncthing is an open source peer-to-peer file synchronisation tool. ([Source Code](https://github.com/syncthing/syncthing)) `MPLv2` `Go`
  * [Unison](https://www.cis.upenn.edu/~bcpierce/unison/) - Unison is a file-synchronization tool for OSX, Unix, and Windows. `GPLv3` `OCaml`
  * [Z-Push](http://z-push.org/) - An implementation of Microsoft’s [ActiveSync](https://en.wikipedia.org/wiki/ActiveSync) protocol. ([Source Code](https://stash.z-hub.io/projects/ZP/repos/z-push)) `AGPLv3` `PHP`

#### Peer-to-peer filesharing p2p分享

  * [bittorrent-tracker](https://webtorrent.io/) - Simple, robust, BitTorrent tracker (client & server) implementation. ([Source Code](https://github.com/feross/bittorrent-tracker)) `MIT` `Nodejs`
  * [cloud-torrent](https://github.com/jpillora/cloud-torrent) - A torrent Web Client with HTTP retrievable or streamable downloaded files. `AGPLv3` `Go`
  * [Dat Project](https://datproject.org) - Powerful decentralized file sharing applications built from a large ecosystem of modules. ([Source Code](https://github.com/datproject)) `MIT` `Nodejs`
  * [FilePizza](http://file.pizza/) - Peer-to-peer file transfers in your browser. ([Source Code](https://github.com/kern/filepizza)) `BSD` `Nodejs`
  * [instant.io](https://github.com/feross/instant.io) - Streaming file transfer over WebTorrent. ([Demo](https://instant.io)) `MIT` `Nodejs`
  * [Magnetico](https://github.com/boramalper/magnetico) - Magnetico is the first autonomous (self-hosted) BitTorrent DHT search engine suite that is designed for end-users. `APGLv3` `Python`
  * [Magnetissimo](https://github.com/sergiotapia/magnetissimo) - Search engine that indexes all popular torrent sites. `MIT` `Elixir`
  * [Opentracker](http://erdgeist.org/arts/software/opentracker/) - Open and free bittorrent tracker. It aims for minimal resource usage and is intended to run at your wlan router. ([Source Code](http://erdgeist.org/gitweb/opentracker/)) `Beerware` `C`
  * [peerflix-server](https://github.com/asapach/peerflix-server) - Downloads torrent files and provides a direct link download or a direct link stream. `MIT` `Nodejs`
  * [rartracker](https://github.com/swetorrentking/rartracker) - Complete private bittorrent tracker. `WTFPL` `PHP`
  * [Reep](https://reep.io) - In-browser peer-to-peer file transfer and streaming made easy. ([Source Code](https://github.com/KodeKraftwerk/reepio)) `GPLv2` `Nodejs`
  * [Transmission](https://transmissionbt.com/) - 比特文件下载器. ([Source Code](https://github.com/transmission/transmission)) `GPLv3` `C`

#### Single-click/drag-n-drop upload 一键上传分享

  * [BoZoN](https://github.com/broncowdd/BoZoN) - Minimalist Drag & drop file sharing app. `AGPLv3` `PHP`
  * [Coquelicot](https://coquelicot.potager.org/) - Coquelicot is a “one-click” file sharing web application with a focus on protecting users’ privacy. ([Source Code](https://coquelicot.potager.org/gitweb/?p=coquelicot.git)) `AGPLv3` `Ruby`
  * [droppy](https://github.com/silverwind/droppy) - droppy is a self-hosted cloud server with an interface similar to desktop file managers and has capabilities to edit files on-the-fly as well as view and playback media directly in the browser. ([Demo](http://droppy.silverwind.io/)) `BSD` `Nodejs`
  * [FileShelter](https://github.com/epoupon/fileshelter) - FileShelter is a self-hosted software that allows you to easily share files over the Internet. ([Demo](http://fileshelter.suroot.com/)) `GPLv3` `C++`
  * [Files Sharing](https://github.com/axeloz/filesharing) - Open Source and self-hosted files sharing application based on unique and temporary links. `GPLv3` `PHP`
  * [img.bi](https://github.com/imgbi/img.bi) - 图片分享 `GPLv3` `Nodejs`
  * [ipfs.pics](https://github.com/ipfspics/server) - ipfs.pics is a o distributed image hosting website. `AGPLv3` `PHP`
  * [Jirafeau](https://gitlab.com/mojo42/Jirafeau) - 上传文件，生成一个唯一的链接 ([Demo](http://jirafeau.net/)) `AGPLv3` `PHP`
  * [linx](https://github.com/andreimarcu/linx-server) - 文件分享 ([Demo](https://linx.li/)) `GPLv3` `Go`
  * [lufi](https://git.framasoft.org/luc/lufi) - Let's Upload that FIle, client-side encrypted. ([Demo](https://demo.lufi.io), [Source Code](https://git.framasoft.org/luc/lufi/tree/master)) `AGPLv3` `Perl`
  * [lutim](https://github.com/ldidry/lutim) - Let's Upload That Image. `AGPLv3` `Perl`
  * [Minio](https://minio.io/) - 存储文件为对象. ([Source Code](https://github.com/minio/minio)) `Apache` `Go`
  * [Nimbus](https://github.com/ethanal/nimbus) - 一键文件分享 OS X. `MIT` `Python`
  * [OnionShare](https://github.com/micahflee/onionshare) - Securely and anonymously share a file of any size. `GPLv2` `Python`
  * [PictShare](https://www.pictshare.net/) - PictShare is a multi lingual, open source image hosting service with a simple resizing and upload API. ([Demo](https://www.pictshare.net/), [Source Code](https://github.com/chrisiaut/pictshare)) `Apache` `PHP`
  * [Plik](https://github.com/root-gg/plik) - 友好的临时文件上传系统 ([Demo](https://plik.root.gg/)) `MIT` `Go`
  * [Pomf](https://github.com/Pomf/Pomf) - Simple file uploading and sharing, source for the now shut down site Pomf.se. `MIT` `PHP`
  * [ProjectSend](http://www.projectsend.org/) - Upload files and assign them to specific clients you create. Give access to those files to your clients. ([Source Code](https://github.com/ignacionelson/ProjectSend)) `GPLv2` `PHP`
  * [PsiTransfer](https://github.com/psi-4ward/psitransfer) - Simple open source self-hosted file sharing solution with robust up-/download-resume and password protection. ([Demo](https://transfer.psi.cx/)) `BSD` `Nodejs`
  * [Sharry](https://github.com/eikek/sharry) - Share files easily over the internet between authenticated and anonymous users (both ways) with resumable up- and downloads. ([Demo](https://sharrydemo.eknet.org)) `GPLv3` `Scala/Java`
  * [Uguu](https://uguu.se/) - Stores files and deletes after X amount of time. ([Source Code](https://github.com/nokonoko/uguu)) `MIT` `PHP`
  * [Up1](https://github.com/Upload/Up1) - A Client-side Encrypted Image Host. `MIT` `Nodejs`
  * [uPste](https://u.pste.pw) - A private file hosting application with an emphasis on serving technology communities. ([Source Code](https://github.com/TheReverend403/uPste)) `AGPLv3` `PHP`
  * [YouTransfer](http://www.youtransfer.io) - 文件上传分享，1000+star ([Demo](http://demo.youtransfer.io/), [Source Code](https://github.com/remie/YouTransfer)) `Apache` `Nodejs`

_Command-line file upload_

  * [Beauties](https://github.com/dsx/beauties) - Minimalist file sharing written in Go, to be used primarily from Unix shell (e.g. with curl). Can be built as a Debian package for easy install. `MIT` `Go`
  * [transfer.sh](https://transfer.sh) - Easy file sharing from the command line. ([Source Code](https://github.com/dutchcoders/transfer.sh)) `MIT` `Go`

#### Web based file managers基于web的文件管理

  * [Apaxy](http://adamwhitcroft.com/apaxy/) - Theme built to enhance the experience of browsing web directories, using the mod_autoindex Apache module and some CSS to override the default style of a directory listing. ([Source Code](https://github.com/AdamWhitcroft/Apaxy)) `Unlicense` `HTML`
  * [DirectoryLister](http://www.directorylister.com/) - A simple PHP based directory lister that lists a directory and all it's sub-directories and allows you to navigate there within. ([Source Code](https://github.com/DirectoryLister/DirectoryLister)) `MIT` `PHP`
  * [Encode Explorer](http://encode-explorer.siineiolekala.net/) - Encode Explorer is a single page file browser, it is simple and functional. ([Demo](http://encode-explorer.siineiolekala.net/explorer/index.php), [Source Code](https://github.com/marekrei/encode-explorer)) `MIT` `PHP`
  * [explorer](https://github.com/soyuka/explorer) - Highly-configurable directory listing made with nodejs. ([Source Code](https://github.com/soyuka/explorer)) `MIT` `Nodejs`
  * [eXtplorer](https://extplorer.net/) - A PHP and Javascript based File Manager. ([Source Code](https://extplorer.net/projects/extplorer/repository)) `MPLv1.1/GPLv2` `PHP`
  * [filemanager](https://henriquedias.com/filemanager/) - Web File Manager which can be used as a middleware or standalone app. ([Source Code](https://github.com/hacdias/filemanager)) `Apache` `Go/VueJS`
  * [goBrowser](https://github.com/xataz/gobrowser) - Simple http file browser. ([Source Code](https://github.com/xataz/gobrowser)) `GPLv3` `Go`
  * [h5ai](https://larsjung.de/h5ai/) - Modern file indexer for HTTP web servers with focus on your files. Directories are displayed in a appealing way and browsing them is enhanced by different views, a breadcrumb and a tree overview. ([Demo](https://larsjung.de/h5ai/demo/), [Source Code](https://github.com/lrsjng/h5ai)) `MIT` `PHP`
  * [IFM](https://github.com/misterunknown/ifm/) - A single script file manager. `MIT` `PHP`
  * [Monsta FTP](http://www.monstaftp.com/) - Open source PHP/Ajax cloudware that puts FTP file management right in your browser, anywhere, any time. ([Demo](http://mftp.live/), [Source Code](https://github.com/MonstaApps/Monsta-FTP)) `GPLv3` `PHP`
  * [ResourceSpace](http://www.resourcespace.org) - ResourceSpace open source digital asset management software is the simple, fast, & free way to organise your digital assets. ([Demo](http://www.resourcespace.org/trial), [Source Code](http://www.resourcespace.org/svn)) `BSD/Other` `PHP`
  * [Sprut.io](https://sprut.io) - 2 panel file manager with drag and drop features, code editor, text search, hotkeys. ([Demo](https://demo.sprut.io:9443), [Source Code](https://github.com/LTD-Beget/sprutio)) `GPLv3` `Python`
  * [Surfer](https://github.com/nebulade/surfer) - Simple static file server with webui to manage files. `MIT` `Nodejs`
  * [TagSpaces](https://www.tagspaces.org/) - TagSpaces is an offline, cross-platform file manager and organiser that also can function as a note taking app. The WebDAV version of the application can be installed on top of a WebDAV servers such as Nextcloud or ownCloud. ([Demo](http://demo.tagspaces.org), [Source Code](https://github.com/tagspaces/tagspaces)) `AGPLv3` `Javascript`

## Games

**[`^        back to top        ^`](#)**

  * [0hh1](https://github.com/Q42/0hh1) - 可爱的小游戏 game by Q42. ([Demo](http://0hh1.com/)) `MIT` `HTML5`
  * [A Dark Room](https://github.com/doublespeakgames/adarkroom) - A minimalist text adventure game for your browser. ([Demo](http://adarkroom.doublespeakgames.com/)) `MPLv2` `HTML5`
  * [Agar.IO Clone](https://github.com/huytd/agar.io-clone) - Agar.io clone written with Socket.IO and HTML5 canvas. `MIT` `Nodejs`
  * [battlecraft](https://github.com/jbreindel/battlecraft) - A fully distributed multiplayer browser game. ([Demo](http://battlecraft.online)) `Apache` `Erlang`
  * [Clumsy Bird](https://github.com/ellisonleao/clumsy-bird) - A MelonJS port of the famous Flappy Bird Game. ([Demo](http://www.ellison.rocks/clumsy-bird/)) `MIT` `Nodejs`
  * [elevatorsaga](http://play.elevatorsaga.com/) - The elevator programming game. ([Source Code](https://github.com/magwo/elevatorsaga)) `MIT` `Javascript`
  * [Hextris](https://github.com/Hextris/hextris) - Fast paced HTML5 puzzle game inspired by Tetris. ([Demo](http://hextris.io/)) `GPLv3` `HTML5`
  * [Posio](https://github.com/abrenaut/posio/) - A geography multiplayer game. ([Demo](https://posio.abrenaut.com/)) `MIT` `Python`
  * [SourceBans++](https://sbpp.github.io) - Admin, ban, and communication management system for games running on the Source engine. ([Source Code](https://github.com/sbpp/sourcebans-pp)) `CCBYSA` `PHP`
  * [Spyfall](https://github.com/mpcovcd/spyfall) - Fan made web version of the Spyfall party game. ([Demo](http://spyfall.crabhat.com/)) `MIT` `HTML/Javascript`
  * [TournamentMango](http://tournamentmango.com/) - TournamentMango is an open source tournament bracket and user management system. You can build an archive of players and keep track of all their scores over time as well as their regular characters, games, and aliases. ([Source Code](https://github.com/seiyria/tournamentmango)) `MIT` `Javascript`


## Gateways 网关

**[`^        back to top        ^`](#)**

  * [GateOne](http://liftoffsoftware.com/Products/GateOne) - Gate One 基于h5的终端模拟器 ([Source Code](https://github.com/liftoff/GateOne/)) `AGPLv3` `Python`
  * [Guacamole](http://guac-dev.org/) - Guacamole is a clientless remote desktop gateway. It supports standard protocols like VNC and RDP. ([Source Code](https://github.com/glyptodon/)) `Apache` `Java/C`
  * [oneye](https://oneye-project.org/) - Cloud software to access your data from everywhere with any browser. ([Demo](https://wiki.oneye-project.org/0.9:demo), [Source Code](https://github.com/oneye/oneye)) `AGPLv3` `PHP`
  * [OS.js](https://os.js.org/) - A desktop implementation for your browser with a fully-fledged window manager, Application APIs, GUI toolkits and filesystem abstraction. ([Demo](https://demo.os-js.org/), [Source Code](https://github.com/os-js/OS.js)) `BSD` `Nodejs`


## Groupware组合软件

**[`^        back to top        ^`](#)**

  * [Citadel](http://www.citadel.org/doku.php) - Groupware including email, calendar/scheduling, address books, forums, mailing lists, IM, wiki and blog engines, RSS aggregation and more. ([Source Code](http://www.citadel.org/doku.php/installation:source)) `GPLv3` `C`
  * [Cozy Cloud](https://cozy.io) - A personal cloud where you can read your emails or manage and sync your contact, files or calendars, with an app store full of community contributions. ([Source Code](https://github.com/cozy)) `GPLv3` `Nodejs`
  * [egroupware](http://www.egroupware.org/) - Software suite including calendars, address books, notepad, project management tools, client relationship management tools (CRM), knowledge management tools, a wiki and a CMS. ([Source Code](https://github.com/EGroupware/egroupware)) `GPLv2` `PHP`
  * [Horde](http://www.horde.org/) - The Horde Project is about creating high quality Open Source applications and libraries, based on PHP and the Horde Framework. ([Demo](http://demo.horde.org/login.php), [Source Code](https://github.com/horde/horde)) `GPLv2` `PHP`
  * [HRCloud2](https://www.honestrepair.net/index.php/hrcloud2/) - A full-featured home hosted Cloud Drive, Personal Assistant, App Launcher, File Converter, Streamer, Share Tool & more. ([Source Code](https://github.com/zelon88/HRCloud2)) `GPLv3` `PHP`
  * [Kolab](https://kolab.org/) - Kolab community is a unified communication and collaboration system. ([Source Code](https://git.kolab.org/)) `Multiple` `C++/Python/PHP`
  * [Kopano](https://kopano.com/) - Groupware suite including e-mail, calendars, tasks, todos and notes. Featuring a modern WebApp, DeskApp and mobile access over Z-Push/ActiveSync. ([Demo](http://demo.kopano.com), [Source Code](https://stash.kopano.io)) `AGPLv3` `C/Python/PHP`
  * [Mayan EDMS](http://www.mayan-edms.com) - Free Open Source Electronic Document Management System. An electronic vault for your documents with preview generation, OCR, and automatic categorization among other features. ([Demo](http://demo.mayan-edms.com), [Source Code](https://gitlab.com/mayan-edms/mayan-edms)) `Apache` `Python`
  * [Openmeetings](https://openmeetings.apache.org/index.html) - Openmeetings provides video conferencing, instant messaging, white board, collaborative document editing and other groupware tools using API functions of the Red5 Streaming Server for Remoting and Streaming. ([Source Code](https://openmeetings.apache.org/source-repository.html)) `Apache` `Java`
  * [Sogo](http://www.sogo.nu/) - SOGo offers multiple ways to access the calendaring and messaging data. CalDAV, CardDAV, GroupDAV, as well as ActiveSync, including native Outlook compatibility and web interface. ([Demo](http://demo.sogo.nu/SOGo/), [Source Code](https://github.com/inverse-inc/sogo)) `GPLv1/LGPLv2` `Objective-C`
  * [Tine 2.0](https://www.tine20.org) - Contacts, Calendar, Tasks, WebDAV, ActiveSync, VOIP, Mail-Client, CRM, Sales, Projects, Timetracker. ([Demo](https://demo.tine20.net), [Source Code](https://packages.tine20.com/maintenance/source/)) `AGPLv3/Other` `PHP`
  * [Zimbra Collaboration](https://www.zimbra.com/downloads/) - Email, calendar, collaboration server with web interface and lots of integrations. ([Source Code](https://git.zimbra.com/repos/zimbra-foss/)) `GPLv2/CPALv1` `Java`


## Human Resources Management (HRM) 人力资源管理

**[`^        back to top        ^`](#)**

  * [admidio](https://www.admidio.org/) - Admidio is a free open source user management system for websites of organizations and groups. The system has a flexible role model so that it’s possible to reflect the structure and permissions of your organization. ([Demo](https://www.admidio.org/demo/), [Source Code](https://github.com/Admidio/admidio)) `GPLv2` `PHP`
  * [IceHrm](https://icehrm.com/) - IceHrm employee management system allows companies to centralize confidential employee information. ([Demo](https://icehrm.com/demo.php), [Source Code](https://github.com/gamonoid/icehrm/)) `Apache` `PHP`
  * [OrangeHRM](https://www.orangehrm.com/) - OrangeHRM is a comprehensive HRM system that captures all the essential functionalities required for any enterprise. ([Source Code](https://sourceforge.net/projects/orangehrm/)) `GPLv2` `PHP`
  * [Sentrifugo](http://www.sentrifugo.com/) - Sentrifugo is a HRM system that can be easily configured to meet your organizational needs. ([Source Code](https://github.com/sapplica/sentrifugo)) `GPLv3` `PHP`


## Learning and Courses学习课程

**[`^        back to top        ^`](#)**

  * [Canvas LMS](https://www.canvaslms.com/) - Canvas is the trusted, open-source learning management system (LMS) that is revolutionizing the way we educate. ([Demo](https://canvas.instructure.com/register), [Source Code](https://github.com/instructure/canvas-lms)) `AGPLv3` `Ruby`
  * [Chamilo LMS](https://chamilo.org/chamilo-lms/) - Chamilo LMS allows you to create a virtual campus for the provision of online or semi-online training. ([Source Code](https://github.com/chamilo/chamilo-lms)) `GPLv3` `PHP`
  * [edX](https://www.edx.org/) - The Open edX platform is open-source code that powers [edX.org](https://www.edx.org/). ([Source Code](https://github.com/edx/)) `AGPLv3` `Python`
  * [ILIAS](http://www.ilias.de) - ILIAS is the Learning Management System that can cope with anything you throw at it. ([Demo](http://demo.ilias.de), [Source Code](https://github.com/ILIAS-eLearning/ILIAS)) `GPLv3` `PHP`
  * [lxHive](http://www.lxhive.com/) - Open Source ExperienceAPI compliant Learning Record Store (LRS) - previously code-named TinCanAPI. ([Source Code](https://github.com/Brightcookie/lxHive)) `GPLv3` `PHP`
  * [Mahara](https://mahara.org/) - Open Source fully featured web application to build students electronic portfolio. ([Source Code](https://github.com/MaharaProject/mahara)) `GPLv3` `PHP`
  * [Moodle](https://moodle.org/) - Moodle is a learning and courses platform with one of the largest open source communities worldwide. ([Demo](https://moodle.org/demo/), [Source Code](https://git.moodle.org/gw)) `GPL` `PHP`
  * [Open eClass](http://www.openeclass.org/) - Open eClass is an advanced e-learning solution that can enhance the teaching and learning process. ([Demo](http://demo.openeclass.org/), [Source Code](https://github.com/gunet/openeclass)) `GPL` `PHP`
  * [RELATE](https://documen.tician.de/relate/) - RELATE is a web-based courseware package, includes features such as: flexible rules, statistics, multi-course support, class calendar. ([Source Code](https://github.com/inducer/relate/)) `MIT` `Python`
  * [Sakai](https://www.sakaiproject.org/) - The Sakai project provides a flexible and feature-rich environment for teaching, learning, research and other collaboration. ([Demo](https://www.sakaiproject.org/try-sakai), [Source Code](https://github.com/sakaiproject/sakai)) `ECLv2` `Java`
  * [SchoolTool](http://schooltool.org/) - SchoolTool is free administrative software for schools. It includes demographics, gradebook, attendance, calendaring, reporting and more for primary and secondary schools. ([Source Code](http://bazaar.launchpad.net/~schooltool-owners/schooltool/2.8/files)) `GPLv2` `Python`


## Maps & GPS 地图和定位系统

**[`^        back to top        ^`](#)**

  * [Graphhopper](https://graphhopper.com/) - Fast routing library and server using OpenStreetMap. ([Source Code](https://github.com/graphhopper/graphhopper)) `Apache` `Java`
  * [MapBBCodeShare](https://github.com/MapBBCode/share.mapbbcode.org) - Tool for sharing custom OSM maps. Support for annotated markers, polygons, lines, multi-format import/export, multiple layers, shortlinks. ([Demo](http://share.mapbbcode.org/)) `WTFPL/Other` `PHP`
  * [OpenGTS](http://www.opengts.org/) - Entry-level fleet tracking system. Supports variety of tracking devices and protocols. Comes with rich web-interface and reporting features. ([Demo](http://track.opengts.org/track/Track), [Source Code](https://sourceforge.net/projects/opengts/files/server-base/)) `Apache` `Java`
  * [Openstreetmap](http://www.openstreetmap.org/) - OpenStreetMap is a map of the world, created by people like you and free to use under an open license. ([Source Code](https://github.com/openstreetmap/openstreetmap-website)) `GPLv2` `Ruby`
  * [OwnTracks Recorder](https://github.com/owntracks/recorder) `⚠` - Store and access data published by [OwnTracks](http://owntracks.org/) location tracking apps. `GPLv2` `C`/`Lua`
  * [Traccar](https://www.traccar.org/) - Java application to track GPS positions. Supports loads of tracking devices and protocols, has an Android and iOS App. Has a web interface to view your trips. ([Demo](http://demo.traccar.org/), [Source Code](https://github.com/tananaev?tab=repositories)) `Apache` `Java`
  * [uMap](https://umap.openstreetmap.fr/en/) - Create maps with OpenStreetMap layers in a minute and embed them in your site. ([Source Code](https://github.com/umap-project/umap)) `WTFPL` `Python`


## Media Streaming 媒体流

**[`^        back to top        ^`](#)**

See also <https://en.wikipedia.org/wiki/List_of_streaming_media_systems>, <https://en.wikipedia.org/wiki/Comparison_of_streaming_media_systems>

### Audio Streaming

  * [Ampache](http://ampache.org/) - A web based audio/video streaming application. ([Demo](http://play.dogmazic.net/), [Source Code](https://github.com/ampache/ampache)) `AGPLv3` `PHP`
  * [CherryMusic](http://www.fomori.org/cherrymusic/) - Minimalistic Web-Mediaplayer. ([Source Code](https://github.com/devsnd/cherrymusic)) `GPLv3` `Python`
  * [cloudtunes](https://github.com/jkbrzt/cloudtunes) `⚠` - Web-based music player for the cloud. `MIT` `Python`
  * [Compactd](https://github.com/compactd/compactd) - A remote music player that supports adding content. `MIT` `Nodejs`
  * [FriendsRadio](https://github.com/xouabita/friends-radio) `⚠` - Share music with your friends from Youtube & Soundcloud. ([Demo](https://friends-radio.herokuapp.com/)) `MIT` `Nodejs`
  * [GNU FM](https://gnu.io/fm/) - Running music community websites, alternative to last.fm. ([Source Code](http://git.savannah.gnu.org/cgit/librefm.git/)) `AGPLv3` `PHP`
  * [Groove Basin](https://github.com/andrewrk/groovebasin) - A music player server with a web-based user interface inspired by Amarok 1.4. `MIT` `Nodejs`
  * [Icecast 2](http://www.icecast.org/) - streaming audio/video server which can be used to create an Internet radio station or a privately running jukebox and many things in between. ([Source Code](https://git.xiph.org/?p=icecast-server.git;a=summary)) `GPLv2` `C`
  * [koel](http://koel.phanan.net/) - A personal music streaming server that works. ([Source Code](https://github.com/phanan/koel)) `MIT` `PHP`
  * [Libresonic](http://libresonic.org/) - Open-source web-based media streamer and jukebox. A fork of Subsonic's last open-source release, before it switched licenses. `GPLv3` `Java`
  * [LibreTime](http://libretime.org) - Simple, open source platform that lets you broadcast streaming radio on the web (fork of [Airtime](https://github.com/sourcefabric/Airtime)). ([Source Code](https://github.com/LibreTime/libretime)) `AGPLv3` `PHP`
  * [Mopidy](http://mopidy.readthedocs.org/) - Extensible music server. Offers a superset of the mpd API, as well as integration with 3rd party services like Spotify, SoundCloud etc. ([Source Code](https://github.com/mopidy/mopidy)) `Apache` `Python`
    * [Moped](https://github.com/martijnboland/moped) - Responsive HTML5 + Javascript client for the Mopidy music server. `MIT` `HTML5`
    * [Mopidy MusicBox](https://github.com/pimusicbox/mopidy-musicbox-webclient) - Web Client for Mopidy Music Server. `Apache` `HTML5`
    * [Mopidy-Party](https://github.com/Lesterpig/mopidy-party) - Mopidy web extension designed for party! Let your guests manage the sound. `Apache` `Python`
  * [mpd](http://www.musicpd.org/) - Daemon to remotely play music, stream music, handle and organize playlists. Many clients available. `GPLv2` `C++`
  * [mStream](http://mstream.io/) - Music streaming server with GUI management tools. Runs on Mac, Windows, and Linux. ([Demo](https://darncoyotes.mstream.io/), [Source Code](https://github.com/IrosTheBeggar/mStream)) `GPLv2` `Nodejs`
  * [Music Browser](https://github.com/henrik242/musicbrowser) - Browser and streamer for your music collection. It is runs on most operating systems, and is light enough to run flawlessly on NAS devices. `GPLv3` `PHP`
   * [ympd](http://www.ympd.org/) - Standalone MPD Web GUI written in C, utilizing Websockets and Bootstrap/JS. ([Source Code](https://github.com/notandy/ympd)) `GPLv2` `C`
  * [Sonerezh](https://www.sonerezh.bzh/) - A self-hosted, web-based application for stream your music, everywhere. ([Demo](https://www.sonerezh.bzh/demo/), [Source Code](https://github.com/sonerezh/sonerezh)) `GPLv3` `PHP`

### Video Streaming 视频流

  * [crtmpserver](https://packages.debian.org/stable/crtmpserver) - High performance RTMP/RTSP streaming server. `GPLv3` `C++`
  * [CyTube](https://github.com/calzoneman/sync) - CyTube is a web application providing media synchronization, chat, and more for an arbitrary number of channels. ([Demo](http://cytu.be)) `MIT` `Nodejs`
  * [Darwin Streaming Server](https://macosforge.github.io/dss/) - High performance server for streaming QuickTime and MPEG-4 media over RTP and RTSP protocols. Originated as Apple’s QTSS. ([Source Code](https://github.com/macosforge/dss)) `APSLv2` `C++`
  * [Emby](http://emby.media/) - A home media server built using other popular open source technologies. ([Source Code](https://github.com/MediaBrowser/Emby)) `GPLv2` `C#`
  * [Flumotion](http://flumotion.net/) - A streaming media server with intuitive graphical administration tools. ([Source Code](https://github.com/Flumotion/flumotion)) `LGPLv2` `Python`
  * [Hellowlol HTPC Manager fork](https://github.com/Hellowlol/HTPC-Manager) - A fully responsive interface to manage all your favorite media on your HTPC. ([Source Code](https://github.com/styxit/HTPC-Manager)) `MIT` `Python`
  * [Icecast 2](http://www.icecast.org/) - streaming audio/video server which can be used to create an Internet radio station or a privately running jukebox and many things in between. ([Source Code](https://git.xiph.org/?p=icecast-server.git;a=summary)) `GPLv2` `C`
  * [MistServer](http://mistserver.org/) - A streaming media server that works well in any streaming environment. ([Source Code](https://github.com/DDVTECH/mistserver)) `AGPLv3` `C++`
  * [Myflix](https://github.com/pastapojken/Myflix) - Self-hosted, super lightweight Netflix alternative. `MIT` `Shell`
  * [Odd Networks](http://oddnetworks.com) - Open source video management system (VMS) and API for collections and videos with supporting SDKs for Roku, Apple iOS/tvOS, Google Android, and Amazon FireTV. ([Source Code](https://github.com/oddnetworks/oddworks)) `MIT` `Nodejs`
  * [PeerTube](https://framagit.org/chocobozzz/PeerTube) - Decentralized video streaming platform using P2P (BitTorrent) directly in the web browser. `AGPLv3` `Nodejs`
  * [ReadyMedia](http://sourceforge.net/projects/minidlna/) - A simple media server software, with the aim of being fully compliant with DLNA/UPnP-AV clients. `GPLv2` `C`
  * [Restreamer](https://datarhei.github.io/restreamer/) - Restreamer allows you to do h.264 real-time video streaming on your website without a streaming provider. ([Source Code](https://github.com/datarhei/restreamer)) `Apache` `Nodejs/Docker`
  * [Rygel](https://wiki.gnome.org/action/show/Projects/Rygel) - Rygel is a UPnP AV MediaServer that allows you to easily share audio, video, and pictures. Media player software may use Rygel to become a MediaRenderer that may be controlled remotely by a UPnP or DLNA Controller. `GPLv3` `C`
  * [Shinobi](https://moeiscool.github.io/Shinobi/) - Open Source CCTV software written in Node with both IP and local camera support. ([Source Code](https://github.com/moeiscool/Shinobi)) `GPLv2` `Nodejs`
  * [Streama](https://github.com/dularion/streama) - Self-hosted Netflix alternative. `MIT` `Java`
  * [Zoneminder](https://github.com/ZoneMinder/ZoneMinder) - Closed-circuit television (CCTV) software application which supports IP, USB and Analog cameras. `GPLv2` `PHP`


## Misc/Other 综合/其他

**[`^        back to top        ^`](#)**

  * [411](https://demo.fouroneone.io/) - 报警管理. ([Source Code](https://github.com/etsy/411)) `MIT` `PHP`
  * [Anchr](https://anchr.io) - 工具集。包含书签手机，端地址，加密图片上传 ([Source Code](https://github.com/n1try/anchr)) `GPLv3` `Nodejs`
  * [asciiflow](http://asciiflow.com/) - 流程图工具. ([Source Code](https://github.com/lewish/asciiflow2)) `GPLv3` `Java/JavaScript`
  * [COPS](https://blog.slucas.fr/en/oss/calibre-opds-php-server) - 替代Calibre content server or Calibre2OPDS.的电子书工具 ([Demo](http://cops-demo.slucas.fr/index.php), [Source Code](https://github.com/seblucas/cops)) `GPLv2` `PHP`
  * [CrushPaper](https://www.crushpaper.com/) - Research the web for relevant sources, save quotations from them to CrushPaper and then combine them with your own insights into a paper. ([Source Code](https://github.com/ZapBlasterson/crushpaper)) `AGPLv3` `Java`
  * [DomainMOD](https://domainmod.org) - An application to manage your domains and other internet assets in a central location. DomainMOD includes a Data Warehouse framework that allows you to import your WHM/cPanel web server data so that you can view, export, and report on your data. ([Demo](https://demo.domainmod.org), [Source Code](https://github.com/domainmod/domainmod)) `GPLv3` `PHP`
  * [EasyBook Project](http://easybook-project.org/) - Book publishing as easy as it should be. ([Source Code](https://github.com/javiereguiluz/easybook)) `MIT` `PHP`
  * [Flox](https://github.com/devfake/flox) `⚠` - Self hosted movie, TV series and anime watch list with a 3-point rating system. Uses The Movie Database backend for information. ([Demo](http://80.240.132.120/flox-demo/public/)) `MIT` `PHP`
  * [GeneWeb](https://geneweb.tuxfamily.org/wiki/GeneWeb) - GeneWeb is an open source genealogy software written in OCaml. It comes with a Web interface and can be used off-line or as a Web service. ([Demo](https://demo.geneweb.tuxfamily.org/gw7/), [Source Code](https://github.com/geneweb/geneweb)) `GPLv2` `OCAML`
  * [How Secure Is My Password](https://github.com/howsecureismypassword/hsimp) - Rather than just saying a password is "weak" or "strong", How Secure is My Password? lets your users know how long it would take someone to crack their password. ([Demo](https://howsecureismypassword.net/)) `MIT` `Javascript`
  * [google-webfonts-helper](https://github.com/majodev/google-webfonts-helper) `⚠` - A Hassle-Free Way to Self-Host Google Fonts. Get eot, ttf, svg, woff and woff2 files + CSS snippets. ([Demo](https://google-webfonts-helper.herokuapp.com/)) `MIT` `Nodejs`
  * [Kimai](http://www.kimai.org/) - Simple time and project tracking. ([Demo](http://www.kimai.org/demo/), [Source Code](https://github.com/kimai/kimai)) `GPLv3` `PHP`
  * [King Phisher](https://github.com/securestate/king-phisher) - King Phisher is a tool for testing and promoting user awareness by simulating real world phishing attacks. `BSD` `Python`
  * [LicAPI](https://projects.miguelpiedrafita.com/LicAPI) - A PHP API to manage license info. ([Source Code](https://github.com/m1guelpf/LicAPI)) `MPLv2` `PHP`
  * [Mindmaps](https://github.com/drichard/mindmaps) - An open source, offline capable, mind mapping application. ([Demo](http://drichard.org/mindmaps/)) `AGPLv3` `HTML5`
  * [Monica](https://monicahq.com/) - Personal relationship manager, and a new kind of CRM to organize interactions with your friends and family. ([Source Code](https://github.com/monicahq/monica)) `AGPLv3` `PHP`
  * [Musical Artifacts](https://musical-artifacts.com/) - Helping to catalog, preserve and free the artifacts you need to produce music. ([Source Code](https://github.com/lfzawacki/musical-artifacts)) `MIT` `Ruby`
  * [My Mind](https://github.com/ondras/my-mind) - A web application for creating and managing mind maps. ([Demo](https://my-mind.github.io/?url=examples%2Ffeatures.mymind)) `MIT` `Javascript`
  * [nnmm](https://nnmm.nl/) - A super tiny pastebin/url minifier "microservice". ([Source Code](https://github.com/Mechazawa/nnmm)) `Beerware` `PHP`
  * [Notica](https://notica.us) - Lets you send browser notifications from your terminal to your desktop or phone. No installation or registration is required. ([Source Code](https://github.com/tannercollin/Notica)) `MIT` `Nodejs`
  * [Skygear](https://skygear.io) - A complete backend server for web, mobile and iOT applcations. ([Demo](https://portal.skygear.io), [Source Code](https://github.com/SkygearIO/skygear-server)) `Apache` `Go`
  * [Trello Burndown](https://github.com/swordbeta/trello-burndown) `⚠` - An easy to use SCRUM burndown chart for Trello boards. `MIT` `Go/Docker`
  * [Ulterius](https://ulterius.io) - Ulterius is an open-source remote desktop software with lots of awesome functions. ([Demo](https://ulterius.io/signup/), [Source Code](https://github.com/Ulterius/server)) `MPLv2` `C#`
  * [ViMbAdmin](http://www.vimbadmin.net/) - Provides a web based virtual mailbox administration system to allow mail administrators to easily manage domains, mailboxes and aliases. ([Demo](http://www.vimbadmin.net/demo/auth/login), [Source Code](https://github.com/opensolutions/ViMbAdmin)) `GPLv3` `PHP`
  * [visualCaptcha](http://visualcaptcha.net/) - A configurable captcha solution, focusing on accessibility & simplicity whilst maintaining security. ([Demo](http://demo.visualcaptcha.net/), [Source Code](https://github.com/emotionLoop/visualCaptcha)) `MIT` `PHP/Nodejs/Ruby/Python`
  * [webtrees](https://www.webtrees.net) - webtrees is the web's leading on-line collaborative genealogy application. ([Demo](https://dev.webtrees.net/demo-stable/index.php?ctype=gedcom&ged=demo), [Source Code](https://github.com/fisharebest/webtrees)) `GPLv3` `PHP`

## Money, Budgeting and Management  理财和省钱

**[`^        back to top        ^`](#)**

See also https://github.com/n1trux/awesome-sysadmin#it-asset-management

  * [Akaunting](https://akaunting.com/) - Akaunting免费在线用于小生意和自由工作者 ([Source Code](https://github.com/akaunting/akaunting)) `GPLv3` `PHP`
  * [Benedetto](https://github.com/arecker/bennedetto) - Bennedetto 简单账本管理 `GPLv3` `Python`
  * [Budget App](https://www.budgetapp.io/) - 个人账本管理 ([Demo](https://demo.budgetapp.io/), [Source Code](https://github.com/paukiatwee/budgetapp)) `Apache` `Java`
  * [Dot Ledger](https://www.dotledger.com/) - 个人财务管理工具. ([Demo](https://demo.dotledger.com/), [Source Code](https://github.com/dotledger/dotledger)) `Apache` `Ruby`
  * [Economizzer](http://www.economizzer.org/) - Economizzer 简单金融管理系统 ([Source Code](https://github.com/gugoan/economizzer)) `MIT` `PHP`
  * [ExMoney](https://github.com/gaynetdinov/ex_money) - A [work-in-progress] 个人金融appp `ISC` `Elixir`
  * [Firefly III](https://firefly-iii.github.io/) - Firefly III现代财务管理器，帮你跟踪你的财富和作出预测，支持信用卡，账户，省钱账户 ([Demo](https://firefly-iii.nder.be/), [Source Code](https://github.com/firefly-iii/firefly-iii)) `GPLv3` `PHP`
  * [Galette](http://galette.eu/dc/) - Galette关系管理系统. ([Source Code](http://git.tuxfamily.org/galette/galette.git/)) `GPLv3` `PHP`
  * [GRR](http://grr.devome.com/?lang=en) - 资产管理 ([Source Code](https://github.com/JeromeDevome/GRR)) `GPLv2` `PHP`
  * [Hospital Run](http://hospitalrun.io/) - Hospital医院管理软件 ([Source Code](https://github.com/HospitalRun/hospitalrun-server), [Demo](http://hospitalrun.io/demo/)) `GPLv3` `Nodejs`
  * [Inventaire](https://inventaire.io/welcome) - 书本映射 wikidata and ISBNs. ([Source Code](https://github.com/inventaire/inventaire)) `AGPLv3` `Nodejs`
  * [Invoice Ninja](https://www.invoiceninja.org/) - 发票管理器 ([Demo](https://app.invoiceninja.com/invoices/create), [Source Code](https://github.com/invoiceninja/invoiceninja)) `AAL` `PHP`
  * [InvoicePlane](https://invoiceplane.com/) - 管理支出发票 ([Demo](https://demo.invoiceplane.com), [Source Code](https://github.com/InvoicePlane/InvoicePlane)) `MIT` `PHP`
  * [IHateMoney](http://ihatemoney.org/) - 管理支出. ([Source Code](https://github.com/spiral-project/ihatemoney)) `BSD` `Python`
  * [Koha](https://koha-community.org/) - 可扩展的库. ([Source Code](https://github.com/Koha-Community/Koha)) `GPLv3` `Perl`
  * [PartKeepr](https://www.partkeepr.org) - PartKeepr创新管理. ([Demo](https://demo.partkeepr.org/), [Source Code](https://github.com/partkeepr/PartKeepr)) `GPLv3` `PHP`
  * [StockazNG](https://dev.sigpipe.me/dashie/StockazNG) - 资产管理 `MIT` `Python`


## Monitoring

**[`^        back to top        ^`](#)**

See https://github.com/n1trux/awesome-sysadmin#monitoring and https://github.com/n1trux/awesome-sysadmin#metric--metric-collection


## Note-taking & Editors 笔记和编辑器

**[`^        back to top        ^`](#)**

*See also [Wikis](#wikis)*

  * [dillinger](http://dillinger.io/) - 最后一个 Markdown编辑器 ([Source Code](https://github.com/joemccann/dillinger/)) `MIT` `Nodejs`
  * [draw.io](https://draw.io) - 画图软件，用于制作流程图，过程图，组织图 UML, ER and network图等  ([Source Code](https://github.com/jgraph/drawio)) `Apache` `JavaScript`
  * [HackMD](https://www.hackmd.io) - 全平台实时协作md编辑器 ([Source Code](https://github.com/hackmdio/hackmd/)) `MIT` `Node.js`
  * [Laverna](https://laverna.cc/) - Laverna是Evernote的开源版本. ([Demo](https://laverna.cc/index.html#notes), [Source Code](https://github.com/Laverna/laverna)) `MPLv2` `Nodejs`
  * [Leanote](http://leanote.org/) - Leanote,不仅仅是一个笔记本 ([Demo](https://leanote.com/note), [Source Code](https://github.com/leanote/leanote)) `GPLv2` `Go`
  * [Markdown Edit](http://georgeosddev.github.com/markdown-edit/) - 在线md编辑和查看器 ([Source Code](https://github.com/georgeOsdDev/markdown-edit)) `MIT` `HTML5`
  * [Meemo](https://meemo.minimal-space.de/) - 个人md编辑器 ([Source Code](https://github.com/nebulade/meemo)) `MIT` `Nodejs`
  * [minimalist-web-notepad](https://github.com/pereorga/minimalist-web-notepad) - A minimalist notepad.cc clone. `Apache` `PHP`
  * [MiniNote](https://github.com/n1try/mininote) - 持久话的简单md编辑器 `MIT` `Nodejs`
  * [notes](https://github.com/SSilence/notes) -  WYSIWYG Editor. `GPLv3` `PHP`
  * [OpenNote](https://github.com/FoxUSA/OpenNote) -  Microsoft OneNote (T) and EverNote的替代 ([Demo](https://foxusa.github.io/OpenNote/OpenNote/#/folder)) `MIT` `HTML5`
  * [Paperwork](http://paperwork.rocks) - Evernote, Microsoft OneNote & Google Keep的替代 ([Source Code](https://github.com/twostairs/paperwork)) `MIT` `PHP`
  * [savepad](https://github.com/novavex/textpad) - 基于notepad.cc的笔记本. `MIT` `PHP`
  * [SiMPad](https://gitlab.com/beli3ver/SiMPad) - 简单的自部署md ([Demo](https://pad.malte-kiefer.de/)) `MIT` `PHP`
  * [ShareLaTex](https://www.sharelatex.com/) - 基于web自定义的 LaTeX编辑器 ([Source Code](https://github.com/sharelatex/sharelatex)) `AGPLv3` `Ruby`
  * [Standard Notes](https://standardnotes.org) - 简单，私密的笔记应用([Demo](https://app.standardnotes.org/), [Source Code](https://github.com/standardnotes)) `GPLv3` `Ruby`
  * [to-markdown](https://domchristie.github.io/to-markdown/) - md转换器 ([Source Code](https://github.com/domchristie/to-markdown)) `MIT` `JavaScript`
  * [Turtl](https://turtl.it/) - 完全私有用户笔记 ([Source Code](https://github.com/turtl)) `GPLv3` `CommonLisp`


## Office Suites 办公组件

**[`^        back to top        ^`](#)**

  * [EtherCalc](https://ethercalc.org/) - 扩展sheet  ([Source Code](https://github.com/audreyt/ethercalc)) `CPALv1/Other` `Nodejs`
  * [EtherDraw](https://github.com/JohnMcLear/draw) - web协作会话工具`Apache` `Nodejs`
  * [Etherpad](http://etherpad.org/) - Etherpad 高度自定义的开源编辑器 ，提供实时协作编辑能力. ([Demo](https://demo.sandstorm.io/appdemo/h37dm17aa89yrd8zuqpdn36p6zntumtv08fjpu8a8zrte7q1cn60), [Source Code](https://github.com/ether/etherpad-lite)) `Apache` `Nodejs`
  * [Infinoted](https://github.com/gobby/gobby/wiki/Dedicated%20Server) - A server for [Gobby](https://github.com/gobby/gobby/wiki), 多平台协作编辑器 ([Source Code](https://github.com/gobby/gobby)) `MIT` `C++`
  * [ONLYOFFICE](http://onlyoffice.org/) - offlice组件能使你管理文档，项目，团队和用户关系. ([Source Code](https://github.com/ONLYOFFICE/DocumentServer)) `AGPLv3` `Nodejs`
  * [PHPOffice](http://phpoffice.github.io/) - PHPOffice可以让你读写醉常用的office组件  `LGPLv3` `PHP`
  * [WebODF](http://webodf.org/) - 工具库让你浏览和编辑otf文件 ([Source Code](https://github.com/kogmbh/WebODF)) `AGPLv3` `HTML5`


## Password Managers 密码管理

**[`^        back to top        ^`](#)**

 * [Bitwarden](https://bitwarden.com/) - Password manager with webapp, browser extension, and mobile app. ([Source Code](https://github.com/bitwarden/core)) `AGPLv3` `C#`
 * [keeweb](https://keeweb.info/) - This webapp is a browser and desktop password manager compatible with KeePass databases. ([Source Code](https://github.com/keeweb/keeweb)) `MIT` `HTML5`
 * [sysPass](http://www.syspass.org/) - Multiuser password management system. ([Demo](http://demo.syspass.org/), [Source Code](https://github.com/nuxsmin/sysPass)) `GPLv3` `PHP`
 * [Teampass](http://teampass.net/) - Password manager dedicated for managing passwords in a collaborative way on any server Apache, MySQL and PHP. ([Source Code](https://github.com/nilsteampassnet/TeamPass/)) `GPLv3` `PHP`


## Pastebins代码片段分享工具

**[`^        back to top        ^`](#)**

  * [0bin](https://github.com/sametmax/0bin) - Client side encrypted pastebin. `WTFPL` `Python`
  * [CoderVault](https://github.com/codervault) - 开源代码管理. ([Source Code](https://github.com/codervault/codervault)) `MIT` `Ruby`
  * [cryptonote](https://cryptonote.me/) - A simple open source web application that lets users encrypt and share messages that can only be read once. ([Source Code](https://github.com/alainmeier/cryptonote)) `BSD` `Ruby`
  * [CryptPad](https://cryptpad.fr/) - CryptPad is the zero knowledge realtime collaborative editor. ([Source Code](https://github.com/xwiki-labs/cryptpad)) `AGPLv3` `Nodejs`
  * [EdPaste](https://github.com/Edraens/EdPaste) - Self-hosted pastebin written in Laravel (PHP Framework). `MIT` `PHP`
  * [fiche](https://github.com/solusipse/fiche) - Command line pastebin, all you need is netcat. ([Demo](http://termbin.com/)) `MIT` `C`
  * [gist](https://gitnet.fr/deblan/gist) - GIST 分享代码的开源应用 `GPLv3` `PHP`
  * [hastebin](http://hastebin.com/about.md) - Open source pastebin written in node.js. ([Demo](http://hastebin.com/), [Source Code](https://github.com/seejohnrun/haste-server)) `MIT` `Nodejs`
  * [localpaste](https://github.com/petermaloney/localpaste) - Simple python based pastebin you can run locally, with curl for input. Supports RAW text by default and binary data such as images (no extensions on returned url). `GPLv2` `Python`
  * [Modern Paste](https://www.modernpaste.com) - Modern pastebin with a contemporary, minimalistic user interface backed by a robust feature set. ([Demo](https://demo.modernpaste.com/), [Source Code](https://github.com/LINKIWI/modern-paste)) `MIT` `Python`
  * [mojopaste](http://search.cpan.org/dist/App-mojopaste/) - Perl based pastebin. ([Demo](http://p.thorsen.pm/), [Source Code](https://github.com/jhthorsen/app-mojopaste)) `ARTv2` `Perl`
  * [NoteHub](https://notehub.org) - Free and Hassle-free Pastebin for Markdown Pages. Simple, clean, password provided, generated-short link. ([Demo](https://notehub.org), [Source Code](https://github.com/chmllr/NoteHub)) `MIT` `Nodejs`
  * [Paste](http://phpaste.sourceforge.io/) - Paste is forked from the original source pastebin.com used before it was bought. ([Demo](http://phpaste.sourceforge.net/demo), [Source Code](https://github.com/jordansamuel/PASTE)) `GPLv3` `PHP`
  * [pastebin](https://github.com/prologic/pastebin) - A simple pastebin service with convenient api and CLI. ([Demo](https://paste.mills.io)) `MIT` `Go`
  * [Pastebin](https://github.com/ewhal/Pastebin) - Modern self-hosted pastebin service with a restful API. `MIT` `Go`
  * [pb](https://github.com/ptpb/pb) - Lightweight pastebin (and url shortener) built using flask. ([Demo](https://ptpb.pw/)) `GPLv3` `Python`
  * [pbnh](https://github.com/bhanderson/pbnh) - Pastebin inspired from project pb and hastebin, with an API and a SQL-based backend. `MIT` `Python`
  * [Phaste](https://pste.pw) - A Phalcon-based, MySQL pastebin application with privacy-respecting Piwik integration and syntax highlighting. ([Source Code](https://github.com/FoxDev/Phaste)) `AGPLv3` `PHP`
  * [PrivateBin](https://privatebin.info/) - PrivateBin is a minimalist, opensource online pastebin/discussion board where the server has zero knowledge of hosted data. ([Demo](https://privatebin.net/), [Source Code](https://github.com/PrivateBin/PrivateBin)) `Zlib` `PHP`
  * [SharpPaste](https://github.com/phonicmouse/SharpPaste) - A simple and modern open-source pastebin made with C# and NancyFX that just works. ([Demo](https://sharppaste.nl/)) `MIT` `C#/ASP.NET`
  * [snipt](https://snipt.net/) - Long-term memory for coders. Share and store code snippets. ([Source Code](https://github.com/nicksergeant/snipt/)) `BSD` `Python`
  * [Sticky Notes](http://sayakb.github.io/sticky-notes/) - A powerful open-source pastebin application for effortless code sharing. ([Source Code](https://github.com/sayakb/sticky-notes)) `BSD` `PHP`
  * [Stikked](https://github.com/claudehohl/Stikked) - An advanced and beautiful pastebin. `GPLv3` `PHP`
  * [Sup3rS3cretMes5age](https://github.com/algolia/sup3rS3cretMes5age) - A very simple (to deploy and to use) secret message service using Hashicorp Vault as a secrets storage. `MIT` `Go`
  * [tastebin](https://github.com/andreineculau/tastebin) - Updated version of hastebin plus additional features. `Apache` `Nodejs`


## Personal Dashboards 个人生活管理
See https://github.com/n1trux/awesome-sysadmin#metric--metric-collection

**[`^        back to top        ^`](#)**

  * [Baby Buddy](https://github.com/cdubz/babybuddy) - Helps caregivers track baby sleep, feedings, diaper changes, and tummy time. ([Demo](https://babybuddy.herokuapp.com/)) `BSD` `Python`
  * [DeviceHive](https://www.devicehive.com/) - Open Source IoT Plaform with a wide range of integration options. ([Demo](https://playground.devicehive.com/), [Source Code](https://github.com/devicehive/devicehive-java-server)) `Apache` `Java`
  * [Dj Diabetes](https://github.com/foxmask/dj-diabetes) - My Glucose Manager - follow your daily health. `BSD` `Python`
  * [Habitica](http://habitica.com/) - A habit tracker app which treats your goals like a Role Playing Game. Previously called HabitRPG. ([Source Code](https://github.com/HabitRPG/habitrpg)) `GPLv3/Other` `Nodejs`
  * [Homepage](https://github.com/thetomester13/homepage) - A simple, standalone, self-hosted PHP page that is your window to your server and the web. `MIT` `PHP`
  * [iDashboard-PHP](https://github.com/causefx/iDashboard-PHP) - HTPC Dashboard to load website services. `MIT` `PHP`
  * [Iotdashboard](http://iotdashboard.pythonanywhere.com/en/) - Fast Django server for IOT Devices. ([Source Code](https://github.com/electrocoder/iotdashboard)) `Apache` `JavaScript`
  * [Phant](http://phant.io/) - Phant is a modular data logging tool for collecting data from the Internet of Things. ([Demo](https://data.sparkfun.com/), [Source Code](https://github.com/sparkfun/phant)) `GPLv3` `Nodejs`
  * [Thingsboard](https://thingsboard.io/) - Open-source IoT Platform - Device management, data collection, processing and visualization. ([Demo](https://demo.thingsboard.io/signup), [Source Code](https://github.com/thingsboard/thingsboard)) `Apache` `Java`
  * [Thingspeak](https://thingspeak.com/) - An open source “Internet of Things” application and API to store and retrieve data from things using HTTP. ([Demo](https://thingspeak.com/channels/public), [Source Code](https://github.com/iobridge/thingspeak)) `GPL` `Ruby`
  * [Tipboard](http://allegro.tech/tipboard/) - In-house, tasty, local dashboarding system. ([Source Code](https://github.com/allegro/tipboard)) `Apache` `Python`
  * [wger](https://wger.de/) - A web-based personal workout, fitness and weight logger/tracker. It can also be used as a simple gym management utility and offers a full REST API as well. ([Demo](https://wger.de), [Source Code](https://github.com/rolandgeider/wger)) `AGPLv3` `Python`


## Photo and Video Galleries 图片视频画廊

**[`^        back to top        ^`](#)**

  * [Chevereto Free](https://chevereto.com/free) - A powerful and fast image hosting script that allows you to create your very own full featured image hosting website in just minutes. ([Source Code](https://github.com/Chevereto/Chevereto-Free)) `AGPLv3` `PHP`
  * [Coppermine](http://coppermine-gallery.net/) - Multilingual photo gallery that integrates with various bulletin boards. Includes upload approval and password protected albums. ([Demo](http://coppermine-gallery.net/demo/cpg15x/), [Source Code](https://github.com/coppermine-gallery/cpg1.6.x)) `GPLv3` `PHP`
  * [CumulusClips](http://cumulusclips.org/) - Your own video sharing website with CumulusClips video sharing script. You can build a YouTube clone where users can upload, rate, comment on videos, and much more. ([Demo](https://tube.devosi.org/)) `GPLv2` `PHP`
  * [Gallery CSS](https://benschwarz.github.io/gallery-css/) - Gallery.css is all CSS. Think: Simple, maintainable and understandable galleries without the use of Javascript. ([Source Code](https://github.com/benschwarz/gallery-css)) `MIT` `CSS`
  * [Lychee](http://lychee.electerious.com/) - An open source grid and album based photo-management-system. ([Source Code](https://github.com/electerious/Lychee)) `MIT` `PHP`
  * [MediaDrop](http://mediadrop.net/) - A video, audio and podcast publication platform. ([Source Code](https://github.com/mediadrop/mediadrop)) `GPLv3` `Python`
  * [Mediagoblin](http://mediagoblin.org) - A Free software media publishing platform that anyone can run. You can think of it as a decentralized alternative to Flickr, YouTube, SoundCloud, etc. ([Source Code](https://savannah.gnu.org/projects/mediagoblin)) `AGPLv3` `Python`
  * [MinigalNano](https://github.com/sebsauvage/MinigalNano) - MinigalNano is a very simple image gallery. It adheres to the KISS principle and is very easy to install. MinigalNano does not have a web admin interface: You just upload your images in the photo folder on your server (using FTP, SFTP). `AGPLv3` `PHP`
  * [Photato](https://github.com/trebonius0/Photato) - A self-hosted photo gallery, accessible through a responsive WebUI. Directly uses and indexes a specific folder in the filesystem. `AGPLv3` `Java`
  * [Photofloat](http://blog.zx2c4.com/567) - A Web 2.0 Photo Gallery Done Right via Static JSON & Dynamic Javascript. ([Demo](http://photos.jasondonenfeld.com/)) `GPLv2` `Python`
  * [PhotoLight](https://github.com/thibaud-rohmer/PhotoLight) - The easiest photo gallery there is. `GPLv3` `PHP`
  * [Photoshow](http://www.photoshow-gallery.com/) - Responsive Web Gallery. ([Source Code](https://github.com/thibaud-rohmer/PhotoShow)) `GPLv3` `PHP`
  * [Piwigo](http://piwigo.org/) - Photo gallery software for the web, built by an active community of users and developers. `GPLv2` `PHP`
  * [Plumi](http://blog.plumi.org/) - Create your own sophisticated video-sharing site. ([Source Code](https://github.com/plumi/plumi.app)) `GPLv2` `Python`
  * [sigal](https://github.com/saimn/sigal) - Yet another simple static gallery generator. `MIT` `Python`
  * [UberGallery](http://www.ubergallery.net) - UberGallery is an easy to use, simple to manage, web photo gallery. UberGallery does not require a database and supports JPEG, GIF and PNG file types. Simply upload your images and UberGallery will automatically generate thumbnails and output HTML. ([Source Code](https://github.com/UberGallery/UberGallery)) `MIT` `PHP`
  * [Videobin](http://videobin.org/code) - A simple video upload and sharing service with transcoding. ([Demo](http://videobin.org/), [Source Code](https://r-w-x.org/videobin.git)) `GPLv3` `Python`
  * [Zenphoto](http://www.zenphoto.org/) - Open-source gallery and CMS project. ([Source Code](https://github.com/zenphoto/zenphoto)) `GPLv2` `PHP`


## Polls and Events 投票和事件

**[`^        back to top        ^`](#)**

  * [Calagator](http://calagator.org/) - 时间聚合器 ([Demo](http://calagator.org/), [Source code](https://github.com/calagator/calagator)) `MIT` `Ruby`
  * [Clerk](https://github.com/chr15m/Clerk) - 简单的事件记录器，跟踪周期性的事件，习惯等等 . `GPLv3` `PHP`
  * [dudle](http://primelife.ercim.eu/results/opensource/63-dudle) - 在线调度应用 ([Demo](https://dudle.inf.tu-dresden.de/)) `AGPLv3` `Ruby`
  * [Fider](http://getfider.com) - 用户之声的开源选择 ([Demo](https://demo.fider.io), [Source Code](https://github.com/getfider/fider)) `MIT` `Go`
  * [Framadate](https://framadate.org/) - 约会和快速决策的一个在线服务 ，可以发给朋友投票连接 ([Demo](https://framadate.org/aqg259dth55iuhwm), [Source Code](https://git.framasoft.org/framasoft/framadate)) `CeCILL-B` `PHP`
  * [Kyélà](http://kyela.net/) - 群组事件的选举投票. ([Demo](http://kyela.net/55232734237c8/), [Source Code](https://github.com/abienvenu/Kyela)) `AGPLv3` `PHP`
  * [LimeSurvey](https://www.limesurvey.org) - 全功能的开源投票软件，支持扩展调研逻辑 ([Demo](https://demo.limesurvey.org), [Source code](https://github.com/LimeSurvey/LimeSurvey)) `GPLv2` `PHP`
  * [MaterialPoll](https://github.com/nearbycoder/materialpoll) - 开源的随机投票 ([Demo](http://materialpoll.tk), [Source Code](https://github.com/nearbycoder/materialpoll)) `MIT` `Nodejs`
  * [Nuages](https://nuages.domainepublic.net/) - 类似doodle or rdvz，协作的会议投票系统 ([Source Code](http://git.domainepublic.net/?p=nuages.git;a=tree)) `GPLv3` `Python`
  * [PHPBack](http://www.phpback.org) - 开源反馈系统. ([Demo](http://www.phpback.org/demo/), [Source Code](https://github.com/ivandiazwm/phpback/)) `GPLv3` `PHP`
  * [TellForm](https://tellform.com) - 在线论坛和调研生成器  ([Demo](https://tellform.com/examples), [Source Code](https://github.com/whitef0x0/tellform)) `MIT` `Nodejs`


## Proxy 代理

**[`^        back to top        ^`](#)**

  * [http2-serverpush-proxy](https://github.com/n1try/http2-serverpush-proxy) - 一个自动应用http2.0的服务推送机制的反响代理 ，可以作为中间件或独立应用 `MIT` `Nodejs`
  * [iodine](http://code.kryo.se/iodine/) - A ipv4 over DNS tunnel solution, 可以建立socks5 代理监听器 ([Source Code](https://github.com/yarrick/iodine)) `ISC` `C`
  * [microproxy](https://github.com/thekvs/microproxy) - 轻量不缓存的代理服务器. ([Source Code](https://github.com/thekvs/microproxy)) `MIT` `Go`
  * [miniProxy](https://github.com/joshdick/miniProxy/) - 简单web代理，允许绕过网络过滤器，匿名访问网络 ([Source Code](https://github.com/joshdick/miniProxy/)) `GPLv3` `PHP`
  * [Oranjeproxy](http://lehollandaisvolant.net/tout/oranjeproxy/) -匿名网络代理. ([Source Code](https://github.com/AmauryCarrade/OranjeProxy)) `GPLv2` `PHP`
  * [PHP-Proxy](https://www.php-proxy.com/) - 视频网站代理. ([Demo](https://unblockvideos.com/), [Source Code](https://github.com/Athlon1600/php-proxy-app)) `MIT` `PHP`
  * [Pound](http://www.apsis.ch/pound/) - 轻量反向代理 ([Source Code](http://www.apsis.ch/pound/)) `GPLv2` `C`
  * [Privoxy](http://www.privoxy.org) - 增强隐私 ，高级过滤功能的非缓存网络代理，可以修改页面数据，http头信息，控制接入，移除广告和其他讨厌的网络垃圾 `GPLv2` `C`
  * [Squid](http://www.squid-cache.org/) - 支持多种协议的网络缓存代理，减小带宽，通过缓存和重用常用的页面 ([Source Code](https://code.launchpad.net/squid)) `GPLv2` `C`
  * [Swiperproxy](https://swiperproxy.github.io/) - 轻量快速的网络代理  ([Source Code](https://github.com/swiperproxy/swiperproxy)) `MIT` `Python`
  * [Tinyproxy](https://banu.com/tinyproxy/) - proxy . ([Source Code](https://github.com/tinyproxy/tinyproxy)) `GPLv2` `C`
  * [Traefik](https://traefik.io/) - Træfɪk 是现代http反响代理，和负载均衡器，可以轻便的部署微服务，可以支持多种后端(Docker, Swarm, Mesos/Marathon, …) 可以自动动态的管理配置。 ([Source Code](https://github.com/containous/traefik)) `MIT` `Go`


## Read it Later Lists 事后阅读

**[`^        back to top        ^`](#)**

  * [Nunux Keeper](http://keeper.nunux.org/) - 个人内容管理服务 ([Source Code](https://github.com/ncarlier/nunux-keeper)) `GPLv3` `Nodejs`
  * [Wallabag](https://www.wallabag.org) - Wallabag, formerly Poche, 允许保存内容方便以后阅读. ([Demo](http://demo.wallabag.org/), [Source Code](https://github.com/wallabag/wallabag)) `MIT` `PHP`


## Search Engines

**[`^        back to top        ^`](#)**

  * [Gigablast](http://www.gigablast.com/) - 开源的搜索引擎 ([Demo](http://www.gigablast.com/), [Source Code](https://github.com/gigablast/open-source-search-engine)) `Apache` `C++`
  * [Seeks](https://beniz.github.io/seeks/) - A websearch 代理 ([Source Code](https://github.com/beniz/seeks)) `AGPLv3` `C++`
  * [Searx](https://asciimoo.github.io/searx/) - 一个尊重隐私的，可以控制的元搜索引擎([Demo](https://searx.me/), [Source Code](https://github.com/asciimoo/searx)) `AGPLv3` `Python`
  * [Yacy](http://yacy.net/en/index.html) - 去中心化的搜索引擎 ([Demo](http://search.yacy.net/), [Source Code](https://github.com/yacy/yacy_search_server)) `GPLv2` `Java`


## Software Development 软件开发

**[`^        back to top        ^`](#)**

### Project Management 项目管理

_See also [Ticketing](#ticketing), [Task management/To-do lists](#task-managementto-do-lists)_

  * [Apache Bloodhound](https://bloodhound.apache.org/) - 管理软件，跟踪功能，任务和bugs `Apache` `Python`
  * [Bonobo Git Server](https://bonobogitserver.com/) - 建立自己的git服务([Source Code](https://github.com/jakubgarfield/Bonobo-Git-Server)) `MIT` `C#`
  * [CaseBox](https://www.casebox.org) - 管理所有的组织信息. ([Source Code](https://github.com/KETSE/casebox)) `AGPLv3` `PHP/Java`
  * [Fossil](https://www.fossil-scm.org/index.html/doc/trunk/www/index.wiki) - 包含wiki和bug跟踪的分布式 版本控制器。 `BSD` `C`
  * [Gitblit](http://gitblit.com/) - 纯java的管理git . ([Source Code](https://github.com/gitblit/gitblit)) `Apache` `Java`
  * [gitbucket](https://gitbucket.github.io/gitbucket-news/) - 使用Scala的github替代方案 ([Source Code](https://github.com/gitbucket/gitbucket)) `Apache` `Scala/Java`
  * [Gitea](https://gitea.io) - fork自Gogs,社区维护的轻量代码存储方案 ([Demo](https://try.gitea.io), [Source Code](https://github.com/go-gitea/gitea)) `MIT` `Go`
  * [GitLab](http://gitlab.org/) -无需多言 ([Demo](https://gitlab.com/), [Source Code](https://gitlab.com/gitlab-org/gitlab-ce)) `MIT` `Ruby`
  * [Gitlist](http://gitlist.org/) - 基于web的git库浏览([Source Code](https://github.com/klaussilveira/gitlist)) `BSD` `PHP`
  * [GitPrep](http://gitprep.yukikimoto.com/) - 便携的Github. ([Demo](http://perlcodesample.sakura.ne.jp/gitprep/gitprep.cgi), [Source Code](https://github.com/yuki-kimoto/gitprep)) `GPL` `Perl`
  * [Git WebUI](https://github.com/alberthier/git-webui) - 单机的git查看的ui`Apache` `Python`
  * [Gogs](https://gogs.io/) - 用Go写的git. ([Demo](https://try.gogs.io/), [Source Code](https://github.com/gogits/gogs)) `MIT` `Go`
  * [Kallithea](https://kallithea-scm.org/) - 源代码管理器支持 Mercurial and Git,([Source Code](https://kallithea-scm.org/repos/kallithea)) `GPLv3` `Python`
  * [Klaus](https://github.com/jonashaag/klaus/) - 简单容易部署的gitweb . `ISC` `Python`
  * [Lavagna](http://lavagna.io) - 小团队事件 项目管理工具。([Source Code](https://github.com/digitalfondue/lavagna)) `GPLv3` `Java`
  * [Octobox](https://octobox.io/) `⚠` - 管理github的通知 ([Source Code](https://github.com/octobox/octobox)) `AGPLv3` `Ruby`
  * [OpenProject](https://www.openproject.org) - 基于web的项目管理系统 `GPLv3` `Ruby`
  * [Phabricator](http://phabricator.org/) - 帮助构建更好的软件. ([Demo](https://secure.phabricator.com/), [Source Code](https://github.com/phacility/phabricator)) `Apache` `PHP`
  * [Redmine](http://www.redmine.org/) - 灵活的项目管理 . ([Demo](http://demo.redmine.org/), [Source Code](https://svn.redmine.org/redmine/)) `GPLv2` `Ruby`
  * [RhodeCode](https://rhodecode.com/) - 软件管理 ([Demo](https://try.rhodecode.com/), [Source Code](https://code.rhodecode.com/)) `AGPLv3` `Python`
  * [SCM Manager](https://www.scm-manager.org/) - vcs管理. ([Source Code](https://bitbucket.org/sdorra/scm-manager/src)) `BSD` `Java`
  * [Taiga](https://taiga.io/) - 敏捷的项目管理工具 ([Source Code](https://github.com/taigaio)) `AGPLv3` `Python`
  * [The Bug Genie](http://www.thebuggenie.com/) - 友好的项目管理工具. ([Source Code](https://github.com/thebuggenie/thebuggenie)) `MPLv2` `PHP`
  * [Trac](http://trac.edgewall.org/) - 增强的事件管理和issue 跟踪 `BSD` `Python`
  * [Tuleap](https://www.tuleap.org/) - 软件管理 ([Source Code](https://tuleap.net/plugins/git/tuleap/tuleap/stable?p=tuleap%2Fstable.git&a=tree)) `GPLv2` `PHP`
  * [Phproject](http://www.phproject.org/) - 项目管理系统 ([Demo](http://demo.phproject.org/), [Source Code](https://github.com/Alanaktion/phproject)) `GPLv3` `PHP`


### Bug Trackers bug跟踪

See **[Ticketing](#ticketing)**


### IDE/Tools

  * [Codiad](http://codiad.com/) - ide. ([Source Code](https://github.com/Codiad/Codiad)) `MIT` `PHP`
  * [Eclipse Che](http://www.eclipse.org/che/) - 云ide ([Source Code](https://github.com/eclipse/che)) `EPLv1` `Docker/Java`
  * [ICEcoder](https://icecoder.net/) - 在浏览器写代码 . ([Demo](http://demo.icecoder.net/ICEcoder/), [Source Code](https://github.com/mattpass/ICEcoder)) `MIT` `PHP`
  * [JS Bin](http://jsbin.com/) - 协同web开发调试工具([Source Code](https://github.com/jsbin/jsbin)) `MIT` `Nodejs`
  * [Judge0 API](https://api.judge0.com) - 编译工具([Source Code](https://github.com/judge0/api)) `GPLv3` `Ruby`
  * [Koding](http://www.koding.com/) - 管理整个开发架构 ([Source Code](https://github.com/koding/koding)) `Apache` `Nodejs`
  * [Microglark](http://micro.glark.io) - 最小的远程代码编辑器 ([Demo](http://micro.glark.io), [Source Code](https://github.com/Bluefinch/microglark)) `AGPLv3` `Nodejs`
  * [Regexr](http://regexr.com/) - 基于js的正则表达检验. ([Source Code](https://github.com/gskinner/regexr/)) `MIT` `Nodejs`
  * [RequestBin](https://requestb.in/) - 检查http请求 . ([Source Code](https://github.com/Runscope/requestbin)) `MIT` `python`
  * [RStudio Server](https://www.rstudio.com/products/rstudio/#Server) - R语言基于web的IDE ([Source Code](https://github.com/rstudio/rstudio/)) `AGPLv3` `Java/C++`
  * [Selenoid](http://aerokube.com/selenoid/latest/) - 容器部署的轻量Selenium实现，在浏览器使用 ([Source Code](https://github.com/aerokube/selenoid)) `Apache` `Go`
  * [Wide](https://github.com/b3log/wide) - go开发的web编辑器 ([Demo](http://wide.b3log.org/signup)) `Apache` `Go`
  * [Zalenium](https://github.com/zalando/zalenium) - 允许任何人一次性和扩展基于docker的 Selenium `Apache` `Java/Shell`



### Continuous Integration 持续集成

  * [Buddy GO](https://buddy.works/) - git持续集成开发平台 `Fair` `Nodejs/Java`
  * [Concourse](https://concourse.ci/) - Concourse是一个持续集成工具，把pipeline作为一等对象，容器化每一个步骤 ([Demo](https://ci.concourse.ci/), [Source Code](https://github.com/concourse/concourse)) `Apache` `Go`
  * [drone](https://drone.io/) - Drone是一个持续部署平台 ([Source Code](https://github.com/drone/drone)) `Apache` `Go`
  * [Factor](http://www.factor.io/) - 类似IFTTT (if-this-then-that) for Dev and DevOps. ([Source Code](https://github.com/factor-io/factor)) `MIT` `Ruby`
  * [Jenkins](https://jenkins-ci.org/) - 大名鼎鼎ci服务 ([Source Code](https://github.com/jenkinsci/jenkins/)) `MIT` `Java`
  * [PHPCI](https://www.phptesting.org/) - php的ci工具. ([Source Code](https://github.com/block8/phpci)) `BSD` `PHP`
  * [Strider](http://strider-cd.github.io/) - cd ci工具 ([Source Code](https://github.com/Strider-CD/strider)) `BSD` `Nodejs`


### API Management api管理

 * [DreamFactory](https://www.dreamfactory.com/) - 转变sql结构数据到restful api ([Source Code](https://github.com/dreamfactorysoftware/dreamfactory)) `Apache` `PHP`
 * [Endpoint](https://github.com/LINKIWI/endpoint/) - 超级简单的构造httpapi的数据，返回静态json数据，可以进行测试webhook和客户端库 `MIT` `Nodejs`
 * [Fusio](http://www.fusio-project.org/) - 构建管理 REST APIs. ([Demo](http://fusio-project.org/demo), [Source Code](https://github.com/apioo/fusio)) `AGPLv3` `PHP`
 * [Hapttic](https://github.com/jsoendermann/hapttic) - Simple HTTP server that 转发所有请求到shell脚本 `Apache` `Go`
 * [Para](http://www.paraio.org) - 灵活模块快的后端架构，为对象存储，api开发和认证 ([Source Code](https://github.com/erudika/para)) `Apache` `Java`


### Documentation Generators 文档生成器

See also [Static site generators](#static-site-generators)

  * [Docstore](http://haldean.org/) - 静态文档主机，不需要服务端处理，文档变化时不需要处理 ，clone库，添加文章到text目录 ([Source Code](https://github.com/haldean/docstore)) `BSD` `Javascript`
  * [Flatdoc](http://ricostacruz.com/flatdoc/) - 小型js文件从md获取选染成完全的页面  `MIT` `Javascript`
  * [markdown-tree](https://github.com/mil/markdown-tree) - 提供md文件的树形架构  `MIT` `Ruby`
  * [Read the Docs](https://docs.readthedocs.org/en/latest/install.html) - git管理的文档. ([Demo](https://readthedocs.org/projects/), [Source Code](https://github.com/rtfd/readthedocs.org)) `MIT` `Python`

### Localization 本地化

  * [Parrot](http://anthonynsimon.com/parrot.github.io/) - Go and Angular 2部署的本地化管理工具 ([Source Code](https://github.com/anthonynsimon/parrot)) `MIT` `Go`
  * [Pootle](http://pootle.translatehouse.org) - 在线翻译和本地化工具. ([Source Code](https://github.com/translate/pootle)) `GPLv3` `Python`
  * [Weblate](https://weblate.org) - 基于web的翻译工具，紧版本控制集成 ([Demo](https://demo.weblate.org), [Source Code](https://github.com/WeblateOrg/weblate)) `GPLv3` `Python`
  * [Zanata](http://zanata.org) - 基于web的翻译平台，内容管理器和管理本地化项目 ([Source Code](https://github.com/zanata/zanata-platform)) `GPLv2` `Java`

## Static site generators 静态网站生成

**[`^        back to top        ^`](#)**

See https://staticsitegenerators.net and https://www.staticgen.com


## Task management/To-do lists 任务管理

**[`^        back to top        ^`](#)**

*See also [Project Management](#project-management) and [Ticketing](#ticketing).*

  * [Crepido](https://github.com/arshad/crepido) - 从md文件生成看板. `MIT` `Nodejs`
  * [Kanboard](http://kanboard.net/) - A simple and open source visual task board. ([Source Code](https://github.com/kanboard/kanboard)) `MIT` `PHP`
  * [Wheatbin](http://wheatbin.com/) - 从Law of the Harvest得到的看板方法管理 . ([Source Code](https://github.com/wheatbin/wheatbin)) `MIT` `PHP`
  * [myTinyTodo](http://www.mytinytodo.net/) - 管理todolist  Uses PHP, jQuery, SQLite/MySQL. GTD compliant. `GPLv2` `PHP`
  * [omgnata](https://github.com/chr15m/omgnata) - 移动端友好的todolist([Demo](https://chr15m.github.io/omgnata/)) `GPLv3` `ClojureScript`
  * [PHP Task/Todo list](https://github.com/lgg/tasks.php) - json文件保存的todo list `MIT` `PHP`
  * [Restyaboard](http://restya.com/board/) - 类似Trello的看板 ([Demo](http://restya.com/board/demo.html), [Source Code](https://github.com/RestyaPlatform/board)) `OSLv3` `PHP`
  * [scrumblr](http://scrumblr.ca/) - 在线协同 Scrum Tool使用websocket 。Node.js, jQuery, and CSS3. ([Source Code](https://github.com/ocdtrekkie/scrumblr/tree/sandstorm)) `GPLv3` `Nodejs`
  * [TaskBoard](http://taskboard.matthewross.me/) - 基于kanban的app，跟踪待办事项 ([Source Code](https://github.com/kiswa/TaskBoard)) `MIT` `PHP`
  * [Taskfreak](http://www.taskfreak.com/original) - 简单高效的任务管理器 ([Demo](http://demo.taskfreak.com/)) `GPLv3` `PHP`
  * [Tasks](https://projects.miguelpiedrafita.com/Tasks/) - 简单任务管理  ([Demo](https://demo.miguelpiedrafita.com/tasks/), ([Source Code](https://github.com/m1guelpf/tasks)) `MPLv2` `PHP`
  * [Tasks](https://github.com/thewhitetulip/Tasks) - 待办list `MIT` `Go`
  * [tasks.php](https://github.com/RaymiiOrg/tasks.php) - A simple task/todo list manager. `MIT` `PHP`
  * [Taskwarrior](https://taskwarrior.org/) - Taskwarrior 命令行管理任务([Source Code](https://taskwarrior.org/download/#git)) `MIT` `C++`
  * [Tinyissue](https://github.com/satrun77/tinyissue) - 团队issue跟踪 `MIT` `PHP`
  * [todo](https://github.com/prologic/todo) - todo管理. ([Demo](https://todo.mills.io)) `MIT` `Go`
  * [Tracks](http://www.getontracks.org/) - A web-based application to help you implement David Allen’s [Getting Things Done™](https://en.wikipedia.org/wiki/Getting_Things_Done) methodology. ([Source Code](https://github.com/TracksApp/tracks)) `GPLv2` `Ruby`
  * [Volition](https://www.usevolition.com) - 固执己见的任务工具. ([Source Code](https://github.com/garrettqmartin8/volition)) `MIT` `Ruby`
  * [Wekan](https://wekan.github.io/) - 开源Trello kanban. ([Demo](https://oasis.sandstorm.io/appdemo/m86q05rdvj14yvn78ghaxynqz7u2svw6rnttptxx49g1785cdv1h), [Source Code](https://github.com/wekan/wekan)) `MIT` `Nodejs`


## Ticketing 任务跟踪管理

**[`^        back to top        ^`](#)**

*See also [Task management/To-do lists](#task-managementto-do-lists) and [Project Management](#project-management)*

  * [Brimir](https://getbrimir.com/) - Simple and clean open-source ticket manager written in Ruby on Rails. ([Source Code](https://github.com/ivaldi/brimir)) `AGPLv3` `Ruby`
  * [Bugzilla](https://www.bugzilla.org/) - General-purpose bugtracker and testing tool originally developed and used by the Mozilla project. `MPLv2` `Perl`
  * [Bumpy Booby](http://bumpy-booby.derivoile.fr/) - A simple, responsive and highly customizable PHP bug tracking system. ([Source Code](https://github.com/piero-la-lune/Bumpy-Booby)) `MIT` `PHP`
  * [Cerb](http://www.cerberusweb.com/) - Group-based e-mail management project. ([Source Code](https://github.com/wgm/cerb)) `DPL` `PHP`
  * [Coordino](http://coordino.com/) - Open Source question & answer system on top of CakePHP. ([Source Code](https://github.com/Datawalke/Coordino)) `MIT` `PHP`
  * [Deskulu](https://github.com/Taskulu/deskulu) - Opensource helpdesk and ticketing system based on Drupal 7. ([Demo](https://help.taskulu.com)) `GPLv2` `PHP`
  * [DiamanteDesk](http://diamantedesk.com/) - DiamanteDesk is FREE Open Source easy-to-use help-desk solution. ([Demo](http://diamantedesk.com/demo/), [Source Code](https://github.com/eltrino/diamantedesk-application)) `OSLv3` `PHP`
  * [Flyspray](http://www.flyspray.org/) - Uncomplicated, web-based bug tracking system. ([Source Code](https://github.com/Flyspray/flyspray)) `GPLv2` `PHP`
  * [HuBoard](https://github.com/huboard/huboard) `⚠` - Instant project management for your GitHub issues (Connects directly GitHub API). `MIT` `Ruby`
  * [MantisBT](https://www.mantisbt.org/) - Self hosted bug tracker, fits best for software development. ([Demo](https://www.mantisbt.org/bugs/my_view_page.php)), ([Source Code](https://github.com/mantisbt/mantisbt)) `GPLv2` `PHP`
  * [osTicket](http://osticket.com/) -  Manage, organize and archive all your support requests and responses in one place. ([Source Code](https://github.com/osTicket/osTicket)) `GPLv2` `PHP`
  * [OTRS](http://www.otrs.com/) - Trouble ticket system for assigning tickets to incoming queries and tracking further communications. ([Source Code](https://github.com/OTRS/otrs)) `AGPLv3` `Perl`
  * [Request Tracker](https://www.bestpractical.com/rt/) -  An enterprise-grade issue tracking system. ([Source Code](https://github.com/bestpractical/rt)) `GPLv2` `Perl`
  * [TheBugGenie](http://www.thebuggenie.org) - Ticket system with extensive user rights system. ([Source Code](https://github.com/thebuggenie/thebuggenie)) `MPLv2` `PHP`
  * [Zammad](https://zammad.org/) - Easy to use but powerful open-source support & ticketing system. ([Source Code](https://github.com/zammad/zammad)) `AGPLv3` `Ruby`


## URL Shorteners 短地址生成

**[`^        back to top        ^`](#)**

  * [Link-shortener-bot](https://github.com/tommyku/link-shortener-front-end) `⚠` - Telegram Bot短地址生成器 ([Demo](http://t.me/GiveMeShortLinkBot)) `MIT` `ruby`
  * [Linkr](https://linkrapp.com) - 快速短连接生成. ([Demo](https://demo.linkrapp.com), [Source Code](https://github.com/LINKIWI/linkr)) `MIT` `Python/Nodejs`
  * [Lstu](https://github.com/ldidry/lstu) - _Let's SHorten That Url_ - 轻量短地址生成. `WTFPL` `Perl`
  * [Nimbus](https://github.com/ethanal/nimbus) - 短地址生成，文件分享，在mac上可以拖拽完成 . `MIT` `Python`
  * [Polr](https://project.polr.me/) - 现代，微小，模块化短地址生成  ([Source Code](https://github.com/Cydrobolt/polr)) `GPLv2` `PHP`
  * [shorturl](https://github.com/prologic/shorturl) - tiny短地址生成 ([Demo](https://url.mills.io)) `MIT` `Go`
  * [shuri](https://github.com/pips-/shuri) - . `MIT` `PHP`
  * [url-shortener](https://github.com/cagataycali/url-shortener) `⚠` - 支持emoji and AI powered. `MIT` `Nodejs`
  * [YOURLS](http://yourls.org/) - 功能丰富. ([Source Code](https://github.com/YOURLS/YOURLS/)) `MIT` `PHP`


## VPN

**[`^        back to top        ^`](#)**

See https://github.com/n1trux/awesome-sysadmin#vpn


## Web servers

**[`^        back to top        ^`](#)**

See https://github.com/n1trux/awesome-sysadmin#web


## Wikis

**[`^        back to top        ^`](#)**

See also [Documentation Generators](#documentation-generators), [Wikimatrix](http://www.wikimatrix.org/), [Wiki Engines on WikiIndex](http://wikiindex.org/Category:Wiki_Engine), [List of wiki software on wikipedia](https://en.wikipedia.org/wiki/List_of_wiki_software), [Comparison of wiki software on wikipedia](https://en.wikipedia.org/wiki/Comparison_of_wiki_software).

  * [Blazekiss](http://projet.idleman.fr/blazekiss/) - BlazeKiss is a KISS-based wiki (Keep It Simple, Stupid) - 简单，功能完善是第一位. ([Source Code](https://github.com/ldleman/blazekiss)) `GPLv3` `PHP`
  * [BookStack](https://www.bookstackapp.com/) - 组织，存储信息 ([Demo](https://www.bookstackapp.com/#demo), [Source Code](https://github.com/ssddanbrown/BookStack)) `MIT` `PHP`
  * [django-wiki](https://github.com/django-wiki/django-wiki) - 一个wiki ([Demo](https://demo.django.wiki/)) `GPLv3` `Python`
  * [Documize](https://documize.com) - 具有workflow功能. ([Source Code](https://github.com/documize/community)) `AGPLv3` `Go`
  * [Dokuwiki](https://www.dokuwiki.org/DokuWiki) - 一个简单的wiki ([Source Code](https://github.com/splitbrain/dokuwiki)) `GPLv2` `PHP`
  * [Gitit](https://github.com/jgm/gitit) - 存储页面和上传文件  `GPLv2` `Haskell`
  * [Gollum](https://github.com/gollum/gollum) - 简单支持git的wiki . `MIT` `Ruby`
  * [jingo](https://github.com/claudioc/jingo) - 支持git的wiki  ([Demo](http://jingo.cica.li:6067/wiki/home), [Source Code](https://github.com/claudioc/jingo)) `MIT` `Nodejs`
  * [Mediawiki](https://www.mediawiki.org/wiki/MediaWiki) - 免费开源的wiki  ([Source Code](https://phabricator.wikimedia.org/diffusion/MW/)) `GPLv2` `PHP`
  * [MoinMoin](https://moinmo.in/) - 高级易用的wiki  ([Source Code](http://hg.moinmo.in/moin)) `GPLv2` `Python`
  * [Olelo](https://github.com/minad/olelo) - 支持许多标记样式 ，具可扩展和自定义的架构  ([Demo](http://gitwiki.org/)) `MIT` `Ruby`
  * [Pepperminty Wiki](https://github.com/sbrl/Pepperminty-Wiki/) - 支持md的wiki  ([Demo](https://starbeamrainbowlabs.com/labs/peppermint/build/)) `MPLv2` `PHP`
  * [PineDocs](https://github.com/xy2z/PineDocs) - 浏览文件  `GPLv3` `PHP`
  * [PmWiki](http://www.pmwiki.org) - 协同 `GPLv3` `PHP`
  * [Raneto](http://raneto.com/) - 开源知识平台. `MIT` `Nodejs`
  * [Realms](http://realms.io/) - git作为后端的wiki平台. ([Source Code](https://github.com/scragg0x/realms-wiki)) `GPLv2` `Python`
  * [TiddlyWiki](http://tiddlywiki.com/) - 可重用的非线性个人网络笔记本 ([Source Code](https://github.com/Jermolene/TiddlyWiki5)) `BSD` `Nodejs`
  * [Tiki](https://tiki.org) - cmd wiki ([Demo](https://tiki.org/Demo), [Source Code](https://sourceforge.net/p/tikiwiki/code/HEAD/tree/)) `LGPLv2` `PHP`
  * [TWiki](http://twiki.org/) - 结构化的wiki应用. ([Demo](http://twiki.org/cgi-bin/view/Sandbox/WebHome), [Source Code](http://svn.twiki.org/svn/twiki/)) `GPL` `Perl`
  * [wiki](https://github.com/prologic/wiki) - md的wiki引擎([Demo](https://wiki.mills.io)) `MIT` `Go`
  * [Wiki.js](https://wiki.js.org/) - 支持git md  ([Demo](https://docs.requarks.io/wiki)) `AGPLv3` `Nodejs`
  * [Wikifeat](https://github.com/rhinoman/wikifeat) -  `BSD` `GO`
  * [WiKiss](http://wikiss.tuxfamily.org/) - A Wiki, simple to use and install. ([Source Code](https://svnweb.tuxfamily.org/listing.php?repname=wikiss/svn&path=%2F&sc=0)) `GPLv2` `PHP`
  * [XWiki](http://www.xwiki.org) - 第二代wiki. ([Demo](http://playground.xwiki.org), [Source Code](https://github.com/xwiki/xwiki-platform)) `LGPLv2` `Java`


## Self-hosting Solutions 自部署方案

**[`^        back to top        ^`](#)**

  * [Cloudron](https://cloudron.io) - Effortlessly self-host web apps on your server. ([Source Code](https://git.cloudron.io/groups/cloudron)) `AGPLv3` `Nodejs/Docker`
  * [DietPi](http://dietpi.com/) - Minimal Debian OS optimized for single-board computers, which allows you to easily install and manage several services for selfhosting at home. ([Source Code](https://github.com/Fourdee/DietPi)) `GPLv2` `Shell`
  * [DPlatform](https://dfabric.github.io/DPlatform-ShellCore/) - Deploy self-hosted apps easily: simple, bloat-free, independent installation. ([Source Code](https://github.com/j8r/DPlatform)) `MIT` `Shell`
  * [FreedomBone](https://freedombone.net/) - Home server configuration based on Debian. ([Source Code](https://github.com/bashrc/freedombone)) `AGPLv3` `Shell`
  * [FreedomBox](https://wiki.debian.org/FreedomBox) - A community project to develop, design and promote personal servers running free software for private, personal, communications. `GPLv3` `Python/Other`
  * [FreeNAS](https://www.freenas.org/) - Network-attached storage (NAS) software based on FreeBSD and the OpenZFS file system. Support for SMB, AFP, NFS, iSCSI, SSH, rsync and FTP/TFTP protocols. Advanced features include full-disk encryption and plug-ins. ([Source Code](https://github.com/freenas/freenas)) `BSD` `Python/Other`
  * [OpenMediaVault](http://www.openmediavault.org/) - OpenMediaVault is the next generation network attached storage (NAS) solution based on Debian Linux. It contains services like SSH, (S)FTP, SMB/CIFS, DAAP media server, RSync, BitTorrent client and many more. ([Source Code](https://github.com/openmediavault/openmediavault)) `GPLv3` `PHP`
  * [Piratebox](https://piratebox.cc/start) - A DIY anonymous offline file-sharing and communications system built with free software and inexpensive off-the-shelf hardware. ([Source Code](https://github.com/PirateBox-Dev)). `GPLv3` `Python/Other`
  * [Puffin](http://puffin.rocks/) - Lightweight webapp catalog based on containers, with user interface à la mobile app store. ([Demo](http://puffin.rocks/), [Source Code](https://github.com/puffinrocks/puffin)) `AGPLv3` `Python/Docker`
  * [Sandstorm](https://sandstorm.io/) - Personal server for running self-hosted apps easily and securely. ([Demo](https://demo.sandstorm.io/), [Source Code](https://github.com/sandstorm-io/sandstorm)) `Apache` `C++/Other`
  * [sovereign](https://github.com/sovereign/sovereign) - A set of Ansible playbooks to build and maintain your own private cloud: email, calendar, contacts, file sync, IRC bouncer, VPN, and more. `GPLv3` `YAML/Other`
  * [Syncloud](http://syncloud.org/) - Your own online file storage, social network or email server. ([Source Code](https://github.com/syncloud/platform)) `GPLv3/Other` `Python/Other`
  * [UBOS](http://ubos.net/) - Linux distro that runs on indie boxes (personal servers and IoT devices). Single-command installation and management of apps - Jenkins, Mediawiki, Owncloud, WordPress, etc., - and other [features](http://ubos.net/about/). `GPLv3` `Perl/Other`
  * [WikiSuite](http://WikiSuite.org) - The most comprehensive and integrated Free / Libre / Open Source software suite ever developed. ([Source Code](http://wikisuite.org/Source)) `Multiple` `ClearOS`
  * [YunoHost](https://yunohost.org/) - A server operating system aiming to make self-hosting accessible to everyone. ([Demo](https://yunohost.org/#/try), [Source Code](https://github.com/YunoHost)) `AGPLv3` `Python/Other`

<!-- END SOFTWARE LIST -->

-------------------------------------------------------

## List of Licenses

**[`^        back to top        ^`](#)**

 * ` ⚠ ` - Depends on a third party network service
 * `AAL` - [Attribution Assurance License](https://opensource.org/licenses/AAL)
 * `AGPLv3` - [GNU Affero General Public License 3.0](https://www.gnu.org/licenses/agpl-3.0)
 * `Apache` - [Apache, Version 2.0](http://www.apache.org/licenses/)
 * `APSLv2` - [Apple Public Source License, Version 2.0](https://opensource.org/licenses/APSL-2.0)
 * `ARTv2` - [Artistic License Version 2.0](http://opensource.org/licenses/Artistic-2.0)
 * `Beerware` - [Beerware License](https://spdx.org/licenses/Beerware.html)
 * `BSD` - [FreeBSD License](https://www.freebsd.org/copyright/license.html)
 * `BSD` - [BSD 2-Clause](https://opensource.org/licenses/BSD-3-Clause) or [BSD 3-Clause](https://opensource.org/licenses/BSD-3-Clause) license
 * `CCBYSA`  - [Creative Commons Attribution-ShareAlike International License](https://creativecommons.org/licenses/by-sa/4.0/)
 * `CC0` - [Public Domain](https://creativecommons.org/about/cc0/)
 * `CDDL` - [Common Development and Distribution License](https://opensource.org/licenses/CDDL-1.0)
 * `CeCILL-B` - [CEA CNRS INRIA Logiciel Libre](http://www.cecill.info/licences/Licence_CeCILL-B_V1-en.txt)
 * `CPALv1` - [Common Public Attribution License Version 1.0](http://opensource.org/licenses/CPAL-1.0)
 * `DPL` - [Devblocks Public License 1.0](http://www.cerberusweb.com/license)
 * `ECLv2` - [Educational Community License, Version 2.0 ](http://opensource.org/licenses/ECL-2.0)
 * `EPLv1` - [Eclipse Public License, Version 1.0](https://www.eclipse.org/legal/epl-v10.html)
 * `Fair` - [Fair License](http://fairlicense.org/)
 * `GPL` - [GNU General Public License](https://www.gnu.org/licenses/gpl-1.0)
 * `GPLv2` - [GNU General Public License 2.0](https://www.gnu.org/licenses/old-licenses/gpl-2.0.en.html)
 * `GPLv3` - [GNU General Public License 3.0](http://www.gnu.org/licenses/gpl-3.0.en.html)
 * `IPL` - [IBM Public License](https://opensource.org/licenses/IPL-1.0)
 * `ISC` - [Internet Software Consortium License](https://www.isc.org/downloads/software-support-policy/isc-license/)
 * `LGPLv2` - [Lesser General Public License 2.1](http://opensource.org/licenses/LGPL-2.1)
 * `LGPLv3` - [Lesser General Public License 3.0](http://opensource.org/licenses/LGPL-3.0)
 * `MIT` - [MIT License](http://opensource.org/licenses/MIT)
 * `MPLv1.1` - [Mozilla Public License Version 1.1](https://www.mozilla.org/media/MPL/1.1/index.txt)
 * `MPLv2` - [Mozilla Public License](https://www.mozilla.org/MPL/2.0/index.txt)
 * `OSLv3` - [Open Software License 3.0](https://opensource.org/licenses/osl-3.0.php)
 * `SENDMAIL` - [Sendmail License](https://www.sendmail.com/pdfs/open_source/sendmail_license.pdf)
 * `Unlicense` - [The Unlicense](http://unlicense.org/)
 * `WTFPL` - [Do What the Fuck You Want to Public License](http://www.wtfpl.net/about/)
 * `Zlib` - [Zlib/libpng License](https://opensource.org/licenses/Zlib)
 * `Zope` - [Zope Public License 2.0](http://opensource.org/licenses/ZPL-2.0)


-------------------------------------------------------

## External links

**[`^        back to top        ^`](#)**

 * [Awesome Selfhosted Chat](https://chat.awesome-selfhosted.com) - A rocket.chat instance setup for the awesome selfhosted community.
 * [Awesome Big Data](https://github.com/onurakpolat/awesome-bigdata) - A curated list of awesome big data frameworks, resources and other awesomeness.
 * [Awesome Sysadmin](https://github.com/n1trux/awesome-sysadmin) - A curated list of amazingly awesome open source sysadmin resources.
 * [PRISM Break](https://prism-break.org/en/), [privacytools.io](https://www.privacytools.io/), [Alternative Internet](https://redecentralize.github.io/alternative-internet/), [Libre Projects](http://libreprojects.net/) - Lists of software aimed at privacy and decentralization (in some form).
 * Dynamic Domain Name services: [Afraid.org](https://freedns.afraid.org/domain/registry/), [Pagekite](https://pagekite.net/)
 * Communities/forums: [/r/selfhosted](https://www.reddit.com/r/selfhosted), [Auto-Hébergement (FR)](http://www.auto-hebergement.fr/)

-------------------------------------------------------

## Contributing

Contributing guidelines can be found [here](.github/CONTRIBUTING.md).

## Authors

The list of authors can be found [here](AUTHORS.md).

## License

This list is under the [Creative Commons Attribution-ShareAlike 3.0 Unported](LICENSE) License.


