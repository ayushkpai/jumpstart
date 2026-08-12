# jumpstart

Macbook setup - zero to development

- Run bootstrap file to clone jumpstart

  ```
  ruby -e  "$(curl -fsSL https://raw.githubusercontent.com/ayushkpai/jumpstart/refs/heads/main/bootstrap)"
  ```

- Run

  ```
  ansible-playbook <file>
  ```

- If you want to just check if you have it installed

  ```
  ansible-playbook <file> --check
  ```

- Manual install

  ```
  rbenv init
  rbenv install 3.4.4
  rbenv global 3.4.4
  gem install rails -v 8.0.2 --no-document
  sudo npm i -g typescript
  brew services restart redis
  brew services start mysql
  npm install -g yo generator-code
  npm install -g vsce
  uv python install 3.14
  uv python pin 3.14
  uv python install 3.13
  sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
  gh auth login
  ```
