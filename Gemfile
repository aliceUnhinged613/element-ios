source "https://rubygems.org"

gem "xcode-install"
gem "fastlane", '~>2.156.0'
gem "cocoapods", "~> 1.10.0"

plugins_path = File.join(File.dirname(__FILE__), 'fastlane', 'Pluginfile')
eval_gemfile(plugins_path) if File.exist?(plugins_path)
