# This is a Puppetfile, which describes a collection of Puppet modules. For
# format and syntax examples, see one of the following resources:
#
# https://github.com/rodjek/librarian-puppet/blob/master/README.md
# https://github.com/adrienthebo/r10k/blob/master/README.markdown
#

#=============================================================================
# ENVIRONMENT: production
#=============================================================================
#
# This Puppetfile is for the Puppet environment listed above. It should be in a
# git branch by the same name.
#
# For development instructions, see the integration environment's Puppetfile

##
# SITE CODE
#
# Should be assigned a specific version (tag or commit).
#
basemod 'code',
    :git => 'https://github.com/puppetlabs/puppet-site-code.git',
    :ref => '1.1'

##
# MODULES
#
# Each module here should be assigned a specific version (tag or commit).
#
mod 'puppetlabs/stdlib',
  :git => 'https://github.com/puppetlabs/puppetlabs-stdlib.git',
  :ref => '4.20.0'
mod 'lwf/remote_file',
  :git => 'https://github.com/lwf/puppet-remote_file.git',
  :ref => '1.1.3'
mod 'puppetlabs/concat',
  :git => 'https://github.com/puppetlabs/puppetlabs-concat.git',
  :ref => '4.1.0'
mod 'puppetlabs/powershell',
  :git => 'https://github.com/puppetlabs/puppetlabs-powershell.git',
  :ref => '2.1.2'
mod 'puppetlabs/inifile',
  :git => 'https://github.com/puppetlabs/puppetlabs-inifile.git',
  :ref => '2.0.0'
mod 'puppetlabs/puppet_agent',
  :git => 'https://github.com/puppetlabs/puppetlabs-puppet_agent.git',
  :ref => '1.4.1'
