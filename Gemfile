# If you have OpenSSL installed, we recommend updating
# the following line to use "https"
source 'https://rubygems.org'
ruby '2.0.0'

gem "middleman", "~>3.1.4"

gem 'susy'

# Live-reloading plugin
gem "middleman-livereload", "~> 3.1.0"

gem "middleman-favicon-maker", "~> 3.2"

gem "therubyracer", :require => 'v8'

# For faster file watcher updates on Windows:
gem "wdm", "~> 0.1.0", :platforms => [:mswin, :mingw]

# Cross-templating language block fix for Ruby 1.8
platforms :mri_18 do
  gem "ruby18_source_location"
end