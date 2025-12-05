# Branching and Merging

Branches allow you to experiment without actually changing the main code in a given project

## How to Create a Branch
- '''bash
- git branch feature-xyz
- git checkout feature-xyz

## Why Branches Matter
- Safe experimentation
- Multiple people can collaborate
- The main code for the project is still able to run

If you are happy with the changes you made in your branch and want to bring them to the main project, then you can merge the changes

  ## Merging a Branch
  - git checkout main
  - git merge feature-xyz
 
---

## Navigation
- [Back: Commits](commits.md)
- [Next: Collaboration](collaboration.md)
