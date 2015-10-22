source "https://rubygems.org"

chef_version = ENV.fetch("CHEF_VERSION", "11.16")

gem "chef", "~> #{chef_version}"
gem "chefspec", "~> 4.1.1" if chef_version =~ /^11/

gem "berkshelf", "~> 3.2.1"
gem "foodcritic", "~> 4.0.0"
gem "license_finder", "~> 1.2.0"
gem "rake"
gem "rubocop", "~> 0.27.1"
gem "serverspec", "~> 2.3.1"

group :integration do
  gem "busser-serverspec", "~> 0.5.3"
  gem "guard-rspec", "~> 4.3.1"
  gem "kitchen-vagrant", "~> 0.15.0"
  gem "test-kitchen", "~> 1.2.1"
end
