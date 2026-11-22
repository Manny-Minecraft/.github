# Manny-Minecraft community files

Default files shared by every repository of the [Manny-Minecraft](https://github.com/Manny-Minecraft) organization.

| Path | What it does |
|---|---|
| `profile/README.md` | The organization's public profile, shown on its GitHub page |
| `.github/ISSUE_TEMPLATE/bug_report.yml` | Bug report form: steps to reproduce, mod, Minecraft and loader versions, logs |
| `.github/ISSUE_TEMPLATE/feature_request.yml` | Feature request form |
| `.github/ISSUE_TEMPLATE/config.yml` | Allows blank issues too |

## How the issue forms apply

GitHub uses these forms in every repository of the organization that has **no** `.github/ISSUE_TEMPLATE` folder of its own. A repository with its own templates uses only those, so to customize the forms for one mod, copy the whole folder into that repository.

The labels set by the forms (`bug`, `enhancement`) must exist in this repository and in every repository that uses them. GitHub creates both by default.
