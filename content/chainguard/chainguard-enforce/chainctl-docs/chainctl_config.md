---
date: 2022-08-29T10:58:14-04:00
title: "chainctl config"
slug: chainctl_config
url: /chainguard/chainguard-enforce/chainctl-docs/chainctl_config/
draft: false
images: []
type: "article"
toc: true
---
## chainctl config

Local config file commands for chainctl.

### Options

```
  -h, --help   help for config
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

* [chainctl](/chainguard/chainguard-enforce/chainctl-docs/chainctl/)	 - Chainguard Control
* [chainctl config edit](/chainguard/chainguard-enforce/chainctl-docs/chainctl_config_edit/)	 - Edit the current chainctl config file.
* [chainctl config save](/chainguard/chainguard-enforce/chainctl-docs/chainctl_config_save/)	 - Save the current chainctl config to a config file.
* [chainctl config view](/chainguard/chainguard-enforce/chainctl-docs/chainctl_config_view/)	 - View the current chainctl config.

