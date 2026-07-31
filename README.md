# Multi-Agent-AI-Research-Platform-with-AWS-Guardrails-LLM-Gateway-Red-Teaming
A production-grade autonomous research platform where a 4-agent LangGraph pipeline (Search → Summarize → Write → Verify) processes any topic end-to-end, with every request passing through AWS Bedrock Guardrails, a TensorZero LLM gateway with GPT-4o/Groq fallback, and a three-tier memory system — Redis session memory (STM), pgvector long-term memory (LTM), and semantic caching. Every report is automatically scored by an LLM-as-judge via LangSmith, while a PyRIT red team dashboard continuously stress-tests the system with jailbreak, XPIA, crescendo, and skeleton key attacks to prove the guardrails hold under real adversarial pressure. Full infrastructure on AWS, provisioned with Terraform, deployed via GitHub Actions CI/CD.

## 📸 Project Preview

<p align="center">
  <img
    src="https://career-platform-may-2026.s3.ap-south-1.amazonaws.com/krishnaik.in/media/project_banners/WhatsApp_Image_2026-07-23_at_3.26.05_PM.jpeg"
    alt="Project Preview"
    width="900"
  />
</p>

<p align="center">
  <b>Application Preview</b>
</p>

---

## 🏗️ Project Architecture

<p align="center">
  <img
    src="https://career-platform-may-2026.s3.ap-south-1.amazonaws.com/krishnaik.in/media/project_architecture_diagrams/AWS_Multi-Agent_Pipeline-2026-06-29-104635.png"
    alt="AWS Multi-Agent Architecture"
    width="900"
  />
</p>

<p align="center">
  <b>AWS Multi-Agent System Architecture</b>
</p>
