swagger: "2.0"
x-collection-name: Predix
x-complete: 1
info:
  title: VIEWS
  version: 1.0.0
host: thetaray-anomaly-service.run.aws-usw02-pr.ice.predix.io
basePath: /v1
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