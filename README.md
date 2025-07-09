
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

## Módulo 2
<details open>
<summary>Dependências e ferramentas</summary>
 
 ### Pré-Requisitos:
 - É altamente recomendado que o GoLand seja instalado para facilitar o andamento da trilha neste módulo.
 - Será necessário instalar o Postman para realizar requisições a API, o link para download está aqui: [Download Postman](https://www.postman.com/)
 - Nesta etapa da oficina serão abordados conceitos de API's REST, protocolo HTTP e o banco de dados MongoDB, caso você não tenha conhecimento no assunto irei deixar alguns vídeos de apoio:

 #### API's
 [![API REST](https://img.youtube.com/vi/9SbUPqKEWcY/0.jpg)](https://www.youtube.com/watch?v=9SbUPqKEWcY)

 #### MongoDB em 100 segundos
 [![API REST](https://img.youtube.com/vi/-bt_y4Loofg/0.jpg)](https://www.youtube.com/watch?v=-bt_y4Loofg&pp=0gcJCfwAo7VqN5tD)

</details>


### Caso surja alguma dúvida, entre em contato por e-mail (liprog@ufcspa.edu.br) ou pelo instagram (@liprog.ufcspa).
