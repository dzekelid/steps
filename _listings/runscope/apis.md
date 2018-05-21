---
name: Runscope
x-slug: runscope
description: Runscope was started with the idea that depending on a web service API
  in a mobile or web application should be as easy as depending on code running locally.
  We&rsquo;ve assembled a team of API, infrastructure and developer experience experts
  to build tools to support the modern application development lifecycle.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/runscope-logo.png
x-kinRank: "9"
x-alexaRank: ""
tags: Steps
created: "2018-05-20"
modified: "2018-05-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/steps/master/_listings/runscope/apis.md
specificationVersion: "0.14"
apis:
- name: Runscope Get Buckets Tests Steps
  x-api-slug: runscope
  description: List test steps for a test.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/runscope-logo.png
  humanURL: https://www.runscope.com/
  baseURL: https://api.runscope.com////buckets/{bucketKey}/tests/{testId}/steps
  tags: Buckets, Tests, Steps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/steps/master/_listings/runscope/bucketsbucketkeyteststestidsteps-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/steps/master/_listings/runscope/bucketsbucketkeyteststestidsteps-get-openapi.md
- name: Runscope Add Buckets Tests Steps
  x-api-slug: runscope
  description: Add new test step.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/runscope-logo.png
  humanURL: https://www.runscope.com/
  baseURL: https://api.runscope.com////buckets/{bucketKey}/tests/{testId}/steps
  tags: Buckets, Tests, Steps
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/steps/master/_listings/runscope/bucketsbucketkeyteststestidsteps-post-openapi.md
- name: Runscope Delete Buckets Tests Steps
  x-api-slug: runscope
  description: Delete a step from a test.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/runscope-logo.png
  humanURL: https://www.runscope.com/
  baseURL: https://api.runscope.com////buckets/{bucketKey}/tests/{testId}/steps/{stepId}
  tags: Buckets, Tests, Steps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/steps/master/_listings/runscope/bucketsbucketkeyteststestidstepsstepid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/steps/master/_listings/runscope/bucketsbucketkeyteststestidstepsstepid-delete-openapi.md
- name: Runscope Put Buckets Tests Steps
  x-api-slug: runscope
  description: Update the details of a single test step.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/runscope-logo.png
  humanURL: https://www.runscope.com/
  baseURL: https://api.runscope.com////buckets/{bucketKey}/tests/{testId}/steps/{stepId}
  tags: Buckets, Tests, Steps
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/steps/master/_listings/runscope/bucketsbucketkeyteststestidstepsstepid-put-openapi.md
- name: Runscope
  x-api-slug: runscope
  description: Runscope was started with the idea that depending on a web service
    API in a mobile or web application should be as easy as depending on code running
    locally. We&rsquo;ve assembled a team of API, infrastructure and developer experience
    experts to build tools to support the modern application development lifecycle.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/runscope-logo.png
  humanURL: https://www.runscope.com/
  baseURL: https://api.runscope.com//
  tags: Steps
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/steps/master/_listings/runscope/openapi.md
x-common:
- type: x-base-url
  url: https://api.runscope.com
- type: x-blog
  url: http://blog.runscope.com/
- type: x-blog-rss
  url: http://blog.runscope.com/posts?format=rss
- type: x-crunchbase
  url: http://www.crunchbase.com/company/runscope
- type: x-developer
  url: https://www.runscope.com/docs/api
- type: x-github
  url: https://github.com/Runscope
- type: x-openapi-spec--authoritative
  url: https://raw.githubusercontent.com/Runscope/runscope-api-examples/master/schemas/runscope-swagger.json
- type: x-pricing
  url: https://www.runscope.com/pricing-and-plans
- type: x-privacy
  url: https://www.runscope.com/privacy
- type: x-status
  url: http://status.runscope.com/
- type: x-support
  url: https://www.runscope.com/support
- type: x-terms-of-service
  url: https://www.runscope.com/terms
- type: x-twitter
  url: https://twitter.com/Runscope
- type: x-website
  url: https://www.runscope.com/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---