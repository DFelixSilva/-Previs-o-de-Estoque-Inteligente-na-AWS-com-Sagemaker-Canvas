# 📦 Previsão de Estoque Inteligente na AWS com SageMaker Canvas

## 📌 Descrição do Projeto
Projeto desenvolvido como parte do desafio da **Digital Innovation One (DIO)** utilizando o **Amazon SageMaker Canvas** para criação de um modelo de **Machine Learning no-code** voltado à previsão de estoque.

O objetivo é demonstrar, de forma prática, como a IA pode apoiar decisões estratégicas de estoque, reduzindo riscos de ruptura e excesso de inventário.

---

## 🎯 Objetivo
Criar um modelo preditivo capaz de estimar níveis futuros de estoque com base em dados históricos de vendas.

---

## 🧰 Tecnologias Utilizadas
- Amazon Web Services (AWS)
  - Amazon SageMaker Canvas
- Machine Learning no-code
- Git & GitHub

---

## 📁 Estrutura do Repositório
```bash
lab-aws-sagemaker-canvas-estoque/
│
├── datasets/
│   └── estoque_historico.csv
│
├── images/
│   └── (prints do SageMaker Canvas)
│
└── README.md
```

---

## 🚀 Etapas do Desenvolvimento

### 1️⃣ Seleção do Dataset
Foi utilizado um dataset histórico contendo informações de:
- Data
- Produto
- Vendas diárias
- Estoque atual

O arquivo foi carregado diretamente no SageMaker Canvas.

---

### 2️⃣ Construção e Treinamento
No SageMaker Canvas:
- Dataset importado
- Variável alvo configurada (estoque futuro)
- Treinamento realizado em modo automático

---

### 3️⃣ Análise
- Avaliação das métricas de desempenho
- Identificação das variáveis mais relevantes
- Validação da qualidade das previsões

---

### 4️⃣ Previsão
- Geração de previsões futuras de estoque
- Exportação dos resultados
- Análise estratégica para apoio à tomada de decisão

---

## 📊 Insights Obtidos
- Tendência de queda de estoque conforme aumento das vendas
- Importância do histórico de consumo para previsões confiáveis
- Viabilidade do uso de ML no-code em cenários reais

---

## 🏁 Conclusão
O projeto evidencia como o **Amazon SageMaker Canvas** permite a aplicação prática de Machine Learning de forma acessível, sendo uma excelente alternativa para profissionais de BI, Dados e áreas de negócio.

---

📌 Projeto desenvolvido para fins educacionais no Bootcamp DIO.
