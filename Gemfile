# frozen_string_literal: true

source 'https://rubygems.org'

ruby '2.4.4'

git_source(:github) { |repo_name| "https://github.com/#{repo_name}.git" }

gem 'nokogiri'
gem 'open-uri-cached'
gem 'rest-client'
gem 'scraped', github: 'everypolitician/scraped', branch: 'scraper-class'
gem 'scraperwiki', github: 'openaustralia/scraperwiki-ruby', branch: 'morph_defaults'
gem 'table_unspanner', github: 'everypolitician/table_unspanner'

group :test do
  gem 'minitest'
  gem 'minitest-around'
  gem 'minitest-vcr'
  gem 'rake'
  gem 'rubocop'
  gem 'scraper_test', github: 'everypolitician/scraper_test'
  gem 'vcr'
  gem 'webmock'
end

group :development do
  gem 'pry'
end
