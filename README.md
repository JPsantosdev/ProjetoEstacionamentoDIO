# Projeto Estacionamento DIO

Esse projeto foi desenvolvido para o bootcamp DecolaTech 2024 da AVANADE ministrado através da plataforma DIGITAL INNOVATION ONE (DIO).

A aplicação busca simular o funcionamento de uma API de cobrança de um estacionamento, calculando o preço por hora e registrando veículos através de uma String que representa a sua placa, além de oferecer uma interface na CLI, tornando o projeto interativo.

O arquivo do projeto pode ser encontrado em ```models/Estacionamento.cs```. 

A tecnologias utilizadas foram o C#, utilizando-se do .NET CORE e utilizando a IDE VSCode para seu desenvolvimento.

Este projeto não utiliza uma camada de Modelo para desenvolvimento do objeto "carro", embora seja altamente recomendável para um projeto mais amplo e que segue as boas práticas de desenvolvimento.

Em um projeto mais compexo, o objeto seria desenvolvido com a seguinte estrutura:
```
Carro {
modelo: String,
vaga_estacionada: String,
horario_de_entrada: DateTime,
horario_de_saida: DateTime
}  
