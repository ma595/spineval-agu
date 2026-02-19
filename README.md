# AGU Presentation

Slides for AGU 2026 - "A Physics-Based Benchmarking Platform for ML-based Spinup off the NEMO Ocean Model"

Slide rendered [here](https://ma595.github.io/spineval-agu).

## Building

To build the presentation, run:

```bash
quarto render agu-presentation.qmd
```

Or preview in development mode:

```bash
quarto preview agu-presentation.qmd
```

## Structure

- `agu-presentation.qmd` - Main presentation file
- `_intro.qmd` - Introduction section
- `_main_content.qmd` - Main content section
- `_conclusion.qmd` - Conclusion section
- `custom.scss` - Custom styling
- `references.bib` - Bibliography
- `images/` - Images and figures

## Required Extensions

This presentation uses the following Quarto extensions:

- [attribution](https://github.com/quarto-ext/attribution) - For image attributions
- [fontawesome](https://github.com/quarto-ext/fontawesome) - For Font Awesome icons

Install them with:

```bash
quarto add quarto-ext/attribution
quarto add quarto-ext/fontawesome
```

## License

MIT License - See LICENSE file for details.
