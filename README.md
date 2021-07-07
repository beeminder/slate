# Beeminder API Documentation

This repository contains the source for the website of the Beeminder API Reference https://api.beeminder.com.

To Do
------------

* More prominent link to Beeminder
* [for bee] Possibly update links to api in beeminder/beeminder to have target=blank

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
2. Clone *your forked repository* (not our original one) to your hard drive with `git clone https://github.com/YOURUSERNAME/apidocs.git`
3. `cd apidocs`
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

Once you've made your changes, you can submit a pull request to beeminder/apidocs!

### Deploying changes to the docs

(For beeminder/apidocs owners)

1. Commit changes and push to the master branch at beeminder/apidocs (or accept / merge pull request) 
2. Run ./deploy.sh 

* Do not touch the gh-pages branch
* Double check if api.beeminder.com is still available.[1]

[1] There was a problem where the custom domain setting was getting unset every time we deployed. It looks like I've successfully fixed it now, but if you check after deploy and the subdomain is broken (e.g. you get redirect to the github pages url) then go quickly into https://github.com/beeminder/apidocs/settings and re-add "api.beeminder.com" under 'Custom domain').



Need Help? Found a bug?
--------------------

[Submit an issue](https://github.com/beeminder/slate/issues), or email support@beeminder.com if you need any help.


<br>
<br>
<p align="center"><em>The Beeminder api docs are created with Slate. Check it out at <a href="https://lord.github.io/slate">lord.github.io/slate</a>.</em></p>


