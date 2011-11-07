task :build_sass do
  sh 'rm bootstrap.css bootstrap.min.css'
  sh 'sass lib/bootstrap.sass > bootstrap.css'
  sh 'sass -t compressed lib/bootstrap.sass > bootstrap.min.css'
end