---
swagger: "2.0"
x-collection-name: AWS Elastic MapReduce
x-complete: 0
info:
  title: AWS Elastic MapReduce API Cancel Steps
  version: 1.0.0
  description: Cancels a pending step or steps in a running cluster.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=CancelSteps:
    get:
      summary: Cancel Steps
      description: Cancels a pending step or steps in a running cluster.
      operationId: cancelSteps
      x-api-path-slug: actioncancelsteps-get
      parameters:
      - in: query
        name: ClusterId
        description: The ClusterID for which specified steps will be canceled
        type: string
      - in: query
        name: StepIds
        description: The list of StepIDs to cancel
        type: string
      responses:
        200:
          description: OK
      tags:
      - Steps
  /?Action=DescribeStep:
    get:
      summary: Describe Step
      description: Provides more detail about the cluster step.
      operationId: describeStep
      x-api-path-slug: actiondescribestep-get
      parameters:
      - in: query
        name: ClusterId
        description: The identifier of the cluster with steps to describe
        type: string
      - in: query
        name: StepId
        description: The identifier of the step to describe
        type: string
      responses:
        200:
          description: OK
      tags:
      - Steps
  /?Action=ListSteps:
    get:
      summary: List Steps
      description: Provides a list of steps for the cluster in reverse order unless
        you specify stepIds with the request.
      operationId: listSteps
      x-api-path-slug: actionliststeps-get
      parameters:
      - in: query
        name: ClusterId
        description: The identifier of the cluster for which to list the steps
        type: string
      - in: query
        name: Marker
        description: The pagination token that indicates the next set of results to
          retrieve
        type: string
      - in: query
        name: StepIds
        description: The filter to limit the step list based on the identifier of
          the steps
        type: string
      - in: query
        name: StepStates
        description: The filter to limit the step list based on certain states
        type: string
      responses:
        200:
          description: OK
      tags:
      - Steps
  /?Action=AddJobFlowSteps:
    get:
      summary: Add Job Flow Steps
      description: AddJobFlowSteps adds new steps to a running job flow.
      operationId: addJobFlowSteps
      x-api-path-slug: actionaddjobflowsteps-get
      parameters:
      - in: query
        name: JobFlowId
        description: A string that uniquely identifies the job flow
        type: string
      - in: query
        name: Steps
        description: A list of StepConfig to be executed by the job flow
        type: string
      responses:
        200:
          description: OK
      tags:
      - Job Flow Steps
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