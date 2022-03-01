# Melhor quarteirão do meu bairro
Project in which I found the best block in my neighbourhood

https://medium.com/@pedropatricio7/melhor-quarteir%C3%A3o-do-meu-bairro-2e6a890af0fa

Quando eu era adolescente, e andava bastante de ônibus por aí, percebia que o bairro onde morava, o Prado (em BH), tinha boa acessibilidade a diversas linhas de ônibus que me levariam para qualquer lugar da cidade que quisesse. Naquela época, havia feito uma estimativa de cabeça que o quarteirão da minha avó era o melhor do bairro, pois teria acesso a todos os diferentes tipos de ônibus, além de ficar numa rua tranquila e arborizada. Hoje, mais de uma década depois, tenho os meios técnicos de tentar avaliar isso.

O Prado começa, para quem conhece bem BH, na esquina entre as Av. Amazonas e Av. do Contorno. Também é delimitado pela Av. Tereza Cristina e a Av. Silva Lobo. Ou seja, fica entre três das principais avenidas da cidade. Dentro dele também tem a Rua Platina, também importante. Voltarei a essas vias mais a frente.

Vamos lá. O objetivo é quantificar a localidade com menor distância para os pontos de ônibus que atendem ao bairro. Para isso, vou usar dados disponibilizados pela Prefeitura de BH no site BH Map (http://bhmap.pbh.gov.br/v2/mapa/idebhgeo). Utilizei a quadra como unidade de análise para facilitar. Depois, peguei todos os pontos de ônibus que passam dentro ou nas imediações do Prado. Por fim, estimaria a distância de cada quadra para cada ponto de uma linha de ônibus que estivesse mais próximo. A quadra com menor média de distância é a com melhor acessibilidade.

No entanto, percebi que se fizesse isso para todas as linhas, geraria um viés para as quadras próximas da Av. Amazonas, pois lá passam um grande volume de linhas de ônibus. Portanto, decidi dividir em 4 categorias: os ônibus da Av. Amazonas; os ônibus da Av. do Contorno; os ônibus da Rua Platina e; os ônibus que passam por dentro do bairro (as linhas 2103 e 9210). Como eu conheço bem o bairro, sei que os ônibus que passam na Av. do Contorno costumam levar a lugares semelhantes, mas diferentes dos ônibus que passam na Av. Amazonas. No mapa a seguir, dá para ver todos os pontos de ônibus, divididos nas 4 categorias pelos símbolos em vermelho.

Agora é possível calcular a distância de cada quadra para o ponto mais próximo de cada categoria. Tirei a média das 4 distâncias, classifiquei em 4 categorias e apresento no mapa a seguir. Quanto mais escuro, melhor é a acessibilidade da quadra às categorias de ônibus.

![prado2](https://user-images.githubusercontent.com/67980930/156225913-48351675-ee42-4d9f-9b56-0ff9fa3c7d36.png)

Como é possível ver, as quadras mais próximas das Av. Amazonas e Av. do Contorno são as melhores, segundo esse critério. Isto é, o quarteirão da minha avó não era o melhor. Porém, não estava satisfeito. Além do acesso aos ônibus, uma das coisas que me fazia pensar no quarteirão dela como ótimo era por conta da tranquilidade dele. Então decidi adicionar a esse exercício a distância para as avenidas. Isto é, o quarteirão perfeito para mim é aquele onde eu pudesse chegar nas linhas de ônibus, mas também estivesse longe o suficiente do trânsito. O resultado das novas categorias estão no mapa a seguir. Detalhe que agora pode ter valores negativos, pois a distância para as avenidas entra com valor negativo. Dei o nome de "índice de distância". A intuição segue a mesma, quanto menor o valor para a quadra, melhor.

![prado3](https://user-images.githubusercontent.com/67980930/156225962-09ec9ced-5977-464d-bf48-bf70c08d1934.png)

Assim já começou a se aproximar do que eu imaginava. A melhor região do Prado, dentro desses quesitos que defini, de fato é o meio dele, ao longo da Rua Turquesa, outra rua importante. Mas isso é quase que óbvio, dado que coloque a distância para as avenidas e as categorias de ônibus, que também estão nas grandes vias. O objetivo é encontrar a MELHOR quadra. Verificando as duas melhores, tenho o seguinte resultado:

![prado4](https://user-images.githubusercontent.com/67980930/156226008-dee6251f-c79c-4c95-9ac2-b57281b4f18c.png)

O trecho que está entre essas duas quadras é a Rua Safira, esquina com as ruas Turquesa e Nepomuceno. Infelizmente, não é a rua da minha avó. Mas a dela está a apenas dois quarteirões abaixo. Bem, não estava certo aos 17 anos, mas valeu ter feito essa brincadeira.
