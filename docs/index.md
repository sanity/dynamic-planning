---
marp: true
theme: default
class: invert
size: 4:3
---

# PriorityFlow

## A Simple Project Management Methodology

by [Ian Clarke](https://blog.locut.us/about)

---

## Goals

- Ensure that we are working on the right things at any given time by prioritizing what is important and correctly balancing short, medium, and long-term priorities.
- Provide predictability to the team about what will get done when by both prioritizing and estimating tasks.

---

## What is a Task?

A task is a **completable** piece of work, such as:

- Fixing a bug
- Implementing a feature
- Investigating and proposing a solution to a larger problem

Tasks can vary in size from half a day's work to a large project requiring several weeks. However, something like "improve UI" is not a task because it is not clear how to complete it. It is more of a category of work.

---

## Planned and Potential Work

- **Planned work**: A comprehensive, prioritized list of tasks that we will do as a company. The tasks at the top should be started next, and tasks are removed from the list when completed.
- **Potential work**: Tasks that we may do in the future. New tasks are added to the top, and they are periodically triaged and either prioritized and moved to the planned work list or deleted.

---

## Breaking Down Tasks

- Large tasks should be broken down into smaller component tasks as they get close to the top of the planned work list.
- Tasks should be progressively broken down into smaller subtasks as they get closer to being started.
- Tasks must be 4 person-days of work or smaller before they can be started. This process can be part of the planned work grooming process, or it can be a separate, less frequent planning meeting.

---

## Estimation

### Value

To estimate value, stakeholders (such as sales, marketing, and product) can be given tokens that they can assign to tasks based on their perceived value. Google Sheets may be useful for this.

### Cost

Use the "planning poker" technique to quickly estimate task size, ask people to choose between coarse options like 0.5, 1, 2, 5, ... 30 person-days.

Tasks are then prioritized based on value divided by cost, so the task with the highest value per unit of cost is the highest priority.

---

## Planned Work Review

- Review upcoming tasks in the planned work list, particularly those likely to be started in the next week.
- Evaluate whether the current prioritization still makes sense.
- Determine whether tasks are ready to be started.
- Check if anything is missing from the list and move it back to the icebox if necessary.
- Verify that tasks are appropriately categorized as started, done, etc., to ensure the planned work list is in sync with reality.

---

## Regular Process Meetings

- Potential work review: Determine if tasks are still relevant, prioritize if possible, or delete if not.
- Planned work review: Evaluate if tasks are still relevant, reprioritize if necessary, or delete if not.
- Retrospective: A forum for providing feedback on the process, identifying problems, and discussing improvements.

---

## Tools

There are a vast number of project management tools to choose from. Having tried most of them, I recommend Pivotal Tracker because:

- It’s opinionated and most of its opinions are good ones
  Contrast with tool like JIRA which are super-flexible but give people way too much rope to hang themselves
- It automatically calibrates time estimates based on actual progress, using a 
  simple and transparent algorithm based on the idea of “velocity”
