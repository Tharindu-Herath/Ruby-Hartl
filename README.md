# Ruby-Hartl
hello_app.rb

1. $ echo "gem: --no-document" >> ~/.gemrc
2. Install Sinatra gem and puma server install
$ gem install sinatra -v 2.2.2
$ gem install puma    -v 5.6.5
3.Add Sinatra format to ruby_app
![image](https://github.com/Tharindu-Herath/Ruby-Hartl/assets/76625418/4ce870b9-9b7c-4857-b7b1-702909e2c568)
4. Run sinatra app
$ ruby hello_app.rb
5. Add gem files and config.ru file.
ruby_tutorial/config.ru
require './hello_app'
run Sinatra::Application

ruby_tutorial/Gemfile
source 'https://rubygems.org'

ruby '3.1.2'   # Change this line if you're using a different Ruby version.

gem 'sinatra', '2.2.2'
gem 'puma',    '5.6.5'
