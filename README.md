# install-packages

packages= ['java', 'git', 'python']
packages.each do |pkg|
    package pkg do
  action :install
end
end

