task :build do
  sh "staticmatic build ."
  sh "rm -r /srv/http/test/"
  sh "cp -r site /srv/http/test/"
end
