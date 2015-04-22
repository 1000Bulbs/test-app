desc "Pretend to do some work"
task :worker do
  while true do
    puts "#{Time.now} - We're pretending to do some work!"
    STDERR.puts "#{Time.now} - This is STDERR?"
    puts "Here's ENV['TEST_APP_VAR']: #{ENV['TEST_APP_VAR']}"
    sleep 2
  end
end