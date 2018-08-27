{
  "info": {
    "name": "Bitbucket Get Repositories Username Repo Slug Branch Restrictions",
    "_postman_id": "7828efd5-5dcb-475d-9d73-32046af41b62",
    "description": "Get repositories username repo slug branch restrictions",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "repositories",
      "item": [
        {
          "id": "7f613547-5b99-4b93-a55c-291dac10bd9f",
          "name": "getRepositoriesUsernameRepoSlugBranchRestrictions",
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
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get repositories username repo slug branch restrictions"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6b732008-0d19-4bd4-aabb-ecc915d28914"
            }
          ]
        }
      ]
    }
  ]
}