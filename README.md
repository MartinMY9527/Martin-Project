# 项目经历

## 1. Another Me
**担任角色**：前端开发工程师  
**项目周期**：2025.03-2025.11

**项目概述**：基于 Android 平台的智能 AI 聊天应用，集成本地 AI 模型推理、多平台用户认证、订阅支付系统、社交媒体分享等功能，为用户提供安全、私密且功能丰富的 AI 对话体验。

**个人职责**：
- 项目负责人（团队开发）
- 负责应用的核心功能开发，包括 AI 聊天系统、用户认证、支付订阅、社交分享等 17 个核心 Activity 模块
- 设计良好的架构，采用 Kotlin + MVVM 设计模式，不断迭代优化，维护效率高
- 编写开发规范、代码规范、组件的描述、模块划分、方法注解
- 协助测试团队进行功能测试和性能测试，保证应用的质量和稳定性

**技术要点**：
- 从 0 到 1 搭建项目并设计网络请求架构，采用 Retrofit + RxJava + OkHttp 框架实现高效稳定的网络通信
- 集成 Google MediaPipe LLM 进行本地 AI 推理，实现流式响应显示，当本地模型不可用时自动切换到模拟响应模式
- 集成 Google 登录认证系统，使用最新的 Credential Manager API，实现用户信息的本地加密存储和自动登录
- 集成 Stripe 支付系统，使用 PaymentSheet 实现多层级订阅（基础版、高级版、超级高级版），支持 WebView 支付作为备选方案
- 集成 Twitter、Facebook、Kakao 等社交媒体 SDK，实现多平台内容分享功能
- 开发 Token 挖矿系统、排行榜系统、邀请奖励等游戏化元素，提升用户参与度
- 集成 Persona SDK 实现 KYC 身份验证功能
- 使用 ExoPlayer 实现视频背景播放，使用 Glide 实现图片懒加载
- 自定义 StackLayoutManager 实现卡片堆叠动画效果，优化 UI 交互体验
- 对应用进行性能优化，包括内存优化、布局优化、代码优化等，确保 60fps 流畅动画效果
- 开发崩溃管理组件工具类，实现启动优化、弱网优化，为其他 App 提供支持

---

## 2. Another Me - 去中心化 AI 算力共享平台 官网
**担任角色**：前端开发工程师  
**项目周期**：2025.03-2025.11

**项目概述**:
去中心化 AI 算力共享平台官网，通过可视化方式展示"激活闲置设备算力，实现被动收益"的产品理念，为用户提供沉浸式的交互体验和产品教育。

**个人职责**：
- 负责前端架构设计，采用 React + MobX 构建单页应用
- 设计并实现复杂滚动动画和交互效果，提升用户体验
- 开发智能导航系统，实现滚动方向感知和区域激活状态管理
- 配置 Docker + Nginx 生产环境部署流程，优化静态资源加载性能

**技术要点**：
- 使用 React 19 + React Router 7 构建多页面路由系统
- 集成 GSAP + ScrollTrigger 实现滚动视差、文字粒子、方向感知按钮等复杂动画
- 使用 Lottie 动画库加载 10+ 个高质量矢量动画，提升视觉吸引力
- 采用 MobX 进行响应式状态管理，结合 Ant Design 5 快速构建 UI 组件
- 配置 Axios 拦截器实现统一请求处理和错误管理
- 使用 Craco 自定义 Create React App 配置，支持路径别名和 SCSS 预处理
- 实现 requestAnimationFrame 节流优化滚动事件性能
- 配置 Nginx Gzip 压缩和静态资源缓存策略，提升加载速度
- 使用 Docker 多阶段构建优化镜像体积，实现容器化部署

---

## 3. RWA Frontend
**担任角色**：前端开发工程师  
**项目周期**：2025.09-2025.11

**项目概述**：基于 Next.js 构建的去中心化应用（DApp），集成 Privy 钱包连接、多链网络切换、代币转账、消息签名等 Web3 功能，为用户提供完整的区块链交互体验。

