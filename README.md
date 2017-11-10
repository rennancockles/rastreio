# Rastreio

Script em python para rastrear objetos dos correios

&nbsp;

## Exemplos

Com um código

`rastreio -c PO938188265BR`


Com mais de um código

`rastreio -c PO938188265BR,PO919443331BR`


Obtendo códigos de um arquivo (um código por linha)

`rastreio -f caminho/para/arquivo`


Obtendo códigos de um arquivo e removendo os códigos dos objetos que já foram entregues

`rastreio -f caminho/para/arquivo --auto-remove`


Exportando o resultado para um arquivo texto comum

`rastreio -c PO938188265BR -o saida`


Exportando o resultado para um arquivo html

`rastreio -c PO938188265BR -o saida.html`

&nbsp;

![DFU MODE](https://image.ibb.co/dQc03G/rastr.jpg)
