# FactSmith widgets (published build)

Public build output of FactSmith widgets, served by GitHub Pages at https://widgets.factsmith.co.za/. Do not edit by hand: each widget has its own source repo and a publish script.

## fs-conditions

Conditions forecast widget (fishing, surf, kite, boat). Source: Emilio-Martin-DataEng/fs-conditions (private).

```html
<fs-conditions place="my-place" lat="-30.6996" lon="30.457" sea-lat="-30.72" sea-lon="30.5"
               coast-bearing="115" modes="fishing,boat" default-mode="fishing"
               climate="https://widgets.factsmith.co.za/fs-conditions/climate/salt-cartel.json"></fs-conditions>
<script type="module" src="https://widgets.factsmith.co.za/fs-conditions/1.0/fs-conditions.js"></script>
```

A FactSmith product. Weather: Open-Meteo.com (CC BY 4.0).
