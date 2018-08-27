---
swagger: "2.0"
x-collection-name: CircleCI
x-complete: 0
info:
  title: CircleCI Add Project Username Project Tree Branch
  description: |-
    Triggers a new build, returns a summary of the build.
    Optional build parameters can be set using an experimental API.

    Note: For more about build parameters, read about [using parameterized builds](https://circleci.com/docs/parameterized-builds/)
  version: 1.0.0
host: circleci.com
basePath: /api/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /project/{username}/{project}/tree/{branch}:
    parameters:
      summary: Parameters Project Username Project Tree Branch
      description: Parameters project username project tree branch.
      operationId: parametersProjectUsernameProjectTreeBranch
      x-api-path-slug: projectusernameprojecttreebranch-parameters
      responses:
        200:
          description: OK
      tags:
      - Parameters
      - Project
      - Username
      - Project
      - Tree
      - Branch
    post:
      summary: Add Project Username Project Tree Branch
      description: |-
        Triggers a new build, returns a summary of the build.
        Optional build parameters can be set using an experimental API.

        Note: For more about build parameters, read about [using parameterized builds](https://circleci.com/docs/parameterized-builds/)
      operationId: postProjectUsernameProjectTreeBranch
      x-api-path-slug: projectusernameprojecttreebranch-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Project
      - Username
      - Project
      - Tree
      - Branch
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