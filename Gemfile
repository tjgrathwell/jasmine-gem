source 'https://rubygems.org'

gemspec

unless ENV['TRAVIS']
  group :debug do
    gem 'debugger'
  end
end


# during development, do not release
gem 'jasmine-core', :git => 'http://github.com/tjgrathwell/jasmine.git'
