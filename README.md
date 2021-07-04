# lista-de-convidados
Esse projeto é uma lista bem simples de convidados, onde o objetivo era apenas realizar cadastros de convidados em um determinando evento. Esse projeto foi proposto pelo o curso Dev Samurai, onde apenas era para implementar o cadastro dos nomes dos convidados, porém, dei uma incrementada colocando o cadastro de CPF e estilizei o sistema com um toque de CSS.

# Apresentação do Sistema
Esse é o layout do sistema, nele está contido os campos nome, cpf e o botão de cadastrar. Até então esse projeto não tinha nenhum estilo implementado, optei por fazer isso e coloquei cores e sombras.
<p align="center">
  <img src="https://user-images.githubusercontent.com/62810095/124394032-deda7100-dcd3-11eb-8ba2-22fa5d8abc3d.PNG"
</p>

## Cadastrando Convidados
Demonstrativo de como é a exibição do convidado cadastrado na lista. Temos o botão excluir, caso deseja remover algum convidado da lista. Esse botão é exibido somente quando se faz o cadastro.
<p align="center">
  <img src="https://user-images.githubusercontent.com/62810095/124394303-50ff8580-dcd5-11eb-9e7b-bbef87ec2e37.PNG"
</p>

## Excluindo Convidados
Adicionei mais um convidado para poder mostrar a exclusão. No caso irei excluir o convidado "Joãozinho Santos".
<p align="center">
  <img src="https://user-images.githubusercontent.com/62810095/124394788-4d6cfe00-dcd7-11eb-910f-a6efaa9cdfdc.PNG"
</p>

Após excluir o convidado "Joãozinho Santos".
<p align="center">
  <img src="https://user-images.githubusercontent.com/62810095/124395039-57433100-dcd8-11eb-956f-ca56af426953.PNG"
</p>

# Alguns detalhes do Projeto
Esse projeto armazena os dados dos convidados diretamente no browser, utilizando esse comando:
<p align="center">
  <img src="https://user-images.githubusercontent.com/62810095/124395321-d9802500-dcd9-11eb-98b7-2dd1c692ba0b.PNG"
</p>

O <b>localStorage</b> só grava em strings, então precisamos transformar esse objeto em uma string, com isso, optamos utilzar o <b>JSON.stringify</b>.

Outro detalhe que vale ressaltar é que, como se trata de um armazenamento no browser, ao cadastrar ou excluir os convidados e nós mudarmos de navegador ou máquina, ele não irá salvar os dados. Então é importante que nesse projeto utilize o mesmo navegador para poder armazenar os dados e ter o resultado esperado.
