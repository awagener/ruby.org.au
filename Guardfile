guard :shell do
#guard 'rake', :task => 'build:stylesheets' do
  watch(%r{^stylesheets/.+\.scss$}) { `rake build:stylesheets` }
end

guard :shell do
#guard 'rake', :task => 'build:pages' do
  watch(%r{^pages/.+\.html\.erb}) { `rake build:pages` }
end
