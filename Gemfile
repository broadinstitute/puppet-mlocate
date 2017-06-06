source "https://rubygems.org"

group :test do
  gem 'rake'
  gem 'puppet', ENV['PUPPET_VERSION'] || '~> 3.8.0'
  gem 'rspec-puppet', git: 'https://github.com/rodjek/rspec-puppet.git'
  gem 'puppetlabs_spec_helper'
  gem 'metadata-json-lint', '~> 1.0.0' if RUBY_VERSION < '2.0.0'
  gem 'metadata-json-lint' if RUBY_VERSION >= '2.0.0' 
  gem 'rspec-puppet-facts'
  gem 'rspec'
  gem 'puppet-blacksmith'
  gem 'rubocop', '~> 0.39.0' if RUBY_VERSION < '2.0.0'
  gem 'rubocop' if RUBY_VERSION >= '2.0.0'
  gem 'puppet-lint-absolute_classname-check'
  gem 'puppet-lint-leading_zero-check'
  gem 'puppet-lint-trailing_comma-check'
  gem 'puppet-lint-version_comparison-check'
  gem 'puppet-lint-classes_and_types_beginning_with_digits-check'
  gem 'puppet-lint-unquoted_string-check'
  gem 'puppet-lint-variable_contains_upcase'
  gem 'json_pure', '~> 1.x'
end

group :development do
  gem 'travis'
  gem 'travis-lint'
  gem 'guard-rake'
end

group :system_tests do
  gem 'beaker'
  gem 'beaker-rspec'
end

