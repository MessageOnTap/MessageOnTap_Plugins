# MessageOnTap_Plugins
This is a collection of official plugins of MessageOnTap.

## Project Structure
This is an Android Studio project with 4 modules:

* [Google Docs Plugin](https://github.com/MessageOnTap/GoogleDocsPlugin)
* [I am Home Plugin](https://github.com/MessageOnTap/ImHome)
* [Smart Calendar Plugin](https://github.com/MessageOnTap/SmartCalendar)
* [Starbucks Plugin](https://github.com/MessageOnTap/StarbucksPlugin)

Each module is a submodule of this Git Repo and is NOT dependent on other
modules. However, cloning the separate repo without cloninig this repo will
lead to compilation errors, because some shared Gradle-related files are only
in this repo. **Hence, it is recommended that you clone this repo and only
fetch the submodule that you need.**

## Auto Roller
The master branch contains not necessarily the newest code. While you could
always fetch the newest code by fetching the master branch of each plugin repo,
**you can also clone the
[nightly](https://github.com/MessageOnTap/MessageOnTap_Plugins/tree/nightly)
branch of this repo, which is updated to the newest available code every
midnight (UTC) by our Auto Roller.**

*Be advised that the nightly branch might not work stably, since it's
auto-updated. It will only be merged back to master branch when project
maintainers have manually tested them.*

## Contribution
All submissions, including submissions by project members, require review. We
use Github pull requests for this purpose. Please do NOT submit pull requests
to this repo. Only submit pull requests to individual plugin repos.

Upon submitting pull requests, you must agree that your contribution is
offered under and will be made available under the project's existing license
(Apache 2.0).
