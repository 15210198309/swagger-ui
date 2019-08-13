# <img src="https://raw.githubusercontent.com/swagger-api/swagger.io/wordpress/images/assets/SWU-logo-clr.png" height="80">

[![NPM version](https://badge.fury.io/js/swagger-ui.svg)](http://badge.fury.io/js/swagger-ui)
[![Build Status](https://jenkins.swagger.io/view/OSS%20-%20JavaScript/job/oss-swagger-ui-master/badge/icon?subject=jenkins%20build)](https://jenkins.swagger.io/view/OSS%20-%20JavaScript/job/oss-swagger-ui-master/)

**👉🏼 Want to score an easy open-source contribution?** Check out our [Good first issue](https://github.com/swagger-api/swagger-ui/issues?q=is%3Aissue+is%3Aopen+label%3A%22Good+first+issue%22) label.

**🕰️ Looking for the older version of Swagger UI?** Refer to the [*2.x* branch](https://github.com/swagger-api/swagger-ui/tree/2.x).


This repository publishes to three different NPM modules:

* [swagger-ui](https://www.npmjs.com/package/swagger-ui) is a traditional npm module intended for use in single-page applications that are capable of resolving dependencies (via Webpack, Browserify, etc).
* [swagger-ui-dist](https://www.npmjs.com/package/swagger-ui-dist) is a dependency-free module that includes everything you need to serve Swagger UI in a server-side project, or a single-page application that can't resolve npm module dependencies.
* [swagger-ui-react](https://www.npmjs.com/package/swagger-ui-react) is Swagger UI packaged as a React component for use in React applications.

We strongly suggest that you use `swagger-ui` instead of `swagger-ui-dist` if you're building a single-page application, since `swagger-ui-dist` is significantly larger.


## Compatibility
The OpenAPI Specification has undergone 5 revisions since initial creation in 2010.  Compatibility between Swagger UI and the OpenAPI Specification is as follows:

Swagger UI Version | Release Date | OpenAPI Spec compatibility | Notes
------------------ | ------------ | -------------------------- | -----
3.18.3 | 2018-08-03 | 2.0, 3.0 | [tag v3.18.3](https://github.com/swagger-api/swagger-ui/tree/v3.18.3)
3.0.21 | 2017-07-26 | 2.0 | [tag v3.0.21](https://github.com/swagger-api/swagger-ui/tree/v3.0.21)
2.2.10 | 2017-01-04 | 1.1, 1.2, 2.0 | [tag v2.2.10](https://github.com/swagger-api/swagger-ui/tree/v2.2.10)
2.1.5 | 2016-07-20 | 1.1, 1.2, 2.0 | [tag v2.1.5](https://github.com/swagger-api/swagger-ui/tree/v2.1.5)
2.0.24 | 2014-09-12 | 1.1, 1.2 | [tag v2.0.24](https://github.com/swagger-api/swagger-ui/tree/v2.0.24)
1.0.13 | 2013-03-08 | 1.1, 1.2 | [tag v1.0.13](https://github.com/swagger-api/swagger-ui/tree/v1.0.13)
1.0.1 | 2011-10-11 | 1.0, 1.1 | [tag v1.0.1](https://github.com/swagger-api/swagger-ui/tree/v1.0.1)

## Documentation

#### Usage 用法
- [Installation](docs/usage/installation.md)
- [Configuration](docs/usage/configuration.md)
- [CORS](docs/usage/cors.md)
- [OAuth2](docs/usage/oauth2.md)
- [Deep Linking](docs/usage/deep-linking.md)
- [Limitations](docs/usage/limitations.md)
- [Version detection](docs/usage/version-detection.md)
- [安装]（docs/usage/installation.md）
- [配置]（docs/usage/configuration.md）
- [cors]（文档/用法/cors.md）
- [OAuth2]（文档/用法/OAuth2.md）
- [深度链接]（docs/usage/deep-linking.md）
- [限制]（docs/usage/limitations.md）
- [版本检测]（docs/usage/version-detection.md）

#### Customization 定制
- [Overview](docs/customization/overview.md)
- [Plugin API](docs/customization/plugin-api.md)
- [Custom layout](docs/customization/custom-layout.md)
- [概述]（docs/customization/overview.md）
- [插件API]（docs/customization/plugin api.md）
- [自定义布局]（docs/customization/custom layout.md）

#### Development 开发
- [Setting up](docs/development/setting-up.md)
- [Scripts](docs/development/scripts.md)
- [设置]（docs/development/setting-up.md）
- [脚本]（docs/development/scripts.md）

##### Integration Tests 集成测试

You will need JDK of version 7 or higher as instructed here
http://nightwatchjs.org/gettingstarted#selenium-server-setup

Integration tests can be run locally with `npm run e2e` - be sure you aren't running a dev server when testing!

如本文所述，您需要7版或更高版本的JDK
http://nightwatchjs.org/gettingstarted#selenium-server-setup

集成测试可以使用“npm run e2e”在本地运行-确保测试时没有运行dev服务器！

### Browser support 浏览器支持
Swagger UI works in the latest versions of Chrome, Safari, Firefox, Edge and IE11.

Swagger用户界面适用于最新版本的Chrome、Safari、Firefox、Edge和IE11。

### Known Issues 已知问题

To help with the migration, here are the currently known issues with 3.X. This list will update regularly, and will not include features that were not implemented in previous versions.

- Only part of the parameters previously supported are available.
- The JSON Form Editor is not implemented.
- Support for `collectionFormat` is partial.
- l10n (translations) is not implemented.
- Relative path support for external files is not implemented.

为了帮助迁移，以下是3.x当前已知的问题。此列表将定期更新，并且不包括以前版本中未实现的功能。

- 只有以前支持的部分参数可用。
- 未实现JSON表单编辑器。
- 对“collectionformat”的支持是部分的。
- l10n（翻译）未实现。
- 未实现外部文件的相对路径支持。

## Security contact 安全联系人

Please disclose any security-related issues or vulnerabilities by emailing [security@swagger.io](mailto:security@swagger.io), instead of using the public issue tracker.

请通过电子邮件[security@swager.io]（mailto:security@swager.io）而不是使用公共问题跟踪程序来披露任何与安全相关的问题或漏洞。

## License 许可证

Copyright 2019 SmartBear Software

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at [apache.org/licenses/LICENSE-2.0](http://www.apache.org/licenses/LICENSE-2.0)

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

版权所有2019 SmartBear软件

根据Apache许可证2.0版（“许可证”）获得许可；
除非符合许可证，否则您不能使用此文件。
您可以在[apache.org/licenses/license-2.0]获取许可证副本（http://www.apache.org/licenses/license-2.0）

除非适用法律要求或书面同意，软件根据许可证分发是按“原样”分发的，无任何明示或暗示的保证或条件。
有关管理权限和许可证限制。

