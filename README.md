# Projeto Estacionamento DIO

Esse projeto foi desenvolvido para o bootcamp DecolaTech 2024 da AVANADE ministrado através da plataforma DIGITAL INNOVATION ONE (DIO).

A aplicação busca simular o funcionamento de uma API de cobrança de um estacionamento, calculando o preço por hora e registrando veículos através de uma String que representa a sua placa, além de oferecer uma interface na CLI, tornando o projeto interativo.

O arquivo do projeto pode ser encontrado em ```models/Estacionamento.cs```. 

A tecnologias utilizadas foram o C#, utilizando-se do .NET CORE e utilizando a IDE VSCode para seu desenvolvimento.

#Estrutura

Diagrama de classe estacionamento
A classe contém três variáveis, sendo:

precoInicial: Tipo decimal. É o preço cobrado para deixar seu veículo estacionado.

precoPorHora: Tipo decimal. É o preço por hora que o veículo permanecer estacionado.

veiculos: É uma lista de string, representando uma coleção de veículos estacionados. Contém apenas a placa do veículo.

A classe contém três métodos, sendo:

AdicionarVeiculo: Método responsável por receber uma placa digitada pelo usuário e guardar na variável veiculos.

RemoverVeiculo: Método responsável por verificar se um determinado veículo está estacionado, e caso positivo, irá pedir a quantidade de horas que ele permaneceu no estacionamento. Após isso, realiza o seguinte cálculo: precoInicial * precoPorHora, exibindo para o usuário.

ListarVeiculos: Lista todos os veículos presentes atualmente no estacionamento. Caso não haja nenhum, exibir a mensagem "Não há veículos estacionados".

Por último, deverá ser feito um menu interativo com as seguintes ações implementadas:

Cadastrar veículo
Remover veículo
Listar veículos
Encerrar
Solução
