task :spec do
  specs = Dir.glob('spec/**/*_spec.rb')
  sh "macruby -r #{specs.join(' -r ')} -e ''"
end

task :default => :spec
