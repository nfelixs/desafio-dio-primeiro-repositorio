# Github

#### **CLONAR REPOSITORIO NO GIT HUB**

Copia repositório e coloca na sua máquina. Quando fizer isso não pode simplesmente copiar URL e colar no Git Clone pois vai em formato HTTPS e não é o que queremos, tem que usar o caminho SSH.

Quando clica em Dropdown do Code para escolher como clonar repositorio vai oferecer HTTPS e o SSH. Escolher SSH pois é repositório privado.



#### Comandos importantes

- **Git int:** Iniciar repositório

- **Git add:** Mover arquivos e começar primeiros comandos

- **Git commit**: Criar primeiro commit



#### Configurações iniciais

- *git config --global user.email "felix.nataliasilva@yahoo.com.br"*

- *git config --global user.name nfelixs*

- **Commitar**: *git commit -m "commit inicial"*

  

**Arquivo Markdown**: Forma mais humana de escrever arquivos HTML. Usamos o **Typora** para editar arquivos em formato .md

**HTML**: Esqueleto de qualquer página na Web

 

#### Conceitos importantes

**TRACKED:** Arquivos rastreados pelo git

- **UNMODIFIED**: Ainda não foi modificado

- **MODIFIED**: Algo que foi modificado, git compara SHA1.

- **STAGED**: Conceito chave, bastidores, arquivos se preparando para outro tipo de agrupamento

**UNTRACKED**: Git ainda não tem ciência deles. 



**GIT INIT**: Além de criar pasta .git inicia repositório dentro do diretório (pasta)

**GIT ADD**: Pegou arquivo untracked e moveu direto pro staged.

**COMMIT**: Quando coloca no staged e integra commit, deixa de ser staged e retorna arquivo pra unmodified. É como se tirasse uma foto SNAPSHOT do arquivo e aguardasse novas modificações.

Arquivos ficam transitando entre **WORKING DIRECTORY** e **STAGING AREA.** Quando **COMMITA** move arquivos de **STAGED** para **UNMODIFILED** e assim popula o repositório local, que só é composto por **COMMITS**, se não estiver **COMMITADO** não consegue transferir para repositório remoto.

**GIT STATUS**: Monitora status dos arquivos



#### Passar arquivo do Git Bash pro Git Hub:

- Clicar em repositório – Novo

- Copiar Https que me mostrar
-  Ir para Git Bash
  - _Git remote add origin + colar https_: Origin é o apelido que demos pro Https para não precisar colocar o link toda vez que precisa usar
  - _Git remote -v_: verifica se deu certo
  - _Git status_: se certifica que não tem nenhuma pendencia no repositório
  - _Git push origin master_ : Empurra arquivo do repositório local pro Github
  - Pede pra colocar credenciais e confirma que deu certo 😊

**Merge conflit: resolve manualmente**

- _Git pull origin master_: Puxar conteúdo do git hub para repositório local.

- _Git clone + Colar Https_ do que quero clonar