---
title: "CCM-HealthInsight: A Multi-Agent Assistant for Complex Clinical Case Analysis"
excerpt: "CCM-HealthInsight is a multi-agent LLM system designed for complex clinical case analysis and structured report generation for an ACT clinic.
In clinical practice, some cases require extensive review of patient history, symptom patterns, syndrome differentiation, and supporting medical literature.
 This process can be time-consuming, especially for complex cases where clinicians need to compare multiple diagnostic possibilities and justify treatment 
 decisions with appropriate evidence.
This project was developed to support that workflow. CCM-HealthInsight integrates three large language model providers, DeepSeek, Qwen, and Moonshot,
 to assist with case structuring, Chinese medicine syndrome differentiation, evidence research, treatment reasoning, report generation, and safety review. 
 By combining LLM-assisted analysis with the expertise of experienced clinicians, the system aims to improve the efficiency, consistency, and transparency of complex case review.
The system uses a four-layer architecture: a Vue-based frontend, a FastAPI backend, a multi-agent workflow layer, and external LLM services. 
Users can enter or dictate clinical case information through the frontend. The backend then coordinates a set of role-based agents to transform 
raw patient narratives into a structured, reviewable clinical report.
The multi-agent workflow includes specialized agents for case structuring, syndrome differentiation, evidence research, consensus reasoning, 
report writing, and safety auditing. Instead of relying on a single LLM response, CCM-HealthInsight compares and consolidates outputs 
from multiple LLM providers so that different reasoning perspectives can be reviewed together. The final report is designed to be hierarchical, 
transparent, and easy for clinicians to validate.
A key design principle of this project is that AI should support, not replace, clinical judgment. The generated report includes model 
reasoning, evidence summaries, consensus results, safety notes, and review prompts. Clinicians remain responsible for validating, editing, and approving the final output before use. <br/><img src='/images/ccm_healthinsight_4layer_flow_chat.png' style='margin-top: 15px;'>"
collection: project
---

This is an item in your portfolio. It can be have images or nice text. If you name the file .md, it will be parsed as markdown. If you name the file .html, it will be parsed as HTML. 
