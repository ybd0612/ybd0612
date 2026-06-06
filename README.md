<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=auto&height=150&section=header&text=Hey%20👋,%20I'm%20Ybond&fontSize=40&animation=twinkling" alt="header" />
</p>

<p align="center">
  ☕ <b>Java 后端开发工程师</b> | 📍 中国
</p>

<p align="center">
  <a href="#-关于我">关于我</a> •
  <a href="#-技术栈">技术栈</a> •
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

## 🐍 贪吃蛇动画（最近贡献的仓库）
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/ybd0612/ybd0612/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/ybd0612/ybd0612/output/github-snake.svg" />
  <img alt="github-snake" src="https://raw.githubusercontent.com/ybd0612/ybd0612/output/github-snake.svg" />
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

---

<p align="center">
  <sub><sup>用 ❤️ 和 ☕ 制作 | Powered by GitHub</sup></sub>
</p>
