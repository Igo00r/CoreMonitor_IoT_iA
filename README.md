# 🧩 CoreMonitor

### Projeto Integrador – Disruptive Architectures: IoT, IoB & Generative IA  
**FIAP | 3º Semestre – Análise e Desenvolvimento de Sistemas**

---

## 📖 Visão Geral

O **CoreMonitor** é uma plataforma contábil-financeira integrada com IoT, desenvolvida para centralizar dados operacionais e financeiros em um único ambiente inteligente.  
A proposta do sistema é permitir o monitoramento de eventos gerados por dispositivos conectados, o registro de informações contábeis e financeiras e a consolidação desses dados em dashboards e relatórios estratégicos.

A solução combina **IoT, banco de dados Oracle, Oracle APEX, APIs REST, microsserviços em .NET, Docker e aplicação mobile em React Native**, formando uma arquitetura moderna e escalável voltada ao apoio à tomada de decisão.

---

## 🎯 Objetivo do Projeto

O objetivo do **CoreMonitor** é transformar dados operacionais e financeiros em informações estratégicas, promovendo:

- maior visibilidade sobre custos, vendas e lançamentos contábeis;
- integração entre eventos IoT e indicadores financeiros;
- apoio à análise gerencial por meio de dashboards e relatórios;
- uso de Inteligência Artificial para previsão de custos operacionais e suporte analítico.

---

## ⚙️ Arquitetura da Solução

O projeto foi estruturado a partir dos seguintes componentes:

- **Oracle Database** para persistência de dados;
- **Oracle APEX** para dashboards, relatórios e visualização analítica;
- **Microsserviços em .NET + Docker** para processamento e exposição de APIs;
- **React Native** para experiência mobile;
- **Node-RED + MQTT** para simulação e integração de eventos IoT;
- **Módulo de IA preditiva** para apoio à análise de custos operacionais.

---

## 🚀 Funcionalidades do Protótipo

✅ Integração IoT simulada com **Node-RED e MQTT**  
✅ Visualização de dados IoT em **dashboards Oracle APEX**  
✅ Cadastro e gerenciamento de **lançamentos contábeis e financeiros**  
✅ Consumo de dados de API externa para simulação operacional  
✅ Geração de **relatórios consolidados**  
✅ Protótipo mobile em **React Native** integrado à API  
✅ Estrutura conceitual de **IA para previsão de custos operacionais**

---

## 🤖 Componente de Inteligência Artificial

O componente de IA do **CoreMonitor** foi definido com o objetivo de **prever custos operacionais** e apoiar a análise de impacto financeiro a partir da correlação entre dados contábeis e eventos IoT.

### Problema de IA

O sistema busca reduzir a dificuldade de interpretar, de forma preditiva, como eventos operacionais influenciam os custos e os resultados financeiros da empresa.  
Na prática, a proposta é transformar dados históricos do sistema em previsões que apoiem a tomada de decisão gerencial.

### Tipo de IA adotado

Foi adotada a abordagem de **Machine Learning supervisionado com regressão**.

Essa escolha foi feita porque o problema tratado pelo CoreMonitor envolve a **estimativa de valores numéricos**, como:
- custo operacional previsto;
- tendência de gasto por período;
- impacto financeiro associado a eventos operacionais.

Diferentemente de modelos voltados a imagem ou linguagem natural, a regressão supervisionada é mais adequada para cenários em que o objetivo é **prever valores financeiros com base em dados históricos estruturados**.

### Como a IA atua na solução

A IA atua como uma camada analítica complementar ao sistema principal.  
Enquanto a aplicação realiza o cadastro e a consolidação dos dados contábeis, financeiros e operacionais, o módulo de IA utiliza esse histórico para gerar previsões e indicadores estratégicos.

Seu papel dentro da solução é:
- analisar padrões históricos de custo;
- relacionar dados financeiros com dados operacionais;
- prever tendências de custo operacional;
- apoiar relatórios e dashboards analíticos apresentados ao usuário.

### Dados processados pela IA

A IA utiliza dados provenientes do **Oracle Database**, alimentados pelas camadas transacionais e operacionais do sistema.

Entre os principais dados processados estão:

- lançamentos contábeis;
- vendas;
- centros de custo;
- contas contábeis;
- serviços;
- registros financeiros históricos;
- eventos IoT integrados por **Node-RED** e **MQTT**.

