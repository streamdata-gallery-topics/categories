---
name: Product Hunt
x-slug: product-hunt
description: Product Hunt is a curation of the best new products, every day. Discover
  the latest mobile apps, websites, and technology products that everyones talking
  about.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11269-product-hunt.jpg
x-kinRank: "7"
x-alexaRank: "4019"
tags: Categories
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/categories/master/_listings/product-hunt/apis.md
specificationVersion: "0.14"
apis:
- name: Product Hunt Get Categories
  x-api-slug: product-hunt
  description: Get categories.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11269-product-hunt.jpg
  humanURL: http://producthunt.com
  baseURL: https://api.producthunt.com//v1//categories/{category}/posts
  tags: Categories
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/categories/master/_listings/product-hunt/categoriescategoryposts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/categories/master/_listings/product-hunt/categoriescategoryposts-get-openapi.md
- name: Product Hunt
  x-api-slug: product-hunt
  description: Product Hunt is a curation of the best new products, every day. Discover
    the latest mobile apps, websites, and technology products that everyones talking
    about.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11269-product-hunt.jpg
  humanURL: http://producthunt.com
  baseURL: https://api.producthunt.com//v1
  tags: Categories
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/categories/master/_listings/product-hunt/openapi.md
x-common:
- type: x-api-json--authoritative
  url: https://raw.githubusercontent.com/producthunt/producthunt-api/master/manifests/v1/apis.json
- type: x-blog
  url: https://stories.producthunt.com/
- type: x-blog-rss
  url: https://stories.producthunt.com/feed/
- type: x-crunchbase
  url: https://crunchbase.com/organization/product-hunt
- type: x-email
  url: hello@producthunt.com
- type: x-email
  url: ship@producthunt.com
- type: x-github
  url: https://github.com/producthunt
- type: x-linkedin
  url: https://www.linkedin.com/company/product-hunt/
- type: x-twitter
  url: https://twitter.com/producthunt
- type: x-website
  url: http://producthunt.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---