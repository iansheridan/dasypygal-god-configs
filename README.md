Dasypygal god Configs
=====================

These are my config files that I use. I will be adding to it and I wanted a central place to hold them.

Dags

Usage and Cavets
----------------

The god config files will be relitively easy to understand. The same for the `init.d` file.

What you have to watch out for is that I use [RVM][1] and accordingly
you should know that I use wrapper scripts to make sure that the needed
environmental variables are set. For instance on [line 7][2] you will
find `/bin/blog_unicorn` that is a wrapper script created with [RVM][1].


[1]: https://rvm.beginrescueend.com/
[2]: https://github.com/iansheridan/dasypygal-god-configs/blob/master/config/unicorn-sinatra-app.god#L7
