source 'https://rubygems.org'
gemspec

unless ENV['TRAVIS']
  gem 'byebug', require: false, platforms: :mri
  gem 'yard',   require: false
end

gem 'hanami-utils', '~> 1.2', require: false, git: 'https://github.com/hanami/utils.git', branch: 'master'
gem 'haml'

gem 'hanami-devtools', require: false, git: 'https://github.com/hanami/devtools.git'
gem 'coveralls', require: false
