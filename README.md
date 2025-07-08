# Detecção Automatizada de Negociações de Substâncias Ilı́citas em Mensagens de WhatsApp

Este repositório contém os materiais da apresentação do projeto para disciplina de Processamento de Linguagem Naural, intitulada "Detecção Automatizada de Negociações de Substâncias Ilı́citas em
Mensagens de WhatsApp", que aborda o desenvolvimento de um modelo de Processamento de Linguagem Natural (PLN) para a detecção automatizada de negociações de substâncias ilícitas em mensagens de WhatsApp.

## 🎥 Apresentação em Vídeo

Assista à gravação completa da apresentação para uma compreensão detalhada do projeto:

## 📄 Slides da Apresentação

Os slides utilizados na apresentação estão disponíveis em formato PDF. Eles contêm a estrutura, os objetivos, a metodologia e os resultados preliminares da pesquisa.


## 🎯 Objetivo do Projeto

O objetivo principal deste trabalho é desenvolver um modelo de Processamento de Linguagem Natural capaz de identificar automaticamente padrões de negociação presentes em mensagens de WhatsApp associadas ao comércio de substâncias ilícitas.

## 💡 Hipóteses de Pesquisa

1.  **H1 - Termos Indicativos:** Mensagens que apresentam combinações de termos relacionados a transações financeiras e logísticas são mais frequentemente classificadas como negociações.
2.  **H2 - Padrão Linguístico:** O uso de linguagem cifrada ou gírias específicas aumenta a probabilidade de uma mensagem estar relacionada à negociação de substâncias ilícitas.

## ❓ Perguntas de Pesquisa

1.  **RQ1:** Quais características linguísticas são mais indicativas de mensagens relacionadas à negociação de substâncias ilícitas no WhatsApp?
2.  **RQ2:** Como diferentes técnicas de vetorização (TF-IDF, Word2Vec, BERT) se comparam na detecção de negociações?
3.  **RQ3:** É possível identificar diferentes tipos de negociação (preço, prazo, condições)?

## 🛠️ Metodologia

A metodologia proposta envolve as seguintes etapas:

1.  **Coleta e Pré-processamento de Dados:** Exportação e limpeza de conversas do WhatsApp.
2.  **Anotação e Rotulação:** Classificação manual de mensagens para treinamento.
3.  **Extração de Features:** Análise de características linguísticas (N-grams, POS tags, entidades nomeadas) e semânticas (embeddings).
4.  **Modelagem:** Implementação de modelos de classificação, incluindo:
    *   **Baseline:** TF-IDF + SVM/Random Forest
    *   **Word2Vec:** + Redes Neurais
    *   **BERT:** Fine-tuning para classificação
    *   **Ensemble:** Combinação de modelos
5.  **Avaliação:** Utilização de métricas como Coherence Score, Curva ROC e AUC, Acurácia, Precisão, Recall e F1-Score.
6.  **Análise dos Resultados:** Estudo de features importantes, casos específicos e análise de erros.

