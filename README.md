# Bachelor's Thesis: When AIs Change Their Minds: Testing LLM Robustness to Altered Voting Protocols

**Abstract:**

Large-language-model (LLM) agents are highly assigned collective decision-making tasks; nevertheless, there is limited understanding of their proneness to influence when the voting mechanism or social context is altered. We study this vulnerability with two types of simulation experiments made on the current 10 different popular LLMs (10 agents per model). In the first stage, the stand-alone LLM approach stage, we test each LLM individually within an isolated voting environment where each model receives a topic prompt and responds with a one-word verdict: agree or disagree. Per-model agreement rates establish reference distributions. In the second type of experiment, we studied the degree-dependent influence of the network by creating a random network of 100 agents with mixed LLMs as their background. Agents are fed with their neighbours’ opinions and then perform the voting procedure. The goal is to examine how an increase in the network degree affects opinion formation in agents. We record per-agent vote-flip rates, group-level entropy, and Kullback-Leibler divergence from the baseline. The research presents the initial comprehensive proof that modifications to voting methods or network degree may significantly influence LLM-mediated collective decisions.


**Keywords:** Large Language Models, Voting Protocol, Social Influence, Opinion Dynamics, Multi-Agent Simulation



