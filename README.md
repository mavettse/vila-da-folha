# vila-da-folha

Este é um projeto de aplicação desktop desenvolvido em **Java** para gerenciamento de **Moradores** (Ninjas e Civis) e **Missões**, simulando uma estrutura de gestão de aldeia, como a Vila da Folha.

O sistema adota a arquitetura **MVC** (Model-View-Controller) e utiliza a persistência de dados em arquivos **CSV**.

---

## Funcionalidades Principais

*	**Gerenciamento de Moradores:** Cadastro, listagem, edição e remoção de Ninjas e Civis.
*	**Gerenciamento de Missões:** Criação de missões com diferentes níveis, atribuição a ninjas e atualização de status (pendente, em andamento, concluída).
*	**Persistência de Dados:** Os dados de moradores e missões são salvos em arquivos CSV (`moradores.csv` e `missoes.csv`).
*	**Interface Gráfica:** Aplicação com interface de usuário desenvolvida utilizando **Java Swing/AWT**.

---

## Tecnologias Utilizadas

*	**Linguagem de Programação:** Java
*	**Arquitetura:** MVC (Model-View-Controller)
*	**Interface Gráfica:** Java Swing/AWT
*	**Persistência:** DAO (Data Access Object) para manipulação de arquivos CSV

---

## Estrutura do Projeto

O código-fonte segue a separação de responsabilidades da arquitetura MVC:

*	**[`src/principal/model`](`src/principal/model`)**: Classes de entidade (`Morador`, `Ninja`, `Civil`, `Missao`) e enums.
*	**[`src/principal/view`](`src/principal/view`)**: Classes de interface gráfica (`Janela`, `DialogAdicionarMorador`, `DialogAdicionarMissao`).
*	**[`src/principal/controller`](`src/principal/controller`)**: Classe `Controller` para a lógica de aplicação.
*	**[`src/principal/dao`](`src/principal/dao`)**: Classes de acesso a dados (`MoradorDAO`, `MissaoDAO`) para interação com os arquivos CSV.
*	**[`src/principal/App.java`](`src/principal/App.java`)**: Ponto de entrada da aplicação.

---

## Como Executar o Projeto

### Pré-requisitos

Certifique-se de ter o **Java Development Kit (JDK)** instalado (versão 8 ou superior).

### Execução

A maneira mais prática é importar o projeto em uma **IDE** (como IntelliJ IDEA ou Eclipse) e executar a classe principal:

1.	**Importe** a pasta do projeto para sua IDE.
2.	**Localize** a classe `principal.App`.
3.	**Execute** o método `main` da classe `principal.App`.

*(Alternativamente, a compilação e execução podem ser feitas via terminal, garantindo que todas as classes estejam no classpath.)*

---

## Autores

* **Giovanni Estevam** - [GitHub](https://github.com/mavettse)
* **Wescley Júnior** - [GitHub](https://github.com/wescleyj)
* **João Vitor Lopes** - [GitHub](https://github.com/joaovitorf4)

---
*Projeto desenvolvido para fins acadêmicos - Engenharia da Computação / 2025.*
