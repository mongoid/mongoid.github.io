---
layout: page
comments: false
title: Adding a Project to the Mongoid Org
---

## Moving a Project to the Mongoid Org

We encourage you to move projects into the Mongoid org to reduce bus factor. This enables continuity when you decide that you no longer want to be involved in your project.

1. [Open an issue](https://github.com/mongoid/mongoid.github.io/issues) with some information about the project.
2. We will grant you mongoid org permissions.
3. Transfer the project into the mongoid organization. You will continue being the project's maintainer, but you can now grant other people owner permissions so that they can add other maintainers.
4. Grant gem co-ownership to maintainers of this org via `gem owner --add dblock@dblock.org emily@mongodb.com durran@gmail.com`.
5. Fork the project off the mongoid org, make a pull request updating links. Feel free to merge it yourself and conduct business as usual.
6. Consider adding [danger.systems](https://github.com/mongoid/danger) for PR linting.

Thank you, we love you!
