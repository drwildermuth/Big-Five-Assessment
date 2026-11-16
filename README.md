# Big Five Personality Inventory

A 10-question Big Five personality inventory (BFI-10) for student use. It is a single self-contained page (`index.html`) that runs entirely in the browser. No data is collected, stored, or sent anywhere, and there are no external libraries or fonts.

## Publishing with GitHub Pages

1. In the repo, go to **Settings > Pages**.
2. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, and save.
3. The page will be live at `https://<your-username>.github.io/<repo-name>/` after a minute or two.

## Customizing

Everything is in `index.html`:

- **Items and scoring:** the `ITEMS` list near the top of the script (`rev: true` marks reverse-scored items).
- **Trait names, colors, and descriptions:** the `TRAITS` list.
- **Colors:** the CSS variables at the top of the `<style>` block.
- **Interpretation cutoffs:** the `interpret()` function (4.5+ Very High, 4+ High, 2.5+ Average, 2+ Low, below 2 Very Low).

## Attribution

The BFI-10 was developed by Beatrice Rammstedt & Oliver P. John and is available for non-commercial use (Source: GESIS).

Rammstedt, B., & John, O. P. (2007). Measuring personality in one minute or less: A 10-item short version of the Big Five Inventory in English and German. *Journal of Research in Personality, 41*(1), 203-212. https://doi.org/10.1016/j.jrp.2006.02.001
