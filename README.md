<div class="Box-sc-g0xbh4-0 bJMeLZ js-snippet-clipboard-copy-unpositioned" data-hpc="true"><article class="markdown-body entry-content container-lg" itemprop="text"><p align="center" dir="auto">
<a target="_blank" rel="noopener noreferrer" href="/kubero-dev/kubero/blob/main/docs/logo/kubero-logo-horizontal.png"><img src="/kubero-dev/kubero/raw/main/docs/logo/kubero-logo-horizontal.png" style="max-width: 100%;"></a>
</p>
<hr>
<br>
<p dir="auto"><a href="https://github.com/kubero-dev/kubero/blob/main/LICENSE"><img alt="执照" src="https://camo.githubusercontent.com/17d5987de862b8694f05f03ea3ed16c46ed8c6f61a7d66b45a333414bf037efa/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f6c6963656e73652f6b756265726f2d6465762f6b756265726f3f7374796c653d666c61742d73717561726526636f6c6f723d626c7565" data-canonical-src="https://img.shields.io/github/license/kubero-dev/kubero?style=flat-square&amp;color=blue" style="max-width: 100%;"></a>
<a href="https://github.com/kubero-dev/kubero/releases/latest"><img alt="GitHub 版本（按日期排序）" src="https://camo.githubusercontent.com/ab2c7b8e0092573c4c9e3bb8947fd42f03bab642e0e9115eba8f58cfd9d048e2/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f762f72656c656173652f6b756265726f2d6465762f6b756265726f3f7374796c653d666c61742d73717561726526636f6c6f723d627269676874677265656e" data-canonical-src="https://img.shields.io/github/v/release/kubero-dev/kubero?style=flat-square&amp;color=brightgreen" style="max-width: 100%;"></a>
<a href="https://discord.gg/tafRPMWS4r" rel="nofollow"><img alt="不和谐" src="https://camo.githubusercontent.com/89d4b4e4c707ef4aa421088fe38a35b0627bcb6064eecef99d9d34d7c899e9e9/68747470733a2f2f696d672e736869656c64732e696f2f646973636f72642f313035313234393934373437323832363430383f7374796c653d666c61742d737175617265" data-canonical-src="https://img.shields.io/discord/1051249947472826408?style=flat-square" style="max-width: 100%;"></a>
<a href="https://github.com/kubero-dev/kubero/releases/latest"><img alt="GitHub（预）发布日期" src="https://camo.githubusercontent.com/d8d9402aba2a5cacc33c4496429c265dbf9d181423b5b607c279633a6f0b10f6/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f72656c656173652d646174652d7072652f6b756265726f2d6465762f6b756265726f3f7374796c653d666c61742d737175617265" data-canonical-src="https://img.shields.io/github/release-date-pre/kubero-dev/kubero?style=flat-square" style="max-width: 100%;"></a>
<a href="https://demo.kubero.dev" rel="nofollow"><img alt="演示" src="https://camo.githubusercontent.com/ead2a5cc563f325c77990b07d63452290782a6b775f0acb3e5303ed3c265e07b/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f64656d6f2d75702d7375636573733f7374796c653d666c61742d73717561726526636f6c6f723d626c7565" data-canonical-src="https://img.shields.io/badge/demo-up-sucess?style=flat-square&amp;color=blue" style="max-width: 100%;"></a></p>
<br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
Kubero [发音：Kube Hero] 是一个完全自托管的内部开发者平台 (IDP)，它将 Heroku 的工作流程引入您的 Kubernetes 集群。它使您能够通过几次点击来部署应用程序。它具有内置的 CI/CD 管道并支持多个暂存环境。
</font></font><br>
<br>
<p dir="auto"><animated-image data-catalyst=""><a target="_blank" rel="noopener noreferrer" href="/kubero-dev/kubero/blob/main/docs/screenshots/createapp.gif" data-target="animated-image.originalLink"><img src="/kubero-dev/kubero/raw/main/docs/screenshots/createapp.gif" style="max-width: 100%; display: inline-block;" data-target="animated-image.originalImage"></a>
      <span class="AnimatedImagePlayer" data-target="animated-image.player" hidden="">
        <a data-target="animated-image.replacedLink" class="AnimatedImagePlayer-images" href="https://github.com/kubero-dev/kubero/blob/main/docs/screenshots/createapp.gif" target="_blank">
          
         
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">更多</font></font><a href="https://docs.kubero.dev/screenshots" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">截图</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和完整视频请见
</font></font><a href="https://www.youtube.com/watch?v=kmqhddc6UlI" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">YouTube</font></font></a></p><p dir="auto"></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">工作原理 (</font></font><a href="https://demo.kubero.dev" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">演示</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">)</font></font></h2><a id="user-content-how-it-works-demo" class="anchor" aria-label="永久链接：工作原理（演示）" href="#how-it-works-demo"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ol dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">创建包含所需阶段（审查、测试、阶段、生产）的管道</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">将管道连接到您的 git 存储库（Github、Bitbucket、Gitlab、Gitea、Gogs）</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用 cronjobs 和插件配置你的应用程序</font></font></li>
</ol>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Kubero 会启动两个容器：一个用于克隆您的存储库，另一个用于构建您的应用程序。构建完成后，Kubero 将启动最终容器并通过配置的域使其可访问。</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">特征</font></font></h2><a id="user-content-features" class="anchor" aria-label="固定链接：功能" href="#features"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">为所有应用程序</font><font style="vertical-align: inherit;">创建无限的 CI/CD 管道，最多可达 4 个独立的</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">暂存环境</font></font></strong><font style="vertical-align: inherit;"></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">打开/关闭拉取请求后</font><font style="vertical-align: inherit;">自动构建、启动和清理</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">审核应用程序</font></font></strong><font style="vertical-align: inherit;"></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">根据分支或标签的推送</font><font style="vertical-align: inherit;">自动</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">重新部署应用程序</font></font></strong><font style="vertical-align: inherit;"></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">将计划任务创建为</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">cronjobs</font></font></strong></li>
<li><font style="vertical-align: inherit;"></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用模板</font></font></strong> <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">部署知名应用程序</font></font><a href="https://www.kubero.dev/templates" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（Wordpress、Grafana 等）</font></font></a></li>
<li><font style="vertical-align: inherit;"><strong><font style="vertical-align: inherit;">无需编写 Helm Charts 即可</font></strong><font style="vertical-align: inherit;">轻松在 Kubernetes 上部署 Docker 容器</font></font><strong><font style="vertical-align: inherit;"></font></strong></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">为您的应用程序部署</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">附加组件</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（PostgreSQL、Redis</font></font><a href="https://github.com/kubero-dev/kubero#preconfigured-add-ons"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">等......</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">）</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在 Web UI 中</font><font style="vertical-align: inherit;">轻松访问</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">应用程序日志</font></font></strong><font style="vertical-align: inherit;"></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在 Web UI 中</font><font style="vertical-align: inherit;">轻松安全地</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">重启应用程序</font></font></strong><font style="vertical-align: inherit;"></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">对正在运行的应用程序</font><font style="vertical-align: inherit;">进行触发或定期的</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">漏洞扫描</font></font></strong><font style="vertical-align: inherit;"></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">带有</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">API 和 CLI</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，可与您现有的工具和 CI/CD 集成</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">内置</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">容器 Web 控制台</font></font></strong></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">构建并部署</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">通知</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">至 Discord/Slack/Webhooks</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">集成</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">指标和监控</font></font></strong></li>
<li><strong><font style="vertical-align: inherit;"></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用 Github 和 Oauth2 进行</font><strong><font style="vertical-align: inherit;">SSO</font></strong></font></li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">支持的 GIT 存储库（托管和自托管）</font></font></h2><a id="user-content-supported-git-repositories-hosted-and-self-hosted" class="anchor" aria-label="永久链接：支持的 GIT 存储库（托管和自托管）" href="#supported-git-repositories-hosted-and-self-hosted"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">希特亚 / 福尔热霍</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">戈格斯</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Github</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">GitLab</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Bitbucket</font></font></li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">测试语言/框架</font></font></h2><a id="user-content-tested-languagesframeworks" class="anchor" aria-label="永久链接：经过测试的语言/框架" href="#tested-languagesframeworks"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">基本上</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">所有</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">可以打包在单个容器中的东西都可以通过 Kubero 部署。</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">GoLang（包括 Hugo、gin-gonic）</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Python（包括 Flask）</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">JavaScript/NodeJS</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">PHP（包括 Laravel）</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Ruby（包括 Rails）</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">静态 HTML</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Rust（包括 Rocket）</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">...</font></font></li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您可以在此处找到预配置的构建包和示例：
 </font></font><a href="https://github.com/kubero-dev/buildpacks"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https：//github.com/kubero-dev/buildpacks</font></font></a></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">附加组件</font></font></h2><a id="user-content-add-ons" class="anchor" aria-label="永久链接：附加组件" href="#add-ons"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<table>
