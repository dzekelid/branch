swagger: "2.0"
x-collection-name: CircleCI
x-complete: 1
info:
  title: CircleCI
  description: the-circleci-api-is-a-restful-fullyfeatured-api-that-allows-you-to-do-almost-anything-in-circleci--you-can-access-all-information-and-trigger-all-actions--the-only-thing-we-dont-provide-access-to-is-billing-functions-which-must-be-done-from-the-circleci-web-ui-
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