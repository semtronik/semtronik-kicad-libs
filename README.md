# semtronik-kicad-libs

Shared KiCad component library (symbols, footprints, 3D models) for
Semtronik hardware projects.

## Layout

```
symbols/       SEM_*.kicad_sym — one file per component category
footprints/    *.pretty/
3dmodels/      *.3dshapes/
```

## Using this library in a project

1. Clone this repository next to your project's repository.
2. In KiCad, go to **Preferences → Configure Paths** and add an environment
   variable `SEMTRONIK_KICAD_LIBS` pointing to your local clone.
3. The project's `sym-lib-table` / `fp-lib-table` reference libraries as
   `${SEMTRONIK_KICAD_LIBS}/symbols/...` and
   `${SEMTRONIK_KICAD_LIBS}/footprints/...`.

## License

Licensed under [CC-BY-SA 4.0](LICENSE).
