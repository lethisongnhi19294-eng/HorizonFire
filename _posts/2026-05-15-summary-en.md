---
layout: default
title: "Horizon Summary: 2026-05-15 (EN)"
date: 2026-05-15
lang: en
---

> From 37 items, 26 important content pieces were selected

---

1. [Severe Remote Code Execution Vulnerability in NGINX Disclosed](#item-1) ⭐️ 9.0/10
2. [First public macOS kernel memory corruption exploit on Apple M5](#item-2) ⭐️ 8.0/10
3. [Codex is now in the ChatGPT mobile app](#item-3) ⭐️ 8.0/10
4. [New arXiv policy: 1-year ban for hallucinated references](#item-4) ⭐️ 8.0/10
5. [Rewrite Bun in Rust has been merged](#item-5) ⭐️ 8.0/10
6. [Anthropic Partners with SpaceX to Enhance Claude Services](#item-6) ⭐️ 8.0/10
7. [US Approves H200 Chip Sales to Chinese Firms](#item-7) ⭐️ 8.0/10
8. [DeepSeek Dialogue System Session Isolation Vulnerability Discovered](#item-8) ⭐️ 8.0/10
9. [vllm-project/vllm releases v0.21.0 with major updates](#item-9) ⭐️ 7.0/10
10. [Introduction of DwarfStar4 LLM Inference Runtime](#item-10) ⭐️ 7.0/10
11. [RTX 5090 and M4 MacBook Air: Can It Game?](#item-11) ⭐️ 7.0/10
12. [President Kornbluth Addresses Funding and Talent Pipeline Issues](#item-12) ⭐️ 7.0/10
13. [Mitchell Hashimoto on Programming Language Fungibility](#item-13) ⭐️ 7.0/10
14. [CSP Allow-list Experiment](#item-14) ⭐️ 7.0/10
15. [Anthropic Launches Claude for Small Business](#item-15) ⭐️ 7.0/10
16. [Nvidia's Market Cap Surpasses $5.5 Trillion](#item-16) ⭐️ 7.0/10
17. [Boeing Negotiates Up to 500 737 MAX Orders with China](#item-17) ⭐️ 7.0/10
18. [Transition from Legacy Apps to React Native](#item-18) ⭐️ 6.0/10
19. [Ma Huateng Addresses Tencent's AI Progress at Shareholder Meeting](#item-19) ⭐️ 6.0/10
20. [Obesity Rates Stabilize in High-Income Countries, Rise in Low-Income Nations](#item-20) ⭐️ 6.0/10
21. [Huawei, JAC Motors, and Stellantis Discuss Maserati EV Collaboration](#item-21) ⭐️ 6.0/10
22. [Removing Modem and GPS from 2024 RAV4 Hybrid](#item-22) ⭐️ 5.0/10
23. [Exploring the Computer Hobby Movement in Canada](#item-23) ⭐️ 5.0/10
24. [Release of datasette-ip-rate-limit 0.1a0 Plugin](#item-24) ⭐️ 5.0/10
25. [JD.com Launches AI Hardware Section with NVIDIA Products](#item-25) ⭐️ 5.0/10
26. [ChatGPT Android Version Reveals Remote Desktop Control Feature](#item-26) ⭐️ 5.0/10

---

<a id="item-1"></a>
## [Severe Remote Code Execution Vulnerability in NGINX Disclosed](https://depthfirst.com/research/nginx-rift-achieving-nginx-rce-via-an-18-year-old-vulnerability) ⭐️ 9.0/10

A critical remote code execution vulnerability, identified as CVE-2026-42945, was disclosed on May 13, 2026, affecting NGINX versions from 0.6.27 to 1.30.0 and various enterprise products. This vulnerability has existed for 18 years and has a CVSS v4.0 score of 9.2. This vulnerability poses a significant risk to millions of servers worldwide, particularly those deployed in cloud-native Kubernetes environments. Immediate patching is crucial to prevent potential exploitation and protect sensitive data. The vulnerability arises from a heap buffer overflow in the ngx_http_rewrite_module, allowing attackers to execute arbitrary code remotely without authentication. Users are advised to upgrade to specific patched versions to mitigate the risk.

telegram · zaihuapd · May 14, 02:41

**Background**: NGINX is a widely used web server and reverse proxy server known for its performance and scalability. The ngx_http_rewrite_module is a component that processes URL rewriting, which is essential for routing and managing web traffic. Buffer overflow vulnerabilities are common in software and can lead to serious security issues if not addressed.

<details><summary>References</summary>
<ul>
<li><a href="https://nvd.nist.gov/vuln/detail/CVE-2026-42945">NVD - CVE - 2026 - 42945</a></li>
<li><a href="https://securityvulnerability.io/vulnerability/CVE-2026-42945">CVE - 2026 - 42945 : Heap Buffer Overflow in NGINX Plus and NGINX...</a></li>
<li><a href="https://www.picussecurity.com/resource/blog/nginx-rift-cve-2026-42945-critical-heap-buffer-overflow-vulnerability-explained">NGINX Rift: CVE - 2026 - 42945 Critical Heap Buffer Overflow...</a></li>

</ul>
</details>

**Discussion**: Community members have expressed concerns about the exploit's complexity and the conditions required for successful exploitation. Some users noted that while the vulnerability is serious, certain preconditions must be met for it to be effective.

**Tags**: `#NGINX`, `#security`, `#vulnerability`, `#remote code execution`, `#CVE`

---

<a id="item-2"></a>
## [First public macOS kernel memory corruption exploit on Apple M5](https://blog.calif.io/p/first-public-kernel-memory-corruption) ⭐️ 8.0/10

The first public exploit of kernel memory corruption on Apple's M5 chip has been reported, raising concerns about macOS security. This exploit highlights vulnerabilities that could be exploited by malicious actors. This is significant as it exposes potential security weaknesses in macOS that could affect millions of users. The exploit could lead to unauthorized access and data breaches if not addressed promptly. The exploit reportedly involves a kernel memory corruption technique that could allow attackers to gain elevated privileges. It raises questions about the effectiveness of Apple's security measures in protecting against such vulnerabilities.

hackernews · quadrige · May 14, 18:25 · [Discussion](https://news.ycombinator.com/item?id=48139219)

**Background**: Kernel memory corruption is a serious type of security vulnerability that can lead to system crashes or unauthorized access. Apple's M5 chip is part of its silicon family, designed to enhance performance and efficiency in macOS devices.

<details><summary>References</summary>
<ul>
<li><a href="https://9to5mac.com/2026/05/14/new-macos-vulnerabilities-were-exposed-by-anthropics-mythos-report/">New macOS vulnerabilities were exposed by Anthropic ... - 9to5Mac</a></li>

</ul>
</details>

**Discussion**: Community comments reflect a mix of curiosity and concern regarding the exploit's implications. Some users express skepticism about the details provided, while others highlight the potential financial value of the exploit in Apple's bug bounty program.

**Tags**: `#macOS`, `#security`, `#exploit`, `#Apple`, `#M5`

---

<a id="item-3"></a>
## [Codex is now in the ChatGPT mobile app](https://openai.com/index/work-with-codex-from-anywhere/) ⭐️ 8.0/10

Codex has been integrated into the ChatGPT mobile app, enabling users to access its capabilities on both iOS and Android devices. This integration allows for seamless coding assistance on the go. This integration significantly enhances accessibility for developers, allowing them to utilize Codex's capabilities anytime and anywhere. It reflects a growing trend towards mobile solutions in software development tools. The mobile app supports remote SSH access and HIPAA compliance, making it suitable for a variety of development environments. Users can interact with Codex through both the mobile app and desktop applications.

hackernews · mikeevans · May 14, 20:06 · [Discussion](https://news.ycombinator.com/item?id=48140529)

**Background**: Codex is an AI coding assistant developed by OpenAI, designed to assist developers with tasks such as writing code and fixing bugs. It has been available through various platforms, including a desktop app and integrations with development environments.

<details><summary>References</summary>
<ul>
<li><a href="https://thenewstack.io/openai-codex-chatgpt-mobile/">OpenAI brings Codex to the ChatGPT mobile app</a></li>

</ul>
</details>

**Discussion**: Community comments reflect a mix of excitement and concerns about the usability of Codex on mobile devices. Some users appreciate the free access, while others express challenges with smaller screens impacting their coding efficiency.

**Tags**: `#Codex`, `#ChatGPT`, `#Mobile App`, `#AI Tools`, `#Developer Tools`

---

<a id="item-4"></a>
## [New arXiv policy: 1-year ban for hallucinated references](https://twitter.com/tdietterich/status/2055000956144935055) ⭐️ 8.0/10

arXiv has implemented a new policy that imposes a one-year ban on submissions containing hallucinated references. Future submissions must be accepted at a peer-reviewed venue before being submitted to arXiv. This policy is significant as it aims to enhance the integrity of academic references in submissions, which is crucial for maintaining trust in scientific communication. Researchers and authors will need to ensure their work is rigorously vetted before sharing it on arXiv. The penalty for including hallucinated references is a one-year ban from arXiv, and subsequent submissions must be peer-reviewed. This change reflects growing concerns about the reliability of machine learning outputs and their implications in academic publishing.

hackernews · gjuggler · May 14, 20:39 · [Discussion](https://news.ycombinator.com/item?id=48140922)

**Background**: Hallucinated references refer to citations that do not exist or are inaccurately represented, often generated by large language models (LLMs). This issue has raised concerns in the academic community about the credibility of research outputs, especially as LLMs become more prevalent in generating scholarly content.

<details><summary>References</summary>
<ul>
<li><a href="https://info.arxiv.org/help/policies/content-types.html">Policies for specific content types - arXiv info</a></li>
<li><a href="https://info.arxiv.org/help/submit/index.html">Submission Guidelines - About arXiv</a></li>
<li><a href="https://en.wikipedia.org/wiki/Hallucination_(artificial_intelligence)">Hallucination (artificial intelligence) - Wikipedia</a></li>

</ul>
</details>

**Discussion**: Community sentiment appears to be mixed, with some expressing support for the policy as a positive step for scientific integrity, while others raise concerns about the implications for authors who may inadvertently include hallucinated references. Overall, there is a recognition of the need for careful implementation.

**Tags**: `#arXiv`, `#academic integrity`, `#machine learning`, `#LLMs`, `#policy changes`

---

<a id="item-5"></a>
## [Rewrite Bun in Rust has been merged](https://github.com/oven-sh/bun/pull/30412) ⭐️ 8.0/10

The Bun JavaScript runtime has been successfully rewritten in Rust, significantly increasing its codebase complexity and performance potential. This change was officially merged on GitHub, marking a major milestone for the project. This rewrite is significant as it enhances performance and safety features, potentially impacting developers who rely on Bun as a Node.js alternative. The shift to Rust may also influence future software development practices in the JavaScript ecosystem. The new codebase exceeds 1 million lines of Rust code, which is approaching the size of the Rust compiler itself. Additionally, the use of Rust's memory safety features aims to reduce common programming errors such as use-after-free and double-free.

hackernews · Chaoses · May 14, 08:15 · [Discussion](https://news.ycombinator.com/item?id=48132488)

**Background**: Bun is a JavaScript runtime designed as a drop-in replacement for Node.js, utilizing Safari's JavaScriptCore as its engine. Rust is a programming language known for its focus on performance and memory safety, making it a suitable choice for high-performance applications.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Bun_(software)">Bun (software) - Wikipedia</a></li>
<li><a href="https://rust-lang.org/">Rust Programming Language</a></li>

</ul>
</details>

**Discussion**: Community members have expressed curiosity about the preparation time for the rewrite and the implications of the increased code complexity. There is a mix of excitement and caution regarding the potential challenges that come with such a significant change.

**Tags**: `#Rust`, `#JavaScript`, `#Bun`, `#Software Development`, `#Open Source`

---

<a id="item-6"></a>
## [Anthropic Partners with SpaceX to Enhance Claude Services](https://t.me/zaihuapd/41371) ⭐️ 8.0/10

Anthropic has announced a partnership with SpaceX to utilize the full computational power of the Colossus 1 data center, gaining over 300 megawatts of additional capacity within a month, including over 220,000 NVIDIA GPUs. This collaboration significantly increases the usage limits for Claude Code and Claude API services. This partnership is significant as it enhances the computational capabilities of Claude's services, potentially allowing for more advanced AI applications and broader accessibility. The increase in capacity and usage limits could attract more developers and businesses to utilize Claude's offerings. The Colossus 1 data center is noted for being the world's largest AI supercomputer, which will now fully support Anthropic's operations. The increase in usage limits includes doubling the rate limits for paid plans and removing peak usage restrictions for Pro and Max users.

telegram · zaihuapd · May 14, 00:57

**Background**: The Colossus 1 data center, operated by SpaceX's xAI, is designed to provide substantial computational power for AI training and inference. NVIDIA GPUs are widely used in AI applications due to their efficiency and performance in handling complex computations. This collaboration marks a significant step in the AI infrastructure landscape.

<details><summary>References</summary>
<ul>
<li><a href="https://www.datacenterdynamics.com/en/news/anthropic-to-use-all-of-spacex-xais-colossus-1-data-center-compute/">Anthropic to use all of SpaceX-xAI's Colossus 1 data center compute</a></li>
<li><a href="https://x.ai/colossus">Colossus: The World's Largest AI Supercomputer | xAI</a></li>
<li><a href="https://en.wikipedia.org/wiki/Colossus_(supercomputer)">Colossus (supercomputer) - Wikipedia</a></li>

</ul>
</details>

**Tags**: `#AI`, `#Cloud Computing`, `#Partnership`, `#NVIDIA`, `#Infrastructure`

---

<a id="item-7"></a>
## [US Approves H200 Chip Sales to Chinese Firms](https://www.reuters.com/business/retail-consumer/us-clears-h200-chip-sales-10-china-firms-nvidia-ceo-looks-breakthrough-2026-05-14/) ⭐️ 8.0/10

The US Department of Commerce has approved the sale of Nvidia's H200 chips to about 10 Chinese companies, including Alibaba and Tencent. Each customer can purchase up to 75,000 chips, although no deliveries have been completed yet. This development is significant as it highlights the ongoing technology competition between the US and China, particularly in the semiconductor sector. The approval could impact the capabilities of Chinese firms in AI and high-performance computing. The H200 chip is designed for high-performance computing and generative AI applications, featuring advanced memory capabilities. Despite the approval, Chinese companies are reportedly cautious about proceeding with purchases due to guidance from the Beijing government.

telegram · zaihuapd · May 14, 08:57

**Background**: The H200 chip is part of Nvidia's Hopper architecture, which is aimed at enhancing performance in AI and data center applications. The approval for sales comes amid strict US export controls on advanced semiconductor technologies to China, reflecting the geopolitical tensions in the tech industry.

<details><summary>References</summary>
<ul>
<li><a href="https://www.cnbc.com/2026/05/14/us-clears-h200-chip-sales-to-10-china-firms-as-nvidia-ceo-looks-for-breakthrough.html">U.S. clears H200 chip sales to 10 China firms as ... - CNBC H200 GPU | NVIDIA Exclusive-US Clears H200 Chip Sales to 10 China Firms as ... US reportedly allows 10 Chinese companies to buy NVIDIA's ... Nvidia China H200 Chip Sales Stalled Despite U.S. Green Light ... Why China blocked Nvidia H200 AI chip sales despite US ... - WION Trump Clears Nvidia H200 Sales To Alibaba, Tencent And 8 ...</a></li>

</ul>
</details>

**Tags**: `#US-China relations`, `#technology`, `#Nvidia`, `#semiconductors`, `#AI`

---

<a id="item-8"></a>
## [DeepSeek Dialogue System Session Isolation Vulnerability Discovered](https://github.com/deepseek-ai/DeepSeek-R1/issues/840) ⭐️ 8.0/10

A session isolation vulnerability has been found in the DeepSeek dialogue system, allowing attackers to leak other users' conversation fragments through an unclosed <think string input. This issue was reported on May 11, 2026. This vulnerability poses a significant security risk as it could expose sensitive information, affecting user privacy and trust in the system. The implications of such a leak can have broader consequences for the AI dialogue system industry. The vulnerability occurs when an attacker sends an unclosed <think string in a new empty dialogue, resulting in the model returning conversation history fragments from other users, including potentially sensitive information like codes and keys. The issue has been publicly disclosed, indicating a wide-ranging impact.

telegram · zaihuapd · May 14, 13:15

**Background**: Session isolation is a critical security principle that ensures separate sessions do not interfere with each other, preventing unauthorized access to sensitive data. The DeepSeek dialogue system is an AI-based chatbot that allows users to engage in conversations, but vulnerabilities like this can undermine user trust and system integrity.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/DeepSeek_(chatbot)">DeepSeek (chatbot) - Wikipedia</a></li>
<li><a href="https://www.ncsc.gov.uk/collection/cross-domain-solutions/using-the-principles/session-isolation">Session isolation | National Cyber Security Centre</a></li>

</ul>
</details>

**Discussion**: Community members have expressed concerns about the implications of this vulnerability, with some noting that it also affects third-party deployments. There is a significant level of engagement and discussion regarding potential fixes and the overall security of the system.

**Tags**: `#security`, `#vulnerability`, `#DeepSeek`, `#AI`, `#dialogue systems`

---

<a id="item-9"></a>
## [vllm-project/vllm releases v0.21.0 with major updates](https://github.com/vllm-project/vllm/releases/tag/v0.21.0) ⭐️ 7.0/10

The v0.21.0 release of the vllm-project introduces the deprecation of Transformers v4 support and a new requirement for a C++20-compatible compiler. Additionally, it includes enhancements in memory allocation and speculative decoding. This release is significant as it impacts developers who rely on the Transformers library and those needing to upgrade their compilers. The changes reflect ongoing trends in machine learning towards more efficient memory management and performance optimization. The release includes 367 commits from 202 contributors, with major changes such as the integration of KV offloading with a Hybrid Memory Allocator and the introduction of speculative decoding that respects reasoning budgets. These enhancements aim to improve overall efficiency and performance.

github · khluu · May 14, 23:15

**Background**: vLLM is an open-source project designed for large language model inference, focusing on optimizing memory usage and computational efficiency. The project has been evolving rapidly, with previous versions introducing various features to enhance model performance and usability.

<details><summary>References</summary>
<ul>
<li><a href="https://vllm-project.github.io/2026/01/08/kv-offloading-connector.html">Inside vLLM’s New KV Offloading Connector: Smarter Memory ...</a></li>
<li><a href="https://deepwiki.com/vllm-project/tpu-inference/6.5-kv-cache-offload">KV Cache Offload | vllm-project/tpu-inference | DeepWiki</a></li>
<li><a href="https://en.wikipedia.org/wiki/Speculative_decoding">Speculative decoding</a></li>

</ul>
</details>

**Discussion**: The community has shown significant interest in the updates, particularly regarding the breaking changes and new features. Users are discussing the implications of migrating to Transformers v5 and the necessity of upgrading compilers.

**Tags**: `#vllm`, `#transformers`, `#C++20`, `#machine learning`, `#software release`

---

<a id="item-10"></a>
## [Introduction of DwarfStar4 LLM Inference Runtime](https://antirez.com/news/165) ⭐️ 7.0/10

The article introduces DwarfStar4, a new small LLM inference runtime that can run DeepSeek 4. It highlights the performance and hardware requirements, specifically noting a need for 96GB of VRAM. This development is significant as it reflects the ongoing advancements in local AI models, which could lead to more efficient and accessible AI solutions. The community's engagement suggests a strong interest in the future capabilities of such models. DwarfStar4 is designed to support multiple backends, including Metal for MacBooks with 96GB of RAM, NVIDIA CUDA, and AMD ROCm. The model-specific inference engine raises questions about its long-term viability compared to existing solutions like llamacpp.

hackernews · caust1c · May 14, 22:29 · [Discussion](https://news.ycombinator.com/item?id=48142108)

**Background**: DwarfStar4 is part of a growing trend in AI towards local models that can operate independently of cloud services. Local AI models offer advantages such as improved privacy and reduced latency, making them appealing for various applications.

<details><summary>References</summary>
<ul>
<li><a href="https://www.gmicloud.ai/en/blog/vllm-vs-tensorrt-llm-vs-triton">vLLM vs TensorRT-LLM vs Triton: The Runtime Decision That Shapes Your Inference Cost | GMI Cloud</a></li>
<li><a href="https://localai.io/">LocalAI</a></li>

</ul>
</details>

**Discussion**: Community comments reflect a mix of excitement and skepticism about DwarfStar4's capabilities and its future in a rapidly evolving landscape. Some users express concerns about the sustainability of developing a model-specific inference engine.

**Tags**: `#AI`, `#Machine Learning`, `#LLM`, `#Inference`, `#Community Discussion`

---

<a id="item-11"></a>
## [RTX 5090 and M4 MacBook Air: Can It Game?](https://scottjg.com/posts/2026-05-05-egpu-mac-gaming/) ⭐️ 7.0/10

The article examines the gaming performance of the RTX 5090 when used with the M4 MacBook Air, focusing on the challenges faced and insights from the community regarding GPU usage. It highlights the potential for gaming on non-traditional platforms. This is significant as it showcases the evolving capabilities of Apple's hardware for gaming, which has traditionally been limited. The findings could influence gamers' choices and perceptions of gaming on Mac systems. The RTX 5090 is based on Nvidia's Blackwell architecture and features advanced capabilities for real-time ray tracing. However, the compatibility of eGPUs with Apple Silicon remains a significant challenge, as noted by community comments.

hackernews · allenleee · May 14, 15:47 · [Discussion](https://news.ycombinator.com/item?id=48137145)

**Background**: The RTX 5090 is part of Nvidia's latest GPU series, designed for high-performance gaming and rendering tasks. The M4 MacBook Air is Apple's latest iteration of its laptop line, featuring the M4 chip, which is part of the Apple Silicon family, known for its efficiency and performance improvements over previous generations.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/GeForce_RTX_50_series">GeForce RTX 50 series - Wikipedia</a></li>
<li><a href="https://www.nvidia.com/en-us/geforce/graphics-cards/50-series/rtx-5090/">GeForce RTX 5090 Graphics Cards - NVIDIA</a></li>
<li><a href="https://pcvenus.com/apple-m-series-chip-comparison/">Apple M5 vs M4 vs M3 vs M2 vs M1 – The Full Comparison - PCVenus</a></li>

</ul>
</details>

**Discussion**: Community comments reflect a mix of enthusiasm and skepticism regarding the feasibility of using eGPUs with Apple Silicon. Some users express frustration over the lack of support for GPU pass-through, while others share positive experiences with gaming benchmarks.

**Tags**: `#GPU`, `#MacBook Air`, `#Gaming`, `#RTX 5090`, `#Apple Silicon`

---

<a id="item-12"></a>
## [President Kornbluth Addresses Funding and Talent Pipeline Issues](https://president.mit.edu/writing-speeches/video-transcript-message-president-kornbluth-about-funding-and-talent-pipeline) ⭐️ 7.0/10

President Kornbluth has released a message addressing concerns about research funding and the challenges facing the academic talent pipeline. This message has prompted extensive community discussion regarding the future of academia. This issue is significant as it highlights the struggles within academia, particularly regarding funding and job prospects for PhD graduates. The outcome of these discussions could impact the future landscape of academic careers and research opportunities. Kornbluth's message emphasizes the declining research funding and its implications for attracting and retaining talent in academia. The current environment has led many recent PhD graduates to consider leaving academia for better opportunities.

hackernews · dmayo · May 14, 14:51 · [Discussion](https://news.ycombinator.com/item?id=48136262)

**Background**: The academic talent pipeline refers to the process of preparing and transitioning students into academic and research roles. Research funding is critical for supporting these roles and ensuring that institutions can attract top talent. Recent trends indicate a growing concern about the sustainability of funding models in academia.

<details><summary>References</summary>
<ul>
<li><a href="https://www.chapman.edu/campus-services/career-professional-development/recruit-hire/_files/premier-employer-partnerprog-white-paper.pdf">CREATING A WORKFORCE PIPELINE - chapman.edu</a></li>
<li><a href="https://www.wgu.edu/blog/reimagining-talent-pipelines-jff2409.html">Reimagining Talent Pipelines: A New Era of Higher Ed</a></li>

</ul>
</details>

**Discussion**: Community comments reflect a mix of concerns about the state of research funding and disillusionment with academia. Many recent PhD graduates are considering leaving academia, while others emphasize the need for systemic change in the educational model.

**Tags**: `#academia`, `#funding`, `#PhD`, `#talent pipeline`, `#research`

---

<a id="item-13"></a>
## [Mitchell Hashimoto on Programming Language Fungibility](https://simonwillison.net/2026/May/14/mitchell-hashimoto/#atom-everything) ⭐️ 7.0/10

Mitchell Hashimoto commented on the increasing fungibility of programming languages, highlighting the Bun project's ability to switch from Zig to Rust in a short time frame. He noted that Rust, while currently useful, could be easily replaced by other languages as needed. This observation is significant as it reflects a broader trend in software development where flexibility and adaptability in programming languages are becoming increasingly important. Developers and companies may benefit from this trend by being able to choose the best tools for their specific needs without being locked into a single language. Hashimoto's comments suggest that the rapid evolution of programming languages allows projects like Bun to adapt quickly, which could lead to a more dynamic development environment. This adaptability raises questions about the long-term viability of certain languages in the face of emerging alternatives.

rss · Simon Willison · May 14, 22:31

**Background**: Programming languages have historically been seen as rigid choices, often leading to 'lock-in' situations where developers are unable to switch languages without significant costs. The Bun project is a JavaScript runtime that has demonstrated the ability to transition between programming languages, showcasing the increasing flexibility in the software development landscape.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Bun_(software)">Bun (software) - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Zig_(programming_language)">Zig (programming language) - Wikipedia</a></li>

</ul>
</details>

**Tags**: `#programming-languages`, `#rust`, `#zig`, `#mitchell-hashimoto`, `#software-engineering`

---

<a id="item-14"></a>
## [CSP Allow-list Experiment](https://simonwillison.net/2026/May/13/csp-allow/#atom-everything) ⭐️ 7.0/10

The CSP Allow-list Experiment introduces a method for intercepting CSP errors in a sandboxed iframe, enabling users to add domains to an allow-list. This tool was developed using GPT-5.5 and demonstrates a custom fetch() function that communicates errors to the parent window. This experiment is significant as it provides a practical solution for developers facing CSP errors, enhancing web security practices. By allowing users to manage their own allow-lists, it could lead to more secure web applications and improved user experiences. The tool utilizes a sandboxed iframe to minimize security risks while allowing for dynamic error handling. It prompts users to add domains to the allow-list when CSP errors occur, which can streamline the development process.

rss · Simon Willison · May 13, 04:50

**Background**: Content Security Policy (CSP) is a security feature that helps prevent various types of attacks, such as cross-site scripting (XSS) and code injection. Sandboxed iframes provide a secure environment by restricting the capabilities of the content they contain. The fetch() API allows web applications to make network requests similar to XMLHttpRequest, but with a simpler and more powerful interface.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Content_Security_Policy">Content Security Policy - Wikipedia</a></li>
<li><a href="https://developer.mozilla.org/en-US/docs/Web/HTTP/Guides/CSP">Content Security Policy (CSP) - HTTP | MDN - MDN Web Docs</a></li>
<li><a href="https://web.dev/articles/sandboxed-iframes">Play safely in sandboxed IFrames | Articles | web.dev</a></li>

</ul>
</details>

**Tags**: `#CSP`, `#Web Security`, `#Sandboxing`, `#JavaScript`, `#Developer Tools`

---

<a id="item-15"></a>
## [Anthropic Launches Claude for Small Business](https://www.anthropic.com/news/claude-for-small-business) ⭐️ 7.0/10

Anthropic has launched Claude for Small Business, integrating it with platforms like QuickBooks and PayPal. This new service offers 15 workflows and skills tailored for various business tasks. This launch is significant as it integrates AI into widely-used business tools, potentially transforming how small enterprises operate. The impact could be substantial, especially for businesses looking to automate routine tasks. The service operates through Claude Cowork, requiring user approval for actions like sending or making payments. Notably, Team and Enterprise versions do not use customer data for training by default.

telegram · zaihuapd · May 14, 12:41

**Background**: Claude is a series of AI models developed by Anthropic, designed for various applications including business automation. The integration with popular platforms aims to streamline tasks in finance, sales, marketing, HR, and customer service.

<details><summary>References</summary>
<ul>
<li><a href="https://claude.com/product/overview">The AI for Problem Solvers | Claude by Anthropic</a></li>

</ul>
</details>

**Tags**: `#AI`, `#Small Business`, `#Anthropic`, `#Automation`, `#Product Launch`

---

<a id="item-16"></a>
## [Nvidia's Market Cap Surpasses $5.5 Trillion](https://www.ithome.com/0/950/303.htm) ⭐️ 7.0/10

On May 13, Nvidia's market capitalization exceeded $5.5 trillion, setting a new record for publicly traded companies. This milestone means Nvidia's valuation is now higher than Germany's nominal GDP for 2024 and 2025. This achievement highlights Nvidia's significant role in the tech industry and reflects broader trends in technology valuations. It could influence investor sentiment and market dynamics, particularly in the semiconductor and AI sectors. Nvidia's stock price rose by 3% on the day it reached this valuation, marking a 19.58% increase in market cap since the beginning of 2026. Other major tech companies like Alphabet and Apple have market caps of $4.86 trillion and $4.39 trillion, respectively.

telegram · zaihuapd · May 14, 16:43

**Background**: Market capitalization, often referred to as market cap, is the total value of a company's outstanding shares. It is a key indicator of a company's size and market position, and Nvidia's rise reflects the increasing importance of AI and technology in the global economy.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Nominal_GDP">Nominal GDP</a></li>
<li><a href="https://en.wikipedia.org/wiki/Market_capitalization">Market capitalization - Wikipedia Market Capitalization: What It Is and Why It Matters Market Capitalization: How It Works And Its Formula | Bankrate What Is Market Cap? Definition and Calculation - Investing.com Market Capitalization Explained: Formula, Calculator ...</a></li>

</ul>
</details>

**Tags**: `#Nvidia`, `#Market Capitalization`, `#Tech Industry`, `#Economy`, `#Investment`

---

<a id="item-17"></a>
## [Boeing Negotiates Up to 500 737 MAX Orders with China](https://t.me/zaihuapd/41389) ⭐️ 7.0/10

Boeing is in negotiations with China for a potential order of up to 500 737 MAX aircraft, marking the first significant deal in nearly a decade. This announcement is expected to be made during Trump's visit to China at the end of this month or early next month. This deal could significantly impact U.S.-China trade relations and the aviation industry, especially given the recent slowdown in China's large aircraft purchases from Boeing due to geopolitical tensions. If finalized, it would represent a major shift in Boeing's business with China. In addition to the 737 MAX order, Boeing is also discussing the potential sale of around 100 wide-body 787 and 777X aircraft, although these may be announced separately. The negotiations are still ongoing, and no binding agreements have been finalized yet.

telegram · zaihuapd · May 15, 01:09

**Background**: The Boeing 737 MAX is a series of narrow-body aircraft that features advanced technology for improved fuel efficiency and reduced emissions. The aircraft has faced scrutiny and regulatory challenges in the past, but Boeing aims to regain market confidence with new orders, especially from significant markets like China.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Boeing_737_MAX">Boeing 737 MAX - Wikipedia</a></li>
<li><a href="https://www.boeing.com/commercial/737max">737 MAX - The Boeing Company</a></li>
<li><a href="https://www.cirium.com/thoughtcloud/ascend-consultancy-how-trade-policy-shifts-are-shaping-global-aviation/">How Trade Policy Shifts Are Shaping Global Aviation - Cirium</a></li>

</ul>
</details>

**Tags**: `#Aviation`, `#Trade Relations`, `#Boeing`, `#China`, `#737 MAX`

---

<a id="item-18"></a>
## [Transition from Legacy Apps to React Native](https://simonwillison.net/2026/May/14/not-so-locked-in/#atom-everything) ⭐️ 6.0/10

A medium-sized technology company has successfully rewritten its legacy mobile apps to React Native, highlighting the framework's improvements over the years. This transition allows for easier future adaptations back to native apps if needed. This shift signifies a broader trend in mobile development where flexibility and adaptability are prioritized over traditional lock-in scenarios. It could influence other companies to reconsider their technology stacks and embrace modern frameworks. React Native has evolved significantly, providing the necessary features for modern app development while reducing the need for separate native apps. However, companies must still be aware of potential limitations in accessing platform-specific functionalities.

rss · Simon Willison · May 14, 22:53

**Background**: React Native is a popular framework for building cross-platform mobile applications using JavaScript and React. It allows developers to write code once and deploy it on both iOS and Android, which can save time and resources compared to maintaining separate native applications.

<details><summary>References</summary>
<ul>
<li><a href="https://medium.com/@fireartstudio/what-are-pros-cons-of-react-native-for-your-product-development-a85176ef0443">What are Pros & Cons of React Native for Your Product... | Medium</a></li>
<li><a href="https://nodedrift.com/blog/open-source-coding-agents-rewrite-developer-workflow">Open Source Coding Agents Are Quietly Rewriting Developer ...</a></li>
<li><a href="https://cloud.google.com/discover/what-is-agentic-coding">What is agentic coding? How it works and use cases</a></li>

</ul>
</details>

**Tags**: `#React Native`, `#Mobile Development`, `#Technology Trends`, `#Software Engineering`

---

<a id="item-19"></a>
## [Ma Huateng Addresses Tencent's AI Progress at Shareholder Meeting](https://t.me/zaihuapd/41377) ⭐️ 6.0/10

At a recent shareholder meeting, Tencent's CEO Ma Huateng discussed the company's AI progress, acknowledging past shortcomings and emphasizing a cautious approach to development. He mentioned that Tencent has been focusing on talent development and team management to strengthen its AI capabilities. This discussion is significant as it highlights Tencent's strategic shift towards enhancing its AI capabilities amidst increasing competition in the tech industry. The approach taken by Tencent could influence its market position and future innovations in AI. Ma Huateng noted that Tencent's early AI foundational capabilities were not strong, but the company is gradually getting on track through talent construction and internal training. Tencent aims to advance steadily without blindly competing for market share.

telegram · zaihuapd · May 14, 06:52

**Background**: Tencent is a major player in the technology sector, and its AI development is crucial for maintaining competitiveness. The company has shifted its focus from foundational technology development to commercial productization and ecosystem integration in recent years.

<details><summary>References</summary>
<ul>
<li><a href="https://enkiai.com/ai-market-intelligence/tencent-ai-strategy-2026-a-shift-to-dominance/">Tencent AI Strategy 2026: A Shift to Dominance - enkiai.com</a></li>
<li><a href="https://www.morningstar.com/news/dow-jones/2026051314672/tencents-valuation-repair-path-hinges-on-ai-development-market-talk">Tencent's Valuation Repair Path Hinges on AI Development ...</a></li>
<li><a href="https://www.edgen.tech/news/post/tencent-doubles-down-on-ai-with-37-billion-yuan-q1-investment">Tencent Doubles Down on AI With 37 Billion Yuan Q1 Investment</a></li>

</ul>
</details>

**Tags**: `#Tencent`, `#AI Development`, `#Corporate Strategy`, `#Ma Huateng`, `#Technology`

---

<a id="item-20"></a>
## [Obesity Rates Stabilize in High-Income Countries, Rise in Low-Income Nations](https://www.nature.com/articles/s41586-026-10383-0) ⭐️ 6.0/10

A study covering 200 countries reveals that obesity rates in high-income countries have stabilized since the 1990s, while those in low- and middle-income countries continue to rise. This trend indicates a need for policy interventions in these lower-income nations. This finding is significant as it highlights the growing obesity crisis in low- and middle-income countries, which could lead to increased health complications and economic burdens. Effective policy interventions are necessary to address this escalating public health issue. The study indicates that while childhood obesity rates in high-income countries have plateaued, adult obesity rates are following a similar trend. In contrast, low- and middle-income countries are experiencing a continuous rise in obesity rates, necessitating targeted policy responses.

telegram · zaihuapd · May 14, 09:45

**Background**: Obesity has traditionally been viewed as a problem primarily affecting high-income countries, but recent trends show that it is becoming increasingly prevalent in low- and middle-income nations. Factors such as socioeconomic status, food availability, and dietary habits play crucial roles in these trends. Understanding these dynamics is essential for developing effective public health strategies.

<details><summary>References</summary>
<ul>
<li><a href="https://www.annualreviews.org/content/journals/10.1146/annurev-publhealth-031816-044604">Obesity in Low - and Middle- Income Countries ... | Annual Reviews</a></li>
<li><a href="https://www.who.int/news-room/fact-sheets/detail/obesity-and-overweight">Obesity and overweight</a></li>

</ul>
</details>

**Tags**: `#Obesity`, `#Public Health`, `#Epidemiology`, `#Socioeconomic Factors`, `#Nutrition`

---

<a id="item-21"></a>
## [Huawei, JAC Motors, and Stellantis Discuss Maserati EV Collaboration](https://eu.36kr.com/zh/p/3807764479680774) ⭐️ 6.0/10

Huawei, JAC Motors, and Stellantis are in discussions to create a Maserati-branded electric vehicle, with production expected to start in the second half of next year. Huawei will lead product definition and provide core technology, while JAC will handle manufacturing. This collaboration highlights a significant trend in the automotive industry, where traditional car manufacturers are partnering with tech companies to enhance their electric vehicle offerings. It could impact Maserati's market presence and Stellantis's strategy for electrification in China. The first model is currently in the design phase, and while a formal agreement has not been signed, development work is already underway. The vehicles will have both domestic and international versions, with the domestic version branded as '尊界' and the international version bearing the Maserati logo.

telegram · zaihuapd · May 14, 11:15

**Background**: The collaboration comes at a time when Maserati is facing sales challenges and Stellantis is seeking partnerships with Chinese automakers to accelerate its electrification efforts. Huawei's HarmonyOS technology may play a crucial role in the vehicle's smart features.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/HarmonyOS">HarmonyOS - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Stellantis">Stellantis - Wikipedia</a></li>

</ul>
</details>

**Tags**: `#Electric Vehicles`, `#Automotive`, `#Collaboration`, `#Technology`, `#Maserati`

---

<a id="item-22"></a>
## [Removing Modem and GPS from 2024 RAV4 Hybrid](https://arkadiyt.com/2026/05/13/removing-the-modem-and-gps-from-my-rav4/) ⭐️ 5.0/10

The author details their experience of removing the modem and GPS from their 2024 RAV4 hybrid. This modification has led to discussions in the community about vehicle telemetry and data sharing practices. This modification highlights growing concerns over privacy and data sharing in modern vehicles, which can affect many car owners. It reflects a broader trend of consumers seeking more control over their vehicle's data. The removal of the modem and GPS does not completely eliminate data sharing, as connecting a phone via Bluetooth can still transmit telemetry data. Additionally, using CarPlay or Android Auto may still capture vehicle telemetry.

hackernews · arkadiyt · May 14, 17:08 · [Discussion](https://news.ycombinator.com/item?id=48138136)

**Background**: Vehicle telemetry refers to the collection and transmission of data from vehicles, which can include information on performance, location, and diagnostics. This data is often used by manufacturers for various purposes, including improving vehicle safety and performance. Concerns about data privacy have grown as more vehicles become connected to the internet.

<details><summary>References</summary>
<ul>
<li><a href="https://www.geotab.com/glossary/telemetry/">What is telemetry? How it works and why fleets need it - Geotab</a></li>
<li><a href="https://indeema.com/blog/intelligent-vehicle-telemetry-for-electric-bikes-case-study">Investigating Vehicle Telemetry - What It Is, Why It Matters ...</a></li>

</ul>
</details>

**Discussion**: Community comments reveal mixed sentiments, with some users sharing their own experiences and concerns about data sharing. Others discuss technical aspects of vehicle modifications and the implications of using connected services.

**Tags**: `#automotive`, `#modification`, `#telemetry`, `#privacy`, `#community discussion`

---

<a id="item-23"></a>
## [Exploring the Computer Hobby Movement in Canada](https://museum.eecs.yorku.ca/exhibits/show/hobby_canada/hobby_canada) ⭐️ 5.0/10

The article discusses the history and impact of the computer hobby movement in Canada, focusing on community experiences and challenges faced by enthusiasts. It highlights personal anecdotes and reflections from individuals involved in the movement. This exploration is significant as it sheds light on the cultural and historical aspects of computing in Canada, illustrating how community engagement has shaped the hobbyist landscape. Understanding this movement can inform current and future trends in technology and community building. The article does not delve deeply into technical aspects but provides a nostalgic overview of the hobbyist culture. It mentions community gatherings and the evolution of resources available to enthusiasts over time.

hackernews · rbanffy · May 14, 12:57 · [Discussion](https://news.ycombinator.com/item?id=48134743)

**Background**: The computer hobby movement emerged in the mid-20th century as individuals began to explore computing technology outside of formal education and corporate environments. This movement fostered a sense of community among enthusiasts who shared knowledge and resources, leading to the development of early computing culture.

**Discussion**: Community comments reflect a sense of nostalgia and personal connection to the past, with users sharing their experiences and the challenges they faced in accessing technology. There is a general sentiment of longing for the earlier days of the hobbyist culture.

**Tags**: `#Computer History`, `#Hobbyist Culture`, `#Canada`, `#Community`, `#Nostalgia`

---

<a id="item-24"></a>
## [Release of datasette-ip-rate-limit 0.1a0 Plugin](https://simonwillison.net/2026/May/14/datasette-ip-rate-limit/#atom-everything) ⭐️ 5.0/10

The release of datasette-ip-rate-limit 0.1a0 introduces a configurable rate limiting plugin designed to protect the Datasette site from aggressive crawlers. This plugin allows for the blocking of IPs that make excessive requests to specific areas of the site. This plugin is significant as it helps maintain the performance and stability of the Datasette site by preventing overload from aggressive crawlers. It benefits web developers and site administrators who rely on Datasette for data management and presentation. The plugin allows configuration of parameters such as maximum requests per IP and exempt paths. It can block IPs for a specified duration if they exceed the request limits.

rss · Simon Willison · May 14, 04:10

**Background**: Rate limiting is a technique used to control the amount of incoming traffic to a server, preventing abuse and ensuring fair usage. It is particularly important for web applications that may be targeted by bots or aggressive crawlers. Datasette is an open-source tool for publishing and exploring datasets, and plugins extend its functionality.

<details><summary>References</summary>
<ul>
<li><a href="https://datasette.io/plugins">Datasette Plugins</a></li>
<li><a href="https://docs.datasette.io/en/stable/plugins.html">Plugins - Datasette documentation</a></li>
<li><a href="https://learn.microsoft.com/en-us/aspnet/core/performance/rate-limit?view=aspnetcore-10.0">Rate limiting middleware in ASP.NET Core | Microsoft Learn</a></li>

</ul>
</details>

**Tags**: `#Datasette`, `#Rate Limiting`, `#Web Development`, `#Plugins`, `#Open Source`

---

<a id="item-25"></a>
## [JD.com Launches AI Hardware Section with NVIDIA Products](https://u.jd.com/HaDkFMa) ⭐️ 5.0/10

JD.com has launched a dedicated section for AI hardware, featuring products like the NVIDIA GeForce RTX 5090, RTX PRO 6000, and H100, which were previously subject to sanctions. These products are now available for purchase again. This launch is significant as it indicates a potential easing of restrictions on high-performance computing hardware in China, which could impact the AI and gaming industries. Consumers and businesses may benefit from access to advanced technology that was previously unavailable. The NVIDIA GeForce RTX 5090 features 32GB of GDDR7 memory and is built on the Blackwell architecture, while the RTX PRO 6000 is designed for professional rendering and data centers. The H100 GPU is known for its exceptional performance in AI workloads and has a dedicated Transformer Engine.

telegram · zaihuapd · May 14, 15:15

**Background**: The NVIDIA GeForce RTX series is known for its advanced graphics capabilities, including real-time ray tracing and AI-enhanced performance. The H100 GPU is part of NVIDIA's Hopper architecture, designed to accelerate AI applications significantly. The availability of these products on JD.com marks a notable shift in the accessibility of high-end computing hardware in China.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Nvidia_GeForce_RTX_5090">Nvidia GeForce RTX 5090</a></li>
<li><a href="https://www.nvidia.com/en-us/data-center/h100/">NVIDIA H100 GPU</a></li>
<li><a href="https://www.nvidia.com/en-us/products/workstations/professional-desktop-gpus/rtx-pro-6000/">NVIDIA RTX PRO 6000 Blackwell Workstation Edition</a></li>

</ul>
</details>

**Tags**: `#AI Hardware`, `#NVIDIA`, `#E-commerce`, `#Technology`, `#China`

---

<a id="item-26"></a>
## [ChatGPT Android Version Reveals Remote Desktop Control Feature](https://t.me/zaihuapd/41388) ⭐️ 5.0/10

The APK teardown of ChatGPT Android version 1.2026.125 shows that OpenAI is developing a remote desktop session control feature for mobile devices. This feature will allow users to search and reconnect to remote sessions directly from their phones. This development is significant as it could enhance the usability of Codex by allowing users to manage their coding sessions remotely. It may impact developers who rely on mobile access to their desktop environments. The feature is still in development and does not have a publicly available preview or launch date. Users will need to log in with the same account on both mobile and desktop to utilize this functionality.

telegram · zaihuapd · May 14, 21:48

**Background**: Remote desktop control technologies allow users to access and manage their computers from mobile devices. OpenAI's Codex is a tool designed to assist with coding tasks, and this new feature aims to expand its functionality by integrating mobile access.

<details><summary>References</summary>
<ul>
<li><a href="https://developers.openai.com/codex/remote-connections">Remote connections – Codex | OpenAI Developers</a></li>
<li><a href="https://www.androidheadlines.com/2026/05/openai-chatgpt-codex-remote-pc-control-android-leak.html">ChatGPT Codex to Get Remote PC Control from Android Phones</a></li>

</ul>
</details>

**Discussion**: There have been mixed reactions in the community, with some expressing excitement about the potential for mobile coding. Others have raised concerns about security and the practicality of using remote desktop features on mobile devices.

**Tags**: `#ChatGPT`, `#OpenAI`, `#Android`, `#Remote Control`, `#APK Teardown`

---