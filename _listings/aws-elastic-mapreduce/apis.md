---
name: AWS Elastic MapReduce
x-slug: aws-elastic-mapreduce
description: Amazon EMR provides a managed Hadoop framework that makes it easy, fast,
  and cost-effective to process vast amounts of data across dynamically scalable Amazon
  EC2 instances. You can also run other popular distributed frameworks such as Apache
  Spark, HBase, Presto, and Flink in Amazon EMR, and interact with data in other AWS
  data stores such as Amazon S3 and Amazon DynamoDB.Amazon EMR securely and reliably
  handles a broad set of big data use cases, including log analysis, web indexing,
  data transformations (ETL), machine learning, financial analysis, scientific simulation,
  and bioinformatics.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AmazonEMR.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Steps
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/steps/master/_listings/aws-elastic-mapreduce/apis.md
specificationVersion: "0.14"
apis:
- name: AWS Elastic MapReduce API Add Job Flow Steps
  x-api-slug: aws-elastic-mapreduce-api
  description: AddJobFlowSteps adds new steps to a running job flow.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AmazonEMR.png
  humanURL: https://aws.amazon.com/emr/
  baseURL: ://///?Action=AddJobFlowSteps
  tags: Job Flow Steps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/steps/master/_listings/aws-elastic-mapreduce/actionaddjobflowsteps-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/steps/master/_listings/aws-elastic-mapreduce/actionaddjobflowsteps-get-openapi.md
- name: AWS Elastic MapReduce API Cancel Steps
  x-api-slug: aws-elastic-mapreduce-api
  description: Cancels a pending step or steps in a running cluster.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AmazonEMR.png
  humanURL: https://aws.amazon.com/emr/
  baseURL: ://///?Action=CancelSteps
  tags: Steps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/steps/master/_listings/aws-elastic-mapreduce/actioncancelsteps-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/steps/master/_listings/aws-elastic-mapreduce/actioncancelsteps-get-openapi.md
- name: AWS Elastic MapReduce API Describe Step
  x-api-slug: aws-elastic-mapreduce-api
  description: Provides more detail about the cluster step.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AmazonEMR.png
  humanURL: https://aws.amazon.com/emr/
  baseURL: ://///?Action=DescribeStep
  tags: Steps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/steps/master/_listings/aws-elastic-mapreduce/actiondescribestep-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/steps/master/_listings/aws-elastic-mapreduce/actiondescribestep-get-openapi.md
- name: AWS Elastic MapReduce API List Steps
  x-api-slug: aws-elastic-mapreduce-api
  description: Provides a list of steps for the cluster in reverse order unless you
    specify stepIds with the request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AmazonEMR.png
  humanURL: https://aws.amazon.com/emr/
  baseURL: ://///?Action=ListSteps
  tags: Steps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/steps/master/_listings/aws-elastic-mapreduce/actionliststeps-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/steps/master/_listings/aws-elastic-mapreduce/actionliststeps-get-openapi.md
- name: AWS Elastic MapReduce API
  x-api-slug: aws-elastic-mapreduce-api
  description: Amazon EMR provides a managed Hadoop framework that makes it easy,
    fast, and cost-effective to process vast amounts of data across dynamically scalable
    Amazon EC2 instances. You can also run other popular distributed frameworks such
    as Apache Spark, HBase, Presto, and Flink in Amazon EMR, and interact with data
    in other AWS data stores such as Amazon S3 and Amazon DynamoDB.Amazon EMR securely
    and reliably handles a broad set of big data use cases, including log analysis,
    web indexing, data transformations (ETL), machine learning, financial analysis,
    scientific simulation, and bioinformatics.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AmazonEMR.png
  humanURL: https://aws.amazon.com/emr/
  baseURL: :///
  tags: Steps
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/steps/master/_listings/aws-elastic-mapreduce/openapi.md
x-common:
- type: x-article
  url: http://aws.amazon.com/articles/Elastic-MapReduce
- type: x-command-line-interface
  url: http://docs.aws.amazon.com/ElasticMapReduce/latest/DeveloperGuide/emr-cli-reference.html
- type: x-faq
  url: https://aws.amazon.com/emr/faqs/
- type: x-getting-started
  url: https://aws.amazon.com/emr/getting-started/
- type: x-partners
  url: https://aws.amazon.com/emr/partners/
- type: x-pricing
  url: https://aws.amazon.com/emr/pricing/
- type: x-documentation
  url: http://docs.aws.amazon.com/ElasticMapReduce/latest/API/
- type: x-website
  url: https://aws.amazon.com/emr/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---