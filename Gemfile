source "https://rubygems.org"

# 使用 GitHub Pages（会自动包含 Jekyll 和所有兼容插件）
gem "github-pages", "~> 232", group: :jekyll_plugins

# 额外的插件（GitHub Pages 白名单里的才能用）
group :jekyll_plugins do
  gem "jekyll-remote-theme", "~> 0.4.0"
  gem "jekyll-toc", "~> 0.19.0"
  gem "jekyll-seo-tag", "~> 2.8"  # ← 添加这行
end

# Windows 和 JRuby 支持
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Windows 性能优化
gem "wdm", "~> 0.1", :platforms => [:mingw, :x64_mingw, :mswin]

# JRuby 兼容性
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]
