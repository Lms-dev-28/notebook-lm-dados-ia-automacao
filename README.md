# 🧠 Segundo Cérebro: Dados, IA e Automação no RH & DP

**Notebook:** https://notebook.google.com/notebook/ed7e441a-de26-4141-9e3e-90206cd724de

> **Objetivo:** Dominar Python, SQL e IA Generativa para transformar dados operacionais em decisões estratégicas e automatizar processos repetitivos de Recursos Humanos (RH) e Departamento Pessoal (DP).

Este repositório documenta a base de conhecimento e as fontes de curadoria utilizadas no **NotebookLM** para criar um assistente especializado em automação e análise de dados aplicada a rotinas de gestão de pessoas.

---

## 🤖 Diretriz de Comportamento (System Prompt)

Ao interagir com o NotebookLM ou qualquer agente configurado com esta base, utilize a seguinte instrução:

> **Diretriz:**  
> *"Comporte-se como um especialista em dados, automação e Inteligência Artificial focado na melhoria de processos, conformidade legal e eficiência operacional no Departamento Pessoal (DP) e Recursos Humanos (RH)."*

---

## 📚 Fontes Curadas

### 🎥 Fontes em Vídeo

#### Referências Institucionais e Especialistas
* [Visão Geral da Trilha](https://youtu.be/zKBvE1EteJg?si=xw1SvwG0S5zq0IjJ)
* [Canal Oficial DIO](https://www.youtube.com/@dio_me) — Aulas abertas, mentorias e projetos práticos.
* [PyData TV](https://www.youtube.com/@PyDataTV) — Melhores práticas globais em manipulação e análise de dados com Python.
* [Google for Developers](https://www.youtube.com/@GoogleDevelopers) — Novidades e ferramentas de IA Generativa e ecossistema Gemini.

#### Casos de Uso e Estudos Práticos
* [Estudo de Caso 1](https://youtu.be/uwywvykf33w?si=hOV76KX9_jTxAri7)
* [Estudo de Caso 2](https://youtu.be/xU19RszBR6E?si=OoMLgR4j8hopXXDI)
* [Estudo de Caso 3](https://youtu.be/VA1TQMzsMdc?si=hm2KBF3DWwRsKAcL)
* [Estudo de Caso 4](https://youtu.be/u4gs6ja-rjQ?si=S2qGA_moLbFo4uf9)
* [Live Técnica: Aplicações Práticas](https://www.youtube.com/live/_55FXEutwqU?si=M7289td-0qTEwZ5c)
* [Estudo de Caso 5](https://youtu.be/1VDcke66TRE?si=zyEQZEUi2_VMWQXX)

---

### 📄 Fontes em Texto e Documentações Oficiais

* 🐍 [Tutorial Oficial do Python (pt-BR)](https://docs.python.org/pt-br/3/tutorial/) — Sintaxe, estruturas de dados e lógica.
* 🐼 [10 Minutes to pandas](https://pandas.pydata.org/docs/user_guide/10min.html) — Guia essencial de manipulação de tabelas e DataFrames.
* 🐘 [Tutorial Oficial do PostgreSQL](https://www.postgresql.org/docs/current/tutorial.html) — Consultas SQL, filtros, junções e agregações.
* ⚡ [Prompting Strategies (Google AI)](https://ai.google.dev/gemini-api/docs/prompting-strategies) — Engenharia de prompts e contextos para LLMs.
* 📰 [Artigos Técnicos da DIO](https://www.dio.me/articles) — Publicações da comunidade sobre tecnologia e mercado.
* 🌐 [Requests: HTTP for Humans](https://requests.readthedocs.io/) — Consumo e integração de APIs web em Python.
* 🗄️ [SQLite3 (Biblioteca Padrão)](https://docs.python.org/pt-br/3/library/sqlite3.html) — Armazenamento local e pipelines leves de dados.

---

## 💡 Base de Conhecimento

### 📌 Pergunta 1: De que maneira posso usar Python, IA e dados para melhorar processos dentro do departamento de RH e DP?

A combinação de **Python, Inteligência Artificial (IA) e Ciência de Dados** permite transformar os departamentos de Recursos Humanos (RH) e Departamento Pessoal (DP), evoluindo de tarefas manuais e operacionais para fluxos automatizados e análises estratégicas.

#### 1. Processamento Inteligente de Documentos (IDP) em Admissão e DP
O DP lida com um volume massivo de documentos físicos e digitais não estruturados (RG, CPF, comprovantes de residência, carteiras de trabalho e formulários de onboarding).
* **Pipeline OCR + LLM:** Utilização de bibliotecas Python integradas a motores de OCR e modelos de linguagem para extrair e validar dados automaticamente de documentos digitalizados.
* **Validação Semântica e Regras de Negócio:** O LLM interpreta o contexto dos dados extraídos e aplica regras automáticas para cruzamento com sistemas internos (ERP/HRIS).
* **Redução de Erros e Tempo:** Redução de até 90% dos erros manuais de digitação e aceleração da triagem de documentos em mais de 65%.

#### 2. Triagem e Classificação de Currículos (Recrutamento e Seleção)
A análise manual de centenas de currículos em formatos variados pode ser automatizada com inteligência semântica:
* **Extração Padronizada:** Classificação estruturada de experiência profissional, competências técnicas e formação acadêmica.
* **Análise Semântica:** Modelos de linguagem avaliam a compatibilidade do candidato com a descrição da vaga além da simples busca por palavras-chave.
* **Aviso de Governança e Regulação:** O uso de IA em recrutamento e seleção é classificado como de **alto risco** em marcos regulatórios internacionais (*EU AI Act* e ISO/IEC 42001). É fundamental garantir supervisão humana contínua (*Human-in-the-Loop*), transparência e auditoria periódica.

#### 3. Automação de Rotinas e Fluxos Operacionais com Python
Para conectar sistemas legados, planilhas e portais (eSocial, sistemas de benefícios):
* **RPA e Scripts Python:** Automação de tarefas repetitivas como cálculo de férias, validação de horas extras, conciliação de folha de pagamento e geração de relatórios periódicos.
* **Integração Corporativa:** Scripts em Python podem ser orquestrados via Microsoft Power Automate ou expostos via APIs (FastAPI/Flask) para automação agendada.

#### 4. Autoatendimento de Colaboradores com Agentes de IA e RAG
Dúvidas frequentes sobre holerites, políticas de benefícios, código de conduta ou férias consomem tempo valioso da equipe:
* **Assistentes de Conhecimento (RAG):** Arquiteturas de *Retrieval-Augmented Generation* com bancos vetoriais permitem criar assistentes que respondem dúvidas consultando diretamente os manuais e regulamentos internos da empresa.
* **Agentes de Ação:** Integração com canais corporativos (Teams, Slack ou WhatsApp) para abrir solicitações, enviar comprovantes e encaminhar exceções para análise humana.

#### 5. Analytics e Previsão de Indicadores de Pessoal (People Analytics)
* **Tratamento em Escala:** Com o `pandas`, o RH processa rapidamente históricos extensos de folha, ponto e avaliações de desempenho.
* **Modelos Preditivos de Turnover e Absenteísmo:** Algoritmos de aprendizado de máquina identificam padrões atípicos e antecipam riscos de desligamento involuntário ou faltas.
* **Dashboards Dinâmicos:** Dados tratados alimentam painéis em ferramentas de BI para acompanhamento executivo.

#### 6. Cuidados Éticos, Privacidade de Dados e Engenharia de Prompt
* **Anonimização Efetiva de PII:** Remover Nome e CPF não é suficiente; a combinação de cargo, salário e departamento pode permitir a reidentificação do colaborador.
* **Engenharia de Prompt Consciente:** Uso de personas delimitadas, exemplos (*few-shot*) e restrições explícitas contra alucinações.
* **Viés de Automação:** A IA deve atuar como copiloto. A responsabilidade decisória final cabe sempre ao profissional humano.

---

### 📌 Pergunta 2: Como garantir a conformidade com a LGPD ao usar IA no RH?

Garantir a conformidade com a LGPD e regulamentações de governança ao utilizar Inteligência Artificial no RH e DP exige estruturar os processos em torno de **privacidade, rastreabilidade e supervisão humana**:

#### 1. Minimização de Dados e Anonimização Efetiva de PII
* **Sanitização Prévia:** Antes de enviar documentos ou históricos para LLMs, é indispensável sanitizar informações de identificação pessoal (*PII*).
* **Cuidado com a Reidentificação:** Variáveis indiretas mantidas no texto (faixa salarial, setor, tempo de casa, localização) podem permitir reidentificar o colaborador.
* **Zero Persistence e Segurança:** Adoção de arquiteturas com controles rigorosos de acesso, criptografia e políticas de retenção nula (*Zero Persistence*), evitando que dados internos treinem modelos públicos na nuvem.

#### 2. Mapeamento de Ativos e Rastreabilidade Contínua (*Data Lineage*)
* **Inventário Vivo de Ativos:** Manter registro atualizado de todas as ferramentas, scripts, modelos e bots em uso no RH/DP.
* **Logs Imutáveis e Auditoria (LLMOps):** Sistema de registro (*System of Record*) com rastreamento distribuído que grave autor da consulta, dados de entrada, versão do prompt e saída gerada para auditorias.

#### 3. Supervisão Humana (*Human-in-the-Loop*) e Combate aos Vieses
* **Classificação de Alto Risco:** Aplicações de IA em recrutamento, promoção ou desligamento são consideradas de alto risco regulatório.
* **O Humano como Autoridade Decisória:** Nenhuma decisão rescisória, disciplinar ou remuneratória deve ser 100% autônoma. O julgamento crítico humano é indispensável para combater o viés de automação.
* **Mitigação de Vieses Preditivos:** Testes contínuos em bases históricas para evitar que a IA reproduza ou amplifique discriminações.

#### 4. Engenharia de Prompt Segura e Proteção contra *Prompt Injection*
* **Contexto Estrito e Ancoragem:** Prompts estruturados com delimitadores e regras para forçar a IA a responder estritamente com base nos documentos enviados, evitando confabulações.
* **Guardrails na Ingestão:** Filtros de entrada para neutralizar comandos maliciosos escondidos em currículos ou PDFs enviados por terceiros.

#### 5. Atribuição de Responsabilidade e Frameworks de Governança
* **AI System Owner:** Cada projeto de IA no DP deve ter um responsável formalmente designado para acompanhar o ciclo de vida e a conformidade do sistema.
* **Alinhamento a Normas Internacionais:** Adoção de frameworks como **ISO/IEC 42001** e **NIST AI RMF** para garantir governança documental, matrizes de risco e respaldo jurídico.
