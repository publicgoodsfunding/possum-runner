# possum-runner

This repository runs CI for possum, the software project it belongs to. Possum
lives in `apps/possum` of
[`publicgoodsfunding/www.prosperous.software`](https://github.com/publicgoodsfunding/www.prosperous.software).
It backports upstream CVE fixes into the exact package versions that distros
ship; its CI here lints, tests, builds and verifies those packages.

Everything in this repository is generated from `apps/possum/runner/` in
www.prosperous.software. Don't edit it here: change it there instead.
