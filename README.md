# DCM Remote

A small phone web app for running the DCM lanes away from the PC: lane status, questions waiting on Anthony, a "yes" for a checked merge, and starting lanes.

- It holds no keys or data. Each phone stores its own GitHub fine-grained token in its own browser storage.
- It talks only to the GitHub API. Requests go as comments on dream-culture-movement issue #714; the DCM Hub watcher on Anthony's PC carries them out and replies there.
- The phone never merges by itself: a "yes" asks the PC to run the checked merge, which merges only if the checks pass.

Served by GitHub Pages from `main`.
