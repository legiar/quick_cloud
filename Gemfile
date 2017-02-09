source 'https://rubygems.org'

gem 'rails',          '~> 5.0.0', '>= 5.0.0.1'
gem 'puma',           '~> 3.0'

gem 'sqlite3'

gem 'bcrypt',                           '~> 3.1.7'
gem 'devise',                           '~> 4.2.0'
gem 'cancancan',                        '~> 1.15'

gem 'kaminari',                         '~> 0.17.0'

gem 'redis',                            '~> 3.0'
#gem 'connection_pool',                  '~> 2.0'
gem 'redis-rails',                      '~> 5.0'

gem 'sidekiq',                          '~> 4.2'
gem 'sidekiq-cron',                     '~> 0.4.0'
gem 'redis-namespace',                  '~> 1.5.2'

gem 'slim-rails'
gem 'simple_form'
gem 'cocoon'

gem 'sass-rails',                       '~> 5.0'
gem 'uglifier',                         '>= 1.3.0'
gem 'coffee-rails',                     '~> 4.2'

gem 'jquery-rails'
gem 'turbolinks',                       '~> 5'
gem 'jbuilder', '~> 2.5'

gem 'countries',                        require: 'countries/global'
gem 'tzinfo',                           '~> 1.2', '>= 1.2.2'
gem 'validates_zipcode'
gem 'phony_rails'

#gem 'exception_notification'
#gem 'slack-notifier'

gem 'ruby-libvirt'

group :development do
  gem 'pry-rails'

  gem 'web-console'
  gem 'listen',                         '~> 3.0.5'

  gem 'spring'
  gem 'spring-watcher-listen',          '~> 2.0.0'
end

group :development, :test do
  gem 'byebug', platform: :mri

  gem 'database_cleaner',               '~> 1.5.0'
  gem 'factory_girl_rails',             '~> 4.7.0'
  gem 'rspec-rails',                    '~> 3.5.0'
  gem 'ffaker',                         '~> 2.2.0'
end

group :test do
  gem 'shoulda-matchers',               '~> 3.1'
  gem 'json_spec'
  gem 'rspec-json_expectations'
  gem 'rspec-its'
  gem 'webmock', '~> 1.21.0'
  gem 'test_after_commit',              '~> 0.4.2'
  gem 'timecop',                        '~> 0.8.0'

  gem 'simplecov',                      require: false
end

