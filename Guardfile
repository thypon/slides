guard :shell do
  watch /^(.*\.text)$/ do |match|
    `slideshow --template csss --output target #{match} --h2`
    `cp images/*.png target`
  end
end
