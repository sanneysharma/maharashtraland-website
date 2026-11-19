MAHARASHTRALAND.COM — INTERACTIVE MAP TILE FIX (V11.3)

This update addresses the 403 Access blocked tiles shown in the user's browser screenshot.
- Replaces the OpenStreetMap standard tile server with Esri World Street Map tiles.
- Keeps Leaflet interactive zoom/pan and the Maharashtra district GeoJSON overlay.
- Keeps clickable districts, region/district selection and WhatsApp enquiry prefill.
- Keeps the white background, light orange/peach theme, Book Antiqua font and all brand wording, including:
  “Trusted land. Lasting value.”
  “Browse emerging locations and uncover new value.”
  “Own the earth. Shape your future.”
  “Smart ground. Strong returns.”

Basemap attribution is displayed on the map: Esri and its data providers, including HERE, USGS, TomTom and the GIS User Community.
District boundary data source: https://github.com/udit-001/india-maps-data

IMPORTANT TESTING:
The screenshot supplied showed the page opened from a local file (file:///...). Browser security may block the remote GeoJSON fetch when opened this way. Upload the files to GitHub Pages and test the HTTPS website.
The basemap and district boundary GeoJSON both require internet access.
District boundaries are general administrative boundaries, not cadastral/survey/property title boundaries.

Upload/replace these files in the root of the existing repository and commit to main:
1. index.html
2. maharashtraland-logo.svg
3. README.txt

Keep GitHub Pages and DNS settings unchanged.