**个人职责**：
- 负责 Web3 钱包集成和区块链交互功能开发
- 设计并实现钱包连接、网络切换、智能合约调用等核心模块
- 开发用户认证系统，基于钱包签名实现去中心化登录
- 负责前端架构设计，采用 React Hooks + Context 模式管理应用状态
- 配置开发和生产环境的部署流程，使用 PM2 进行进程管理

**技术要点**：
- 集成 Privy SDK 实现多钱包连接支持，包括 MetaMask、WalletConnect 等主流钱包
- 使用 ethers.js v6 与以太坊区块链交互，实现 USDT、WBTC、POWER 等 ERC-20 代币合约调用
- 开发自动网络切换功能，确保用户在正确的区块链网络上进行操作
- 实现基于钱包签名的去中心化身份认证，生成随机 nonce 防止重放攻击
- 设计 Token 管理机制，实现访问令牌的本地存储和自动刷新
- 使用 TypeScript 提供类型安全，结合 React Context 实现全局状态管理
- 配置 Axios 拦截器自动处理认证 Token，优化 API 请求流程
- 实现错误处理机制，对钱包操作异常进行友好提示和降级处理
- 使用 Ant Design 组件库快速构建用户界面，提升开发效率
- 配置多环境部署方案，支持开发环境（3011端口）和生产环境（3012端口）独立运行

---

## 4. Jarvis
**担任角色**：前端开发工程师  
**项目周期**：2025.03-2025.11

**项目内容**：
- 蓝牙传输模块：设计并搭建蓝牙传输功能，确保数据传输的稳定性和安全性。
- AI 解析模块：开发 AI 解析功能，实现音频内容的智能解析，识别会议纪要和待办事项。
- 音频处理模块：负责音频文件的上传与处理，确保音质和传输效率。
- 文件上传模块：设计并搭建文件上传模块，支持多平台文件的无缝上传。
- 编写开发规范与代码规范：制定详细的开发规范，确保代码的可维护性和一致性。
- 组件描述与模块划分：优化组件设计，实现模块化开发，提高项目的整体效率。

## 技术要点

- 从 0 到 1 搭建 iOS 项目并设计网络请求架构，采用 Alamofire + RxSwift + HandyJSON 框架实现高效稳定的网络通信，封装 JSApiClient 和 JSRequest 统一管理 API 请求
- 集成讯飞实时语音识别 SDK (IflyRTASRManager)，实现音频流式转写功能，支持 16kHz 采样率 PCM 格式音频处理，集成 ASC 音频解码库实现音频格式转换
- 开发 WebSocket + SSE 双通道实时通信方案，实现 AI 对话流式响应显示，支持断线重连和错误处理机制，确保实时交互的稳定性
- 集成 CoreBluetooth 框架开发蓝牙设备管理系统 (BLEManager)，实现设备扫描、连接、数据传输等完整功能，支持设备状态实时监控和自动重连
- 开发后台任务管理系统，使用 BGTaskScheduler 实现文件上传后台任务 (UploadManager)，支持后台音频播放和数据处理，确保应用在后台也能正常工作
- 使用 RxSwift + RxCocoa + RxDataSources 实现响应式数据流管理，优化 TableView/CollectionView 数据绑定，提升列表滚动性能和用户体验
- 开发日历集成系统 (CalendarManager)，实现日程创建、编辑、删除等功能，支持系统日历同步，提供自定义日期选择器组件
- 自定义录音浮窗组件 (JarvisRecordView) 和悬浮按钮 (JarvisFloatingButton)，实现全局录音功能，支持拖拽、动画效果和状态管理
- 使用 SnapKit 实现声明式 Auto Layout 布局，开发多个自定义 UI 组件（弹窗、日期选择器、错误提示等），提升代码可读性和开发效率
- 使用 Kingfisher 实现图片异步加载和缓存管理，集成 GTMRefresh 实现下拉刷新功能，使用 IQKeyboardManager 自动处理键盘遮挡问题
- 对应用进行性能优化，包括内存管理、布局优化、网络请求优化等，使用 LookinServer 进行 UI 层级调试，确保应用流畅运行
- 开发通用工具类库 (JarvisUtils)，封装常用功能和扩展方法，实现代码复用，为项目提供统一的基础设施支持

