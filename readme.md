# Configuration for deploying Rails Project using Rockerteer
- Installation (**Ruby required**)
```
gem install capistrano capistrano-laravel capistrano-composer capistrano-npm
```
- For more information and detailed usages, please refer [Capistrano](https://github.com/capistrano/capistrano) and [Capistrano Laravel](https://github.com/capistrano/laravel)
- Download `Capfile` and move it into your Laravel project. Download file and folder inside `config` folder and move them into Laravel's `config` project.
- You have to change some configurations in the following files:
    - `config/deploy.rb` The repository url `your_repo_url`
    - `config/deploy/staging.rb` or `config/deploy/production.rb` The deploy server information `deploy_user@server_name_or_ip_address`
