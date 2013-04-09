guard :shell do
  watch /^(.*\.text)$/ do |match|
    `slideshow --output target #{match} --h2`
  end
end
