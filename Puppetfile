# This is a Puppetfile, which describes a collection of Puppet modules. For
# format and syntax examples, see one of the following resources:
#
# https://github.com/rodjek/librarian-puppet/blob/master/README.md
# https://github.com/adrienthebo/r10k/blob/master/README.markdown
#

#=============================================================================
# ENVIRONMENT: integration
#=============================================================================
#
# This Puppetfile is for the Puppet environment listed above. It should be in a
# git branch by the same name.
#
# COPYING: to make a copy, or "fork" an environment, follow these steps.
#
#   1. Make sure your local repository is up to date
#        `git fetch origin`
#   2. Create a new git branch based on the environment you want to fork
#        `git checkout -b <new_env_name> origin/<source_env_name>`
#   3. In the now forked environment, edit this file and change the
#      environment comment above to the new name
#
# Example:
#
#   git fetch origin
#   git checkout -b feature_ticket_15432 integration
#   vim Puppetfile

##
# SITE CODE
#
# In the integration environment, site data (site.pp, roles, profiles, hiera
# data, hiera.yaml, etc) is deployed from the master branch of the
# puppet-site-code repo. In later environments specific versions of the site
# code is deployed.
#
basemod 'code',
    :git => 'https://github.com/reidmv/puppet-site-code.git',
    :ref => 'master'

##
# MODULES
#
# Each module here should be assigned a specific version (tag or commit). When
# developing a module in a forked development environment, edit the module
# you're working on below such that it is deployed from your module development
# branch
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
