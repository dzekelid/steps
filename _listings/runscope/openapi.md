---
swagger: "2.0"
x-collection-name: Runscope
x-complete: 1
info:
  title: Runscope
  description: manage-runscope-programmatically
  version: 1.0.0
host: api.runscope.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /buckets/{bucketKey}/tests/{testId}/steps:
    get:
      summary: Get Buckets Tests Steps
      description: List test steps for a test.
      operationId: buckets.bucketKey.tests.testId.steps.get
      x-api-path-slug: bucketsbucketkeyteststestidsteps-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Buckets
      - Tests
      - Steps
    post:
      summary: Add Buckets Tests Steps
      description: Add new test step.
      operationId: buckets.bucketKey.tests.testId.steps.post
      x-api-path-slug: bucketsbucketkeyteststestidsteps-post
      parameters:
      - in: query
        name: No Name
      - in: body
        name: TestStep
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Buckets
      - Tests
      - Steps
  /buckets/{bucketKey}/tests/{testId}/steps/{stepId}:
    delete:
      summary: Delete Buckets Tests Steps
      description: Delete a step from a test.
      operationId: buckets.bucketKey.tests.testId.steps.stepId.delete
      x-api-path-slug: bucketsbucketkeyteststestidstepsstepid-delete
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Buckets
      - Tests
      - Steps
    put:
      summary: Put Buckets Tests Steps
      description: Update the details of a single test step.
      operationId: buckets.bucketKey.tests.testId.steps.stepId.put
      x-api-path-slug: bucketsbucketkeyteststestidstepsstepid-put
      parameters:
      - in: query
        name: No Name
      - in: body
        name: TestStep
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Buckets
      - Tests
      - Steps
---