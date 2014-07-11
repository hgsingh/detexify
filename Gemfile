source 'https://rubygems.org'

ruby '2.1.2'

gem "json"
gem "sinatra"
gem "rest-client", :require => 'rest_client'
gem "httparty"
gem "armchair"
gem "couchrest"
gem "threadify"
gem "thin" # for deployment on heroku

group :test do
  gem "rspec"
  gem "fakeweb"
  gem "rack-test"
end

group :development do
  gem "middleman", "~>3.3.2"
  gem "middleman-livereload", "~> 3.1.0"
  gem "bourbon"
  gem "neat"
  gem "font-awesome-sass"
  gem 'dotenv'
  gem 'rmagick'
  gem 'sprite-factory'
end

group :rake do
  gem "rake"
  gem "aws-s3"
end
