---
name: AWS CodeCommit
x-slug: aws-codecommit
description: AWS CodeCommit is a fully-managed source control service that makes it
  easy for companies to host secure and highly scalable private Git repositories.
  CodeCommit eliminates the need to operate your own source control system or worry
  about scaling its infrastructure. You can use CodeCommit to securely store anything
  from source code to binaries, and it works seamlessly with your existing Git tools.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Developer-Tools_AWSCodeCommit.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Branches
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/branches/master/_listings/aws-codecommit/apis.md
specificationVersion: "0.14"
apis:
- name: AWS CodeCommit API Get Branch
  x-api-slug: aws-codecommit-api
  description: Returns information about a repository branch, including its name and
    the last commit ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Developer-Tools_AWSCodeCommit.png
  humanURL: https://aws.amazon.com/codecommit/
  baseURL: ://///?Action=GetBranch
  tags: Branches
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/branches/master/_listings/aws-codecommit/actiongetbranch-get-openapi.md
- name: AWS CodeCommit API List Branches
  x-api-slug: aws-codecommit-api
  description: Gets information about one or more branches in a repository.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Developer-Tools_AWSCodeCommit.png
  humanURL: https://aws.amazon.com/codecommit/
  baseURL: ://///?Action=ListBranches
  tags: Branches
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/branches/master/_listings/aws-codecommit/actionlistbranches-get-openapi.md
- name: AWS CodeCommit API Update Default Branch
  x-api-slug: aws-codecommit-api
  description: Sets or changes the default branch name for the specified repository.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Developer-Tools_AWSCodeCommit.png
  humanURL: https://aws.amazon.com/codecommit/
  baseURL: ://///?Action=UpdateDefaultBranch
  tags: Branches
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/branches/master/_listings/aws-codecommit/actionupdatedefaultbranch-get-openapi.md
- name: AWS CodeCommit API
  x-api-slug: aws-codecommit-api
  description: AWS CodeCommit is a fully-managed source control service that makes
    it easy for companies to host secure and highly scalable private Git repositories.
    CodeCommit eliminates the need to operate your own source control system or worry
    about scaling its infrastructure. You can use CodeCommit to securely store anything
    from source code to binaries, and it works seamlessly with your existing Git tools.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Developer-Tools_AWSCodeCommit.png
  humanURL: https://aws.amazon.com/codecommit/
  baseURL: :///
  tags: Branches
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/branches/master/_listings/aws-codecommit/openapi.md
x-common:
- type: x-command-line-interface
  url: http://docs.aws.amazon.com/cli/latest/reference/codecommit/index.html
- type: x-documentation
  url: http://docs.aws.amazon.com/codecommit/latest/APIReference/
- type: x-faq
  url: https://aws.amazon.com/codecommit/faqs/
- type: x-getting-started
  url: ttps://aws.amazon.com/codecommit/getting-started/
- type: x-pricing
  url: https://aws.amazon.com/codecommit/pricing/
- type: x-website
  url: https://aws.amazon.com/codecommit/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---