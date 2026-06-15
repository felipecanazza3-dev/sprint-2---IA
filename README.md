

# Chatbot GoodWe AI - EV Challenge 2026

Repositório desenvolvido para a entrega da **Sprint 2** da disciplina de **Prompt and Artificial Intelligence** na FIAP. Este projeto consiste em um chatbot inteligente focado nas soluções de mobilidade elétrica da GoodWe, utilizando modelos de linguagem locais via **Ollama**.

##  Escopo do Projeto
O assistente virtual foi blindado e otimizado através de técnicas avançadas de engenharia de prompt para atuar exclusivamente sobre duas soluções estratégicas da GoodWe:
1. **ChargeGrid Intelligence:** Ecossistema de carregamento inteligente para Veículos Elétricos (EV) integrado com inversores solares, gerenciando dinamicamente fontes de energia e modos de carregamento (*PV Priority, Fast, PV+Battery*).
2. **EV ChargeOps:** Plataforma operacional voltada para o gerenciamento de frotas de carregadores, controle de demanda, faturamento e monitoramento em tempo real de estações de recarga.

---

##  Pré-requisitos e Dependências

Para executar este projeto localmente, você precisará ter o Python instalado e o ecossistema do **Ollama** configurado na sua máquina.

### 1. Instalação do Ollama
1. Baixe e instale o aplicativo de acordo com o seu sistema operacional em [ollama.com](https://ollama.com).
2. Certifique-se de que o Ollama está rodando (verifique o ícone da Lhama na barra de tarefas).

### 2. Download do Modelo de Linguagem
Abra o seu terminal (CMD, PowerShell ou terminal do VS Code) e baixe o modelo padrão utilizado no código:
```bash
ollama run llama3
