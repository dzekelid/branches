---
swagger: "2.0"
x-collection-name: Dezrez
x-complete: 0
info:
  title: Dezrez Request Csv for either set of negotiators or set of branches, with
    specified set of ReportFacets.
  version: 1.0.0
  description: Request csv for either set of negotiators or set of branches, with
    specified set of reportfacets..
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