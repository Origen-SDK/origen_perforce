# Origen Perforce

This plugin provides a driver for the Perforce revision control system that is fully compliant with the
[Origen Revision Control API](http://origen-sdk.org/origen/guides/misc/revisioncontrol/).

It is not included in Origen core since it makes use of a 3rd party gem (p4ruby) which can be problematic to install in certain environments.
Therefore, it was decided to limit this dependency only to those who actually want to use the Perforce driver by providing it via a plugin.

To use the Perforce driver, simply add this to your Gemfile:

~~~ruby
gem 'origen_perforce'
~~~