---

## 5. AI 拍照机
**担任角色**：前端开发工程师  
**项目周期**：2024.07-2025.02

**个人职责**：
- 项目负责人（团队开发）
- 负责应用的核心功能开发，如拍照功能、图片处理、图像展示等，设计良好的架构，不断迭代优化，维护效率高
- 协助测试团队进行功能测试和性能测试，保证应用的质量和稳定性
- 编写开发规范、代码规范、组件的描述、模块划分、方法注解

**技术要点**：
- 从 0 到 1 搭建项目并设计网络请求架构，采用 Retrofit 和 OkHttp 框架实现高效稳定的网络通信
- 采用 Kotlin + MVVM 的设计模式设计框架
- 对应用进行性能优化，包括内存优化、布局优化、代码优化等；参与应用的界面设计和交互优化，与 UI 设计师紧密合作，根据用户反馈对界面进行多次调整，提高了应用的易用性和美观度，用户满意度提升了 20%
- 开发崩溃管理组件工具类，实现启动优化、弱网优化，为其他 App 提供支持

---

## 6. 车库导航小程序
**担任角色**：Uniapp 前端开发工程师  
**项目周期**：2023.12-2024.07

**个人职责**：
- 项目负责人（团队开发）
- 本项目采用 UniApp 开发
- 负责地下车库导航、反向寻车、车库预约功能开发
- 编写开发规范、代码规范、组件的描述、模块划分

**技术要点**：
- Uniapp 开发的应用，从零到一的开发过程
- 集成底层蓝牙模块，实现对硬件的操作和部署
- iOS 采用 iBeacon，Android 采用蓝牙来定位当前位置
- 采用 WebView 实现地下车库导航功能

---

## 7. 部署工具 Pro
**担任角色**：前端开发工程师  
**项目周期**：2022.06-2024.07

**个人职责**：
- 项目负责人（团队开发）
- 维护底层蓝牙库
- 按需求分派任务给初级开发工程师
- 拓展新业务开发模块
- 日常维护

**技术要点**：
- 通过蓝牙部署蓝牙设备
- 添加项目、房间、蓝牙组来方便操控蓝牙设备
- 底层蓝牙库的开发
- 个性化制定蓝牙设备

---

## 8. tink（香港苏宁，三星门店 app）
**担任角色**：Android 开发工程师  
**项目周期**：2021.01-2022.03

**个人职责**：
- 项目负责人（团队开发）
- 从零到一项目，尝试搭建 Android 架构
- 日常维护、迭代版本、升级版本、重构项目布局

**技术要点**：
- 使用 Retrofit 网络请求数据
- SharedPreferences 存储应用的各种配置信息
- 集成 ZBar 的二维码扫描预约订单、报价功能
- 使用 LocalBroadcastManager 本地广播来同步信息，管理项目三大组件

---

## 8. Samsung App
**担任角色**：iOS 开发工程师  
**项目周期**：2021.01-2022.03

**个人职责**：
- 项目负责人（团队开发）
- 负责 Samsung 回收机应用开发
- 设计良好的架构，不断迭代优化
- API 设计规范，使模块和工具类可读性更高
- 编写开发规范、代码规范、组件的描述、模块划分

**技术要点**：
- Swift 开发的应用，从零到一的开发过程
- 采用 MVVM 设计模式搭建框架
- 集成创新研发的 SDK，实现对硬件的操作
- 采用 hook 的方式进行数据处理
- 开发崩溃管理组件工具类，实现启动优化、弱网优化，为其他 App 提供支持

