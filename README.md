# Análise Socioeconômica do Jardim das Flores utilizando Big Data e Python

## Descrição do Projeto

Este projeto tem como objetivo realizar uma análise socioeconômica do bairro **Jardim das Flores**, utilizando técnicas de **Big Data** e a linguagem de programação **Python**. Através do tratamento e visualização de dados, buscamos fornecer insights que auxiliem a **Associação Comunitária Jardim das Flores** no planejamento de suas ações sociais, alinhando-as às reais necessidades da comunidade.

## Objetivos

- **Desenvolver visualizações e relatórios** que retratem o perfil socioeconômico dos moradores do bairro.
- **Capacitar os colaboradores** da associação no uso das ferramentas desenvolvidas.
- **Possibilitar a elaboração de projetos sociais mais eficazes**, alinhados às necessidades reais da comunidade.

## Dataset

O conjunto de dados utilizado é fictício e foi criado para fins educacionais. O arquivo `dados_jardim_das_flores.csv` contém as seguintes informações:

- **Renda**: Renda mensal em reais (R$) do indivíduo.
- **Escolaridade**: Nível de escolaridade do indivíduo.
  - Fundamental Incompleto
  - Fundamental Completo
  - Médio Incompleto
  - Médio Completo
  - Superior Incompleto
  - Superior Completo
  - Pós-graduação
- **Faixa Etária**: Faixa etária em anos.
  - 18-25
  - 26-35
  - 36-45
  - 46-55

## Tecnologias Utilizadas

- **Python 3.x**
- Bibliotecas Python:
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`
- **Jupyter Notebook** (opcional)

## Pré-requisitos

- Ter o **Python 3.x** instalado em seu sistema.
- Instalar as bibliotecas necessárias usando o `pip` ou `conda`.

---

## Estrutura do Projeto

- `dados_jardim_das_flores.csv` : Conjunto de dados utilizado na análise.
- `analise_socioeconomica.ipynb` : Notebook Jupyter com o código e análises detalhadas.
- `imagens/` : Pasta contendo as visualizações geradas durante a análise.
- `README.md` : Este arquivo.

## Análises Realizadas

- **Distribuição de Renda:** Histogramas mostrando como a renda está distribuída entre os moradores.
- **Nível de Escolaridade:** Gráficos de barras apresentando a quantidade de pessoas em cada nível educacional.
- **Distribuição por Faixa Etária:** Análise demográfica dos moradores por faixa etária.

## Resultados e Discussão

Os resultados da análise indicam:

- **Concentração de Baixa Renda:** A maioria dos moradores possui renda mensal abaixo de R$ 1.500,00.
- **Baixo Nível de Escolaridade:** Predomínio de níveis de escolaridade fundamental incompleto e médio incompleto.
- **População Jovem:** Alta concentração de moradores na faixa etária de 18 a 25 anos.
- **Correlação Positiva entre Escolaridade e Renda:** Indivíduos com maior nível educacional tendem a ter rendas mais altas.

Essas informações podem auxiliar a associação na criação de projetos voltados para:

- **Educação:** Programas de alfabetização e incentivo à continuidade dos estudos.
- **Empregabilidade:** Cursos profissionalizantes para aumentar as oportunidades de emprego.
- **Juventude:** Atividades e projetos direcionados aos jovens da comunidade.
