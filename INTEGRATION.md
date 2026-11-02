# Shared ZARBITZ account integration

Run through the sibling UserProfile Compose deployment. Open `/agri/?asset=<owned-asset-uuid>` from the approved user's account dashboard. `/account/platform.js` validates the selected asset and publishes it as `window.zarbitzAsset` and the `zarbitz:asset` event.

The original Agri UI is retained. Its `/api/zarr/kpi` backend was absent from this repository; displayed legacy/demo values are NOT the selected user's observations. A visible banner states this. A real schema-aware KPI service must be implemented against the Mac Mini agricultural Zarr before customer monitoring use.

Installation, providers, approval and data mounting: see `UserProfile/MAC_MINI_RULEBOOK.md`.