<thead>
<tr>
<th></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">添加在</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">维护者</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">内置*</font></font></th>
</tr>
</thead>
<tbody>
<tr>
<td><a target="_blank" rel="noopener noreferrer" href="/kubero-dev/kubero/blob/main/client/public/img/addons/MySQL.png"><img src="/kubero-dev/kubero/raw/main/client/public/img/addons/MySQL.png" width="30px" style="max-width: 100%;"></a></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">MySQL</font></font></td>
<td><a href="https://github.com/bitnami/charts/tree/main/bitnami/mysql"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">比特纳米</font></font></a></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✅</font></font></td>
</tr>
<tr>
<td><a target="_blank" rel="noopener noreferrer" href="/kubero-dev/kubero/blob/main/client/public/img/addons/postgresql.png"><img src="/kubero-dev/kubero/raw/main/client/public/img/addons/postgresql.png" width="30px" style="max-width: 100%;"></a></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">PostgreSQL</font></font></td>
<td><a href="https://github.com/bitnami/charts/tree/main/bitnami/postgresql"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">比特纳米</font></font></a></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✅</font></font></td>
</tr>
<tr>
<td><a target="_blank" rel="noopener noreferrer" href="/kubero-dev/kubero/blob/main/client/public/img/addons/Redis.png"><img src="/kubero-dev/kubero/raw/main/client/public/img/addons/Redis.png" width="30px" style="max-width: 100%;"></a></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Redis</font></font></td>
<td><a href="https://github.com/bitnami/charts/tree/main/bitnami/redis"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">比特纳米</font></font></a></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✅</font></font></td>
</tr>
<tr>
<td><a target="_blank" rel="noopener noreferrer" href="/kubero-dev/kubero/blob/main/client/public/img/addons/MongoDB.png"><img src="/kubero-dev/kubero/raw/main/client/public/img/addons/MongoDB.png" width="30px" style="max-width: 100%;"></a></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">MongoDB</font></font></td>
<td><a href="https://github.com/bitnami/charts/tree/main/bitnami/mongodb"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">比特纳米</font></font></a></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✅</font></font></td>
</tr>
<tr>
<td><a target="_blank" rel="noopener noreferrer" href="/kubero-dev/kubero/blob/main/client/public/img/addons/Elasticsearch.png"><img src="/kubero-dev/kubero/raw/main/client/public/img/addons/Elasticsearch.png" width="30px" style="max-width: 100%;"></a></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Elasticsearch</font></font></td>
<td><a href="https://github.com/bitnami/charts/tree/main/bitnami/elasticsearch"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">比特纳米</font></font></a></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✅</font></font></td>
</tr>
<tr>
<td><a target="_blank" rel="noopener noreferrer" href="/kubero-dev/kubero/blob/main/client/public/img/addons/Kafka.png"><img src="/kubero-dev/kubero/raw/main/client/public/img/addons/Kafka.png" width="30px" style="max-width: 100%;"></a></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">卡夫卡</font></font></td>
<td><a href="https://github.com/bitnami/charts/tree/main/bitnami/kafka"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">比特纳米</font></font></a></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✅</font></font></td>
</tr>
<tr>
<td><a target="_blank" rel="noopener noreferrer" href="/kubero-dev/kubero/blob/main/client/public/img/addons/CouchDB.png"><img src="/kubero-dev/kubero/raw/main/client/public/img/addons/CouchDB.png" width="30px" style="max-width: 100%;"></a></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CouchDB</font></font></td>
<td><a href="https://apache.github.io/couchdb-helm" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">阿帕奇</font></font></a></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✅</font></font></td>
</tr>
<tr>
<td><a target="_blank" rel="noopener noreferrer" href="/kubero-dev/kubero/blob/main/client/public/img/addons/Haraka.png"><img src="/kubero-dev/kubero/raw/main/client/public/img/addons/Haraka.png" width="30px" style="max-width: 100%;"></a></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Haraka 邮件服务器</font></font></td>
<td><a href="https://github.com/kubero-dev/haraka-docker"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">库贝罗</font></font></a></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✅</font></font></td>
</tr>
<tr>
<td><a target="_blank" rel="noopener noreferrer" href="/kubero-dev/kubero/blob/main/client/public/img/addons/Memcached.png"><img src="/kubero-dev/kubero/raw/main/client/public/img/addons/Memcached.png" width="30px" style="max-width: 100%;"></a></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">内存缓存</font></font></td>
<td><a href="https://github.com/bitnami/charts/tree/main/bitnami/memcached"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">比特纳米</font></font></a></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✅</font></font></td>
</tr>
<tr>
<td><a target="_blank" rel="noopener noreferrer" href="/kubero-dev/kubero/blob/main/client/public/img/addons/RabbitMQ.png"><img src="/kubero-dev/kubero/raw/main/client/public/img/addons/RabbitMQ.png" width="30px" style="max-width: 100%;"></a></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">RabbitMQ</font></font></td>
<td><a href="https://github.com/bitnami/charts/tree/main/bitnami/rabbitmq"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">比特纳米</font></font></a></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✅</font></font></td>
</tr>
<tr>
<td><a target="_blank" rel="noopener noreferrer" href="/kubero-dev/kubero/blob/main/client/public/img/addons/cloudflare.svg"><img src="/kubero-dev/kubero/raw/main/client/public/img/addons/cloudflare.svg" width="30px" style="max-width: 100%;"></a></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">克洛德弗雷隧道</font></font></td>
<td><a href="https://github.com/adyanth/cloudflare-operator"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">石竹</font></font></a></td>
<td></td>
</tr>
<tr>
<td><a target="_blank" rel="noopener noreferrer" href="/kubero-dev/kubero/blob/main/client/public/img/addons/Minio.png"><img src="/kubero-dev/kubero/raw/main/client/public/img/addons/Minio.png" width="30px" style="max-width: 100%;"></a></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">米尼奥</font></font></td>
<td><a href="https://artifacthub.io/packages/olm/community-operators/minio-operator" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">米尼奥</font></font></a></td>
<td></td>
</tr>
<tr>
<td><a target="_blank" rel="noopener noreferrer" href="/kubero-dev/kubero/blob/main/client/public/img/addons/MongoDB.png"><img src="/kubero-dev/kubero/raw/main/client/public/img/addons/MongoDB.png" width="30px" style="max-width: 100%;"></a></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Percona MongoDB 集群</font></font></td>
<td><a href="https://artifacthub.io/packages/olm/community-operators/mongodb-operator" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">佩科纳</font></font></a></td>
<td></td>
</tr>
<tr>
<td><a target="_blank" rel="noopener noreferrer" href="/kubero-dev/kubero/blob/main/client/public/img/addons/postgresql.png"><img src="/kubero-dev/kubero/raw/main/client/public/img/addons/postgresql.png" width="30px" style="max-width: 100%;"></a></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">松脆的 Postgres 集群</font></font></td>
<td><a href="https://artifacthub.io/packages/olm/community-operators/postgresql" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">脆脆的数据</font></font></a></td>
<td></td>
</tr>
<tr>
<td><a target="_blank" rel="noopener noreferrer" href="/kubero-dev/kubero/blob/main/client/public/img/addons/Redis.png"><img src="/kubero-dev/kubero/raw/main/client/public/img/addons/Redis.png" width="30px" style="max-width: 100%;"></a></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Redis 集群</font></font></td>
<td><a href="https://artifacthub.io/packages/olm/community-operators/redis-operator" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">奥普斯特里</font></font></a></td>
<td></td>
</tr>
<tr>
<td><a target="_blank" rel="noopener noreferrer" href="/kubero-dev/kubero/blob/main/client/public/img/addons/CockroachDB.svg"><img src="/kubero-dev/kubero/raw/main/client/public/img/addons/CockroachDB.svg" width="30px" style="max-width: 100%;"></a></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">蟑螂数据库</font></font></td>
<td><a href="https://artifacthub.io/packages/olm/community-operators/cockroachdb" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">蟑螂数据库</font></font></a></td>
<td></td>
</tr>
</tbody>
</table>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">* 随附 Kubero Operator</font></font></p>
<div class="markdown-heading" dir="auto"><h4 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">计划中的附加组件</font></font></h4><a id="user-content-planned-add-ons" class="anchor" aria-label="固定链接：计划中的附加组件" href="#planned-add-ons"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><a href="https://aerospike.com/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">航空尖峰</font></font></a></li>
<li><a href="https://pingcap.com/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">TiDB</font></font></a></li>
<li><a href="https://www.arangodb.com/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安格数据库</font></font></a></li>
<li><a href="https://cassandra.apache.org/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">卡桑德拉</font></font></a></li>
<li><a href="https://www.influxdata.com/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">流入数据库</font></font></a></li>
<li><a href="https://mariadb.org/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">玛拉雅数据库</font></font></a></li>
<li><a href="https://prometheus.io/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">普罗米修斯</font></font></a></li>
<li><a href="https://github.com/unagex/immudb-operator"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">免疫数据库</font></font></a></li>
</ul>
<div class="markdown-heading" dir="auto"><h4 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">长期未来附加组件</font></font></h4><a id="user-content-longterm-future-add-ons" class="anchor" aria-label="永久链接：长期未来附加组件" href="#longterm-future-add-ons"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><a href="https://crossplane.io/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">横平面</font></font></a></li>
<li><a href="https://neo4j.com/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Neo4j</font></font></a></li>
<li><a href="https://prestodb.io/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">普雷斯托</font></font></a></li>
<li><a href="https://www.timescale.com/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">时间尺度数据库</font></font></a></li>
<li><a href="https://zookeeper.apache.org/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Zookeeper</font></font></a></li>
<li><a href="https://rethinkdb.com/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">重新思考数据库</font></font></a></li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">60 多个应用程序模板（类似于 Heroku Buttons）</font></font></h2><a id="user-content-60-application-templates-similar-to-heroku-buttons" class="anchor" aria-label="永久链接：60 多个应用程序模板（类似于 Heroku Buttons）" href="#60-application-templates-similar-to-heroku-buttons"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">WordPress 的</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">格拉法纳</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Bluesky PDS（个人数据服务器）</font></font></li>
<li><a href="https://uptime.kuma.pet" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">隈</font></font></a></li>
<li><a href="https://github.com/zadam/trilium"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Trilium 笔记</font></font></a></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">...</font></font></li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"></font><a href="https://www.kubero.dev/templates/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在此处</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">查看完整列表</font><font style="vertical-align: inherit;">或提交您自己的应用程序！</font></font><a href="https://github.com/kubero-dev/kubero/blob/main/services/"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在此处阅读</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如何操作。</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">基本概念</font></font></h2><a id="user-content-basic-concept" class="anchor" aria-label="固定链接：基本概念" href="#basic-concept"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Kubero 是 Kubernetes 原生的，可以在任何 Kubernetes 实例上运行两个容器。
</font></font><br>
<br></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="/kubero-dev/kubero/blob/main/docs/img/highlevel.png"><img src="/kubero-dev/kubero/raw/main/docs/img/highlevel.png" style="max-width: 100%;"></a></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">快速开始</font></font></h2><a id="user-content-quickstart" class="anchor" aria-label="永久链接：快速入门" href="#quickstart"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">1）下载并解压</font></font><a href="https://github.com/kubero-dev/kubero-cli/releases/latest"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Kubero CLI</font></font></a></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（MacOS、Linux、Windows）</font></font></p><p dir="auto"></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">二进制文件（MacOS、Linux）</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>curl -fsSL get.kubero.dev | bash
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="curl -fsSL get.kubero.dev | bash" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Brew（MacOS、Linux）</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>brew tap kubero-dev/kubero
brew install kubero-cli
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="brew tap kubero-dev/kubero
brew install kubero-cli" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2）运行</font></font><code>kubero install</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">以在新的或现有的集群上安装所有组件</font></font></strong></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您可以自带集群，也可以在以下任一提供商上安装 kubero 来创建一个集群：</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">吉科</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">尺度道</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">数字海洋</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">利诺德</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">种类（本地）</font></font></li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文档</font></font></h2><a id="user-content-documentation" class="anchor" aria-label="永久链接：文档" href="#documentation"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><a href="https://docs.kubero.dev/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://docs.kubero.dev/</font></font></a></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">路线图</font></font></h2><a id="user-content-roadmap" class="anchor" aria-label="永久链接：路线图" href="#roadmap"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><a href="https://github.com/orgs/kubero-dev/projects/1/views/3"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://github.com/orgs/kubero-dev/projects/1/views/3</font></font></a></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">社区</font></font></h2><a id="user-content-community" class="anchor" aria-label="固定链接：社区" href="#community"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><a href="https://discord.gg/tafRPMWS4r" rel="nofollow"><img src="https://camo.githubusercontent.com/f0074147786c6a230f6b66c26c9551255ca33a3ad1ae109ba1552d311c4bffae/68747470733a2f2f646973636f72646170702e636f6d2f6170692f6775696c64732f313035313234393934373437323832363430382f7769646765742e706e673f7374796c653d62616e6e657232" alt="kubero Discord 服务器横幅" data-canonical-src="https://discordapp.com/api/guilds/1051249947472826408/widget.png?style=banner2" style="max-width: 100%;"></a></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">贡献</font></font></h2><a id="user-content-contributing" class="anchor" aria-label="永久链接：贡献" href="#contributing"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">欢迎各界投稿！</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">打开一个问题</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">添加功能或打开功能请求</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在讨论中讨论想法</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">修正拼写错误</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">贡献代码</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">撰写文章</font></font></li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">支持该项目</font></font></h2><a id="user-content-supporting-this-project" class="anchor" aria-label="永久链接：支持此项目" href="#supporting-this-project"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">主演这个项目是一个巨大的动力。⭐谢谢！</font></font></p>
<p dir="auto"><a href="https://starchart.cc/kubero-dev/kubero" rel="nofollow"><img src="https://camo.githubusercontent.com/57a1a588a49cd0a8d1a9d31fafa78e01bbe67d05974216508920e34c7cb876b9/68747470733a2f2f7374617263686172742e63632f6b756265726f2d6465762f6b756265726f2e737667" alt="随着时间的推移，观星者" data-canonical-src="https://starchart.cc/kubero-dev/kubero.svg" style="max-width: 100%;"></a></p>
</article></div>
