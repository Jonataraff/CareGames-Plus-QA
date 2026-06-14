CareGames+ | Quality Assurance
Sobre o Projeto

O CareGames+ é um aplicativo mobile desenvolvido com React Native, Expo e Expo Router, criado para incentivar hábitos saudáveis por meio da gamificação.

A plataforma permite que os usuários acompanhem seu progresso, participem de desafios, acumulem pontos, visualizem rankings competitivos e resgatem benefícios de acordo com seu desempenho.

Além disso, o aplicativo conta com integração com dispositivos wearables, persistência de dados utilizando AsyncStorage e recursos voltados ao bem-estar e à saúde dos usuários.

Objetivo da Atividade

Este projeto foi utilizado como estudo de caso para aplicação dos conceitos de Quality Assurance (QA), contemplando:

Planejamento de testes;
Gestão de backlog;
Criação de Épicos, Features, PBIs e Tasks;
Criação de casos de teste;
Execução de testes manuais;
Execução de testes automatizados;
Rastreabilidade entre requisitos e testes;
Utilização do Azure DevOps para gerenciamento do projeto.
Integrantes
Nome	RM
Vinicius Silva	RM553240
Victor Didoff	RM552965
Matheus Zottiz	RM94119
Diogo Julio	RM553837
Jonata Rafael	RM552939
Tecnologias Utilizadas
Categoria	Tecnologia
Front-end Mobile	React Native
Framework	Expo
Navegação	Expo Router
Linguagem	TypeScript
Persistência	AsyncStorage
Comunicação em Tempo Real	WebSocket
Gestão Ágil	Azure DevOps
Automação de Testes	Katalon Studio
Ambiente de Testes	Android Emulator
Funcionalidades Validadas
Autenticação
Cadastro de usuários
Login
Persistência de sessão
Perfil
Visualização de perfil
Upload de foto
Persistência de informações
Gamificação
Sistema de desafios
Acúmulo de pontos
Ranking de usuários
Benefícios
Consulta de benefícios
Resgate de recompensas
Configurações
Alteração de tema
Persistência de preferências
Integração IoT
Comunicação com wearables
Atualização de dados em tempo real
Casos de Teste Implementados
Código	Caso de Teste
TC01	Cadastro válido de usuário
TC02	Cadastro inválido
TC03	Login válido
TC04	Login inválido
TC05	Upload de foto de perfil
TC06	Alteração de tema
TC07	Conclusão de desafio
TC08	Visualização de ranking
TC09	Resgate de benefício
TC10	Integração com wearable
Testes Automatizados

Foram implementados testes automatizados contemplando os principais fluxos da aplicação:

Cadastro de usuário
Login
Alteração de tema
Resgate de benefícios

Os testes foram executados utilizando Katalon Studio em ambiente Android.

Azure DevOps

Gerenciamento do backlog, planejamento e rastreabilidade dos testes:

https://dev.azure.com/RM553240/Care-Games-Plus-Project/_workitems/recentlyupdated/

Vídeo de Demonstração

Execução dos testes automatizados:

https://youtu.be/U705FTcsAQQ

Estrutura de Gerenciamento
Epic
 └── Feature
      └── Product Backlog Item (PBI)
           └── Task

Product Backlog Item
 └── Test Case
Considerações Finais

O projeto permitiu aplicar na prática conceitos relacionados a planejamento, rastreabilidade, testes manuais, automação de testes e metodologias ágeis, utilizando ferramentas amplamente empregadas no mercado de desenvolvimento de software.