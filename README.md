# RAG Innovator Lab
## Powerful AI Apps on Open and Lake-centric Data Foundation

This repository is part of Microsoft Korea's AI Innovator Labs.

-----

## 0️⃣ Introduction

**RAG Innovator Lab** designs an end-to-end integration scenario between Microsoft Fabric (OneLake) and AI Foundry.

The scenario demonstrates how to ingest data from multiple sources into OneLake, connect it with AI Search, and further integrate it with AI Foundry to enable AI-driven responses and analytics.

RAG Innovator Lab's goal is to showcase the **integration between Microsoft Fabric and AI Foundry**, and ultimately, to provide insights for future service requirements and enhancements.


## 1️⃣ Solution Scenario

In this current setup:

* **AI Search** is positioned between OneLake and AI Foundry as the vector search engine for RAG.

* By leveraging the **OneLake Indexer**, there's no need to manually connect separate databases or data sources other than OneLake.

* OneLake serves directly as both the data source and the vector store for the target data within Promptflow in AI Foundry.

* Using the **Promptflow** GUI, users can easily connect **OneLake-based AI Search** to an LLM node, creating a seamless RAG pipeline.

## 2️⃣ Lab Agenda

This lab is designed to be hands-on, allowing users to experience and interact with the integrated RAG pipeline firsthand. The lab is designed to take approximately 4 hours.

| No | Task                                   | Duration       | Description                       |
|----|----------------------------------------|----------------|-----------------------------------|
| 1  | Microsoft Fabric Overview              | 60 minutes     |                                   |
| 2  | Microsoft Fabric Hands-On Lab          | 60 minutes     |                                   |
| 3  | Azure AI Foundry Overview              | 60 minutes     |                                   |
| 4  | AI Application Development Hands-On Lab| 30 minutes     | (Optional) Evaluation, +30 minutes |
| 5  | Wrap-up and Q&A                        | 30 minutes     |                                   |

## 3️⃣ Materials

You can find the step-by-step instructions for lab participants here: [Step-by-Step User's Guide - Korean](RAG_Inno_Lab_User_Guide.pdf)

The pre-lab setup guide for instructors will be available here: [Pre-Lab Instructor's Guide - TBU](AIFoundry\RBAC_CLI\instructor-role-assign.azcli)
