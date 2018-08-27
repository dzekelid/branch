---
name: Bitbucket
x-slug: bitbucket
description: Collaborate on code with inline comments and pull requests. Manage and
  share your Git repositories to build and ship software, as a team.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19810-bitbucket.jpg
x-kinRank: "8"
x-alexaRank: "901"
tags: Branch
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/branch/master/_listings/bitbucket/apis.md
specificationVersion: "0.14"
apis:
- name: Bitbucket - Get Repositories Username Repo Slug Branch Restrictions
  x-api-slug: repositoriesusernamerepo-slugbranchrestrictions-get
  description: |-
    Returns a paginated list of all branch restrictions on the
    repository.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19810-bitbucket.jpg
  humanURL: http://bitbucket.org
  baseURL: https://api.bitbucket.org//2.0
  tags: Imports, Stack Network, Developers, Code, Technology, SaaS, Enterprise, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/branch/master/_listings/bitbucket/repositoriesusernamerepo-slugbranchrestrictions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/branch/master/_listings/bitbucket/repositoriesusernamerepo-slugbranchrestrictions-get-openapi.md
- name: Bitbucket - Parameters Repositories Username Repo Slug Branch Restrictions
  x-api-slug: repositoriesusernamerepo-slugbranchrestrictions-parameters
  description: Parameters repositories username repo slug branch restrictions
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19810-bitbucket.jpg
  humanURL: http://bitbucket.org
  baseURL: https://api.bitbucket.org//2.0
  tags: Imports, Stack Network, Developers, Code, Technology, SaaS, Enterprise, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/branch/master/_listings/bitbucket/repositoriesusernamerepo-slugbranchrestrictions-parameters-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/branch/master/_listings/bitbucket/repositoriesusernamerepo-slugbranchrestrictions-parameters-openapi.md
- name: Bitbucket - Add Repositories Username Repo Slug Branch Restrictions
  x-api-slug: repositoriesusernamerepo-slugbranchrestrictions-post
  description: |-
    Creates a new branch restriction rule for a repository.

    `kind` describes what will be restricted. Allowed values are: `push`,
    `force`, `delete`, and `restrict_merges`.

    Different kinds of branch restrictions have different requirements:

    * `push` and `restrict_merges` require `users` and `groups` to be
      specified. Empty lists are allowed, in which case permission is
      denied for everybody.
    * `force` can not be specified in a Mercurial repository.

    `pattern` is used to determine which branches will be restricted.

    A `'*'` in `pattern` will expand to match zero or more characters, and
    every other character matches itself. For example, `'foo*'` will match
    `'foo'` and `'foobar'`, but not `'barfoo'`. `'*'` will match all
    branches.

    `users` and `groups` are lists of user names and group names.

    `kind` and `pattern` must be unique within a repository; adding new
    users or groups to an existing restriction should be done via `PUT`.

    Note that branch restrictions with overlapping patterns are allowed,
    but the resulting behavior may be surprising.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19810-bitbucket.jpg
  humanURL: http://bitbucket.org
  baseURL: https://api.bitbucket.org//2.0
  tags: Imports, Stack Network, Developers, Code, Technology, SaaS, Enterprise, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/branch/master/_listings/bitbucket/repositoriesusernamerepo-slugbranchrestrictions-post-openapi.md
- name: Bitbucket - Delete Repositories Username Repo Slug Branch Restrictions
  x-api-slug: repositoriesusernamerepo-slugbranchrestrictionsid-delete
  description: Delete repositories username repo slug branch restrictions
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19810-bitbucket.jpg
  humanURL: http://bitbucket.org
  baseURL: https://api.bitbucket.org//2.0
  tags: Imports, Stack Network, Developers, Code, Technology, SaaS, Enterprise, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/branch/master/_listings/bitbucket/repositoriesusernamerepo-slugbranchrestrictionsid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/branch/master/_listings/bitbucket/repositoriesusernamerepo-slugbranchrestrictionsid-delete-openapi.md
- name: Bitbucket - Get Repositories Username Repo Slug Branch Restrictions
  x-api-slug: repositoriesusernamerepo-slugbranchrestrictionsid-get
  description: Get repositories username repo slug branch restrictions
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19810-bitbucket.jpg
  humanURL: http://bitbucket.org
  baseURL: https://api.bitbucket.org//2.0
  tags: Imports, Stack Network, Developers, Code, Technology, SaaS, Enterprise, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/branch/master/_listings/bitbucket/repositoriesusernamerepo-slugbranchrestrictionsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/branch/master/_listings/bitbucket/repositoriesusernamerepo-slugbranchrestrictionsid-get-openapi.md
- name: Bitbucket - Parameters Repositories Username Repo Slug Branch Restrictions
  x-api-slug: repositoriesusernamerepo-slugbranchrestrictionsid-parameters
  description: Parameters repositories username repo slug branch restrictions
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19810-bitbucket.jpg
  humanURL: http://bitbucket.org
  baseURL: https://api.bitbucket.org//2.0
  tags: Imports, Stack Network, Developers, Code, Technology, SaaS, Enterprise, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/branch/master/_listings/bitbucket/repositoriesusernamerepo-slugbranchrestrictionsid-parameters-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/branch/master/_listings/bitbucket/repositoriesusernamerepo-slugbranchrestrictionsid-parameters-openapi.md
- name: Bitbucket - Update Repositories Username Repo Slug Branch Restrictions
  x-api-slug: repositoriesusernamerepo-slugbranchrestrictionsid-put
  description: |-
    Updates an existing branch restriction rule.

    Fields not present in the request body are ignored.

    See [`POST`](../../branch-restrictions#post) for details.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19810-bitbucket.jpg
  humanURL: http://bitbucket.org
  baseURL: https://api.bitbucket.org//2.0
  tags: Imports, Stack Network, Developers, Code, Technology, SaaS, Enterprise, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/branch/master/_listings/bitbucket/repositoriesusernamerepo-slugbranchrestrictionsid-put-openapi.md
x-common:
- type: x-api-gallery
  url: http://bigoven.api.gallery.streamdata.io
- type: x-api-stack
  url: http://bitbucket.stack.network
- type: x-crunchbase
  url: https://crunchbase.com/organization/bitbucket
- type: x-developer
  url: https://developer.atlassian.com/cloud/bitbucket/
- type: x-documentation
  url: https://confluence.atlassian.com/bitbucket/bitbucket-cloud-documentation-221448814.html?_ga=2.77295890.629375793.1519179030-1077111323.1516485126
- type: x-status
  url: https://status.bitbucket.org/?_ga=2.76365714.629375793.1519179030-1077111323.1516485126
- type: x-support
  url: https://support.atlassian.com/bitbucket-cloud/
- type: x-terms-of-service
  url: https://www.atlassian.com/legal/customer-agreement?_ga=2.76365714.629375793.1519179030-1077111323.1516485126
- type: x-twitter
  url: https://twitter.com/bitbucket
- type: x-website
  url: http://bitbucket.org
- type: x-website
  url: https://bitbucket.org/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---