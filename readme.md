Gerador de Assinaturas .PNG
===========

Este projeto basicamente implementa uma página em que os funcionários de determinada empresa
podem criar suas assinaturas de e-mail. Após o preenchimento do formulário a assinatura pode ser baixada
no formato png.


![Alt text](http://i.imgur.com/WfoRaI1.png "Gerador de Assinaturas")

#### Como funciona? ####

O arquivo Index.html implementa o formulário. Os valores são recebidos e posicionados sobrepondo a imagem Template.png (via css), em seguinda o script [Html2canvas](http://html2canvas.hertzen.com) se encarrega
de tirar uma espécie de screenshot do elemento html que contem a assinatura. 
Esses elementos html são escondidos e apenas a imagem é mostrada.

#### Como usar? ####
Se você desejar implementar este projeto, basta alterar as imagens logo.png e template.png que estão no diretório raiz e talvez alterar os dados no formulário (index.html) para incluir determinada informação.
