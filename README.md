
# Oficina Introdução à Linguagem Go
## Módulo 1
<details>
<summary>Instruções de instalação</summary>
 
# Primeiros passos para configuração do ambiente local:

### Pré Requisitos:
 - Realizar a instalação de um editor de código ou IDE, as recomendações são o VSCode ou Goland.
<div style="text-align: center;">  
     <img src="/assets/vscode.png" style="margin-right: 100px" width="100"/>                       
     <img src="/assets/goland.png" style="margin-right: 100px" width="100"/>
</div>

## 1. Baixar o Instalador
 - Acesse o site oficial do Go para baixar a versão mais recente: [Download Go](https://go.dev/doc/install)
 - Escolha a versão correspondente ao seu sistema operacional:
   1. Windows: .msi
   2. Linux: .tar.gz
   3. macOS: .pkg
## 2. Instalar o Go

Como sempre vou deixar um link de um vídeo para auxiliar caso surja alguma dúvida.
 - [Tutorial de instalação Go.](https://youtu.be/eJq_D9at6ec?si=NQeV1cZcozKjjgVC)

### Windows

1. Execute o arquivo `.msi` baixado.
2. Siga as instruções do assistente de instalação.
3. Verifique se o Go foi instalado corretamente abrindo o **Terminal** e executando:
   ```sh
   go version
   
   go version go1.24.1  👈 o output esperado é esse
   ```

### Linux

1. Extraia o arquivo baixado para `/usr/local`:
   ```sh
   sudo tar -C /usr/local -xzf go<versao>.linux-amd64.tar.gz
   ```
2. Adicione o caminho do Go ao `PATH` editando `~/.bashrc` ou `~/.profile`:
   ```sh
   echo "export PATH=$PATH:/usr/local/go/bin" >> ~/.bashrc
   source ~/.bashrc
   ```
3. Verifique a instalação:
   ```sh
   go version
   
   go version go1.24.1  👈 o output esperado é esse
   ```

### macOS

1. Execute o arquivo `.pkg` baixado.
2. Siga as instruções do instalador.
3. Verifique a instalação abrindo o **Terminal** e executando:
   ```sh
   go version
   
   go version go1.24.1  👈 o output esperado é esse
   ```

### 4. Por fim, faça o `git clone` deste repositório na sua máquina para acompanhar e realizar os exercícios durante a oficina!
### 5. Tá pronto o sorvetinho! Nos vemos novamente no dia da oficina  🐈🚀
</details>

<hr>

## Módulo 2
<details open>
<summary>Dependências e ferramentas</summary>
 
 ### Pré-Requisitos:
 - É altamente recomendado que o **GoLand** seja instalado para facilitar o andamento da trilha neste módulo.
 - Será necessário instalar o Postman para realizar requisições a API, o link para download está aqui: [Download Postman](https://www.postman.com/)
 - Iremos utilizar o banco de dados MongoDB no projeto deste módulo, para isso iremos criar uma conta no MongoDB Atlas.
 - Nesta etapa da oficina serão abordados conceitos de API's REST, protocolo HTTP e o banco de dados MongoDB, caso você não tenha conhecimento no assunto irei deixar alguns vídeos de apoio.

 ### Criando banco de dados no MongoDB Atlas:
### 1. Criar conta no MongoDB Atlas

#### Passos:
1. Acesse: [https://www.mongodb.com/cloud/atlas](https://www.mongodb.com/cloud/atlas)
2. Clique em **“Get Started”**
3. Escolha entre:
   - Criar com e-mail e senha
   - Ou usar conta do **Google**, **GitHub**, etc.
4. Caso sejam feitas algumas perguntas é só clicar em Skip logo abaixo
5. Complete o cadastro

---

### 2. Criar um Cluster gratuito

#### Passos:
1. Após o login, você será direcionado para criar um cluster
2. Escolha a opção **Free (Shared Cluster)**
3. Selecione a **região** desejada (ex: `South America (São Paulo)` ou `AWS / us-east-1`)
4. Clique em **“Create Deployment”**
5. Aguarde a criação (leva de 1 a 2 minutos)

---

### 3. Criar usuário de acesso ao banco

#### Passos:
1. Você irá se deparar com uma tela para criar usuário
2. Crie um **Username** e um **Password** para esse usuário, iremos usar esses dados para conectar no banco.
3. Após isso pode clicar em **Close**
---

### 4. Liberar acesso ao IP

#### Passos:
1. Vá em **Network Access**
2. Clique em **“+ ADD IP ADDRESS”** ou **Edit** caso você já tenha um para acessar o banco
3. Escolha:
   - **ALLOW ACCESS FROM ANYWHERE** (`0.0.0.0/0`)
4. Clique em **Confirm**

---

### 5. Criar o banco de dados `trilha-go` com a collection `users`

#### Passos:
1. Vá em **Database** > selecione seu cluster > clique em **“Add Data”**
2. Clique em **“+ Create Database”**
3. Preencha os campos:
   - **Database Name**: `trilha-go`
   - **Collection Name**: `users`
4. Clique em **“Create”**


## Vídeos de Apoio

---
#### O que é uma API REST?
<a href="https://www.youtube.com/watch?v=9SbUPqKEWcY">
  <img src="https://img.youtube.com/vi/9SbUPqKEWcY/0.jpg" alt="API REST" width="300"/>
</a>

<hr>

#### MongoDB em 100 segundos
<a href="https://www.youtube.com/watch?v=-bt_y4Loofg">
  <img src="https://img.youtube.com/vi/-bt_y4Loofg/0.jpg" alt="MongoDB" width="300"/>
</a>

</details>


### Caso surja alguma dúvida, entre em contato por e-mail (liprog@ufcspa.edu.br) ou pelo instagram (@liprog.ufcspa).
