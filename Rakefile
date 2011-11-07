task :build_sass do
  sh 'rm bootstrap.css bootstrap.min.css'
  sh 'sass lib/sass/bootstrap.sass > bootstrap.css'
  sh 'sass -t compressed lib/sass/bootstrap.sass > bootstrap.min.css'
end