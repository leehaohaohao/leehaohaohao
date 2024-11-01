# 你好 👋

我是 @leehaohaohao，欢迎来到我的 GitHub 主页！

## 关于我
- 👨‍🎓 **李昊**，男，19岁，目前就读于浙江传媒学院软件工程专业，大三在读。
- 📫 **联系方式**：电话：19817115293 | 邮箱：805459342@qq.com
- 🌐 **个人项目 Git 仓库**：GitHub
- 🏫 **科研经历**：浙传603实验室，跟随导师做项目。

## 职业技能
- ⚙️ **Java**：熟练掌握 Java 编程语言基础，能够高效地编写、调试和优化代码。
- 🗄️ **MySQL**：熟练使用 MySQL 关系型数据库，了解事务隔离级别、索引、存储引擎以及 SQL 优化等关键知识点。
- 🌱 **Spring 框架**：熟练使用 MyBatis、Spring、SpringMVC、SpringBoot、SpringCloud 等主流框架。
- 🛠️ **微服务**：了解微服务架构理念，学习过 RabbitMQ、ElasticSearch、Nacos、Setea、OpenFeign 等中间件。
- 🌐 **Netty**：具备基础的 Netty 网络编程知识，能够使用 Netty 进行 WebSocket 通讯功能开发。
- 🧠 **Redis**：熟练使用 Redis 非关系型数据库，能够利用其高性能和灵活性处理各种数据存储需求。
- 🔑 **Etcd**：熟练运用基于 Go 语言的分布式键值存储系统。
- 🛠️ **Maven & Git & Linux**：熟练使用 Maven 项目构建工具和 Git 版本控制工具，熟悉 Linux 常用命令。
- 💻 **前端基础**：了解 HTML、JavaScript、CSS 等前端基础知识，能够进行简单的前端开发和调试。

## 教育背景
- 🎓 **浙江传媒学院**，软件工程，全日制本科，2022.09-2026.06（目前大三在读）
- 📊 **GPA**：3.95/5.0（专业前15%）
- 🏆 **获奖情况**：
  - 浙江省23届多媒体设计大赛（数字教育交互资源）省一等奖
  - 浙江省22届多媒体设计大赛（VR\AR 开发类）省二等奖
  - CET 英语四级

## 项目经历
### 项目一：立体智学教育网站
- 🏆 **奖项**：浙江省23届多媒体数字教育交互资源类省一等奖
- 📚 **项目介绍**：立体智学是一款面向高中生的立体几何交互学习网站，通过三维模型展示、2D 转 3D 功能、AI 问答和智能组卷等功能，提升学生学习立体几何的效率和兴趣。网站还利用 WebRTC 技术实现在线课堂。
- 🔧 **负责职责**：
  - 项目部署：后端项目部署在阿里云服务器上，前端项目利用 Docker 拉取 Nginx 镜像，将前端部署在 Nginx 上。
  - 图像识别与建模：使用百度图像识别接口识别 2D 图形，并通过 GPT 进行 3D 建模，返回 HTML 给前端。
  - 知识库管理：利用 txt 文件存储立体几何知识库内容，通过分词统计和知识点查找辅助学生学习。
  - 在线课堂：利用 Netty 和 WebRTC 技术实现网页端在线课堂。
  - 学习记录与智能组卷：记录学生学习信息，教师端可实时查看，并根据学生测试错误比率进行智能组卷。
- 🛠️ **技术栈**：SpringBoot，MyBatis，Netty，MySQL，Docker，Nginx

### 项目二：大学复习资料综合博客网站
- 📚 **项目介绍**：该网站为大学生提供一个平台，分享、查找和讨论各种课程的复习资料，解决学校内测试试卷和复习资料零散的问题。
- 🔧 **负责职责**：
  - 权限设计：采用 RBAC 权限设计模式，细分用户和角色权限。利用 Spring AOP 和 Java 注解实现灵活的权限验证。
  - 文章推荐、文章条件筛选：文章首页有随机文章推荐、支持条件筛选文章类型。
  - 社交：支持用户之间相互关注、查看个人主页、查看他人文章、文章点赞、收藏。
  - 网页交流室：利用 Netty 实现用户创建群组或在公开频道聊天的功能。
- 🛠️ **技术栈**：SpringBoot，MyBatis，MySQL，Redis，Netty，JWT

### 项目三：个人技术研究
- 🔧 **敏感词过滤 API 开放平台**：基于 DFA 算法实现敏感词过滤，利用非对称密钥授权和鉴权，并且支持 Java 版 SDK 导入调用敏感词服务接口。
- 🔧 **接口限流、防抖、QPS 统计**：基于 SpringBoot 开发的注解，在 GitHub 上部署 Maven 仓库，项目引入依赖接口添加注解使用。
- 🔧 **RPC 框架**：基于 Etcd 实现的简易版 RPC 框架，实现自定义通讯协议，支持注册中心、负载均衡、容错、自由扩展。

<!---
leehaohaohao/leehaohaohao is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->