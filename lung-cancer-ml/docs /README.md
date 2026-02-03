# L.C.P - Lung Cancer Prediction

> **Sistema Inteligente de Apoio à Decisão Clínica (CDSS)**

O **L.C.P** é uma ferramenta de auxílio ao diagnóstico médico projetada para identificar a **probabilidade de risco** de câncer de pulmão em pacientes.

Diferente de sistemas convencionais, **o L.C.P não busca substituir o julgamento clínico**, mas atuar como uma "segunda opinião" baseada em dados, agilizando a triagem e destacando automaticamente os fatores de risco críticos (como tabagismo, idade, sintomas específicos) para que o médico possa focar sua atenção nos casos de maior urgência.

Atualmente, o núcleo de inteligência artificial já opera com uma precisão validada superior a **89%** e o projeto caminha para se tornar um produto de software (SaaS) para integração em hospitais e clínicas.

## 🎯 Objetivo e Funcionalidade

O sistema funciona como um **Alerta de Risco**:

1.  **Entrada:** O médico preenche um formulário rápido com dados clínicos e comportamentais do paciente durante a consulta ou triagem.
2.  **Processamento:** O algoritmo analisa os padrões com base em milhares de casos históricos.
3.  **Saída:** O sistema retorna:
    * O **Nível de Probabilidade** (Baixo, Médio ou Alto Risco).
    * Os **Fatores de Risco Determinantes** para aquele paciente específico (Ex: *O sistema alertou risco alto devido à combinação de Idade X + Sintoma Y*).

## 🚀 Status do Projeto

🚧 **Em Desenvolvimento (Fase de Transição)** 🚧

*  **Núcleo de IA:** Modelo preditivo treinado, validado e otimizado (Random Forest com ~89% de acurácia).
*  **Em Progresso:** Desenvolvimento da API (Backend) e Interface Web (Frontend em React).

## 📋 Pré-requisitos

Para rodar o núcleo de Data Science localmente, você precisará de:

* **Python 3.8+**
* **Jupyter Lab** ou **Notebook**

Principais bibliotecas:
* `scikit-learn` (Modelagem Preditiva)
* `pandas` & `numpy` (Processamento de Dados)
* `matplotlib` & `seaborn` (Análise Visual)

## 🔧 Instalação e Execução

Siga os passos abaixo para testar o modelo preditivo:

1.  **Clone o repositório:**
    ```bash
    git clone [https://github.com/seu-usuario/lung-cancer-prediction.git](https://github.com/seu-usuario/lung-cancer-prediction.git)
    ```

2.  **Acesse a pasta:**
    ```bash
    cd lung-cancer-prediction
    ```

3.  **Instale as dependências:**
    ```bash
    pip install pandas numpy scikit-learn matplotlib seaborn jupyterlab
    ```

4.  **Inicie o ambiente:**
    ```bash
    jupyter lab
    ```

5.  **Visualize:**
    Abra o arquivo `lung_cancer_prediction.ipynb` para ver o treinamento do modelo, a matriz de confusão e os gráficos de fatores de risco.

## ⚙️ Validação Científica

A confiabilidade é o pilar deste projeto. O modelo atual passou por rigorosos testes estatísticos:

* **Hold-out Test:** Testado em dados nunca vistos pelo treinamento, mantendo acurácia estável de ~89.16%.
* **Sensibilidade vs. Especificidade:** O modelo é calibrado para minimizar falsos negativos (evitar que pacientes doentes sejam classificados como saudáveis).
* **Análise de Fatores:** Mapeamento de correlações reais (ex: impacto do fumo, idade e doenças crônicas) para garantir que a IA segue a lógica médica.

## 🛠️ Tecnologias

* [Python](https://www.python.org/) - Análise de Dados e Backend
* [JupyterLab](https://jupyter.org/) - Prototipagem rápida
* [Scikit-Learn](https://scikit-learn.org/) - Machine Learning
* [React](https://reactjs.org/) - *Futura interface do usuário*

## ✒️ Autores e Equipe

* **[Luidy Costa dos Santos](https://github.com/Luidy-Costa/)** - *Tech Lead & Backend*
    * Responsável pela arquitetura do sistema, engenharia do modelo de IA e supervisão técnica.
* **[Letícia Justino Maciel](https://github.com/leticiamaciel0)** - *Frontend Lead & Design*
    * Responsável pelo desenvolvimento da interface em React, auxílio na prototipagem e design do sistema.
* **[Aerton David Barbosa Mendes](https://github.com/davidbarbosam)** - *Prototipagem & Design*
    * Responsável pela criação dos protótipos de alta fidelidade (UI/UX) e auxílio no frontend.
* **[William Axel da Silva Ribeiro](https://github.com/williaxl)** - *Documentação*
    * Responsável pela elaboração e manutenção da documentação técnica e de usuário.
* **[Germano de Oliveira Moraes](https://github.com/germanomoraes)** - *Documentação*
    * Responsável pela elaboração e manutenção da documentação técnica e de usuário.
    
## 📄 Licença

Este projeto está sob a licença MIT - veja o arquivo [LICENSE.md](LICENSE.md) para detalhes.

## 🎁 Expressões de gratidão

* Compartilhe este projeto com quem se interessa por Data Science e Saúde 📢;
* Um agradecimento especial à equipe pelo esforço conjunto 🫂;
