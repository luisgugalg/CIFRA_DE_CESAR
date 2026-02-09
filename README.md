# CIFRA_DE_CESAR
Descrição:
A Cifra de César é um dos algoritmos de criptografia mais antigos.
A ideia é simples: cada letra do texto é deslocada um certo número de posições no alfabeto.

Por exemplo, com deslocamento de 3:

"A" vira "D"
"B" vira "E"
"Z" volta para o início e vira "C"
Você deverá implementar duas funções que codifiquem e decodifiquem mensagens usando a cifra de César.

Comando:

Implemente a função codificar_cesar(texto: str, deslocamento: int) -> str que deve receber uma mensagem e retornar o texto codificado.
Implemente a função decodificar_cesar(texto: str, deslocamento: int) -> str que deve receber um texto cifrado e retornar a mensagem original.
Necessidades:

Considere apenas letras do alfabeto (maiúsculas e minúsculas devem ser preservadas).
Espaços, números e pontuações devem permanecer inalterados.
O deslocamento pode ser qualquer número inteiro positivo.

Exemplo de uso esperado:

Entrada: codificar_cesar("Ola Mundo!", 3)

Saída esperada: "Rod Pxqgr!"
Entrada: decodificar_cesar("Rod Pxqgr!", 3)

Saída esperada: "Ola Mundo!"
