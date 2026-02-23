# Aula de Análise Preliminar e Exploratória de Dados
## Engenharia Biomédica - IPC

---

## 📚 Conteúdo do Material

Este material contém **4 notebooks Jupyter** para a disciplina de **Análise Inteligente de Dados**, focados em análise preliminar e exploratória de datasets biomédicos.

### Notebooks Disponíveis:

#### 1️⃣ **Diabetes Dataset** (`notebooks/01_Diabetes_Analise_Exploratoria.ipynb`)
- **Dataset:** Pima Indians Diabetes Database
- **Tipo:** Dados clínicos tabulares
- **Características:** 768 pacientes, 8 features clínicas
- **Foco:** Análise de qualidade de dados (zeros inválidos), correlações, comparação entre grupos
- **Nível:** Introdutório

#### 2️⃣ **Heart Disease Dataset** (`notebooks/02_Heart_Disease_Analise_Exploratoria.ipynb`)
- **Dataset:** Cleveland Heart Disease Database
- **Tipo:** Dados cardiovasculares mistos (numéricos + categóricos)
- **Características:** 303 pacientes, 13 features
- **Foco:** Análise de variáveis categóricas, relações multivariadas, fatores de risco
- **Nível:** Intermédio

#### 3️⃣ **Breast Cancer Dataset** (`notebooks/03_Breast_Cancer_Analise_Exploratoria.ipynb`)
- **Dataset:** Wisconsin Breast Cancer Database
- **Tipo:** Features extraídas de imagens médicas
- **Características:** 569 amostras, 30 features (MEAN, SE, WORST)
- **Foco:** Multicolinearidade, features derivadas, comparação MEAN vs WORST
- **Nível:** Avançado

#### 4️⃣ **Vital Signs Dataset** (`notebooks/04_Sinais_Vitais_Analise_Exploratoria.ipynb`)
- **Dataset:** Sinais vitais simulados (UCI)
- **Tipo:** Séries temporais de monitorização
- **Características:** 100 pacientes, 24h de monitorização, 6 sinais vitais
- **Foco:** Análise temporal, padrões circadianos, variabilidade, alertas
- **Nível:** Avançado

---

## 🎯 Objetivos Pedagógicos

### Análise Preliminar:
- ✅ Carregar e inspecionar dados
- ✅ Identificar tipos de dados
- ✅ Detetar valores em falta
- ✅ Identificar duplicados
- ✅ Calcular estatísticas descritivas
- ✅ Avaliar qualidade dos dados

### Análise Exploratória:
- 📊 Visualizar distribuições (histogramas, boxplots, violin plots)
- 📊 Analisar correlações entre variáveis
- 📊 Comparar grupos/categorias
- 📊 Identificar outliers
- 📊 Descobrir padrões e relações
- 📊 Criar visualizações informativas

---

## 🔧 Requisitos Técnicos

## 📁 Estrutura do Repositório

```text
.
├── README.md
└── notebooks/
   ├── 01_Diabetes_Analise_Exploratoria.ipynb
   ├── 02_Heart_Disease_Analise_Exploratoria.ipynb
   ├── 03_Breast_Cancer_Analise_Exploratoria.ipynb
   └── 04_Sinais_Vitais_Analise_Exploratoria.ipynb
```

### Bibliotecas Python Necessárias:
```python
pandas
numpy
matplotlib
seaborn
scipy
scikit-learn  # apenas para notebook 3
```

### Ambiente virtual (recomendado):
```bash
python -m venv .venv
```

Ativação no Windows (PowerShell):
```bash
.venv\Scripts\Activate.ps1
```

### Instalação (recomendado):
```bash
pip install -r requirements.txt
```

### Instalação (alternativa):
```bash
pip install pandas numpy matplotlib seaborn scipy scikit-learn
```

### Ambiente Recomendado:
- Python 3.8+
- Jupyter Notebook ou JupyterLab
- 4GB RAM mínimo

---

## 📖 Como Usar Este Material

### Para Professores:

1. **Sequência Sugerida:**
   - Notebook 1 (Diabetes) - Introdução
   - Notebook 2 (Heart Disease) - Variáveis categóricas
   - Notebook 3 (Breast Cancer) - Features complexas
   - Notebook 4 (Vital Signs) - Dados temporais

2. **Duração Estimada:**
   - Cada notebook: 2-3 horas (incluindo exercícios)
   - Total: 8-12 horas de conteúdo prático

3. **Adaptações Possíveis:**
   - Remover secções para aulas mais curtas
   - Adicionar exercícios práticos adicionais
   - Usar como base para projetos

### Para Estudantes:

1. **Execute célula por célula** - não execute tudo de uma vez
2. **Leia os comentários** - contêm informação importante
3. **Faça os exercícios** - marcados com ✏️
4. **Reflita nas questões** - marcadas com 🤔
5. **Experimente modificar o código** - aprenda fazendo

---

## 📊 Estrutura de Cada Notebook