---

## 10. 苹果 MTA 手机自动回收机
**担任角色**：Android 开发工程师  
**项目周期**：2019.07-2021.12

**项目概述**：随着电子设备更新换代速度加快，废旧手机回收处理需求日益增长。为提高回收效率和服务质量，开发 MTA 手机自动回收机，为用户提供便捷的手机回收服务。

**个人职责**：
- Android 项目负责人之一
- 负责苹果回收机应用开发
- 设计良好的架构，不断迭代优化

**技术要点**：
- 深入了解 Android 开发，完成从零到一的应用开发过程
- 集成创新研发的 SDK，实现对 MTA 机器硬件的操作
- 使用 RecyclerView 展示 SKU 选项，并使用 ViewHolder 复用机制
- 挑战解决：分享并解决在项目开发过程中遇到的重大挑战和困难，如硬件兼容性问题、网络不稳定、弱网状态、图片上传不成功等，并详细描述解决问题的思路和方法

---

## 11. 大器管理（团队开发）
**担任角色**：iOS 开发工程师  
**项目周期**：2018.03-2019.06

**个人职责**：
- 项目小组成员
- 负责设备模块、汇报模块、项目地址、智能设备模块的开发
- 设计良好的架构，不断迭代优化
- 根据需求文档进行项目优化，提交测试，迭代更新版本

**技术要点**：
- 本项目从 2.0 进化到 3.0，并在 3.0 采用组件化的方式进行开发，高效提升工作与维护效率
- 使用 Socket 对设备进行实时监控 / 防倾斜预警
- 善于用项目开发中的小技巧、交换方法来避免线上出现崩溃现象
- 登录成功后采用一对多的代理方式处理页面逻辑
- 模仿 CTMediator 采用 KVC + 创建动态类的方法实现模块之间的通信
- 利用 MVVM + RAC 的模式高效完成模块开发
- 使用 Instrument 常用工具进行性能调优
  
---

## 12. 到喜啦
**担任角色**：iOS 开发工程师  
**项目周期**：2017.03-2018.01

**个人职责**：
- 本项目负责人
- 负责上传，后续操作由产品负责
- 根据需求文档进行项目优化，提交测试，迭代更新版本

**技术要点**：
- 以 Swift 为主，以 Objective-C 为辅完成此项目，并做系统适配
- 使用 Masonry 和 Snapkit 适配所有机型
- 使用 Runtime 的特性对系统方法进行交换
- 使用系统 API 进行应用内评分、撰写评论等功能
- 使用 MJExtension 进行字典数组转模型数组
- 对 Cookie 进行处理并加入 Web 端需要的参数和值

---

## 13. ANADA（独立开发）
**担任角色**：iOS 开发工程师  
**项目周期**：2015.10-2018.01

**项目概述**：
- 打造一款高质量的内容交流平台, 一个大型交友社区，国内专业, 海量视频, 全国活动, 高清图库, 社交平台, 在线商城.

**个人职责**：
- 与产品负责人即时沟通项目需求、功能实现
- 每天总结当天的工作，记录相关问题，把控代码质量
- 负责上传至 App Store 等程序
- 完成项目优化、测试、迭代更新版本

**技术要点**：
- 使用 Swift 与 Objective-C 混写完成此项目，并做系统适配
- 封装七牛云的方法，实现文件上传的功能类
- 使用高德地图的 POI 关键字搜索，获取附近的地理位置
- 使用融云 IM 集成聊天系统，实现 1 对 1 实时聊天
- 集成微信支付、支付宝支付，完成支付系统
- 使用 Apple 内购，完成会员充值、积分充值
- 上传视频、图片，结合通知中心，实现七牛云与后台之间的交互
- 运用 AVPlayer 并封装，播放用户上传和后台上传的视频
- 使用沙盒缓存，实现本地数据化

---

