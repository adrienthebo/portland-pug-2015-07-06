guard :shell do
  watch(/^(slides|css)/) do |m|
    [
      "bundle exec rev-present"
    ].each do |cmd|
      puts %x[#{cmd}]
    end
  end
end
