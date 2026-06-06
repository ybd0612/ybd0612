<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=auto&height=150&section=header&text=Hey%20👋,%20I'm%20Ybond&fontSize=40&animation=twinkling" alt="header" />
</p>

<p align="center">
  ☕ <b>Java 后端开发工程师</b> | 📍 中国
</p>

<p align="center">
  <a href="#-关于我">关于我</a> •
  <a href="#-技术栈">技术栈</a> •
  <a href="#-开源数据">开源数据</a> •
  <a href="#-代码片段展示">代码片段</a> •
  <a href="#-联系我">联系我</a>
</p>

---

## 🙋 关于我

> 一个被 Java 选中的后端仔 👨‍💻，日常和 `null` 斗智斗勇。

- 🔭 **正在深耕**：用 **Java** 搭建后端世界——一砖一瓦，全是接口和注解。
- 🌱 **技术沉迷**：最近沉迷 **Spring Cloud / 微服务 / 中间件**，感觉头发日渐稀薄。
- 👯 **极客精神**：热衷研究新技术，看到新框架比看到新番还兴奋。
- ⚡ **生活真相**：一杯茶，一根烟，一个 Bug 改一天。第十天发现少了个分号 ☕

<br>

<details>
<summary>📂 <b>点我看看我的项目现状（划掉）项目列表</b></summary>

<br>

| 项目 | 说明 | 状态 |
|:---:|:---|:---:|
| **工作项目** | Java 后端服务，稳定输出中 | ✅ 已上线 |
| **个人项目** | 造轮子进行时，探索微服务边界 | 🚧 开发中 |
| **AI 应用** | 结合大模型 API 的智能体尝试 | 💡 规划中 |

</details>

---

## 🛠 技术栈

### 核心语言与微服务架构
<p align="left">
  <img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white" alt="Java" />
  <img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=spring-boot&logoColor=white" alt="Spring Boot" />
  <img src="https://img.shields.io/badge/Spring%20Cloud-6DB33F?style=flat-square&logo=spring&logoColor=white" alt="Spring Cloud" />
  <img src="https://img.shields.io/badge/MyBatis-EC1C24?style=flat-square&logo=mybatis&logoColor=white" alt="MyBatis" />
</p>

### 数据存储与中间件
<p align="left">
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white" alt="MySQL" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" alt="Redis" />
  <img src="https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white" alt="Nginx" />
</p>

### 基础设施与生产力工具
<p align="left">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" alt="Linux" />
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git" />
  <img src="https://img.shields.io/badge/IntelliJ_IDEA-000000?style=flat-square&logo=intellij-idea&logoColor=white" alt="IntelliJ IDEA" />
</p>

> [!TIP]
> **当代程序员的修养**：帮派的功力就这几招：<kbd>Ctrl</kbd> + <kbd>C</kbd> 和 <kbd>Ctrl</kbd> + <kbd>V</kbd>，修炼已至化境 🔥

---

## 📊 开源数据与状态

<p align="center">
  <img src="https://img.shields.io/github/stars/ybd0612?style=for-the-badge&logo=github&label=Stars" alt="Stars" />
  <img src="https://img.shields.io/github/followers/ybd0612?style=for-the-badge&logo=github&label=Followers" alt="Followers" />
  <img src="https://img.shields.io/github/last-commit/ybd0612?style=for-the-badge&logo=github&label=Last%20Commit" alt="Last Commit" />
</p>

<p align="center">
  <img src="https://img.shields.io/github/languages/count/ybd0612?style=for-the-badge&logo=github&label=Languages" alt="Languages" />
  <img src="https://img.shields.io/github/repo-size/ybd0612/ybd0612?style=for-the-badge&logo=github&label=Repo%20Size" alt="Repo Size" />
  <img src="https://img.shields.io/github/commit-activity/y/ybd0612?style=for-the-badge&logo=github&label=Commits/Year" alt="Commits Per Year" />
</p>

---

## 💻 代码片段展示

### ⚡ 微服务经典组件：Spring Boot Redis 配置

```java
@Configuration
public class RedisConfig {

    @Bean
    public RedisTemplate<String, Object> redisTemplate(RedisConnectionFactory factory) {
        RedisTemplate<String, Object> template = new RedisTemplate<>();
        template.setConnectionFactory(factory);
        template.setKeySerializer(new StringRedisSerializer());
        template.setValueSerializer(new GenericJackson2JsonRedisSerializer());
        return template;
    }
}
```

---

## 🔄 最近动态 & 任务

### 🎯 升级路线图

- [x] 熟练掌握微服务常用组件（Gateway, Nacos, Sentinel）
- [x] 构建高可用的 Redis 缓存生产实践
- [ ] 精通 Spring Cloud 深度底层源码与调优
- [ ] 构建属于自己的独立 SaaS 产品 / 参与 1k+ Star 开源项目

---

## 🎵 编码 BGM

<details>
<summary>🎶 <b>点击展开我的编码歌单</b></summary>

<br>

| # | 歌曲 | 艺术家 | 适合场景 |
|:---:|:---|:---|:---|
| 1 | Lo-Fi Beats | ChilledCow | 日常编码 |
| 2 | Breathe | Telepopmusik | Debug 时放松 |
| 3 | The Algorithm | Perturbator | 冲刺 Deadline |
| 4 | Coding in the Rain | Various | 夜间独处 |

</details>

---

## 📬 联系我

<p align="center">
  <a href="mailto:ybd0612@qq.com">
    <img src="https://img.shields.io/badge/QQ邮箱-ybd0612@qq.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="https://github.com/ybd0612">
    <img src="https://img.shields.io/badge/GitHub-ybd0612-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>
  <img src="https://img.shields.io/badge/微信-fwtmde-07C160?style=for-the-badge&logo=wechat&logoColor=white" alt="WeChat" />
</p>

---

> [!NOTE]
> 🚀 **进阶技巧：如何让主页"全自动更新"？**
>
> 如果你想让你的 GitHub 主页展示最新的博客文章或最近在 GitHub 上的动态，你可以利用 GitHub Actions 引入自动化组件：
>
> **1. 自动展示最新 GitHub 动态**
>
> 在 README 中留下注释标记：
> ```html
> <!--START_SECTION:activity-->
> <!--END_SECTION:activity-->
> ```
> 然后使用开源的 [github-activity-readme](https://github.com/JamesIves/github-activity-readme) Action。它每天会自动把你最近的 Commit、Issue、PR 动态刷进这两个注释中间，完全不需要手动维护。
>
> **2. 自动展示最新博客（若你有个人博客/知乎/掘金等）**
>
> 使用 [blog-post-workflow](https://github.com/gautamkrishnar/blog-post-workflow)，配置好你的 RSS 订阅地址，它就会自动把你最新的文章同步到主页上。

---

<p align="center">
  <sub><sup>用 ❤️ 和 ☕ 制作 | Powered by GitHub</sup></sub>
</p>