### Formato e origem dos dados

Os dados processados pelo modelo possuem origem estruturada, armazenados em tabelas do **Oracle Database**, e podem incluir:

- atributos numéricos, como valores de compra, venda e custo;
- atributos categóricos, como tipo de conta contábil e centro de custo;
- atributos temporais, como data e hora do evento;
- atributos operacionais, como identificação de dispositivos e registros IoT.

### Fluxo da IA no sistema

O funcionamento da IA no CoreMonitor ocorre em etapas:

1. O usuário registra informações financeiras e contábeis no sistema;
2. Eventos operacionais podem ser simulados e enviados via **MQTT / Node-RED**;
3. Os dados são persistidos no **Oracle Database**;
4. O módulo de IA consulta os dados históricos armazenados;
5. O modelo de regressão processa essas informações para identificar padrões;
6. O sistema gera uma previsão de custo operacional ou impacto financeiro;
7. O resultado é retornado ao **Oracle APEX**;
8. O usuário visualiza o resultado em dashboards, relatórios ou indicadores analíticos.

### Entrada, processamento e saída

#### Entrada
A entrada da IA é composta por dados históricos financeiros e operacionais, incluindo registros contábeis, contas, centros de custo, vendas e eventos IoT.

#### Processamento
Durante o processamento, o modelo supervisionado de regressão analisa a relação entre essas variáveis para identificar padrões de comportamento financeiro e operacional.

#### Saída
Como saída, a IA produz:
- previsão de custo operacional;
- estimativa de impacto financeiro;
- suporte analítico para dashboards e relatórios gerenciais.

### Integração com o sistema

O fluxo de integração pode ser resumido da seguinte forma:

**Usuário → Oracle APEX → Oracle Database → Módulo de IA → Resultado analítico → Oracle APEX**

Dessa forma, o usuário pode acionar funcionalidades analíticas no APEX e receber previsões ou indicadores estratégicos gerados pela IA.

---

## 🔄 Fluxo resumido do sistema

- Eventos IoT são simulados e enviados via **MQTT / Node-RED**;
- Os dados operacionais são armazenados no **Oracle Database**;
- O sistema consolida informações financeiras e contábeis;
- O **Oracle APEX** apresenta dashboards e relatórios;
- O módulo de IA processa os dados históricos;
- O usuário visualiza previsões e análises no sistema.

---

## 🛠️ Tecnologias Utilizadas

- Oracle Database
- Oracle APEX
- .NET
- Docker
- React Native
- Node-RED
- MQTT
- Machine Learning / IA preditiva
- API REST

---

## 📂 Estrutura do Projeto

Este repositório reúne os principais artefatos do projeto, incluindo:

- documentação técnica e acadêmica;
- scripts e estrutura de banco de dados;
- definição da arquitetura da solução;
- materiais de apoio da aplicação;
- organização do componente de IA e sua integração com o Oracle APEX.

---

## 📹 Vídeo Pitch

🎥 **Vídeo pitch do projeto:**  
👉 https://youtu.be/9DPN7liI8rU

O vídeo apresenta a ideia central do CoreMonitor, a integração entre IoT, Oracle APEX e banco de dados, além da proposta de Inteligência Artificial aplicada à previsão de custos operacionais.

---

## 📹 Demonstração do Projeto

🎥 **Apresentação anterior / demonstração funcional:**  
👉 https://youtu.be/qjO4meaf5LY

Este vídeo demonstra a evolução do projeto, o funcionamento do protótipo e as integrações já implementadas.

---

## 👥 Equipe do Projeto

| Nome | RM |
|------|----|
| Igor Neris Soares Alves | RM560088 |
| Guilherme Jun Conheci | RM559986 |

---

## 🏁 Considerações Finais

O **CoreMonitor** representa uma proposta de solução que integra **Contabilidade, IoT, Inteligência Artificial e Cloud Computing** em uma arquitetura unificada.

Seu diferencial está em transformar dados operacionais e financeiros em informações analíticas e estratégicas, ampliando o potencial do sistema para monitoramento, gestão e apoio à decisão.

Além disso, a definição mais detalhada do componente de IA demonstra que a solução não se limita à coleta e visualização de dados, mas evolui para uma abordagem preditiva, capaz de oferecer suporte analítico a partir do processamento estruturado de informações financeiras e operacionais.
