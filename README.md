# Sistema de Estacionamento (.NET)

![GitHub repo size](https://img.shields.io/github/repo-size/katyagomes/DesafioFundamentos?style=for-the-badge)
![GitHub language count](https://img.shields.io/github/languages/count/katyagomes/DesafioFundamentos?style=for-the-badge)
![GitHub forks](https://img.shields.io/github/forks/katyagomes/DesafioFundamentos?style=for-the-badge)
![Bitbucket open issues](https://img.shields.io/bitbucket/issues/katyagomes/DesafioFundamentos?style=for-the-badge)
![Bitbucket open pull requests](https://img.shields.io/bitbucket/pr-raw/katyagomes/DesafioFundamentos?style=for-the-badge)

> Projeto desenvolvido como parte do desafio da trilha de **Fundamentos de .NET** da **Digital Innovation One (DIO)**.

## Sobre o Projeto

Este projeto consiste em um sistema construído em C# para gerenciar os veículos estacionados e realizar operações básicas de um estacionamento. O programa foi desenvolvido para aplicar conhecimentos de lógica de programação, manipulação de listas e sintaxe do C#.

## Funcionalidades

O sistema conta com um menu interativo que permite:

- [x] **Cadastrar Veículo:** Recebe a placa do veículo e o adiciona à lista.
- [x] **Listar Veículos:** Exibe todos os veículos atualmente estacionados.
- [x] **Remover Veículo:** Verifica se o veículo existe, calcula o valor a ser cobrado com base no tempo de permanência e remove o veículo da lista.

## Regra de Negócio

O cálculo do valor a ser cobrado segue a seguinte lógica:

$$Total = PrecoInicial + (PrecoPorHora * HorasPermanecidas)$$

**Exemplo:**
- Preço Inicial: R$ 5,00
- Preço por Hora: R$ 2,00
- Tempo estacionado: 3 horas
- **Total:** 5 + (2 * 3) = **R$ 11,00**

## Estrutura do Projeto

O projeto está organizado da seguinte forma:

```text
DesafioFundamentos/
├── Models/
│   └── Estacionamento.cs   # Classe com a lógica principal
├── Program.cs              # Ponto de entrada e menu interativo
├── DesafioFundamentos.csproj
└── README.md
```
## Como Executar

### Pré-requisitos

Certifique-se de ter o **[.NET SDK](https://dotnet.microsoft.com/download)** instalado em sua máquina (versão 6.0 ou superior).

### Passo a passo

1. **Clone o repositório:**
   ```bash
   git clone (https://github.com/katyagomes/DesafioFundamentos)
   ```
2. **Navegue até a pasta do projeto:**
   ```bash
   cd DesafioFundamentos
   ```
3. **Execute o programa:**
   ```bash
   dotnet run
   ```
## Tecnologias Utilizadas

* **C#** - Linguagem de programação.
* **.NET** - Framework de desenvolvimento.
* **Git & GitHub** - Versionamento de código.

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues e pull requests.

## Licença

Este projeto está sob a licença MIT.
