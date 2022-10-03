# renovate-presets

Custom [Renovate presets](https://docs.renovatebot.com/config-presets/), add to your renovate config:

```diff
  {
    "$schema": "https://docs.renovatebot.com/renovate-schema.json",
-   "extends": ["config:base"],
+   "extends": ["github>mikaello/renovate-presets"],
  }
```
