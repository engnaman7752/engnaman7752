<div align="center">

# Hey there, I'm Naman Jain 👋

### `Software Engineer` | `C++ Compilers & Systems` | `Java & Spring Boot Backend` | `Generative AI & LangGraph` | `1,400+ DSA Problems`

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/naman-jain7752/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/engnaman7752)
[![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com/u/eng_naman7752)
[![Email](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:nj260106@gmail.com)

</div>

---

## ⚡ Who Am I?

```java
@SpringBootApplication
public class NamanJain {

    public static void main(String[] args) {
        Developer naman = Developer.builder()
            .name("Naman Jain")
            .education("B.Tech ECE @ IIIT Kota | CGPA: 8.36/10")
            .role("Software Engineer — Backend & Systems")
            .passions(List.of("C++ & Compilers", "Distributed Backend", "Generative AI Agents", "System Design"))
            .currentlyBuilding("Optimizing Compilers & AI-Powered Recovery Engines")
            .build();

        SpringApplication.run(NamanJain.class, args);
    }
}
```

> I engineer **systems & production backends** — from optimizing compilers in **C++** and resilient microservices in **Java & Spring Boot** to autonomous agents with **LangGraph & RAG**.

---

## 💼 Experience

### **Software Engineer Intern (Backend)** — *Delito* `May 2026 – Jul 2026 · Remote`
- 🍕 **Microservices & REST APIs** — Engineered RESTful services for a multi-app food delivery platform using **Java, Spring Boot, and PostgreSQL**, serving 500+ menu items across customer, seller, and delivery-partner clients.
- 🔐 **Role-Based Access Control** — Implemented role-based access control (**RBAC**) with **Spring Security and JWT** across four user roles, eliminating unauthorized cross-role data access.
- 💳 **Financial Reconciliation & ACID APIs** — Built order-lifecycle and commission-splitting APIs on **ACID transactions**, automating seller payout reconciliation with consistent order and payout records.
- 🚢 **Production Shipping** — Shipped features in a fully remote team via Git code reviews, Postman-verified API contracts, and **Docker**.

---

## 🏗️ Core Backend Architecture
<div align="center">

```
                        ┌─────────────────────────────────────────┐
                        │         NAMAN'S BACKEND STACK           │
                        └────────────────────┬────────────────────┘
                                             │
                 ┌───────────────────────────┼───────────────────────────┐
                 │                           │                           │
      ┌──────────▼──────────┐    ┌───────────▼───────────┐   ┌──────────▼──────────┐
      │   🟢 SPRING BOOT    │    │   🧠 GENERATIVE AI    │   │   📱 MOBILE/WEB     │
      │                     │    │                       │   │                     │
      │  RESTful APIs       │    │  LangGraph Agents     │   │  React (Vite)       │
      │  Spring Security    │    │  Spring AI + RAG      │   │  Flutter (Dart)     │
      │  JWT Auth & RBAC    │    │  Vector Embeddings    │   │  Firebase           │
      │  Hibernate / JPA    │    │  Gemini API (LLMs)    │   │  FCM Push           │
      │  WebSockets (STOMP) │    │  PyTorch ResNet50     │   │  Google Maps API    │
      │  Webhook Processing │    │  Deterministic EV     │   │  Razorpay Gateway   │
      └─────────────────────┘    └───────────────────────┘   └─────────────────────┘
                 │                           │                           │
                 └───────────────────────────┼───────────────────────────┘
                                             │
                        ┌────────────────────▼────────────────────┐
                        │    PostgreSQL · SQLite · Firebase       │
                        │         GCP · AWS · Docker              │
                        └─────────────────────────────────────────┘
```

</div>

---

## 🌟 Featured Projects

### 1️⃣ <img src="https://img.shields.io/badge/💳_Revenue_Recovery_Engine-Razorpay_AI_Buildathon_Top_30-00838F?style=for-the-badge" />
> **Autonomous Payment Recovery Platform** — Java 17 + Spring Boot 3 + Python FastAPI + LangGraph + PostgreSQL + React
> 
> 🏆 **Razorpay AI Buildathon — Ranked Top 30 out of 85,000+ Participants**

<table>
<tr>
<td width="60%">

**🔧 Architecture**
| Layer | Technology |
|:---|:---|
| **Core Backend** | Java 17, Spring Boot 3, REST APIs, JPA |
| **Agent Decision Engine** | Python 3.11, FastAPI, LangGraph State Machine |
| **Governance & Policy** | Policy-as-Code Guardrails, Quiet Hours, EV Math |
| **State & Checkpoints** | PostgreSQL (`PostgresSaver` durable memory) |
| **Payment Gateway** | Live Razorpay API (Test Mode), HMAC Webhooks |
| **Frontend** | React + Vite, Tailwind CSS, Recharts |

</td>
<td width="40%">

**📈 Impact Metrics**
| Metric | Result |
|:---|:---|
| Total Revenue Recovered | **₹15.36L+ (99.7% of ceiling)** |
| Recovery vs Naive Retries | **3.3× more revenue** |
| Payment Attempts Reduction | **>50% fewer attempts** |
| Automated Test Coverage | **46 passing tests** |

</td>
</tr>
</table>

**Key Engineering:**
- 🏗️ **Dual-Service Decoupled Architecture** — Architected a secure two-service system: a **Java 17 / Spring Boot 3** backend (owning REST APIs, webhook handling, and data layer) and a sandboxed **Python/FastAPI** decision service that can act only through 6 authenticated internal tool endpoints.
- 💳 **Razorpay Integration & Cryptographic Webhooks** — Integrated Razorpay (Orders API, Payment Links, signed webhooks) with **HMAC-SHA256 signature verification over raw request bytes**, persisting workflow state in PostgreSQL so paused human-in-the-loop approvals survive full process restarts.
- 🧠 **LangGraph Decision Machine with EV Fallback** — Built a state machine (Diagnose ➔ Decide ➔ Guard ➔ Execute) ranking actions by Expected Value; recovered **3.3× the revenue** of naive always-retry logic with **under half the payment attempts** across 300 simulated failures.

👉 [View Repository](https://github.com/engnaman7752/razorpay-revenue-recovery-engine)

---

### 2️⃣ <img src="https://img.shields.io/badge/⚙️_Mini--C_Compiler-Optimizing_C%2B%2B17_Compiler-4A148C?style=for-the-badge" />
> **Optimizing Mini-C Compiler** — C++17 + Three-Address IR + CFG Optimizer + Linear-Scan Register Allocator + x86-64 ASM
> 
> ⚡ **Emits ~28% fewer instructions and achieves 1.2–1.7× speedups over -O0, matching/beating GCC -O0 across benchmarks**

<table>
<tr>
<td width="60%">

**🔧 Architecture**
| Layer | Technology |
|:---|:---|
| **Front End** | Hand-Written Lexer, Recursive-Descent Parser, AST |
| **Intermediate Repr.** | Control-Flow Graph (CFG) of Basic Blocks, 3-Address Code |
| **Optimizer (-O1)** | 10 Fixed-Point Passes (Constant Fold, CSE, DCE, CFG Cleanup) |
| **Register Allocator** | Iterative Dataflow Liveness + Linear Scan (5 Callee-Saved Regs) |
| **Target Backend** | x86-64 AT&T Assembly, System V AMD64 ABI |
| **Verification** | Differential Testing vs GCC (-O0/-O1) + 2,000+ Random Fuzz Tests |

</td>
<td width="40%">

**📈 Impact Metrics**
| Metric | Result |
|:---|:---|
| Instruction Reduction | **~28% fewer instructions** |
| Execution Speedup | **1.2–1.7× faster runtime** |
| vs. GCC -O0 | **Matches or outperforms** |
| Differential Test Suite | **53/53 GCC checks passing** |
| Random Fuzz Testing | **2,000+ tests zero mismatches** |

</td>
</tr>
</table>

**Key Engineering:**
- 🧩 **Zero-Dependency Front End & CFG IR** — Hand-crafted lexer, recursive-descent parser, and semantic analyzer lowering C constructs into a virtual-register 3-address control-flow graph in ~2,600 lines of modern C++17.
- ⚡ **Fixed-Point IR Optimizer** — Implemented 10 optimization passes including global/local constant folding (32-bit wrapping semantics), common-subexpression elimination (LVN), copy propagation, algebraic simplification, and branch/jump threading.
- 🎯 **Linear-Scan Register Allocation & Peepholes** — Computed live intervals via dataflow analysis to map virtual registers to x86-64 physical registers, fusing compares/branches (`cmp` + `jcc`) and replacing division/modulus by powers of 2 with rounding shifts.

👉 [View Repository](https://github.com/engnaman7752/mini-c-compiler)

---

### 3️⃣ <img src="https://img.shields.io/badge/🏫_EduPay_AI-GenAI_School_System-1565C0?style=for-the-badge" />
> **Generative AI School Management System** — Spring Boot + Spring AI + RAG + WebSockets (STOMP)

<table>
<tr>
<td width="60%">

**🔧 Architecture**
| Layer | Technology |
|:---|:---|
| **Core Backend** | Java, Spring Boot, Hibernate, JPA |
| **Generative AI** | Spring AI, RAG, Vector Embeddings |
| **Real-Time Engine** | WebSockets (STOMP Protocol) |
| **Security** | Spring Security, JWT (Multi-Tenant Isolation) |
| **Database** | PostgreSQL |

</td>
<td width="40%">

**📈 Impact Metrics**
| Metric | Result |
|:---|:---|
| RAG Query Accuracy | **90%+** |
| Fee Reminders | **Automated AI drafts** |
| Parent Inquiries | **24/7 AI self-service** |
| Architecture | **Multi-Tenant Isolation** |

</td>
</tr>
</table>

**Key Engineering:**
- ⚡ **STOMP WebSocket Notification Engine** — Engineered a real-time notification engine using **WebSockets (STOMP) in Spring Boot** to push automated, AI-drafted fee reminders to students and parents with instant sub-second delivery.
- 🔒 **Multi-Tenant JWT Security** — Secured an enterprise multi-tenant architecture with **Spring Security and JWT**, strictly isolating each educational institution's data at the API and query layer.
- 🧠 **RAG Helpdesk with Spring AI** — Built an institutional helpdesk on **Spring AI and Retrieval-Augmented Generation (RAG)** querying vector-embedded handbooks, answering student and parent queries with **90%+ response accuracy**.

👉 [View Repository](https://github.com/engnaman7752/EDUPay)

---

### 4️⃣ <img src="https://img.shields.io/badge/🌾_Agri_Shield_AI-AI_Crop_Insurance-2E7D32?style=for-the-badge" />
> **AI-Powered Crop Insurance Platform** — Spring Boot + PyTorch + LangChain ReAct Agent

<table>
<tr>
<td width="60%">

**🔧 Architecture**
| Layer | Technology |
|:---|:---|
| **Core Backend** | Java, Spring Boot, Spring Security, JWT |
| **AI/ML Engine** | PyTorch ResNet50, FastAPI |
| **GenAI Agent** | LangChain, RAG, ReAct Agent |
| **Mobile** | Flutter (Farmer App + Inspector App) |
| **Payments** | Razorpay Gateway |
| **Database** | PostgreSQL |

</td>
<td width="40%">

**📈 Impact Metrics**
| Metric | Result |
|:---|:---|
| Damage Detection Accuracy | **98.7%** |
| Claim Processing Speedup | **80% faster** |
| Platform Users | Farmers + Inspectors |
| AI Agent Queries | Real-time RAG |

</td>
</tr>
</table>

**Key Engineering:**
- 🏗️ **Spring Boot Microservice** — Core backend with JWT-secured REST APIs powering dual Flutter apps for farmers and field inspectors
- 🤖 **PyTorch Vision Pipeline** — Custom ResNet50 model served via FastAPI achieving 98.7% crop damage classification
- 🧠 **LangChain ReAct Agent** — Built a LangChain ReAct agent that answers farmer queries and triggers claim workflows via tool calling, dynamically retrieving policy context from knowledge bases
- 💳 **Razorpay Payment Flow** — End-to-end automated claim settlement reducing turnaround by 80%

👉 [View Repository](https://github.com/engnaman7752/agri-shield-ai)

---

## 🛠️ Tech Stack

<div align="center">

### ☕ Core Backend — Java & Spring Ecosystem
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring%20Security-6DB33F?style=for-the-badge&logo=spring-security&logoColor=white)
![Hibernate](https://img.shields.io/badge/Hibernate-59666C?style=for-the-badge&logo=hibernate&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=JSON%20web%20tokens&logoColor=white)

### 🧠 Generative AI & Agentic Systems
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![Spring AI](https://img.shields.io/badge/Spring%20AI-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini%20API-8E75B2?style=for-the-badge&logo=google-gemini&logoColor=white)

`LangGraph State Machines` · `RAG` · `Vector Embeddings` · `Prompt Engineering` · `Policy-as-Code` · `Human-in-the-Loop`

### 💻 Languages
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=white)
![x86-64 Assembly](https://img.shields.io/badge/x86--64_Assembly-37474F?style=for-the-badge)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white)

### 📱 Frontend & Mobile
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)

### 🗄️ Databases & Cloud
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![GCP](https://img.shields.io/badge/Google%20Cloud-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)

### 🔧 DevOps & Tools
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![GCC](https://img.shields.io/badge/GCC-A040A0?style=for-the-badge&logo=gnu&logoColor=white)
![Make](https://img.shields.io/badge/Make-064F8C?style=for-the-badge&logo=gnu&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-C71A36?style=for-the-badge&logo=apache-maven&logoColor=white)
![Gradle](https://img.shields.io/badge/Gradle-02303A?style=for-the-badge&logo=gradle&logoColor=white)
![IntelliJ IDEA](https://img.shields.io/badge/IntelliJ%20IDEA-000000?style=for-the-badge&logo=intellij-idea&logoColor=white)

</div>

---

## 🏆 Competitive Programming & Achievements
<div align="center">

| Platform | Rating | Problems | Badge |
|:---:|:---:|:---:|:---:|
| **LeetCode** | ⚔️ Knight **(1950+)** | 1,400+ Total Problems Solved | [![LeetCode](https://img.shields.io/badge/Knight-FFA116?style=flat-square&logo=leetcode&logoColor=black)](https://leetcode.com/u/eng_naman7752) |
| **Codeforces** | 🔵 Specialist **(Max 1540)** | Active Competitive Coder | [![Codeforces](https://img.shields.io/badge/Specialist-1F8ACB?style=flat-square&logo=codeforces&logoColor=white)](https://codeforces.com/profile/namanjain7752) |
| **CodeChef** | ⭐ 4-Star **(1,819)** | Active Division 2 Coder | [![CodeChef](https://img.shields.io/badge/4%20Star-5B4638?style=flat-square&logo=codechef&logoColor=white)](https://www.codechef.com/users/nj260106) |

</div>

| 🏆 Achievement | Details |
|:---|:---|
| 💳 **Razorpay AI Buildathon** | **Top 30 of 85,000+** participants — *Revenue Recovery Engine* advanced to the final Hiring Manager round |
| 🥇 **HacktoCrack 2.0** | **1st Place** in EdTech Track — outperformed 50+ multidisciplinary teams (2023) |
| 🎯 **Algo Utsav Contest** | **Top 30** out of 2,200+ teams with a 3-member squad architecting optimal algorithms |
| 🚀 **IICPC CodeFest'25** | **Rank 1748** among 45,000+ participants organized by IICPC |

---

## 🤝 Leadership
**Technical & Event Management Lead** — *IIIT Kernel (Technical Exploration Club)*
- 🎤 Organized **25+ technical sessions** with industry leaders and distinguished alumni
- 👥 Engaged **500–800 students per event**, building a culture of technical curiosity across campus

---

## 📊 GitHub Stats
<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=engnaman7752&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=58A6FF&icon_color=58A6FF&text_color=C9D1D9)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=engnaman7752&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=58A6FF&text_color=C9D1D9)

![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=engnaman7752&theme=tokyonight&hide_border=true&background=0D1117&ring=58A6FF&fire=58A6FF&currStreakLabel=58A6FF)

</div>

---

## 📚 Relevant Coursework
`Data Structures & Algorithms` · `Object-Oriented Programming` · `Operating Systems` · `Compiler Design` · `Computer Networking` · `Database Management Systems` · `System Design`

---

## 📫 Let's Build Something Together
<div align="center">

**Open to collaborations, freelance projects, and backend, systems and compiler engineering opportunities!**

[![LinkedIn](https://img.shields.io/badge/Connect_on_LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/naman-jain7752/)
[![Email](https://img.shields.io/badge/Send_an_Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:nj260106@gmail.com)
[![GitHub](https://img.shields.io/badge/Follow_on_GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/engnaman7752)

---

![Visitor Count](https://komarev.com/ghpvc/?username=engnaman7752&style=for-the-badge&color=58A6FF)

**⭐ If you find my projects interesting, consider giving them a star!**

*Built with ☕ Java and ❤️ by Naman Jain*

</div>
