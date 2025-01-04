# trab
O que fizemos:
Mudamos a ordem dos elementos no HTML: O #main agora vem antes do #sidebar no código. Isso é importante porque o #main vai flutuar para a esquerda, então ele precisa aparecer primeiro para garantir que ocupe o espaço maior na tela. O #sidebar vai ficar ao lado do #main.

Fizemos o #main flutuar à esquerda: Colocamos o float: left no #main. Isso faz com que o conteúdo do #main se alinhe à esquerda da página, ocupando a maior parte da largura. A largura dele foi definida como 650px (ele vai ocupar esse espaço).

Tiramos a flutuação do #sidebar: Antes, o #sidebar estava flutuando à direita, mas agora, para que ele fique ao lado do #main, retiramos o float dele. Então ele vai se alinhar automaticamente abaixo do #main, mas com uma margem à esquerda que vamos definir para que ele fique alinhado corretamente.

Calculamos a margem do #sidebar: O #sidebar precisa de um espaço à esquerda para ficar ao lado do #main. Como o #main tem 650px de largura, colocamos a margem esquerda do #sidebar como 660px. Isso faz com que o #sidebar comece exatamente onde termina o #main.

O rodapé: Para garantir que o rodapé (o #footer) fique abaixo de ambos os elementos (o #main e o #sidebar), colocamos a propriedade clear: both; no #footer. Isso garante que ele não seja sobreposto ou se misture com os outros elementos flutuantes.
