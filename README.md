<h2 id="chinese">🇨🇳 中文版</h2>

<h1 align="center">👋 你好！</h1>
<h3 align="center">我是一位热爱网络编程与开源社区的开发者</h3>

---

### 🧑🏻‍🎓 关于我

- **学历**：浙江工业大学 **·** 公共事业管理 **·** 大一
  
- **语言**：
  <img src="https://img.shields.io/badge/-C-A8B9CC?style=flat-square&logo=c&logoColor=white" alt="C" />
  <img src="https://img.shields.io/badge/-C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white" alt="C++" />
  <img src="https://img.shields.io/badge/-Golang-00ADD8?style=flat-square&logo=go&logoColor=white" alt="Golang" />
  <br />
  
- **技术栈**：
  <img src="https://img.shields.io/badge/-Linux-FCC624?style=flat-square&logo=linux&logoColor=black" alt="Linux" />
  <img src="https://img.shields.io/badge/-CMake-064F8C?style=flat-square&logo=cmake&logoColor=white" alt="CMake" />
  <img src="https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/-TCP%2FIP-005571?style=flat-square&logo=internet-explorer&logoColor=white" alt="TCP/IP" />
  <br />
  
- **工具链**：
  <img src="https://img.shields.io/badge/-Wrk-FF6B6B?style=flat-square&logo=wireshark&logoColor=white" alt="Wrk" />
  <img src="https://img.shields.io/badge/-GDB-FF6600?style=flat-square&logo=gnu&logoColor=white" alt="GDB" />
  <img src="https://img.shields.io/badge/-Valgrind-7B2CBF?style=flat-square&logo=valgrind&logoColor=white" alt="Valgrind" />
  <img src="https://img.shields.io/badge/-Perf-003366?style=flat-square&logo=linux&logoColor=white" alt="Perf" />
  <img src="https://img.shields.io/badge/-pprof-003366?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/-trace-FF6600?style=flat-square&logo=grafana&logoColor=white" />
  <img src="https://img.shields.io/badge/-benchstat-2C5E8C?style=flat-square&logo=go&logoColor=white" />
  <img src="https://img.shields.io/badge/-go%20test%20--bench-00ADD8?style=flat-square&logo=go&logoColor=white" alt="go test -bench" />
  <img src="https://img.shields.io/badge/-ghz-663399?style=flat-square&logo=gnu-bash&logoColor=white" alt="ghz" />

---

### 📫 联系我

- WeChat: `lzn121234121234`
- Email: `lizining1231@outlook.com`

---

### ☺️ 我正在做的事

#### (1) [Evolutionary-Cpp-Network-Library](https://github.com/lizining1231/Evolutionary-Cpp-Network-Library)

> 一个从零做起，基于演进架构的 C++ 网络库 —— 它还很幼稚，但我正在持续开发中！  
> **它是一个长期项目，欢迎任何形式的贡献与交流 🙌**

- **开发时长**：2026.2 – 至今
- **目标**：用它学习底层的知识，并逐渐提升工程规范，最终把它打造成真实可用的网络库而非求职项目
- **现状**：当前采取 epoll LT 模式，添加多线程后 (本地回环下) **QPS 峰值 450.3k, P99 在 0-5ms**。

还处于完善组件的时期，最近正在完善配置系统

#### (2) 开源社区贡献

正在积极接触开源，拥抱开源，尝试参与以下项目：

