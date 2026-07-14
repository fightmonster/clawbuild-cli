# ClawBuild CLI

Release-only distribution for ClawBuild CLI.

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
