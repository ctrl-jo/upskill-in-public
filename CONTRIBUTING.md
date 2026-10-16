# Contributing

An issue is a discussion on GitHub about a suggestion or problem. A pull request is a proposed set of file changes that the owner can review.

## Suggest a path

1. Sign in to GitHub and open [Issues](https://github.com/ctrl-jo/upskill-in-public/issues).
2. Select **New issue**, then **Suggest a path** (and **Get started** if shown). The [template](.github/ISSUE_TEMPLATE/suggest-path.md) shows the fields.
3. Describe the path, why it matters, linked resources, and who it is for.
4. Select **Submit new issue**.

## Propose a fix

1. For a simple report, open [Issues](https://github.com/ctrl-jo/upskill-in-public/issues), select **New issue**, and choose the blank-issue option. Include the file name, the confusing or incorrect text, and your suggested correction.
2. If you already know GitHub editing, open the file in the original repository and select the pencil icon. Follow GitHub's prompt to create a fork (your connected copy) if needed.
3. Make a focused change, save it with **Commit changes** or **Propose changes**, then use **Compare & pull request** in your fork to propose it to `ctrl-jo/upskill-in-public`, branch `main`.
4. Explain what changed and how you checked it, then select **Create pull request**. A report without a code change is welcome too.

## Commit messages for future updates

A commit is a saved set of file changes. Future contributions to this repository follow [Conventional Commits 1.0.0](https://www.conventionalcommits.org/en/v1.0.0/). The older setup commits remain unchanged. This is a contributor and maintainer review convention; there is no automatic commit-message check installed.

```text
type(optional-scope): short description
```

The type describes the change. The optional scope names the area affected. For example, `docs(web): expand the frontend roadmap` updates learning documentation in the web path.

| Type | Use in this repository | Example |
| --- | --- | --- |
| docs | Learning guides, roadmaps, resources, or wording | `docs(aws): add the fundamentals roadmap` |
| feat | A new working feature or runnable learning example | `feat(javascript): add a word counter example` |
| fix | A bug in runnable code | `fix(javascript): handle empty word counter input` |
| chore | Repository maintenance | `chore: update ignore rules` |
| ci | Automated checks or build workflows | `ci: check documentation links` |
| test | Tests for runnable examples | `test(javascript): cover empty input` |
| refactor | Code restructuring without changing behavior | `refactor(javascript): simplify word counting` |
| style | Code formatting only | `style(javascript): format project examples` |
| perf | A code performance improvement | `perf(javascript): avoid repeated scans` |
| build | Build tooling or dependencies | `build: update example dependencies` |
| revert | Undoing an earlier change | `revert: remove an unfinished example` |

These type choices and lowercase spelling are repository preferences. Conventional Commits allows additional types. Suggested scopes are `web`, `mobile`, `azure`, `aws`, `gcp`, `javascript`, `templates`, and `contributing`; a scope is optional. Correcting a broken documentation link uses `docs`, while fixing executable behavior uses `fix`.

1. Group one logical change into each commit. Separate unrelated roadmap updates and code fixes.
2. Choose a type from the table and, if useful, a short scope. Write a specific action after the colon and one space, such as `docs(mobile): add platform selection steps`.
3. On GitHub, enter that message in the short message field in **Commit changes**. With Git, use `git commit -m "docs(web): expand the frontend roadmap"` after staging the intended files. Students' private logs do not need this convention; it applies to contributions here.
4. If more explanation is needed, add a body after a blank line. Optional footers go after another blank line; for example, `Refs: #12` refers to issue 12.
5. For a breaking change, one that makes an existing documented usage stop working, add `!` immediately before the colon and explain how to adapt. A `BREAKING CHANGE:` footer is also supported. Routine new lessons are not breaking changes.
6. Use the same format for a pull request title. Before merging, the maintainer reviews commit messages. When using **Squash and merge** (combining the proposed changes into one commit), the maintainer sets the final message to this format. Published history is not rewritten just to rename old commits.

Example of an intentional breaking change:

```text
docs(paths)!: move a learning path to a new folder

The path now has a clearer name.

BREAKING CHANGE: Update saved links from the old folder to the new folder.
```

## Content rules

1. Add only content you wrote yourself, or links to official or free sources. Never copy paid or copyrighted material from someone else.
2. Write original roadmaps in simple language, explain new terms, and use numbered steps for instructions.
3. Put shared guides in `paths/`. Keep personal learning work in your own copy's `my-learning/` folder.
4. Follow the standard path template below for every new learning path or cloud provider. Group overviews and topic folders can use a shorter introduction.
5. Check every relative link (a link to another file in this kit), add the path to [the index](paths/README.md), and use only **Available** or **Planned** for its status. A Planned stub must clearly say **Coming soon**.

## Standard path template

1. Copy the existing [mobile app development folder](paths/software-development/mobile-app-development/) as the starting folder for a new path. It contains the three required files without extra topic folders.
2. Rename the copied folder with lowercase words separated by hyphens. Replace its title and content; use the README outline below in this exact section order.
3. Write an original `roadmap.md` and linked `resources.md`, or label both **Coming soon** for a Planned route. Add optional topic folders only when needed.
4. Replace `RELATIVE-PATH` below with the path from the new folder to the root `my-learning/README.md`. At the same depth as mobile app development, it is `../../../my-learning/README.md`. Check the link by opening it.
5. List every direct file and subfolder in **Folder contents**, including the README itself. Update the parent overview and path index.
6. Read the route as a first-time learner and verify all its links before proposing the change.

```markdown
# [Path name]

## What this path is

[Two or three simple sentences explaining the path.]

## Who it is for

[Audience and any prior knowledge.]

## How to use this folder

1. Read [roadmap.md](roadmap.md).
2. Open [resources.md](resources.md) and pick one free resource.
3. Take your own notes in [my-learning](RELATIVE-PATH).
4. Build one small project.
5. Share what you learned when ready.

## Folder contents

| Item | Purpose |
| --- | --- |
| [README.md](README.md) | This introduction. |
| [roadmap.md](roadmap.md) | Learning order. |
| [resources.md](resources.md) | Outside learning links. |

## Status

[Available or Planned]
```

## Standard roadmap format for every future path

Each roadmap follows foundations, a choice of direction, a small project, and next steps toward a role. A role is a kind of work, such as frontend developer or cloud administrator. A roadmap is guidance, not a job guarantee.

1. Keep the existing five-section README format above. Copy the mobile folder for the three-file structure, then replace its content for the new subject.
2. Use the roadmap outline below. Include entry requirements, a 10–30 minute first task, plain definitions, numbered actions, and a visible checkpoint for every stage.
3. Make timing flexible. A learner moves on when they can show the checkpoint; finishing by a fixed month is not required. Offer a review task for learners with prior experience.
4. Give a clear default route and optional branches. Explain which foundations each branch needs. Do not require learners to complete every branch or use every tool.
5. Pair each stage with a resource in `resources.md`. Explain free reading versus optional paid tools, services, labs, or exams. Keep the project possible without purchasing a certificate.
6. For cloud paths, separate fundamentals study, practical engineering skills, and later role-based certification study. Verify certification names and codes against official sources and record the verification date.
7. Mark the path Available when its beginner route and links are usable. Mark unfinished stages **Planned — Coming soon**, even when the parent path is Available. Keep the root README, path index, parent overview, FAQ, and choosing guide consistent.
8. Verify links and checkpoints, then use a Conventional Commit message for the update.

```markdown
# [Path] roadmap

## Before you start

[Prerequisites, tools, costs, flexible pace, and first small task.]

## Stage 1: Foundations

1. [Read a linked resource and explain a basic idea.]
2. [Practice one small task.]

Checkpoint: [Something the learner can demonstrate.]

## Stage 2: Choose a direction

1. [Choose one role or platform using clear criteria.]
2. [Follow its next practice steps and resource links.]

Checkpoint: [A result for the chosen branch.]

## Stage 3: Build and check

1. [Make an original small project.]
2. [Check a normal case and a failure case.]

Checkpoint: [A working result or documented design.]

## Stage 4: Share and continue

1. [Save evidence and an explanation in my-learning.]
2. [Choose a next role-focused topic.]

[Separate Available material from Planned — Coming soon additions.]
```
