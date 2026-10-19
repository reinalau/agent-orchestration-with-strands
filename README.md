![Python](https://img.shields.io/badge/Python-3.11+-3776AB?style=flat&logo=python&logoColor=white)
![Strands Agents](https://img.shields.io/badge/Strands_Agents-SDK-FF9900?style=flat&logo=amazonaws&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-Local_LLM-000000?style=flat&logo=ollama&logoColor=white)
![Gemma](https://img.shields.io/badge/Gemma-gemma4:e2b--it--qat-4285F4?style=flat&logo=google&logoColor=white)

# agent-orchestration-with-strands
Aquí reuno 5 proyectos sobre las diferentes maneras de orquestar agentes de IA con Strands con sus correspondientes artículos técnicos publicados.


| Descripción | GitHub | Artículo | Actualización |
| :--- | :--- | :--- | :--- |
| Ejemplo educativo del **patrón de orquestación Agents As Tools** del framework Strands Agents. Es un patrón jerárquico (hub-and-spoke) donde un orquestador delega tareas a agentes especializados. El caso de uso con el que se ejemplifica es la automatización del soporte básico de TI, ejecutado localmente con Ollama + gemma 4 | [Repo](https://github.com/reinalau/strands-agents-as-tools) | [Agents as Tools en Strands: orquestación jerárquica en local con Gemma 4 y Ollama](https://builder.aws.com/content/3GmRe87jkx3NhuN7t43nx1jW5se/agents-as-tools-en-strands-orquestacion-jerarquica-en-local-con-gemma-4-y-ollama) | 2026 |
|Ejemplo educativo del patrón de orquestación de agentes Graph del framework Strands Agents ➡ Un grafo es un sistema de orquestación de agentes basado en un grafo dirigido determinista, donde los agentes, los nodos personalizados u otros sistemas multiagente (como Swarm o grafos anidados) son nodos en un grafo |[Repo](https://github.com/reinalau/strands-graph) |[Graph en Strands: Parallel + Aggregation y Feedback Loop para construir Knowledge Graphs](https://builder.aws.com/content/3HbLH89H93R7rT8HSDN0HzKtMTj/graph-en-strands-parallel-aggregation-y-feedback-loop-para-construir-knowledge-graphs) |2026 |
|Ejemplo educativo del patrón de orquestación **Swarm** (Enjambre) del framework Strands Agents. Swarm es un patrón multi-agente donde no hay un orquestador central que decida el flujo: cada agente puede ver el trabajo de los agentes anteriores, y decide de forma autónoma cuándo transferir el control a otro agente. |[Repo](https://github.com/reinalau/strands-swarm) |[Swarm en Strands: orquestación autónoma mediante handoffs emergentes](https://builder.aws.com/content/3H6Gn1rh6Ke5Rrxu1NNL5btj1yJ/swarm-en-strands-orquestacion-autonoma-mediante-handoffs-emergentes) |2026 |
|Este es un ejemplo educativo del patrón de orquestación de **Agent Workflow** del framework Strands Agents. El Workflow tool es una herramienta de orquestación basada en **tareas con dependencias explícitas y resolución automática**, un grafo de tareas acíclico. |[Repo](https://github.com/reinalau/strands-workflow) |[Workflow en Strands: un DAG de tareas ejecutado como herramienta única](https://builder.aws.com/content/3Hv0A1JrHbwfgzEktts2k0Z1FeO/workflow-en-strands-un-dag-de-tareas-ejecutado-como-herramienta-unica) |2026 |
|Proyecto educativo sobre Agent-to-Agent (A2A) en Strands. Se presentan 2 casos de uso de agentes remotos con routing determinístico y discovery dinámico. |[Repo](https://github.com/reinalau/strands-a2a-patterns) |[A2A en Strands: agentes remotos con routing determinístico y discovery dinámico]([A2A en Strands: agentes remotos con routing determinístico y discovery dinámico](https://builder.aws.com/content/3IEOXhwX9PxCQwxhggtL5jsD1WJ/a2a-en-strands-agentes-remotos-con-routing-deterministico-y-discovery-dinamico) | 2026|

## Referencias
[Strands SDK](https://strandsagents.com/docs/user-guide/sdk/)
