task :build_scss do
  sh 'rm bootstrap.css bootstrap.min.css'
  sh 'scss lib/scss/bootstrap.scss > bootstrap.css'
  sh 'scss -t compressed lib/scss/bootstrap.scss > bootstrap.min.css'
end