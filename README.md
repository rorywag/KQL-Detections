# 👹 KQL Detections

KQL detections for Microsoft Sentinel and Microsoft Defender Advanced Hunting and
custom detection rules.

## Browse on the web

These detections are also published at
[sleuthifer.nz/detections](https://sleuthifer.nz/detections/), rendered with their
MITRE ATT&CK mapping, tactic tags and descriptions. That's an easier way to read
them than the raw files here, and it's part of [sleuthifer.nz](https://sleuthifer.nz/).

## Using a detection

Each `.kql` file is a standalone query. Open one, copy the query, and run it in
Sentinel Logs or Defender Advanced Hunting. Any that suit ongoing detection can be
saved as an analytics rule in Sentinel or a custom detection rule in Defender.

Every file starts with a header block describing the detection: its name, author,
date, a short description, a reference, and the MITRE ATT&CK tactic and technique it
maps to.

## A note before you deploy

Test any detection in your own environment first and tune the thresholds and filters
to fit your data. These are a starting point, not drop-in rules.

## Author

Rory Wagner - @Sleuthifer
https://www.linkedin.com/in/rorywagner/