## 14. 婚礼自由人
**担任角色**：iOS 开发工程师  
**项目周期**：2015.10-2018.01

**个人职责**：
- 本项目负责人
- 负责上传，后续操作由产品负责
- 根据需求文档进行项目优化，提交测试，迭代更新版本

**技术要点**：
- 纯 Swift 开发
- 使用 SnapKit 适配所有机型
- 使用系统 API 进行应用内评分、撰写评论等功能
- 使用 FMDB 查询存储用户的积分信息
- 对 Cookie 进行处理并加入 Web 端需要的参数和值

---

## 15. 大圣理财
**担任角色**：iOS 开发工程师  
**项目周期**：2015.03-2015.10

**个人职责**：
- 本项目负责人
- 负责组织产品需求的沟通、讨论和协调工作
- 总结问题，记录项目进度
- 负责用户评价、发红包、红包列表等核心代码
- 负责上传至 App Store 等程序
- 负责解决测试组提交的 BUG，完成优化任务，并对项目进行维护

**技术要点**：
- 与 HTML5 进行对接并联调，解决登录状态一致问题
- 读取本地 plist 文件，实现首页、登录、个人中心页面的数据持久化
- 手势密码进行对用户手势密码开关的管理
- 使用本地沙盒保存 App 部分使用数据
- 使用多线程解决 UI 界面卡顿、数据重复请求等操作
- 根据后台技术人员提供的加密方法加密数据，在 iOS 端实现加密、解密
- 使用友盟 SDK 添加埋点
- 实现消息推送功能
- 与汇付天下技术人员进行对接

---

# Project Experience (English)

## 1. Another Me
**Role**: Android Engineer  
**Duration**: 2025.03–2025.11

**Project Overview**: Intelligent AI chat application on Android platform, integrating local AI model inference, multi-platform user authentication, subscription payment system, and social media sharing, delivering a secure, private, and feature-rich AI conversation experience.

**Responsibilities**:
- Project lead (team development)
- Built core features including AI chat system, user authentication, payment subscriptions, social sharing, and 17 core Activity modules
- Designed scalable architecture using Kotlin + MVVM design pattern, iterated and optimized for high maintainability
- Authored development standards, code conventions, component descriptions, module boundaries, and method annotations
- Supported QA with functional and performance testing to ensure quality and stability

**Highlights**:
- Built project from scratch; designed networking architecture with Retrofit + RxJava + OkHttp for robust and efficient network communications
- Integrated Google MediaPipe LLM for local AI inference, implemented streaming response display, with automatic fallback to simulated responses when local models are unavailable
- Integrated Google authentication system using the latest Credential Manager API, implemented local encrypted storage for user information and auto-login functionality
- Integrated Stripe payment system using PaymentSheet for multi-tier subscriptions (Basic, Premium, Super Premium), with WebView payment as fallback option
- Integrated Twitter, Facebook, and Kakao social media SDKs for multi-platform content sharing functionality
- Developed gamification elements including Token mining system, leaderboard system, and referral rewards to enhance user engagement
- Integrated Persona SDK for KYC identity verification functionality
- Used ExoPlayer for video background playback and Glide for image lazy loading
- Custom StackLayoutManager for card stacking animation effects, optimizing UI interaction experience
- Performance optimization including memory, layout, and code optimization, ensuring 60fps smooth animation effects
- Developed crash management utility classes, implemented startup optimization and weak-network optimization, providing support for other apps

---

## 2. Another Me - Decentralized AI Computing Power Sharing Platform Website
**Role**: Front-end Engineer  
**Duration**: 2025.03–2025.11

**Project Overview**:
Official website for a decentralized AI computing power sharing platform, visualizing the concept of "activating idle device computing power to achieve passive income," providing users with an immersive interactive experience and product education.

