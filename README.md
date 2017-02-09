Laptop
======

Laptop is a script to set up my macOS laptop.

It can be run multiple times on the same machine safely.
It installs, upgrades, or skips packages
based on what is already installed on the machine.

Forked from [thoughtbot/laptop](https://github.com/thoughtbot/laptop) script.

Install
-------

Download and execute the script:

```sh
curl https://raw.githubusercontent.com/ryanaghdam/laptop/master/mac | sh 2>&1 | tee ~/laptop.log
```

Debugging
---------

Your last Laptop run will be saved to `~/laptop.log`.
Read through it to see if you can debug the issue yourself.
If not, copy the lines where the script failed into a
[new GitHub Issue](https://github.com/thoughtbot/laptop/issues/new) for us.
Or, attach the whole log file as an attachment.

What it sets up
---------------

macOS tools:

* [Homebrew] for managing operating system libraries.

[Homebrew]: http://brew.sh/

Unix tools:

* [RCM] for managing company and personal dotfiles

[RCM]: https://github.com/thoughtbot/rcm


License
-------

Laptop is © 2011-2016 thoughtbot, inc.
It is free software,
and may be redistributed under the terms specified in the [LICENSE] file.

[LICENSE]: LICENSE

About thoughtbot
----------------

![thoughtbot](https://thoughtbot.com/logo.png)

Laptop is maintained and funded by thoughtbot, inc.
The names and logos for thoughtbot are trademarks of thoughtbot, inc.

We are passionate about open source software.
See [our other projects][community].
We are [available for hire][hire].

[community]: https://thoughtbot.com/community?utm_source=github
[hire]: https://thoughtbot.com?utm_source=github
