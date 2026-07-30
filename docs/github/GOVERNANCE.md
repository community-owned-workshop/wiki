# Governance

| Action                                     | Everyone | COW Member |    Project Maintainer   |
| ------------------------------------------ | :------: | :--------: | :---------------------: |
| Report bugs                                |     ✅    |      ✅     |            ✅            |
| Suggest features                           |     ✅    |      ✅     |            ✅            |
| Create Pull Requests                       |     ❌    |      ✅     |            ✅            |
| Review Pull Requests                       |     ❌    |      ✅     |            ✅            |
| Approve Pull Requests                      |     ❌    |      ✅     |            ✅            |
| Merge Pull Requests                        |     ❌    |      ✅     |            ✅            |
| Trigger automatic Steam release (by merge) |     ❌    |      ✅     |            ✅            |
| Push directly to `main`                    |     ❌    |      ❌     | ✅ (own repository only) |
| Publish to Steam manually                  |     ❌    |      ❌     | ✅ (own repository only) |

## Core Principles

### Community Ownership

Every repository belongs to the community.

A project should never become inactive simply because its original author is unavailable. Any contributor may continue development by submitting Pull Requests.

### Four-Eyes Principle

No contributor may merge their own Pull Request.

Every change must be reviewed and merged by a different contributor or project maintainer.

### Project Maintainers

Each repository has one or more Project Maintainers.

Project Maintainers are responsible for:

* maintaining the project's long-term vision;
* reviewing community contributions;
* publishing emergency fixes when necessary.

Project Maintainers may push directly to the default branch of **their own repository only**.

They do not receive special permissions for other repositories.

### Automatic Releases

Merging a Pull Request into the default branch automatically triggers the project's release pipeline, including publishing to the Steam Workshop where configured.

No manual intervention from a Project Maintainer is required.

### Respectful Collaboration

Technical decisions should be discussed openly.

Consensus is preferred whenever practical.

When consensus cannot be reached, contributors are encouraged to experiment through Pull Requests rather than prolonged debate.

### Becoming a Project Maintainer

A repository may have multiple Project Maintainers.

Additional maintainers may be appointed by agreement of the existing maintainer(s) or, if a project has become inactive, by the organization.

The goal is continuity, not ownership.
