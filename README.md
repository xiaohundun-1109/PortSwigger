# PortSwigger

PortSwigger Web Security Academy
Web 安全学习平台

当你进入网站后，主要会和以下三个部分打交道：

Learning Materials (学习资料)：

这是教科书部分。它把 Web 安全分成了具体的专题（Topics），比如 SQL 注入、XSS（跨站脚本）、CSRF、SSRF 等。

每个专题都从“是什么”、“怎么产生的”、“怎么攻击”、“怎么防御”四个维度讲解。

Labs (靶场)：

这是最核心的部分。每个 Lab 都是一个模拟的真实网站环境，你需要利用刚学到的知识攻破它。

难度分级：

Apprentice (学徒)： 基础入门，通常照着教程做就能解出来。

Practitioner (从业者)： 进阶，需要你动脑子绕过一些简单的防御。

Expert (专家)： 极难，通常涉及复杂的逻辑链或最新的攻击手法（初学者不要轻易尝试，容易自闭）。

Burp Suite (工具)：

在学习过程中，你需要下载并安装 Burp Suite Community Edition（社区版，免费）。绝大多数 Lab 都需要你用 Burp Suite 来抓包、改包才能完成。




PortSwigger 贴心地整理了学习路径（Learning Paths），建议优先选择 Server-side vulnerabilities (服务端漏洞) 开始。

推荐的入门攻关顺序（这也是面试最常问的）：

SQL Injection (SQL注入)： 必学，Web 安全的基石。

Authentication (身份验证)： 学习怎么暴力破解、绕过登录。

Directory Traversal (目录遍历)： 相对简单，容易上手。

Command Injection (命令注入)： 危害极大，理解起来很直观。

Business Logic Vulnerabilities (业务逻辑漏洞)： 很有趣，比如“用 0 元买光所有商品”，不需要高深的某些代码知识，全靠逻辑。
