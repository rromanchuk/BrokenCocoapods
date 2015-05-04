# -*- coding: utf-8 -*-
$:.unshift("/Library/RubyMotion/lib")
require 'motion/project/template/ios'
require 'motion-env'
require 'motion-cocoapods'

begin
  require 'bundler'
  Bundler.require
rescue LoadError
end

Motion::Project::App.setup do |app|
  # Use `rake config' to see complete project settings.
  app.name = 'BrokenCocoapods'

  app.pods do
    platform :ios, '7.0'
    pod 'AWSCore'
    pod 'AWSS3'
    pod 'AWSCognito'
  end
end
