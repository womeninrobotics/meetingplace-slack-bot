ruby File.read('.ruby-version').chomp

source 'https://rubygems.org' do
  gem 'activesupport'
  gem 'dotenv'
  gem 'dotiw'
  gem 'rake'
  gem 'slack-ruby-bot'
  gem 'zeitwerk'

  group :development, :test do
    gem 'rack-test'
    gem 'rspec'
    gem 'simplecov', require: false
    gem 'timecop'
    gem 'vcr'
    gem 'webmock'
  end
end