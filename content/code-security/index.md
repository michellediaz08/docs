---
title: Code security documentation
shortTitle: Code security
intro: 'Build security into your {% data variables.product.prodname_dotcom %} workflow with features to keep secrets and vulnerabilities out of your codebase, and to maintain your software supply chain.'
redirect_from:
  - /code-security/guides
introLinks:
  overview: /code-security/getting-started/github-security-features
  try_ghas_for_free: '{% ifversion ghec %}/billing/managing-billing-for-github-advanced-security/setting-up-a-trial-of-github-advanced-security{% endif %}'
featuredLinks:
  startHere:
    - /code-security/getting-started/securing-your-repository
    - /code-security/getting-started/securing-your-organization
    - '{% ifversion fpt or ghec %}/code-security/security-advisories/working-with-repository-security-advisories/creating-a-repository-security-advisory{% endif %}'
    - '{% ifversion code-scanning-without-workflow %}/code-security/code-scanning/enabling-code-scanning/configuring-default-setup-for-code-scanning{% endif %}'
    - '{% ifversion ghes < 3.9 %}/code-security/code-scanning/creating-an-advanced-setup-for-code-scanning/configuring-advanced-setup-for-code-scanning{% endif %}'
  guideCards:
    - '{% ifversion fpt or ghec or ghes %}/code-security/dependabot/dependabot-security-updates/configuring-dependabot-security-updates{% endif %}'
    - '{% ifversion fpt or ghec or ghes %}/code-security/dependabot/dependabot-version-updates/configuring-dependabot-version-updates{% endif %}'
    - '{% ifversion code-scanning-without-workflow %}/code-security/code-scanning/enabling-code-scanning/configuring-default-setup-for-code-scanning{% endif %}'
    - '{% ifversion ghes < 3.9 %}/code-security/code-scanning/creating-an-advanced-setup-for-code-scanning/configuring-advanced-setup-for-code-scanning{% endif %}'
    - /code-security/supply-chain-security/end-to-end-supply-chain/end-to-end-supply-chain-overview
  popular:
    - '{% ifversion ghes %}/admin/release-notes{% endif %}'
    - /code-security/dependabot/dependabot-alerts/about-dependabot-alerts
    - /code-security/security-advisories/guidance-on-reporting-and-writing-information-about-vulnerabilities/about-coordinated-disclosure-of-security-vulnerabilities
    - /code-security/dependabot/working-with-dependabot/keeping-your-actions-up-to-date-with-dependabot
    - /code-security/dependabot/dependabot-version-updates/configuration-options-for-the-dependabot.yml-file
    - /code-security/dependabot/working-with-dependabot/configuring-access-to-private-registries-for-dependabot
    - /code-security/dependabot/working-with-dependabot/troubleshooting-the-detection-of-vulnerable-dependencies
changelog:
  label: security-and-compliance
  versions:
    fpt: '*'
    ghec: '*'
layout: product-landing
versions:
  fpt: '*'
  ghes: '*'
  ghec: '*'
topics:
  - Repositories
  - Dependencies
  - Vulnerabilities
children:
  - /getting-started
  - /adopting-github-advanced-security-at-scale
  - /secret-scanning
  - /code-scanning
  - /codeql-cli
  - /security-advisories
  - /supply-chain-security
  - /dependabot
  - /security-overview
---
