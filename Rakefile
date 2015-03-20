require 'html/proofer'

task :test do
  sh 'hugo'
  HTML::Proofer.new('./public').run
end

task default: :test
