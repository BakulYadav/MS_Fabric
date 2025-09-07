**Fabric data agent concepts**

Data agent in Microsoft Fabric is a new Microsoft Fabric feature that allows you to build your own conversational Q&A systems using generative AI. A Fabric data agent makes data insights more accessible and actionable for everyone in your organization. With a Fabric data agent, your team can have conversations, with plain English-language questions, about the data that your organization stored in Fabric OneLake and then receive relevant answers. This way, even people without technical expertise in AI or a deep understanding of the data structure can receive precise and context-rich answers.

You can also add organization-specific instructions, examples, and guidance to fine-tune the Fabric data agent. This ensures that responses align with your organization's needs and goals, allowing everyone to engage with data more effectively. Fabric data agent fosters a culture of data-driven decision-making because it lowers barriers to insight accessibility, it facilitates collaboration, and it helps your organization extract more value from its data.

**Prerequisites**

A paid F2 or higher Fabric capacity, or a Power BI Premium per capacity (P1 or higher) capacity with Microsoft Fabric enabled
Fabric data agent tenant settings is enabled.
Copilot tenant switch is enabled.
Cross-geo processing for AI is enabled.
Cross-geo storing for AI is enabled.
At least one of these: A warehouse, a lakehouse, one or more Power BI semantic models, or a KQL database with data.
Power BI semantic models via XMLA endpoints tenant switch is enabled for Power BI semantic model data sources.

**Difference between a Fabric data agent and a copilot**

While both Fabric data agents and Fabric copilots use generative AI to process and reason over data, there are key differences in their functionality and use cases:

Configuration Flexibility: Fabric data agents are highly configurable. You can provide custom instructions and examples to tailor their behavior to specific scenarios. Fabric copilots, on the other hand, are preconfigured, and they don't offer this level of customization.

Scope and Use Case: Fabric copilots are designed to assist with tasks within Microsoft Fabric, such as generation of notebook code or warehouse queries. Fabric data agents, in contrast, are standalone artifacts. To make Fabric data agents more versatile for broader use cases, they can integrate with external systems like Microsoft Copilot Studio, Azure AI Foundry, Microsoft Teams, or other tools outside Fabric.

**Reference**: https://learn.microsoft.com/en-us/fabric/data-science/concept-data-agent# MS_Fabric
A curated collection of my Microsoft Fabric projects, covering end-to-end implementations with Lakehouse, Warehouse, Data Pipelines, Real-Time Analytics, and Power BI integrations. This repository includes hands-on labs, sample datasets, reusable code snippets, and best practices for building modern data solutions using Microsoft Fabric.
