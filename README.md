# Ferramentas de IA da Google para realizar code review


<img width="419" height="226" alt="image" src="https://github.com/user-attachments/assets/94a30912-42cc-4225-a951-54e6faba05f5" />


<img width="384" height="202" alt="image" src="https://github.com/user-attachments/assets/2cbb6e31-3d50-45f7-bdfc-6cca283ae4d2" />


<img width="418" height="228" alt="image" src="https://github.com/user-attachments/assets/06191c93-4ae7-4cdf-bf3e-daeaafbefa2f" />

🌐 Todo o Ecossistema da Google

<img width="419" alt="Ecossistema Google" src="https://github.com/user-attachments/assets/94a30912-42cc-4225-a951-54e6faba05f5" />

O ecossistema da Google é um conjunto interligado de plataformas, ferramentas, APIs e serviços que atuam em sinergia para criar um ambiente produtivo, inteligente e automatizado para usuários e empresas. A Google integra hardware, software e inteligência artificial de forma fluida, formando três grandes pilares:

---
Baseado num treinamento interno da empresa para aprofundamento de ferramentas de IA para apoiar code review

## 🧰 2. Ferramentas de Produtividade

- **Google Workspace (antigo G Suite):** inclui Gmail, Docs, Sheets, Drive, Meet, Calendar e outras ferramentas de colaboração.  
- **AppSheet:** criação de apps no-code com base em planilhas e dados.  
- **Google Chat + Spaces:** comunicação e organização de times.

---

## 🤖 3. Inteligência Artificial e Assistente

- **Google Assistant:** integra-se com a agenda, e-mails, documentos, apps de mensagens e muito mais, automatizando ações com base em voz ou texto.  
- **Vertex AI:** plataforma para treinar e implantar modelos de IA no GCP.  
- **PaLM / Gemini:** grandes modelos de linguagem usados em várias aplicações internas.

---

## 🔍 Detalhes: Integração e Automação Inteligente

<img width="384" alt="Detalhes do Ecossistema" src="https://github.com/user-attachments/assets/2cbb6e31-3d50-45f7-bdfc-6cca283ae4d2" />

A imagem acima aprofunda como os componentes se conectam:

- **Integrações nativas com Gmail e Drive:** permitem que a IA analise documentos, e-mails, reuniões agendadas e tarefas automaticamente.  
- **Assistente como central de comando:** a IA atua proativamente com sugestões, lembretes, automações e até mesmo geração de conteúdo com base no contexto do usuário.  
- **Ciclo fechado de produtividade:** os dados circulam entre e-mails, documentos, planilhas e IA, permitindo decisões mais rápidas e embasadas.

---

## 🤝 Code Review Usando Google Assistente

<img width="418" alt="Code Review com Google Assistente" src="https://github.com/user-attachments/assets/06191c93-4ae7-4cdf-bf3e-daeaafbefa2f" />

A imagem acima ilustra um uso avançado: **code review com suporte do Google Assistente**.

### Como funciona esse processo:

- **Conexão com o GitHub ou repositórios internos:**  
  O assistente acessa as PRs (pull requests), arquivos e histórico de commits.

- **Análise automatizada do código:**  
  Utiliza modelos de linguagem como PaLM/Gemini para verificar padrões, sugerir melhorias e apontar bugs.

- **Feedback via voz ou texto:**  
  Você pode perguntar: _“Esse código está seguindo o padrão da empresa?”_  
  O assistente responde com base nas práticas recomendadas, docs internos e histórico do projeto.

- **Ações automatizadas:**  
  _“Aprovar PR se todos os testes passarem”_ ou _“Solicitar revisão de segurança”_.

---

🧠 O que é Jules, da Google?
Jules é o codinome interno de um sistema de inteligência artificial da Google, voltado para assistência ao desenvolvedor, especialmente em tarefas como code review, geração de código, análise de pull requests, e suporte técnico automatizado.

🔍 Resumo funcional do Jules:
Função	Descrição
🤖 Assistente de revisão de código	Jules analisa PRs (Pull Requests), sugere melhorias e aponta problemas no código.
📚 Acesso a documentação interna	Ele entende os padrões de código da empresa, frameworks utilizados e pode referenciar documentos internos.
🗣️ Interação via linguagem natural	Você pode conversar com ele, por exemplo: "Esse código segue os padrões de acessibilidade?"
⚙️ Automação de tarefas repetitivas	Aprovar testes, aplicar refatorações simples, e sugerir snippets prontos.
🔐 Segurança e conformidade	Ajuda a identificar vulnerabilidades e violações de políticas internas.

