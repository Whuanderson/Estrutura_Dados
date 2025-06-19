# Estrutura de Dados com JavaFX

Este projeto implementa estruturas de dados utilizando Java e JavaFX para fornecer uma interface gráfica interativa. A aplicação é iniciada pela classe `App`, localizada no diretório `src`.

## 🎥 Demonstração

<p align="center">
   <img src="https://raw.githubusercontent.com/Whuanderson/Estrutura_Dados/refs/heads/main/assets/gif2.gif" alt="Demonstração 2" width="400" />
  <img src="https://raw.githubusercontent.com/Whuanderson/Estrutura_Dados/refs/heads/main/assets/gif1.gif" alt="Demonstração 1" width="460" />  
</p>

## 📋 Pré-requisitos

- **Java Development Kit (JDK) 11 ou superior**  
  Certifique-se de que o JDK está instalado e configurado corretamente no seu sistema.

- **JavaFX SDK**  
  Necessário para compilar e executar aplicações JavaFX.

## ⚙️ Instalação do JavaFX

### 1. Baixar o JavaFX SDK

- Acesse: [https://openjfx.io](https://openjfx.io)
- Baixe a versão correspondente ao seu sistema operacional.

### 2. Configurar no IntelliJ IDEA

1. Vá em `File` > `Project Structure` > `Libraries`
2. Clique em `+` e adicione o diretório `lib` da pasta do JavaFX SDK baixado.
3. Aplique as alterações.

### 3. Configurar as opções da VM

1. Vá em `Run` > `Edit Configurations`
2. No campo **VM options**, adicione:

--module-path /caminho/para/javafx-sdk/lib --add-modules javafx.controls,javafx.fxml

Substitua `/caminho/para/javafx-sdk/lib` pelo caminho real onde o JavaFX SDK está localizado.

## Executando o Projeto

1. **Clone o repositório**:

git clone https://github.com/Whuanderson/Estrutura_Dados.git

### Abra o projeto no IntelliJ IDEA:
2.
- Selecione a pasta do projeto clonado.
- Aguarde o IntelliJ importar as configurações do projeto.

### Execute a classe `App`:
3.
- Navegue até `src > App.java`.
- Clique com o botão direito na classe `App` e selecione **Run 'App.main()'**.



## 🤝 Contribuições

Contribuições são bem-vindas!  
Sinta-se à vontade para abrir issues ou enviar pull requests com melhorias ou correções.

---


## 🔗 Links úteis

- [JavaFX - Site oficial](https://openjfx.io)
- [Documentação do JavaFX](https://openjfx.io/openjfx-docs/)

