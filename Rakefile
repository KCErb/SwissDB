$:.unshift("/Library/RubyMotion/lib")

require 'motion/project/template/android'

begin
  require 'bundler'
  require 'motion/project/template/gem/gem_tasks'
  Bundler.require
rescue LoadError
end


require 'init'


Motion::Project::App.setup do |app|
  # Use `rake config' to see complete project settings.
  app.name = 'SwissDB'
end