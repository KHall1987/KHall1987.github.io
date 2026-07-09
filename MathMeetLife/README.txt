MathMeetLife widget package
===========================

This package uses a small layered CSS setup:

  assets/mml-toy.css
    Shared base styles: colors, typography, page layout, cards, forms, buttons,
    tabs, tables, status messages, responsive behavior, and print basics.

  assets/widgets/crochet.css
    Crochet-family styles used by:
      - crochet-circle-stitch-calculator.html
      - crochet-sphere-pattern-calculator.html

  assets/widgets/graph-lab.css
    Graph / physics / canvas-family styles used by:
      - spring-constraint-diagram-toy.html
      - global-geodesic-graph-layout.html

Files
-----

  crochet-circle-stitch-calculator.html
  crochet-sphere-pattern-calculator.html
  spring-constraint-diagram-toy.html
  global-geodesic-graph-layout.html

Notes
-----

- The crochet widgets are pattern generators with shared Pattern/Table/Details/Raw text views.
- The spring widget is a 2D canvas visual editor.
- The global geodesic graph widget is a Three.js-based 3D graph solver and loads Three.js from jsDelivr.
- Keep mml-toy.css conservative and reusable. Put family-specific rules in crochet.css or graph-lab.css.
