# possum-runner

This repository runs CI for
[`publicgoodsfunding/possum`](https://github.com/publicgoodsfunding/possum),
the software project it belongs to. Possum backports upstream CVE fixes into
the exact package versions that distros ship; its CI here lints, tests, builds
and verifies those packages.

Everything in this repository is generated from possum's `runner/` directory.
Don't edit it here: change `runner/` in possum instead.
