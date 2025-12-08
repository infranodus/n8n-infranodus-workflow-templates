# n8n Infranodus Workflow Templates

Useful n8n templates to be used with [InfraNodus knowledge graphs](https://infranodus.com) for portable GraphRAG integrated into your LLM workflows.

## Installation Instructions

- Choose the template based on your use case,
- Download the JSON file,
- Import the JSON file into your n8n workflow
- Provide your InfraNodus API key in InfraNodus GraphRAG nodes
- The API key can be obtained at [https://infranodus.com/api-access](https://infranodus.com/api-access) if you have an account. You can send empty requests to try out the workflows.

Alternatively, you can also use the templates we published in [n8n workflows](https://n8n.io/creators/infranodus) but as n8n delays publishing, many more templates are available in this repository.

## Use Cases

- [Chatbot Experts](graphrag-chatbots-experts/) — Use InfraNodus knowledge graphs and our GraphRAG to create chatbots with a panel of experts. Each graph is an expert on a certain topic. Check out the example on [Circadian Press](https://circadian.co/shop/) website where every book has an AI chatbot that answers questions based on the book's content. You can also see the custom Zendesk AI chatbot in action on our support portal [support.noduslabs.com](https://support.noduslabs.com).

You can also use our custom [n8n chatbot widget tool](https://n8n-chat-widget.com) to create a customized embeddable / popup chatbot widget and add it to your website, blog, or Zendesk portal. It can also be accessed via a URL.

- [Zendesk AI Chatbot Agent](customer-support-email/zendesk-ai-chatbot-agent.json) — An easy to set up custom AI chatbot for your Zendesk knowledge portal. Works much better than the native Zendesk one and is cheaper, too. Learn more and see it in action on our [support portal](https://support.noduslabs.com/hc/en-us/articles/24080152180252-Building-an-Embeddable-AI-Chat-for-Zendesk-Knowledge-Support-Portal)

- [Telegram Chat with a Knowledge Graph](graphrag-chatbots-experts/telegram-ai-experts.json) — Telegram chat with a panel of experts using the InfraNodus knowledge graph as its knowledge.

- [Chat to PDFs with no Vector Store](graphrag-chatbots-experts/graphrag-pdf-chat-no-vector-store.json) — Use the InfraNodus knowledge graph to set up a chatbot with PDFs without complex vector store setup. Just plug and play.

- [Web Chat with a Knowledge Graph](graphrag-chatbots-experts/chatbot-ai-experts.json) — Web chat with a panel of experts using the InfraNodus knowledge graph as its knowledge.

- [Voice Chat with a Knowledge Graph and ElevenLabs](graphrag-chatbots-experts/chatbot-voice-ai-knowledge-graphs.json) — Voice chat with a panel of experts using InfraNodus as an knowledge agent for your ElevenLabs voice chatbot.

- [Reasoning Expert with Graph RAG Knowledge Ontology](graphrag-chatbots-experts/reasoning-expert-graph-ontology.json) — Use the InfraNodus knowledge graph to set up a reasoning expert with a knowledge ontology that tells your AI agent how to think (not only what to think).

- [Marketing and SEO: Finding Gaps and Studying Competition](marketing-seo/) - These workflows use InfraNodus to study the market and identify content gaps in your competitors' discourse. You can use these gaps to generate business ideas and SEO-optimized content.

  - [Find Content Gaps in URLs List](marketing-seo/find-content-gaps-in-urls-list.json) — Upload a list of URLs, build a knowledge graph, identify the main topics, generate research ideas based on the gaps between them.

  - [Find Content Gaps in URLs List with AI Content Creator Agent](marketing-seo/find-content-gaps-in-urls-list-open-ai-agent.json) — Same as above, but with the content creator agent that generates a blog post draft based on the gaps between the topics.

- [Research & Science](research/) — Study the current discourse in any field and identify the gaps between topical clusters using the knowledge graphs. Use the gaps to generate ideas and bridge the topics in a new way.

  - [Find Content Gaps in PDFs](research/content-gaps-research-ideas-pdfs.json) — Upload PDFs, build a knowledge graph, identify the main topics, generate research ideas based on the gaps between them.

  - [Generate AI Prompts from PDFs](research/generate-ai-prompts-research-questions-pdfs.json) — Upload PDFs, build a knowledge graph, and generate AI prompts based on the gaps between the topics. Use it in your LLM workflows or for idea generation.

- [Content Creation](content-creation/) - Generate content ideas for your blog, website, and social media.

  - [Generate Content Ideas from PDF Documents using GraphRAG](content-creation/generate-content-ideas-from-pdfs-content-gaps.json) — Upload PDFs, build a knowledge graph, and generate content ideas based on the gaps between the topics.

  - [Optimize Top Performing Content with Firecrawl and Google Analytics](content-creation/optimize-top-performing-content-firecrawl-google-analytics.json) — Use Firecrawl and Google Analytics to detect the main topics and content gaps in your top-performing content and to get inspiration for new publications.

- [Customer Support and Email Analysis](customer-support-email/) — AI workflows to analyze your customer support tickets and email content.

  - [Zendesk AI Chatbot Agent](customer-support-email/zendesk-ai-chatbot-agent.json) — An easy to set up custom AI chatbot for your Zendesk knowledge portal. Works much better than the native Zendesk one and is cheaper, too. Learn more and see it in action on our [support portal](https://support.noduslabs.com/hc/en-us/articles/24080152180252-Building-an-Embeddable-AI-Chat-for-Zendesk-Knowledge-Support-Portal)

  - [Zendesk Visual Summary and Slack Notifications](customer-support-email/zendesk-visual-summary-slack-notifications.json) — Daily visual summary of the main topics in your Zendesk tickets - notified via Slack.

  - [Gmail Visual Summary and Auto-Labeling](customer-support-email/gmail-label-emails-knowledge-graph.json) — Visual summary and auto-labeling of Gmail emails.

  - [Gmail Summarize Knowledge Graph](customer-support-email/gmail-summarize-knowledge-graph.json) — Generate a knowledge graph from your Gmail emails and summarize the main topics. Receive the notification via Telegram or Email.

- [Automated File Processing](file-upload-sync/) — Automatically sync the files from your Google Drive or Dropbox to your InfraNodus account.

## Future Plans

[ ] Generate a SEO Report for any Market: Keywords, Topical Clusters, and Content Gaps

[ ] Generate a Public InfraNodus Graph for any Content with a URL and image

[ ] Your suggestions? Please, leave them in [this repo's issues](https://github.com/infranodus/n8n-infranodus-workflow-templates/issues)

## API Documentation and Support

Video with a demo of the Chat workflows: [https://www.youtube.com/watch?v=kS0QTUvcH6E](https://www.youtube.com/watch?v=kS0QTUvcH6E)

Check this [YouTube playlist on InfraNodus GraphRAG API applications](https://www.youtube.com/playlist?list=PLZhDuTZwzpWcgWKn2ZKQPPvuFU4hepQc9) to learn more about the different AI workflows that you can use with n8n, Dify, Make.Com, Crew AI, and other tools and agentic frameworks.

You will need an [InfraNodus account](https://infranodus.com/use-case/ai-knowledge-graphs) and the [InfraNodus API key](https://inranodus.com/api-access) to use the InfraNodus HTTP request nodes in these templates.

![https://support.noduslabs.com/hc/article_attachments/20174232165916](https://support.noduslabs.com/hc/article_attachments/20174232165916)
