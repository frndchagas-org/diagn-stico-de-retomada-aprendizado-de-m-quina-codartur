[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/ARkoM8Jo)
# Diagnóstico de retomada - Aprendizado de Máquina

Esta atividade serve para mapear o que você já domina em Aprendizado de Máquina depois das atividades anteriores da disciplina.

Responda individualmente. Use suas palavras. Rode o código quando possível. Se usar IA depois da primeira tentativa, registre o uso na seção 8.

Prazo: 11/05/2026 às 23:59, horário de Fortaleza.

## 1. Mapa do que eu lembro

Marque cada tópico como: lembro bem, lembro parcialmente, não lembro, nunca vi ou não tenho certeza.

- vetores, matrizes e produto escalar: **lembro parcialmente**
- média, desvio padrão e correlação: **lembro parcialmente**
- probabilidade condicional e Teorema de Bayes: **lembro parcialmente**
- regressão linear: **lembro parcialmente**
- classificação supervisionada: **não tenho certeza**
- treino, teste e validação: **lembro bem**
- normalização ou padronização de dados: **lembro parcialmente**
- KNN: **não lembro**
- árvore de decisão: **lembro parcialmente**
- matriz de confusão: **lembro parcialmente**
- acurácia, precisão, recall e F1-score: **lembro parcialmente**
- overfitting e underfitting: **lembro bem**
- validação cruzada: **lembro parcialmente**
- Random Forest: **lembro parcialmente**
- XGBoost ou boosting: **lembro parcialmente**
- `predict_proba()`: **lembro parcialmente**
- SQL/ETL aplicado a dados: **lembro parcialmente**
- simulação de Monte Carlo: **lembro parcialmente**

## 2. O que foi trabalhado antes

Explique, em 8 a 12 linhas:

1. quais desses tópicos você lembra de ter trabalhado na disciplina;

> Todos estes tópicos foram trabalhados, porém a sensação que tenho é que foram trabalhados em graus diferentes. Levando em conta a sensação de aprendizado que tive, e associando ao modelo Aula + Estudos dirigidos, classifiquei desta forma:

Sensação de ter sido bem trabalhado nas atividades:
(Aqui, entender que muitas demandaram dos alunos estudos e pesquisas para entender e escrever sobre, e a sensação é de ter visto "mais sobre")
- vetores, matrizes e produto escalar
- média, desvio padrão e correlação
- probabilidade condicional e Teorema de Bayes
- acurácia, precisão, recall e F1-score
- overfitting e underfitting
- KNN

Sensação de ter sido trabalhado superficialmente nas atividades:
(Buscando na memória, acredito que estes temas não requereram explicação teórica por parte dos alunos, mas sim aplicação prática direta em uma atividade, produzindo  uma sensação de conhecimento "menos consolidado" do que os citados anteriormente).
- validação cruzada
- Random Forest
- XGBoost ou boosting
- SQL/ETL aplicado a dados
- simulação de Monte Carlo
- `predict_proba()`
- matriz de confusão

Sensação de ter sido trabalhado bem durante as aulas e atividades:
(Foram temas recorrentes em pelo menos duas aulas, além de duas atividades — uma delas não está no compêndio que enviei ao senhor pelo fato de ter sido uma atividade em sala (a única) — portanto acredito terem sido os temas mais bem cobertos da lista).
- regressão linear
- treino, teste e validação

Sensação de ter sido trabalhado superficialmente durante as aulas:
(Foram temas apresentados e discorridos superficialmente em uma única aula, portanto acredito que não tiveram grande absorção pela turma)
Obs: Confesso que não estive presente nesta aula específica, porém me informei com outros colegas.
- classificação supervisionada
- normalização ou padronização de dados (tocamos nesse ponto em alguns outros momentos em outras aulas, mas se me recordo bem, nada muito técnico, e sim o fato de ser necessário para a criação de bons modelos).
- árvore de decisão

2. quais atividades ou exemplos você lembra;
Acredito que a resposta da pergunta 1 também responde a esta.

3. o que você conseguiu fazer com autonomia;
Os diversos tópicos no estilo "Referencial Teórico" demandados nas atividades para serem pesquisados e descorridos foram de grande ajuda para compreender certos temas. É claro que, pelo fato de serem atividades em grupo, nem todos os tópicos foram estudados com o mesmo afinco por mim (a saber, os que foram desenvolvidos por meus colegas). Ainda assim, estes me forçaram entender mais alguns temas.

