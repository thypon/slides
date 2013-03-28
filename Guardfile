guard :shell do
  watch /^(.*\.text)$/ do |match|
    `slideshow --output target --template csss #{match} --h2`
  end
end
