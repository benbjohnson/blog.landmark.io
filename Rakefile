require 'open-uri'

namespace :landmark do
  task :assets do
    IO.write("css/landmark.css", open("http://landmark.io/assets/application.css").read)
    IO.write("js/landmark.js", open("http://landmark.io/assets/application.js").read)
  end
end