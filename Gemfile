source 'https://rubygems.org'
ruby '2.1.3'


gem 'rails', '4.1.6'

gem 'sass-rails', '~> 4.0.3'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.0.0'
gem 'jquery-rails'
gem 'turbolinks'
gem 'jbuilder', '~> 2.0'
gem 'sdoc', '~> 0.4.0', group: :doc
gem 'spring', group: :development
gem 'bootstrap-sass'
gem 'devise', '~> 3.4.1' #squiggly lets you do this version and anything after (in 3) 

group :development, :test do #development means use this one the computer 
	gem 'sqlite3' 
end

group :production do #for when it's running on the web / for Heroku
	gem 'pg'
	gem 'rails_12factor'
end
