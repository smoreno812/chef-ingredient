source 'https://supermarket.chef.io'

metadata

cookbook 'compat_resource', '>= 12.10'

cookbook 'chef_services', git: 'https://github.com/smoreno812/chef_services.git'


group :integration do
  cookbook 'git'
  cookbook 'apt'
end
