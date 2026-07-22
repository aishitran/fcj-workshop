---

title: "Event 3: FCAJ Community Day - 27/06/2026 (Online)"
date: 27-06-2026
weight: 3
chapter: false
pre: " <b> 4.3. </b> "
----------------------

![Proof](/fcj-workshop/images/4-EventParticipated/20260627.jpg)

### **1. Speaker 1 (Steve Tran): AgenticOps for your Cloud**

* **Increasing cloud operational complexity:** As systems evolve from **Microservices** toward environments with more advanced **Observability** requirements, the number of tools and operational tasks also increases. This creates a **"Complexity Wall"**, while also increasing the demand for cloud operations engineers and the time required to resolve incidents (**MTTR**).

* **CloudThinker:** An enterprise AgenticOps platform that uses AI agents to observe cloud environments, analyze system conditions, and assist with operational issues.

  * Supports incident response, security-related tasks, and cost optimization.
  * Provides specialized agents for different operational roles and tasks.
  * Continuously observes the environment to collect context and determine appropriate actions.
  * Applies **context optimization** to reduce unnecessary context and control costs in multi-agent systems.
  * Follows the **Detect → Resolve → Validate** operational cycle, while important actions may still require human approval and must comply with SLA requirements.

### **2. Speakers 2 (Trung Vu, Nghi Danh, Kiet Tran): Building Voice Agent (VA) at Scale**

* **Speech-to-speech:** Current speech-to-speech technology is still not fully ready for widespread production deployment.

* **Practical approach:** Combining **TTS (Text-to-Speech)** with fine-tuned models to produce more natural speech and a more human-like communication experience.

* **Latency reduction:** Performing model **warm-up** before processing requests to improve response time.

* **Observability for Voice Agents:** A complete system of metrics, tracing, and observability is required to monitor model behavior, identify issues, and support continuous improvement.

### **3. Speakers 3 (Bao Phan, Nguyen Nguyen): AWS DevOps Agent**

* **Limitations of traditional incident response:** Manual investigation requires significant time and cost, while **MTTD** and **MTTR** can remain high. Important context may also be lost during handoffs between teams.

* **AWS DevOps Agent:** An AI agent designed to support the automation of incident investigation and response, while also helping proactively suggest ways to prevent similar incidents in the future.

* **Key principles:** The solution focuses on **Context Learning, Control, Integration, Collaboration**, and **Cost-effectiveness**.

* **Incident response lifecycle:** The process follows **Triage → Investigation → Mitigation → Prevention**, covering incident classification, investigation, impact reduction, and prevention.

* **Suitable environment:** The solution works more effectively in systems with mature observability, including well-organized logs, metrics, and alarms. The AI agent can summarize context and recommend next steps, while humans remain responsible for reviewing, approving, and making final decisions.

### **4. Speakers 4 (Truong Tran, Anh Minh): AI-Powered Productivity Workforce Planning for Enterprise**

* **Challenges in traditional HR:** Manual processes often require significant time, may overlook valuable talent, and can rely heavily on subjective judgment rather than data.

* **The role of AI:** Reducing manual screening and processing tasks, supporting data-driven HR decisions, and allowing more focus on talent development and workforce strategy.

* **Amazon Quick Solutions:** Tools such as **Chat Agents, Research, QuickSight, Flows**, and **Automate** support data processing, report generation, data visualization, and multi-step workflow automation.

* **HR use cases:** Connecting data → analyzing information → generating reports and visualizations → evaluating candidates → following up on subsequent actions.

* **Recruitment support:** AI can generate interview questions based on hiring objectives, assist with candidate evaluation, and provide recommendations for HR to consider during the decision-making process.

### **5. Speakers 5 (Toan Nguyen, Nghi Danh): Building Secure Private MCP for AWS Quick**

* **Amazon Quick and MCP:** An overview of Amazon Quick and the **Model Context Protocol (MCP)**, including the role of MCP in connecting AI systems with external services.

* **The public endpoint challenge:** The default MCP connector requires a **public endpoint**, which may cause context and logs to travel through the public internet. This increases the **attack surface** and introduces additional security concerns.

* **Private VPC connectivity:** A private MCP architecture can be used to reduce exposure to the public internet.

  * **Private Entry:** Removes the dependency on a public endpoint.
  * **Private DNS:** The hostname is resolved only within the VPC's internal network.
  * **Private traffic flow:** Traffic follows the **ENI → ALB → MCP** path, keeping the connection within a private network environment and reducing exposure to the public internet.
