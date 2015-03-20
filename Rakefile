require 'html/proofer'

task :test do
  sh 'hugo'
  HTML::Proofer.new('./public',
    href_ignore: [%r{github\.com/18F/DevOps}i]
  ).run
end

task default: :test
