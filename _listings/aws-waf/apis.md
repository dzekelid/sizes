---
name: AWS WAF
x-slug: aws-waf
description: AWS WAF is a web application firewall that helps protect your webapplications
  from common web exploits that could affect applicationavailability, compromise security,
  or consume excessive resources. AWSWAF gives you control over which traffic to allow
  or block to your webapplications by defining customizable web security rules. You
  can use AWSWAF to create custom rules that block common attack patterns, such as
  SQLinjection or cross-site scripting, and rules that are designed for your specific
  application. New rules can be deployed within minutes, letting you respondquickly
  to changing traffic patterns. Also, AWS WAF includes a full-featuredAPI that you
  can use to automate the creation, deployment, and maintenanceof web security rules.With
  AWS WAF you pay only for what you use. AWS WAF pricing is based on how many rules
  you deploy and how many web requests your web application receives. There are no
  upfront commitments.You can deploy AWS WAF on either Amazon CloudFront as part of
  your CDN solution or the Application Load Balancer (ALB) that fronts your web servers
  or origin servers running on EC2.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSWAF.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Sizes
created: "2018-08-26"
modified: "2018-08-26"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/sizes/master/_listings/aws-waf/apis.md
specificationVersion: "0.14"
apis:
- name: AWS WAF API - Create Size Constraint Set
  x-api-slug: actioncreatesizeconstraintset-get
  description: 'Service: AWS WAFCreates a SizeConstraintSet.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSWAF.png
  humanURL: https://aws.amazon.com/waf/
  baseURL: :///
  tags: Amazon Web Services, Security, Firewall, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sizes/master/_listings/aws-waf/actioncreatesizeconstraintset-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sizes/master/_listings/aws-waf/actioncreatesizeconstraintset-get-openapi.md
- name: AWS WAF API - Delete Size Constraint Set
  x-api-slug: actiondeletesizeconstraintset-get
  description: 'Service: AWS WAFPermanently deletes a.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSWAF.png
  humanURL: https://aws.amazon.com/waf/
  baseURL: :///
  tags: Amazon Web Services, Security, Firewall, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sizes/master/_listings/aws-waf/actiondeletesizeconstraintset-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sizes/master/_listings/aws-waf/actiondeletesizeconstraintset-get-openapi.md
- name: AWS WAF API - Get Size Constraint Set
  x-api-slug: actiongetsizeconstraintset-get
  description: 'Service: AWS WAFReturns the.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSWAF.png
  humanURL: https://aws.amazon.com/waf/
  baseURL: :///
  tags: Amazon Web Services, Security, Firewall, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sizes/master/_listings/aws-waf/actiongetsizeconstraintset-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sizes/master/_listings/aws-waf/actiongetsizeconstraintset-get-openapi.md
- name: AWS WAF API - List Size Constraint Sets
  x-api-slug: actionlistsizeconstraintsets-get
  description: 'Service: AWS WAFReturns an array of.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSWAF.png
  humanURL: https://aws.amazon.com/waf/
  baseURL: :///
  tags: Amazon Web Services, Security, Firewall, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sizes/master/_listings/aws-waf/actionlistsizeconstraintsets-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sizes/master/_listings/aws-waf/actionlistsizeconstraintsets-get-openapi.md
- name: AWS WAF API - Update Size Constraint Set
  x-api-slug: actionupdatesizeconstraintset-get
  description: 'Service: AWS WAFInserts or deletes.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSWAF.png
  humanURL: https://aws.amazon.com/waf/
  baseURL: :///
  tags: Amazon Web Services, Security, Firewall, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sizes/master/_listings/aws-waf/actionupdatesizeconstraintset-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sizes/master/_listings/aws-waf/actionupdatesizeconstraintset-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://aws.storage.gateway.service.api.gallery.streamdata.io
- type: x-api-stack
  url: http://aws.waf.stack.network
- type: x-documentation
  url: http://docs.aws.amazon.com/waf/latest/APIReference/Welcome.html
- type: x-faq
  url: https://aws.amazon.com/waf/faq/
- type: x-getting-started
  url: https://aws.amazon.com/waf/getting-started/
- type: x-partners
  url: https://aws.amazon.com/waf/partners/
- type: x-pricing
  url: https://aws.amazon.com/waf/pricing/
- type: x-tutorials
  url: https://aws.amazon.com/waf/preconfiguredrules/
- type: x-webinars
  url: https://aws.amazon.com/waf/webinars/
- type: x-website
  url: https://aws.amazon.com/waf/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---