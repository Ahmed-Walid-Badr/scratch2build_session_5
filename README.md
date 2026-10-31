# Scratch2Build - Week 3 Saturday Online Sync (Discover)

This repository supports the **120-minute Saturday online session**. Week 3 focuses on turning static pages into interactive interfaces with JavaScript, DOM mutation, and event-driven behavior.

## Learning goals

By the end of the session, participants should be able to:

- Explain how the DOM represents a page and how JavaScript changes it.
- Describe event-driven behavior, the event loop, event bubbling, and closures.
- Use modern JavaScript syntax: `const`, `let`, arrow functions, and template literals.
- Recognize how a stale closure can produce an outdated UI message.
- Select DOM elements, attach event listeners, and update the page without reloading it.

## Suggested 120-minute run of show

The overview sets a **33% guidance / 67% practice** target and explicitly includes a 15-minute individual mini-task, a 15-minute prayer/rest break, and a 5-minute refresh break. The overview does not assign durations to every remaining item, so the following is a practical suggested allocation:

| Time | Duration | Activity | Mode |
|---|---:|---|---|
| 00:00-00:05 | 5 min | Opening poll and readiness check | Guidance |
| 00:05-00:25 | 20 min | DOM tree, event loop, bubbling, and closures | Guidance |
| 00:25-00:40 | 15 min | Individual stale-closure diagnostic mini-task | Practice |
| 00:40-00:55 | 15 min | Prayer and rest break | Break |
| 00:55-01:22 | 27 min | Live line-by-line review of 2-3 student PRs | Practice |
| 01:22-01:27 | 5 min | Refresh break | Break |
| 01:27-01:35 | 8 min | Weekly assignment briefing and capstone connection | Guidance |
| 01:35-01:50 | 15 min | Short DOM/event-listener application challenge | Practice |
| 01:50-02:00 | 10 min | Q&A, feedback, and Discord wrap-up | Practice / wrap-up |

The active session time is 100 minutes: 33 minutes guidance and 67 minutes practice. The 20 minutes of breaks are additional. The short DOM application challenge is a suggested activity to meet the practice target; it is not separately specified in the overview.

## Repository structure

```text
mini-task/
  index.html       # Browser page for the diagnostic task
  buggy.js         # Deliberately buggy version for participants
  solution.js      # Clean reference solution for facilitator review
  README.md        # Mini-task instructions
```

## Run the mini-task

1. Open `mini-task/index.html` in a browser.
2. Click **Increment** several times quickly.
3. Watch the main counter and the delayed announcement.
4. Identify why an earlier delayed callback can display an old count.
5. Use `solution.js` as the facilitator/reference version after the 15-minute attempt.

No build tools, frameworks, or package installation are required.

## Session activities

- Opening polls and readiness checks.
- Core architecture explanation: DOM tree, event loop, event bubbling, and closures.
- Individual diagnostic mini-task (15 minutes).
- Live code review and PR debrief (2-3 student PRs).
- Weekly assignment briefing, capstone connection, and the 4-step research rule.
- Q&A, feedback collection, and Discord wrap-up.

> **Facilitator note:** The overview mentions a 4-step research rule but does not define its four steps. Add the official instructions before presenting this repository as the complete rule set.

## Topics covered

- DOM selection: `querySelector`, `querySelectorAll`, `getElementById`.
- DOM mutation: `createElement`, `appendChild`, `remove`.
- Class and attribute updates: `classList.add`, `classList.toggle`.
- Event handling: `addEventListener`, click, keyup, and submit events.
- Event lifecycle: bubbling, capturing, and `event.preventDefault()`.
- Array methods: `filter()`, `map()`, and `forEach()`.
- Functional scope, closures, and stale values.
- Real-time input validation and dynamic list rendering.
