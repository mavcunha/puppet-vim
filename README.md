# vim Puppet Module for Boxen

Install [vim](http://www.vim.org/) along with [vundle](https://github.com/gmarik/vundle), an easy way to install vim bundles.

This package won't interfere the [puppet-macvim](https://github.com/boxen/puppet-macvim) package.

## Usage
The following example will install vim and vundle.

    include vim


## Required Puppet Modules

* `boxen`
* `boxen-repository`
* `puppetlabs-stdlib`
* `boxen-python`