**Responsibilities**:
- Responsible for frontend architecture design, building single-page application with React + MobX
- Designed and implemented complex scroll animations and interactive effects to enhance user experience
- Developed intelligent navigation system with scroll direction awareness and section activation state management
- Configured Docker + Nginx production environment deployment process, optimized static resource loading performance

**Highlights**:
- Built multi-page routing system with React 19 + React Router 7
- Integrated GSAP + ScrollTrigger for complex animations including scroll parallax, text particles, and direction-aware buttons
- Used Lottie animation library to load 10+ high-quality vector animations, enhancing visual appeal
- Adopted MobX for reactive state management, combined with Ant Design 5 to quickly build UI components
- Configured Axios interceptors for unified request handling and error management
- Used Craco to customize Create React App configuration, supporting path aliases and SCSS preprocessing
- Implemented requestAnimationFrame throttling to optimize scroll event performance
- Configured Nginx Gzip compression and static resource caching strategy to improve loading speed
- Used Docker multi-stage builds to optimize image size, achieving containerized deployment

---

## 3. RWA Frontend
**Role**: Front-end Engineer  
**Duration**: 2025.09–2025.11

**Project Overview**: Decentralized application (DApp) built on Next.js, integrating Privy wallet connection, multi-chain network switching, token transfers, message signing, and other Web3 features, providing users with a complete blockchain interaction experience.

**Responsibilities**:
- Responsible for Web3 wallet integration and blockchain interaction functionality development
- Designed and implemented core modules including wallet connection, network switching, and smart contract calls
- Developed user authentication system based on wallet signature for decentralized login
- Responsible for frontend architecture design, using React Hooks + Context pattern to manage application state
- Configured deployment processes for development and production environments, using PM2 for process management

**Highlights**:
- Integrated Privy SDK to support multiple wallet connections, including mainstream wallets such as MetaMask and WalletConnect
- Used ethers.js v6 to interact with Ethereum blockchain, implementing ERC-20 token contract calls for USDT, WBTC, POWER, etc.
- Developed automatic network switching functionality to ensure users operate on the correct blockchain network
- Implemented decentralized identity authentication based on wallet signature, generating random nonce to prevent replay attacks
- Designed Token management mechanism, implementing local storage and automatic refresh of access tokens
- Used TypeScript for type safety, combined with React Context for global state management
- Configured Axios interceptors to automatically handle authentication tokens, optimizing API request flow
- Implemented error handling mechanism, providing user-friendly prompts and fallback handling for wallet operation exceptions
- Used Ant Design component library to quickly build user interfaces, improving development efficiency
- Configured multi-environment deployment solution, supporting independent operation of development environment (port 3011) and production environment (port 3012)

---

## 4. Jarvis
**Role**: Front-end Engineer  
**Duration**: 2025.03–2025.11

**Scope**:
- Bluetooth Transfer Module: Designed and built stable and secure BLE data transfer.
- AI Parsing Module: Implemented AI-powered audio parsing to extract meeting minutes and todos.
- Audio Processing Module: Handled audio upload and processing to balance quality and throughput.
- File Upload Module: Built a cross-platform file upload pipeline.
- Engineering Standards: Authored development and code conventions to ensure maintainability.
- Componentization: Refined component design and modularized features to improve delivery efficiency.

