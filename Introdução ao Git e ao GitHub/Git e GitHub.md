<h1 align="center"> Introdução ao Git e ao GitHub </h1>

<h2 align="justify"> Descrição do projeto 💻 </h2>

<p align="justify"> Desenvolver um guia colaborativo do Git/GitHub com linguagem de fácil entendimento e didático, que possa ser usado por qualquer pessoa. Além de servir como caderno de anotações, será também um local para registros de problemas comuns, possíveis cenários, assim como a sua solução. Sinta-se a vontade para contribuir com esse projeto!</p>
<br>

<h2>Quem eu sou ༼ つ ◕_◕ ༽つ</h2>

<p align="justify"> Olá, sou o Marcelo! Estou me graduando em Ciência da Computação, tenho muita vontade de estar sempre aprendendo alguma coisa, além de gostar de ensinar, eu adoro compartilhar todos os meus conhecimentos. Na DIO/Eduzz Fullstack Developer, eu tive o meu primeiro contato com o Git e ao GitHub e estou encantado com o propósito deles. Então vamos juntos nessa, tornar ainda mais didático a linha de aprendizagem do Git e GitHub! Espero conseguir compartilhar todas as minhas conquistas e evolução com vocês, transmitindo-as de forma que atinja todas as pessoas. </p>
<br>

## Status do Projeto: Em desenvolvimento ⚠
<br>

## O que é o Git? <img align="center" src="Img/git.png" width="64" height="64"></img>

<p align="justify"> Git é um sistema de controle de versão distribuído gratuito e de código aberto projetado para lidar com tudo, desde projetos pequenos a muito grandes com velocidade e eficiência.

Git é fácil de aprender e tem uma pegada pequena com desempenho extremamente rápido. Ele supera as ferramentas SCM como Subversion, CVS, Perforce e ClearCase com recursos como ramificação local barata, áreas de teste convenientes e vários fluxos de trabalho. 

Em outras palavras, Git é essencial para projetos realizados em equipe, tornando possível o desenvolvimento do projeto de forma colaborativa, onde a equipe poderá desenvolver no mesmo código, evitando conflitos entre as alterações realizadas.</p>
<br>

## Como instalar o Git?

#### Versão para Linux/Unix: <br>
[Clique aqui.](https://git-scm.com/download/linux)
<br>

#### Versão para macOS: <br> 
[Clique aqui.](https://git-scm.com/download/mac)
<br>

#### Versão para Windows:
<br>

#### 1º - [Acesse o link da página oficial do Git, clicando aqui.](https://git-scm.com/)
<br>

#### 2º - Clique em Download for Windows para baixar o instalador do git.
<br>

<img src="img/git-down.png"></img>

<br>

#### 3º - Depois de baixado, basta clicar duas vezes sobre o instalador do Git para Windows, seguir as instruções na tela, clicando em **Next** e no final em **Finish** para terminar a instalação.
<br>

#### 4º - Se tudo ocorreu com sucesso, poderemos verificar a versão do Git instalada usando o seguinte comando no cmd do Windows:
<br>

1. #### Abra o menu iniciar e digite cmd e clique em **Prompt de Comando**;
<br>

2. #### No Prompt de Comando, digite o seguinte comando: <br>`git --version`
   #### O resultado será como esse:
        C:\Users\namepc>git --version
        git version 2.33.0.windows.2
    #### Onde estar mostrando que a versão instalada é a 2.33.0.windows.2
<br> 

#### 5º - Crie uma conta no GitHub, [clique aqui.](https://github.com/)
<br>

#### 6º - Supondo que você já tenha uma conta no GitHub, iremos criar uma chave SSH e um Token para os seus futuro repositórios.
<br>

## Chave SSH 🔑 <br>

<p align="justify"> Se você confia na máquina em que estar usando, onde a mesma não é pública, poderemos autenticar ela. Com isso, ao fazermos o uso do Git/GitHub com a máquina confiável, não será preciso passar por alguns fatores de autenticação.</p>

1. #### Inicie o **Git Bash**. Basta abrir o menu iniciar e digitar Git e depois clicar em **Git Bash**.
   <br>

2. #### Execute o seguinte comando para gerar a chave SSH: <br> `ssh-keygen -t ed25519 -C Seu_E-mail_usado_no_GitHub`
   <br>

3. #### Após, navegue até o diretório onde as chaves foram salvas usando o comando **cd**. Por padrão as chaves são salvas na Pasta_do_Usuário/.ssh. Lembre-se de trocar no comando abaixo o "Nome_do_Usuário", sem as aspas, pelo o seu nome de usuário. <br>
   `cd /c/Users/Nome_do_Usuário/.ssh`
   
   <br>

4. #### Poderemos usar o comando **ls** para listar os conteúdos do diretório: <br>
   `ls`
   
   <br>
5. #### Visualize o conteúdo da chave SSH **pública** utilizando o comando **cat** e a copie para adicionar no GitHub/SSH and GPG Keys. A chave **pública** tem a extensão **.pub**. Substitua "id_sua_chave_SSH.pub", sem as aspas, pela a sua:
   `cat id_sua_chave_SSH.pub`
   
   <br>

6. #### Agora precisamos iniciar o SSH Agent: <br>
   `eval $(ssh-agent -s)`

   <br>

7. #### Passar a chave **privada** para o SSH Agent. Troque "Id_chave", sem as aspas, pela a sua: <br>
   `ssh-add Id_chave`
   
   <br>

8. #### Após, iremos ao GitHub para adicionar a chave SSH.
   1. #### Clique no seu ícone de perfil, depois em Settings;
   2. #### No canto esquerdo, procure por **SSH and GPG keys**;
   3. #### Em SSH keys, clique em **New SSH key**;
   4. #### Adicione um título que tenha algum significado, como por exemplo: "Minha máquina linux";
   5. #### Cole o conteúdo da chave SSH **PÚBLICA**;
   6. #### Depois de colado, clique em **Add SSH key**.

<br>

## Token de acesso pessoal 🔑 <br>

<p align="justify"> Com o token</p>