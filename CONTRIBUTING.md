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
