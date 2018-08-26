---
swagger: "2.0"
x-collection-name: Charity Navigator
x-complete: 1
info:
  title: CharityNavigatorDataAPI
  description: the-charity-navigator-data-api-provides-access-to-charity-navigatorsratings-research-content-and-charitable-organization-profiles-
  version: 1.0.0
host: api.data.charitynavigator.org
basePath: /v2
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /Advisory:
    get:
      summary: Get Advisory
      description: |-
        Retrieve the full set of Charity Navigator advisories for a specified
        organization. An advisory is a cautionary communication from Charity Navigator,
        advising of unusual events or behavior related to a known organization.
      operationId: getAllActiveAdvisories
      x-api-path-slug: advisory-get
      parameters:
      - in: query
        name: app_id
        description: '3Scale App ID: unique identifier for an application registered
          in theCharity Navigator  developer portal'
      - in: query
        name: app_key
        description: '3Scale App Key: a secret key to authenticate the assigned App
          ID'
      - in: query
        name: pageNum
        description: Page number to return, in case the number of available objects
          in the resultset is greater than the specified or default `pageSize`
      - in: query
        name: pageSize
        description: Number of organizations to return in a single response message
      responses:
        200:
          description: OK
      tags:
      - Advisory
---