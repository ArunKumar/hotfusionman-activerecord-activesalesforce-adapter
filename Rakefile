begin
  require 'jeweler'
  Jeweler::Tasks.new do |gemspec|
    gemspec.name = "hotfusionman-activerecord-activesalesforce-adapter"
    gemspec.summary = "ActiveSalesforce (ASF) is a Rails connection adapter that provides direct access to Salesforce.com hosted data and metadata via the ActiveRecord model layer. Objects, fields, and relationships are all auto surfaced as ActiveRecord attributes and rels."
    gemspec.email = 'HotFusionMan@GMail.com'
    gemspec.homepage = "http://github.com/HotFusionMan/hotfusionman-activerecord-activesalesforce-adapter"
    gemspec.authors = ["Doug Chasman","Luigi Montanez","Senthil Nayagam","Justin Ball","Jesse Hallett", "Andrew Freeberg", 'Albert Davidson Chou']
    
    gemspec.test_files = Dir.glob( 'test/**/*.rb' )
    
    gemspec.add_dependency('rails', '>= 2.3.3')
    gemspec.add_dependency('builder', '>= 1.2.4')
    gemspec.add_dependency('hpricot', '>=0.8.2')

    
  end
rescue LoadError
  puts "Jeweler not available. Install it with: sudo gem install jeweler"
end
