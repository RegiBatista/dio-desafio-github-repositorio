![](https://user-images.githubusercontent.com/89160333/171444686-5a45b637-1aa4-479c-bac6-821a5f22f6fe.jpg)

# Desafio de Projeto sobre Git/Github da DIO
 
Repositório criado para o desafio de projeto, da [Digital Innovation One - DIO](https://web.digitalinnovation.one/home)!

## :key: Informações úteis:
#### 1. Comandos importantes do *Prompt de Comando* (também utilizado no Git):
   * **cls(win), clear(git, linux)** - para apagar todo o histórico de comandos do prompt;
   * **cd(win, git, linux)** - para se transitar entre as pastas dos diretórios, também há a variante "cd .." para retornar à pasta anterior;
   * **dir(win), ls(git, linux)** - para mostrar a lista de diretórios contidos na pasta em que estiver, também há a variante **dir -a(win), ls -a(git, linux)** para mostrar inclusive os diretórios ocultos ;
   * **mkdir(win, git, linux)** - para criar uma pasta no diretório;
   * **echo(win, git, linux)** - retorna o que for inserido, entretanto se utilizado como **"echo > nome.extensão"**, ele cria o arquivo na extensão desejada, ótimo para criar um readme bem rápido sem sair do git em?! :happy:
   * **start(win, git, linux)** - inicia um arquivo executável de qualquer tipo;
   * **TAB** - Sim, a tecla TAB tem a incrível função de abreviar algo que você deseja escrever, extremamente útil e vai agilizar muito a sua vida!

#### 2. Comandos de iniciação do *Git*:
   * **git init** - inicia o versionamento na pasta em que estiver;
   * **git config --global user.email "email"** - configura o ambiente de versionamento para todos os repositórios, com essa identificação de e-mail; em caso da necessidade de alterar isso posteriormente, use *git config --global unset user.email*;
   * **git config --global user.name "username"** - configura o ambiente de versionamento para todos os repositórios, com essa identificação de usuário no github (é importante ressaltar que os dados aqui, devem refletir o usuário no Github); em caso da necessidade de alterar isso posteriormente, use *git config --global unset user.name*
   * **git config --list** - mostra todos os parâmetros da configuração atual do Git; para sair, use a tecla *q*;
   * **git remote add nome (link)** - direciona seu repositório local para um repositório na nuvem, o parâmetro *NOME* é apenas um apelido para que você possa referenciar o link sem tê-lo que mencionar novamente; você também pode posteriormente utilizar o comando **git remote -v** para consultar o repositório que está recebendo os arquivos locais.

#### 3. A configuração do ambient com Git/Github com *chave SSH*:
   * Use o código abaixo no *Git*, para gerar uma chave SSH;
   * $ ssh-keygen -t ed25519 -C "seu\_email@example.com"
   * **cat (chave gerada)** - use esse comando **(git, linux)** para "ler" o conteúdo da chave, em seguida vá até a página principal no *Github>settings>SSH and GPG keys>New SSH key* em seguida insira o seu conteúdo da chave no campo "key".
   * Calma que ainda não acabou!:laughing: Agora no *Git Bash*, você precisa executar o agente para que gerencie suas chaves.
   * $ eval "$(ssh-agent -s)"
   * A saída do comando será *"> Agent pid (número\_qualquer)"*, o agente continuará executando em segundo plano. Agora como última etapa, você deve passar a chave privada para o agent com o seguinte código:
   * $ ssh-add "chave privada"
   * Pronto!:handshake: Agora você pode **usar todas as funcionalidades do git sem precisar se identificar o tempo todo**.

#### 5. O editor de arquivos *Markdown(.md)*, muito útil para o Github:
   * **Typora** - [clique aqui para baixar o Typora](https://typora.io);
   * Lista completa de [**emoticons**](https://gist.github.com/rxaviers/7360908):skull::smiley::collision:;

####  Obrigado por sua visita! (( Thank you for your visit! )) :sunglasses: :sunglasses: :sunglasses:
