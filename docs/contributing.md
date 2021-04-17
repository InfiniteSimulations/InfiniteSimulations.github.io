# Contributing Guide

The four best ways for you to contribute to the Church of Infinite Simulations is to contribute to the [Church Wiki](https://github.com/InfiniteSimulations/InfiniteSimulations.github.io/wiki), [volunteer to do website development](https://github.com/InfiniteSimulations/InfiniteSimulations.github.io), and help develope our AI technology core, the [Kabuki Starship](https://github.com/InfiniteSimulations/InfiniteSimulations.github.io/wiki).
## Bug Reports

**1.** Ensure the bug was not already reported by by reading the [Issues](https://github.com/InfiniteSimulations/InfiniteSimulations.github.io/issues).

**2.** Open `/docs/bug_report_template.md` and copy it's contents to the clipboard.

**3.** Create an issue, paste the template into the Issue body and fill it out.

## Feature Requests

**1.** Same as the instructions for submitting a bug report except with using `/docs/feature_request.md`.

### Completing Issues

**1.** Clone the repo and create a branch for the IssueNumber:

```Console
git clone https://github.com/InfiniteSimulations/InfiniteSimulations.github.io.git
cd InfiniteSimulations.github.io.git
git checkout -b Issue123
```

**2.** Complete the issue with passing unit tests and submit the completed issue:

```Console
git add --all
git commit -m "ModuleID.Add feature XYZ. #123"
git push origin Issue123
```

**3.** Create a Pull Requesting using the `/docs/pull_request_template.md`

**4.** Get others to inspect your changes and merge the branch to the master.

**5.** Merge the branch, complete another ticket, and delete the old branch. Please replace Issue123 with the last branch used, and Issue125 with the current Mission number.

```Console
git branch -m Issue123 Issue125
git add --all
git commit "module_id:Fix feature ABC. #125"
git branch -d Issue123
```

## License

Copyright © 2020-1 Church of Infinite Simulations.

This Source Code Form is subject to the terms of the Mozilla Public License, v. 2.0. If a copy of the MPL was not distributed with this file, You can obtain one at <https://mozilla.org/MPL/2.0/>.
