# SuperBLT Hasher Contribution Guidelines

:tada: **Thanks for taking the time and effort to make SuperBLT Hasher better!**

## Code of Conduct

This project and everyone participating in it is governed by the [SuperBLT Hasher Code of Conduct](./CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code. Please report unacceptable behavior to `strappazzon [AT] protonmail [DOT] com`.

## Crash, Error, Issue reporting/Feature requests

* Take a look at the [issues](https://github.com/Strappazzon/PD2-SuperBLT-Hasher/issues) first to make sure your issue/feature hasn't been reported/requested before. If so, engage in the already existing discussion.
* Check whether your issue/feature is already fixed/implemented.
* Check if the issue still exists in the latest release.
* Issues in languages other than English will be closed and ignored.
* If you are a Visual Basic .Net developer, you are always welcome to fix/implement an issue/feature yourself. PRs are welcome!
* Add one issue at a time. Do not put multiple issues into one thread.
* When reporting a bug please describe the steps which reproduce the problem.
* When reporting a crash include the stack trace from SuperBLT Hasher (click the "**▼ Details**" button in the crash window). Include the stack trace in the issue in a [file attachment](https://help.github.com/en/github/managing-your-work-on-github/file-attachments-on-issues-and-pull-requests), or put it in a [PrivateBin](https://privatebin.net/) and provide the link to that paste.
* All issues must be properly formatted with Markdown. If you don't know what that is, read [Mastering Markdown](https://guides.github.com/features/mastering-markdown/) before submitting an issue.

### DO NOT post "+1" comments

**DO NOT post "+1", "me too", or similar comments - they just add noise to an issue.**

If you don't have any additional info/context to add but would like to indicate that you're affected by the issue, upvote the original issue by clicking its [+:smiley:] button and hitting :thumbsup: (+1) icon.

## Code Contribution

* Make changes on a separate branch, not on the master branch, then send your changes as a pull request.
* When submitting changes, you confirm that your code is licensed under the terms of the [MIT License](https://opensource.org/licenses/MIT).
* Please test (compile and run) your code before you submit changes. Untested code will **not** be merged!
* Make sure your PR is up-to-date with the rest of the code.

## Website Development

SuperBLT Hasher website is inside `/docs`, so it’s easy to keep docs and code in sync.

The website is built with [Jekyll](https://jekyllrb.com/), and automatically deployed onto GitHub Pages.

Even though bundled in this repo, the website is regarded as a separate project.

### Local Previews

See [docs/README.md](https://github.com/Strappazzon/PD2-SuperBLT-Hasher/blob/master/docs/README.md).

## Git Commit Messages

* Use the present tense ("Add feature" not "Added feature").
* Use the imperative mood ("Move cursor to..." not "Moves cursor to...").
* Reference issues and pull requests after the first line.
* When changing the website, README, documentation, etc., start the commit message with `docs:` ("docs: Update index.html").

## Licensing

By contributing to this repository, you agree to license your work under the current license of this repository: In this case, MIT.

## Project Structure

### Repository Structure

This is a brief description on how the repository files and folders are structured and what each one contains. It only contains the most relevant files and folders as most of them are brief and self-explanatory.

```sh
PD2-SuperBLT-Hasher/
 ├─ .gitignore               # Ignored files, directories and paths
 ├─ BUILDING.md              # Building instructions
 ├─ version                  # File used by SuperBLT Hasher updater
 │   
 ├─ .github                  # GitHub files
 │   ├─ CODE_OF_CONDUCT.md   # Code of Conduct
 │   ├─ CONTRIBUTING.md      # Contributing guidelines
 │   ├─ README.md            # Repository Readme file
 │   └─ ISSUE_TEMPLATE       # Issue templates
 │   
 ├─ .vscode                  # Visual Studio Code-related files
 │   └─ tasks.json           # Visual Studio Code tasks
 │   
 ├─ script                   # Scripts
 │   ├─ build.bat            # Build SuperBLT Hasher from source
 │   └─ jekyll-serve.bat     # Preview the website locally
 │   
 ├─ docs
 │   ├─ _config.yml          # Jekyll configuration
 │   └─ assets               # Website assets (images, CSS, ...)
 │   
 └─ src                      # SuperBLT Hasher source code
     └─ SuperBLTHasher.sln   # Visual Studio solution
```
