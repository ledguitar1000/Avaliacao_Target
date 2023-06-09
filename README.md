# Avaliacao_Target

	Inteligência artificial

	Desde a tempos remotos, o homem vem tentando substituir a força física por maquinas.  Assim, com o tempo a tecnologia foi avançando e ainda mais nas ultimas décadas, que deu um salto tecnológico assustador. Podemos dizer que, aos poucos e cada vez em números maiores, o homem está perdendo seu espaço para as máquinas. Mas, até que ponto isso é positivo ou negativo? 
	
	Podemos citar o final da década de 60, onde a classe trabalhadora se surpreendeu com a robótica no Japão. Essa transformação na troca de operários por robôs inteligentes, capazes de tarefas complexas, alertou a todos que era de extrema necessidade a intelectualização do ser humano.

	No início da década de 70 nos escritórios, e no início de 80 nos lares e escolas, demonstrou o quanto a população tinha interesse pela inteligência artificial que havia nos computadores. Vimos funções complexas como: Calculo de orçamento, criação de desenhos técnicos, sendo executado até mesmo com mais eficiência do que o homem.

	No entanto, da década de 90 até os dias atuais, com todo o avanço tecnológico, pudemos ver um lado negativo nessa história. As máquinas, ao dominarem as redes sociais com seus algoritmos bem elaborados, também com o sistema de vigilância e segurança invadindo a privacidade das pessoas, fez com que usuários comuns ficassem preocupados com o que mais poderia acontecer, se a inteligência artificial se rebelasse, já que estamos cercados por essa tecnologia tão avançada.

	Precisamos refletir e pensar num meio termo, para que todos possam ter benefícios com a Inteligência artificial, mas sermos escravizados por ela. E fato que nos nos hospitais, nas lojas, nas escolas e até mesmo em nossos lares, faz uma enorme diferença possuirmos coisas automatizadas, mas isso também faz com que os cidadãos comuns dependam cada vez mais disso, e coloquem cada vez menos seu raciocínio lógico pra funcionar.

	Para finalizar, nada do que foi citado, tem a intenção de diminuir a importância da inteligência artificial, isso só serve de alerta, para que nenhuma pessoa se coloque por completo nas mãos de algo que não sabemos até aonde pode chegar.   

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------

Job Rotation - Ribeirão Preto - Observe o trecho de código abaixo: 

1-

int INDICE = 13, SOMA = 0, K = 0; 
enquanto K < INDICE faça { K = K + 1; 
SOMA = SOMA + K; 
} 
Imprimir (SOMA);

Ao final do processamento, qual será o valor da variável SOMA?

R: O código acima é um laço de repetição "enquanto" que soma os números de 1 até 13 e armazena o resultado na variável SOMA. Na primeira iteração do laço, K será 1 e SOMA será 1. Na segunda iteração, K será 2 e SOMA será 3 (SOMA + K). O processo continua até que K seja igual a 13 e SOMA seja igual a 91 (1 + 2 + 3 + ... + 13). Após o término do laço, o valor de SOMA será impresso.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
2) Dado a sequência de Fibonacci, onde se inicia por 0 e 1 e o próximo valor sempre será a soma dos 2 valores anteriores (exemplo: 0, 1, 1, 2, 3, 5, 8, 13, 21, 34...), escreva um programa na linguagem que desejar onde, informado um número, ele calcule a sequência de Fibonacci e retorne uma mensagem avisando se o número informado pertence ou não a sequência.

IMPORTANTE: 

Esse número pode ser informado através de qualquer entrada de sua preferência ou pode ser previamente definido no código;


num = int(input("Digite um número inteiro: "))

fib1 = 0
fib2 = 1
fib_atual = 1

while fib_atual < num:
    fib_atual = fib1 + fib2
    fib1 = fib2
    fib2 = fib_atual

if fib_atual == num:
    print(num, "pertence à sequência de Fibonacci.")
else:
    print(num, "não pertence à sequência de Fibonacci.")

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------

3) Descubra a lógica e complete o próximo elemento: 

a) 1, 3, 5, 7, ___9   Segue uma sequência de dois em dois.

b) 2, 4, 8, 16, 32, 64, ____128   Segue a sequência dos bits

c) 0, 1, 4, 9, 16, 25, 36, ____  49  Segue a sequência somando os números impares 0+1=1 ,1+3= 4, 4+5=9 , 9+7=16 e assim por diante até chegar no 49..

d) 4, 16, 36, 64, ____  100  Segue a sequência de multiplicação dos números pares por si mesmo.

e) 1, 1, 2, 3, 5, 8, ____ 13    Sequência de Fibonacci, onde os números somam com o anterior

f) 2,10, 12, 16, 17, 18, 19, ____ 200 Sequência de números com a letra D

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------

