# Ablo Studio — Campaign Dashboard

Auto-published every 6 hours by the `render_dashboard.py` script in `Brain/projects/ablo/Ablo Studio/autopilot/`.

Live URL: https://alex-runner.github.io/ablo-dashboard/

Sources:
- Meta Marketing API (direct, lifetime + per-adset insights)
- PostHog (project 419152, unfiltered + UTM-filtered funnels)
- Klaviyo (signups roster)
- LinkedIn Campaign Manager export (manual CSV ingest + demographics JSON)
- Autopilot state (`state/last-cycle.json` from the 6h cron)

Not meant to be human-edited -- regenerated on every autopilot cycle.
