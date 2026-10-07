# Everwright uptime

Checks every five minutes, from GitHub, that each Everwright site answers. When one stops, an issue
labelled `down` opens (GitHub emails the people watching this repo); when it answers again, the issue
closes. Sites: `SITES` in `.github/workflows/check.yml`. Public so the checks cost nothing; it holds
only public addresses.
