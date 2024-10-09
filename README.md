## Projeto de Automação Java Web

Projeto de treinamento de automação de testes Java Web. Esse projeto tem o objetivo de automatizar uma aplicação web, utilizando a linguagem de programação Java e a biblioteca Selenium WebDriver.

### Tecnologias

- Linguagem de programação: Java
- Framework de Testes: JUnit 5
- Automação de Navegador: Selenium  WebDriver 4
- Gerenciamento de dependências: Maven
- Navegador: Google Chrome

### Estrutura do Projeto

A estrutura do projeto segue o padrão maven, com a seguinte organização de diretórios.

* **/src/main/java** : Contém o código da aplicação, caso seja necessário para os testes.
* **/src/test/java** : Contém os scripts de automação de testes.
* **/src/test/resources** : Contém arquivos de configuração e drivers necessários para a execução dos testes.

### Configuração do Ambiente

#### Pré-requisitos

* **Java JDK 11+** : Certifique-se de que o JDK está instalado e configurado no PATH.
* **Maven** : Ferramenta de gerenciamento de dependências.
* **Google Chrome** : Navegador utilizado para os testes.
* **ChromeDriver** : Driver necessário para controlar o navegador Google Chrome.

#### Instalação

1. Clone o repositório do projeto:

```
git clone https://github.com/labsdev-Training/automation-javaweb
```

2. Navegue até o diretório do projeto:

```
cd java-app
```

3. **ChromeDriver** está no diretório **/src/test/resources** ou adicione o caminho do driver no arquivo de configuração.

#### Caso de Uso

Nesse estudo, utilizamos a aplicação:

* https://petlov.vercel.app/

  Com as seguintes features:
* skelleton de um projeto de automação básico;
* cadastro;