**Highlights**:
- Built iOS project from scratch and designed network request architecture, using Alamofire + RxSwift + HandyJSON framework for efficient and stable network communication, encapsulated JSApiClient and JSRequest for unified API request management
- Integrated iFlytek real-time speech recognition SDK (IflyRTASRManager), implemented audio streaming transcription functionality, supporting 16kHz sample rate PCM format audio processing, integrated ASC audio decoding library for audio format conversion
- Developed WebSocket + SSE dual-channel real-time communication solution, implemented AI conversation streaming response display, supporting reconnection and error handling mechanisms to ensure stability of real-time interactions
- Integrated CoreBluetooth framework to develop Bluetooth device management system (BLEManager), implemented complete functionality including device scanning, connection, data transmission, supporting real-time device status monitoring and automatic reconnection
- Developed background task management system, using BGTaskScheduler to implement file upload background tasks (UploadManager), supporting background audio playback and data processing, ensuring the app works normally in the background
- Used RxSwift + RxCocoa + RxDataSources to implement reactive data flow management, optimized TableView/CollectionView data binding, improved list scrolling performance and user experience
- Developed calendar integration system (CalendarManager), implemented schedule creation, editing, deletion and other functions, supporting system calendar synchronization, providing custom date picker components
- Custom recording floating window component (JarvisRecordView) and floating button (JarvisFloatingButton), implemented global recording functionality, supporting drag, animation effects and state management
- Used SnapKit to implement declarative Auto Layout, developed multiple custom UI components (popups, date pickers, error prompts, etc.), improved code readability and development efficiency
- Used Kingfisher to implement asynchronous image loading and cache management, integrated GTMRefresh for pull-to-refresh functionality, used IQKeyboardManager to automatically handle keyboard occlusion issues
- Performed application performance optimization, including memory management, layout optimization, network request optimization, etc., used LookinServer for UI hierarchy debugging, ensuring smooth application operation
- Developed general utility library (JarvisUtils), encapsulated common functions and extension methods, implemented code reuse, providing unified infrastructure support for the project

---

## 5. AI Camera
**Role**: Front-end Engineer  
**Duration**: 2024.07–2025.02

Responsibilities:
- Project lead (team development).
- Built core features including capture, image processing, and gallery; designed scalable architecture and iterated for maintainability.
- Supported QA with functional and performance testing to ensure quality and stability.
- Wrote development and code standards, component docs, module boundaries, and method annotations.

**Highlights**:
- Built project from scratch; designed networking with Retrofit + OkHttp for robust communications.
- Adopted Kotlin + MVVM.
- Performance optimization: memory/layout/code. Collaborated with UI to refine UX; user satisfaction improved by ~20%.
- Developed crash management utilities; startup and weak-network optimizations; shared utility for other apps.

---

## 6. Parking Garage Mini Program
**Role**: Uniapp Front-end Engineer  
**Duration**: 2023.12–2024.07

**Responsibilities**:
- Project lead (team development) using Uniapp.
- Delivered underground navigation, reverse car finding, and parking reservation.
- Authored development standards, code conventions, component descriptions, and module layout.

**Highlights**:
- End-to-end Uniapp delivery from zero to production.
- Integrated low-level Bluetooth operations for hardware control and deployment.
- Indoor positioning: iOS via iBeacon; Android via Bluetooth.
- Implemented underground navigation with WebView.

---

## 7. Deployment Tool Pro
**Role**: Front-end Engineer  
**Duration**: 2022.06–2024.07

**Responsibilities**:
- Project lead (team development).
- Maintained the core Bluetooth library.
- Assigned tasks to junior engineers; expanded new business modules; handled daily maintenance.

**Highlights**:
- BLE-based device deployment.
- Organized projects/rooms/groups to streamline device control.
- Built and evolved the underlying BLE library; supported device customization.

---

## 8. tink (Suning HK, Samsung Store App)
**Role**: Android Engineer  
**Duration**: 2021.01–2022.03

**Responsibilities**:
- Project lead (team development).
- Greenfield Android architecture; continuous maintenance, iteration, version upgrades, and layout refactoring.

**Highlights**:
- Networking with Retrofit.
- App configuration via SharedPreferences.
- Integrated ZBar for QR scanning (order booking, quotation).
- Used LocalBroadcastManager for component sync and app-wide state messaging.

---

## 8. Samsung App
**Role**: iOS Engineer  
**Duration**: 2021.01–2022.03

**Responsibilities**:
- Project lead (team development) for Samsung recycling machine app.
- Iterative architecture improvements; API standards for higher readability of modules and utilities.
- Authored development conventions and component/module docs.

