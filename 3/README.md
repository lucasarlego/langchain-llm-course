20. LangChain - Introdução
    * Principais Componentes:
        * Models: Interface padrão para integrções com ampla gama de LLMs.
        * Prompts: Ferramenta para simplificar a criação e tratamento de prompts dinâmicos.
        * Chains: Interface padrão para encadear LLMs em aplicações complexas, permitindo a ligação entre múltiplos modelos ou outros módulos especializados.
        * Memory: Módulos que permitem o gerenciamento e alteração de conversas anteriores, essencial para chatbots que precisam relembrar interações passadas para manter a coerência.
        * Agents: Equipados com um kit de ferramentas abrangente, podem escolher quais ferramentas usar com base nas informações do usuário.
        * Indexes: Métodos para organizar documentos (que contém dados proprietários, por exemplo) de forma a facilitar a interação eficaz com LLMs.
    * Ecossistema LangChain:
        - langchain-core: Abstrações básicas e LangChain Expression Language (LCEL).
        - langchain-community: Integrações de terceiros. Pacotes parceiros (por exemplo, langchain-openai, langchain-anthropic, etc.): Algumas integrações foram divididas em seus próprios pacotes leves que dependem apenas do langchain-core.
        - langchain: Chains, Agentes e Estratégias de Retrieval que compõem a arquitetura cognitiva de uma aplicação.
        - LangGraph: Para construir aplicações robustas e com estado para múltiplos atores com LLMs, modelando etapas como arestas e nós em um gráfico. Integra-se perfeitamente com LangChain, mas pode ser usado sem ele.
        - LangServe: Para implementar chains do LangChain como APIs REST.
        - LangSmith: Uma plataforma para desenvolvedores que permite depurar, testar, avaliar e monitorar aplicações LLM.
21. Instalação do LangChain
22. Modelos LangChain
23. Outros modelos OpenSource
24. Modelos de Chat
25. Prompt templates
26. Chains e funções customizadas
27. Streaming
28. Outros serviços para Modelos
29. Execução em máquina local
30. Execução local com Ollama