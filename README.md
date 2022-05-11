# Eliza

On of those ergo in one piece layouts.
They tend to have short feminine names such as `Alice` and `Elise`.
The layout was inspired by the `Prime Elise` keyboard which is a very cute 40 percent layout.
I named mine after the Elise but I dutch-ified it.
- 42 key layout
- stabless
  - you press a key at a certain sweetspot which isn't that big
  - if a key is big enough for a stab it's wasting space: you will never hit outside the small sweetspot
- 11.25 degree split
  - First it was 15 degrees but after seeing some Alice style layouts having 6 and 7 degree angles i deradicalized to 11.25

## Stacked acrylic build plan

- M2 standoff mounting:
  - M2x20mm 3.5mm outer diameter round standoffs
  - M2 flat top scews, 5mm long, 5mm wide(top)
- Elite-c v4 usb-c controller
- Handwired:
  - thick brass/copper wiring for rows and columns
  - connect to MCU with thin flexible normal wiring
- Layers: plate (metal), bottom, top, open, closed (acrylic)
- 20.5mm A:
  - 8mm to edge of keycaps
    - 2 x 3mm closed + 2mm top
    - 2mm closed + 2 x 3mm top
    - 2mm top + 2 x 3mm top
  - 1.5mm plate
  - 9mm space on bottom (3 x 3mm open layer)
  - 2mm base layer
- 20.5mm B:
  - 7mm to edge of keycaps
    - 2 x 2mm closed + 3mm top
    - 3mm closed + 2 x 2mm top
    - 3mm top + 2 x 2mm top
  - 1.5mm plate
  - 9mm space on bottom (3 x 3mm open layer)
  - 3mm base layer

## Some notes

- swillkb params:
  - mount holes: 10, 3.5, 15
  - edge padding: 20
  - plate corners: 5
  - kerf: 0.15
- Elite C dimensions: 19mm x 35mm x 5mm
- plate switches selection: 247.498mm x 102.721mm at 26.947, 29.393
- top at 23.945, 26.208 which is relative to switches selection at: -3.002, -3.185
- stroke: 0.189mm (plate)
- 976 gr: (6 x 3mm + 2mm) x (29 cm x 14 cm) perspex clear pmma + foil + stickers
- laserboost cutplate:
  - 2mm screw holes perfect
  - 3.5mm standof holes to small (or stand of to thick)
  - switches fit, but are fitted horizontally (ok with cherry profile)
  - 320 gr

## Costs including shipping, tax, import (for me)

Total: 182.47 eur
- Hardware: 7.22
  - 10 Gold coloured aluminium standoff: M2x20mm, OD: 3.5mm, 5.94
  - 25 M2 stainless steel cross philips flat wafer head screw: 3mm long, 5mm wide, 1.28
- Electronics: 30.52 + ?
  - Elite-C v4
  - 50 through hole diodes
  - unused M2 bits
  - Wiring: ?
- Caps, Switches: 45.62 + ?
  - GMK Oblivion V3.1 ASCII: 37.62 cost + 8 shipping = 45.62 (of which 7.92 is tax)
  - GMK Oblivion V2 Git: 0 (used some caps from left overs of in-use set)
  - Switches: ?
  - Tribosys 3204: 0 (used left over from previous build)
  - Kebo switch films: 0 (used left over from previous build)
- Construction: 99.11
  - Copper plate: 30.87 cost + 20.14 shipping + 10.71 tax = 61.72
  - Acrylic: 15 cost + 15.90 shipping + 6.49 tax = 37.39

Lesson to be learned: when building things like this from scratch you need to order many separate items.
All these are going to have shipping included even if it's just a silly small thing.
Shipping can be more costly than the item itself on many occasions.
I hoped it would be cheaper to build something like this.
I even used some items I already had left over from a previous build reducing the cost.

## handy links

- http://www.keyboard-layout-editor.com/#/
- https://kbplate.ai03.com/
- https://plate.keeb.io/
- http://builder.swillkb.com
- https://kbfirmware.com/
- https://deskthority.net/wiki/Elite-C
