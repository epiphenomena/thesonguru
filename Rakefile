desc "Rsync website to Dreamhost"
task :sync do
    sh "rsync -avzzh --progress --delete --exclude .git --exclude Rakefile ./ aryn:thesonguru.com/"
end

desc "Run development server"
task :serve do
    sh "php -S localhost:8001 -t ./public/"
end