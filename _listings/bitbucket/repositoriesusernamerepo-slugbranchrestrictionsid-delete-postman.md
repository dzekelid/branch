{
  "info": {
    "name": "Bitbucket Delete Repositories Username Repo Slug Branch Restrictions",
    "_postman_id": "98d64e79-50cb-405f-8278-c37350cf6030",
    "description": "Delete repositories username repo slug branch restrictions",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "repositories",
      "item": [
        {
          "id": "8f07fde9-5ed9-4631-99a7-f1f58bbac4de",
          "name": "deleteRepositoriesUsernameRepoSlugBranchRestrictions",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.bitbucket.org",
              "path": [
                "2.0",
                "repositories/:username/:repo_slug/branch-restrictions/:id"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "username",
                  "value": "username",
                  "type": "string"
                },
                {
                  "id": "repo_slug",
                  "value": "repo_slug",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Delete repositories username repo slug branch restrictions"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "92e550c6-48af-418c-8e60-06664cb4056a"
            }
          ]
        }
      ]
    }
  ]
}