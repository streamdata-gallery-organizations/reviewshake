---
name: Reviewshake
x-slug: reviewshake
description: Reviewshake helps you manage all your review sites from one place, automate
  new reviews from your customers and track review performance
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28931-subdomain-reviewshake-com.jpg
x-kinRank: "7"
x-alexaRank: ""
tags: Reviewshake
created: "2018-08-31"
modified: "2018-08-31"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reviewshake/master/_listings/reviewshake/apis.md
specificationVersion: "0.14"
apis:
- name: Reviewshake API - Create order
  x-api-slug: order-post
  description: |-
    Creating orders in Reviewshake allows you to automate the sending of review invitations. You can setup this automation in your dashboard by visiting *Review Invitations* -> *Triggers*.

    Set the *Trigger* as *Order created*, and you can then setup the trigger options such as templates and subject lines to use as well as delays.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28931-subdomain-reviewshake-com.jpg
  humanURL: https://www.reviewshake.com/
  baseURL: https://subdomain.reviewshake.com//api/v1
  tags: Reviews
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reviewshake/master/_listings/reviewshake/order-post-openapi.md
- name: Reviewshake API - List widgets
  x-api-slug: widgets-get
  description: List widgets.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28931-subdomain-reviewshake-com.jpg
  humanURL: https://www.reviewshake.com/
  baseURL: https://subdomain.reviewshake.com//api/v1
  tags: Reviews
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reviewshake/master/_listings/reviewshake/widgets-get-openapi.md
- name: Reviewshake API - Create widget
  x-api-slug: widgets-post
  description: |-
    You can create the following widget types:

    1. List
    2. Caroussel
    3. Slider
    4. Grid
    5. Quote
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28931-subdomain-reviewshake-com.jpg
  humanURL: https://www.reviewshake.com/
  baseURL: https://subdomain.reviewshake.com//api/v1
  tags: Reviews
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reviewshake/master/_listings/reviewshake/widgets-post-openapi.md
- name: Reviewshake API - View widget
  x-api-slug: widgets1-get
  description: View widget.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28931-subdomain-reviewshake-com.jpg
  humanURL: https://www.reviewshake.com/
  baseURL: https://subdomain.reviewshake.com//api/v1
  tags: Reviews
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reviewshake/master/_listings/reviewshake/widgets1-get-openapi.md
- name: Reviewshake API - Update widget
  x-api-slug: widgetsid-put
  description: Update widget.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28931-subdomain-reviewshake-com.jpg
  humanURL: https://www.reviewshake.com/
  baseURL: https://subdomain.reviewshake.com//api/v1
  tags: Reviews
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reviewshake/master/_listings/reviewshake/widgetsid-put-openapi.md
- name: Reviewshake API - Delete widget
  x-api-slug: widgetsid-delete
  description: Delete widget.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28931-subdomain-reviewshake-com.jpg
  humanURL: https://www.reviewshake.com/
  baseURL: https://subdomain.reviewshake.com//api/v1
  tags: Reviews
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reviewshake/master/_listings/reviewshake/widgetsid-delete-openapi.md
x-common:
- type: x-api-gallery
  url: http://request.baskets.api.gallery.streamdata.io
- type: x-twitter
  url: https://twitter.com/reviewshake
- type: x-website
  url: https://www.reviewshake.com/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---