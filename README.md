
Gravata aside in Octopress
===================

installation
---------------

1. copy `gravatar.html` to `/path/to/octopress-repo/source/_includes/custom/asides`.

2. opne `_config.yml` file.

3. add `custom/aside/gravatar.html` to `default_asides` property.

4. add `gravatar_hash` property to "3rd Party Settings" and setting [your emai hash][gravatar-help] to this prop.
```
	# Gravatar email hash
	gravatar_hash: (your e-mail md5 hash (when registered to the Gravatar))
```

5. `rake gen_deploy`, enjoy!

license
----------------
MIT

-----------------

<address>&copy; 2013 alalwww.</address>

[gravatar-help]: http://www.gravatar.com/site/implement/hash/ "Creating the Hash"
