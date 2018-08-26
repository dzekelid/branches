---
swagger: "2.0"
x-collection-name: Dezrez
x-complete: 1
info:
  title: Dezrez.Rezi.Client.Api
  version: 1.0.0
host: api.dezrez.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/reporting/csv:
    post:
      summary: Request Csv for either set of negotiators or set of branches, with
        specified set of ReportFacets.
      description: Request csv for either set of negotiators or set of branches, with
        specified set of reportfacets..
      operationId: Reporting_RealtimeReportCsvByreportCsvRequest
      x-api-path-slug: apireportingcsv-post
      parameters:
      - in: body
        name: reportCsvRequest
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Request
      - Csveither
      - Set
      - Of
      - Negotiators
      - Set
      - Of
      - Branches
      - ""
      - Specified
      - Set
      - Of
      - ReportFacets
---