# Criando Chaves no Git Bash - Criptografia

-  Gerar chave publica/privada: *ssh-keygen -t ed25519 -C e@mail.com*

- Mostra o local em que está armazenada *(/c/Users/silva/.ssh/id_ed25519)*
  - Ponto antes do ssd pois é pasta oculta

- Criar senha pra chave e confirmar esta senha (Obs.: enquanto digita fica oculto, não aparece que está digitando)

- *cd /c/Users/silva/.ssh/*

- *cat id_ed25519.pub* comando para visualizar conteúdo das chaves, sempre pública para compartilhar nos locais

- Coloca a chave que mostrou no local que pediu a chave pública

- Inicializar SSH Agent: *eval $(ssh-agent -s)*

- Se aparecer: Agent pid XXXX deu certo :smile:

- Entregar chave privada pro agente*: ssh-add id_ed25519*

- Validar com senha criada anteriormente