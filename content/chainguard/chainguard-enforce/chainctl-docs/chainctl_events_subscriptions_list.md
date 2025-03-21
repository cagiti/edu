---
date: 2022-08-29T10:58:14-04:00
title: "chainctl events subscriptions list"
slug: chainctl_events_subscriptions_list
url: /chainguard/chainguard-enforce/chainctl-docs/chainctl_events_subscriptions_list/
draft: false
images: []
type: "article"
toc: true
---
## chainctl events subscriptions list

List subscriptions.

```
chainctl events subscriptions list [--group GROUP_NAME|GROUP_ID] [--output table|json|id] [flags]
```

### Options

```
      --group string   The parent group id of the subscription.
  -h, --help           help for list
```

### Options inherited from parent commands

```
      --api string        The url of the Chainguard platform API. (default "http://api.api-system.svc")
      --audience string   The Chainguard token audience to request. (default "http://api.api-system.svc")
      --config string     A specific chainctl config file.
      --console string    The url of the Chainguard platform Console. (default "http://console-ui.api-system.svc")
      --issuer string     The url of the Chainguard STS endpoint. (default "http://issuer.oidc-system.svc")
  -o, --output string     Output format. One of: ["", "table", "tree", "json", "id", "wide"]
```

### SEE ALSO

* [chainctl events subscriptions](/chainguard/chainguard-enforce/chainctl-docs/chainctl_events_subscriptions/)	 - Subscription interactions.

