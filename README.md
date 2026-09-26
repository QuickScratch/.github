<p align="center">
  <a href="https://quickscratch.io">
    <img src="./banner.png" alt="Quickscratch: secure, private AI agents for your business" width="100%">
  </a>
</p>

# Quickscratch

**An EU-based AI studio.** We build AI assistants, document processing and private AI systems on one shared core, so a standard assistant is scoped to go live within 2 weeks, not quarters.

Your team shouldn't spend Friday compiling reports.

[Website](https://quickscratch.io) · [What we build](https://quickscratch.io/build/) · [Worked example](https://quickscratch.io/work/) · [Book a 30-min call](https://calendly.com/d/dv7y-xs3-y52/quickcall) · [LinkedIn](https://www.linkedin.com/company/quickscratch)

---

## What we build

| | |
|---|---|
| **[AI support and sales assistants](https://quickscratch.io/build/support-sales-assistant/)** | Answers from your knowledge base, qualifies leads, explains your offer. Scoped to go live in up to 2 weeks, and it tells users it's an AI from the first message. |
| **[Search across company knowledge](https://quickscratch.io/build/company-knowledge-assistant/)** | Plain-language questions across drives, wikis and systems, answered with sources and with access rights respected. A knowledge graph when a question spans many documents. |
| **[Document extraction](https://quickscratch.io/build/document-extraction/)** | Scanned PDFs and images into structured data, with OCR on the cloud you already use (AWS Textract, Azure Document Intelligence, Google Document AI) or fully on your own servers. |
| **[Reports from your own systems](https://quickscratch.io/build/automated-reports/)** | Connected to your helpdesk, CRM or internal tools through their API. The weekly summary, statistics and trends arrive on their own. |
| **[Small private models](https://quickscratch.io/build/private-small-models/)** | Extraction, classification, reranking and masking personal data before it reaches a cloud model. Trained on your examples when nothing public is good enough, and run where your data lives. |
| **[MCP server](https://quickscratch.io/build/mcp-server/)** | Query and analyse your database, spreadsheets or CRM from Claude, ChatGPT or Cursor through the Model Context Protocol. *Early access.* |

## One shared core underneath

Every product stands on the same core: retrieval, file handling, OCR integrations, model routing, evaluation and monitoring. For each project we select the modules it needs and build only the integration with your systems.

- **Model-agnostic by default.** OpenAI, Anthropic, Google, Qwen, DeepSeek or an open-weight model on your own infrastructure, all behind one interface. Switching is a configuration change, not a rewrite.
- **Retrieval matched to the question.** Plain vector search for a clean knowledge base, a corrective second pass when the first result doesn't answer, a knowledge graph when the answer spans documents.
- **The right store for the job.** Qdrant for scale and metadata filtering, Neo4j when the answer depends on how things relate, BM25 alongside vector search so exact codes and names aren't lost.
- **Evals before opinions.** Every behaviour you care about becomes a test, and nothing ships until it passes.
- **Cost you can see.** Spend per request, per feature and per client, with limits you set.
- **Better after launch.** Your integration is kept separate from the core, so fixes and upgrades reach every project.

## Private by design

Before anything reaches a cloud model, a small local model finds and masks names, ID numbers, account numbers and other personal data, then restores them in the answer. The cloud model sees the task, not the person. For fully private workloads, the whole pipeline runs on your own servers.

## How we work

1. **30-minute call.** You describe the problem; we tell you whether it needs AI at all.
2. **Fixed quote.** Scope and price, set to your requirements, agreed in writing before any code.
3. **Build.** We assemble the core, integrate your systems and test against your data. You see a working demo on your own documents before launch.
4. **Run and improve.** We host, monitor and improve it. Payment follows proof: the last milestone comes after acceptance tests agreed before the build started.

## Get in touch

Bring us one workflow. We'll tell you what it needs.

**[Book a 30-min call](https://calendly.com/d/dv7y-xs3-y52/quickcall)** or write to **[contact@quickscratch.io](mailto:contact@quickscratch.io)**.
