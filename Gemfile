source "http://rubygems.org"

gemspec

rails_version = case ENV['RAILS_MAJOR_VERSION']
                when '4'
                  '~> 4.0'
                else
                  '~> 5.0'
                end

gem 'rails', rails_version

# jquery-rails is used by the dummy application
gem 'jquery-rails'

gem 'json-schema'
