---
swagger: "2.0"
x-collection-name: Predix
x-complete: 0
info:
  title: Predix Nurego Post Subscriptions Entitlements
  description: You can use this method to retrieve the Entitlements associated with
    a specific Subscription. It returns a list of entitlement objects.
  contact:
    name: support@nurego.com
  version: 1.0.0
host: api.nurego.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v1/subscriptions/{subscription_id}/entitlements:
    parameters:
      summary: Parameters Subscriptions Entitlements
      description: Parameters subscriptions entitlements.
      operationId: parametersV1SubscriptionsSubscriptionEntitlements
      x-api-path-slug: v1subscriptionssubscription-identitlements-parameters
      responses:
        200:
          description: OK
      tags:
      - Parameters
      - Subscriptions
      - Entitlements
    post:
      summary: Post Subscriptions Entitlements
      description: You can use this method to retrieve the Entitlements associated
        with a specific Subscription. It returns a list of entitlement objects.
      operationId: postV1SubscriptionsSubscriptionEntitlements
      x-api-path-slug: v1subscriptionssubscription-identitlements-post
      parameters:
      - in: body
        name: body
        description: Body Parameters
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Subscriptions
      - Entitlements
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