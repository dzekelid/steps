---
swagger: "2.0"
x-collection-name: SalesLoft
x-complete: 0
info:
  title: SalesLoft Fetch a step
  description: Fetches a step, by ID only.
  version: v2
host: api.salesloft.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v2/steps.json:
    get:
      summary: List steps
      description: |-
        Fetches multiple step records. The records can be filtered, paged, and sorted according to
        the respective parameters.
      operationId: v2.steps.json.get
      x-api-path-slug: v2steps-json-get
      parameters:
      - in: query
        name: cadence_id
        description: Filter by cadence ID
      - in: query
        name: has_due_actions
        description: Filter by whether a step has due actions
      - in: query
        name: ids
        description: IDs of steps to fetch
      - in: query
        name: include_paging_counts
        description: Whether to include total_pages and total_count in the metadata
      - in: query
        name: page
        description: The current page to fetch results from
      - in: query
        name: per_page
        description: How many records to show per page in the range [1, 100]
      - in: query
        name: sort_by
        description: 'Key to sort on, must be one of: created_at, updated_at'
      - in: query
        name: sort_direction
        description: 'Direction to sort in, must be one of: ASC, DESC'
      - in: query
        name: type
        description: Filter by step type
      responses:
        200:
          description: OK
      tags:
      - Sales
      - List
      - Steps
  /v2/steps/{id}.json:
    get:
      summary: Fetch a step
      description: Fetches a step, by ID only.
      operationId: v2.steps.id.json.get
      x-api-path-slug: v2stepsid-json-get
      parameters:
      - in: path
        name: id
        description: Step ID
      responses:
        200:
          description: OK
      tags:
      - Sales
      - Fetch
      - Step
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---