---
swagger: "2.0"
x-collection-name: GitLab
x-complete: 0
info:
  title: GitLab Delete Projects Repository Branches Branch
  version: 1.0.0
  description: Delete projects repository branches branch.
host: localhost:3000
basePath: /api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v3/projects/{id}/repository/branches/{branch}:
    get:
      summary: Get Projects Repository Branches Branch
      description: Get projects repository branches branch.
      operationId: getV3ProjectsIdRepositoryBranchesBranch
      x-api-path-slug: v3projectsidrepositorybranchesbranch-get
      parameters:
      - in: path
        name: branch
        description: The name of the branch
      - in: path
        name: id
        description: The ID of a project
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Repository
      - Branches
      - Branch
    delete:
      summary: Delete Projects Repository Branches Branch
      description: Delete projects repository branches branch.
      operationId: deleteV3ProjectsIdRepositoryBranchesBranch
      x-api-path-slug: v3projectsidrepositorybranchesbranch-delete
      parameters:
      - in: path
        name: branch
        description: The name of the branch
      - in: path
        name: id
        description: The ID of a project
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Repository
      - Branches
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