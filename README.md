# nacaspanner

## License
This Excel spreadsheet is released under MIT license.

## Usage
Type in your 4-digit NACA airfoil code into the correspondng NACA cells on the spreadsheet. Once all 4 digits are entered, the correct cambered upper and lower y-values (thickness) will be displayed alongside the cambered upper and lower x-values (chord).

The spreadhseet handles symmetric, uncambered airfoil (NACA 00xx) series the same way. It's just that y-sub-c (y_c) will remain at zero and is still represented correctly under the x and y upper and lower coordinate pair values.

## Chord
Maximum chord length by design is 1m for convenience. Can be altered by dragging the list further.

The chord resolution is 0.01m, giving 100 data points each for the upper and lower surfaces.