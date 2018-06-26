# Gem devise
- Add gemfile: gem 'devise'
- Run: bundle install, rails generate devise:install
- Create model and db migrate: rails generate devise User
- Go to forder: config/environments/development.rb, 
  paste: config.action_mailer.default_url_options = { host: 'localhost', port: 3000 }
- Paste in controller:   before_action :authenticate_user!

- Document: https://viblo.asia/p/gioi-thieu-gem-devise-amoG84YnGz8P
