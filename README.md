# AULA-PRÁTICA-1
ROTEIRO-DE-AULA-PR-TICA-1 - MATÉRIA - Framework para desenvolvimento de software
# Entrega - Atividade Prática 1
## Projeto
Prova de conceito: Projeto Java Web com Spring MVC no VS Code, deploy no Tomcat.

## Requisitos
- JDK 11 ou 17 instalado
- Maven instalado
- Apache Tomcat 8.x ou 9.x (se for deploy via WAR)
- VS Code com extensões:
  - Java Extension Pack
  - Spring Boot Extension Pack
  - Tomcat for Java
  - Maven for Java

## Como executar (Modo Spring Boot - rápido)
1. Abra um terminal na pasta do projeto.
2. Build e run:
   ```bash
   mvn clean package
   mvn spring-boot:run
# Configuração do Servidor Tomcat 8.x (Projeto Aula Prática 1)

## Descrição
Projeto de configuração do servidor **Apache Tomcat 8.x** para execução de aplicações web desenvolvidas na **IDE NetBeans**.  
Foi criado um projeto Java Web simples com o framework **Spring MVC** para testar o funcionamento do servidor.

## Funcionalidades
- Configuração completa do servidor Tomcat 8.x  
- Integração com NetBeans IDE  
- Criação e execução de projeto Java Web simples usando Spring MVC  
- Teste de execução da aplicação web no navegador

## Tecnologias Utilizadas
- NetBeans IDE  
- Java JDK  
- Apache Tomcat 8.x  
- Spring Web MVC  

## Estrutura de Arquivos
ProjetoJavaWeb/
├── index.jsp
├── WEB-INF/
│ ├── web.xml
│ └── ... (arquivos do Spring MVC)

## Como Executar
1. Instale o NetBeans IDE e Java JDK no seu computador  
2. Configure o Tomcat 8.x no NetBeans, apontando para a pasta `apache-tomcat-8.x.x`  
3. Crie um projeto Java Web e selecione o framework Spring MVC  
4. Execute a aplicação e abra o link gerado pelo Tomcat no navegador  

## Autor
- **Rerisson Henrique Rodrigues da Silva**
