# [Markdown Software Engineering](../)

## Contributing Guide

**1.** Ensure the bug was not already reported by by reading the [Issues](https://github.com/abc_org/xyz_project/issues).

**2.** Open `/docs/BUG_REPORT_TEMPLATE` and copy it's contents to the clipboard.

**3.** Create an issue, paste the template into the Issue body and fill it out.

### Feature Requests

**1.** Same as the instructions for submitting a bug report except with using `/docs/FEATURE_REQUEST`.

### Completing Issues

**1.** Clone the repo and create a branch for the IssueNuber:

```Console
git clone https://github.com/abc_org/xyz_project.git
cd Script2™
git checkout -b Issue123
```

**2.** Complete the issue with passing unit tests and submit the completed issue:

```Console
git add --all
git commit -m "module_id.Add feature XYZ. #123"
git push origin Issue123
```

**3.** Create a Pull Requesting using the `/docs/PULL_REQUEST_TEMPLATE`

**4.** Get others to inspect your changes and merge the branch to the master.

**5.** Merge the branch, complete another ticket, and delete the old branch.

```Console
git checkout -b Issue125
git add --all
git commit "module_id:Fix feature ABC. #125"
git branch -d Issue123
```

## License

Copyright 2020 © Cale McCollough.

This is an open-source source code form, the Source, that was written by and contains intellectual property of the Copyright holder. The Source consists of documents, files, source code, technology design files, art, and other content contained this file, folder and the GitHub repository KabukiStarship/IGEEKCookbook. The Source is published under the Kabuki Strong Source-available License, the License, which is a non-commercial open-source license and is for educational and demonstration purposes only. You may use, reproduce, publicly display, and modify the Source so long as you submit and donate fixes and derived intellectual property, the Donated Ideas, to the Repository as an Issue ticket to become part of the Source. You may not sell the Source or otherwise profit from derivative works created from the Source without the expressed written permission of the copyright holder. Unless required by applicable law or agreed to in writing, the Source distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
