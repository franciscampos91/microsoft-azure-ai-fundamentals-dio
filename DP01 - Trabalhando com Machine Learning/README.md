# MACHINE LEARNING

## Criação de uma modelo de previsão

Será apresentado o processo de criação passo a passo de um modelo de previsão e seu testando seu resultado utilizando o estúdio do Azure Machine Learning.
O Azure Machine Learning é um aplicativo web onde é possível criar, treinar, testas e implantar modelos de Machine Learning.

No portal da Microsoft Azure vamos acessar o Azure Machine Learning Studio e iniciar o estúdio.
![imagem1](https://github.com/franciscampos91/microsoft-azure-ai-fundamentals-dio/blob/main/DP01%20-%20Trabalhando%20com%20Machine%20Learning/images/ml01.png)

Vamos clicar no menu lateral à esquerda em "ML automatizado" e depois em "Novo trabalho de ML automatizado".
![imagem1](https://github.com/franciscampos91/microsoft-azure-ai-fundamentals-dio/blob/main/DP01%20-%20Trabalhando%20com%20Machine%20Learning/images/ml02.png)

Na próxima tela, daremos um nome ao trabalho e ao experimento. Adicionamos uma descrição e avançamos.
![imagem1](https://github.com/franciscampos91/microsoft-azure-ai-fundamentals-dio/blob/main/DP01%20-%20Trabalhando%20com%20Machine%20Learning/images/ml03.png)

Em tipo de tarefas e dados, vamos selecionar a opção “Regressão” e em seguida clicar em “Criar”.
![imagem1](https://github.com/franciscampos91/microsoft-azure-ai-fundamentals-dio/blob/main/DP01%20-%20Trabalhando%20com%20Machine%20Learning/images/ml04.png)

Vamos dar um novo nome e avançar.
![imagem1](https://github.com/franciscampos91/microsoft-azure-ai-fundamentals-dio/blob/main/DP01%20-%20Trabalhando%20com%20Machine%20Learning/images/ml05.png)

Na próxima janela, selecionar a opção "De arquivos da Web" e avançar.
![imagem1](https://github.com/franciscampos91/microsoft-azure-ai-fundamentals-dio/blob/main/DP01%20-%20Trabalhando%20com%20Machine%20Learning/images/ml06.png)

Em "URL da Web" inserir o endereço "https://aka.ms/bike-rentals"
![imagem1](https://github.com/franciscampos91/microsoft-azure-ai-fundamentals-dio/blob/main/DP01%20-%20Trabalhando%20com%20Machine%20Learning/images/ml07.png)

Em configurações, no campo Cabeçalhos de Coluna selecionar a opção “Somente o primeiro arquivo tem cabeçalhos” e avançar.
![imagem1](https://github.com/franciscampos91/microsoft-azure-ai-fundamentals-dio/blob/main/DP01%20-%20Trabalhando%20com%20Machine%20Learning/images/ml08.png)

Manter as configurações em Esquema e avançar.
![imagem1](https://github.com/franciscampos91/microsoft-azure-ai-fundamentals-dio/blob/main/DP01%20-%20Trabalhando%20com%20Machine%20Learning/images/ml09.png)

E clicar em "Criar".
![imagem1](https://github.com/franciscampos91/microsoft-azure-ai-fundamentals-dio/blob/main/DP01%20-%20Trabalhando%20com%20Machine%20Learning/images/ml10.png)

Vamos selecionar o ativo de dados que acabamos de criar e clicar em avançar.
![imagem1](https://github.com/franciscampos91/microsoft-azure-ai-fundamentals-dio/blob/main/DP01%20-%20Trabalhando%20com%20Machine%20Learning/images/ml11.png)

Nas configurações de tarefas, em Coluna de destino, selecionar a opção “rentals (Integer)”, depois em “Exibir configurações adicionais”. Desmarcar todas as opções em Métrica primária e em Modelos permitidos selecionar “RandomForest” e “LightGBM”.

![imagem1](https://github.com/franciscampos91/microsoft-azure-ai-fundamentals-dio/blob/main/DP01%20-%20Trabalhando%20com%20Machine%20Learning/images/ml12.png)

![imagem1](https://github.com/franciscampos91/microsoft-azure-ai-fundamentals-dio/blob/main/DP01%20-%20Trabalhando%20com%20Machine%20Learning/images/ml13.png)


![imagem1](https://github.com/franciscampos91/microsoft-azure-ai-fundamentals-dio/blob/main/DP01%20-%20Trabalhando%20com%20Machine%20Learning/images/ml14.png)


![imagem1](https://github.com/franciscampos91/microsoft-azure-ai-fundamentals-dio/blob/main/DP01%20-%20Trabalhando%20com%20Machine%20Learning/images/ml15.png)

![imagem1](https://github.com/franciscampos91/microsoft-azure-ai-fundamentals-dio/blob/main/DP01%20-%20Trabalhando%20com%20Machine%20Learning/images/ml16.png)


![imagem1](https://github.com/franciscampos91/microsoft-azure-ai-fundamentals-dio/blob/main/DP01%20-%20Trabalhando%20com%20Machine%20Learning/images/ml17.png)

![imagem1](https://github.com/franciscampos91/microsoft-azure-ai-fundamentals-dio/blob/main/DP01%20-%20Trabalhando%20com%20Machine%20Learning/images/ml18.png)

![imagem1](https://github.com/franciscampos91/microsoft-azure-ai-fundamentals-dio/blob/main/DP01%20-%20Trabalhando%20com%20Machine%20Learning/images/ml19.png)

![imagem1](https://github.com/franciscampos91/microsoft-azure-ai-fundamentals-dio/blob/main/DP01%20-%20Trabalhando%20com%20Machine%20Learning/images/ml20.png)

![imagem1](https://github.com/franciscampos91/microsoft-azure-ai-fundamentals-dio/blob/main/DP01%20-%20Trabalhando%20com%20Machine%20Learning/images/ml21.png)

![imagem1](https://github.com/franciscampos91/microsoft-azure-ai-fundamentals-dio/blob/main/DP01%20-%20Trabalhando%20com%20Machine%20Learning/images/ml22.png)

![imagem1](https://github.com/franciscampos91/microsoft-azure-ai-fundamentals-dio/blob/main/DP01%20-%20Trabalhando%20com%20Machine%20Learning/images/ml23.png)

![imagem1](https://github.com/franciscampos91/microsoft-azure-ai-fundamentals-dio/blob/main/DP01%20-%20Trabalhando%20com%20Machine%20Learning/images/ml24.png)

![imagem1](https://github.com/franciscampos91/microsoft-azure-ai-fundamentals-dio/blob/main/DP01%20-%20Trabalhando%20com%20Machine%20Learning/images/ml25.png)

