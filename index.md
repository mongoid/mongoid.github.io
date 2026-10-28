---
layout: default
comments: false
---

## Mongoid Community Organization

Mongoid is the officially supported object-document mapper (ODM) for MongoDB in Ruby. [MongoDB maintains Mongoid itself](https://github.com/mongodb/mongoid); the [Mongoid community organization](https://github.com/mongoid) is an independent group of open-source contributors maintaining libraries and tools around it.

## Mongoid Releases and Documentation

Latest stable releases, checked October 28, 2026:

| Release line | Latest release | Release notes |
|:---:|:---:|:---:|
| Current major: 9.x | [9.1.1](https://rubygems.org/gems/mongoid/versions/9.1.1) | [v9.1.1](https://github.com/mongodb/mongoid/releases/tag/v9.1.1) |
| Previous major: 8.x | [8.1.13](https://rubygems.org/gems/mongoid/versions/8.1.13) | [v8.1.13](https://github.com/mongodb/mongoid/releases/tag/v8.1.13) |

Start with the [current documentation](https://www.mongodb.com/docs/mongoid/current/), [API reference](https://www.mongodb.com/docs/mongoid/current/api/), and [upgrade notes](https://www.mongodb.com/docs/mongoid/current/reference/release-notes/). Check the official [compatibility tables](https://www.mongodb.com/docs/drivers/compatibility/?driver-language=ruby&ruby-driver-framework=mongoid) before choosing Ruby, Rails, MongoDB Server, or Ruby driver versions. Listing a previous major here does not imply the same support or compatibility as the current release.

## Active Community Projects

These projects have recent substantive maintenance or active modernization work. Each project's README and CI matrix describe its own compatibility; inclusion does not mean every project supports every Mongoid version.

| Project | Purpose |
|---|---|
| [delayed_job_shallow_mongoid](https://github.com/mongoid/delayed_job_shallow_mongoid) | Store references to Mongoid documents instead of full objects in delayed_job payloads. |
| [mongo_session_store](https://github.com/mongoid/mongo_session_store) | Rails sessions backed by MongoDB, using Mongoid or the Ruby driver. |
| [mongoid-cached-json](https://github.com/mongoid/mongoid-cached-json) | Cache nested JSON representations of Mongoid documents. |
| [mongoid-collection-snapshot](https://github.com/mongoid/mongoid-collection-snapshot) | Maintain collections of processed data. |
| [mongoid-compatibility](https://github.com/mongoid/mongoid-compatibility) | Compatibility helpers for multiple Mongoid versions. |
| [mongoid-geospatial](https://github.com/mongoid/mongoid-geospatial) | Geospatial fields and queries, with optional GeoRuby/RGeo support. |
| [mongoid-grid_fs](https://github.com/mongoid/mongoid-grid_fs) | GridFS file storage through Mongoid. |
| [mongoid-history](https://github.com/mongoid/mongoid-history) | Track document history, audit changes, and support undo/redo. |
| [mongoid-locker](https://github.com/mongoid/mongoid-locker) | Document-level locking. |
| [mongoid-observers](https://github.com/mongoid/mongoid-observers) | Observer callbacks extracted from Mongoid core. |
| [mongoid-rspec](https://github.com/mongoid/mongoid-rspec) | RSpec matchers and macros for Mongoid models. |
| [mongoid-scroll](https://github.com/mongoid/mongoid-scroll) | Cursor-based pagination and infinite scrolling. |
| [mongoid-shell](https://github.com/mongoid/mongoid-shell) | Derive shell commands from Mongoid configuration. |
| [mongoid-slug](https://github.com/mongoid/mongoid-slug) | Generate URL slugs and permalinks from document fields. |
| [mongoid-tag-collectible](https://github.com/mongoid/mongoid-tag-collectible) | Maintain tag collections and aggregate counts. |
| [mongoid_fulltext](https://github.com/mongoid/mongoid_fulltext) | N-gram-based full-text and fuzzy search. |
| [mongoid_orderable](https://github.com/mongoid/mongoid_orderable) | Maintain ordered lists of documents. |
| [mongoid_search](https://github.com/mongoid/mongoid_search) | Full-text search with relevance matching. |

Archived repositories, dormant demos, the old Mongoid fork, and legacy standalone drivers are not part of this directory. The [organization's repository list](https://github.com/orgs/mongoid/repositories) remains available for historical projects.

## Get Involved

We welcome maintained Mongoid-related projects into the community organization. See [adding a project](/misc/adding) for the transfer and maintenance process, or [contribute to this website](https://github.com/mongoid/mongoid.github.io/blob/master/CONTRIBUTING.md).

For Mongoid itself, use the [MongoDB Community Forums](https://www.mongodb.com/community/forums/tag/mongoid-odm) for questions and the [MONGOID issue tracker](https://jira.mongodb.org/browse/MONGOID) for bug reports. Report community-library issues in the corresponding project's GitHub repository.

## Historical Documentation

The [Mongoid 4](/old/en/mongoid/index.html) and [Mongoid 3](/old/en/mongoid/v3/index.html) documentation is preserved for existing links and legacy applications. It is not documentation for current releases.
