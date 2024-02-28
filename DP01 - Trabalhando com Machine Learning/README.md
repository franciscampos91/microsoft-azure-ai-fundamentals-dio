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

Ainda nas configurações de tarefas, inserir as configurações, conforme imagem, e avançar.
![imagem1](https://github.com/franciscampos91/microsoft-azure-ai-fundamentals-dio/blob/main/DP01%20-%20Trabalhando%20com%20Machine%20Learning/images/ml13.png)

Em computação clicar em avançar em alterações.
![imagem1](https://github.com/franciscampos91/microsoft-azure-ai-fundamentals-dio/blob/main/DP01%20-%20Trabalhando%20com%20Machine%20Learning/images/ml14.png)

Por fim, clicar em “Enviar trabalho de treinamento”.
![imagem1](https://github.com/franciscampos91/microsoft-azure-ai-fundamentals-dio/blob/main/DP01%20-%20Trabalhando%20com%20Machine%20Learning/images/ml15.png)

O processo então entrará em execução e aproximadamente 15 minutos após será concluído.
![imagem1](https://github.com/franciscampos91/microsoft-azure-ai-fundamentals-dio/blob/main/DP01%20-%20Trabalhando%20com%20Machine%20Learning/images/ml16.png)


![imagem1](https://github.com/franciscampos91/microsoft-azure-ai-fundamentals-dio/blob/main/DP01%20-%20Trabalhando%20com%20Machine%20Learning/images/ml17.png)

Após terminar a execução o status exibirá “Concluído”.
![imagem1](https://github.com/franciscampos91/microsoft-azure-ai-fundamentals-dio/blob/main/DP01%20-%20Trabalhando%20com%20Machine%20Learning/images/ml18.png)

No menu lateral à esquerda, em Tarefas, exibe as tarefas executadas.
![imagem1](https://github.com/franciscampos91/microsoft-azure-ai-fundamentals-dio/blob/main/DP01%20-%20Trabalhando%20com%20Machine%20Learning/images/ml19.png)

Em “Modelos”, clicar em “Pontos de Extremidade”
![imagem1](https://github.com/franciscampos91/microsoft-azure-ai-fundamentals-dio/blob/main/DP01%20-%20Trabalhando%20com%20Machine%20Learning/images/ml20.png)


## Realizar o teste do modelo

Clicar em “Pontos de Extremidade” e depois clicar no nome.
![imagem1](https://github.com/franciscampos91/microsoft-azure-ai-fundamentals-dio/blob/main/DP01%20-%20Trabalhando%20com%20Machine%20Learning/images/ml21.png)

No ponto de extremidade selecionado, clicar em “Testar”.
![imagem1](https://github.com/franciscampos91/microsoft-azure-ai-fundamentals-dio/blob/main/DP01%20-%20Trabalhando%20com%20Machine%20Learning/images/ml22.png)

Na próxima tela iremos inserir os valores no código para teste.
![imagem1](https://github.com/franciscampos91/microsoft-azure-ai-fundamentals-dio/blob/main/DP01%20-%20Trabalhando%20com%20Machine%20Learning/images/ml23.png)

Vamos inserir os valores conforme a documentação e clicar no botão “Testar”.
![imagem1](https://github.com/franciscampos91/microsoft-azure-ai-fundamentals-dio/blob/main/DP01%20-%20Trabalhando%20com%20Machine%20Learning/images/ml24.png)


Será exibido o resultado do teste.
![imagem1](https://github.com/franciscampos91/microsoft-azure-ai-fundamentals-dio/blob/main/DP01%20-%20Trabalhando%20com%20Machine%20Learning/images/ml25.png)


O resultado previsto é **329.0222291921439**.

Arquivo json de teste:
```
{
	"input_data": {
		"data": [
			{
				"day":  1,
				"mnth": 1,
				"year": 2022,
				"season": 2,
				"foliday": 0,
				"weekday": 1,
				"workingday": 1,
				"weathersit": 2,
				"temp": 0.3,
				"windspeed": 0.3
			}
		]
	}
}
```