A parte de implementação das atividades já não foi tão autônoma. Uma contextualização rápida: em se tratando de implementações e programação com uso de modelos de IA, tivemos alguns exemplos na disciplina de IA no período anterior (disciplina esta em que, ao meu ver, se teve pouco aproveitamento), e também alguns materiais (livros) fornecidos pelo professor já dessa disciplina de Aprendizado de Máquina: um específico sobre a linguagem Python e outros sobre Machine Learning com alguns snippets em Python,

Dito isso, não me achei suficientemente seguro para conseguir realizar as atividades que envolviam implementação sozinho, por isso contei com a ajuda da IA, da seguinte forma: Entendia o que havia sido solicitado na atividade, implementava o código com IA, estudava o código linha a linha tentando compreender tanto a sintaxe quanto a lógica, fazia testes, e por fim correções. 

4. o que você só conseguiu fazer seguindo roteiro;
Complementando o que já relatei na pergunta anterior, a última atividade em específico (atividade 6) foi um verdadeiro desafio, pois muitos tópicos cobrados eram novos, então havia a dificuldade maior de primeiro compreender os conceitos para depois entender como eram implementados estes conceitos dentro do código. Utilizei IA extensivamente e mesmo assim foi muito difícil entender tudo, mesmo depois de apresentar o trabalho em sala.

5. qual assunto precisa ser retomado com mais urgência.
Uma sugestão: retomar a partir de Classificação (Regressão Logística, KNN, Árvores, etc). Acredito que seja o passo ideal depois de termos visto Regressão Linear.

## 3. Conceitos essenciais

Responda com suas palavras e dê um exemplo simples.

1. O que é aprendizado supervisionado? Aprendizado que conta com rótulos ou "respostas".
2. O que é uma tarefa de classificação? Uma tarefa que busca separar em grupos determinado conjunto de dados baseado em características ou features.
3. O que são features e target? Features são características que os dados podem ter. Target são features que se deseja prever.
4. Para que serve separar treino e teste? Para não enviesar o modelo com informações que ele já viu. Não teríamos resultados fidedignos ou realmente "às cegas" se utilizássemos os dados do teste no treinamento.
5. O que é overfitting? Quando o modelo aprendeu "demais" a base de dados utilizada no treinamento. Ou seja, ele praticamente decorou o dataset e não consegue generalizar ou "ver além" daquele conjunto de informações. Basicamente não funciona com informações novas que não tenha visto antes.
6. Por que acurácia pode ser uma métrica enganosa? Eu tinha uma noção do porquê há algumas semanas atrás, mas não me recordo mais.

## 4. Diagnóstico prático com Scikit-Learn

No arquivo `diagnostico_ml.py`, use o dataset `load_breast_cancer` do Scikit-Learn e faça:

1. carregue os dados;
2. separe `X` e `y`;
3. divida em treino e teste;
4. treine uma regressão logística;
5. treine uma árvore de decisão;
6. mostre matriz de confusão, acurácia, precisão, recall e F1-score para cada modelo;
7. compare o desempenho em treino e teste;
8. escreva aqui qual modelo generalizou melhor e por quê.

Se não conseguir terminar tudo, registre até onde chegou e qual erro apareceu.

### Resultados

Cole aqui os principais resultados do seu código.

```text

```

### Interpretação

Qual modelo generalizou melhor? Explique usando as métricas e a comparação entre treino e teste.

Resposta:

## 5. Probabilidade e interpretação

Escolha um dos modelos treinados e responda:

1. O modelo produz probabilidade com `predict_proba()`?
2. O que significa uma probabilidade alta para uma classe?
3. Probabilidade alta garante que a previsão está correta? Explique.
4. Em um problema real, qual seria o risco de confiar cegamente nessa previsão?

Resposta:

## 6. Generalização

Compare treino e teste:

1. Há sinal de overfitting?
2. Há sinal de underfitting?
3. O que você tentaria mudar para melhorar o resultado?
4. O que você precisaria estudar melhor para responder com mais segurança?

Resposta:

## 7. Ponto de dificuldade

Escolha um tópico da lista inicial e escreva:

1. o que você entende dele;
2. onde você se confunde;
3. que tipo de explicação ajudaria: exemplo no quadro, notebook guiado, exercício curto, revisão matemática, visualização ou projeto pequeno.

Resposta:

## 8. Uso de IA, se houver

Se você usou IA depois da primeira tentativa, registre:

```text
Pergunta feita:
Resumo da resposta:
Como eu verifiquei:
O que eu alterei na minha resposta:
O que ainda não entendi:
```

## Submissão no Moodle

Depois de finalizar, copie no Moodle:

```text
Repositório:
Commit final:
Autoavaliação: nível atual, maior dificuldade e tópico que precisa ser retomado.
```
