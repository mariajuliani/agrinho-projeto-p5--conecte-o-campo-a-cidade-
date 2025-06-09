Como o projeto funciona:
Cenário Inicial:

O ambiente é uma tela de 600x400px.

A cidade está posicionada em (550, 100) e o campo em (50, 300).

O campo e a cidade são representados por quadrados de cores diferentes.

Árvores aleatórias são colocadas no cenário (8 árvores), com posições variando entre (100, 500) no eixo X e (100, 350) no eixo Y.

Interação:

O usuário desenha um caminho com o mouse, e esse caminho vai se acumulando no array path (ou seja, o mouse arrasta a linha e ela é registrada como pontos).

O caminho é desenhado no quadro, começando onde o usuário arrasta o mouse.

Objetivo:

O usuário deve tentar conectar o campo à cidade sem tocar nas árvores. Para isso, ele precisa desenhar um caminho que passe de um ponto a outro sem colidir com os círculos verdes (as árvores).

Verificação:

O código verifica, a cada movimento, se o usuário desenhou o caminho até a cidade e se, ao longo do caminho, houve colisão com alguma árvore.

Quando o mouse se aproxima da cidade (distância menor que 50 pixels), o jogo checa se o caminho tocou nas árvores:

Se o caminho tocar nas árvores, o fundo da tela fica vermelho e uma mensagem de "Você danificou a natureza!" é exibida.

Se o caminho não tocar nas árvores, o fundo fica verde e a mensagem "Conexão Sustentável!" aparece.

Resumo do Objetivo:
Objetivo do jogo: Criar um caminho sustentável, ou seja, ligar o campo à cidade sem prejudicar as árvores. A mecânica do jogo desafia o jogador a pensar na melhor forma de evitar as árvores, como se fosse um exercício de preservação ambiental em um cenário virtual.

Essa ideia de conectar elementos do ambiente (campo, cidade e árvores) sem prejudicar a natureza sugere uma analogia com a sustentabilidade, onde o jogador precisa buscar soluções criativas e cuidadosas para o desenvolvimento sem causar danos ao meio ambiente.