- [`dubbo-go`](https://github.com/apache/dubbo-go) — 审查中（[PR #3590](https://github.com/apache/dubbo-go/pull/3590)、[PR #3607](https://github.com/apache/dubbo-go/pull/3607)）
- [`envoy`](https://github.com/envoyproxy/envoy) — 文档修改，已合并（[PR #46098](https://github.com/envoyproxy/envoy/pull/46098)）
- [`nginx`](https://github.com/nginx/nginx) — 代码实现与 review，未合并（[PR #1462](https://github.com/nginx/nginx/pull/1462)）

#### (3) 积极寻找实习机会

#### (4) 经营技术公众号

它叫做 **豆浆技术 🐋**，里面会整理我在开发中遇到的有趣的问题，例如：

- [《从阻塞开始：accept() 和 recv() 阻塞的本质及唤醒机制》](https://mp.weixin.qq.com/s/zlgPIsSRF9gVzByqA4smwA) — 从一个“第二个客户端无法连接”的经典问题出发，深入操作系统知识，图解 `accept()` 和 `recv()` 阻塞的本质、进程状态变迁与完整的唤醒链路梳理。
- [《连续两次QPS暴跌95%：新手第一次性能排查连踩七个坑？》](https://mp.weixin.qq.com/s/Kn-uA6J0l83c6KVfErxMQQ) — 从 QPS 暴跌 95% 的困境出发，完整记录了从 `docker-proxy` 到内核参数 `tcp_tw_reuse` 的曲折排查过程、七个典型误区，以及用 Linux 源码和利特尔定律推演问题根因的实战复盘。
- [《缓冲区共享导致的P99剧烈抖动——为什么一定要有Buffer和Connection类》](https://mp.weixin.qq.com/s/EwHW-IwffJhSDk-1ugwRyg) — 从发现 P99 诡异抖动开始，到定位到“共享缓冲区”这个幽灵 Bug，并自然生长出 Buffer 与 Connection 类的完整排查与决策过程。
- [《如何将一个阻塞IO服务器逐步重构为网络库(上)》](https://mp.weixin.qq.com/s/KNp1CZ7ru5DRf3h-drm0Lw) — 从阻塞IO开始，通过九轮重构将阻塞服务器逐步拆解为网络库组件的完整思路与踩坑经历。

---

<h2 id="english">🇬🇧 English Version</h2>

<h1 align="center">👋 Hi there!</h1>
<h3 align="center">A developer passionate about network programming & open source</h3>

---

### 🧑🏻‍🎓 About Me

- **Education**：Zhejiang University of Technology · Public Administration · Freshman
  
- **Languages**：
  <img src="https://img.shields.io/badge/-C-A8B9CC?style=flat-square&logo=c&logoColor=white" alt="C" />
  <img src="https://img.shields.io/badge/-C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white" alt="C++" />
  <img src="https://img.shields.io/badge/-Golang-00ADD8?style=flat-square&logo=go&logoColor=white" alt="Golang" />
  <br />
  
- **Tech Stack**：
  <img src="https://img.shields.io/badge/-Linux-FCC624?style=flat-square&logo=linux&logoColor=black" alt="Linux" />
  <img src="https://img.shields.io/badge/-CMake-064F8C?style=flat-square&logo=cmake&logoColor=white" alt="CMake" />
  <img src="https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/-TCP%2FIP-005571?style=flat-square&logo=internet-explorer&logoColor=white" alt="TCP/IP" />
  <br />
  
- **Toolchain**：
  <img src="https://img.shields.io/badge/-Wrk-FF6B6B?style=flat-square&logo=wireshark&logoColor=white" alt="Wrk" />
  <img src="https://img.shields.io/badge/-GDB-FF6600?style=flat-square&logo=gnu&logoColor=white" alt="GDB" />
  <img src="https://img.shields.io/badge/-Valgrind-7B2CBF?style=flat-square&logo=valgrind&logoColor=white" alt="Valgrind" />
  <img src="https://img.shields.io/badge/-Perf-003366?style=flat-square&logo=linux&logoColor=white" alt="Perf" />
  <img src="https://img.shields.io/badge/-pprof-003366?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/-trace-FF6600?style=flat-square&logo=grafana&logoColor=white" />
  <img src="https://img.shields.io/badge/-benchstat-2C5E8C?style=flat-square&logo=go&logoColor=white" />
  <img src="https://img.shields.io/badge/-go%20test%20--bench-00ADD8?style=flat-square&logo=go&logoColor=white" alt="go test -bench" />
  <img src="https://img.shields.io/badge/-ghz-663399?style=flat-square&logo=gnu-bash&logoColor=white" alt="ghz" />

---

### 📫 Connect with Me

- WeChat: `lzn121234121234`
- Email: `lizining1231@outlook.com`

---

### ☺️ What I'm Working On

#### (1) [Evolutionary-Cpp-Network-Library](https://github.com/lizining1231/Evolutionary-Cpp-Network-Library)

> A C++ network library built from scratch with evolutionary architecture — **it's still immature, but I'm continuously improving it!**  
> **It's a long-term project. Contributions and discussions of any kind are warmly welcomed 🙌**

- **Timeline**：Feb 2026 – Present
- **Goal**：Learn low-level knowledge, progressively improve engineering standards, and eventually build it into a production-ready network library (not just a portfolio project)
- **Current Status**：epoll LT mode with multi-threading, (loopback) **450.3k QPS with P99 under 0-5ms**. Currently in the component-enhancement phase — working on the configuration system.

#### (2) Open Source Contributions

Actively exploring and embracing open source:

- [`dubbo-go`](https://github.com/apache/dubbo-go) — Under review（[PR #3590](https://github.com/apache/dubbo-go/pull/3590)、[PR #3607](https://github.com/apache/dubbo-go/pull/3607)）
- [`envoy`](https://github.com/envoyproxy/envoy) — Documentation fix, merged（[PR #46098](https://github.com/envoyproxy/envoy/pull/46098)）
- [`nginx`](https://github.com/nginx/nginx) — Code implementation & review, pending（[PR #1462](https://github.com/nginx/nginx/pull/1462)）

#### (3) Actively Seeking Internship Opportunities

#### (4) Running a Technical WeChat Public Account

It's called **豆浆技术 🐋** (Soybean Tech), where I document interesting problems encountered during development, such as:

- [Starting from Blocking: The Essence of accept() and recv() Blocking and Wake-up Mechanisms](https://mp.weixin.qq.com/s/zlgPIsSRF9gVzByqA4smwA) — Starting from the classic "second client cannot connect" problem, this article dives into the OS kernel to diagram the essence of blocking, process state transitions, and the complete wake-up chain for accept() and recv().
- [QPS Crashed 95% Twice: A Rookie's First Performance Debugging Journey Through 7 Pitfalls](https://mp.weixin.qq.com/s/Kn-uA6J0l83c6KVfErxMQQ) — A complete, honest account of debugging a 95% QPS drop, from chasing `docker-proxy` to uncovering the `tcp_tw_reuse` kernel parameter, detailing 7 common misconceptions, with Linux kernel source code and Little's Law used to reason about the root cause.
- [P99 Jitter Caused by Shared Buffer — Why Buffer and Connection Classes Are Essential](https://mp.weixin.qq.com/s/EwHW-IwffJhSDk-1ugwRyg) — A deep dive into troubleshooting erratic P99 latency, uncovering the "shared buffer" ghost bug through 20 rounds of stress testing, and the natural evolution of Buffer and Connection classes.
- [How to Refactor a Blocking I/O Server into a Network Library (Part 1)](https://mp.weixin.qq.com/s/KNp1CZ7ru5DRf3h-drm0Lw) — A detailed walkthrough of my 9-step refactoring journey from a blocking server to a component-based network library architecture.
