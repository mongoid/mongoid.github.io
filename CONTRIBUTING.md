Contributing
============

The https://mongoid.github.io site is work of [many contributors](https://github.com/mongoid/mongoid.github.io/graphs/contributors). You're encouraged to submit [pull requests](https://github.com/mongoid/mongoid.github.io/pulls) and [propose topics](https://github.com/mongoid/mongoid.github.io/issues). When in doubt, ask a question in the [MongoDB User Group](https://groups.google.com/group/mongodb-user).

#### Fork the Project

Fork the [project on Github](https://github.com/mongoid/mongoid.github.io) and check out your copy.

```
git clone https://github.com/contributor/mongoid.github.io.git
cd mongoid.github.io
git remote add upstream https://github.com/mongoid/mongoid.github.io.git
```

#### Create a Topic Branch

Make sure your fork is up-to-date and create a topic branch for your feature or bug fix.

```
git checkout master
git pull upstream master
git checkout -b my-feature-branch
```

#### Bundle Install and Run Jekyll

Ensure that you can build the project and run tests.

```
bundle install
bundle exec jekyll serve
```

Navigate to http://localhost:4000.

#### Add Content

Create markdown content.

#### Commit Changes

Make sure git knows your name and email address:

```
git config --global user.name "Your Name"
git config --global user.email "contributor@example.com"
```

Writing good commit logs is important. A commit log should describe what you did.

```
git add ...
git commit
```

#### Push

```
git push origin my-feature-branch
```

#### Make a Pull Request

Go to https://github.com/contributor/mongoid.github.io and select your feature branch. Click the 'Pull Request' button and fill out the form. Pull requests are usually reviewed within a few days.

#### Rebase

If you've been working on a change for a while, rebase with upstream/master.

```
git fetch upstream
git rebase upstream/master
git push origin my-feature-branch -f
```

Amend your previous commit and force push the changes.

```
git commit --amend
git push origin my-feature-branch -f
```

#### Be Patient

It's likely that your change will not be merged and that the nitpicky maintainers will ask you to do more, or fix seemingly benign problems. Hang on there!

#### Thank You

Please do know that we really appreciate and value your time and work. We love you, really.
