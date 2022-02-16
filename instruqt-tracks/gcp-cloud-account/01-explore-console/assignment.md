---
slug: explore-console
id: 4urtpmgcxmrm
type: challenge
title: explore-console
teaser: Explore the console
notes:
- type: text
  contents: |-
    A Google Cloud Project has been created for you.

    Use the GCP console or the `gcloud` CLI to interact with it.

    Your project credentials are shown on the Console tab on the left.
tabs:
- title: Console
  type: service
  hostname: cloud-client
  path: /
  port: 80
- title: CLI
  type: terminal
  hostname: cloud-client
difficulty: basic
timelimit: 600
---

🤖 Let's start
==============

Explore the console using the given login credentials or with `gcloud` CLI available.

Remember that you are only allowed to interact with Compute service, for example:

## Listing compute instances

```
gcloud compute instances list
```

## Listing compute images
```
gcloud compute images list
```