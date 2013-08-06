

## Bundler

Bundle install 安装 Gemfile 里面的 gem

Bundle Package 打包 gem 到 vendor/cache 目录下,
可以避免外部依赖，或者包含私有的资源。


## initialize

config/environment.rb -> 
config/application.rb ->
config/boot.rb ->
rails/all


## LoadPath

config.autoload_paths += %W(#{config.root}/app/presenters)

## TimeZone

config.time_zone = 'Central Time (US & Canada)'

[All Available TimeZone](http://api.rubyonrails.org/classes/ActiveSupport/TimeZone.html)

## Filter Parameter Logging

在 filter_parameter_logging.rb 里面定义的需要过滤的参数


## Development Mode

1. Automatic Class Reloading
2. Eager Load
3. Error Reports
4. Caching -- no
5. Raise Delivery Errors
6. Deprecation Notices
7. Pending Migrations Error Page
8. Assets Debug Mode

Test Mode, Production Mode

## colorize log

Rails::Subscriber.colorize_logging
syslog
1. 





