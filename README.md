# ISSCC 2025 Country Share Dashboard

A static dashboard to visualize **country shares** (first / last author) overall and by session theme (used here as a proxy for subcommittees).

## Files
- `index.html` — Single-file D3.js dashboard (no build tools required).
- `overall_country_share.csv` — Country-level counts and shares.
- `subcommittee_country_share.csv` — Session-theme × country counts and shares.
- `papers_raw.csv` — Parsed paper list for audit (optional).

## Publish on GitHub Pages
1. Create a repository (e.g., `isscc-country-share`).
2. Upload all four files at the **repo root**.
3. Go to **Settings → Pages**:
   - Source: **Deploy from a branch**
   - Branch: **main**, Folder: **/** (root)
4. Open the Pages URL to view the dashboard.

## Data Update
If you refresh the CSVs (e.g., better parsing), keep filenames the same and re-upload. The page will auto-use the new data on reload.

## Notes
- Session themes are used as a placeholder for subcommittees. If you provide a mapping table (theme → subcommittee), you can update the `subcommittee_country_share.csv` accordingly.
- No external dependencies except D3.js CDN and a Google Font.

---
Generated for internal analysis and visualization.
