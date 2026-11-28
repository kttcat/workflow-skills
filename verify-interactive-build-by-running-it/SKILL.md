---
name: verify-interactive-build-by-running-it
description: "Use before delivering any interactive build (page, app, widget): run the real code in three load scenarios (normal, swallowed event, total failure) and confirm it reaches a usable state."
---
# Verify an interactive build by running it

## Run the real code in three load scenarios

- Run the actual code of the build before you deliver it and treat a syntax check or a string search as no check at all.

- Run the normal load path and confirm the build reaches a usable state with no error and no blank screen.

- Run the path where a load event is swallowed and confirm the build still reaches a usable state instead of waiting forever.

- Run the path where the build does not load at all and confirm the failure is visible to the user instead of a silent zero percent.

- Give every loader polling plus a timeout plus a visible failure message and never let it sit silently at zero percent.

- Guard every storage read and every external resource read so one failed read cannot kill the whole script.

## Check the first frame and the settled defaults

- Open the build at its default view and confirm the main content is in frame and identifiable on the first frame.

- Refit the default view from the actual projected bounds of the content after any layout or spacing change and do not reuse a fit based on a theoretical radius.

- List each settled user instruction the fix touches and confirm the fix keeps every one of them before you ship it.

- Keep a settled default such as paused animation unchanged unless the user approves the change in that round.

- Fix the performance or physics fault itself and do not mask it by changing a settled default.

## Check interaction on the devices the user will use

- Check the build on each viewport the user will actually open, including desktop and phone, and treat a pass on one viewport as no pass on the other.

- Click or tap the main nodes and controls after animation starts and confirm each one responds.

- Confirm labels are fully readable and not pressed by a node, covered by another label, or cropped at a screen edge.

- Confirm a legend or panel that covers content can collapse and that the content stays above its top edge.

- Confirm drag, pan, zoom, and reset work on touch as well as on mouse and that input stops any auto motion while the user is interacting.

## Report only what the run showed

- State which scenarios you ran, which viewports you checked, and which interaction you tried before you call the build working.

- Name any scenario or viewport you could not run and keep it out of a verified claim.

- Fix a fault the run shows before delivery and run the affected scenario again after the fix.

- Ask the user to confirm on their own device when the final check is the phone view and say plainly that it is unconfirmed until they do.

## Available connectors

- Use `muse.connector_search` to find other connectors and `muse.skill_search` to find related skills.

- If nothing here fits, look on the web for a maintained API or MCP server and set it up with Custom Connectors and MCPs, or build a custom connector.

## Alternatives for better results

- Split a large build check into one pass for loading, one pass for the first frame, and one pass for interaction so a single pass does not hide a fault.

- Ask the user for the one viewport that matters most when you cannot check every device before delivery.

- Ship the smallest working version first and add motion, labels, and extra views only after the core interaction passes.
