guard :shell do
  watch /^(.*\.text)$/ do |match|
    `slideshow --output target #{match} --h2`
    `cp *.png target`
  end
end
