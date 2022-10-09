# rubyセットアップ
- 2022/10/08

## Rubyの開発環境を用意しよう！（macOS用）
- https://prog-8.com/docs/ruby-env


```sh
cd ruby_lesson
ruby index.rb
brew -v
rbenv -v
brew install rbenv ruby-build
rbenv -v
echo 'export RBENV_ROOT="$HOME/.rbenv"' >> ~/.zshrc
echo 'export PATH="$RBENV_ROOT/bin:$PATH"' >> ~/.zshrc
echo 'eval "$(rbenv init -)"' >>  ~/.zshrc
source ~/.zshrc
rbenv install --list
rbenv install 3.1.2
rbenv versions
rbenv global 3.1.2
```