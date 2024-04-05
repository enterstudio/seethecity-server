source 'https://rubygems.org'

ruby "2.2.0"

gem 'active_model_serializers'
gem 'rails', '7.0.8.1'
gem 'pg', '~> 0.15'
gem 'uglifier', '>= 1.3.0'
gem 'jbuilder', '~> 2.0'
gem 'sdoc', '~> 1.0.0', group: :doc
gem 'rails-api', '>= 0.4.1'
gem 'twitter'

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug'
  gem 'dotenv-rails', '>= 2.7.6'
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'web-console', '~> 2.3', '>= 2.3.0'

  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
end

group :production do
	gem 'rails_12factor'
	gem 'puma'
end

