source "http://rubygems.org"

gem "rake"
gem "cucumber", "0.9.2"
gem "aruba", "0.2.3"
gem "autotest"
gem "watchr"
gem "rcov"
gem "mocha"
gem "rr"
gem "flexmock"
gem "nokogiri"
gem "syntax"
gem "rspec-core", :path => "."
gem "rspec-expectations", :path => "../rspec-expectations"
gem "rspec-mocks", :path => "../rspec-mocks"
gem "relish"
unless RUBY_PLATFORM == "java"
  gem "ruby-prof"
  case RUBY_VERSION
  when /^1.9.2/
    gem "ruby-debug19"
  when /^1.8/
    gem "ruby-debug"
  end
end