**Highlights**:
- Swift app from scratch; MVVM architecture.
- Integrated in-house SDK for hardware control.
- Data processing via hook-style interception.
- Built crash management utilities; startup and weak-network optimizations; reusable across apps.

---

## 10. Apple MTA Automated Phone Recycling Machine
**Role**: Android Engineer  
**Duration**: 2019.07–2021.12

**Overview**:
- Addressed growing demand for used phone recycling by delivering an automated MTA solution for efficient, high-quality service.

**Responsibilities**:
- One of the Android leads; built the Apple recycling machine app; iterated and optimized architecture.

**Highlights**:
- Full lifecycle Android delivery from zero to one.
- Integrated custom SDK to operate MTA hardware.
- Used RecyclerView with ViewHolder for SKU presentation.
- Tackled major challenges: hardware compatibility, unstable/weak networks, unreliable uploads; documented approaches and fixes.

---

## 11. Daqi Management (Team Development)
**Role**: iOS Engineer  
**Duration**: 2018.03–2019.06

**Responsibilities**:
- Team member; delivered device, reporting, project address, and smart device modules.
- Iterative architecture improvements; implemented based on PRD and shipped frequent updates.

**Highlights**:
- Evolved from 2.0 to 3.0 with a componentized architecture to improve efficiency.
- Real-time device monitoring via Socket (anti-tilt alerts).
- Applied runtime techniques to prevent crashes.
- Post-login, used one-to-many delegation for page logic.
- KVC + dynamic classes to enable CTMediator-like inter-module communication.
- MVVM + RAC for efficient module development.
- Performance tuning with Instruments.

---

## 12. Daoxila
**Role**: iOS Engineer  
**Duration**: 2017.03–2018.01

**Responsibilities**:
- Project owner; responsible for delivery and handoff to product for operations; optimization, testing, and iterations per PRD.

**Highlights**:
- Primarily Swift with Objective-C interop; system compatibility work.
- Adaptive UI with Masonry and SnapKit.
- Method swizzling with Runtime.
- Used system APIs for in-app rating and reviews.
- MJExtension for model mapping.
- Managed Cookies and injected required Web parameters.

---

## 13. ANADA (Indie Development)
**Role**: iOS Engineer  
**Duration**: 2015.10–2018.01

**Responsibilities**:
- Communicated requirements in real time; daily summaries; quality control; App Store submission; optimization, testing, and iterations.

**Highlights**:
- Swift + Objective-C mixed codebase with system compatibility.
- Encapsulated Qiniu upload utilities.
- AMap POI keyword search for nearby places.
- RongCloud IM for 1:1 real-time chat.
- Integrated WeChat Pay and Alipay.
- Apple IAP for membership/credits.
- Media uploads with NotificationCenter to orchestrate Qiniu-backend interactions.
- Encapsulated AVPlayer for user- and backend-uploaded media.
- Local data caching via sandbox.

---

## 14. Wedding Freelancer
**Role**: iOS Engineer  
**Duration**: 2015.10–2018.01

**Responsibilities**:
- Project owner; delivery and product-led operations; optimization, testing, iteration.

**Highlights**:
- Pure Swift; adaptive UI with SnapKit.
- System APIs for in-app rating and reviews.
- FMDB for points/credits persistence.
- Cookie handling with required Web parameters.

---

## 15. Dasheng Finance
**Role**: iOS Engineer  
**Duration**: 2015.03–2015.10

**Responsibilities**:
- Project owner; led product requirement discussions; tracked progress; owned core modules (reviews, red packets, lists); App Store submission; bug fixes and optimization.

**Highlights**:
- H5 integration and joint debugging; resolved login state consistency.
- Persisted home/login/profile via local plist.
- Gesture lock management and local sandbox storage.
- Multithreading to avoid UI jank and duplicate requests.
- Client-side encryption/decryption per backend spec.
- Umeng analytics and push notifications.
- Integrated with IPS/Chinapnr.
