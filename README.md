# FIAP - Faculdade de Informática e Administração Paulista

<p align="center">
    <a href="https://www.fiap.com.br/">
        <img src="https://www.fiap.com.br/wp-content/themes/fiap2016/images/sharing/fiap.png" alt="FIAP - Faculdade de Informática e Admnistração Paulista" border="0" width=40% height=40%>
    </a>
</p>

<br>

# Challenge - FASE 7  
    Sprint 3: Análise Estatística de Produtividade Agrícola com Base Histórica Integrada

## Nome do grupo  
    TerraFusion Tech 

## Integrantes: 
- <a href="https://www.linkedin.com/in/ana-kolodji-94ba66324/">Ana Kolodji</a>
- <a href="https://www.linkedin.com/in/fernando-segregio/">Fernando Segregio</a>    
- <a href="https://www.linkedin.com/in/matheusconciani/">Matheus Conciani</a>

## Professores:
### Tutor(a)  
- <a href="https://www.linkedin.com/in/leonardoorabona/">Leonardo Ruiz Orabona</a>
### Coordenador(a)  
- <a href="https://www.linkedin.com/in/profandregodoi/">André Godoi</a>

---

## Descrição do Projeto – Sprint 3

Nesta etapa, o foco foi a análise estatística dos dados históricos integrados da agricultura baiana, relacionando produtividade da soja com os índices de vegetação NDVI e EVI. A partir de dados reais da CONAB e SATVEG, estruturamos uma base de dados robusta e aplicamos métodos estatísticos para entender a correlação entre variáveis vegetativas e desempenho produtivo.

---

## Objetivos da Sprint 3

- Realizar análise exploratória da base histórica  
- Calcular correlações entre NDVI, EVI e produtividade agrícola  
- Construir modelos de regressão linear simples  
- Gerar visualizações explicativas sobre tendências e padrões  
- Documentar os resultados em relatório técnico

---

## Etapas Realizadas

### 1. Importação e Tratamento dos Dados  
- Coleta dos dados de produtividade via CONAB (Bahia)  
- Coleta dos índices NDVI e EVI via plataforma SATVEG  
- Integração dos dados pela variável comum “Ano”  
- Limpeza e verificação da consistência da base

### 2. Análise Estatística  
- Cálculo da correlação de Pearson  
- Regressão Linear Simples com NDVI e EVI como variáveis preditoras  
- Interpretação dos coeficientes e R² do modelo

### 3. Visualização Gráfica  
- Gráficos de linha para tendências temporais  
- Dispersão com linha de regressão (NDVI x Produtividade e EVI x Produtividade)

### 4. Geração de Relatório  
- Documento técnico em PDF com metodologia, gráficos e discussão crítica  
- Sugestões de melhoria e expansão futura da base

---

## Resultados Observados

- Correlação positiva significativa entre NDVI e produtividade agrícola  
- Regressão linear com NDVI apresentou boa explicabilidade (R² satisfatório)  
- Tendência crescente dos índices vegetativos ao longo dos anos, indicando impacto do manejo agrícola e tecnologias de cultivo

---

## Estrutura do Projeto

- `data/`  
  - `NDVI_EVI.csv`  
  - `produtividade_conab.csv`  

- `notebook/`  
  - `Notebook_Sprint3_Agricultura.ipynb`  

- `report/`  
  - `Relatorio_Sprint3_Projeto_Agricultura.pdf`

---

## Como Executar

1. Abra o notebook `sprint3.ipynb` no Google Colab ou Jupyter.  
2. Faça upload dos arquivos `NDVI_EVI.csv` e `produtividade_conab.csv`.  
3. Execute as células do notebook em ordem.  
4. Os gráficos e análises estatísticas serão gerados automaticamente.

---

## Licença

Este projeto segue os moldes do **MODELO GIT FIAP** e está licenciado sob a [Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/)

---