4 - Dois veículos (um carro e um caminhão) saem respectivamente de cidades opostas pela mesma rodovia. O carro de Ribeirão Preto em direção a Franca, a uma velocidade constante de 110 km/h e o caminhão de Franca em direção a Ribeirão Preto a uma velocidade constante de 80 km/h. Quando eles se cruzarem na rodovia, qual estará mais próximo a cidade de Ribeirão Preto? 

IMPORTANTE: 

a) Considerar a distância de 100km entre a cidade de Ribeirão Preto <-> Franca. 

b) Considerar 2 pedágios como obstáculo e que o caminhão leva 5 minutos a mais para passar em cada um deles e o carro possui tag de pedágio (Sem Parar)

R: é necessário calcular o ponto exato em que o carro e o caminhão se encontram. Sabendo que a distância entre Ribeirão Preto e Franca é de 100 km, e que os dois veículos estão se movendo em direções opostas, a distância total que eles percorrem até se encontrarem será de 100 km.

Para calcular o tempo que cada veículo leva até se encontrar, podemos utilizar a fórmula:

tempo = distância / velocidade

Para o carro, temos:

tempo do carro = distância até o encontro / velocidade do carro
tempo do carro = 50 km / 110 km/h
tempo do carro = 0,45 h (ou 27 minutos)

Para o caminhão, temos:

tempo do caminhão = distância até o encontro / velocidade do caminhão
tempo do caminhão = 50 km / 80 km/h
tempo do caminhão = 0,625 h (ou 37,5 minutos)

Sabendo que o caminhão leva 5 minutos a mais em cada um dos dois pedágios, podemos adicionar esse tempo ao tempo total do caminhão. Portanto, o tempo total do caminhão será:

tempo total do caminhão = tempo do caminhão + (2 x 5 minutos)
tempo total do caminhão = 0,625 h + 0,1 h
tempo total do caminhão = 0,725 h (ou 43,5 minutos)

Agora que temos o tempo total de cada veículo, podemos calcular a distância percorrida por cada um. Para o carro, a distância percorrida será:

distância percorrida pelo carro = velocidade do carro x tempo do carro
distância percorrida pelo carro = 110 km/h x 0,45 h
distância percorrida pelo carro = 49,5 km

Para o caminhão, a distância percorrida será:

distância percorrida pelo caminhão = velocidade do caminhão x tempo total do caminhão
distância percorrida pelo caminhão = 80 km/h x 0,725 h
distância percorrida pelo caminhão = 58 km

Agora, podemos calcular a distância de cada veículo até Ribeirão Preto. Para o carro, a distância até Ribeirão Preto será:

distância do carro até Ribeirão Preto = distância de Ribeirão Preto a Franca - distância percorrida pelo carro
distância do carro até Ribeirão Preto = 100 km - 49,5 km
distância do carro até Ribeirão Preto = 50,5 km

Para o caminhão, a distância até Ribeirão Preto será:

distância do caminhão até Ribeirão Preto = distância percorrida pelo caminhão
distância do caminhão até Ribeirão Preto = 58 km

Portanto, quando os veículos se cruzarem na rodovia, o carro estará mais próximo da cidade de Ribeirão Preto, a uma distância de 50,5 km, enquanto o caminhão estará a uma distância de 58 km.
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------

5) Escreva um programa que inverta os caracteres de um string. 

IMPORTANTE: 

a) Essa string pode ser informada através de qualquer entrada de sua preferência ou pode ser previamente definida no código; 

b) Evite usar funções prontas, como, por exemplo, reverse; 

NÃO SE ESQUEÇA DE INSERIR O LINK DO SEU REPOSITÓRIO NO GITHUB COM O CÓDIGO FONTE QUE VOCÊ DESENVOLVEU.

string_original = input("Digite uma string para ser invertida: ")
string_invertida = ""

for i in range(len(string_original)-1, -1, -1):
    string_invertida += string_original[i]

print("String invertida: " + string_invertida)


a string original é recebida como entrada do usuário através da função input(). Em seguida, a variável string_invertida é inicializada como uma string vazia.

O laço for percorre a string original do final para o início, utilizando a função range() com os parâmetros len(string_original)-1 (para começar no índice final da string), -1 (para terminar no índice 0) e -1 (para percorrer de trás para frente).

A cada iteração do laço, o caractere da posição atual é concatenado na variável string_invertida utilizando o operador +=.

Por fim, a string invertida é impressa na tela junto com uma mensagem explicativa.

Exemplo mais simples:

1-Receber a string como entrada do usuário ou definir previamente no código;
2-Criar uma nova string vazia;
3-Percorrer a string original do final para o início e concatenar cada caractere na nova string;
4-Imprimir a nova string com os caracteres invertidos.

