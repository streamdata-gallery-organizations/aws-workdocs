---
swagger: "2.0"
info:
  title: AWS WorkDocs API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=GetFolder&k=1:
    get:
      summary: ' Get Folder '
      description: Retrieves the metadata of the specified folder
      operationId: getFolder
      parameters:
      - in: query
        name: FolderId
        description: The ID of the folder
        type: string
      responses:
        200:
          description: OK
      tags:
      - folders
definitions: []
x-collection-name: AWS WorkDocs
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