### Parte I - Análise Preliminar
1. Importação de bibliotecas
2. Carregamento dos dados
3. Primeiras observações
4. Informações gerais
5. Valores em falta
6. Estatísticas descritivas
7. Duplicados

### Parte II - Análise Exploratória
8. Análise da variável alvo
9. Distribuições univariadas
10. Análise de outliers
11. Matriz de correlação
12. Análise bivariada
13. Comparações entre grupos
14. Análises específicas do dataset
15. Síntese e conclusões

---

## 💡 Diferenciais deste Material

✨ **Focado em Engenharia Biomédica:**
- Todos os datasets são biomédicos
- Interpretações clínicas incluídas
- Contexto médico relevante

📚 **Pedagógico:**
- Progressão gradual de dificuldade
- Exercícios intercalados
- Questões de reflexão
- Código comentado em português

🔍 **Completo:**
- Análise preliminar + exploratória
- Múltiplas técnicas de visualização
- Interpretação de resultados
- Síntese e conclusões

🎓 **Prático:**
- Código pronto a executar
- Datasets automaticamente carregados
- Sem necessidade de downloads manuais

---

## 🌟 Conceitos-Chave Abordados

### Gerais:
- Qualidade de dados
- Valores em falta e outliers
- Estatísticas descritivas
- Visualização de dados
- Correlação vs causalidade

### Por Dataset:
- **Diabetes:** Valores biologicamente inválidos, balanceamento
- **Heart Disease:** Variáveis categóricas, fatores de risco
- **Breast Cancer:** Multicolinearidade, features derivadas, escalas
- **Vital Signs:** Séries temporais, padrões circadianos, variabilidade

---

## 📝 Exercícios e Avaliação

Cada notebook contém:
- **3-4 exercícios principais** (marcados com ✏️)
- **4-6 questões de reflexão** (marcadas com 🤔)
- **1 exercício final integrador**

### Sugestões de Avaliação:
1. **Trabalho prático:** Executar e interpretar um notebook
2. **Relatório:** Síntese das descobertas de um dataset
3. **Projeto:** Aplicar as técnicas a um novo dataset
4. **Apresentação oral:** Explicar as visualizações criadas

---

## 🔗 Datasets Utilizados

### Fontes:
1. **Diabetes:** UCI ML Repository
2. **Heart Disease:** UCI ML Repository (Cleveland)
3. **Breast Cancer:** Scikit-learn / UCI ML Repository
4. **Vital Signs:** Simulado (código incluído)

### Notas sobre os Dados:
- Datasets 1-3: Dados reais, publicamente disponíveis
- Dataset 4: Simulado com parâmetros realistas
- Todos: Utilizados para fins educacionais

---

## 🚀 Próximos Passos Após Esta Aula

Após dominar a análise exploratória, os estudantes estarão preparados para:

1. **Pré-processamento de Dados:**
   - Normalização/padronização
   - Feature engineering
   - Tratamento de outliers
   - Imputação de valores em falta

2. **Modelação:**
   - Classificação
   - Regressão
   - Clustering
   - Redução de dimensionalidade (PCA)

3. **Validação:**
   - Train/test split
   - Cross-validation
   - Métricas de avaliação

---

## 📧 Contacto e Contribuições

**Professor:** [Seu Nome]  
**Instituição:** Instituto Politécnico de Coimbra - ISEC  
**Disciplina:** Análise Inteligente de Dados  
**Curso:** Licenciatura em Engenharia Biomédica

### Contribuições:
- Sugestões de melhorias são bem-vindas
- Reportar erros ou problemas
- Partilhar adaptações e extensões

---

## 📚 Referências Adicionais

### Livros Recomendados:
- "Python for Data Analysis" - Wes McKinney
- "Hands-On Machine Learning" - Aurélien Géron
- "Introduction to Statistical Learning" - James et al.

### Recursos Online:
- Pandas Documentation: https://pandas.pydata.org/
- Seaborn Gallery: https://seaborn.pydata.org/examples/
- Kaggle Learn: https://www.kaggle.com/learn

### Cursos Complementares:
- Exploratory Data Analysis (Coursera)
- Data Visualization with Python (edX)
- Applied Data Science with Python (Coursera)

---

## 📄 Licença

Este material é disponibilizado para fins educacionais. 

**Uso permitido:**
- ✅ Ensino em ambiente académico
- ✅ Estudo pessoal
- ✅ Modificação e adaptação (com atribuição)

**Uso não permitido:**
- ❌ Uso comercial
- ❌ Redistribuição sem atribuição

---

## 🎓 Bom Trabalho!

Esperamos que este material seja útil para aprender análise exploratória de dados biomédicos. 

**Lembrete importante:** A análise exploratória é uma arte tanto quanto uma ciência. Não existe apenas "uma forma certa" de explorar dados - seja curioso, criativo e crítico!

---

**Última atualização:** Fevereiro 2026  
**Versão:** 1.0