🧬 Relação com outros produtos Google
O Jules está inserido dentro do ecossistema maior da Google, como mostrado em seu material, e se conecta com:

Google Assistant (interface de interação)

PaLM / Gemini (os modelos de linguagem)

Google Cloud e GitHub (infraestrutura e repositórios)

Bard (antigo nome) e Workspace AI (em versões mais amplas para produtividade)

No link e possível se inscrever e testar a ferramenta : https://codeassist.google/#available-in-your-terminal-favorite-ides-and-platforms

## 💡 Conclusão

O ecossistema da Google vai além de e-mails e buscas — ele permite uma **experiência inteligente, integrada e fluida**.  
O uso do Google Assistente como **copiloto de produtividade** ou até **revisor de código** mostra como a IA pode elevar o desempenho de equipes técnicas e operacionais.
✅ 




--- Dialog flow --------

<img width="650" height="221" alt="image" src="https://github.com/user-attachments/assets/43396c31-4f64-4ab1-a402-6be12b1039d8" />


# 🤖 Dialogflow vs Vertex AI Conversation (Agent Builder)

## 1. Dialogflow

O **Dialogflow** é uma plataforma do Google (antiga API.AI) usada para criar chatbots baseados em intenção, com foco em regras e *NLU* (Natural Language Understanding).

### 🛠️ Principais características:
- Usa **intents**, **entities** e **contexts** para entender o que o usuário quer.
- Pode ser integrado com **sites, aplicativos, WhatsApp, Messenger, Google Assistant**, entre outros.
- Disponível em duas versões:
  - **Dialogflow ES (Essentials)** → mais simples, baseado em intents.
  - **Dialogflow CX (Customer Experience)** → mais avançado, com fluxos visuais de conversa e gerenciamento de estado mais complexo.

### ✅ Bom para:
- Fluxos baseados em regras.
- Casos com muitas rotas de decisão previsíveis.
- Integrações com canais e backends estruturados.

---

## 2. Vertex AI Conversation (Agent Builder)

O **Vertex AI Conversation** é a evolução do Dialogflow, com integração direta ao **Vertex AI**, a plataforma de IA generativa do Google.

> Antigamente chamado de *Dialogflow CX com Vertex AI*, agora é voltado para assistentes inteligentes com IA generativa.

### 🚀 O que ele oferece:
- Criação de agentes com **IA generativa** usando **LLMs** como o **Gemini**.
- Respostas baseadas em **documentos, APIs ou bases de conhecimento**.
- Suporte a **funções (tools/functions)** para executar ações personalizadas com base nas intenções detectadas.
- Integração com:
  - **Vertex AI Search**
  - **PaLM/Gemini**
  - **Embeddings**
  - **RAG (retrieval-augmented generation)**

### ✅ Bom para:
- Casos **complexos e não estruturados**.
- Atendimento que exige **flexibilidade e respostas dinâmicas**.
- Assistentes que combinam **fluxos com IA generativa**.

---

## 🔍 Comparativo Rápido

| Característica | Dialogflow ES/CX | Vertex AI Conversation |
|----------------|------------------|-------------------------|
| Base de funcionamento | Intents, entidades e contextos | LLMs e IA generativa |
| Ideal para | Chatbots de fluxo fixo | Assistentes mais inteligentes |
| Customização | Por regras e intents | Por embeddings e modelos de IA |
| Suporte a IA generativa | Limitado | Completo (Gemini, RAG etc.) |
| Integração com dados não estruturados | Difícil ou não nativa | Nativo (PDFs, APIs, páginas etc.) |

---

## 📦 Exemplos de uso

- **Dialogflow CX** → Chatbot que ajuda o cidadão a agendar uma consulta médica no site do governo de Goiás.

- **Vertex AI Conversation** → Assistente inteligente que responde perguntas sobre políticas públicas, lendo PDFs ou bases de dados, e que também pode acionar APIs automaticamente se necessário.

## 📦 Avatares
https://genai.ffeldhaus.demo.altostrat.com/






---

### 📁 Repositório útil? Deixe uma estrela ⭐ e contribua!

---

