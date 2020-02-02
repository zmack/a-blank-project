require 'rake/testtask'

Rake::TestTask.new do |t| 
  t.libs << 'tests' # adds the tests directory to the lists of directories in the #$LOADPATH 
  t.test_files = FileList['test*.rb']
  t.verbose = true 
end
