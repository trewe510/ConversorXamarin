OBS: Nunca fiz um TXT de projeto, então agradeço a compreensão e me corrijam por gentileza.

Projeto Xamarin.Forms

Construir um App para Android de Conversão de Moedas.

Inicio:

Construí uma tela inicial com uma caixa de texto para pessoa se identificar, mas não é obrigatório o preenchimento;
Coloquei um botão avançar para navegar para página seguinte;
Configurei o botão na aba MainPage.Xaml.cs

Na página dois:

Incluí uma bandeira de cada país relacionada com o nome da Moeda ( BandeiraBrasil: BRL);
Construí o layout do meu app, detalhadamente ( Texto, fontsize, espaço alocado, etc)
Fiz um botão em forma de calculadora;
Configurei o botão na Page1.Xaml.cs ( Navegar para a calculadora) esse botão foi construído e inserido ao final de cada guia de cada moeda;

Na página três:

Ao apertar o botão da calculadora, vamos direto para a calculadora;
Construí a mesma, coluna por coluna e linha por linha;
Depois, fui no Xaml.cs da minha página dois e incluí todas as configurações para a calculadora ser funcional (soma, subtração,divisão, multiplicação) ( A porcentagem não ficou do jeito que eu queria mas fuciona);
Configurei o Botão "$" para que o mesmo retornasse a tela onde encontra-se as moedas;
Criei uma pasta para receber a API ( Models, Services )
Instalei o Pack Json para utilizar a API;

Não concluído ainda: - Retornar com os valores obtidos na calculadora, na page das moedas;
Vincular a API do https://freecurrencyapi.net/ no meu app, apesar de ter criado um "folder" para a API não consegui designar sua função nas configurações;
Expor após a extração do resultado obtido na calculadora, a conversão dos demais valores em cima do resultado;

Preciso seguir estudando, mas estou feliz com os avanços. Em pouco tempo estarei com habilidades para construir apps melhores.
Grato pelo tempo destinado a compreensão de meus estudos até agora.