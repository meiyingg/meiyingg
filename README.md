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

I build **tool-using agents and retrieval systems** for tasks that need more than one LLM call. My research at **Universiti Malaya** explores how scene-aware AR can support spoken English practice.

## Selected systems

### 01 / Multi-agent decision support

Built a LangGraph supervisor to split requests into subtasks and route them to specialist agents. Each specialist uses ReAct-style tool calls to gather evidence for its part of the task.

`LangGraph` · `ReAct` · `Python` · `Tool calling`

### 02 / Hybrid knowledge retrieval

Combined **BM25** for exact keyword matches with **pgvector** for semantic matches. A **gte reranker** reorders the candidates before the strongest passages are passed to the LLM.

`BM25` · `Neon Postgres` · `pgvector` · `gte-reranker`

### 03 / Mobile AR English Tutor

Developed a Unity research app that uses the learner’s surroundings and input to create spoken practice scenarios. For example, the app can use the café scene as context for a conversation about ordering a drink. The app presents the dialogue as text and speech.

`Unity` · `AR Foundation` · `LLM dialogue` · `Text-to-speech`

## Public code & research

- [AI-Agent](https://github.com/meiyingg/AI-Agent) — TypeScript agent repository
- [Medical VQA study](https://github.com/meiyingg/From-Classification-to-Generation-A-Comparative-Study-of-Med-VQA-Models) — comparison of classification and generative approaches to medical visual question answering
- [AR Group Assignment](https://github.com/meiyingg/AR-Group-Assignment) — C++ augmented reality coursework

<sub>Typing animation by <a href="https://github.com/DenverCoder1/readme-typing-svg">Readme Typing SVG</a>.</sub>
