# 🧬 Modelo Preditivo para a Incidência de Câncer de Mama

Este repositório contém o projeto de conclusão de curso desenvolvido para a **Especialização em Eng. e Adm. de Sistemas de Banco de Dados (Faculdade de Tecnologia / Unicamp)**. O objetivo principal do trabalho é o desenvolvimento e a comparação de modelos preditivos baseados em Machine Learning para classificar tumores de mama entre benignos (B) e malignos (M), auxiliando no diagnóstico precoce.

---

## 🎯 Escopo do Projeto

O projeto aborda o ciclo completo de desenvolvimento em Ciência de Dados e IA:

1.  **Análise Exploratória de Dados (AED):** Investigação estatística e visual (gráficos de distribuição e matrizes de correlação) para compreender a distribuição das variáveis e identificar relações relevantes no ecossistema do tumor.
2.  **Engenharia e Preparação de Dados:** Tratamento de dados, conversão de variáveis categóricas e normalização de atributos em escalas distintas para garantir a estabilidade do treinamento.
3.  **Modelagem e Treinamento:** Implementação comparativa utilizando três algoritmos tradicionais de Machine Learning:
    * Regressão Logística
    * Árvore de Decisão (*Decision Tree*)
    * Floresta Aleatória (*Random Forest*)
4.  **Métricas de Avaliação:** Validação rigorosa dos modelos através de métricas de Acurácia, Precisão, *Recall*, *F1-Score* e validação cruzada (*Cross-Validation*).

---

## 📊 Resultados Obtidos

Após os testes e validação cruzada, o **Modelo de Árvore de Decisão** apresentou o melhor desempenho na previsão do diagnóstico:

* **Acurácia no conjunto de teste:** 100%
* **Pontuação de Validação Cruzada:** ~91%
* **Principais Variáveis Preditoras:** Os fatores mais relevantes e de maior peso para as decisões do modelo foram:
    1. `concave points_mean`
    2. `area_mean`
    3. `radius_mean`
    4. `perimeter_mean`
    5. `concavity_mean`

---

## 🛠️ Stack Tecnológica

* **Linguagem Principal:** Python
* **Manipulação & Análise de Dados:** Pandas, NumPy
* **Machine Learning & Frameworks:** Scikit-Learn, Keras, TensorFlow
* **Visualização de Dados:** Matplotlib, Seaborn
* **Ambiente de Desenvolvimento:** Jupyter Notebook
* **Dataset Utilizado:** Wisconsin Diagnostic Breast Cancer (WDBC)

---

## 🚀 Como Executar o Projeto Localmente

1.  **Clone o repositório:**
    ```bash
    git clone [https://github.com/ocostajr/public-projects.git](https://github.com/ocostajr/public-projects.git)
    cd public-projects/redes-neurais
    ```

2.  **Configure o seu ambiente virtual (Recomendado):**
    ```bash
    python -m venv venv
    # No Linux/Mac: source venv/bin/activate
    # No Windows: .\venv\Scripts\activate
    ```

3.  **Instale as dependências:**
    ```bash
    pip install -r requirements.txt
    ```

4.  **Execute o Notebook:**
    Abra o ambiente do Jupyter ou VS Code e execute o arquivo `.ipynb` desenvolvido para acompanhar o passo a passo da análise e treinamento.

---

## 📄 Licença

Este projeto está sob a licença MIT. Sinta-se à vontade para clonar e utilizar o código para fins de estudo em Inteligência Artificial e Saúde Coletiva.

---
Trabalho desenvolvido por [Osvaldo da Costa Júnior](https://github.com/ocostajr).
