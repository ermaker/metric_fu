source 'https://rubygems.org'


group :test, :local_development  do
  gem 'pry'
  gem 'pry-nav'
  # https://github.com/kina/simplecov-rcov-text
  gem 'simplecov-rcov-text', group: :metrics
end

gemspec :path => File.expand_path('..', __FILE__)

# group :development, :test do
#   gem 'devtools', git: 'https://github.com/rom-rb/devtools.git'
# end

# Added by devtools
eval_gemfile File.expand_path('Gemfile.devtools', File.dirname(__FILE__))
