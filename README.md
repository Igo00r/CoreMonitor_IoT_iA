# 🌐 CoreMonitor

### 🧩 Projeto Integrador – Disruptive Architectures: IoT, IoB & Generative IA  
**FIAP | 3º Semestre – Análise e Desenvolvimento de Sistemas**

---

## 📖 Visão Geral

O **CoreMonitor** é uma plataforma **contábil-financeira integrada com IoT**, desenvolvida para centralizar dados operacionais e financeiros em um único ambiente inteligente.  
A proposta do sistema é permitir o monitoramento de eventos gerados por dispositivos conectados, o registro de informações contábeis e financeiras e a consolidação desses dados em dashboards e relatórios estratégicos.

A solução combina **IoT, banco de dados Oracle, Oracle APEX, APIs REST, microsserviços em .NET, Docker e aplicação mobile em React Native**, formando uma arquitetura moderna e escalável voltada ao apoio à tomada de decisão.

---

## 🎯 Objetivo do Projeto

O objetivo do **CoreMonitor** é transformar dados operacionais e financeiros em **informações estratégicas**, promovendo:
- maior visibilidade sobre custos, vendas e lançamentos contábeis;
- integração entre eventos IoT e indicadores financeiros;
- apoio à análise gerencial por meio de dashboards e relatórios;
- uso de **Inteligência Artificial** para previsão de custos operacionais e suporte analítico.

---

## ⚙️ Arquitetura da Solução

O projeto foi estruturado a partir dos seguintes componentes:

- **Oracle Database** para persistência de dados;
- **Oracle APEX** para dashboards, relatórios e visualização analítica;
- **Microsserviços em .NET + Docker** para processamento e exposição de APIs;
- **React Native** para experiência mobile;
- **Node-RED + MQTT** para simulação e integração de eventos IoT;
- **Módulo de IA** com abordagem preditiva para apoio à análise de custos operacionais.

---

## 🚀 Funcionalidades do Protótipo

✅ Integração IoT simulada com **Node-RED** e **MQTT**  
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
O sistema busca reduzir a dificuldade de interpretar, de forma preditiva, como eventos operacionais influenciam os custos e resultados financeiros da empresa.

### Modelo escolhido
Foi adotada a abordagem de **Machine Learning supervisionado com regressão**, pois o problema envolve a estimativa de valores numéricos, como tendências de custo operacional e impactos financeiros.

### Dados utilizados
A IA utiliza dados provenientes do **Oracle Database**, incluindo:
- lançamentos contábeis;
- vendas;
- centros de custo;
- serviços;
- eventos IoT integrados por **Node-RED** e **MQTT**.

### Integração com o sistema
O fluxo proposto ocorre da seguinte forma:

**Usuário → Oracle APEX → Oracle Database → Módulo de IA → Resultado analítico → Oracle APEX**

Dessa forma, o usuário pode acionar funcionalidades analíticas no APEX e receber previsões ou indicadores estratégicos gerados pela IA.

---

## 🔄 Fluxo resumido do sistema

1. Eventos IoT são simulados e enviados via **MQTT / Node-RED**  
2. Os dados operacionais são armazenados no **Oracle Database**  
3. O sistema consolida informações financeiras e contábeis  
4. O **Oracle APEX** apresenta dashboards e relatórios  
5. O módulo de **IA** processa os dados históricos  
6. O usuário visualiza previsões e análises no sistema

---

## 🛠️ Tecnologias Utilizadas

- **Oracle Database**
- **Oracle APEX**
- **.NET**
- **Docker**
- **React Native**
- **Node-RED**
- **MQTT**
- **Machine Learning / IA preditiva**
- **API REST**

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
👉 **[INSERIR LINK DO VÍDEO PITCH AQUI]**

> O vídeo apresentará a ideia central do CoreMonitor, a integração entre IoT, Oracle APEX e banco de dados, além da proposta de Inteligência Artificial aplicada à previsão de custos operacionais.

---

## 📹 Demonstração do Projeto

🎥 **Apresentação anterior / demonstração funcional:**  
👉 [https://youtu.be/qjO4meaf5LY](https://youtu.be/qjO4meaf5LY)

Este vídeo demonstra a evolução do projeto, o funcionamento do protótipo e as integrações já implementadas.

---

## 👥 Equipe do Projeto

| Nome | RM |
|------|----|
| **Igor Neris Soares Alves** | RM560088 |
| **Guilherme Jun Conheci** | RM559986 |

---

## 🏁 Considerações Finais

O **CoreMonitor** representa uma proposta de solução que integra **Contabilidade, IoT, Inteligência Artificial e Cloud Computing** em uma arquitetura unificada.  
Seu diferencial está em transformar dados operacionais e financeiros em **informações analíticas e estratégicas**, ampliando o potencial do sistema para monitoramento, gestão e apoio à decisão.

---
