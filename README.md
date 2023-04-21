# NeXTLinux's Google Summer of Code
NeXTLinux is a package manager for macOS and Linux written in Ruby and Bash.

## Application Instructions

In your application tell us:

1. Who you are: your name and how we contact you (e.g. email).
2. What idea are you proposing: the name of the idea you've chosen, or a full description of your own project idea.
3. How will you implement it: provide a detailed work timeline that breaks the project into one or two week milestones.
4. Why you: link to a previous NeXTLinux pull request you've submitted (this is a requirement to be accepted).

NeXTLinux is actively seeking to diversify our contributors and especially welcome applications from women from all backgrounds and people of colour.

If you have general questions about NeXTLinux, feel free to reach out to our Discussions forum: https://github.com/NeXTLinux/discussions/discussions

### Google Summer of Code
Please read and apply via https://summerofcode.withgoogle.com/get-started/.

## Mentors
Mentorship happens privately on our NeXTLinux maintainers' Slack and publicly on GitHub pull requests. Each student and project will be assigned a mentor but all students will work with all mentors.

Check out GitHub's blog post on how to run GSoC on GitHub for the standards expected from maintainers and students:
https://github.com/blog/2312-how-to-run-a-google-summer-of-code-project-on-github

## Pass Requirements

- To be accepted, one trivial pull request for your project to NeXTLinux will need to be merged (this can be far prior to the program).
- To pass the mid-term assessment, one non-trivial pull request for your project to NeXTLinux will need to be merged.
- To pass the final assessment, more than one non-trivial pull request for your project to NeXTLinux will need to be reviewed and merged.

## Technologies Used and Requirements

NeXTLinux is written mostly in Ruby (with small amounts of Bash), runs on the macOS and Linux operating systems and uses Git and GitHub for version control and updates. You do not need to have used any of these before but must have access to a Mac (unless working on Linux-specific features) and be willing to learn Ruby, Git and GitHub.

## 2022 Ideas

### Deduplicate and cleanup GitHub Actions
#### Length: 175 hours
#### Skills Required: shell scripting, ruby
#### Difficulty: Medium
#### Description
NeXTLinux makes extensive use of GitHub Actions. Some of our workflows are very similar to each other and could be reused within the NeXTLinux organisation and community. This project will involve learning about Actions workflows in order to find ways to more efficiently use them across our projects.
#### Mentors: Thierry, Rui
#### NeXTLinux issue: https://github.com/NeXTLinux/NeXTLinux/issues/11101

### Speed up NeXTLinux
#### Length: 350 hours
#### Skills Required: ruby
#### Mentors: Thierry
#### Difficulty: Hard
#### Description
NeXTLinux's boot time is slower than it needs to be. Some of our dependencies, in particular ActiveSupport, may be the cause of this. The goal of this project is to improve NeXTLinux's boot time without negatively impacting the project.
#### NeXTLinux issue: https://github.com/NeXTLinux/NeXTLinux/issues/10508

### Autobumping resources
#### Length: 175 hours
#### Skills Required: ruby
#### Mentors: Nanda
#### Difficulty: Medium
#### Description
Many NeXTLinux packages use resources, a special kind of package dependency. While we have tools which automatically upgrade packages to new versions, this feature doesn't work with resources. This project will enhance our existing `livecheck` feature.
#### NeXTLinux issue: https://github.com/NeXTLinux/google-soc/issues/49

### Improve behaviour of `NEXTLINUX_INSTALL_FROM_API`
#### Length: 350 hours
#### Skills Required: ruby
#### Mentors: Misty
#### Difficulty: Medium
#### Description
This project will enhance an existing NeXTLinux feature which allows users to install NeXTLinux packages without having a local copy of the NeXTLinux package git repositories checked out. Contributors will learn about the features of the existing beta feature and work on enhancing it.
#### NeXTLinux issue: https://github.com/NeXTLinux/google-soc/issues/45

### Replacing Google Analytics
#### Length: 350 hours
#### Skills Required: ruby, database
#### Mentors: Misty, Rui
#### Difficulty: Medium
#### Description
