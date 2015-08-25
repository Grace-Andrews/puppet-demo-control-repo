# This is a Puppetfile, which describes a collection of Puppet modules. For
# format and syntax examples, see one of the following resources:
#
# https://github.com/rodjek/librarian-puppet/blob/master/README.md
# https://github.com/adrienthebo/r10k/blob/master/README.markdown
#
# Brief example:
#
#   mod 'puppetlabs/stdlib', '4.1.0'
#
# The default production environment for the SE Team is just going to pull in
# the current version of our "profile" module from the Forge and whatever
# dependencies it has.

forge "https://forgeapi.puppetlabs.com"

# PL Modules
mod 'puppetlabs/ntp', '4.1.0'
mod 'puppetlabs/firewall', '1.7.0'
mod 'puppetlabs/mysql', '3.5.0'
mod 'puppetlabs/puppetserver_gem', '0.1.0'

# Community Modules
mod 'stahnma/epel', '1.0.2'

# TSE modules - either maintained under seteam or by individual SE's
mod 'razordemo',
  :git => 'git@github.com:puppetlabs/tse-module-razordemo.git',
  :ref => 'v2.1'

mod 'nginxdemo',
  :git => 'git@github.com:kaipak/nginx_puppet_demo.git',
  :ref => 'a996d3ea31eb7c6f6b93354aac7a6c29593dcffe'
  :branch => 'development'
