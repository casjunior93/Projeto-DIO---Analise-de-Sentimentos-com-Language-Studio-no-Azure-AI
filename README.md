# Análise de Sentimentos com Language Studio no Azure AI

Passo a passo do desafio de projeto "Análise de Sentimentos com Language Studio no Azure AI" da DIO.

Links importantes:

[Detect faces in Vision Studio](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/04-face.html)

[Read text in Vision Studio](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/05-ocr.html)

[Analyze images in Vision Studio](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/03-image-analysis.html)

## Passo 1: Criando recurso do Speech service no Azure AI Services e convertendo fala em texto

Primeiro precisei criar um recurso do Speech service dentro do Azure AI Services.

![Img](./img/img1.gif)

Após o recurso ter sido criado, acessei o [Estúdio de fala do Azure](https://speech.microsoft.com/portal). Na página inicial, no tópico "Conversão de fala em texto", cliquei em "Conversão de fala em texto em tempo real".

Na próxima página, precisei indicar o recurso anterior que eu iria usar. Para isso, cliquei em meu nome no canto superior, e em "Recurso atual", mudei para o recurso criado anteriormente no Portal do Azure.

![Img](./img/img2.png)

Assim o checkbox informando sobre o uso do recurso ficou disponível.

![Img](./img/img3.png)

Entretando, essa é a forma que segui para criar e usar o recurso. A forma utilizada no vídeo para criar o recurso dentro do Estúdio de fala deve funcionar.

Em segui, fiz o upload de uma gravação que eu havia feito minutos antes. A fala foi convertida para texto muito rapidamente.

![Img](./img/img4.gif)

Esse foi o resultado da conversão:

![Img](./img/img5.png)
