## Loginha Web Automação

Esse é um repositório que contém a automação de alguns testes, de um site denominado Lojinha. Os sub-tópicos abaixo descrevem algumas decisões tomadas na estruturação do projeto.

### Tecnologias utilizadas
- JUnit Jupiter API https://mvnrepository.com/artifact/org.junit.jupiter/junit-jupiter-api/5.9.1
- Selenium Java https://mvnrepository.com/artifact/org.seleniumhq.selenium/selenium-java/4.0.0-beta-4
- ChromeDriver 108.0.5 https://chromedriver.storage.googleapis.com/index.html?path=108.0.5359.71/

Testes Automatizados

Testes para validar o código relacionadas ao Abrir o Navegador, Maximizar o mesmo, em seguida  Preencher Usuário e Senha, após logado ele clica em  ADICIONAR PRODUTO, preenche os dados do Produto na Lojinha e faz a comparação de valor inseridos e valores permitidos, que estão vinculados diretamente a regra de negócio que diz que o valor do produto deve estar entre R$ 0,01 e R$ 7.000,00, como o valor inserido (0,00) está fora da regra de negócio especificada

### Notas Gerais

-   Neste código, submetemos o navegador a trabalhar em preenchimento de um formulário, login e senha, em uma plataforma web, denominada lojinha
-   Após a abertura e fazer o login, a automação preenche
-   Fizemos o uso do CSSSelector, pra localiza elementos da tela, que não tinha, identificador exclusivo, como : id, name e etc.
-   Nesse projeto fazemos uso do JUnit 5, o que nos dá a possibilidade de usar a anotação DisplayName, para dar descrições em português para nossos testes.