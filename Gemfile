source 'https://rubygems.org'

# Use https for github source
git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

gem 'locomotivecms_wagon', github: 'akretion/wagon', branch: 'fix-slug-404-issue'
gem 'locomotivecms_steam', github: 'akretion/steam', branch: 'better-attribute-parser'

group :misc do
  gem 'shop_invader', github: 'akretion/locomotive-shopinvader', branch: 'fix-esi-snippet'
end
