source 'https://supermarket.chef.io'

metadata

cookbook 'marker', github: 'rightscale-cookbooks/marker'
cookbook 'machine_tag', github: 'rightscale-cookbooks/machine_tag'

group :integration do
  cookbook 'fake', path: './test/cookbooks/fake'
end
