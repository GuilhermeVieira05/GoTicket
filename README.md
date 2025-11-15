# GoTicket 🎟️

![Status](https://img.shields.io/badge/status-conclu%C3%ADdo-brightgreen.svg)
![Licença](https://img.shields.io/badge/licen%C3%A7a-MIT-blue.svg)

## 📋 Sobre o Projeto

GoTicket é um projeto de documentação técnica que modela uma plataforma completa de venda e gerenciamento de ingressos. O sistema atua como um marketplace, conectando **Organizadores de Evento** (que publicam e gerenciam) e **Clientes** (que buscam e compram ingressos), com um **Administrador** para moderar a plataforma.

Este repositório centraliza toda a especificação de software e o design de arquitetura do sistema.

## 📚 Modelos & Diagramas Incluídos

A documentação (em formato PDF) cobre todo o ciclo de vida da modelagem do sistema. Todos os diagramas foram gerados a partir de código-fonte (PlantUML) para garantir o versionamento e a manutenção.

### Modelos de Análise (O Quê?)

* **Diagrama de Casos de Uso**: Descreve as funcionalidades do sistema e as interações dos atores (Cliente, Organizador, Admin).
* **Diagrama de Arquitetura**: Mostra a relação entre os Processos de Negócio, Serviços de Aplicação e Componentes de Tecnologia.

### Modelos de Design (Como?)

#### UML Estrutural

* **Diagrama de Classes**: Detalha as entidades do sistema (`Usuario`, `Evento`, `Ingresso`, `Pedido`, etc.) e seus relacionamentos.
* **Diagrama de Componentes**: Ilustra a arquitetura lógica de microsserviços do backend e como eles se conectam.
* **Diagrama de Implantação**: Mostra a arquitetura física (infraestrutura em nuvem) e onde cada componente é executado (deploy).

#### UML Comportamental

* **Diagrama de Sequência**: Demonstra a interação entre os componentes ao longo do tempo para os principais casos de uso (ex: Comprar Ingresso, Validar Check-in).
* **Diagrama de Comunicação**: Foca nos links e mensagens trocadas entre os objetos para realizar os casos de uso.
* **Diagrama de Estados**: Modela o ciclo de vida de objetos-chave, como o `Ingresso` (Disponível -> Vendido -> Utilizado -> Expirado).

### Modelos de Dados

* **Diagrama de Entidade e Relacionamento (DER)**: Apresenta o esquema do banco de dados relacional (tabelas e chaves estrangeiras).

## 🛠️ Ferramentas Utilizadas

* **PlantUML**: Todos os diagramas foram gerados usando a sintaxe de "modelagem como código" do PlantUML.

## 📂 Como Acessar a Documentação

Os arquivos de documentação em PDF e os códigos-fonte dos diagramas (`.puml`) estão disponíveis neste repositório.

1.  Clone o repositório:
    ```bash
    git clone https://github.com/GuilhermeVieira05/GoTicket.git
    ```

2.  Acesse a pasta do projeto:
    ```bash
    cd GoTicket
    ```

3.  Abra o arquivo `Trabalho 2 - Template - Documentação de Projeto.pdf` (ou similar) com seu visualizador preferido.

## 🎯 Objetivo

Este projeto tem como objetivo centralizar toda a documentação técnica do GoTicket, servindo como uma "fonte da verdade" para a arquitetura, fluxos de processos e regras de negócio do sistema.

## 📄 Licença

Este projeto é licenciado sob a Licença MIT.

## ✨ Contribuições

Para sugestões ou melhorias na documentação, sinta-se à vontade para abrir uma *issue* ou *pull request*.
