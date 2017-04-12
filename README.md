# Pequena biografia, utilizando CSS, de Pedro Rafael Simplício Cunha

Descrição de como rodar o projeto: 

### Fazer o clone do repositório:

https://github.com/pedrorafaell/biografiapedro

### Para rodar com o Tomcat dentro do repositório após o clone (irá rodar na porta 9090):

mvnw org.apache.tomcat.maven:tomcat7-maven-plugin:run -Dmaven.tomcat.port=9090 -Dmaven.tomcat.path=/biografiapedro

Atenção: No Linux, use `./mvnw` ao invés de apenas `mvnw`, como no Windows. Além disso, pelo menos uma vez, é preciso dar permissão de execução ao arquivo de script **mvnw** com o comando `chmod +x mvnw`.

### Para acessar a aplicação

http://localhost:9090/biografiapedro/ em qualquer navegador.

### O Maven já esta embutido na aplicação.
