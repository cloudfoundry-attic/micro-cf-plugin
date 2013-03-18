source "http://rubygems.org"

#############
# WARNING: Separate from the Gemspec. Please update both files
#############

gem "cfoundry", :git => "git://github.com/cloudfoundry/cfoundry.git"
gem "cf", :git => "git://github.com/cloudfoundry/cf.git"

group :development, :test do
  gem "rake"
end

group :development do
  gem "auto_tagger"
  gem "gerrit-cli"
end

group :test do
  gem "rspec", "~> 2.11"
  gem "webmock", "~> 1.9"
  gem "rr", "~> 1.0"
end
