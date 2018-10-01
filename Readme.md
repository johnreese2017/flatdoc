# Awesome-Selfhosted-CN

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

## 这是一个可以自建的[自由](https://zh.wikipedia.org/wiki/%E8%87%AA%E7%94%B1%E8%BD%AF%E4%BB%B6)软件和[网络应用](https://zh.wikipedia.org/wiki/%E7%BD%91%E7%BB%9C%E5%BA%94%E7%94%A8%E7%A8%8B%E5%BA%8F)列表。非自由软件在[Non-Free](non-free-CN.md)页面

这是一个可以在本地服务器上搭建的自由应用列表,准备合并[awesome-selfhosted](https://github.com/Kickball/awesome-selfhosted)和[awesome-sys-admin](https://github.com/n1trux/awesome-sysadmin)并且每个项目增加一个文档快捷方式快速部署。不免费列表点击[Non-Free-CN](non-free-CN.md)  个人推荐应用（注重隐私）查看[Recommend](Selfhosted-Recommend.md)

查看 [贡献列表](.github/CONTRIBUTING.md).

--------------------

- 软件列表
  - [数据分析](#数据分析)
  - [Archiving and Digital Preservation (DP)](#archiving-and-digital-preservation-dp)
  - [Automation](#automation)
  - [Blogging Platforms](#blogging-platforms)
  - [Bookmarks and Link Sharing](#bookmarks-and-link-sharing)
  - [Calendaring and Contacts Management](#calendaring-and-contacts-management)
  - [Communication systems](#communication-systems)
    - [Custom communication systems](#custom-communication-systems)
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
  - [Document Management](#document-management)
  - [E-books and Integrated Library Systems (ILS)](#e-books-and-integrated-library-systems-ils)
  - [Federated Identity/Authentication](#federated-identityauthentication)
  - [Feed Readers](#feed-readers)
  - [File Sharing and Synchronization](#file-sharing-and-synchronization)
    - [Distributed filesystems](#distributed-filesystems)
    - [File transfer/synchronization](#file-transfersynchronization)
    - [Peer-to-peer filesharing](#peer-to-peer-filesharing)
    - [Object storage/file servers](#object-storagefile-servers)
    - [Single-click/drag-n-drop upload](#single-clickdrag-n-drop-upload)
    - [Web based file managers](#web-based-file-managers)
  - [Games](#games)
  - [Gateways](#gateways)
  - [Groupware](#groupware)
  - [Human Resources Management (HRM)](#human-resources-management-hrm)
  - [Learning and Courses](#learning-and-courses)
  - [Maps and Global Positioning System (GPS)](#maps-and-global-positioning-system-gps)
  - [Media Streaming](#media-streaming)
    - [Multimedia Streaming](#multimedia-streaming)
    - [Audio Streaming](#audio-streaming)
    - [Video Streaming](#video-streaming)
  - [Misc/Other](#miscother)
  - [Money, Budgeting and Management](#money-budgeting-and-management)
  - [Monitoring](#monitoring)
  - [Note-taking and Editors](#note-taking-and-editors)
  - [Office Suites](#office-suites)
  - [Password Managers](#password-managers)
  - [Pastebins](#pastebins)
  - [Personal Dashboards](#personal-dashboards)
  - [Photo and Video Galleries](#photo-and-video-galleries)
  - [Polls and Events](#polls-and-events)
  - [Proxy](#proxy)
  - [Read it Later Lists](#read-it-later-lists)
  - [Resource Planning](#resource-planning)
    - [Enterprise Resource Planning](#enterprise-resource-planning)
    - [Kitchen Resource Planning](#kitchen-resource-planning)
  - [Search Engines](#search-engines)
  - [Software Development](#software-development)
    - [Project Management](#project-management)
    - [Bug Trackers](#bug-trackers)
    - [IDE/Tools](#idetools)
    - [Continuous Integration](#continuous-integration)
    - [FaaS/Serverless](#faas-serverless)
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

--------------------

<!-- BEGIN SOFTWARE LIST -->

## 数据分析
针对个人的数据分析/面板, 参考 [Personal Dashboards](https://github.com/Kickball/awesome-selfhosted#personal-dashboards)

**[`^        返回顶部        ^`](#)**

_网页分析_

- [AWStats](http://www.awstats.org/) - 生成图形化的网页，流媒体服务，FTP 或者邮件服务器的分析。 ([源码](https://github.com/eldy/awstats),[演示站](https://www.nltechno.com/awstats/awstats.pl?config=destailleur.fr),[文档](http://www.awstats.org/docs/index.html)) `GPL-3.0` `Perl`
- [Countly](https://count.ly) - 实时移动和网络平台数据分析，应用崩溃报告并及时推送信息的一个平台。 ([源码](https://github.com/countly),[文档](https://resources.count.ly/)) `AGPL-3.0` `Javascript`
- [Druid](http://druid.io/) - 分布式的以列为中心的实时数据分析站点。([源码](https://github.com/druid-io/druid/),[文档](http://druid.io/docs/latest/design/index.html)) `Apache-2.0` `Java`
- [Fathom Analytics](https://usefathom.com) - 简单，值得信任的网站分析应用。 ([源码](https://github.com/usefathom/fathom),[演示站](https://stats.usefathom.com/),[文档](https://github.com/usefathom/fathom/wiki)) `MIT` `Go`
- [GoAccess](http://goaccess.io/) - Real-time web log analyzer and interactive viewer that runs in a terminal. ([源码](https://github.com/allinurl/goaccess),[演示站](http://rt.goaccess.io/?20180921163458),[文档](https://goaccess.io/man)) `GPL-2.0` `C`
- [Hastic](https://hastic.io) - Hackable time series pattern recognition tool with UI for Grafana. ([Source Code](https://github.com/hastic)) `Apache-2.0` `Python/Nodejs`
- [Matomo](https://matomo.org/) - Leading open-source analytics platform that gives you more than just powerful analytics, formerly known as Piwik. ([Source Code](https://github.com/matomo-org/)) `GPL-3.0` `PHP`
- [Open Web Analytics](http://www.openwebanalytics.com/) - Google Analytics and Piwik alternative. ([Source Code](https://github.com/padams/Open-Web-Analytics/)) `GPL-2.0` `PHP`
- [Rakam](https://rakam.io/) - Custom analytics platform that allows you to create your own analytics services. Integrate with any data source (web, mobile, IoT etc.), analyze data with SQL and create dashboards. ([Source Code](https://github.com/rakam-io/rakam)) `Apache-2.0` `Java`
- [Serposcope](https://serposcope.serphacker.com/) - Serposcope is a free and open-source rank tracker to monitor websites ranking in Google and improve your SEO performances. ([Source Code](https://github.com/serphacker/serposcope)) `MIT` `Java`
- [Snowplow](http://snowplowanalytics.com/) - Have every single event, from your websites, mobile apps, desktop applications and server-side systems, stored in your own data warehouse and available to action in real-time. ([Source Code](https://github.com/snowplow/)) `Apache-2.0` `Scala`
- [Suet](https://suet.co/) `⚠` - Detailed analytics and reporting for your Mailgun transactional emails. ([Source Code](https://github.com/kehers/suet)) `GPL-3.0` `Nodejs`

_Business Intelligence_

- [Metabase](http://www.metabase.com/) - Simple Dashboarding and GUI Query tool, Nightly Emails and Slack Integration w/ PostgreSQL, MySQL, Redshift and other DBs. ([Source Code](https://github.com/metabase/metabase)) `AGPL-3.0` `Clojure`
- [Redash](http://redash.io) - connect to over 18 types of databases (SQL and "NoSQL"), query your data, visualize it and create dashboards. Everything has a URL that can be shared. Slack and HipChat integration. ([Demo](https://demo.redash.io), [Source Code](https://github.com/getredash/redash)) `BSD-2-Clause` `Python`
- [Superset](http://superset.apache.org/) - Modern, enterprise-ready business intelligence web application. ([Source Code](https://github.com/apache/incubator-superset)) `Apache-2.0` `Python`

## Archiving and Digital Preservation (DP)

**[`^        back to top        ^`](#)**

Some [Content Management System](#content-management-systems-cms) solutions also feature archiving and digital preservation.

- [Access to Memory (AtoM)](https://www.accesstomemory.org/) - Web-based, open source application for standards-based archival description and access in a multilingual, multi-repository environment. ([Demo](https://demo.accesstomemory.org/), [Source Code](https://github.com/artefactual/atom)) `PHP` `AGPL-3.0-only`
- [Archivematica](https://www.archivematica.org/) - Mature digital preservation system designed to maintain standards-based, long-term access to collections of digital objects. ([Demo](http://sandbox.archivematica.org/administration/accounts/login/), [Source Code](https://github.com/artefactual/archivematica)) `Python` `AGPL-3.0-only`
- [ArchivesSpace](https://archivesspace.org/) - Archives information management application for managing and providing Web access to archives, manuscripts and digital objects. ([Demo](https://archivesspace.org/application/demo/), [Source Code](https://github.com/archivesspace/archivesspace)) `Ruby` `ECL-2.0`
- [Collective Access: Providence](http://collectiveaccess.org/) - Highly configurable Web-based framework for management, description, and discovery of digital and physical collections supporting a variety of metadata standards, data types, and media formats. ([Source Code](https://github.com/collectiveaccess/providence)) `PHP` `GPL-3.0-only`

## Automation

**[`^        back to top        ^`](#)**

- [Alltube](http://www.alltubedownload.net) - Web interface for [youtube-dl](https://github.com/rg3/youtube-dl), a program to download videos and audio from [more than 100 websites](https://rg3.github.io/youtube-dl/supportedsites.html). ([Demo](http://www.alltubedownload.net), [Source Code](https://github.com/Rudloff/alltube)) `GPL-3.0` `PHP`
- [AmIUnique](https://amiunique.org/) - Learn how identifiable you are on the Internet (browser fingerprinting tool). ([Source Code](https://github.com/DIVERSIFY-project/amiunique)) `MIT` `Java`
- [Beehive](https://github.com/muesli/beehive) - Flexible event and agent system, which allows you to create your own agents that perform automated tasks triggered by events and filters. `AGPL-3.0` `Go`
- [CampaignChain](https://www.campaignchain.com/) `⚠` - A marketing hub allowing to schedule posts on social media (a la Hootsuite+Buffer) and combine them with newsletter campaigns. ([Source Code](https://github.com/CampaignChain/campaignchain/tree/1.0)) `Apache-2.0` `PHP`
- [CouchPotato](https://couchpota.to/) - CouchPotato is an automatic Video Library Manager for Movies. Automatic torrent/nzb searching, downloading, and processing at the qualities you want. ([Source Code](https://github.com/CouchPotato/CouchPotatoServer/)) `GPL-3.0` `Python`
- [Episodes](https://github.com/guptachetan1997/Episodes) - `⚠` Self Hosted TV show Episode tracker and recommender built using django, bootstrap4. `MIT` `Python`
- [feedmixer](https://github.com/cristoper/feedmixer) - FeedMixer is a WSGI (Python3) micro web service which takes a list of feed URLs and returns a new feed consisting of the most recent n entries from each given feed(Returns Atom, RSS, or JSON). ([Demo](https://mretc.net/feedmixer/json?f=http://hnrss.org/newest&f=http://americancynic.net/atom.xml&n=1)) `WTFPL` `Python`
- [FHEM](https://fhem.de/fhem.html) - FHEM is used to automate common tasks in the household like switching lamps and heating. It can also be used to log events like temperature or power consumption. You can control it via web or smartphone frontends, telnet or TCP/IP directly. ([Source Code](https://svn.fhem.de/trac)) `GPL-3.0` `Perl`
- [Gekko](https://gekko.wizb.it/) - Gekko is a Bitcoin TA trading and backtesting bot which support multiple exchanges and cryptocurrencies. ([Source Code](https://github.com/askmike/gekko)) `MIT` `Nodejs`
- [Headphones](https://github.com/rembo10/headphones) - Automated music downloader for NZB and Torrent, written in Python. It supports SABnzbd, NZBget, Transmission, µTorrent, Deluge and Blackhole. `GPL-3.0` `Python`
- [Healthchecks](https://healthchecks.io/) - Django app which listens for pings and sends alerts when pings are late. ([Source Code](https://github.com/healthchecks/healthchecks)) `BSD-3-Clause` `Python`
- [Home Assistant](https://home-assistant.io/) - Open-source home automation platform. ([Demo](https://home-assistant.io/demo/), [Source Code](https://github.com/home-assistant/home-assistant)) `MIT` `Python`
- [homebank-converter](https://github.com/Binnette/homebank-converter) - Web app to convert an export bank file to compatible Homebank csv. ([Demo](http://binnette.github.io/homebank-converter/)) `AGPL-3.0` `HTML5`
- [Huginn](https://github.com/cantino/huginn) - Allows you to build agents that monitor and act on your behalf. `MIT` `Ruby`
- [Http2pic](https://http2pic.haschek.at/) - Website screenshots/renderer. It uses the wkhtmltox to render websites with various options. ([Source Code](https://github.com/chrisiaut/http2pic)) `Apache 2.0` `PHP/Javascript`
- [Kibitzr](https://kibitzr.github.io) - Lightweight personal web assistant with powerful integrations. ([Source Code](https://github.com/kibitzr/kibitzr/)) `MIT` `Python`
- [LazyLibrarian](https://github.com/DobyTang/LazyLibrarian) `⚠` - LazyLibrarian is a program to follow authors and grab metadata for all your digital reading needs. It uses a combination of Goodreads Librarything and optionally GoogleBooks as sources for author info and book info. `GPL-3.0` `Python`
- [Lidarr](https://lidarr.audio/) - Lidarr is a music collection manager for Usenet and BitTorrent users. ([Source Code](https://github.com/Lidarr/Lidarr)) `GPL-3.0` `C#`
- [Medusa](https://github.com/pymedusa/SickRage) - Automatic Video Library Manager for TV Shows. It watches for new episodes of your favorite shows, and when they are posted it does its magic. `GPL-3.0` `Python`
- [Node RED](http://nodered.org/) - Browser-based flow editor that helps you wiring hardware devices, APIs and online services to create IoT solutions. ([Source Code](https://github.com/node-red/node-red)) `Apache-2.0` `Nodejs`
- [openHAB](http://www.openhab.org) - Vendor and technology agnostic open source software for home automation. ([Source Code](https://github.com/openhab/openhab)) `EPL-1.0` `Java`
- [PolitePol](https://github.com/taroved/pol) - Online tool for creation of RSS feeds for any web page. ([Demo](http://politepol.com)) `MIT` `Python`
- [Poffer](http://poffer.gabinaureche.com) `⚠` - Tool that makes it easier to share the content you like thanks to Pocket+Buffer. ([Source Code](https://github.com/Zhouzi/Poffer)) `MIT` `Nodejs`
- [pyLoad](https://pyload.net/) - Lightweight, customizable and remotely manageable downloader for 1-click-hosting sites like rapidshare.com or uploaded.to. ([Source Code](https://github.com/pyload/pyload)) `GPL-3.0` `Python`
- [Radarr](https://radarr.video/) - Radarr is an independent fork of Sonarr reworked for automatically downloading movies via Usenet and BitTorrent, à la Couchpotato. ([Source Code](https://github.com/Radarr/Radarr)) `GPL-3.0` `C#`
- [RSS-Bridge](https://github.com/sebsauvage/rss-bridge) - rss-bridge is a PHP project capable of generating ATOM feeds for websites which don't have one. `Public domain` `PHP`
- [RSS Merger](https://github.com/taophp/rss-merger) - PHP script which will take multiple RSS / Atom feeds as input and merge them into a single RSS feed. `GPL-2.0` `PHP`
- [SickRage](http://sickrage.github.io/) - SickRage is an automatic Video Library Manager for TV Shows. Automatic torrent/nzb searching, downloading, and processing at the qualities you want. ([Source Code](https://github.com/SickRage/SickRage/)) `GPL-3.0` `Python`
- [Sonarr](https://sonarr.tv/) - Automatic TV Shows downloader and manager for Usenet and BitTorrent. It can grab, sort and rename new episodes and automatically upgrade the quality of files already downloaded when a better quality format becomes available. ([Source Code](https://github.com/Sonarr/Sonarr)) `GPL-3.0` `C#`
- [TriggerHappy](http://trigger-happy.eu/) - Open source clone of IFTTT, a bridge between your internet services. ([Source Code](https://github.com/foxmask/django-th)) `BSD-3-Clause` `Python`
- [WebUI-aria2](https://github.com/ziahamza/webui-aria2) - Interface to interact with the aria2 downloader. Very simple to use, just download and open index.html in any web browser. ([Demo](http://ziahamza.github.io/webui-aria2/)) `MIT` `HTML5`
- [WTFDYUM](https://github.com/jchampemont/WTFDYUM) `⚠` - Why The Fuck Did You Unfollow Me - Find out who stops following you on Twitter. ([Demo](https://www.wtfdyu.me/), [Source Code](https://github.com/jchampemont/WTFDYUM)) `Apache-2.0` `Java`
- [Zenbot 3](https://github.com/carlos8f/zenbot) - Zenbot is a lightweight, extendable, artificially intelligent trading bot for Bitcoin, Ether, Litecoin, and more. `MIT` `Node.js`

## Blogging Platforms

**[`^        back to top        ^`](#)**

See also [Static Site Generators](#static-site-generators), [Content Management Systems](#content-management-systems-cms) and [WeblogMatrix](http://www.weblogmatrix.org/)

- [Anchor CMS](https://anchorcms.com/) - Free, lightweight, faster-than-a-bullet, simple blogging system, made for art–directed posts. ([Source Code](https://github.com/anchorcms/anchor-cms)) `GPL-3.0` `PHP`
- [Antville](https://antville.org) - Free, open source project aimed at the development of a high performance, feature rich weblog hosting software. ([Source Code](https://github.com/antville/antville)) `Apache-2.0` `Javascript`
- [Blogotext](http://lehollandaisvolant.net/blogotext/) - Free blog-engine written in PHP and using SQLite. This offers you both an unmatched simplicity during installation and great performances. ([Source Code](https://github.com/timovn/blogotext)) `MIT` `PHP`
- [Bludit](https://www.bludit.com/) `⚠` - Simple application to build a site or blog in seconds. Bludit uses flat-files (text files in JSON format) to store posts and pages. ([Demo](https://demo.bludit.com/), [Source Code](https://github.com/dignajar/bludit)) `MIT` `PHP`
- [Chyrp Lite](http://chyrplite.net) - Extra-awesome, extra-lightweight blog engine. ([Source Code](https://github.com/xenocrat/chyrp-lite)) `BSD-3-Clause` `PHP`
- [Dante Stories](https://dante-stories.herokuapp.com/) - A self hosted Medium platform built with Ruby on Rails. ([Source Code](https://github.com/michelson/dante-stories)) `MIT` `Ruby`
- [Dotclear](http://dotclear.org/) - Take control over your blog. ([Source Code](https://hg.dotclear.org/dotclear)) `GPL-2.0` `PHP`
- [Formtools](https://formtools.org/) - Powerful, flexible, free and open source PHP/MySQL script to manage your forms and data. ([Source Code](https://github.com/formtools)) `GPL-2.0` `PHP`
- [Ghost](https://ghost.org/) - Just a blogging platform. ([Source Code](https://github.com/TryGhost/Ghost)) `MIT` `Nodejs`
- [Hexo](https://hexo.io/) - Fast, simple and powerful blog framework, powered by Node.js. ([Source Code](https://github.com/hexojs/hexo)) `MIT` `Nodejs`
- [Hotglue](https://hotglue.me/) - Freehand CMS which allows to construct websites directly in a web-browser. It uses flat files for storage and provides an intuitive GUI. ([Demo](https://hotglue.me/demo/), [Source Code](https://github.com/k0a1a/hotglue2)) `GPL-3.0` `PHP`
- [htmly](https://www.htmly.com/) - Databaseless Blogging Platform (Flat-File Blog). ([Demo](https://www.htmly.com/demo/), [Source Code](https://github.com/danpros/htmly)) `GPL-2.0` `PHP`
- [Known](https://withknown.com/) - Single website for all your content. ([Source Code](https://github.com/idno/idno)) `Apache-2.0` `PHP`
- [Noddity](http://noddity.com/) - It's a blog, it's a wiki, it's a fast CMS. ([Source Code](https://github.com/TehShrike/noddity)) `WTFPL` `Nodejs`
- [PluXml](http://www.pluxml.org/) - XML-based blog/CMS platform. ([Source Code](https://github.com/pluxml/PluXml)) `GPL-1.0` `PHP`
- [Postleaf](https://www.postleaf.org/) - Open source blogging platform with inline editing, handlebar templates, and a beautiful user interface. ([Source Code](https://github.com/Postleaf/postleaf)) `MIT` `Nodejs`
- [Solo](http://b3log.org/) - Blogging system written in Java, feel free to create your or your team own blog. ([Demo](http://88250.b3log.org/), [Source Code](https://github.com/b3log/solo)) `Apache-2.0` `Java`
- [WordPress](https://wordpress.org/) - Create a beautiful website or blog. ([Source Code](https://github.com/WordPress/WordPress)) `GPL-2.0` `PHP`

## Bookmarks and Link Sharing

**[`^        back to top        ^`](#)**

- [Bookie](https://github.com/bookieio/Bookie) - Python based delicious.com replacement. `AGPL-3.0` `Python`
- [dyu/bookmarks](https://github.com/dyu/bookmarks) - Single-threaded/process bookmark app powered by leveldb and uWebSockets. Supports importing from Delicious and Chrome. ([Demo](https://dyuproject.com/bookmarks/)) `Apache-2.0` `Java`
- [Firefox Auth Server](https://docs.services.mozilla.com/howtos/run-fxa.html) - This project implements the core server-side API for Firefox Accounts. ([Source Code](https://github.com/mozilla/fxa-auth-server/)) `MPL-2.0` `Nodejs`
  - [Firefox Content Server](https://docs.services.mozilla.com/howtos/run-fxa.html) - Static server that hosts Firefox Account sign up, sign in, email verification, etc. flows. ([Source Code](https://github.com/mozilla/fxa-content-server/)) `MPL-2.0` `Java`
  - [Firefox Sync Server](https://docs.services.mozilla.com/howtos/run-sync-1.5.html) - Sync Firefox bookmarks, passwords, history, tabs, preferences. ([Source Code](https://github.com/mozilla-services/syncserver)) `MPL-2.0` `Python`
- [Geekmarks](https://geekmarks.dmitryfrank.com/) - Personal bookmarking service focused on speed and organization using hierarchical tags. ([Source Code](https://github.com/dimonomid/geekmarks)) `BSD-2-Clause` `Go`
- [golinks](https://github.com/prologic/golinks) - Web application that allows you to create smart bookmarks, commands and aliases by pointing your web browser's default search engine at a running instance. Similar to bunny1 or yubnub. ([Demo](https://search.mills.io)) `MIT` `Go`
- [Lobsters](https://lobste.rs) - Run your own link aggregation site. ([Source Code](https://github.com/jcs/lobsters)) `BSD` `Ruby`
- [No Fuss Bookmarks](http://nofussbm.herokuapp.com/signup.html) - Very simple software and service to store bookmarks especially designed for hackers (that don't need fancy interfaces, but nice API). ([Source Code](https://github.com/mapio/nofussbm)) `GPL-3.0` `Python`
- [Pinry](http://getpinry.com/) - The tiling image board system for people who want to save, tag, and share images, videos, and webpages. ([Source Code](https://github.com/pinry/pinry)) `BSD-2-Clause` `Python`
- [saveto](https://save.duyet.net/) - Open source, home for the best links on the web. ([Source Code](https://github.com/saveto-co/saveto)) `MIT` `Nodejs`
- [SemanticScuttle](http://semanticscuttle.sourceforge.net/) - SemanticScuttle is a social bookmarking tool experimenting with features like structured tags and collaborative tag descriptions. ([Source Code](https://sourceforge.net/p/semanticscuttle/code/ci/master/tree/)) `GPL-2.0` `PHP`
- [Shaarli](https://github.com/shaarli/Shaarli) - Personal, minimalist, super-fast, no-database bookmarking and link sharing platform. ([Demo](https://demo.shaarli.org)) `Zlib` `PHP`
- [Shiori](https://github.com/RadhiFadlillah/shiori) - Simple bookmark manager built with Go. `MIT` `Go`
- [unmark](https://github.com/plainmade/unmark) - Open source to do app for links. `MIT` `PHP`
- [ymarks](https://bitbucket.org/ymarks/ymarks-server) - Keep your browser's bookmarks synchronized without limiting yourself to one provider. `WTFPL` `C`


## Calendaring and Contacts Management

**[`^        back to top        ^`](#)**

Some [Groupware](#groupware) solutions also feature calendar/address book editing and synchronization.

See https://en.wikipedia.org/wiki/Comparison_of_CalDAV_and_CardDAV_implementations

_CalDAV or CardDAV servers_

- [Baïkal](http://sabre.io/baikal/) - Lightweight CalDAV and CardDAV server based on sabre/dav. ([Source Code](https://github.com/sabre-io/Baikal)) `GPL-3.0` `PHP`
- [CalendarServer](https://www.calendarserver.org/) - Apple, Inc.'s standards-compliant server implementing the CalDAV and CardDAV protocols shipped with macOS Server. ([Source Code](https://github.com/apple/ccs-calendarserver)) `Apache-2.0` `Python`
- [calypso](https://keithp.com/calypso/) - Python-based CalDAV and CardDAV server, forked from Radicale. ([Source Code](https://keithp.com/git/calypso.git)) `GPL-3.0` `Python`
- [DAViCal](https://www.davical.org/) - Server for calendar sharing (CalDAV) that uses a PostgreSQL database as a data store. ([Source Code](https://gitlab.com/davical-project/davical)) `MIT` `PHP`
- [EteSync Server](https://www.etesync.com) - End-to-end encrypted and journaled personal information server supporting calendar and contact data, offering its own clients. ([Source Code](https://github.com/etesync/server-skeleton)) `AGPL-3.0` `Python/Django`
- [Radicale](http://radicale.org/) - Simple calendar and contact server with extremely low administrative overhead. ([Source Code](https://github.com/Kozea/Radicale)) `GPL-3.0` `Python`
- [SabreDAV](http://sabre.io/) - Open source CardDAV, CalDAV, and WebDAV framework and server. ([Source Code](https://github.com/sabre-io/dav)) `MIT` `PHP`
- [Xandikos](https://www.xandikos.org/) - Open source CardDAV, CalDAV and WebDAV server with minimal administrative overhead, backed by a Git repository. ([Source Code](https://github.com/jelmer/xandikos)) `GPL-3.0` `Python`

_CalDAV or CardDAV clients._

- [AgenDAV](http://agendav.org/) - Multilanguage CalDAV web client with a rich AJAX interface and shared calendars support. ([Source Code](https://github.com/agendav/agendav)) `GPL-3.0` `PHP`
- [DAVDroid](https://www.davdroid.com/) - Open-source CalDAV/CardDAV suite and sync app for Android. ([Source Code](https://gitlab.com/bitfireAT/davdroid)) `GPL-3.0` `Java`
- [InfCloud](https://www.inf-it.com/open-source/clients/infcloud/) - Open source CalDAV/CardDAV web client implementation. ([Demo](https://www.inf-it.com/infcloud/), [Source Code](https://www.inf-it.com/InfCloud_0.13.1.zip)) `AGPL-3.0` `Javascript`
- [EteSync Web](https://www.etesync.com/faq/#web-client) - EteSync's official Web-based client (i.e., their Web app). ([Demo](https://client.etesync.com/), [Source Code](https://github.com/etesync/etesync-web)) `AGPL-3.0` `TypeScript`

## Communication systems

**[`^        back to top        ^`](#)**

### Custom communication systems

- [Broid](https://broid.ai) - Broid enables rich conversations on all messaging channels within a single schema integration using W3C standards. ([Demo](https://www.broid.ai), [Source Code](https://github.com/broidHQ/integrations)) `AGPL-3.0` `Nodejs`
- [Centrifugo](https://github.com/centrifugal/centrifugo) - Language-agnostic real-time messaging (Websocket or SockJS) server. ([Demo](https://github.com/centrifugal/centrifugo#demo)) `MIT` `Go`
- [Cherry](https://github.com/rafael-santiago/cherry) - Tiny webchat server. `GPL-2.0` `Go`
- [Freenet](https://freenetproject.org/index.html) - Anonymously share files, browse and publish "freesites" (web sites accessible only through Freenet) and chat on forums. ([Source Code](https://github.com/freenet/fred)) `GPL-2.0` `Java`
- [Friends](http://moose-team.github.io/friends/) - P2P chat powered by the web. ([Source Code](https://github.com/moose-team/friends)) `MIT` `Nodejs`
- [GNUnet](https://gnunet.org/) - Free software framework for decentralized, peer-to-peer networking. ([Source Code](https://gnunet.org/git/)) `GPL-3.0` `C`
- [Hawkpost](https://hawkpost.co) - HawkPost is a web app that lets you create unique links that you can share with a person that desires to send you important information but doesn't know how to encrypt it. The message is encrypted in their browser and sent to your email address. ([Source Code](https://github.com/whitesmith/hawkpost)) `MIT` `Python`
- [Hubl.in](https://hubl.in/) - WebRTC powered video conference, chat and collaborative editor. ([Source Code](https://github.com/linagora/hublin)) `AGPL-3.0` `Nodejs`
- [Jitsi Meet](https://jitsi.org/Projects/JitsiMeet) - Jitsi Meet is an OpenSource (MIT) WebRTC Javascript application that uses Jitsi Videobridge to provide high quality, scalable video conferences. ([Source Code](https://github.com/jitsi/jitsi-meet)) `MIT` `Javascript`
- [Jitsi Video Bridge](https://jitsi.org/Projects/JitsiVideobridge) - WebRTC compatible Selective Forwarding Unit (SFU) that allows for multiuser video communication. ([Source Code](https://github.com/jitsi/jitsi-videobridge)) `Apache-2.0` `Java`
- [Kandan](http://getkandan.com/) - Kandan is an Open Source Alternative to HipChat. ([Source Code](https://github.com/kandanapp/kandan)) `AGPL-3.0` `Ruby`
- [KChat](https://github.com/php-kchat/kchat) - PHP Based Live Chat Aplication. `Apache-2.0` `PHP`
- [Lets-Chat](http://sdelements.github.io/lets-chat/) - Self hosted chat suite written in Node. ([Source Code](https://github.com/sdelements/lets-chat)) `MIT` `Nodejs`
- [Live Helper Chat](http://livehelperchat.com/) - Live Support chat for your website. ([Source Code](https://github.com/LiveHelperChat/livehelperchat)) `Apache-2.0` `PHP`
- [Mattermost](http://www.mattermost.org/) - Open-source, on-prem Slack-alternative. It can be integrated with [Gitlab](https://about.gitlab.com/). ([Source Code](https://github.com/mattermost/platform)) `AGPL-3.0/Apache` `Go`
- [MiAOU](https://dystroy.org/miaou/login) - Multi-room persistent chat server. ([Source Code](https://github.com/Canop/miaou)) `MIT` `Nodejs`
- [Mibew](https://mibew.org) - Mibew Messenger is an open-source live support application written in PHP and MySQL. It enables one-on-one chat assistance in real-time directly from your website. ([Demo](https://mibew.org/demo2), [Source Code](https://github.com/Mibew/mibew)) `Apache-2.0` `PHP`
- [Mumble](http://wiki.mumble.info/wiki/Main_Page) - Low-latency, high quality voice/text chat software. ([Source Code](https://github.com/mumble-voip/mumble), [Clients](https://wiki.mumble.info/wiki/3rd_Party_Applications)) `BSD` `C++`
- [Node-Chat](https://github.com/IgorAntun/node-chat) - Not-so-basic open-source chat with admin features. `MIT` `Nodejs`
- [Pushjet](https://pushjet.io/) - Self hosted push notification service built with a simple API making sending notifications easy. ([Source Code](https://github.com/Pushjet/Pushjet-Server-Api)) `BSD-2-Clause` `Python`
- [Rallly](http://rallly.co) - Rallly is a free collaborative scheduling service. ([Source Code](https://github.com/lukevella/Rallly)) `CC-BY-SA-4.0` `Nodejs`
- [RetroShare](http://retroshare.org) - Secured and decentralized communication system. Offers decentralized chat, forums, messaging, file transfer. ([Source Code](https://github.com/RetroShare/RetroShare)) `GPL-2.0` `С++`
- [Ring](https://ring.cx/) - Free software for universal communication which respects freedoms and privacy of its users. ([Source Code](https://github.com/savoirfairelinux/ring-project)) `GPL-3.0` `C++`
- [Rocket.Chat](https://rocket.chat/) - Teamchat solution similar to Gitter.im or Slack. ([Source Code](https://github.com/RocketChat/Rocket.Chat)) `MIT` `Nodejs`
- [Spectrum 2](http://spectrum.im/) - Spectrum 2 is an open source instant messaging transport.  It allows users to chat together even when they are using different IM networks. ([Source Code](https://github.com/hanzz/spectrum2)) `GPL-3.0` `C++`
- [Spreed](https://www.spreed.me/) - WebRTC audio/video calls, conferencing server, and web client. ([Source Code](https://github.com/strukturag/spreed-webrtc)) `AGPL-3.0` `Go`
- [Synapse](http://matrix.org/docs/projects/server/synapse.html) - Server for [Matrix](https://matrix.org/), an open standard for decentralized persistent communication. ([Source Code](https://github.com/matrix-org/synapse)) `Apache-2.0` `Python`
  - [Matrix Console Web](http://matrix.org/docs/projects/client/matrix-console.html) - Web client meant to be a showcase of Matrix capabilities, and reference implementation of the Matrix standard. ([Source Code](https://github.com/matrix-org/matrix-angular-sdk)) `Apache-2.0` `Javascript`
  - [RIOT](http://riot.im) - Glossy Matrix web client with an emphasis on performance and usability. ([Source Code](https://github.com/vector-im/riot-web)) `Apache-2.0` `Javascript`
- [Syndie](https://www.syndie.de) - Syndie is a libre system for operating distributed forums. `CC0-1.0` `Java`
- [TextBelt](https://github.com/typpo/textbelt) `⚠` - Outgoing SMS API that uses carrier-specific gateways to deliver your text messages for free, and without ads. `MIT` `Javascript`
- [Tox](https://tox.chat/) - Distributed, secure messenger with audio and video chat capabilities. ([Source Code](https://github.com/irungentoo/toxcore)) `GPL-3.0` `C`
- [Tuber](https://blog.trailofbits.com/2015/12/15/self-hosted-video-chat-with-tuber/) - Peer-to-peer video chat that works. ([Source Code](https://github.com/trailofbits/tubertc)) `MIT` `Javascript`
- [ZeroNet](https://zeronet.io/) `⚠` - Open, free, and uncensorable websites, using Bitcoin cryptography and BitTorrent network. ([Source Code](https://github.com/HelloZeroNet/ZeroNet)) `GNU` `Python`
- [Zulip](https://zulip.org) - Zulip is a powerful, open source group chat application. ([Source Code](https://github.com/zulip/zulip)) `Apache/Other` `Python`

### Email

**[`^        back to top        ^`](#)**

#### Complete solutions

_Simple deployment of a mail server, e.g. for inexperienced or impatient admins._

- [docker-mailserver](https://github.com/tomav/docker-mailserver) - Fullstack but simple mail server (smtp, imap, antispam, antivirus, etc.). Only configuration files, no SQL database. Keep it simple and versioned. Easy to deploy and upgrade. `MIT` `Docker`
- [Inboxen](https://inboxen.org) - Inboxen is a service that provides you with an infinite number of unique inboxes. ([Source Code](https://github.com/Inboxen/Inboxen)) `GPL-3.0` `Python`
- [homebox](https://github.com/progmaticltd/homebox) - A suite of Ansible scripts to deploy a fully functional mail server on Debian. Unobtrusive and automatic as much as possible, focusing on stability and security. `GPL-3.0` `Shell`
- [iRedMail](http://www.iredmail.org/) - Full-featured mail server solution based on Postfix and Dovecot. ([Source Code](https://bitbucket.org/zhb/iredmail/commits/)) `GPL-3.0` `Shell`
- [Mailcow](https://mailcow.email/) - Mail server suite based on Dovecot, Postfix and other open source software, that provides a modern Web UI for administration. ([Source Code](https://github.com/andryyy/mailcow)) `GPL-2.0` `PHP`
- [Mailu](https://mailu.io/) - Mailu is a simple yet full-featured mail server as a set of Docker images. ([Demo](https://github.com/Mailu/Mailu/wiki/Demo-server), [Source Code](https://github.com/Mailu/Mailu)) `MIT` `Docker/Python`
- [Mail-in-a-Box](https://mailinabox.email/) - Turns any Ubuntu server into a fully functional mail server with one command. ([Source Code](https://github.com/mail-in-a-box/mailinabox)) `CC0-1.0` `Shell`
- [Modoboa](http://modoboa.org/en/) - Modoboa is a mail hosting and management platform including a modern and simplified Web User Interface. ([Source Code](https://github.com/tonioo/modoboa)) `MIT` `Python`
- [Qmailtoaster](http://www.qmailtoaster.com/) - Stable, full-featured, easy-to-install mail server based on qmail. ([Source Code](https://github.com/QMailToaster/)) `Multiple` `Linux`
- [Simple NixOS Mailserver](https://gitlab.com/simple-nixos-mailserver/nixos-mailserver) - A complete mailserver solution leveraging the Nix Ecosystem. `GPL-3.0` `Nix`

#### Mail Transfer Agents

_MTAs / SMTP servers_

- [Courier MTA](http://www.courier-mta.org/) - Fast, scalable, enterprise mail/groupware server providing ESMTP, IMAP, POP3, webmail, mailing list, basic web-based calendaring and scheduling services. ([Source Code](http://www.courier-mta.org/repo.html)) `GPL-3.0` `C`
- [Exim](https://www.exim.org/) - Message transfer agent (MTA) developed at the University of Cambridge. ([Source Code](http://git.exim.org/exim.git)) `GPL-3.0` `C`
- [Haraka](http://haraka.github.io/) - High-performance, pluginable SMTP server written in Javascript. ([Source Code](https://github.com/haraka/Haraka)) `MIT` `Javascript`
- [MailCatcher](http://mailcatcher.me/) - Ruby gem that deploys a simply SMTP MTA gateway that accepts all mail and displays in web interface. Useful for debugging or development. ([Source Code](https://github.com/sj26/mailcatcher)) `MIT` `Ruby`
- [Maildrop](https://github.com/m242/maildrop) - Disposable email SMTP server, also useful for development. `MIT` `Scala`
- [MailHog](https://github.com/mailhog/MailHog) - Small Golang executable which runs an SMTP MTA gateway that accepts all mail and displays in web interface. Useful for debugging or development. `MIT` `Go`
- [OpenSMTPD](https://opensmtpd.org/) - Secure SMTP server implementation from the OpenBSD project. ([Source Code](http://cvsweb.openbsd.org/cgi-bin/cvsweb/src/usr.sbin/smtpd/)) `ISC` `C`
- [Postfix](http://www.postfix.org/) - Fast, easy to administer, and secure Sendmail replacement. `IPL-1.0` `C`
- [Qmail](http://www.qmail.org/top.html) - Secure Sendmail replacement. ([Source Code](https://sources.debian.net/src/netqmail/1.06-5/)) `CC0-1.0` `C`
- [Sendmail](http://www.sendmail.com/sm/open_source/) - Message transfer agent (MTA). `Sendmail` `C`
- [Slimta](http://slimta.org) - Mail Transfer Library built on Python. ([Source Code](https://github.com/slimta/python-slimta)) `MIT` `Python`

#### Mail Delivery Agents

_MDAs - IMAP/POP3 software_

- [Cyrus IMAP/POP3](http://cyrusimap.org/) - Intended to be run on sealed servers, where normal users are not permitted to log in. ([Source Code](https://github.com/cyrusimap/cyrus-imapd )) `BSD` `C`
- [Dovecot](http://www.dovecot.org/) - IMAP and POP3 server written primarily with security in mind. ([Source Code](https://github.com/dovecot/core)) `MIT/LGPL-2.1` `C`
- [Piler](http://www.mailpiler.org/wiki/start) - feature rich open source email archiving solution. ([Source Code](https://bitbucket.org/jsuto/piler)) `GPL-3.0` `C`

#### Mailing lists and Newsletters

_Mailing lists servers and mass mailing software - one message to many recipients._

- [Dada Mail](http://dadamailproject.com/) - Web-based list management system that can be used for announcement lists and/or discussion lists. ([Source Code](https://github.com/justingit/dada-mail)) `GPL-2.0` `Perl`
- [Mail For Good](https://github.com/freeCodeCamp/mail-for-good) `⚠` - Open source email campaign management tool for nonprofits. `BSD` `Javascript`
- [Mailman](https://www.gnu.org/software/mailman/) - The Gnu mailing list server. `GPL-3.0` `Python`
- [Mailtrain](https://mailtrain.org/) - self hosted newsletter application built on Node.js (v5+) and MySQL (v5.5+ or MariaDB). ([Source Code](https://github.com/andris9/mailtrain)) `GPL-3.0` `Nodejs`
- [MailyHerald](http://mailyherald.org/) - Self-hosted Mailchimp alternative that you can easily integrate with your site. Helps you send and manage your application mailings. It support email marketing and conducting the daily stream of notifications you send to your users. ([Source Code](https://github.com/Sology/maily_herald)) `LGPL-3.0` `Ruby`
- [Mautic](https://www.mautic.org/) - Mautic is marketing automation software (email, social and more). ([Source Code](https://github.com/mautic/mautic)) `GPL-3.0` `PHP`
- [phpList](https://phplist.org) - Newsletter and email marketing with advanced management of subscribers, bounces, and plugins. ([Source Code](https://github.com/phpList/)) `AGPL-3.0` `PHP`
- [Postal](https://github.com/atech/postal) - Fully featured open source mail delivery platform for incoming and outgoing e-mail. `MIT` `Ruby`
- [Schleuder](https://schleuder.nadir.org/) - GPG-enabled mailing list manager with resending-capabilities. ([Source Code](https://0xacab.org/schleuder/schleuder/tree/master)) `GPL-3.0` `Ruby`
- [Sympa](https://www.sympa.org/) - Mailing list manager. `GPL-2.0` `Perl`

#### Webmail clients

- [Cypht](http://cypht.org/index.html) - Feed reader for your email accounts. ([Source Code](https://github.com/jasonmunro/hm3)) `GPL-2.0` `PHP`
- [Disposable Mailbox](https://github.com/synox/disposable-mailbox) - Simple disposable mailbox web-app based on a catch-all IMAP mailbox. ([Demo](https://bhadoomail.com/)) `GPL-3.0` `PHP`
- [IMP](https://www.horde.org/apps/imp/) - HORDE application that provides webmail access to IMAP and POP3 accounts. ([Demo](http://demo.horde.org/), [Source Code](https://www.horde.org/download/imp)) `GPL-2.0` `PHP`
- [Mailpile](https://www.mailpile.is/) - Webmail client with search, filtering, encryption features and more. ([Source Code](https://github.com/mailpile/Mailpile)) `AGPL-3.0` `Python`
- [RainLoop](http://www.rainloop.net/) - Simple, modern and fast webmail with IMAP/SMTP Support and multi accounting. ([Demo](http://demo.rainloop.net/), [Source Code](https://github.com/RainLoop/rainloop-webmail)). `AGPL-3.0` `PHP`
- [Roundcube](https://roundcube.net) - Browser-based IMAP client with an application-like user interface. ([Source Code](https://github.com/roundcube/roundcubemail/)) `GPL-3.0` `PHP`
- [SquirrelMail](http://squirrelmail.org) - Another browser-based IMAP client. ([Source Code](https://sourceforge.net/p/squirrelmail/code/HEAD/tree/)) `GPL-2.0` `PHP`
- [WebMail Lite](http://www.afterlogic.org/webmail-lite) - Web-based IMAP Mail client. ([Source Code](https://github.com/afterlogic/webmail-lite)) `GPL-3.0` `PHP`

### IRC

**[`^        back to top        ^`](#)**

_[IRC](https://en.wikipedia.org/wiki/Internet_Relay_Chat) communication software_

- [Convos](http://convos.by/) - Always online web IRC client. ([Demo](http://demo.convos.by), [Source Code](http://github.com/nordaaker/convos)) `Artistic-2.0` `Perl`
- [Kiwi IRC](https://kiwiirc.com/) - A responsive web IRC client with theming support. ([Demo](https://kiwiirc.com/nextclient/)), ([Source Code](https://github.com/kiwiirc/kiwiirc)) `Apache-2.0` `Nodejs`
- [Quassel IRC](http://quassel-irc.org/) - distributed IRC client, meaning that one (or multiple) client(s) can attach to and detach from a central core. ([Source Code](https://github.com/quassel/quassel)) `GPL-2.0` `C++`
- [Robust IRC](https://robustirc.net/) - RobustIRC is IRC without netsplits. Distributed IRC server, based on RobustSession protocol. ([Source Code](https://github.com/robustirc/robustirc)) `BSD-3-Clause` `Go`
- [The Lounge](https://thelounge.github.io/) - The self-hosted web IRC client. ([Demo](https://demo.thelounge.chat/), [Source Code](https://github.com/thelounge/lounge)) `MIT` `Nodejs`
- [Weechat](https://weechat.org/) - Fast, light and extensible chat client. `GPL-3.0` `C`
- [ZNC](http://wiki.znc.in/ZNC) - Advanced IRC bouncer. ([Source Code](https://github.com/znc/znc)) `Apache-2.0` `C++`

### SIP

**[`^        back to top        ^`](#)**

_[SIP](https://en.wikipedia.org/wiki/Session_Initiation_Protocol) telephony software_

- [Asterisk](http://www.asterisk.org/) - Easy to use but advanced IP PBX system, VoIP gateway and conference server. `GPL-2.0` `C`
- [FreeSWITCH](https://freeswitch.org/) - Scalable open source cross-platform telephony platform. ([Source Code](https://freeswitch.org/stash/projects/FS/repos/freeswitch/browse)) `MPL-2.0` `C`
- [Homer](https://www.sipcapture.org/) - Troubleshooting and monitoring VoIP calls. ([Source Code](https://github.com/sipcapture/homer)) `AGPL-3.0` `Angular/C`
- [Kamailio](http://www.kamailio.org/w/) - Modular SIP server (registrar/proxy/router/etc). ([Source Code](https://github.com/kamailio/kamailio)) `GPL-2.0` `C`
- [Ostel](https://dev.guardianproject.info/projects/ostel/wiki/Server_Documentation) - Secure SIP telephony setup with ZRTP encryption. `GPL-3.0` `Ruby`
- [Tapir](http://www.sip3.io/) - Troubleshooting and real-time monitoring of VoIP-based systems. ([Source Code](https://github.com/sip3io/tapir)) `Apache-2.0` `Java/Kotlin`

### IPBX

**[`^        back to top        ^`](#)**

_[IPBX](https://en.wikipedia.org/wiki/IP_PBX) telephony software_

- [Freepbx](http://www.freepbx.org) - Web-based open source GUI that controls and manages Asterisk. ([Source Code](http://git.freepbx.org/projects/FREEPBX)) `GPL-2.0` `PHP`
- [FusionPBX](https://www.fusionpbx.com/) - Open source project that provides a customizable and flexible web interface to the very powerful and highly scalable multi-platform voice switch called FreeSWITCH. ([Source Code](https://github.com/fusionpbx/fusionpbx)) `MPL-1.1` `PHP`
- [Kazoo](http://2600hz.org/) - KAZOO is an open-source, highly scalable software platform designed to provide carrier-grade VoIP switch functions and features. ([Source Code](https://github.com/2600hz/KAZOO)) `MPL-1.1` `Erlang`
- [Wazo](http://wazo.community/) - Full-featured IPBX solution built atop Asterisk with integrated Web administration interface and REST-ful API. ([Source Code](https://github.com/wazo-pbx)) `GPL-3.0` `Python/PHP`

### Social Networks and Forums

**[`^        back to top        ^`](#)**

- [Abilian SBE](https://github.com/abilian/abilian-sbe) - Open Source Collaboration and Social Networking framework and platform. `LGPL-2.1` `Python`
- [Anahita](https://www.getanahita.com/) - Open Source Social Networking Framework and Platform. ([Source Code](https://github.com/anahitasocial)) `GPL-3.0` `PHP`
- [bbPress](https://bbpress.org/) - bbPress is forum software with a twist from the creators of WordPress. Easily setup discussion forums inside your WordPress.org powered site. ([Source Code](https://bbpress.trac.wordpress.org/browser/trunk)) `GPL-2.0` `PHP`
- [Bootcamp](http://trybootcamp.vitorfs.com) - Enterprise social network. ([Source Code](https://github.com/vitorfs/bootcamp)) `MIT` `Python`
- [Buddycloud](http://buddycloud.com/) - Tools, libraries, services and a community to build user-to-user, group and social messaging into your app. Saves time. Scales up. Supports you. ([Source Code](https://github.com/buddycloud)) `Apache-2.0` `Java`
- [BuddyPress](https://buddypress.org/about/) - Powerful plugin that takes your WordPress.org powered site beyond the blog with social-network features like user profiles, activity streams, user groups, and more. ([Source Code](https://buddypress.svn.wordpress.org/trunk/)) `GPL-2.0` `PHP`
- [cartulary](https://github.com/daveajones/cartulary) - RSS reader, readability tool
