<p align="center">
  <img src="./ai-workflow.svg" width="100%" alt="Li Fenyong — Applied AI Engineer">
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&amp;weight=600&amp;size=22&amp;duration=3200&amp;pause=1000&amp;color=0D9488&amp;center=true&amp;vCenter=true&amp;width=425&amp;height=35&amp;lines=%3E+Orchestrating+AI+agents;%3E+Building+hybrid+retrieval;%3E+Developing+AR+tutors" width="425" alt="Orchestrating AI agents · Building hybrid retrieval · Developing AR tutors">
</p>

<p align="center">
  <a href="#selected-systems">Selected systems</a> ·
  <a href="#public-code--research">Public code &amp; research</a>
</p>

**I build the systems around the model.** I take AI projects from architecture to implementation, building the orchestration, retrieval, and interfaces that turn a model call into a working application.

## Selected systems

### 01 / Multi-agent decision support

**Independently built an end-to-end decision-support system.** A LangGraph supervisor breaks down complex requests and routes subtasks to specialist agents. I built a modular tool library so those agents can gather evidence and work through each step using ReAct.

`LangGraph` · `ReAct` · `Python` · `Tool calling`

### 02 / Hybrid knowledge retrieval

**Built a hybrid RAG pipeline around a practical trade-off:** keyword search finds exact terms, while vector search finds alternate phrasings. I combined BM25 with pgvector on Neon and added a gte reranker to select the passages that reach the model.

`BM25` · `Neon Postgres` · `pgvector` · `gte-reranker`

### 03 / Mobile AR English Tutor

**Turned real-world scenes into conversation practice.** For my research at Universiti Malaya, I built a Unity app that combines scene context and learner input to generate dialogue and deliver it as text and speech. A café scene, for example, becomes practice for ordering a drink.

`Unity` · `AR Foundation` · `LLM dialogue` · `Text-to-speech`

## Public code & research

- [AI-Agent](https://github.com/meiyingg/AI-Agent) — TypeScript agent repository
- [Medical VQA study](https://github.com/meiyingg/From-Classification-to-Generation-A-Comparative-Study-of-Med-VQA-Models) — comparison of classification and generative approaches to medical visual question answering
- [AR Group Assignment](https://github.com/meiyingg/AR-Group-Assignment) — C++ augmented reality coursework

<sub>Typing animation by <a href="https://github.com/DenverCoder1/readme-typing-svg">Readme Typing SVG</a>.</sub>
