# **Análise de Influenciadores no Instagram com Regressão Linear**

## **Descrição do Projeto**  
Este projeto utiliza o algoritmo de Regressão Linear para prever a taxa de engajamento de influenciadores no Instagram. A análise explora relações entre métricas como número de seguidores, média de curtidas e desempenho de novas postagens.  
O objetivo principal é desenvolver insights que auxiliem na escolha de influenciadores com maior potencial de engajamento para campanhas de marketing digital.  

---

## **Estrutura do Projeto**  
1. **Análise Exploratória:**  
   Realizamos uma análise inicial dos dados utilizando gráficos de dispersão, histogramas e análise de correlações para identificar padrões nos comportamentos de engajamento.  

2. **Implementação da Regressão Linear:**  
   Configuração do modelo de Regressão Linear com ajustes nos parâmetros e avaliação dos coeficientes para interpretar o impacto das variáveis independentes na taxa de engajamento.  

3. **Validação e Ajuste de Hiperparâmetros:**  
   Uso de técnicas como validação cruzada e regularização (L1 e L2) para evitar overfitting e garantir a robustez do modelo.  

4. **Avaliação do Modelo:**  
   Métricas como MAE, MSE, R² e visualizações gráficas são utilizadas para avaliar a performance preditiva do modelo.  

---

## **Estrutura dos Dados**  
O conjunto de dados inclui as seguintes variáveis principais:  

- `followers`: Número de seguidores do influenciador.  
- `avg_likes`: Média de curtidas por postagem.  
- `new_post_avg_like`: Média de curtidas recebidas por novas postagens 
- `60_day_eng_rate`: Taxa de engajamento dos últimos 60 dias.

Os dados foram processados para incluir variáveis derivadas e normalizadas, garantindo a qualidade na análise e no treinamento do modelo.  

---

## **Instalação e Requisitos**  

Certifique-se de ter as seguintes bibliotecas instaladas:  

```bash
pip install pandas numpy matplotlib seaborn scikit-learn

git clone https://github.com/SeuNomeDeUsuario/projeto_regressao_linear.git

cd ProjetoRegressaoT3

python main.py 
```
## **Tecnologias Utilizadas**

- Python 3.10: Linguagem base do projeto.
- Pandas: Manipulação e análise de dados.
- NumPy: Operações matemáticas.
- Matplotlib/Seaborn: Visualizações de dados.
- Scikit-learn: Treinamento, validação e ajuste de modelos.


