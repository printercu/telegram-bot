source 'https://rubygems.org'
gemspec

case ENV['RAILS']
when '5'
  gem 'actionpack', '5.0.0.rc1'
when '4'
  gem 'actionpack', '~> 4.2'
end

group :development do
  gem 'sdoc', '~> 0.4.1'
  gem 'pry', '~> 0.10.1'
  gem 'pry-byebug', '~> 3.2.0'

  gem 'telegram-bot-types', '~> 0.3.0'

  gem 'rspec', '~> 3.5.0'
  gem 'rspec-its', '~> 1.1.0'

  gem 'rubocop', '~> 0.45.0'

  gem 'coveralls', '~> 0.8.2', require: false
end
