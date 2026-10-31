# banan-uptime

Uptime monitor for banancakes.vn. Every 5 minutes a GitHub Actions run probes
the public sites (`.github/workflows/uptime.yml`); a failed run emails the
account that last changed that workflow. `keepalive.yml` stops GitHub from
switching the schedule off after 60 quiet days.

No code or secrets live here, only public URLs.
