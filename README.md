# faizankhan107.github.io

Personal site for **Muhammad Faizan Khan** — PhD researcher at Xi'an Jiaotong University working across time-series forecasting, LLM knowledge systems, RF sensing, and IoT/LoRaWAN engineering.

Single static page. No build step and no JavaScript dependencies.

## Files

| File | Purpose |
|---|---|
| `index.html` | Main personal website — HTML, CSS and inline hero SVG |
| `Muhammad_Faizan_Khan_CV.pdf` | CV linked by the **Download CV** button |
| `README.md` | Repository and publishing notes |

## Current sections

- Time-series and wind-power forecasting
- LLM Wiki / retrieval research
- RF sensing and activity monitoring
- Model serving and engineering
- IoT / LoRaWAN monitoring project
- Freelance web development
- Browser demos and GitHub projects
- Publications
- Education and contact information

The LoRaWAN section describes a verified **simulated** end-to-end workflow using ChirpStack v4, MQTT, Python, SQLite and Docker. It does not claim physical RF gateway or range testing.

## Publish on GitHub Pages

1. Create a repository named exactly `faizankhan107.github.io`.
2. Put `index.html`, `README.md`, and `Muhammad_Faizan_Khan_CV.pdf` in the repository root.
3. In GitHub open **Settings → Pages**.
4. Set the source to the `main` branch and `/ (root)`.
5. The site will be available at `https://faizankhan107.github.io`.

## Related project repository

The LoRaWAN monitor should be published separately as:

`https://github.com/faizankhan107/lorawan-iot-monitor`

The personal site links to that repository from the **Projects and demos** section.

## Editing

Open `index.html` in any editor. Colours, fonts and spacing are CSS custom properties in the `:root` block. Each major content block is a `<section>` with an `id`, so sections can be reordered or edited independently.

## Notes

- The repository keeps only the public PDF CV; the editable Word source is intentionally excluded.
- The LoRaWAN project link becomes active once the separate repository is published.