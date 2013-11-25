site :opscode

metadata
cookbook 'rbenv', :git => 'https://github.com/fnichol/chef-rbenv.git', :ref => 'v0.7.2'

group :integration do
  cookbook "apt"
  cookbook "yum"
  cookbook "passenger_apache2_test", :path => "./test/cookbooks/passenger_apache2_test"
end
