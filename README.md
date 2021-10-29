# S206_UI

Lista de Exercício - Teste de UI (User Interface) com cypress

# Como rodar o programa

  • Abrir o GIT Bash na pasta cypress/integration/teste_ui
  
  • Executar o comando ./node_modules/.bin/cypress open
  
  • Clicar no código teste_ui/teste.spec.js

# Como gerar o relatório

  • No terminal (utilizei no VS Code), utilizar o comando ./node_modules/.bin/cypress run --spec 'cypress/integration/teste_ui/**/' 
  
  • Usar o comando npm install --save-dev mochawesome mochawesome-merge mochawesome-report-generator
  
  • Utilizar o comando ./node_modules/.bin/cypress run --spec 'cypress/integration/testes_ui/**/'  novamente, para gerar o relatório.
  
  • Utilizar o comando npx mochawesome-merge "cypress/reports/*.json" > mochawesome.json para realizar o merge.
  
  • Gerar um html com o comando npx marge mochawesome.json.
  
