require 'bundler/gem_tasks'
require 'rake/testtask'
require 'deploy_my_gem/task'

Rake::TestTask.new do |t|
  t.libs << 'test'
  t.test_files = FileList['test/test*.rb']
  t.verbose = true
end
