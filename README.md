# ignition — GH Pages target

Private gh-pages host for **Ignition** (Legend of Toys Influencer Marketing CRM).

- **Live:** https://ignition.legendoftoys.com
- **Source:** [legendlot/throttle](https://github.com/legendlot/throttle) → `apps/ignition`
- **Worker:** ignitionops.afshaan.workers.dev (sibling to csops + lotopsproxy + throttleops)

Do not edit files in this repo directly. The source repo (`legendlot/throttle`)
builds and pushes static-export output here via the
`.github/workflows/deploy-ignition.yml` workflow.
