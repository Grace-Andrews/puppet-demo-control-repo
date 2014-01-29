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

mod 'seteam/profile', '0.2.3'
# └─⌉
#    mod 'nanliu/staging', '0.3.1'
    mod 'seteam/splunk', '3.0.1'
#   │ └─⌉
        mod 'puppetlabs/inifile', '1.0.0'
    mod 'seteam/tomcat', '0.1.0'
#   │ └─⌉
        mod 'puppetlabs/java', '1.0.1'
#   │     └─⌉
            mod 'puppetlabs/stdlib', '4.1.0'
    mod 'stahnma/epel', '0.0.5'
mod 'puppetlabs/firewall',   '0.4.2'
mod 'joshcooper/powershell', '0.0.6'
mod 'puppetlabs/dism', '0.1.0'
mod 'simondean/iis', '0.1.3'
mod 'dotnetcms',
  :git => 'git@github.com:mrzarquon/dotnetcms.git',
  :ref => 'a5469eefc38bf65a03d1f46a428fa06b647fc740'
mod 'staging',
  :git => 'git@github.com:nanliu/puppet-staging.git',
  :ref => '7b3a69b184d22cff6e8b5bfa0de511481ae46d70'
