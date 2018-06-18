---
swagger: "2.0"
x-collection-name: Capital One DevExchange
x-complete: 1
info:
  title: Capital One DevExchange
  description: nessie-is-capital-ones-hackathon-api-that-gives-you-access-to-a-multitude-of-real-publicfacing-data--such-as-atm-and-bank-branch-locations--along-with-mock-customer-account-data--use-http-requests-to-set-up-peertopeer-transactions-simulate-a-weekly-paycheck-or-even-schedule-bills-for-customers-this-is-all-structured-in-a-way-that-resembles-how-we-actually-run-things-here-at-capital-one-
  version: 1.0.0
host: api.reimaginebanking.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /branches:
    get:
      summary: Get all branches
      description: Returns all of the Capital One branches.
      operationId: returns-all-of-the-capital-one-branches
      x-api-path-slug: branches-get
      responses:
        200:
          description: OK
      tags:
      - Banks
      - Branches
  /branches/{id}:
    get:
      summary: Get branch by id
      description: Returns the branch with the specific id
      operationId: returns-the-branch-with-the-specific-id
      x-api-path-slug: branchesid-get
      parameters:
      - in: path
        name: id
        description: ID of branch that needs to be fetched
      responses:
        200:
          description: OK
      tags:
      - Banks
      - Branches
---