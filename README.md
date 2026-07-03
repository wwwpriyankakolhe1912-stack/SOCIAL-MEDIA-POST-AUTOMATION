# SOCIAL-MEDIA-POST-AUTOMATION
Architected and deployed a fully automated, end-to-end asynchronous content generation and publishing pipeline. By bridging structured cloud databases, Large Language Models (LLMs), and third-party social APIs, this system eliminates manual copywriting and scheduling overhead, enabling seamless, zero-intervention content syndication.

System Architecture & Implementation
Automated Data Ingestion (Google Sheets Trigger):

Configured a polling/event-driven listener on a centralized database to monitor for new rows. Each new entry acts as a structured data payload containing the seed topics or parameters that initiate the entire downstream workflow.

Contextual Content Generation (Google Gemini & LLM Chaining):

Integrated Google Gemini using a Basic LLM Chain node.

Engineered contextual prompts to ingest the raw sheet parameters, apply specific brand voice constraints, and programmatically generate high-engagement, platform-optimized text content.

Programmatic Syndication (LinkedIn API Integration):

Developed the final execution node to pipe the AI-generated payload directly into the LinkedIn API, automatically authenticating and publishing the finalized post onto the target profile with zero manual touchpoints.

Core Engineering Takeaways
Event-Driven Automation: Mastered the orchestration of sequential, multi-platform workflows using n8n to connect disparate cloud tools and APIs.

LLM Pipeline Integration: Gained hands-on experience embedding deterministic LLM nodes directly into automated business logic pipelines, turning raw inputs into deployment-ready creative assets.

Tech Stack
n8n | Google Gemini | LLM Chaining | LinkedIn API | Google Workspace API | Workflow Automation | Event-Driven Architecture
