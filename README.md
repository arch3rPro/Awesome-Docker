# Awesome Docker [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

这是一个Docker资源集合，旨在帮助开发者、运维人员和技术团队更好地使用Docker技术。本项目涵盖了从入门教程到高级实践的全方位资源，包括官方文档、管理工具、安全指南、最佳实践等。无论您是Docker初学者还是经验丰富的专家，都能在这里找到有价值的工具和参考资料，助力提升容器化开发和部署效率。

## 目录

- [官方资源](#官方资源)
- [工具](#工具)
- [教程](#教程)
- [最佳实践](#最佳实践)
- [安全性](#安全性)
- [监控](#监控)
- [编排和集群](#编排和集群)
- [镜像构建](#镜像构建)
- [开发工具](#开发工具)
- [应用推荐](#应用推荐)
- [贡献指南](#贡献指南)

## 官方资源

- [Docker 官网](https://www.docker.com/) - Docker官方网站
- [Docker Hub](https://hub.docker.com/) - Docker官方镜像仓库
- [Docker Docs](https://docs.docker.com/) - Docker官方文档
- [Docker GitHub](https://github.com/docker) - Docker的GitHub组织
- [Docker Blog](https://www.docker.com/blog/) - Docker官方博客

## 管理工具

- [Portainer](https://www.portainer.io/) - 强大的容器管理UI界面
- [Docker Compose](https://docs.docker.com/compose/) - 定义和运行多容器Docker应用程序
- [Dive](https://github.com/wagoodman/dive) - 用于探索Docker镜像层的工具
- [Lazydocker](https://github.com/jesseduffield/lazydocker) - Docker的终端UI工具
- [ctop](https://github.com/bcicen/ctop) - 容器的top类监控工具

## 使用教程

- [Docker —— 从入门到实践](https://yeasy.gitbook.io/docker_practice/) - 中文Docker实践指南
- [Docker Curriculum](https://docker-curriculum.com/) - 从零开始学习Docker
- [Play with Docker](https://labs.play-with-docker.com/) - 在线Docker实验室

## 最佳实践

- [Docker最佳实践](https://docs.docker.com/develop/develop-images/dockerfile_best-practices/) - 官方Dockerfile最佳实践指南
- [Container Best Practices](http://docs.projectatomic.io/container-best-practices/) - 容器最佳实践
- [Docker安全最佳实践](https://snyk.io/blog/10-docker-image-security-best-practices/) - Docker镜像安全最佳实践

## 安全性

- [Docker Bench Security](https://github.com/docker/docker-bench-security) - Docker主机安全检查脚本
- [Clair](https://github.com/quay/clair) - 容器漏洞静态分析
- [Trivy](https://github.com/aquasecurity/trivy) - 简单而全面的容器漏洞扫描器

## 容器监控

- [cAdvisor](https://github.com/google/cadvisor) - 容器资源使用和性能分析
- [Prometheus](https://prometheus.io/) - 开源监控解决方案
- [Grafana](https://grafana.com/) - 监控数据可视化

## 编排和集群

- [Kubernetes](https://kubernetes.io/) - 容器编排平台
- [Docker Swarm](https://docs.docker.com/engine/swarm/) - Docker原生集群工具
- [Rancher](https://rancher.com/) - 企业级容器管理平台

## 镜像构建

- [BuildKit](https://github.com/moby/buildkit) - 下一代Docker镜像构建工具
- [Kaniko](https://github.com/GoogleContainerTools/kaniko) - 在Kubernetes中构建容器镜像
- [Multi-stage builds](https://docs.docker.com/develop/develop-images/multistage-build/) - Docker多阶段构建

## 开发工具

- [Docker VS Code Extension](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-docker) - VS Code的Docker扩展
- [Docker Desktop](https://www.docker.com/products/docker-desktop) - 桌面Docker开发环境
- [Telepresence](https://www.telepresence.io/) - 本地开发Kubernetes服务的工具

## 应用推荐

### 📽️ 媒体管理
#### 🎬 影音服务器

| 名称 | 类型 | 应用介绍 | 开源地址 | GitHub Stars | Docker Pulls |
|------|------|----------|-----------|--------------|---------------|
| Plex | 综合服务器 | 功能强大的流媒体服务器，支持电影、电视剧、音乐等多媒体内容的管理和串流 | [plexinc/pms-docker](https://github.com/plexinc/pms-docker) | 8.5k | 6B+ |
| Jellyfin | 综合服务器 | 开源的媒体系统，Emby的分支，完全免费，支持实时转码和多用户管理 | [jellyfin/jellyfin](https://github.com/jellyfin/jellyfin) | 31.2k | 800M+ |
| Emby | 综合服务器 | 专业的媒体服务器，支持直播电视和DVR功能，提供优秀的元数据刮削功能 | [emby/embyserver](https://github.com/MediaBrowser/Emby) | 4.8k | 150M+ |
| Navidrome | 音乐服务器 | 现代化的音乐服务器，支持流媒体播放和音乐库管理 | [navidrome/navidrome](https://github.com/navidrome/navidrome) | 9.2k | 25M+ |

#### 🎵 音乐播放

| 名称 | 类型 | 应用介绍 | 开源地址 | GitHub Stars | Docker Pulls |
|------|------|----------|-----------|--------------|---------------|
| Mopidy | 音乐服务器 | 可扩展的音乐服务器，支持多种音乐来源和播放协议 | [mopidy/mopidy](https://github.com/mopidy/mopidy) | 8.8k | 7M+ |
| Funkwhale | 音乐服务器 | 现代化的音乐流媒体服务器，支持音乐分享和社交功能 | [funkwhale/funkwhale](https://github.com/funkwhale/funkwhale) | 3.8k | 1.5M+ |
| Airsonic | 音乐服务器 | 基于Java的音乐流媒体服务器，支持多用户和跨平台 | [airsonic/airsonic](https://github.com/airsonic/airsonic) | 3.4k | 12M+ |
| Volumio | 音频系统 | 专注于高品质音乐播放的系统，支持多种音频格式 | [volumio/volumio3](https://github.com/volumio/volumio3) | 2.1k | 800K+ |
| DeaDBeeF | 音频播放器 | 高品质音频播放器，支持多种音频格式和插件扩展 | [DeaDBeeF-Player/deadbeef-docker](https://github.com/DeaDBeeF-Player/deadbeef-docker) | 2.8k | 150K+ |
| MPD | 音乐服务器 | 轻量级的音乐播放守护进程，支持多客户端连接 | [jcorporation/myMPD](https://github.com/jcorporation/myMPD) | 1.5k | 1.2M+ |
| Beets | 音乐管理 | 强大的音乐库管理工具，支持自动标签和元数据管理 | [beetbox/beets](https://github.com/beetbox/beets) | 12.1k | 700K+ |
| LMS | 音乐服务器 | Logitech Media Server，支持多房间音频和智能家居集成 | [Logitech/slimserver](https://github.com/Logitech/slimserver) | 1.8k | 250K+ |
| Gonic | 音乐服务器 | 轻量级的Subsonic兼容服务器，支持音乐流媒体和播放列表 | [sentriz/gonic](https://github.com/sentriz/gonic) | 1.5k | 120K+ |

#### 📚 电子书管理

| 名称 | 类型 | 应用介绍 | 开源地址 | GitHub Stars | Docker Pulls |
|------|------|----------|-----------|--------------|---------------|
| Calibre-Web | 综合管理 | 基于Calibre的在线电子书管理系统，支持在线阅读、元数据编辑和格式转换 | [janeczku/calibre-web](https://github.com/janeczku/calibre-web) | 9.5k | 50M+ |
| Kavita | 漫画管理 | 现代化的电子书和漫画服务器，支持多用户和移动端访问 | [Kareadita/Kavita](https://github.com/Kareadita/Kavita) | 3.8k | 5M+ |
| Komga | 漫画管理 | 专注于漫画和图片书籍的媒体服务器，支持系列管理和阅读进度同步 | [gotson/komga](https://github.com/gotson/komga) | 2.9k | 10M+ |
| COPS | OPDS服务 | 轻量级的Calibre OPDS服务器，支持电子书在线浏览和下载 | [seblucas/cops](https://github.com/seblucas/cops) | 1.5k | 1M+ |
| Ubooquity | 综合管理 | 支持电子书和漫画的多用户媒体服务器，提供强大的元数据管理 | [vaemendis/ubooquity](https://github.com/vaemendis/ubooquity) | 2.2k | 5M+ |
| Readarr | 电子书自动化 | 电子书的自动化下载和管理工具，支持多个下载源 | [Readarr/Readarr](https://github.com/Readarr/Readarr) | 2.8k | 10M+ |
| LANraragi | 漫画管理 | 开源的漫画管理器，支持多种格式和标签管理 | [Difegue/LANraragi](https://github.com/Difegue/LANraragi) | 2.1k | 3M+ |
| Calibre-RPC | 格式转换 | Calibre的RPC服务器，提供电子书格式转换API | [calibre-rest/calibre-rest](https://github.com/calibre-rest/calibre-rest) | 1.2k | 500K+ |
| Stump | 漫画管理 | 现代化的漫画和图片书籍服务器，支持多用户和阅读进度同步 | [aaronleopold/stump](https://github.com/aaronleopold/stump) | 1.1k | 200K+ |
| Tanoshi | 漫画阅读 | 自托管的漫画阅读服务器，支持多种漫画源和在线阅读 | [faldez/tanoshi](https://github.com/faldez/tanoshi) | 1.3k | 100K+ |
#### 📸 照片管理

| 名称 | 类型 | 应用介绍 | 开源地址 | GitHub Stars | Docker Pulls |
|------|------|----------|-----------|--------------|---------------|
| PhotoPrism | 照片库管理 | 基于AI的照片管理器，支持面部识别、地理标记和自动分类 | [photoprism/photoprism](https://github.com/photoprism/photoprism) | 28.5k | 100M+ |
| Immich | 照片备份 | 高性能的照片和视频备份工具，支持移动端实时备份 | [immich-app/immich](https://github.com/immich-app/immich) | 21.2k | 10M+ |
| Lychee | 相册分享 | 简洁美观的照片管理系统，支持在线分享和多用户管理 | [LycheeOrg/Lychee](https://github.com/LycheeOrg/Lychee) | 5.2k | 10M+ |
| Pigallery2 | 相册管理 | 快速的照片和视频浏览器，支持目录扫描和元数据管理 | [bpatrik/pigallery2](https://github.com/bpatrik/pigallery2) | 2.1k | 1M+ |
| LibrePhotos | 照片库管理 | 开源的Google Photos替代品，支持面部识别和自动标签 | [LibrePhotos/librephotos](https://github.com/LibrePhotos/librephotos) | 5.8k | 5M+ |
| Piwigo | 相册分享 | 功能丰富的照片库系统，支持插件扩展和多语言 | [Piwigo/Piwigo](https://github.com/Piwigo/Piwigo) | 3.2k | 10M+ |
| Chevereto | 图片托管 | 专业的图片托管和分享平台，支持多存储后端 | [chevereto/chevereto](https://github.com/chevereto/chevereto) | 4.5k | 5M+ |
| Photoview | 照片浏览 | 简单快速的照片库，支持RAW格式和地理信息显示 | [photoview/photoview](https://github.com/photoview/photoview) | 3.8k | 1M+ |

#### 🎥 视频转码

| 名称 | 类型 | 应用介绍 | 开源地址 | GitHub Stars | Docker Pulls |
|------|------|----------|-----------|--------------|---------------|
| Jellyfin | 转码服务器 | 开源的媒体系统，支持实时转码和硬件加速，可作为独立的转码服务器使用 | [jellyfin/jellyfin](https://github.com/jellyfin/jellyfin) | 28.3k | 500M+ |
| HandBrake | 视频转码 | 功能强大的视频转码工具，支持批量处理和自定义预设 | [HandBrake/HandBrake](https://github.com/HandBrake/HandBrake) | 16.8k | 50M+ |
| FFmpeg | 编解码工具 | 最流行的音视频处理框架，支持几乎所有格式的转码和处理 | [FFmpeg/FFmpeg](https://github.com/FFmpeg/FFmpeg) | 39.2k | 2B+ |
| Tdarr | 自动化转码 | 分布式视频转码系统，支持自动化处理和健康检查 | [HaveAGitGat/Tdarr](https://github.com/HaveAGitGat/Tdarr) | 2.8k | 10M+ |
| Unmanic | 自动化转码 | 灵活的文件夹监控和自动转码工具，支持插件扩展 | [Unmanic/unmanic](https://github.com/
### 🤖 自动化工具
#### ⬇️ 下载工具

| 名称 | 类型 | 应用介绍 | 开源地址 | GitHub Stars | Docker Pulls |
|------|------|----------|-----------|--------------|---------------|
| qBittorrent | BT下载 | 功能强大的BT下载客户端，支持RSS订阅和WebUI | [linuxserver/qbittorrent](https://github.com/qbittorrent/qBittorrent) | 21.5k | 500M+ |
| Transmission | BT下载 | 轻量级的BT客户端，支持Web界面和远程控制 | [transmission/transmission](https://github.com/transmission/transmission) | 10.2k | 300M+ |
| Aria2 | 多协议下载 | 轻量级的下载工具，支持BT、HTTP和FTP等多种协议 | [aria2/aria2](https://github.com/aria2/aria2) | 31.2k | 200M+ |
| JDownloader | 网盘下载 | 支持多个网盘和视频网站的下载管理器 | [jlesage/jdownloader-2](https://github.com/jlesage/docker-jdownloader-2) | 3.8k | 100M+ |
| youtube-dl | 视频下载 | 支持多个视频网站的命令行下载工具 | [yt-dlp/yt-dlp](https://github.com/yt-dlp/yt-dlp) | 62.5k | 50M+ |
| Syncthing | 文件同步 | P2P文件同步工具，支持多设备实时同步 | [syncthing/syncthing](https://github.com/syncthing/syncthing) | 55.8k | 150M+ |
| Deluge | BT下载 | 功能丰富的BT客户端，支持插件扩展 | [deluge/deluge](https://github.com/deluge/deluge) | 4.5k | 100M+ |
| pyLoad | 下载管理 | 支持多个下载网站的下载管理器 | [pyload/pyload](https://github.com/pyload/pyload) | 3.2k | 20M+ |
| Motrix | 多协议下载 | 清新简洁的全能下载工具，支持多种协议 | [agalwood/Motrix](https://github.com/agalwood/Motrix) | 41.2k | 10M+ |
| Free Download Manager | 多功能下载 | 功能全面的下载管理器，支持多线程和浏览器集成 | [freedownloadmanager/fdm](https://github.com/freedownloadmanager/fdm) | 2.8k | 5M+ |

#### 📰 RSS聚合

| 名称 | 类型 | 应用介绍 | 开源地址 | GitHub Stars | Docker Pulls |
|------|------|----------|-----------|--------------|---------------|
| FreshRSS | RSS阅读器 | 轻量级的自托管RSS聚合器，支持多用户和移动端访问 | [FreshRSS/FreshRSS](https://github.com/FreshRSS/FreshRSS) | 7.2k | 50M+ |
| Miniflux | RSS阅读器 | 极简风格的Feed阅读器，注重性能和安全性 | [miniflux/v2](https://github.com/miniflux/v2) | 5.8k | 20M+ |
| RSS-Bridge | RSS生成器 | 为不提供RSS的网站生成Feed，支持多个主流网站 | [RSS-Bridge/rss-bridge](https://github.com/RSS-Bridge/rss-bridge) | 6.2k | 10M+ |
| RSSHub | RSS生成器 | 万物皆可RSS的生成器，支持数百个网站 | [DIYgod/RSSHub](https://github.com/DIYgod/RSSHub) | 27.5k | 100M+ |
| Tiny Tiny RSS | RSS阅读器 | 功能丰富的新闻阅读器，支持插件扩展和主题定制 | [tt-rss/tt-rss](https://github.com/tt-rss/tt-rss) | 11.2k | 30M+ |
| NewsBlur | 新闻聚合 | 智能的新闻阅读器，支持训练个性化推荐 | [samuelclay/NewsBlur](https://github.com/samuelclay/NewsBlur) | 6.5k | 5M+ |
| CommaFeed | RSS阅读器 | 简洁现代的RSS阅读器，类似Google Reader | [Athou/commafeed](https://github.com/Athou/commafeed) | 2.8k | 3M+ |
| Selfoss | 新闻聚合 | 多功能的新闻聚合器，支持多种数据源和过滤器 | [fossar/selfoss](https://github.com/fossar/selfoss) | 2.5k | 2M+ |
| Stringer | RSS阅读器 | 简单易用的自托管RSS阅读器，支持Fever API | [stringer-rss/stringer](https://github.com/stringer-rss/stringer) | 3.8k | 1M+ |
| Yarr | RSS阅读器 | 快速轻量的Feed阅读器，支持离线阅读和全文搜索 | [nkanaev/yarr](https://github.com/nkanaev/yarr) | 2.1k | 500K+ |

#### 🏠 智能家居

| 名称 | 类型 | 应用介绍 | 开源地址 | GitHub Stars | Docker Pulls |
|------|------|----------|-----------|--------------|---------------|
| Home Assistant | 家庭自动化 | 开源的智能家居平台，支持数千种设备集成和自动化场景 | [home-assistant/core](https://github.com/home-assistant/core) | 63k | 1亿+ |
| Node-RED | 自动化流程 | 基于流的物联网编程工具，支持可视化设备联动 | [node-red/node-red](https://github.com/node-red/node-red) | 17.8k | 1亿+ |
| OpenHAB | 智能中枢 | 多协议智能家居集成平台，支持2000+设备类型 | [openhab/openhab-core](https://github.com/openhab/openhab-core) | 3.5k | 5000万+ |
| Mosquitto | MQTT代理 | 轻量级的消息代理服务器，支持物联网设备通信 | [eclipse/mosquitto](https://github.com/eclipse/mosquitto) | 7.2k | 2亿+ |
| Zigbee2MQTT | 协议转换 | 将Zigbee设备接入MQTT生态的桥接工具 | [Koenkk/zigbee2mqtt](https://github.com/Koenkk/zigbee2mqtt) | 10.2k | 3000万+ |
| ESPHome | 设备管理 | 通过YAML配置快速创建物联网设备固件 | [esphome/esphome](https://github.com/esphome/esphome) | 7.3k | 2000万+ |
| Glances | 资源监控 | 跨平台的系统监控工具，支持容器化部署 | [nicolargo/glances](https://github.com/nicolargo/glances) | 25k | 5000万+ |
| InfluxDB | 时序数据库 | 专为物联网数据设计的时序数据库 | [influxdata/influxdb](https://github.com/influxdata/influxdb) | 27k | 1亿+ |
| Grafana | 数据可视化 | 智能家居数据看板制作工具 | [grafana/grafana](https://github.com/grafana/grafana) | 58k | 3亿+ |
| Jeedom | 智能中枢 | 法国开源的智能家居管理系统 | [jeedom/core](https://github.com/jeedom/core) | 1.2k | 1000万+ |
| Domoticz | 家庭自动化 | 轻量级家庭自动化系统，支持多种协议 | [domoticz/domoticz](https://github.com/domoticz/domoticz) | 3.5k | 2000万+ |
| Homebridge | 苹果生态 | 将非HomeKit设备接入苹果智能家居 | [homebridge/homebridge](https://github.com/homebridge/homebridge) | 23k | 8000万+ |

#### 🕷️ 网络爬虫

| 名称 | 类型 | 应用介绍 | 开源地址 | GitHub Stars | Docker Pulls |
|--|--|--|--|--|--|
| Scrapy | 爬虫框架 | 功能强大的Python爬虫框架，支持分布式部署和数据管道 | [scrapy/scrapy](https://github.com/scrapy/scrapy) | 48.5k | 50M+ |
| Crawlab | 爬虫管理 | 分布式爬虫管理平台，支持多种编程语言和定时任务 | [crawlab-team/crawlab](https://github.com/crawlab-team/crawlab) | 10.2k | 5M+ |
| Colly | 爬虫框架 | Go语言编写的快速优雅的爬虫框架 | [gocolly/colly](https://github.com/gocolly/colly) | 20.5k | 2M+ |
| Puppeteer | 浏览器自动化 | 基于Chrome的自动化工具，支持页面渲染和交互 | [puppeteer/puppeteer](https://github.com/puppeteer/puppeteer) | 85.6k | 100M+ |
| Selenium | 浏览器自动化 | 跨平台的Web自动化测试工具，支持多种浏览器 | [SeleniumHQ/selenium](https://github.com/SeleniumHQ/selenium) | 27.8k | 200M+ |
| PhantomJS | 无头浏览器 | 无界面的WebKit浏览器，适合自动化数据采集 | [ariya/phantomjs](https://github.com/ariya/phantomjs) | 29.2k | 50M+ |
| Pyspider | 爬虫平台 | Python爬虫系统，带有Web界面，支持脚本编辑和任务监控 | [binux/pyspider](https://github.com/binux/pyspider) | 15.8k | 3M+ |
| Playwright | 浏览器自动化 | 现代Web测试和自动化框架，支持多种浏览器内核 | [microsoft/playwright](https://github.com/microsoft/playwright) | 58.2k | 20M+ |

### 🛠️ 开发运维
#### 🐳 容器管理

| 名称 | 类型 | 应用介绍 | 开源地址 | GitHub Stars | Docker Pulls |
|--|--|--|--|--|--|
| Kubernetes | 容器编排 | 业界标准的容器编排平台，提供自动化部署、扩展和管理 | [kubernetes/kubernetes](https://github.com/kubernetes/kubernetes) | 102k | - |
| Docker Swarm | 容器编排 | Docker原生的集群管理工具，配置简单，适合小规模部署 | [moby/swarmkit](https://github.com/moby/swarmkit) | 6.2k | - |
| Portainer | 容器管理 | 直观的Web UI管理界面，支持Docker和Kubernetes | [portainer/portainer](https://github.com/portainer/portainer) | 26.5k | 1B+ |
| Harbor | 镜像仓库 | 企业级容器镜像仓库，支持安全扫描和访问控制 | [goharbor/harbor](https://github.com/goharbor/harbor) | 20.8k | 10M+ |
| Prometheus | 监控系统 | 强大的监控告警系统，提供丰富的容器监控指标 | [prometheus/prometheus](https://github.com/prometheus/prometheus) | 50.2k | 1B+ |
| Consul | 服务发现 | 分布式服务发现和配置管理系统 | [hashicorp/consul](https://github.com/hashicorp/consul) | 27.3k | 100M+ |
| Rancher | 容器平台 | 完整的容器管理平台，支持多集群管理和应用部署 | [rancher/rancher](https://github.com/rancher/rancher) | 21.4k | 500M+ |
| cAdvisor | 资源监控 | 容器资源使用和性能分析工具 | [google/cadvisor](https://github.com/google/cadvisor) | 15.2k | 1B+ |

#### 📊 监控告警

| 名称 | 类型 | 应用介绍 | 开源地址 | GitHub Stars | Docker Pulls |
|--|--|--|--|--|--|
| Prometheus | 监控系统 | 云原生监控系统的事实标准，提供强大的数据采集、存储和查询功能 | [prometheus/prometheus](https://github.com/prometheus/prometheus) | 50.2k | 1B+ |
| Grafana | 可视化平台 | 功能丰富的指标分析和可视化平台，支持多种数据源 | [grafana/grafana](https://github.com/grafana/grafana) | 58k | 3B+ |
| Zabbix | 企业监控 | 企业级分布式监控系统，支持多种监控方式和告警通知 | [zabbix/zabbix](https://github.com/zabbix/zabbix) | 10k | 500M+ |
| Nagios | 系统监控 | 老牌的IT基础设施监控系统，提供全面的主机和服务监控 | [NagiosEnterprises/nagioscore](https://github.com/NagiosEnterprises/nagioscore) | 3.5k | 50M+ |
| Alertmanager | 告警管理 | Prometheus生态的告警管理器，支持灵活的告警路由和通知 | [prometheus/alertmanager](https://github.com/prometheus/alertmanager) | 5.8k | 500M+ |
| Netdata | 实时监控 | 高性能的分布式实时监控系统，具有出色的可视化界面 | [netdata/netdata](https://github.com/netdata/netdata) | 65k | 2B+ |
| Elastic Stack | 日志监控 | 强大的日志收集和分析平台，支持复杂的数据分析和可视化 | [elastic/elasticsearch](https://github.com/elastic/elasticsearch) | 65k | 1B+ |
| Sensu | 监控框架 | 灵活的监控和告警框架，支持自动化运维和故障排查 | [sensu/sensu-go](https://github.com/sensu/sensu-go) | 4.2k | 100M+ |

#### 📝 日志分析

| 名称 | 类型 | 应用介绍 | 开源地址 | GitHub Stars | Docker Pulls |
|--|--|--|--|--|--|
| Elasticsearch | 日志存储 | 分布式搜索和分析引擎，是ELK栈的核心组件 | [elastic/elasticsearch](https://github.com/elastic/elasticsearch) | 65k | 1B+ |
| Logstash | 日志收集 | 服务器端数据处理管道，能够同时从多个来源收集数据 | [elastic/logstash](https://github.com/elastic/logstash) | 13.5k | 500M+ |
| Kibana | 日志可视化 | 数据可视化和探索工具，为Elasticsearch提供漂亮的分析界面 | [elastic/kibana](https://github.com/elastic/kibana) | 18.7k | 500M+ |
| Fluentd | 日志收集 | 统一日志层，支持多种输入和输出格式的开源数据收集器 | [fluent/fluentd](https://github.com/fluent/fluentd) | 12.3k | 100M+ |
| Graylog | 日志平台 | 集中式日志管理平台，提供强大的搜索功能和告警机制 | [Graylog2/graylog2-server](https://github.com/Graylog2/graylog2-server) | 7.2k | 50M+ |
| Loki | 日志聚合 | Grafana开发的轻量级日志聚合系统，类似Prometheus但针对日志 | [grafana/loki](https://github.com/grafana/loki) | 20.5k | 200M+ |
| Vector | 数据管道 | 高性能的可观测性数据管道，支持收集、转换和路由日志数据 | [vectordotdev/vector](https://github.com/vectordotdev/vector) | 15.3k | 20M+ |
| Graylog | 日志平台 | 集中式日志管理平台，提供强大的搜索和告警功能 | [Graylog2/graylog2-server](https://github.com/Graylog2/graylog2-server) | 7.2k | 50M+ |
| Filebeat | 日志采集 | 轻量级的日志文件采集器，是Elastic Beat家族的一部分 | [elastic/beats](https://github.com/elastic/beats) | 11.8k | 300M+ |
| SigNoz | 可观测平台 | 开源的应用性能监控和可观测性平台，替代Datadog的开源方案 | [SigNoz/signoz](https://github.com/SigNoz/signoz) | 15.2k | 5M+ |
| GoAccess | 日志分析 | 实时Web日志分析器和交互式查看器，支持终端和浏览器界面 | [allinurl/goaccess](https://github.com/allinurl/goaccess) | 16.4k | 10M+ |

#### 🔍 接口测试

| 名称 | 类型 | 应用介绍 | 开源地址 | GitHub Stars | Docker Pulls |
|------|------|----------|-----------|--------------|---------------|
| Postman | 接口测试 | 功能强大的API开发和测试工具，支持自动化测试和团队协作 | [postmanlabs/newman](https://github.com/postmanlabs/newman) | 7.5k | 50M+ |
| SoapUI | 接口测试 | 专业的API测试工具，支持SOAP和REST接口测试 | [SmartBear/soapui](https://github.com/SmartBear/soapui) | 2.8k | 5M+ |
| JMeter | 性能测试 | 功能强大的负载测试和性能测试工具，支持多种协议 | [apache/jmeter](https://github.com/apache/jmeter) | 7.2k | 100M+ |
| Gatling | 性能测试 | 高性能的负载测试工具，基于Scala开发，支持HTTP协议 | [gatling/gatling](https://github.com/gatling/gatling) | 6.1k | 20M+ |
| Locust | 性能测试 | 分布式的用户负载测试工具，使用Python编写测试脚本 | [locustio/locust](https://github.com/locustio/locust) | 22.8k | 30M+ |
| Hoppscotch | API平台 | 轻量级的开源API开发生态系统，支持REST、GraphQL和WebSocket | [hoppscotch/hoppscotch](https://github.com/hoppscotch/hoppscotch) | 55.2k | 10M+ |
| Karate | 自动化测试 | 结合API测试、Mock和性能测试的开源工具 | [karatelabs/karate](https://github.com/karatelabs/karate) | 7.3k | 5M+ |
| Insomnia | API客户端 | 跨平台的REST和GraphQL客户端，支持环境变量和请求管理 | [Kong/insomnia](https://github.com/Kong/insomnia) | 30.5k | 15M+ |
| Taurus | 测试框架 | 自动化测试框架，可以整合JMeter、Gatling等工具 | [Blazemeter/taurus](https://github.com/Blazemeter/taurus) | 1.8k | 2M+ |

### 🔒 网络安全
#### 🛡️ 防火墙WAF

| 名称 | 类型 | 应用介绍 | 开源地址 | GitHub Stars | Docker Pulls |
|------|------|----------|-----------|--------------|---------------|
| ModSecurity | WAF | 开源的Web应用防火墙，提供实时监控和防护功能 | [SpiderLabs/ModSecurity](https://github.com/SpiderLabs/ModSecurity) | 6.2k | 50M+ |
| NGINX WAF | WAF | 基于NGINX的Web应用防火墙，提供高性能的HTTP过滤 | [nginx/nginx](https://github.com/nginx/nginx) | 19.5k | 1B+ |
| OpenWAF | WAF | 基于OpenResty的Web应用防火墙，支持复杂规则和高性能 | [titansec/OpenWAF](https://github.com/titansec/OpenWAF) | 1.2k | 5M+ |
| Naxsi | WAF | NGINX的防XSS和SQL注入模块，轻量级且高效 | [nbs-system/naxsi](https://github.com/nbs-system/naxsi) | 4.8k | 10M+ |
| Crowdsec | 安全引擎 | 开源的安全引擎，能够检测和响应恶意活动 | [crowdsecurity/crowdsec](https://github.com/crowdsecurity/crowdsec) | 7.5k | 15M+ |
| Wazuh | 安全平台 | 开源的安全监控平台，提供入侵检测和安全分析 | [wazuh/wazuh](https://github.com/wazuh/wazuh) | 8.2k | 100M+ |
| pfSense | 防火墙 | 基于FreeBSD的开源防火墙和路由器平台 | [pfsense/pfsense](https://github.com/pfsense/pfsense) | 4.5k | 50M+ |
| OPNsense | 防火墙 | 开源的基于HardenedBSD的防火墙和路由平台 | [opnsense/core](https://github.com/opnsense/core) | 3.2k | 20M+ |
| Fail2Ban | 入侵防护 | 扫描日志文件并禁止显示恶意活动迹象的IP | [fail2ban/fail2ban](https://github.com/fail2ban/fail2ban) | 9.1k | 100M+ |

#### 🔒 安全审计

| 名称 | 类型 | 应用介绍 | 开源地址 | GitHub Stars | Docker Pulls |
|------|------|----------|-----------|--------------|---------------|
| OpenVAS | 漏洞扫描 | 全面的漏洞扫描和管理解决方案，支持多种扫描方式 | [greenbone/openvas-scanner](https://github.com/greenbone/openvas-scanner) | 3.8k | 50M+ |
| OWASP ZAP | 安全测试 | 世界上最流行的免费安全测试工具，用于查找Web应用程序中的漏洞 | [zaproxy/zaproxy](https://github.com/zaproxy/zaproxy) | 11.5k | 100M+ |
| Lynis | 安全审计 | 系统安全审计工具，用于评估Linux/Unix系统的安全状态 | [CISOfy/lynis](https://github.com/CISOfy/lynis) | 11.2k | 20M+ |
| OpenSCAP | 合规检查 | 开源的安全合规解决方案，支持多种安全标准 | [OpenSCAP/openscap](https://github.com/OpenSCAP/openscap) | 1.5k | 10M+ |
| Falco | 运行时安全 | 云原生运行时安全项目，提供容器、主机和云安全监控 | [falcosecurity/falco](https://github.com/falcosecurity/falco) | 6.2k | 100M+ |
| Osquery | 安全分析 | 操作系统检测框架，将操作系统作为高性能关系数据库 | [osquery/osquery](https://github.com/osquery/osquery) | 20.5k | 50M+ |
| Clair | 容器扫描 | 静态分析容器漏洞的开源项目 | [quay/clair](https://github.com/quay/clair) | 9.5k | 100M+ |
| Trivy | 漏洞扫描 | 简单而全面的容器漏洞扫描器 | [aquasecurity/trivy](https://github.com/aquasecurity/trivy) | 18.2k | 500M+ |
| Anchore | 容器分析 | 深度容器镜像分析和策略引擎 | [anchore/anchore-engine](https://github.com/anchore/anchore-engine) | 4.2k | 50M+ |

#### 📈 流量分析

| 名称 | 类型 | 应用介绍 | 开源地址 | GitHub Stars | Docker Pulls |
|--|--|--|--|--|--|
| Wireshark | 流量监控 | 世界上最广泛使用的网络协议分析工具，提供深度数据包检测功能 | [wireshark/wireshark](https://github.com/wireshark/wireshark) | 9.8k | 50M+ |
| Ntopng | 流量监控 | 高性能的网络流量监控和分析工具，支持实时监控和历史数据分析 | [ntop/ntopng](https://github.com/ntop/ntopng) | 5.2k | 20M+ |
| Zeek | 协议分析 | 强大的网络安全监控工具，专注于网络流量分析和异常检测 | [zeek/zeek](https://github.com/zeek/zeek) | 5.8k | 10M+ |
| Suricata | 入侵检测 | 高性能的网络威胁检测引擎，支持IDS、IPS和NSM功能 | [OISF/suricata](https://github.com/OISF/suricata) | 7.2k | 30M+ |
| Moloch | 数据包捕获 | 大规模全数据包捕获和索引系统，适合大型网络监控 | [arkime/arkime](https://github.com/arkime/arkime) | 5.5k | 5M+ |
| NetworkMiner | 取证分析 | 网络取证分析工具，专注于从数据包中提取文件和信息 | [netresec/networkminer](https://github.com/netresec/networkminer) | 2.1k | 1M+ |
| Snort | 入侵防御 | 广泛使用的开源入侵检测和防御系统 | [snort3/snort3](https://github.com/snort3/snort3) | 3.8k | 15M+ |
| Tshark | 命令行分析 | Wireshark的命令行版本，适合自动化分析和脚本集成 | [wireshark/wireshark](https://github.com/wireshark/wireshark) | 9.8k | 10M+ |


#### 🔍 漏洞扫描

| 名称 | 类型 | 应用介绍 | 开源地址 | GitHub Stars | Docker Pulls |
|--|--|--|--|--|--|
| Nmap | 端口扫描 | 最流行的网络探测和安全扫描工具 | [nmap/nmap](https://github.com/nmap/nmap) | 8.5k | 100M+ |
| Nuclei | Web扫描 | 快速且可定制的漏洞扫描器 | [projectdiscovery/nuclei](https://github.com/projectdiscovery/nuclei) | 15.2k | 50M+ |
| Nikto | Web扫描 | Web服务器扫描器，检测危险文件和过时软件 | [sullo/nikto](https://github.com/sullo/nikto) | 7.2k | 20M+ |
| Masscan | 端口扫描 | 互联网规模的端口扫描器，速度极快 | [robertdavidgraham/masscan](https://github.com/robertdavidgraham/masscan) | 21.5k | 10M+ |
| Hydra | 弱口令检测 | 登录密码破解工具，支持多种协议 | [vanhauser-thc/thc-hydra](https://github.com/vanhauser-thc/thc-hydra) | 12.8k | 30M+ |
| Acunetix | Web扫描 | 自动化Web应用安全测试工具 | [acunetix/acunetix](https://www.acunetix.com/) | - | 5M+ |
| DefectDojo | 漏洞管理 | 安全漏洞管理和协作平台 | [DefectDojo/django-DefectDojo](https://github.com/DefectDojo/django-DefectDojo) | 3.2k | 10M+ |
| Xray | Web扫描 | 安全评估工具，支持漏洞扫描和爬虫 | [chaitin/xray](https://github.com/chaitin/xray) | 8.9k | 15M+ |
| Arachni | Web扫描 | 功能丰富的Web应用安全扫描框架 | [Arachni/arachni](https://github.com/Arachni/arachni) | 4.2k | 8M+ |
| OpenVAS | 网络扫描 | 全功能漏洞扫描器，支持多种漏洞检测 | [greenbone/openvas-scanner](https://github.com/greenbone/openvas-scanner) | 3.8k | 50M+ |


#### 🍯 蜜罐系统

| 名称 | 类型 | 应用介绍 | 开源地址 | GitHub Stars | Docker Pulls |
|------|------|----------|-----------|--------------|---------------|
| T-Pot | 综合蜜罐 | 多蜜罐平台，集成了多种蜜罐系统和分析工具 | [telekom-security/tpotce](https://github.com/telekom-security/tpotce) | 4.8k | 10M+ |
| HoneyDrive | 蜜罐集合 | 包含多种蜜罐和分析工具的Linux发行版 | [bruteforce-lab/honeydrive](https://github.com/bruteforce-lab/honeydrive) | 1.2k | 1M+ |
| Cowrie | SSH蜜罐 | 中等交互式SSH和Telnet蜜罐，记录攻击者的行为 | [cowrie/cowrie](https://github.com/cowrie/cowrie) | 4.5k | 5M+ |
| Dionaea | 多协议蜜罐 | 捕获恶意软件的低交互蜜罐，支持多种协议 | [DinoTools/dionaea](https://github.com/DinoTools/dionaea) | 1.8k | 2M+ |
| Glastopf | Web蜜罐 | 模拟Web应用漏洞的低交互蜜罐 | [mushorg/glastopf](https://github.com/mushorg/glastopf) | 1.3k | 1M+ |
| KFSensor | 入侵检测 | 高级Windows蜜罐系统，模拟各种服务 | [kfsensor/kfsensor](https://github.com/kfsensor/kfsensor) | 1k | 500K+ |
| HoneyTrap | 多功能蜜罐 | 可扩展的蜜罐框架，支持多种协议和服务 | [honeytrap/honeytrap](https://github.com/honeytrap/honeytrap) | 1.7k | 1M+ |
| MHN | 蜜罐管理 | 现代蜜网管理系统，简化蜜罐部署和管理 | [threatstream/mhn](https://github.com/threatstream/mhn) | 3.8k | 2M+ |
| HonSSH | SSH代理 | SSH代理蜜罐，记录攻击者的所有SSH会话 | [tnich/honssh](https://github.com/tnich/honssh) | 1.1k | 500K+ |

### 📊 数据分析
#### 📊 BI工具

| 名称 | 类型 | 应用介绍 | 开源地址 | GitHub Stars | Docker Pulls |
|------|------|----------|-----------|--------------|---------------|
| Metabase | 数据分析 | 简单强大的数据分析和可视化工具，支持多种数据源 | [metabase/metabase](https://github.com/metabase/metabase) | 35.2k | 500M+ |
| Superset | 数据探索 | Apache开源的现代数据探索和可视化平台 | [apache/superset](https://github.com/apache/superset) | 55.8k | 200M+ |
| Redash | 数据可视化 | 支持多种数据源的查询和可视化工具，适合团队协作 | [getredash/redash](https://github.com/getredash/redash) | 24.5k | 100M+ |
| Grafana | 监控分析 | 功能强大的可观测性平台，支持多种数据源和插件 | [grafana/grafana](https://github.com/grafana/grafana) | 59.3k | 3.2B+ |
| Cube.js | 分析平台 | 开源的分析API平台，简化复杂数据分析 | [cube-js/cube.js](https://github.com/cube-js/cube.js) | 15.8k | 50M+ |
| Apache Zeppelin | 数据分析 | 基于Web的数据分析和可视化笔记本 | [apache/zeppelin](https://github.com/apache/zeppelin) | 6.2k | 20M+ |
| Tableau | 商业智能 | 专业的数据可视化和商业智能工具 | [tableau/tableau-server](https://github.com/tableau/tableau-server) | 2.5k | 100M+ |
| Looker | 数据平台 | 现代化的数据平台，支持自定义数据模型 | [looker/looker](https://github.com/looker/looker) | 1.8k | 50M+ |
| PowerBI | 商业分析 | 微软的商业分析工具，支持丰富的可视化效果 | [microsoft/powerbi-docker](https://github.com/microsoft/powerbi-docker) | 1.5k | 20M+ |

#### 📈 数据可视化
| 名称 | 类型 | 应用介绍 | 开源地址 | GitHub Stars | Docker Pulls |
|--|--|--|--|--|--|
| ECharts | 图表库 | 百度开源的强大图表库，支持丰富的可视化类型 | [apache/echarts](https://github.com/apache/echarts) | 56.8k | 100M+ |
| D3.js | 可视化库 | 灵活的JavaScript数据可视化库，支持自定义图表 | [d3/d3](https://github.com/d3/d3) | 106k | 50M+ |
| Chart.js | 图表库 | 简单易用的JavaScript图表库，适合快速实现 | [chartjs/Chart.js](https://github.com/chartjs/Chart.js) | 62.5k | 200M+ |
| DataV | 大屏可视化 | 阿里开源的数据大屏解决方案，支持丰富的可视化组件 | [DataV-Team/DataV](https://github.com/DataV-Team/DataV) | 8.2k | 10M+ |
| Plotly | 交互分析 | 支持多种编程语言的交互式科学可视化库 | [plotly/plotly.js](https://github.com/plotly/plotly.js) | 15.8k | 80M+ |
| Highcharts | 商业图表 | 功能强大的JavaScript图表库，支持多种图表类型 | [highcharts/highcharts](https://github.com/highcharts/highcharts) | 11.2k | 150M+ |
| AntV | 可视化套件 | 蚂蚁集团开源的数据可视化解决方案 | [antvis/G2](https://github.com/antvis/G2) | 11.5k | 30M+ |
| Three.js | 3D可视化 | 流行的JavaScript 3D可视化库 | [mrdoob/three.js](https://github.com/mrdoob/three.js) | 94.8k | 40M+ |
| Vega | 声明式可视化 | 声明式的可视化语法，支持复杂的交互设计 | [vega/vega](https://github.com/vega/vega) | 10.2k | 15M+ |

#### 🔄 日志引擎

| 名称 | 类型 | 应用介绍 | 开源地址 | GitHub Stars | Docker Pulls |
|--|--|--|--|--|--|
| Elasticsearch | 搜索引擎 | 分布式搜索和分析引擎，提供强大的全文检索和数据分析能力 | [elastic/elasticsearch](https://github.com/elastic/elasticsearch) | 65k | 1B+ |
| Logstash | 数据处理 | 动态数据收集管道，支持从多种来源采集数据并转换 | [elastic/logstash](https://github.com/elastic/logstash) | 13.5k | 500M+ |
| Kibana | 可视化平台 | 数据可视化和管理界面，让数据分析变得简单直观 | [elastic/kibana](https://github.com/elastic/kibana) | 18.7k | 500M+ |
| Fluentd | 日志收集 | 统一的日志层，支持多种数据源的高效日志收集 | [fluent/fluentd](https://github.com/fluent/fluentd) | 12.3k | 100M+ |
| Loki | 日志聚合 | 高效的日志聚合系统，专注于日志的存储和查询 | [grafana/loki](https://github.com/grafana/loki) | 20.5k | 200M+ |
| Vector | 数据管道 | 高性能的数据管道工具，用于收集、转换和路由可观测性数据 | [vectordotdev/vector](https://github.com/vectordotdev/vector) | 15.3k | 20M+ |
| Graylog | 日志平台 | 集中式日志管理平台，提供强大的搜索和告警功能 | [Graylog2/graylog2-server](https://github.com/Graylog2/graylog2-server) | 7.2k | 50M+ |
| Filebeat | 日志采集 | 轻量级的日志文件采集器，是Elastic Beat家族的一部分 | [elastic/beats](https://github.com/elastic/beats) | 11.8k | 300M+ |
| SigNoz | 可观测平台 | 开源的应用性能监控和可观测性平台，替代Datadog的开源方案 | [SigNoz/signoz](https://github.com/SigNoz/signoz) | 15.2k | 5M+ |
| GoAccess | 日志分析 | 实时Web日志分析器和交互式查看器，支持终端和浏览器界面 | [allinurl/goaccess](https://github.com/allinurl/goaccess) | 16.4k | 10M+ |


### 🧠 AI应用
#### 🤖 机器学习

| 名称 | 类型 | 应用介绍 | 开源地址 | GitHub Stars | Docker Pulls |
|------|------|----------|-----------|--------------|---------------|
| MLflow | 模型管理 | 开源的机器学习生命周期平台，支持实验跟踪和模型部署 | [mlflow/mlflow](https://github.com/mlflow/mlflow) | 15.8k | 100M+ |
| Kubeflow | ML平台 | 基于Kubernetes的机器学习工具包，用于模型开发和部署 | [kubeflow/kubeflow](https://github.com/kubeflow/kubeflow) | 13.2k | 50M+ |
| TensorFlow Serving | 模型服务 | TensorFlow官方的模型部署系统，支持模型版本管理 | [tensorflow/serving](https://github.com/tensorflow/serving) | 5.8k | 500M+ |
| Seldon Core | 推理引擎 | 生产级机器学习模型部署平台，支持多种框架 | [SeldonIO/seldon-core](https://github.com/SeldonIO/seldon-core) | 3.8k | 20M+ |
| BentoML | 模型部署 | 用于构建和部署机器学习服务的框架 | [bentoml/BentoML](https://github.com/bentoml/BentoML) | 5.2k | 10M+ |
| Polyaxon | ML平台 | 机器学习实验管理和模型部署平台 | [polyaxon/polyaxon](https://github.com/polyaxon/polyaxon) | 3.5k | 5M+ |
| DVC | 版本控制 | 数据版本控制和机器学习实验管理工具 | [iterative/dvc](https://github.com/iterative/dvc) | 12.2k | 15M+ |
| Ray | 分布式框架 | 用于构建分布式机器学习应用的框架 | [ray-project/ray](https://github.com/ray-project/ray) | 28.5k | 50M+ |
| Feast | 特征存储 | 机器学习特征存储，支持线上和线下特征管理 | [feast-dev/feast](https://github.com/feast-dev/feast) | 4.2k | 5M+ |

#### 🗣️ 自然语言处理

| 名称 | 类型 | 应用介绍 | 开源地址 | GitHub Stars | Docker Pulls |
|------|------|----------|-----------|--------------|---------------|
| Hugging Face | NLP平台 | 最流行的自然语言处理模型库和平台，提供数千个预训练模型 | [huggingface/transformers](https://github.com/huggingface/transformers) | 115k | 200M+ |
| spaCy | NLP框架 | 工业级的自然语言处理库，支持多种语言和任务 | [explosion/spaCy](https://github.com/explosion/spaCy) | 27.5k | 100M+ |
| NLTK | NLP工具包 | 自然语言处理的经典Python库，提供多种文本处理功能 | [nltk/nltk](https://github.com/nltk/nltk) | 12.8k | 50M+ |
| Rasa | 对话系统 | 开源的对话AI框架，用于构建聊天机器人和语音助手 | [RasaHQ/rasa](https://github.com/RasaHQ/rasa) | 16.5k | 100M+ |
| Gensim | 文本分析 | 主题建模和文档相似性分析库，适用于大规模文本处理 | [RaRe-Technologies/gensim](https://github.com/RaRe-Technologies/gensim) | 14.2k | 20M+ |
| FastText | 文本分类 | Facebook开发的高效文本分类和词向量库 | [facebookresearch/fastText](https://github.com/facebookresearch/fastText) | 24.8k | 10M+ |
| StanfordNLP | NLP工具包 | 斯坦福大学开发的自然语言处理工具包，支持多语言 | [stanfordnlp/stanza](https://github.com/stanfordnlp/stanza) | 6.8k | 5M+ |
| AllenNLP | NLP平台 | 基于PyTorch的自然语言处理研究库 | [allenai/allennlp](https://github.com/allenai/allennlp) | 11.5k | 10M+ |
| Flair | NLP框架 | 简单易用的NLP框架，专注于序列标注和文本分类 | [flairNLP/flair](https://github.com/flairNLP/flair) | 13.2k | 5M+ |

#### 👁️ 计算机视觉

| 名称 | 类型 | 应用介绍 | 开源地址 | GitHub Stars | Docker Pulls |
|------|------|----------|-----------|--------------|---------------|
| OpenCV | 视觉库 | 最流行的计算机视觉库，支持多种图像处理和视觉算法 | [opencv/opencv](https://github.com/opencv/opencv) | 72.5k | 500M+ |
| Detectron2 | 目标检测 | Facebook开发的目标检测和分割框架，基于PyTorch | [facebookresearch/detectron2](https://github.com/facebookresearch/detectron2) | 27.8k | 50M+ |
| YOLO | 目标检测 | 实时目标检测系统，速度快且准确率高 | [ultralytics/yolov5](https://github.com/ultralytics/yolov5) | 45.2k | 100M+ |
| MMDetection | 视觉工具箱 | OpenMMLab开发的目标检测工具箱，支持多种检测算法 | [open-mmlab/mmdetection](https://github.com/open-mmlab/mmdetection) | 25.8k | 20M+ |
| DeepLabCut | 姿态估计 | 用于动物姿态估计的深度学习工具箱 | [DeepLabCut/DeepLabCut](https://github.com/DeepLabCut/DeepLabCut) | 3.8k | 5M+ |
| EasyOCR | 文字识别 | 支持80多种语言的OCR系统，使用简单 | [JaidedAI/EasyOCR](https://github.com/JaidedAI/EasyOCR) | 19.5k | 30M+ |
| Tesseract OCR | 文字识别 | Google开发的OCR引擎，支持多种语言和格式 | [tesseract-ocr/tesseract](https://github.com/tesseract-ocr/tesseract) | 52.8k | 200M+ |
| Deepface | 人脸分析 | 轻量级的人脸识别和分析库，支持多种深度学习模型 | [serengil/deepface](https://github.com/serengil/deepface) | 8.5k | 10M+ |
| ImageAI | 视觉AI | 简单易用的计算机视觉Python库，支持图像预测和检测 | [OlafenwaMoses/ImageAI](https://github.com/OlafenwaMoses/ImageAI) | 7.8k | 5M+ |

#### 🔧 AI开发工具

| 名称 | 类型 | 应用介绍 | 开源地址 | GitHub Stars | Docker Pulls |
|------|------|----------|-----------|--------------|---------------|
| TensorFlow | 深度学习框架 | Google开发的端到端开源机器学习平台 | [tensorflow/tensorflow](https://github.com/tensorflow/tensorflow) | 178k | 1B+ |
| PyTorch | 深度学习框架 | Facebook开发的灵活深度学习框架，研究友好 | [pytorch/pytorch](https://github.com/pytorch/pytorch) | 72.5k | 500M+ |
| Jupyter | 交互式开发 | 支持多种编程语言的交互式计算环境 | [jupyter/docker-stacks](https://github.com/jupyter/docker-stacks) | 7.8k | 1B+ |
| Streamlit | 应用开发 | 快速构建和分享数据科学和机器学习应用的框架 | [streamlit/streamlit](https://github.com/streamlit/streamlit) | 28.5k | 100M+ |
| Gradio | 界面构建 | 为机器学习模型快速创建用户界面的Python库 | [gradio-app/gradio](https://github.com/gradio-app/gradio) | 21.2k | 50M+ |
| ONNX | 模型交换 | 开放神经网络交换格式，支持多框架模型转换 | [onnx/onnx](https://github.com/onnx/onnx) | 16.8k | 100M+ |
| TensorRT | 推理优化 | NVIDIA开发的高性能深度学习推理优化器 | [NVIDIA/TensorRT](https://github.com/NVIDIA/TensorRT) | 8.5k | 200M+ |
| Weights & Biases | 实验跟踪 | 机器学习实验跟踪和可视化工具 | [wandb/wandb](https://github.com/wandb/wandb) | 6.2k | 50M+ |
| DVC | 数据版本控制 | 用于机器学习项目的数据和模型版本控制系统 | [iterative/dvc](https://github.com/iterative/dvc) | 12.2k | 15M+ |

### 📝 文档协作
#### 📄 在线文档

| 名称 | 类型 | 应用介绍 | 开源地址 | GitHub Stars | Docker Pulls |
|------|------|----------|-----------|--------------|---------------|
| Collabora | 在线办公套件 | 基于LibreOffice的在线协作办公套件，支持文档、表格和演示文稿的实时编辑 | [collabora/code](https://github.com/CollaboraOnline/online) | 3.2k | 10M+ |
| OnlyOffice | 在线办公套件 | 功能完整的开源办公套件，支持文档、表格和演示文稿的协作编辑和版本控制 | [onlyoffice/documentserver](https://github.com/ONLYOFFICE/DocumentServer) | 4.5k | 100M+ |
| Etherpad | 实时文档 | 高度可定制的开源协作文本编辑器，支持实时编辑和插件扩展 | [etherpad/etherpad-lite](https://github.com/ether/etherpad-lite) | 14.2k | 10M+ |
| HedgeDoc | Markdown协作 | 实时协作的Markdown编辑器，支持多种格式导出和权限管理 | [hedgedoc/hedgedoc](https://github.com/hedgedoc/hedgedoc) | 4.8k | 5M+ |
| Cryptpad | 加密协作 | 零知识的加密协作平台，支持文档、表格、演示文稿等多种类型文件的安全协作 | [cryptpad/cryptpad](https://github.com/cryptpad/cryptpad) | 5.2k | 2M+ |

#### 📚 知识管理

| 名称 | 类型 | 应用介绍 | 开源地址 | GitHub Stars | Docker Pulls |
|------|------|----------|-----------|--------------|---------------|
| Wikijs | 知识库 | 现代化的开源Wiki系统，支持Markdown编辑、权限管理和多语言 | [requarks/wiki](https://github.com/requarks/wiki) | 21.5k | 50M+ |
| BookStack | 文档管理 | 简单而优雅的文档管理系统，支持章节组织和版本控制 | [bookstackapp/bookstack](https://github.com/BookStackApp/BookStack) | 12.8k | 30M+ |
| Outline | 知识库 | 团队知识库和文档管理工具，支持Markdown和实时协作 | [outline/outline](https://github.com/outline/outline) | 20.1k | 10M+ |
| Documize | 文档协作 | 智能文档协作平台，支持模板和工作流集成 | [documize/community](https://github.com/documize/community) | 1.8k | 1M+ |
| Docusaurus | 文档网站 | 易于维护的开源文档网站生成器，支持版本控制和多语言 | [facebook/docusaurus](https://github.com/facebook/docusaurus) | 49.2k | 5M+ |

#### 📋 项目管理

| 名称 | 类型 | 应用介绍 | 开源地址 | GitHub Stars | Docker Pulls |
|------|------|----------|-----------|--------------|---------------|
| Wekan | 看板工具 | 开源的看板工具，类似Trello，支持拖拽操作和团队协作 | [wekan/wekan](https://github.com/wekan/wekan) | 18.7k | 20M+ |
| Taiga | 项目管理 | 敏捷项目管理平台，支持Scrum和看板方法 | [taigaio/taiga](https://github.com/taigaio/taiga) | 6.2k | 5M+ |
| Planka | 看板工具 | 开源的项目管理工具，支持实时协作和任务跟踪 | [plankanban/planka](https://github.com/plankanban/planka) | 5.1k | 2M+ |
| Focalboard | 项目管理 | 开源的项目管理工具，Notion和Trello的替代品 | [mattermost/focalboard](https://github.com/mattermost/focalboard) | 16.5k | 5M+ |
| OpenProject | 项目管理 | 专业的项目管理软件，支持甘特图和敏捷方法 | [opf/openproject](https://github.com/opf/openproject) | 7.8k | 10M+ |

#### ✏️ 笔记工具

| 名称 | 类型 | 应用介绍 | 开源地址 | GitHub Stars | Docker Pulls |
|------|------|----------|-----------|--------------|---------------|
| Joplin | 笔记应用 | 开源的笔记和待办事项应用，支持Markdown和端到端加密 | [joplin/server](https://github.com/laurent22/joplin) | 38.5k | 5M+ |
| Trilium | 知识库 | 层次化笔记应用，支持丰富的笔记格式和脚本扩展 | [zadam/trilium](https://github.com/zadam/trilium) | 22.3k | 10M+ |
| Standard Notes | 加密笔记 | 端到端加密的笔记应用，注重隐私和长期数据保存 | [standardnotes/app](https://github.com/standardnotes/app) | 4.2k | 2M+ |
| AppFlowy | 工作空间 | 开源的Notion替代品，支持数据库视图和文档协作 | [appflowy/appflowy](https://github.com/AppFlowy-IO/AppFlowy) | 42.1k | 1M+ |
| Logseq | 知识图谱 | 隐私优先的知识管理和协作平台，支持大纲和双向链接 | [logseq/logseq](https://github.com/logseq/logseq) | 26.8k | 1M+ |

### ☁️ 云存储
#### 📁 文件存储

| 名称 | 类型 | 应用介绍 | 开源地址 | GitHub Stars | Docker Pulls |
|------|------|----------|-----------|--------------|---------------|
| Nextcloud | 文件存储 | 功能全面的私有云存储平台，支持文件同步、共享和协作 | [nextcloud/server](https://github.com/nextcloud/server) | 24.5k | 1B+ |
| Seafile | 文件存储 | 高性能的文件同步与共享平台，注重安全性和可靠性 | [haiwen/seafile](https://github.com/haiwen/seafile) | 11.2k | 100M+ |
| Owncloud | 文件存储 | 开源的个人云存储解决方案，提供文件访问和同步功能 | [owncloud/core](https://github.com/owncloud/core) | 8.5k | 500M+ |
| FileRun | 文件管理 | 轻量级的文件管理系统，支持在线预览和编辑文件 | [filerun/filerun](https://github.com/filerun/filerun) | 2.1k | 10M+ |
| Pydio Cells | 文件平台 | 企业级文件共享平台，提供先进的权限管理和协作功能 | [pydio/cells](https://github.com/pydio/cells) | 1.8k | 5M+ |

#### 🗄️ 对象存储

| 名称 | 类型 | 应用介绍 | 开源地址 | GitHub Stars | Docker Pulls |
|------|------|----------|-----------|--------------|---------------|
| MinIO | 对象存储 | 高性能的分布式对象存储服务，兼容Amazon S3 API | [minio/minio](https://github.com/minio/minio) | 41.2k | 1B+ |
| Ceph | 存储系统 | 分布式存储系统，提供对象、块和文件存储功能 | [ceph/ceph](https://github.com/ceph/ceph) | 12.5k | 100M+ |
| Zenko | 多云存储 | 多云数据控制器，支持跨云存储管理和迁移 | [scality/zenko](https://github.com/scality/zenko) | 1.2k | 10M+ |
| Swift | 对象存储 | OpenStack的对象存储项目，可扩展的分布式存储系统 | [openstack/swift](https://github.com/openstack/swift) | 2.5k | 50M+ |
| Garage | 对象存储 | 轻量级的S3兼容对象存储服务，适合边缘计算场景 | [garagehq/garage](https://github.com/garagehq/garage) | 3.8k | 5M+ |

#### 🔄 同步备份

| 名称 | 类型 | 应用介绍 | 开源地址 | GitHub Stars | Docker Pulls |
|------|------|----------|-----------|--------------|---------------|
| Syncthing | 文件同步 | 去中心化的连续文件同步工具，注重隐私和安全 | [syncthing/syncthing](https://github.com/syncthing/syncthing) | 55.8k | 100M+ |
| Duplicati | 备份工具 | 加密的在线备份工具，支持多种云存储服务 | [duplicati/duplicati](https://github.com/duplicati/duplicati) | 9.2k | 50M+ |
| Restic | 备份工具 | 快速、安全、高效的备份程序，支持多种后端存储 | [restic/restic](https://github.com/restic/restic) | 21.5k | 20M+ |
| Kopia | 备份工具 | 跨平台的备份工具，支持加密、重复数据删除和压缩 | [kopia/kopia](https://github.com/kopia/kopia) | 5.2k | 10M+ |
| BorgBackup | 备份工具 | 重复数据删除的备份程序，支持压缩和加密 | [borgbackup/borg](https://github.com/borgbackup/borg) | 9.8k | 15M+ |

#### 💾 网盘系统

| 名称 | 类型 | 应用介绍 | 开源地址 | GitHub Stars | Docker Pulls |
|------|------|----------|-----------|--------------|---------------|
| Cloudreve | 网盘系统 | 支持多家云存储的网盘系统，带有在线文件预览和分享功能 | [cloudreve/cloudreve](https://github.com/cloudreve/cloudreve) | 18.5k | 20M+ |
| Filebrowser | 文件管理 | 简单的文件管理界面，支持文件上传、删除、预览和分享 | [filebrowser/filebrowser](https://github.com/filebrowser/filebrowser) | 22.3k | 100M+ |
| AriaNg | 下载工具 | Aria2的Web前端，支持离线下载和BT下载功能 | [mayswind/AriaNg](https://github.com/mayswind/AriaNg) | 10.8k | 50M+ |
| Filestash | 文件管理 | 现代化的Web文件管理器，支持FTP、SFTP、WebDAV等协议 | [mickael-kerjean/filestash](https://github.com/mickael-kerjean/filestash) | 8.2k | 10M+ |
| Rclone | 云存储工具 | 命令行工具，用于管理云存储上的文件，支持多种云存储服务 | [rclone/rclone](https://github.com/rclone/rclone) | 40.5k | 30M+ |

### 🎮 游戏服务器
#### 🎲 游戏管理

| 名称 | 类型 | 应用介绍 | 开源地址 | GitHub Stars | Docker Pulls |
|------|------|----------|-----------|--------------|---------------|
| Pterodactyl | 游戏面板 | 强大的游戏服务器管理面板，支持多种游戏和自动化部署 | [pterodactyl/panel](https://github.com/pterodactyl/panel) | 12.5k | 50M+ |
| LinuxGSM | 服务器管理 | Linux游戏服务器管理器，支持多种游戏服务端的安装和管理 | [GameServerManagers/LinuxGSM](https://github.com/GameServerManagers/LinuxGSM) | 4.8k | 10M+ |
| Cuberite | MC服务端 | 高性能的Minecraft服务器，使用C++编写，注重性能和可扩展性 | [cuberite/cuberite](https://github.com/cuberite/cuberite) | 3.9k | 5M+ |
| Velocity | MC代理 | 现代化的Minecraft代理服务器，支持多服务器集群和负载均衡 | [PaperMC/Velocity](https://github.com/PaperMC/Velocity) | 2.1k | 15M+ |
| SteamCMD | Steam工具 | Steam游戏服务器的命令行工具，用于安装和更新游戏服务端 | [steamcmd/steamcmd](https://github.com/steamcmd/steamcmd) | 1.5k | 100M+ |
| Crafty | MC管理器 | 简单易用的Minecraft服务器Web管理面板 | [CraftyControl/Crafty](https://github.com/CraftyControl/Crafty) | 1.2k | 2M+ |

#### 🛠️ 游戏工具

| 名称 | 类型 | 应用介绍 | 开源地址 | GitHub Stars | Docker Pulls |
|------|------|----------|-----------|--------------|---------------|
| MCRcon | 远程控制 | Minecraft服务器的RCON客户端，支持远程命令执行 | [Tiiffi/mcrcon](https://github.com/Tiiffi/mcrcon) | 1.8k | 5M+ |
| AMP | 服务监控 | 游戏服务器应用管理面板，支持性能监控和自动重启 | [CubeCoders/AMP](https://github.com/CubeCoders/AMP) | 1.2k | 3M+ |
| ARRCON | 远程管理 | 通用的游戏服务器RCON工具，支持多种游戏协议 | [radj307/ARRCON](https://github.com/radj307/ARRCON) | 0.8k | 1M+ |
| GameDig | 状态查询 | 游戏服务器状态查询库，支持多种游戏协议 | [gamedig/node-gamedig](https://github.com/gamedig/node-gamedig) | 2.1k | 2M+ |
| LGSM-Web | Web面板 | LinuxGSM的Web管理界面，提供图形化的服务器管理 | [GameServerManagers/LGSM-Web](https://github.com/GameServerManagers/LGSM-Web) | 0.5k | 1M+ |

#### 🎯 Minecraft服务器

| 名称 | 类型 | 应用介绍 | 开源地址 | GitHub Stars | Docker Pulls |
|------|------|----------|-----------|--------------|---------------|
| Paper | MC服务端 | 高性能的Minecraft服务器，基于Spigot的优化分支 | [PaperMC/Paper](https://github.com/PaperMC/Paper) | 8.2k | 80M+ |
| Spigot | MC服务端 | 流行的Minecraft服务器，支持插件和高度自定义 | [SpigotMC/Spigot](https://github.com/SpigotMC/Spigot) | 4.5k | 60M+ |
| Purpur | MC服务端 | 基于Paper的高性能服务端，增加了更多自定义选项 | [PurpurMC/Purpur](https://github.com/PurpurMC/Purpur) | 1.8k | 20M+ |
| Waterfall | MC代理 | 高性能的Minecraft代理服务器，BungeeCord的优化分支 | [PaperMC/Waterfall](https://github.com/PaperMC/Waterfall) | 1.5k | 15M+ |
| MineOS | MC管理面板 | 基于Web的Minecraft服务器控制面板 | [hexparrot/mineos-node](https://github.com/hexparrot/mineos-node) | 1.2k | 5M+ |
| McMyAdmin | MC管理面板 | 专业的Minecraft服务器管理面板，支持插件和模组管理 | [McMyAdmin/MCMA](https://github.com/McMyAdmin/MCMA) | 0.9k | 10M+ |

#### 🎲 多人游戏服务器

| 名称 | 类型 | 应用介绍 | 开源地址 | GitHub Stars | Docker Pulls |
|------|------|----------|-----------|--------------|---------------|
| Valheim | 北欧神话 | Valheim专用服务器，支持模组和世界保存 | [lloesche/valheim-server](https://github.com/lloesche/valheim-server) | 2.8k | 30M+ |
| Factorio | 工厂模拟 | Factorio专用服务器，支持多人联机和MOD | [factoriotools/factorio](https://github.com/factoriotools/factorio) | 1.5k | 25M+ |
| Terraria | 沙盒冒险 | Terraria专用服务器，支持多人联机和地图管理 | [beardedio/terraria](https://github.com/beardedio/terraria) | 1.2k | 20M+ |
| CS:GO | 射击游戏 | Counter-Strike: Global Offensive专用服务器 | [CM2Walki/csgo](https://github.com/CM2Walki/csgo) | 1.1k | 40M+ |
| ARK | 生存游戏 | ARK: Survival Evolved专用服务器，支持MOD和多地图 | [thmhoag/arkserver](https://github.com/thmhoag/arkserver) | 0.9k | 15M+ |
| Rust | 生存游戏 | Rust专用服务器，支持插件和自定义配置 | [Didstopia/rust-server](https://github.com/Didstopia/rust-server) | 0.8k | 35M+ |

### 📡 网络工具
#### 🌐 网络代理

| 名称 | 类型 | 应用介绍 | 开源地址 | GitHub Stars | Docker Pulls |
|--|--|--|--|--|--|
| Traefik | 反向代理 | 现代化的HTTP反向代理和负载均衡器，自动服务发现和SSL配置 | [traefik/traefik](https://github.com/traefik/traefik) | 45k | 10B+ |
| HAProxy | 负载均衡 | 高性能的TCP/HTTP负载均衡器，支持多种负载均衡算法 | [haproxy/haproxy](https://github.com/haproxy/haproxy) | 4.2k | 1B+ |
| Nginx Proxy Manager | 反向代理 | 可视化的Nginx配置工具，支持SSL证书自动化管理 | [NginxProxyManager/nginx-proxy-manager](https://github.com/NginxProxyManager/nginx-proxy-manager) | 16k | 100M+ |
| Squid | 正向代理 | 功能丰富的Web缓存代理服务器，支持访问控制和缓存管理 | [squid-cache/squid](https://github.com/squid-cache/squid) | 1.5k | 500M+ |
| Caddy | 反向代理 | 自动HTTPS的Web服务器，配置简单，性能优异 | [caddyserver/caddy](https://github.com/caddyserver/caddy) | 50k | 200M+ |
| 3proxy | 多协议代理 | 支持HTTP、SOCKS、FTP等多种代理协议的轻量级代理服务器 | [3proxy/3proxy](https://github.com/3proxy/3proxy) | 2.8k | 50M+ |
| Envoy | 服务代理 | 云原生高性能边缘和服务代理，支持服务网格 | [envoyproxy/envoy](https://github.com/envoyproxy/envoy) | 22k | 500M+ |
| NGINX | 反向代理 | 高性能的HTTP和反向代理服务器，支持负载均衡和缓存 | [nginx/nginx](https://github.com/nginx/nginx) | 18k | 10B+ |

#### 🔐 VPN服务

| 名称 | 类型 | 应用介绍 | 开源地址 | GitHub Stars | Docker Pulls |
|--|--|--|--|--|--|
| OpenVPN | VPN服务 | 最流行的开源VPN解决方案，支持多种认证方式和加密协议 | [OpenVPN/openvpn](https://github.com/OpenVPN/openvpn) | 8.2k | 500M+ |
| WireGuard | VPN服务 | 新一代高性能VPN协议实现，配置简单，性能优异 | [WireGuard/wireguard-tools](https://github.com/WireGuard/wireguard-tools) | 7.1k | 200M+ |
| Pritunl | VPN管理 | 企业级OpenVPN服务器管理平台，支持多服务器部署 | [pritunl/pritunl](https://github.com/pritunl/pritunl) | 5.2k | 50M+ |
| OpenConnect | VPN服务 | 兼容Cisco AnyConnect的开源VPN客户端和服务器 | [openconnect/openconnect](https://github.com/openconnect/openconnect) | 3.1k | 30M+ |
| SoftEther | VPN服务 | 多协议VPN服务器，支持SSL-VPN、L2TP和IPsec | [SoftEtherVPN/SoftEtherVPN](https://github.com/SoftEtherVPN/SoftEtherVPN) | 9.8k | 100M+ |

#### 🌍 DNS服务

| 名称 | 类型 | 应用介绍 | 开源地址 | GitHub Stars | Docker Pulls |
|--|--|--|--|--|--|
| Pi-hole | 广告过滤 | 网络级广告和互联网跟踪器的黑洞，提供DNS级别的广告拦截 | [pi-hole/pi-hole](https://github.com/pi-hole/pi-hole) | 42k | 1B+ |
| CoreDNS | DNS服务器 | 灵活可扩展的DNS服务器，支持多种后端存储和插件系统 | [coredns/coredns](https://github.com/coredns/coredns) | 10.5k | 10B+ |
| AdGuard Home | 广告过滤 | 网络范围内的广告和跟踪器拦截DNS服务器 | [AdguardTeam/AdGuardHome](https://github.com/AdguardTeam/AdGuardHome) | 18k | 500M+ |
| Technitium DNS | DNS管理 | 跨平台的开源DNS服务器，支持DNS-over-HTTPS和DNS-over-TLS | [TechnitiumSoftware/DnsServer](https://github.com/TechnitiumSoftware/DnsServer) | 2.5k | 50M+ |
| PowerDNS | DNS服务器 | 企业级DNS服务器，支持多种后端数据库和高可用配置 | [PowerDNS/pdns](https://github.com/PowerDNS/pdns) | 3k | 100M+ |
| Unbound | DNS解析器 | 验证、递归和缓存DNS解析器，注重安全性和性能 | [NLnetLabs/unbound](https://github.com/NLnetLabs/unbound) | 1.2k | 200M+ |
| BIND | DNS服务器 | 最广泛使用的DNS软件，提供完整的DNS服务器功能 | [isc-projects/bind9](https://github.com/isc-projects/bind9) | 2.8k | 300M+ |
| DNSCrypt-proxy | DNS加密 | 支持现代加密DNS协议的DNS代理，提高DNS查询的安全性和隐私性 | [DNSCrypt/dnscrypt-proxy](https://github.com/DNSCrypt/dnscrypt-proxy) | 10k | 100M+ |

#### 📡 网络监控

| 名称 | 类型 | 应用介绍 | 开源地址 | GitHub Stars | Docker Pulls |
|--|--|--|--|--|--|
| Prometheus | 监控系统 | 开源的监控告警系统，支持多维度数据模型和强大的查询语言 | [prometheus/prometheus](https://github.com/prometheus/prometheus) | 50.2k | 2B+ |
| Zabbix | 监控平台 | 企业级分布式监控解决方案，支持自动发现和模板管理 | [zabbix/zabbix](https://github.com/zabbix/zabbix) | 4.2k | 500M+ |
| Grafana | 可视化 | 强大的指标数据和日志可视化平台，支持多种数据源 | [grafana/grafana](https://github.com/grafana/grafana) | 58k | 3B+ |
| Nagios | 监控系统 | 经典的IT基础设施监控系统，支持插件扩展和自定义监控 | [NagiosEnterprises/nagioscore](https://github.com/NagiosEnterprises/nagioscore) | 2.8k | 50M+ |
| Netdata | 实时监控 | 分布式的实时性能和健康监控系统，低资源占用 | [netdata/netdata](https://github.com/netdata/netdata) | 65.2k | 1B+ |

### 🤝 协同办公
#### 💬 团队沟通

| 名称 | 类型 | 应用介绍 | 开源地址 | GitHub Stars | Docker Pulls |
|------|------|----------|-----------|--------------|---------------|
| Rocket.Chat | 即时通讯 | 功能丰富的团队聊天平台，支持实时消息、文件共享和视频会议 | [RocketChat/Rocket.Chat](https://github.com/RocketChat/Rocket.Chat) | 37.2k | 500M+ |
| Mattermost | 团队协作 | 开源的企业级团队沟通平台，支持消息、文件共享和集成 | [mattermost/mattermost](https://github.com/mattermost/mattermost) | 27.1k | 100M+ |
| Element | 即时通讯 | 基于Matrix协议的安全通讯工具，支持端到端加密 | [vector-im/element-web](https://github.com/vector-im/element-web) | 9.2k | 50M+ |
| Jitsi Meet | 视频会议 | 高质量的开源视频会议平台，支持屏幕共享和聊天 | [jitsi/jitsi-meet](https://github.com/jitsi/jitsi-meet) | 20.3k | 200M+ |
| Let's Chat | 团队聊天 | 轻量级的团队聊天应用，支持文件上传和表情符号 | [sdelements/lets-chat](https://github.com/sdelements/lets-chat) | 9.5k | 10M+ |


#### 👥 项目协作

| 名称 | 类型 | 应用介绍 | 开源地址 | GitHub Stars | Docker Pulls |
|------|------|----------|-----------|--------------|---------------|
| Redmine | 项目管理 | 灵活的项目管理和问题跟踪系统，支持多项目和时间跟踪 | [redmine/redmine](https://github.com/redmine/redmine) | 4.8k | 100M+ |
| Kanboard | 看板工具 | 简单而强大的可视化项目管理工具，支持任务管理和时间跟踪 | [kanboard/kanboard](https://github.com/kanboard/kanboard) | 7.8k | 50M+ |
| Leantime | 项目管理 | 精益项目管理系统，适合小型团队和创业公司 | [leantime/leantime](https://github.com/leantime/leantime) | 3.2k | 5M+ |
| Phabricator | 开发协作 | 完整的软件开发协作平台，支持代码审查和任务管理 | [phacility/phabricator](https://github.com/phacility/phabricator) | 12.1k | 20M+ |
| Tuleap | 项目管理 | 企业级开源项目管理平台，支持敏捷开发和文档管理 | [Enalean/tuleap](https://github.com/Enalean/tuleap) | 1.2k | 5M+ |


#### ⚡ 工作流程

| 名称 | 类型 | 应用介绍 | 开源地址 | GitHub Stars | Docker Pulls |
|------|------|----------|-----------|--------------|---------------|
| n8n | 工作流自动化 | 强大的工作流自动化工具，支持多种服务集成和自定义节点 | [n8n-io/n8n](https://github.com/n8n-io/n8n) | 39.1k | 63M+ |
| Camunda | 流程引擎 | 开源的业务流程管理平台，支持BPMN工作流建模和执行 | [camunda/camunda-bpm](https://github.com/camunda/camunda-bpm) | 4.2k | 28M+ |
| Formio | 表单平台 | 企业级表单和API平台，支持拖拽式表单设计和工作流 | [formio/formio](https://github.com/formio/formio) | 2.9k | 10M+ |
| ProcessMaker | 工作流平台 | 企业级业务流程管理系统，支持流程设计和表单管理 | [processmaker/processmaker](https://github.com/processmaker/processmaker) | 2.1k | 5M+ |
| Activiti | 工作流引擎 | 轻量级业务流程引擎，支持BPMN 2.0标准 | [Activiti/Activiti](https://github.com/Activiti/Activiti) | 9.5k | 15M+ |


#### 📊 资源管理

| 名称 | 类型 | 应用介绍 | 开源地址 | GitHub Stars | Docker Pulls |
|------|------|----------|-----------|--------------|---------------|
| ERPNext | ERP系统 | 全面的企业资源规划系统，支持财务、库存和人力资源管理 | [frappe/erpnext](https://github.com/frappe/erpnext) | 15.8k | 50M+ |
| Odoo | 企业管理 | 模块化的企业管理软件，覆盖CRM、财务、库存等领域 | [odoo/odoo](https://github.com/odoo/odoo) | 31.2k | 100M+ |
| Snipe-IT | 资产管理 | IT资产管理系统，支持设备跟踪和维护管理 | [snipe/snipe-it](https://github.com/snipe/snipe-it) | 8.9k | 20M+ |
| Dolibarr | 企业管理 | 中小企业ERP/CRM系统，支持销售、财务和库存管理 | [Dolibarr/dolibarr](https://github.com/Dolibarr/dolibarr) | 4.2k | 10M+ |
| OrangeHRM | 人力资源 | 全面的人力资源管理系统，支持员工信息和考勤管理 | [orangehrm/orangehrm](https://github.com/orangehrm/orangehrm) | 1.8k | 5M+ |


### 🗂️ 个人知识管理
#### 📝 笔记系统

| 名称 | 类型 | 应用介绍 | 开源地址 | GitHub Stars | Docker Pulls |
|------|------|----------|-----------|--------------|---------------|
| Joplin | 笔记应用 | 开源的笔记和待办事项应用，支持Markdown和端到端加密 | [joplin/server](https://github.com/laurent22/joplin) | 38.5k | 5M+ |
| Trilium | 知识库 | 层次化笔记应用，支持丰富的笔记格式和脚本扩展 | [zadam/trilium](https://github.com/zadam/trilium) | 22.3k | 10M+ |
| AppFlowy | 工作空间 | 开源的Notion替代品，支持数据库视图和文档协作 | [appflowy/appflowy](https://github.com/AppFlowy-IO/AppFlowy) | 42.1k | 1M+ |
| Logseq | 知识图谱 | 隐私优先的知识管理和协作平台，支持大纲和双向链接 | [logseq/logseq](https://github.com/logseq/logseq) | 26.8k | 1M+ |
| Dendron | 知识库 | 基于VSCode的层次化笔记系统，适合开发者使用 | [dendronhq/dendron](https://github.com/dendronhq/dendron) | 4.2k | 500k+ |

#### ✅ 任务管理

| 名称 | 类型 | 应用介绍 | 开源地址 | GitHub Stars | Docker Pulls |
|------|------|----------|-----------|--------------|---------------|
| Vikunja | 任务管理 | 现代化的待办事项和项目管理工具，支持看板和列表视图 | [vikunja/vikunja](https://github.com/go-vikunja/vikunja) | 3.2k | 2M+ |
| Super Productivity | 时间管理 | 集成了番茄钟和任务追踪的个人生产力工具 | [johannesjo/super-productivity](https://github.com/johannesjo/super-productivity) | 8.1k | 500k+ |
| Habitica | 习惯养成 | 将习惯养成游戏化的任务管理工具 | [HabitRPG/habitica](https://github.com/HabitRPG/habitica) | 10.2k | 1M+ |
| TaskBoard | 任务看板 | 简单的个人和小团队任务管理工具 | [kiswa/taskboard](https://github.com/kiswa/taskboard) | 1.2k | 200k+ |
| Tracks | 时间管理 | 基于GTD理念的任务管理系统 | [TracksApp/tracks](https://github.com/TracksApp/tracks) | 1.5k | 100k+ |

#### 🔖 书签管理

| 名称 | 类型 | 应用介绍 | 开源地址 | GitHub Stars | Docker Pulls |
|------|------|----------|-----------|--------------|---------------|
| Linkding | 书签管理 | 简洁的个人书签管理工具，支持标签和搜索功能 | [sissbruecker/linkding](https://github.com/sissbruecker/linkding) | 3.8k | 5M+ |
| Shiori | 书签管理 | 简单的自托管书签管理器，支持离线阅读和标签 | [go-shiori/shiori](https://github.com/go-shiori/shiori) | 8.5k | 2M+ |
| Shaarli | 链接分享 | 个人的链接分享平台，支持私密和公开分享 | [shaarli/shaarli](https://github.com/shaarli/shaarli) | 4.2k | 1M+ |
| Wallabag | 稍后阅读 | 保存网页内容的工具，支持标签和全文搜索 | [wallabag/wallabag](https://github.com/wallabag/wallabag) | 7.8k | 10M+ |
| Pinry | 图文收藏 | 图片书签收藏工具，类似Pinterest的自托管方案 | [pinry/pinry](https://github.com/pinry/pinry) | 3.1k | 500k+ |

#### 👤 个人资料

| 名称 | 类型 | 应用介绍 | 开源地址 | GitHub Stars | Docker Pulls |
|------|------|----------|-----------|--------------|---------------|
| Bitwarden | 密码管理 | 安全的密码管理器，支持多设备同步和密码共享 | [bitwarden/server](https://github.com/bitwarden/server) | 12.8k | 50M+ |
| Monica | 个人CRM | 个人关系管理系统，记录联系人信息和互动 | [monicahq/monica](https://github.com/monicahq/monica) | 19.2k | 10M+ |
| Paperless-ngx | 文档管理 | 文档扫描和归档系统，支持OCR和自动标签 | [paperless-ngx/paperless-ngx](https://github.com/paperless-ngx/paperless-ngx) | 12.5k | 5M+ |
| Wagtail | 个人网站 | 灵活的个人网站和博客系统，基于Django开发 | [wagtail/wagtail](https://github.com/wagtail/wagtail) | 15.8k | 2M+ |
| RedNotebook | 日记工具 | 支持标签和模板的个人日记应用 | [jendrikseipp/rednotebook](https://github.com/jendrikseipp/rednotebook) | 2.1k | 100k+ |


## 贡献指南

欢迎贡献！请阅读[贡献指南](CONTRIBUTING.md)了解如何开始。

### 贡献标准

- 确保建议的资源是高质量的
- 添加新资源时请提供简短的中文描述
- 保持分类的整洁和逻辑性
- 检查链接的有效性

