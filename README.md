# launchkit-assets

Public binary assets for [LaunchKit](https://github.com/Designedforusers/renderlaunchkit). Hosted here (rather than in the main repo) so the feature branches stay lean and the raw GitHub URLs can be referenced directly from config.

## Files

| File       | Used by                            | Notes                                              |
|------------|------------------------------------|----------------------------------------------------|
| `bufo.png` | Pika video meeting integration     | AI teammate avatar; referenced via `PIKA_AVATAR`   |

## Raw URL pattern

```
https://raw.githubusercontent.com/Designedforusers/launchkit-assets/main/<filename>
```

Pika's `pikastream-video-meeting` Python CLI downloads any `http(s)://` value passed to `--image` via `requests.get(...)`, so these raw URLs work directly as `PIKA_AVATAR` values.
