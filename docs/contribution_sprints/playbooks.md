---
layout: page
title: Sprints Playbooks
parent: Contribution Sprints
nav_order: 4
---

This page contains the information on specific actions for the sprints team.

## Table of Contents

- [Preparing sprint leaders/contributors](#preparing-sprint-leaderscontributors)
- [Hosting office hours for new Sprinters](#hosting-office-hours-for-new-sprinters)

## Preparing sprint leaders/contributors

The ti.to ticket flow includes questions for each Sprints ticket. They ask if the person if they are leading sprints and interested in receiving support before the conference as well as if they are participating in sprints and interested in receiving support.

The purpose here is to collect identify the people we can reach out to for two reasons:

1. They are a sprint leader and need help preparing their project for sprints.
2. They are a prospective contributor and want help getting prepared for sprints.

These participants can be found at https://automation.defna.org/sprints/tickets/. You will need staff permissions to review the information. Ask the automation team in the `#automation` channel on Slack for help here.

The following steps need to be completed for each type of participant:

1. Browse to https://automation.defna.org/sprints/tickets/
2. Download the CSV
3. Filter to the relevant participants
4. Upload the email list to a spreadsheet. Include a timestamp on the column in case we edit it. Include your own email for confirmation purposes.
5. Craft an email text in a Google Doc or similar. Be minimalistic. Include subject line. The communications team can include a button as a link for any call to action.
6. Post on `#communications` channel that you need help sending an email and include the link to the email draft document. It's probably best if they upload the people to be emailed to a email list, such as `YYYY Sprint Leaders` or `YYYY Sprint Contributors`

## Hosting office hours for new Sprinters

Office hours are where new contributors can get their development environment set up and ask questions before the sprints.

### Steps

1. Pick a date and time(s). Aim for one to two weeks before the conference sprints.
2. Create a `.ics` calendar file for each session. See [.ics file guidance](#ics-file-guidance) below.
3. Fetch the list of ticket holders who expressed interest in contributor support. Follow the same steps as [Preparing sprint leaders/contributors](#preparing-sprint-leaderscontributors) and filter to prospective contributors.
4. Craft the invite email using the template in [communication examples](communication_examples.md). Follow step 5 of [Preparing sprint leaders/contributors](#preparing-sprint-leaderscontributors) to send it via the communications team. Include the `.ics` files with the email draft so the communications team can attach them.
5. Ask the communications team (via `#communications` on Slack) to post on social media. Provide them with a short description and any relevant hashtags (e.g. `#DjangoConUS`, `#Django`).
6. Host the session. Share screen to walk through environment setup steps. Leave time for open Q&A.

### .ics file guidance

A `.ics` file lets recipients add the event to any calendar app (Google Calendar, Apple Calendar, Outlook, etc.).

The simplest approach is to create the event in Google Calendar and export it:

1. Create the event in Google Calendar with the correct date, time (UTC), and video call link in the location field.
2. Open the event, click the three-dot menu, and select **Publish event**.
3. Copy the `.ics` link, or download the file directly to attach to the email.

Alternatively, use an online generator such as [icalendar.org](https://icalendar.org/ical-generator.html) to build the file manually. Create one `.ics` file per session.
