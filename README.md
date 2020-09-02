# atalhos

Essa é para quem usa GNU/Linux. Nesses tempos de videochamadas precisamos manter uma janela ativa "sempre no topo" ou desativar essa função.

1. Crie um atalho de teclado para deixar sempre no topo com este comando:
wmctrl -r :ACTIVE: -b toggle,above

2. Para remover a marcação use:
wmctrl -r :ACTIVE: -b remove,above

Em (1) deixei Alt + 1 e em (2) Alt + 2.

Dica extra: Para fazer anotações instale o Gromit-MPX. Com F9 ele aciona (ou desliga) e pode anotar por cima de qualquer coisa. Se estiver trabalhando com R fica show de bola. Shift + F9 limpa as anotações.
