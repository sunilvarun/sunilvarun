### Hi, I'm Sunil 👋

I'm a product manager who likes to learn by building. When I'm trying to understand a problem, I often prototype the ML or agent part myself. It helps me see what's actually possible before I form an opinion.

Lately I've been exploring AI agents that act on someone's behalf, and how to make them safe and trustworthy to use.

---

#### 🧠 A few things I try to keep in mind

- Start from the decision the user is trying to make, not from the model.
- If an agent can act for you, trust matters more than cleverness. Limits and confirmation steps are part of the product.
- A small prototype often teaches more than a long document.
- Measure what changes for the user, not how impressive the demo looks.

I'm still learning all of these, and these projects are where I practice.

---

#### 🛠 Things I've been building

| Project | The question I was curious about | What I tried |
|---|---|---|
| [**agentic-commerce-mcp**](https://github.com/sunilvarun/agentic-commerce-mcp) | How could an AI agent shop for someone without overspending? | An MCP server that lets Claude search, compare, fill a cart and check out. It has simple spending limits and always asks before buying. |
| [**Phone shopping agent**](https://github.com/sunilvarun/apple-store-agent) | Can real owner reviews help someone choose a phone more easily than a spec sheet? | Collected about 10K reviews from YouTube and Reddit and scored them by aspect (battery, camera, etc.) with aspect-based sentiment. A Claude agent uses those scores to suggest phones and show what real reviewers said. |
| [**hotel-reviews-nlp**](https://github.com/sunilvarun/hotel-reviews-nlp) | What do hotel guests actually praise and complain about? | Topic modeling on 515K European hotel reviews, comparing LDA with BERTopic. |

<p align="center">
  <img src="https://raw.githubusercontent.com/sunilvarun/hotel-reviews-nlp/main/eda_overview.png" width="700" alt="Exploring 515K hotel reviews">
</p>

---

#### 🧰 Tools I've used

**ML / NLP:** sentence-transformers · BERTopic · LDA (Gensim) · spaCy · aspect-based sentiment · RAG / FAISS
**Agents & LLMs:** Claude · Model Context Protocol (MCP) · tool use
**Building:** Python · FastAPI · React · Jupyter · SQLite

---

<sub>These are side projects and experiments, so feedback and suggestions are very welcome.</sub>
