---
date: 2022-08-29T10:58:14-04:00
title: "chainctl config view"
slug: chainctl_config_view
url: /chainguard/chainguard-enforce/chainctl-docs/chainctl_config_view/
draft: false
images: []
type: "article"
toc: true
---
## chainctl config view

View the current chainctl config.

```
chainctl config view [--diff] [--output ] [flags]
```

### Options

```
      --diff   Show the difference between the local config file and the active configuration.
  -h, --help   help for view
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

* [chainctl config](/chainguard/chainguard-enforce/chainctl-docs/chainctl_config/)	 - Local config file commands for chainctl.

