---
swagger: "2.0"
x-collection-name: Instructure
x-complete: 0
info:
  title: Instructure Canvas Users API List of preference categories
  description: List of preference categories.
  termsOfService: https://www.canvaslms.com/policies/api-policy
  version: v1
host: canvas.instructure.com
basePath: /api/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /users/self/communication_channels/{communication_channel_id}/notification_preference_categories/category:
    put:
      summary: Update preferences by category
      description: Update preferences by category.
      operationId: update-preferences-by-category
      x-api-path-slug: usersselfcommunication-channelscommunication-channel-idnotification-preference-categoriescategory-put
      parameters:
      - in: query
        name: category
        description: The name of the category
      - in: query
        name: notification_preferences[frequency]
        description: The desired frequency for each notification in the category
      responses:
        200:
          description: OK
      tags:
      - Users
      - Self
      - Communication
      - Channels
      - Communication
      - Channel
      - Id
      - Notification
      - Preference
      - Categories
      - Category
  /users/{user_id}/communication_channels/communication_channel_id/notification_preference_categories:
    get:
      summary: List of preference categories
      description: List of preference categories.
      operationId: list-of-preference-categories
      x-api-path-slug: usersuser-idcommunication-channelscommunication-channel-idnotification-preference-categories-get
      responses:
        200:
          description: OK
      tags:
      - Users
      - User
      - Id
      - Communication
      - Channels
      - Communication
      - Channel
      - Id
      - Notification
      - Preference
      - Categories
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