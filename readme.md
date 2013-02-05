# What is this?
This is [Veewee](https://github.com/jedi4ever/veewee) Template for a Centos 5.8 box. It contains Chef 10.18 installed via the omnibus installer (and therefor in /opt/chef), no puppet.

# How To build the Box

		bundle install
		alias vagrant="bundle exec vagrant"
		vagrant basebox build 'centOs58-x86'
		vagrant basebox export centOs58-x86
		

