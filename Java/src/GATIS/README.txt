O projeto foi desenvolvido no Eclipse.

Para correto funcionamento do algoritmo, deve-se adionar a biblioteca uacari.jar ao build path do projeto.
No eclipse :
1-bot�o direito na pasta do projeto
2-properties
3-Java Build Path
4- em Library, add JARS... (o uacari.jar se encontra em src\GATIS)
5- Apply and close

Os parametros do GA est�o todos como atributos do arquivo GA.java, coloquei 5 imagens para testes.
As imagens 1, 2 e 3 n�o possuem uma plaquinha de marca��o, e o c�digo funciona perfeitamente.
As imagens 4 e 5 possuem a marca��o e est�o ai pra demonstrar um ponto falho do GA.

para alternar as imagens, basta alterar o atributo static String imagem.
por exemplo, para rodar a img1 que est� na pasta, basta alterar para:

static String imagem = "img1";

Para melhor an�lise j� deixei alguns calculos de m�dias que s�o impressas no console.

Todos os parametros est�o comentados para destacar qual � qual.

Para rodar abra a pasata GATIS como projeto e executar o arquivo GA como aplica��o java.