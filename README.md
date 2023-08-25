# caeser_cipher
Practicing Python


Caesar Cipher em Python

Descrição
Este programa é uma implementação simples e interativa da Cifra de César em Python. A Cifra de César é uma das técnicas de cifragem mais antigas e conhecidas. É um tipo de cifra de substituição em que cada letra do texto original é deslocada um certo número de posições no alfabeto.

Por exemplo, com um deslocamento de 3, a letra "A" seria substituída pela letra "D", a letra "B" seria substituída pela letra "E", e assim por diante.

Como Usar
Ao executar o programa, o usuário será solicitado a fornecer uma mensagem que deseja cifrar. Em seguida, o programa solicitará um deslocamento (offset), que é o número de posições que cada letra da mensagem original deve ser movida no alfabeto para produzir a mensagem cifrada.

Após inserir a mensagem e o deslocamento, o programa irá exibir a mensagem cifrada correspondente.

Exemplo
Mensagem: hello
Deslocamento: 3
Mensagem Cifrada: khoor

Detalhes Técnicos
O programa define uma função caesar_cipher que aceita uma mensagem e um deslocamento como argumentos. A função itera por cada caractere da mensagem. Se o caractere for uma letra, ele é deslocado pelo valor do deslocamento fornecido (usando operações modulares para lidar com o "wrap-around" do alfabeto). Caracteres não alfabéticos, como pontuação e espaços, são preservados sem alterações.
