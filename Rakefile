# basic Rake file

desc "Build site with production env"
task :deploy do
  ENV["JEKYLL_ENV"] = "server"
  sh "jekyll build"
end
