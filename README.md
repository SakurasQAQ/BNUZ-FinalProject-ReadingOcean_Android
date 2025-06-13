![image](https://github.com/user-attachments/assets/84176e1c-8222-4199-8149-b15db9c0552c)# 阅读海洋 (Reading Ocean)

## 简介
**阅读海洋 (Reading Ocean)** 是一款为儿童设计的书籍推荐应用程序，目标是加强儿童阅读兴趣和阅读经验。该应用通过在 **Android Studio** 上实现 Android 设计开发，并使用 **API 接口** 获取后台数据，提供一个便捷、可信赖的儿童阅读平台。


## 核心功能

- **智能推荐**：基于用户年龄段及阅读偏好，推荐个性化书单。  
- **书籍详情**：展示封面、简介、作者、评分与用户评论。  
- **阅读记录**：自动统计并展示阅读时长与历史。  
- **书架管理**：一键添加/移除，标记“已读/未读”状态。  
- **搜索与筛选**：支持按书名、作者、分类检索并快速定位。  
- **离线缓存**：已查看内容可在无网络时访问。

---

## 技术栈与架构

- **Android 平台**：Java + ViewBinding + XML 布局  
- **UI 框架**：CoordinatorLayout + AppBarLayout + RecyclerView  
- **网络请求**：Retrofit2 + OkHttp + Gson  
- **本地存储**：Room Database + DAO  
- **架构模式**：MVVM（Model–View–ViewModel）+ LiveData  
- **依赖管理**：Gradle

## 项目结构

'''
BNUZ-FinalProject-ReadingOcean_Android/
├─ .idea/ # IDE 配置
├─ 应用程式 /
│ ├─ 来源/main/
│ │ ├─ java/com/readingocean/
│ │ │ ├─ ui/ # 活动、适配器
│ │ │ ├─ model/ # 实体、DAO
│ │ │ ├─ 网络/ # API 接口
│ │ │ ├─ repository/ # 数据仓库
│ │ │ └─ viewmodel/ # ViewModel
│ │ └─ 无/
│ │ ├─ layout/ # XML 布局
│ │ ├─ drawable/ # 图片资源
│ │ └─ values/ # 主题、资源
│ └─ AndroidManifest.xml
├─ build.gradle
├─ settings.gradle
└─ README.md
'''



## 部署
1. 下载应用代码：
   ```bash
   git clone https://github.com/SakurasQAQ/ydhyfinal.git
   ```
2. 在 Android Studio 中打开项目
3. 确保已经配置好 API 地址，如果使用 Firebase，需要替换 `google-services.json`
4. 运行项目并测试

## 展望
在未来的版本中，将增加：
- AI 智能分析孩子阅读喜好
- 可扩展的社区功能，允许用户分享阅读经验
- 高级视频阅读评价功能

## 贡献
欢迎各位孩子阅读爱好者与开发者共同开发。

---


