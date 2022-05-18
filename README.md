# I2Ctemperature_Twitter_Bot_RaspberryPi

Made with Rodrigo Santos in ASe course.

reads temperature values from I2c component in raspberry and create tweets with it.

O objetivo centra-se na leitura do valor de temperatura lido pelo sensor TC74 e criar um bot para a rede social Twitter que faça tweets informando-nos do valor em questão. Está feito de modo a que um tweet seja escrito pelo bot cada vez que a temperatura varia pelo menos 3ºC. A comunicação com o sensor é feita por I2C em que temos as ligações feitas entre a placa e a raspberry pi através dos GPIO's destinados para este periférico. Para a autenticação foi usado o OAUTH. Para o bot usamos Twitter API v2 e tweepy.


You need to change the API credentials(twitter developer) in order to use it.
