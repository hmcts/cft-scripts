# cft-scripts

Centralized bash scripts written in [zx](https://github.com/google/zx).

Work in progress. Contributions welcome.

## Usage

Install zx `npm install -g zx` and then run

```
zx https://sh.hmcts.co.uk/[command] [args]

# e.g.
zx https://sh.hmcts.co.uk/idam/create-user user@hmcts.net role1,role2
```

Commands will default to run against AAT. The environment can be set to `aat`, `demo`, `ithc`, `perftest`. With the `ENV` environment variable:

```
ENV=perftest zx https://sh.hmcts.co.uk/idam/create-user user@hmcts.net role1,role2
```

