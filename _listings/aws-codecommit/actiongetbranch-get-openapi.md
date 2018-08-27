---
swagger: "2.0"
x-collection-name: AWS CodeCommit
x-complete: 0
info:
  title: AWS CodeCommit API Get Branch
  version: 1.0.0
  description: Returns information about a repository branch, including its name and
    the last commit ID.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=CreateBranch:
    get:
      summary: Create Branch
      description: Creates a new branch in a repository and points the branch to a
        commit.
      operationId: createBranch
      x-api-path-slug: actioncreatebranch-get
      parameters:
      - in: query
        name: branchName
        description: The name of the new branch to create
        type: string
      - in: query
        name: commitId
        description: The ID of the commit to point the new branch to
        type: string
      - in: query
        name: repositoryName
        description: The name of the repository in which you want to create the new
          branch
        type: string
      responses:
        200:
          description: OK
      tags:
      - Branch
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