<h1 align="center">Hi, I'm Aditya 👋</h1>

<p align="center">
  <b>Software + ML engineer · M.S. Computer Engineering @ NYU Tandon</b><br/>
  I build systems that stay correct when things go wrong: offline devices, flaky networks, misbehaving AI agents.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/aditya-patil-710347376/"><img src="https://img.shields.io/badge/LinkedIn-Aditya%20Patil-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:adityaapatil2020@gmail.com"><img src="https://img.shields.io/badge/Email-adityaapatil2020%40gmail.com-D14836?style=flat&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://scholar.google.com/citations?user=lCJvfogAAAAJ"><img src="https://img.shields.io/badge/Google%20Scholar-Papers-4285F4?style=flat&logo=googlescholar&logoColor=white" alt="Google Scholar"/></a>
  <a href="https://leetcode.com/u/Aditya_patil28/"><img src="https://img.shields.io/badge/LeetCode-Profile-FFA116?style=flat&logo=leetcode&logoColor=black" alt="LeetCode"/></a>
</p>

> 🟢 **Open to Summer 2027 internships**: software engineering and ML engineering. [Email me](mailto:adityaapatil2020@gmail.com) or [connect on LinkedIn](https://www.linkedin.com/in/aditya-patil-710347376/).

---

## 🚀 Things I've built

### 📝 [collab-editor](https://github.com/adityapatil2804/collab-editor): Google Docs-style editing that keeps working offline · [**▶ try it live**](https://collab-editor-5ois.onrender.com/?doc=demo)
Two people type into the same document, one goes offline, both keep typing, and when they reconnect every copy ends up identical, with no server deciding the order.
- **The hard part:** a custom sequence **CRDT** (the Fugue algorithm) written twice, in **Rust** and **TypeScript**, and kept byte-for-byte consistent with cross-language tests.
- **Evidence:** 10,000 randomized network scenarios (partitions, reordering, duplicate messages) all converge · 100 concurrent clients on one document · ~160× faster storage than the naive version.
- **Engineering:** a Rust WebSocket server with no dependencies, a crash-safe op log with group commit (fsync latency 3.2 s → 69 ms), and an installable offline app (PWA).

### 🛡️ [mandate](https://github.com/adityapatil2804/mandate): a security gateway that stops AI agents from overstepping
AI agents call tools such as email, files and HTTP. Mandate checks every call against what the human actually delegated, and refuses everything else.
- **The hard part:** delegated authority with **Ed25519-signed task tokens**, policy-as-code in **OPA/Rego**, a fail-closed gateway, and a signed hash-chained audit log you can replay and verify.
- **Evidence:** 37/37 scripted attacks blocked · 0/12 false blocks · ~0.8 ms median decision latency · runs as an **MCP server** inside Claude Desktop.

### 📉 [calibration-under-shift](https://github.com/adityapatil2804/calibration-under-shift): can you trust a model's confidence when the data changes?
Measures how classifiers' confidence holds up under corrupted inputs (CIFAR-10-C, ResNet-34), comparing a baseline, label smoothing, Mixup and deep ensembles on accuracy and calibration error (ECE).

---

## 🔬 Research

- **Focus:** trustworthy AI, especially how to govern and evaluate AI agents.
- Co-author of a paper on **trustworthy agentic RAG**, under review at *IEEE Transactions on Software Engineering*.
- ~10 journal and conference papers (2023–2025) · [Google Scholar](https://scholar.google.com/citations?user=lCJvfogAAAAJ) h-index 2.

| Where | When | What I worked on |
|---|---|---|
| **IKST**, Bangalore | Sep 2025 – Feb 2026 | Safety layer and evaluation framework for AI agents |
| **Korea University**, Seoul | Jun – Aug 2025 | Fraud and anomaly detection on blockchain data |
| **CSIR–NCL**, Pune | Nov 2024 – Feb 2025 | MIS web portal |
| **KIST**, Seoul | Jun – Jul 2024 | Anomaly detection in CCTV footage with vision-language models |
| **KIST**, Seoul | Jul – Aug 2023 | Deepfake detection |

---

## 🛠️ Tools I use

<p>
  <img src="https://skillicons.dev/icons?i=py,rust,ts,js,c,pytorch,tensorflow,nodejs,docker,linux,git,html,css&perline=13" alt="Python, Rust, TypeScript, JavaScript, C, PyTorch, TensorFlow, Node.js, Docker, Linux, Git, HTML, CSS"/>
</p>

## ⚡ A few more things

- 📚 Wrote **3 technical books**: *Data Science Mastery*, *C Programming*, *Python Pathway*.
- 💡 Holds an **Indian design patent** for an IoT cardiovascular monitoring device.
- 🎓 B.Tech. Computer Engineering, VIIT Pune (CGPA 8.81/10) · now M.S. at NYU Tandon, New York.

<p>
  <img height="160" src="https://github-readme-stats.vercel.app/api?username=adityapatil2804&show_icons=true&hide_border=true&count_private=true" alt="GitHub stats"/>
  <img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=adityapatil2804&layout=compact&hide_border=true&langs_count=6" alt="Top languages"/>
</p>
