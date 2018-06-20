---
name: Bitbucket
x-slug: bitbucket
description: Collaborate on code with inline comments and pull requests. Manage and
  share your Git repositories to build and ship software, as a team.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19810-bitbucket.jpg
x-kinRank: "8"
x-alexaRank: "901"
tags: Steps
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/steps/master/_listings/bitbucket/apis.md
specificationVersion: "0.14"
apis:
- name: Bitbucket Get Repositories Username Repo Slug Pipelines Pipeline Uu Steps
  x-api-slug: bitbucket
  description: Get repositories username repo slug pipelines pipeline uu steps
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19810-bitbucket.jpg
  humanURL: http://bitbucket.org
  baseURL: https://api.bitbucket.org//2.0//repositories/{username}/{repo_slug}/pipelines/{pipeline_uuid}/steps/
  tags: Repositories, Username, Repo, Slug, Pipelines, Pipeline, Uu, Steps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/steps/master/_listings/bitbucket/repositoriesusernamerepo-slugpipelinespipeline-uuidsteps-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/steps/master/_listings/bitbucket/repositoriesusernamerepo-slugpipelinespipeline-uuidsteps-get-openapi.md
- name: Bitbucket Get Repositories Username Repo Slug Pipelines Pipeline Uu Steps
    Step Uu
  x-api-slug: bitbucket
  description: Get repositories username repo slug pipelines pipeline uu steps step
    uu
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19810-bitbucket.jpg
  humanURL: http://bitbucket.org
  baseURL: https://api.bitbucket.org//2.0//repositories/{username}/{repo_slug}/pipelines/{pipeline_uuid}/steps/{step_uuid}
  tags: Repositories, Username, Repo, Slug, Pipelines, Pipeline, Uu, Steps, Step,
    Uu
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/steps/master/_listings/bitbucket/repositoriesusernamerepo-slugpipelinespipeline-uuidstepsstep-uuid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/steps/master/_listings/bitbucket/repositoriesusernamerepo-slugpipelinespipeline-uuidstepsstep-uuid-get-openapi.md
- name: Bitbucket Get Repositories Username Repo Slug Pipelines Pipeline Uu Steps
    Step Uu Log
  x-api-slug: bitbucket
  description: |-
    Retrieve the log file for a given step of a pipeline.

    This endpoint supports (and encourages!) the use of [HTTP Range requests](https://tools.ietf.org/html/rfc7233) to deal with potentially very large log files.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19810-bitbucket.jpg
  humanURL: http://bitbucket.org
  baseURL: https://api.bitbucket.org//2.0//repositories/{username}/{repo_slug}/pipelines/{pipeline_uuid}/steps/{step_uuid}/log
  tags: Repositories, Username, Repo, Slug, Pipelines, Pipeline, Uu, Steps, Step,
    Uu, Log
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/steps/master/_listings/bitbucket/repositoriesusernamerepo-slugpipelinespipeline-uuidstepsstep-uuidlog-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/steps/master/_listings/bitbucket/repositoriesusernamerepo-slugpipelinespipeline-uuidstepsstep-uuidlog-get-openapi.md
- name: Bitbucket
  x-api-slug: bitbucket
  description: Collaborate on code with inline comments and pull requests. Manage
    and share your Git repositories to build and ship software, as a team.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19810-bitbucket.jpg
  humanURL: http://bitbucket.org
  baseURL: https://api.bitbucket.org//2.0
  tags: Steps
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/steps/master/_listings/bitbucket/openapi.md
x-common:
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