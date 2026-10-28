Contributing
============

The https://mongoid.github.io site is work of [many contributors](https://github.com/mongoid/mongoid.github.io/graphs/contributors). You're encouraged to submit [pull requests](https://github.com/mongoid/mongoid.github.io/pulls) and [propose topics](https://github.com/mongoid/mongoid.github.io/issues). Ask Mongoid usage questions in the [MongoDB Community Forums](https://www.mongodb.com/community/forums/tag/mongoid-odm).

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

Use Ruby 3.3 or newer and the committed GitHub Pages-compatible bundle. Ensure that the production site builds before submitting a pull request.

```
bundle install
JEKYLL_ENV=production bundle exec jekyll build --strict_front_matter
bundle exec jekyll serve
```

Navigate to http://localhost:4000.

#### Add Content

Create markdown content.

#### Maintain the Homepage

Update release numbers in `index.md` using [RubyGems](https://rubygems.org/gems/mongoid/versions) and [upstream releases](https://github.com/mongodb/mongoid/releases), and refresh the checked date. Distinguish the current major from the previous major without implying that they have the same support policy. Link to MongoDB's official documentation and compatibility tables rather than duplicating a compatibility matrix here.

List only non-archived projects with recent substantive default-branch maintenance or an active modernization pull request. Check the actual code and maintenance activity; a recent repository `updated_at` or incidental branch push alone is not sufficient. Keep descriptions concise, use canonical repository links, and let each project document its supported versions. Remove dormant projects from the homepage without deleting their repositories or historical documentation.

Preserve existing paths under `old/` and keep those references clearly labeled as historical. Keep Markdown paragraphs on one line.

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
git push --force-with-lease origin my-feature-branch
```

Keep the pull request focused and never force-push the default branch.

#### Be Patient

It's likely that your change will not be merged and that the nitpicky maintainers will ask you to do more, or fix seemingly benign problems. Hang on there!

#### Thank You

Please do know that we really appreciate and value your time and work. We love you, really.
