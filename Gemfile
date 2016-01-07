source 'https://rubygems.org'

# fork of the domain_name gem
gem 'domain_name', '= 0.5.25', path: 'vendor/gems/domain_name-0.5.25'

# Specify your gem's dependencies in .gemspec
gemspec

if `cd ..; git remote -v`.include?('countdown')
  gem 'credentials_manager', path: '../credentials_manager'
end
