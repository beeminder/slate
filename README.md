Beeminder API Documentation
---------------------------

<p align="center"><em>The Beeminder api docs are created with Slate. Check it out at <a href="https://lord.github.io/slate">lord.github.io/slate</a>.</em></p>

To Do
------------

* DNS for github pages / beeminder subdomain
* update errors section
* add / update static links in nav 
* edit pass w/ current beeminder docs
* add a "how to contribute" section (or link to this repo & update README here)
* favicon
* smaller / better logo?
* Doesn't actually say "Beeminder API Documentation" anywhere yet 

Contributing 
------------------------------

If you're working on building something with our API and you run into confusion, we'd love to hear about it!
If something's not clear in the docs, or something's not working as you expect it to, it might be us, not you!
If you do find something that needs clarification or is just plain wrong, we'd love a pull request with fixes or edits. 


### Prerequisites

You're going to need:

 - **Linux or OS X** — Windows may work, but is unsupported.
 - **Ruby, version 2.2.5 or newer**
 - **Bundler** — If Ruby is already installed, but the `bundle` command doesn't work, just run `gem install bundler` in a terminal.

### Getting Set Up

1. Fork this repository on Github.
2. Clone *your forked repository* (not our original one) to your hard drive with `git clone https://github.com/YOURUSERNAME/slate.git`
3. `cd slate`
4. Initialize and start Slate. You can either do this locally, or with Vagrant:

```shell
# either run this to run locally
bundle install
bundle exec middleman server

# OR run this to run with vagrant
vagrant up
```

You can now see the docs at http://localhost:4567. Whoa! That was fast!

### Submitting 

Once you've made your changes, you can submit a pull request to beeminder/slate!

Need Help? Found a bug?
--------------------

[Submit an issue](https://github.com/beeminder/slate/issues), or email support@beeminder.com if you need any help.


