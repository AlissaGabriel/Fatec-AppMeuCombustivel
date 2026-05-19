# Calculadora de Combustível - .NET MAUI

## Sobre o Projeto

Este aplicativo foi desenvolvido utilizando .NET MAUI com o objetivo de calcular qual combustível compensa mais: Etanol ou Gasolina.

O usuário informa:

* Preço do Etanol
* Preço da Gasolina

Ao clicar no botão **Calcular**, o aplicativo:

1. Compara os valores informados
2. Realiza o cálculo da proporção entre os combustíveis
3. Exibe qual combustível possui melhor custo-benefício

---

## Conteúdos Aprendidos

Durante o desenvolvimento deste projeto foram aprendidos os seguintes conceitos:

### Interface gráfica com XAML

Uso de componentes como:

* Label
* Entry
* Button
* StackLayout

### Programação em C#

* Conversão de texto para número (`Convert.ToDouble`)
* Estruturas condicionais (`if`, `else`)
* Manipulação de eventos
* Variáveis e operações matemáticas

### Desenvolvimento Mobile com .NET MAUI

* Criação de páginas
* Associação entre XAML e código C#
* Exibição de mensagens usando `DisplayAlert`

---

## Regra Utilizada

O cálculo é realizado utilizando a seguinte regra:

Se o preço do Etanol for maior que 70% do valor da Gasolina, compensa abastecer com Gasolina. Caso contrário, compensa utilizar Etanol.

---

## Funcionamento do Aplicativo

* O usuário digita os preços dos combustíveis
* O sistema compara os valores
* O aplicativo informa qual combustível é mais vantajoso

---

## Como Executar o Projeto

1. Clone o repositório
2. Abra o projeto no Visual Studio 2026
3. Execute o projeto em um emulador Android ou Windows

---

## Estrutura do Projeto

* `MainPage.xaml` → Interface do aplicativo
* `MainPage.xaml.cs` → Lógica do cálculo dos combustíveis

---

Projeto desenvolvido para a disciplina de Programação para Dispositivos Móveis II com .NET MAUI.
