---
name: Event lifecycle management
about: Add support for creating, editing, and deleting extracurricular events
title: "Add event lifecycle management"
labels: ["enhancement", "feature"]
assignees: []
---

## Summary
Add the ability for club organizers to create, update, and remove extracurricular events in the school activities system.

## Problem
The current project only exposes a static list of activities and a simple sign-up flow. It does not support organizers managing events after they are created.

## Proposed behavior
- Create a new event with a name, description, date, location, and capacity
- Edit an existing event
- Delete or cancel an event
- Associate each event with a club or activity group
- Show event details in the UI
- Prevent invalid or incomplete event data

## Acceptance criteria
- Users can create an event from the activity or club page
- Users can edit an event's details
- Users can delete an event
- Event data is persisted in the app
- The UI reflects the updated event list after changes

## Notes
This feature is based on the event management capabilities in the EsieaBoard project and would extend the current extracurricular activity system beyond simple signup.
