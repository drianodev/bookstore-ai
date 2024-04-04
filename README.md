# BookStore-AI

## Visão Geral
Este projeto é uma aplicação de demonstração para Spring Boot que utiliza capacidades de inteligência artificial. Ele integra-se com a biblioteca Spring AI da OpenAI para alavancar funcionalidades de IA dentro de uma aplicação de livraria.

## Pré-requisitos
- Kit de Desenvolvimento Java (JDK) versão 22
- Maven

## Dependências
- **Spring Boot Starter Web**: Fornece suporte básico para web para aplicações Spring Boot.
- **Spring AI OpenAI Spring Boot Starter**: Integra o Spring Boot com a biblioteca Spring AI da OpenAI para funcionalidades de IA.
- **Spring Boot Starter Test**: Fornece suporte para testes de aplicações Spring Boot.

## Configuração
### Versão do Java
Este projeto requer a versão 22 do Java. Certifique-se de ter o JDK 22.

### Versão do Spring AI
O projeto utiliza a versão 0.8.1 da biblioteca Spring AI.

## Compilação
Este projeto utiliza o Maven como ferramenta de compilação. Para compilar o projeto, execute o seguinte comando no diretório raiz do projeto:

```bash
mvn clean install
```

## Uso
Após compilar o projeto, você pode executá-lo como uma aplicação Spring Boot. A classe principal é `br.com.drianodev.bookstore.ai.AiApplication`.

## Configuração do Maven
Este projeto utiliza o Maven para gerenciamento de dependências e automação de build. O arquivo `pom.xml` contém todas as configurações necessárias. Ele gerencia as dependências por meio do Spring AI BOM (Bill of Materials) para gerenciamento consistente de versões.

### Plugins do Maven
- **Spring Boot Maven Plugin**: Permite empacotar e executar aplicações Spring Boot.

## Repositórios
O projeto obtém dependências do repositório Spring Milestones.

## Referências
- [Tutorial em Vídeo do YouTube](https://www.youtube.com/watch?v=NscHAlj-yQ0): Este projeto foi criado com base no tutorial fornecido neste vídeo.
