# ruby-on-rails
set up the environment on Ubuntu of ruby on rails
Rails入门：http://guides.ruby-china.org/getting_started.html
sudo apt-get install ruby-full (Ruby 1.9.3)
sudo apt-get install sqlite3
sudo gem install bundler
sudo gem install rails (sudo apt-get install zlib1g-dev)
在ubuntu中安装及使用rvm管理ruby版本：http://blog.csdn.net/abbuggy/article/details/8170899
dpkg -s curl 检查系统中是否已安装curl
sudo apt-get install curl
curl -L get.rvm.io | bash -s stable 安装curl
rvm -v 查看rvm版本
rvm installation not working: “RVM is not a function”：https://stackoverflow.com/questions/9336596/rvm-installation-not-working-rvm-is-not-a-function
/bin/bash --login
Terminal stuck on installing ri documentation for rails ：https://stackoverflow.com/questions/22945924/terminal-stuck-on-installing-ri-documentation-for-rails
gem install rails --no-ri --no-rdoc
rails --version 查看rails版本
{不推荐用此方法
提高rails new时bundle install运行速度: http://rubyer.me/blog/941/
rails new my_app --skip-bundle
cd my_app
bundle install --local
gem install bundler --pre
bundle install --path vendor/cache
第 2 章 玩具应用: http://railstutorial-china.org/book/chapter2.html
Rails server won't run - Could not find gem error: https://stackoverflow.com/questions/28686855/rails-server-wont-run-could-not-find-gem-error
}
rails new blog
gem install therubyracer
