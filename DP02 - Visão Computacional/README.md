# Reconhecimento Facial e transformação de imagens em Dados no Azure ML

O reconhecimento facial e a transformação de imagens em dados são tarefas comuns em muitos cenários de aprendizado de máquina e análise de dados. O Microsoft Azure oferece várias ferramentas e serviços para ajudar nesses processos, incluindo o Azure Machine Learning (Azure ML) e seus recursos relacionados.

Vamos iniciar os projetos no **Vision Studio** através do link https://portal.vision.cognitive.azure.com/gallery/featured.
![imagem1](https://github.com/franciscampos91/microsoft-azure-ai-fundamentals-dio/blob/main/DP02%20-%20Vis%C3%A3o%20Computacional/images/01.png)

No primeiro teste, vamos utilizar o recurso para reconhecer faces em uma imagem. Na categoria "Face", clicamos em "Detect faces in an image".
![imagem2](https://github.com/franciscampos91/microsoft-azure-ai-fundamentals-dio/blob/main/DP02%20-%20Vis%C3%A3o%20Computacional/images/02.png)

Em "Detect faces in an image" traz algumas imagens para teste, mas vamos enviar uma foto para realizar a detecção. Clicando em "Browse for a file".
![imagem3](https://github.com/franciscampos91/microsoft-azure-ai-fundamentals-dio/blob/main/DP02%20-%20Vis%C3%A3o%20Computacional/images/03.png)

Ao enviar uma foto, a aplicação inicia os teste e faz uma marcação ao detectar um rosto e do lado direito exibe os atributos que foram detectados.
![imagem4](https://github.com/franciscampos91/microsoft-azure-ai-fundamentals-dio/blob/main/DP02%20-%20Vis%C3%A3o%20Computacional/images/04.png)


![imagem5](https://github.com/franciscampos91/microsoft-azure-ai-fundamentals-dio/blob/main/DP02%20-%20Vis%C3%A3o%20Computacional/images/05.png)



No próximo exemplo vamos rotular imagens.  Voltando na tela principal de opções, em "Featured" vamos clicar em "Add captions to images".
![imagem6](https://github.com/franciscampos91/microsoft-azure-ai-fundamentals-dio/blob/main/DP02%20-%20Vis%C3%A3o%20Computacional/images/06.png)

Dando sequencia, vamos enviar uma imagem ao invés de utilizar as do modelo. Clicamos em "Browse for a file" e selecionamos o arquivo para enviar para os testes.
![imagem7](https://github.com/franciscampos91/microsoft-azure-ai-fundamentals-dio/blob/main/DP02%20-%20Vis%C3%A3o%20Computacional/images/07.png)

A imagem é analisada e do lado direito é exibido os atributos detectados. A detecção detectou que a imagem tratava de um cachorro utilizando óculos e bandana.
![imagem8](https://github.com/franciscampos91/microsoft-azure-ai-fundamentals-dio/blob/main/DP02%20-%20Vis%C3%A3o%20Computacional/images/08.png)

Por fim, utilizaremos a função de extrair texto de uma imagem. Vamos em "Optical character recogniton" e "Extract text from images". 
![imagem9](https://github.com/franciscampos91/microsoft-azure-ai-fundamentals-dio/blob/main/DP02%20-%20Vis%C3%A3o%20Computacional/images/09.png)

Esta função extrai textos de imagem, seja um documento, algo escrito a mão  ou placas. Enviaremos uma imagem para os testes clicando em "Browse for a file".
![imagem10](https://github.com/franciscampos91/microsoft-azure-ai-fundamentals-dio/blob/main/DP02%20-%20Vis%C3%A3o%20Computacional/images/10.png)

Através do optical character recognition (OCR) é feita a extração do texto detectado na imagem e exibido ao lado da imagem.
![imagem11](https://github.com/franciscampos91/microsoft-azure-ai-fundamentals-dio/blob/main/DP02%20-%20Vis%C3%A3o%20Computacional/images/11.png)

## Considerações finais

Os serviços que foram mencionados podem ser acessados e utilizado por outros aplicativos ou serviços. Podemos exemplificar sua aplicação em um sistema que detecta as faces e esta conectado a uma servidor de pessoas procuradas pela justiça com rostos cadastrados, se a face detectada for reconhecida e encontrada no banco, o sistema emititá alertas.
Podemos ainda utilizadar para o armazenamento de documentos físicos, o sistema irá reconhecer os textos e transfromará a imagem em dados.
