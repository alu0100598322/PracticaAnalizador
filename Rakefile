desc "Generates out.pdf containing the listings"

task :default do
  sh "a2ps --columns=1 -f 8 -R index.html -o out.ps"
  sh "ps2pdf out.ps out.pdf"
end

task :clean do
  sh 'rm -f out.pdf out.ps out.ps~'
end