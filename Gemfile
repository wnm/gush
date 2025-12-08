source 'https://rubygems.org'
gemspec

rails_version = ENV['RAILS_VERSION'] || '<= 8.1'
rails_version = "~> #{rails_version}" if rails_version =~ /^\d/
gem 'activejob', rails_version

platforms :mri, :ruby do
  gem 'yajl-ruby'
end
