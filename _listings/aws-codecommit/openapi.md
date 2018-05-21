---
swagger: "2.0"
x-collection-name: AWS CodeCommit
x-complete: 1
info:
  title: AWS CodeCommit API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=GetBranch:
    get:
      summary: Get Branch
      description: Returns information about a repository branch, including its name
        and the last commit ID.
      operationId: getBranch
      x-api-path-slug: actiongetbranch-get
      parameters:
      - in: query
        name: branchName
        description: The name of the branch for which you want to retrieve information
        type: string
      - in: query
        name: repositoryName
        description: The name of the repository that contains the branch for which
          you want to retrieve information
        type: string
      responses:
        200:
          description: OK
      tags:
      - Branches
  /?Action=ListBranches:
    get:
      summary: List Branches
      description: Gets information about one or more branches in a repository.
      operationId: listBranches
      x-api-path-slug: actionlistbranches-get
      parameters:
      - in: query
        name: nextToken
        description: An enumeration token that allows the operation to batch the results
        type: string
      - in: query
        name: repositoryName
        description: The name of the repository that contains the branches
        type: string
      responses:
        200:
          description: OK
      tags:
      - Branches
  /?Action=UpdateDefaultBranch:
    get:
      summary: Update Default Branch
      description: Sets or changes the default branch name for the specified repository.
      operationId: updateDefaultBranch
      x-api-path-slug: actionupdatedefaultbranch-get
      parameters:
      - in: query
        name: defaultBranchName
        description: The name of the branch to set as the default
        type: string
      - in: query
        name: repositoryName
        description: The name of the repository to set or change the default branch
          for
        type: string
      responses:
        200:
          description: OK
      tags:
      - Branches
---