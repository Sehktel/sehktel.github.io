source "https://rubygems.org"

# Используем последнюю стабильную версию Jekyll
gem "jekyll", "~> 4.3.3"

# Основная тема
gem "minima", "~> 2.5"

# Плагины Jekyll
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.17.0"
  gem "jekyll-paginate", "~> 1.1"
  gem "jekyll-seo-tag", "~> 2.8"
end

# Windows зависимости (wdm отключён: несовместим с Ruby 3.4, не нужен на GitHub Pages)
platforms :windows, :mswin, :mingw, :x64_mingw, :jruby do
  gem "tzinfo", ">= 2.0"
  gem "tzinfo-data"
  # gem "wdm", "~> 0.1.1"
end

# Для Ruby 3.4+ — stdlib gems исключены из поставки Ruby
gem "webrick", "~> 1.8"
gem "csv", ">= 3.0"

# Обновленные зависимости для безопасности
gem "activesupport", ">= 7.0.8"
gem "nokogiri", ">= 1.16.2"
gem "kramdown", ">= 2.4.0"
gem "addressable", ">= 2.8.5"
gem "commonmarker", ">= 0.23.10"
