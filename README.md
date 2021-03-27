:spiral_calendar: Atualizado em 27 de Março de 2021 :heart:

<img align="right" alt="GIF" height="160px" src="https://github.com/rdeconti/rdeconti-resources/blob/main/Digital%20Innovation%20One%20-%20Logotipo.png" />

# Projeto Digital Innovation One: Bootcamp Impulso FullStack Developer 

# Gerenciador de esferas do Dragon BallZ

Crie um gerenciador de esferas do Dragon BallZ usando ReactJS, Jest, React Testing Library e Cypress
Este projeto foi proposto pela Digital Innovation One - Link do código original da Laís Lima: https://github.com/lalizita/dragon-ball-manager-challenge

Aula: https://web.digitalinnovation.one/lab/crie-um-gerenciador-de-esferas-do-dragon-ballz-usando-reactjs-jest-react-testing-library-e-cypress/learning/817b0285-7dd2-420f-90c9-a839849eed42

# Descrição

Neste Labs você irá construir uma aplicação para gerenciar as esferas do dragão e validar se podemos invocar o Shenlong. Entretanto é preciso garantir a qualidade do software e que ele não tenha falhas. A aplicação será em React e usaremos o react testing library, jest e Cypress, que são ferramentas de testes essenciais para resolver esse problema, garanto que depois de conhecê-las não irá conseguir ficar sem!

# Sugestões feitas pela Laís

- Finalizar os testes e documentar no README;
- React-Test Libray está configurado e o Cypress deve ser instalado e configurado
- Fez tudo "mokado" e tem que fazer "umas coisas no front-end" para funcionar
- Validar campo de "código de esferas" (quando o código é válido = ganhar esfera)
- Tem o Filtro de esferas que pode ser útil em outras aplicações
- Para invocar o "Shenlong" utilizou variável de ambiente globais" - Package-Json Scripts
- O objetivo é escrever testes para os componentes
- Recomendado entender bem o "DOM"
- Ferramenta: API Testing Library (Funciona sem o JEST / Simula o navegador)
- Cypress (Custoso para a empresa), simula um usuário na máquina)
- Teste de renderização
- Manter os testes próximos ao componentes (não criar pasta para testes)
- Utilizar o yarn jest (nome do compoente) para realizar o teste
- Utilizar o DEBUG ao invés do console.log (const = {debug})
- Utilizar o SNAPSHOT (para "fotografar" os testes)

# Executar estes passos

- yarn
- yarn start
- yarn add -D cypress
- yarn cy:run
- yarn run cypress open

# Instalação YARN

<p align="center"> <img src="/Screen-documentation/Yarn install.jpg"> </p>

# Telas da aplicação
<p align="center"> <img src="/Screen-documentation/Application - screen number 1.jpg"> </p>
<p align="center"> <img src="/Screen-documentation/Application - screen number 2.jpg"> </p>
<p align="center"> <img src="/Screen-documentation/Application - screen number 3.jpg"> </p>
<p align="center"> <img src="/Screen-documentation/Application - screen number 4.jpg"> </p>

# Testes executados com Cypress

### Sem invocar Shenlong

<p align="center"> <img src="/Screen-documentation/Cypress - testing shenlong invocation 1.png"> </p>

### Invocando Shenlong

<p align="center"> <img src="/Screen-documentation/Cypress - testing shenlong invocation 2.png"> </p>
