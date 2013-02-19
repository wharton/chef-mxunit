Description
===========

Installs the MXUnit framework for ColdFusion.

Requirements
============

Cookbooks
---------

coldfusion902

Attributes
==========

* `node['mxunit']['install_path']` (Default is /vagrant/wwwroot)
* `node['mxunit']['owner']` (Default is `nil` which will result in owner being set to `node['cf10']['installer']['runtimeuser']`)
* `node['mxunit']['group']` (Default is bin)
* `node[''mxunit']['download']['url']` (Default is https://github.com/downloads/mxunit/mxunit/mxunit-2.1.1.zip)

Usage
=====

On ColdFusion server nodes:

    include_recipe "mxunit"

