# Projeto: Laboratório AI-900 no Azure Machine Learning

Este README documenta o processo realizado para criar um workspace no **Azure Machine Learning**, configurar um experimento de Machine Learning Automatizado e realizar testes com base nos dados de aluguel de bicicletas.

---

## Passos Realizados

### 1. Acessando o Azure Machine Learning
- Acessei minha conta no Azure.
- Pesquisei por **Azure Machine Learning** na barra de pesquisa do portal.

### 2. Criando um Novo Workspace
- Cliquei no botão **Create** e depois em **New workspace**.
- Durante a criação do workspace:
  - Criei um **Resource Group** chamado `teste`.
  - No campo **Name**, defini como `laboratorioai900`.
  - Escolhi a região **East US**.
- Cliquei em **Review + create** para finalizar.

### 3. Validação e Criação do Workspace
- Após a validação bem-sucedida com a mensagem *"Validation passed"*, cliquei em **Create**.
- Esperei o processo de criação e a verificação dos status em *"Microsoft.MachineLearningServices"*.
- Ao final, cliquei em **Go to resource** para acessar o lab criado.

### 4. Acessando o Studio
- No recurso `laboratorioai900`, cliquei no botão **Launch studio**.
- Fui direcionado para o Azure Machine Learning Studio no link:
  [https://ml.azure.com/...](https://ml.azure.com/?tid=b93d187c-4957-41a2-88fe-0ac51f128297&wsid=/subscriptions/b4748eb3-d2ad-459b-914d-7f7c5ee052b7/resourcegroups/teste/providers/Microsoft.MachineLearningServices/workspaces/laboratorioai900).

### 5. Criando um Trabalho de ML Automatizado
- Na página do studio, selecionei **ML Automatizado** na barra lateral esquerda e cliquei em **Novo trabalho de ML automatizado**.
- Segui o guia oficial: [Documentação do Lab](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/01-machine-learning.html).
- Configurei:
  - Nome do trabalho: `mslearn-bike-rental`.
  - Nome do experimento: `mslearn-bike-rental`.
  - Adicionei a descrição indicada sem tags.

### 6. Configuração de Tarefa e Dados
- Escolhi **Regressão** como tipo de tarefa.
- Para os dados:
  - Fonte: **De arquivos da Web**.
  - URL: [https://aka.ms/bike-rentals](https://aka.ms/bike-rentals).
- Escolhi o formato de arquivo conforme indicado na documentação.
- Cliquei em **Create** e, após a confirmação, continuei para a próxima etapa.

### 7. Configuração de Tarefas
- Segui as instruções detalhadas na [documentação](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/01-machine-learning.html).
- Após configurar, o trabalho foi executado automaticamente.

### 8. Execução e Análise
- O processo foi executado em cerca de 5 a 10 minutos.
- Após a conclusão, analisei os gráficos gerados, como:
  - **Residuals**.
  - **Predicted vs True**.
- Verifiquei as métricas do modelo conforme solicitado na documentação.

### 9. Teste Final
- Realizei o teste com os parâmetros fornecidos na documentação e obtive o resultado final:
  - **Resultado do teste**: `352.356467494571`.

---

## Conclusão
O projeto foi concluído com sucesso, incluindo a criação do workspace, configuração do experimento e análise dos resultados do modelo preditivo. A experiência seguiu todas as etapas descritas na documentação oficial.

