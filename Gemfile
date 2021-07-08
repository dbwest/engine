#!/usr/bin/env bundle
# encoding: utf-8

source :rubygems

gemspec # Include gemspec dependencies

# The rest of the dependencies are for use when in the locomotive development environment

group :development do
  # gem 'custom_fields', :path => '../gems/custom_fields' # for Developers
  # gem 'custom_fields', :git => 'git://github.com/locomotivecms/custom_fields.git', :branch => '2.0.0.rc' # Branch on Github

  # gem 'locomotive-aloha-rails', :path => '../gems/aloha-rails' # for Developers
  # gem 'locomotive-tinymce-rails', '~> 3.4.7.5', :path => '../gems/tinymce-rails' # for Developers
  # gem 'locomotive_liquid', :path => '../gems/liquid' # for Developers

  gem 'rspec-rails', '~> 2.8.1' # In order to have rspec tasks and generators
  gem 'rspec-cells', '>= 0.1.7'

  gem 'unicorn' # Using unicorn_rails instead of webrick (default server)

end

group :assets do
  gem 'sass-rails', '~> 4.0.0'
  gem 'coffee-rails', '~> 4.0.0'
  gem 'uglifier',     '~> 1.2.4'
  gem 'compass-rails'
end

group :production do
  gem 'locomotive-aloha-rails', :git => 'git@github.com:dbwest/aloha-rails.git'
end

group :test do
  gem 'launchy'

  # gem 'autotest', :platforms => :mri
  # gem 'ZenTest', :platforms => :mri

  # gem 'growl-glue'

  gem 'cucumber-rails',     :require => false
  gem 'poltergeist',        '~> 1.0.2'
  gem 'rspec-rails', '~> 2.8.1'
  gem 'shoulda-matchers'

  gem 'factory_girl_rails', '~> 1.6.0'
  gem 'pickle'
  gem 'mocha',              '0.9.12' # :git => 'git://github.com/floehopper/mocha.git'

  gem 'capybara',           '~> 1.1'

  gem 'xpath',              '~> 0.1.4'

  gem 'json_spec'

  gem 'database_cleaner'

  # gem 'debugger', :git => 'git://github.com/cldwalker/debugger.git'
end
