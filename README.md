# ClawBuild CLI

Release-only distribution for ClawBuild CLI.

Current release:

```text
version: 0.3.2
asset: clawbuild-cli-0.3.2.tgz
latest: clawbuild-cli.tgz
sha256: 37351f05738330413422c4d0904be4cfd2ad9c5a841b58d62d669edcf60bff72
```

Install latest:

```bash
npm install -g https://github.com/fightmonster/clawbuild-cli/releases/latest/download/clawbuild-cli.tgz
```

Update later:

```bash
clawbuild update --yes
```

Local first-use example on a build machine:

```bash
clawbuild setup --mode local \
  --root /data/platform/Phoenix \
  --workspace-name phoenix \
  --project-name phoenix \
  --template phoenix-mtk
```

Verify:

```bash
clawbuild --version
clawbuild --help
```

Source repository:

```text
https://github.com/fightmonster/clawbuild-cli-src
```
