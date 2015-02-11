## Sensu-Plugins-disk-checks

[![Build Status](https://travis-ci.org/sensu-plugins/sensu-plugins-openstack.svg?branch=master)][1]
[![Gem Version](https://badge.fury.io/rb/sensu-plugins-openstack.svg)][2]
[![Code Climate](https://codeclimate.com/github/sensu-plugins/sensu-plugins-openstack/badges/gpa.svg)][3]
[![Test Coverage](https://codeclimate.com/github/sensu-plugins/sensu-plugins-openstack/badges/coverage.svg)][4]
[![Dependency Status](https://gemnasium.com/sensu-plugins/sensu-plugins-openstack.svg)][5]

## Functionality

## Files
 *
 *
 *
 *

## Usage

## Installation

Add the public key (if you haven’t already) as a trusted certificate

```
gem cert --add <(curl -Ls https://raw.githubusercontent.com/sensu-plugins/sensu-plugins.github.io/master/certs/sensu-plugins.pem)
gem install sensu-plugins-openstack -P MediumSecurity
```

You can also download the key from /certs/ within each repository.

#### Rubygems

`gem install sensu-plugins-openstack`

#### Bundler

Add *sensu-plugins-disk-checks* to your Gemfile and run `bundle install` or `bundle update`

#### Chef

Using the Sensu **sensu_gem** LWRP
```
sensu_gem 'sensu-plugins-openstack' do
  options('--prerelease')
  version '0.0.1.alpha.4'
end
```

Using the Chef **gem_package** resource
```
gem_package 'sensu-plugins-openstack' do
  options('--prerelease')
  version '0.0.1.alpha.4'
end
```

## Notes

[1]:[https://travis-ci.org/sensu-plugins/sensu-plugins-openstack]
[2]:[http://badge.fury.io/rb/sensu-plugins-openstack]
[3]:[https://codeclimate.com/github/sensu-plugins/sensu-plugins-openstack]
[4]:[https://codeclimate.com/github/sensu-plugins/sensu-plugins-openstack]
[5]:[https://gemnasium.com/sensu-plugins/sensu-plugins-openstack]
