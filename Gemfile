source "https://rubygems.org"

gem "xcode-install", ">= 2.6.7"
gem "fastlane", "~> 2.156.1"
gem "cocoapods", "~> 1.11.0"

plugins_path = File.join(File.dirname(__FILE__), 'fastlane', 'Pluginfile')
eval_gemfile(plugins_path) if File.exist?(plugins_path)
