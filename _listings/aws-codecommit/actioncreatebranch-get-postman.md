{
  "info": {
    "name": "AWS CodeCommit API Create Branch",
    "_postman_id": "6a16d2cd-2249-4f34-b431-5344a5080f6a",
    "description": "Creates a new branch in a repository and points the branch to a commit.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Repositories",
      "item": [
        {
          "id": "b96dd7ea-9682-4c02-a04d-fc25da71fe43",
          "name": "batchGetRepositories",
          "request": {
            "url": "http://example.com/api/?Action=BatchGetRepositories?repositoryNames=repositoryNames",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns information about one or more repositories."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "79963f8a-9481-4462-93e1-9aa2bbd9ff4c"
            }
          ]
        }
      ]
    },
    {
      "name": "Branch",
      "item": [
        {
          "id": "f8d7ce37-cff6-4800-9c85-d3b437a928a3",
          "name": "createBranch",
          "request": {
            "url": "http://example.com/api/?Action=CreateBranch?branchName=branchName&commitId=commitId&repositoryName=repositoryName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a new branch in a repository and points the branch to a commit."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "69723e68-b5af-4c73-8d38-8fc42488e65e"
            }
          ]
        }
      ]
    }
  ]
}