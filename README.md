# ENANI 2019 - Análise de Clustering para Obesidade Infantil

## 📊 Sobre o Projeto

Este projeto realiza uma análise de clustering dos dados do Estudo Nacional de Alimentação e Nutrição Infantil (ENANI) 2019, com foco na identificação de padrões relacionados à obesidade infantil no Brasil.

## 🎯 Objetivos

- Identificar grupos (clusters) de crianças com padrões alimentares e características similares
- Analisar fatores de risco associados à obesidade infantil
- Desenvolver perfis característicos para cada cluster identificado
- Fornecer insights para políticas públicas de saúde infantil

## 📁 Estrutura do Projeto

```
clustering(0-4)/
│
├── 1-Sample/
│   └── aval.ipynb              # Análise inicial e amostragem dos dados
│
├── 2-E-Choice/
│   ├── DatasetE.csv            # Dataset com features selecionadas
│   └── echoice.ipynb           # Seleção e engenharia de features
│
├── 3-E-Aval/
│   ├── DSFinal.csv             # Dataset final processado
│   ├── avalFinal.ipynb         # Avaliação final das features
│   ├── e-Val.ipynb             # Validação dos dados
│   └── excluding_features*.ipynb # Notebooks para exclusão de features
│
├── 4-Clustering/
│   ├── perfis_clusters.csv     # Perfis detalhados de cada cluster
│   ├── dataset_completo_clusters.csv # Dataset com labels dos clusters
│   ├── visualizacao_clusters.png # Visualização dos clusters
│   └── relatorio_clusters.txt  # Relatório detalhado da análise
│
└── 4-Clustering play/
    └── cluster.ipynb           # Experimentação com algoritmos de clustering
```

## 🔍 Metodologia

### 1. Pré-processamento
- Limpeza e tratamento de dados ausentes
- Normalização de variáveis
- Seleção de features relevantes

### 2. Engenharia de Features
- Criação de índices compostos
- Transformação de variáveis categóricas
- Redução de dimensionalidade

### 3. Clustering
- Algoritmos utilizados: K-Means, DBSCAN, Hierarchical Clustering
- Otimização do número de clusters
- Validação dos resultados

### 4. Análise dos Resultados
- Caracterização dos perfis de cada cluster
- Identificação de fatores de risco
- Visualização e interpretação

## 📈 Principais Resultados

- **10 clusters identificados** com perfis distintos de crianças
- Fatores principais: padrões alimentares, condições socioeconômicas, acesso a alimentos
- Clusters de alto risco identificados para intervenção prioritária

## 🛠️ Tecnologias Utilizadas

- Python 3.x
- Pandas - Manipulação de dados
- NumPy - Computação numérica
- Scikit-learn - Algoritmos de machine learning
- Matplotlib/Seaborn - Visualização de dados
- Jupyter Notebook - Desenvolvimento interativo

## 📋 Pré-requisitos

```bash
pandas>=1.3.0
numpy>=1.21.0
scikit-learn>=0.24.0
matplotlib>=3.4.0
seaborn>=0.11.0
jupyter>=1.0.0
```

## 🚀 Como Usar

1. Clone o repositório:
```bash
git clone https://github.com/marcelosilva2604/clustering0-4.git
cd clustering0-4
```

2. Instale as dependências:
```bash
pip install -r requirements.txt
```

3. Execute os notebooks na ordem:
   - `1-Sample/aval.ipynb`
   - `2-E-Choice/echoice.ipynb`
   - `3-E-Aval/avalFinal.ipynb`
   - `4-Clustering play/cluster.ipynb`

## ⚠️ Observações Importantes

- Os arquivos de dados originais (>100MB) não estão incluídos no repositório
- Para acesso aos dados completos do ENANI 2019, consulte [site oficial]
- Este projeto é para fins acadêmicos e de pesquisa

## 📊 Visualizações

Os resultados incluem:
- Gráficos de distribuição dos clusters
- Análise de componentes principais
- Heatmaps de correlação
- Perfis comparativos entre clusters

## 🤝 Contribuições

Contribuições são bem-vindas! Por favor:
1. Faça um fork do projeto
2. Crie uma branch para sua feature
3. Commit suas mudanças
4. Push para a branch
5. Abra um Pull Request

## 📝 Licença

Este projeto está sob licença MIT. Veja o arquivo LICENSE para mais detalhes.

## 👥 Autor

Marcelo Silva - [@marcelosilva2604](https://github.com/marcelosilva2604)

## 🙏 Agradecimentos

- Equipe ENANI pela disponibilização dos dados
- Comunidade científica brasileira de nutrição infantil

---

**Nota**: Este é um projeto de pesquisa acadêmica. Os resultados devem ser interpretados no contexto apropriado e não substituem orientação médica profissional.