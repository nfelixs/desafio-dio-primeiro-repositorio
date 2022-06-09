# Conceitos Básicos Git

_Plataforma em nuvem que guarda código de forma segura_

#### SHA1

Algoritmo de encriptação constituído por conjunto de caractere identificador contendo quarenta dígitos. Pega o arquivo e embaralha de forma específica.

#### BLOB

Guarda arquivos fazendo o SHA1 do arquivo

#### TREE

Armazena BLOBS, monta estrutura onde estão armazenados os arquivos. Aponta para BLOBS e tem SHA1 encriptado como metadado da própria TREE

#### COMMIT

Aponta para TREE, parente, autor e mensagem. Também possui SHA1 dos metadados 

___Git  garante que ninguém altere seu commit sem que fique registrado, é muito seguro e demonstra que nao teve interferência de outras pessoas___

#### SSH

Forma de estabelecer conexão segura e encriptada entre duas máquinas. Conceitos de Chave pública e privada.

Computador pessoal será cadastrado como confiável

- Chave Pública: Github
- Chave Privada: Meu notebook







