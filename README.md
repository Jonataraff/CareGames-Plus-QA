# CareGames+ | Quality Assurance

Este repositório documenta o projeto acadêmico de Quality Assurance (QA) para o aplicativo CareGames+, detalhando o planejamento, gerenciamento e execução de testes utilizando Azure DevOps e Katalon Studio.

## Descrição do Projeto

O CareGames+ é um aplicativo mobile desenvolvido com React Native, Expo e Expo Router, concebido para promover hábitos saudáveis através da gamificação. A plataforma permite aos usuários acompanhar sua evolução, participar de desafios, acumular pontos, visualizar rankings competitivos, resgatar benefícios e integrar dispositivos wearables para monitoramento de atividades.

Este repositório foca na documentação das atividades de Quality Assurance, abrangendo planejamento, rastreabilidade, testes manuais e testes automatizados.

## Equipe

A equipe responsável por este projeto é composta por:

| Integrante      | RM       |
|-----------------|----------|
| Vinicius Silva  | RM553240 |
| Victor Didoff   | RM552965 |
| Matheus Zottiz  | RM94119  |
| Diogo Julio     | RM553837 |
| Jonata Rafael   | RM552939 |

## Azure DevOps

Acompanhe o gerenciamento do backlog e dos testes através do Azure Boards:

[Azure Boards](https://dev.azure.com/RM553240/Care-Games-Plus-Project/_workitems/recentlyupdated/)

## Demonstração

Vídeo de execução dos testes automatizados:

[Vídeo de Demonstração](https://youtu.be/U705FTcsAQQ)

## Escopo de Quality Assurance

Durante o projeto, foram realizadas as seguintes atividades de QA:

- Estruturação do Product Backlog
- Criação de Épicos, Features, PBIs e Tasks
- Planejamento de Sprint
- Definição de critérios de aceite
- Criação de casos de teste
- Execução de testes manuais
- Automação de testes
- Rastreabilidade entre requisitos e testes
- Gestão das atividades através do Azure DevOps

## Funcionalidades Avaliadas

As principais funcionalidades do aplicativo CareGames+ avaliadas incluem:

### Autenticação
- Cadastro de usuários
- Login
- Persistência de sessão

### Perfil
- Consulta de informações do usuário
- Upload de foto de perfil

### Configurações
- Alternância entre tema claro e escuro
- Persistência das preferências do usuário

### Gamificação
- Desafios
- Sistema de pontuação
- Ranking de usuários

### Benefícios
- Consulta de benefícios
- Resgate de recompensas

### Wearables
- Integração com dispositivos IoT
- Atualização de dados em tempo real

## Casos de Teste

Os casos de teste desenvolvidos para o projeto são:

| Código | Descrição                   |
|--------|-----------------------------|
| TC01   | Cadastro válido de usuário  |
| TC02   | Cadastro inválido           |
| TC03   | Login válido                |
| TC04   | Login inválido              |
| TC05   | Upload de foto de perfil    |
| TC06   | Alteração de tema           |
| TC07   | Conclusão de desafio        |
| TC08   | Visualização de ranking     |
| TC09   | Resgate de benefício        |
| TC10   | Integração com wearable     |

## Testes Automatizados

Os seguintes fluxos foram automatizados utilizando Katalon Studio em ambiente Android:

- Cadastro de usuário
- Login
- Alteração de tema
- Resgate de benefícios

## Tecnologias Utilizadas

| Categoria                 | Tecnologia       |
|---------------------------|------------------|
| Mobile                    | React Native     |
| Framework                 | Expo             |
| Navegação                 | Expo Router      |
| Linguagem                 | TypeScript       |
| Persistência              | AsyncStorage     |
| Comunicação em Tempo Real | WebSocket        |
| Gestão Ágil               | Azure DevOps     |
| Automação de Testes       | Katalon Studio   |
| Ambiente de Testes        | Android Emulator |




## Objetivo Acadêmico

O objetivo acadêmico deste projeto foi aplicar conceitos de Quality Assurance em um cenário real, empregando práticas de gerenciamento ágil, rastreabilidade de requisitos, testes manuais e automação de testes com ferramentas de mercado.
