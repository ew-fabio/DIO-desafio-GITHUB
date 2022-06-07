### Comandos do **GIT**:

- Algoritmo de encriptação:
  openssl sha1 xxxxxx

- Chave SSH:

  1. ssh-keygen -t ed25519 -C _inserir o email_
  2. cat id_ed25519.pub
  3. eval $(ssh-agent -s) | ssh-add id_ed25519

- Repositório local:
  git init

- Staged:

  - git add _nome do arquivo_
  - git add \*
  - git add .

- Commit:
  git status
  git commit -m "_texto de referrência_"

- Configuração:
  git config --list
  git config --global user.name "_nome do usuário github_"
  git config --global user.email "_email do usuário github_"
  git config --global --unset "_parâmetro_"

- Repositório online:
  git remote -v
  git remote add origin "_end. do repositório_"
  git push origin master
  git pull origin master
  git clone "_end. do repositório_"

- Conflitos de merge: _puxar_ o conteúdo, sanar os conflitos de versão e, _empurrar_ para o repositório remoto (Github).
