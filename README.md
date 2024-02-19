# Aplicativo Java utilizando Lambdas e Streams

Este é um pequeno aplicativo Java que demonstra o uso de lambdas e streams para filtrar uma lista de pessoas com base no sexo. Ele foi criado como parte de uma atividade para exercitar o uso desses recursos da linguagem Java.

## Funcionalidades

O aplicativo inclui as seguintes funcionalidades:

1. **População de Pessoas**: Uma lista de pessoas é criada no método `populaPessoas()` na classe `AppStreams`. Cada pessoa tem um nome, sexo e idade associados.
2. **Filtragem de Pessoas do Sexo Feminino**: Utilizando streams e lambdas, o aplicativo filtra a lista de pessoas, selecionando apenas aquelas do sexo feminino.
3. **Exibição das Listas**: As listas completa e filtrada são impressas no console para visualização.

## Como usar

1. Clone ou baixe o repositório para o seu ambiente local.
2. Abra o projeto em um ambiente de desenvolvimento Java compatível (por exemplo, IntelliJ IDEA, Eclipse, etc.).
3. Execute a classe `AppStreams.java`.

## Exemplo de Saída

A saída do programa irá mostrar a lista completa de pessoas, seguida pela lista apenas com pessoas do sexo feminino.

```
****** LISTA COMPLETA ******
Pessoa{nome='Vinícius', sexo='Masculino'}
Pessoa{nome='Carolina Martins', sexo='Feminino'}
Pessoa{nome='Maria Silva', sexo='Feminino'}
Pessoa{nome='João Santos', sexo='Masculino'}
Pessoa{nome='Ana Oliveira', sexo='Feminino'}
Pessoa{nome='Pedro Almeida', sexo='Masculino'}
****** LISTA SEXO FEM ******
Pessoa{nome='Carolina Martins', sexo='Feminino'}
Pessoa{nome='Maria Silva', sexo='Feminino'}
Pessoa{nome='Ana Oliveira', sexo='Feminino'}
```

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir problemas (issues) ou enviar um pull request com melhorias.

---
Este projeto é apenas um exercício educacional para praticar o uso de lambdas e streams em Java.
