# Canary spec

A made-up spec for the canary's test landings.

## Problem Statement

The canary app needs a greeting.

## Seams

- `app.js`, the only module.

## Acceptance Criteria

| AC | Requirement (EARS) | Red test | Observable | Judge |
|---|---|---|---|---|
| AC1 | When the app loads, it shall export a greeting. | Import app.js and expect a string. | The exported value. | The canary walk |

## End-to-end verification

Import `app.js`.

## Non-goals

None.

## Open questions

None.
