# renovate-presets

Custom [Renovate presets](https://docs.renovatebot.com/config-presets/), add to your renovate config:

```diff
  {
    "$schema": "https://docs.renovatebot.com/renovate-schema.json",
-   "extends": ["config:base"],
+   "extends": ["github>mikaello/renovate-presets"],
}
```

Minor, patch, pin and digest updates are automerged.
Major updates require manual merging except for `actions/checkout`, `actions/setup-go`, `actions/setup-node`, or repository-specific exceptions.

Updates run from Sunday at 22:00 to Monday at 08:00 in `Europe/Oslo`, leading into odd ISO weeks.
ISO week parity resets each year, so a 53-week year can produce consecutive update weekends around New Year.
