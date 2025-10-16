# Análise de Segmentação de Clientes com K-Means

Este projeto demonstra o uso de Machine Learning não supervisionado, especificamente o algoritmo **K-Means**, para segmentar clientes de um shopping com base em seus padrões de consumo. O objetivo é transformar dados brutos em insights acionáveis que possam guiar estratégias de marketing personalizadas.

## 🎯 Objetivo do Projeto

Identificar grupos distintos (clusters) de clientes com base em sua **renda anual** e **pontuação de gastos**, permitindo que a empresa direcione campanhas de marketing de forma mais eficiente e personalizada para cada perfil.

## 📊 Sobre o Dataset

O conjunto de dados `Mall_Customers.csv` foi obtido da plataforma [Kaggle](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python) e contém as seguintes informações:

*   **Gender**: Gênero do cliente
*   **Age**: Idade do cliente
*   **Annual Income (k$)**: Renda anual em milhares de dólares
*   **Spending Score (1-100)**: Pontuação de gastos atribuída pelo shopping, variando de 1 a 100.

## 🛠️ Ferramentas e Técnicas Utilizadas

*   **Linguagem:** Python
*   **Bibliotecas:**
    *   **Pandas:** Para manipulação e limpeza dos dados.
    *   **Matplotlib** e **Seaborn:** Para visualização dos dados e dos clusters.
    *   **Scikit-learn:** Para aplicação do modelo de Machine Learning.
*   **Algoritmo:** K-Means Clustering.
*   **Técnica Auxiliar:** O **Método do Cotovelo (Elbow Method)** foi utilizado para determinar o número ideal de clusters (K=5).

## 🚀 Resultados: Os 5 Segmentos de Clientes

A análise revelou 5 perfis de clientes distintos, cada um com características e potencial de marketing únicos:

1.  **O Alvo Principal (Cluster 1)**
    *   **Perfil:** Alta renda e alta pontuação de gastos.
    *   **Estratégia:** Clientes de alto valor. Ideal para programas de fidelidade premium, marketing de produtos de luxo e acesso antecipado a novidades.

2.  **Os Cautelosos (Cluster 3)**
    *   **Perfil:** Alta renda, mas baixa pontuação de gastos.
    *   **Estratégia:** Possuem alto poder de compra, mas são seletivos. Requerem campanhas que demonstrem valor, qualidade e exclusividade para convencê-los a comprar.

3.  **Os Consumidores Padrão (Cluster 2)**
    *   **Perfil:** Renda e gastos moderados.
    *   **Estratégia:** Representam a base de clientes. Respondem bem a promoções sazonais, marketing de massa e ofertas de combos.

4.  **Os Econômicos (Cluster 0)**
    *   **Perfil:** Baixa renda e baixa pontuação de gastos.
    *   **Estratégia:** Clientes sensíveis a preço. O foco deve ser em promoções agressivas, cupons de desconto e produtos de entrada.

5.  **Os Despreocupados (Cluster 4)**
    *   **Perfil:** Baixa renda, mas alta pontuação de gastos.
    *   **Estratégia:** Provavelmente jovens e influenciados por tendências. Respondem bem a marketing em redes sociais, produtos da moda e ofertas de crédito facilitado.

## 💡 Como Executar

O projeto foi desenvolvido em um ambiente Jupyter Notebook (Google Colab). Para reproduzir a análise:
1.  Clone este repositório.
2.  Certifique-se de ter o arquivo `Mall_Customers.csv` no mesmo diretório.
3.  Abra o arquivo `analise_segmentacao_clientes.ipynb` e execute as células sequencialmente.
