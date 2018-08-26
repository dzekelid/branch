{
  "info": {
    "name": "Bitbucket Get Repositories Username Repo Slug Branch Restrictions",
    "_postman_id": "38635f95-0ea3-4f90-b8e2-856fe5c4f842",
    "description": "Returns a paginated list of all branch restrictions on the\nrepository.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "repositories",
      "item": [
        {
          "id": "3e70021d-3a1d-4674-999c-87392e43b925",
          "name": "getRepositoriesUsernameRepoSlugBranchRestrictions",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.bitbucket.org",
              "path": [
                "2.0",
                "repositories/:username/:repo_slug/branch-restrictions"
              ],
              "variable": [
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
            "description": "Returns a paginated list of all branch restrictions on the\nrepository"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "aca72953-1f59-4451-b63b-beae797cedea"
            }
          ]
        }
      ]
    }
  ]
}