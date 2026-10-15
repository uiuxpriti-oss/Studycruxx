repo: uiuxpriti-oss/StudyCrux
branch: claude/zealous-lovelace-o9hpsg

## Last sync
date: 2026-10-15T13:00:00Z

### Updated in this project
- Report row actions (Saved Reports, Scheduled, Export Center) moved into a vertical ⋮ overflow menu in all 4 modules.
- Reports rebuilt in Speaker, Student, Teacher and Coordinator on the new Speaker report layout: Overview library + 8 module data tabs (directory, onboarding/enrollment, verification, events/classes/batches, performance, payout/payroll, contracts, activity) + Saved Reports, Scheduled, Export Center.
- Not yet pushed — download the zip and commit to the branch.

## Sync history
- 2026-10-12T09:00:00Z — Speaker 360 / Schedule / Content updates.

### Previously updated (2026-10-12)
- Speaker 360: header card on Coordinator layout; Employment & Recruitment, Personal & Professional, Students, Attendance & Leave, Finance & Payroll rebuilt on Teacher/Coordinator layout.
- Speaker Schedule tab: Day / Week / Month / Agenda calendar with event view, reschedule, cancel, replacement and block-availability flows.
- Speaker Content: View / Change overflow menu with versioned replace flow. Performance 360 header matches Teacher hero.
- Not yet pushed — download the zip and commit to the branch.

## Sync history
- 2026-10-07T12:00:00Z — reports popups, Speaker schedule/escalations/performance rebuilt on Coordinator layout, Attendance & Activity in Teacher and Speaker.

### Previously updated
- Reports (Coordinator, Speaker, Teacher): Generate / Schedule / Preview popups in the Student report style.
- Speaker Schedule: Replacements, Conflicts, Requests, Availability, History tabs (Coordinator layout).
- Speaker Reminders & Alerts → Escalations rebuilt on Coordinator layout (ladder, history table, reminder sequences).
- Speaker performance detail rebuilt on Coordinator layout (header, tabs, Outcomes conversion funnel, Activity tiles, goal bars, audit log).
- Performance row menu (Coordinator, Teacher): Compare + Set Goals popups, View Batches/Classes and View Activity open profile tabs, Export prefilled.
- Speaker Performance KPI cards matched to Coordinator.
- Teacher Course & Batch Allocation: Teachers tab rebuilt as Coordinator-style workload table; KPI cards on one row.
- Speaker Reports rebuilt on the Coordinator report layout (filter bar, category tabs, library cards, saved/scheduled/export).
- New Attendance & Activity module in Teacher and Speaker (8 tabs, module-specific data, settings/export/correction popups).
- Attendance & Activity: Save filter / Saved removed in all 3 modules; Reset always beside Filters.
- Not yet pushed — download the zip and commit to the branch.

## Screen map
| Project screen | Repo files |
| --- | --- |
| index.html (module launcher) | index.html |
| dashboard.html — Platform Overview | StudyCrux Dashboard.dc.html, dashboard.html |
| students.html — Student Management | StudyCrux Students.dc.html, students.html |
| teachers.html — Teacher Management | StudyCrux Teachers.dc.html, teachers.html |
| coordinators.html — Coordinator Management | StudyCrux Coordinators.dc.html, coordinators.html |
| speakers.html — Speaker Management | StudyCrux Speakers.dc.html, speakers.html |
| roles-access.html — Role & Access | StudyCrux Roles & Access.dc.html, roles-access.html |
| design-system.html — Design System | StudyCrux Design System.dc.html, design-system.html, DESIGN-SYSTEM.md |
| runtime | support.js |
| deploy config | netlify.toml |
| images | assets/aarav.png, assets/aditya.png, assets/ananya.png, assets/divya.png, assets/teacher-hero.png |

## Sync history
- 2026-10-05T16:30:00Z — onboarding Add dropdowns, Speaker schedule, Reminders & Alerts and Payouts aligned to Teacher.
- 2026-10-05T12:05:24Z — uploads integrated at project root; photos pulled; Dashboard links wired to modules.
- 2026-09-27T10:05:00Z — Coordinators schedule/drawer parity; Teachers week-cell hover; Roles single-page Create Role form.
- 2026-09-27T07:05:32Z — uploads integrated at project root; photos pulled from repo; launcher links Design System.
- 2026-09-25T15:40:00Z — Students blank-screen fix; Teachers, Coordinators, Roles & Access flows.
- 2026-09-25T14:12:28Z — modules integrated from uploads; photos pulled from repo.
- 2026-09-03T12:37:50Z — all six modules pushed upstream (commit 95ebbc72f990).
