---
swagger: "2.0"
x-collection-name: Google Play
x-complete: 0
info:
  title: Google Play Increment Step Of Achievement
  version: 1.0.0
  description: Increments the steps of the achievement with the given ID for the currently
    authenticated player.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /achievements/{achievementId}/setStepsAtLeast:
    post:
      summary: Set Steps for Achievements
      description: Sets the steps for the currently authenticated player towards unlocking
        an achievement. If the steps parameter is less than the current number of
        steps that the player already gained for the achievement, the achievement
        is not modified.
      operationId: games.achievements.setStepsAtLeast
      x-api-path-slug: achievementsachievementidsetstepsatleast-post
      parameters:
      - in: path
        name: achievementId
        description: The ID of the achievement used by this method
      - in: query
        name: consistencyToken
        description: The last-seen mutation timestamp
      - in: query
        name: steps
        description: The minimum value to set the steps to
      responses:
        200:
          description: OK
      tags:
      - Achievement
  /achievements/{achievementId}/increment:
    post:
      summary: Increment Step Of Achievement
      description: Increments the steps of the achievement with the given ID for the
        currently authenticated player.
      operationId: games.achievements.increment
      x-api-path-slug: achievementsachievementidincrement-post
      parameters:
      - in: path
        name: achievementId
        description: The ID of the achievement used by this method
      - in: query
        name: consistencyToken
        description: The last-seen mutation timestamp
      - in: query
        name: requestId
        description: A randomly generated numeric ID for each request specified by
          the caller
      - in: query
        name: stepsToIncrement
        description: The number of steps to increment
      responses:
        200:
          description: OK
      tags:
      - Achievement
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