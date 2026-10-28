![](images/mongoid.png)

Source for [mongoid.github.io](https://mongoid.github.io), the independent Mongoid community website. [Mongoid itself](https://github.com/mongodb/mongoid) is maintained by MongoDB; this site highlights maintained community libraries and links to the official documentation.

The homepage lists the latest releases in the current and previous major lines and a curated directory of active projects. Historical documentation under `old/` is retained to preserve existing URLs.

Use Ruby 3.3 or newer:

```sh
bundle install
bundle exec jekyll build --strict_front_matter
bundle exec jekyll serve
```

Open [localhost:4000](http://localhost:4000). The bundle stays compatible with GitHub Pages' branch-based Jekyll deployment, and pull requests run a production build.

See [CONTRIBUTING](CONTRIBUTING.md) for content maintenance and contribution instructions.
