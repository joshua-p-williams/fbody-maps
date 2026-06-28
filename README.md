# fbody-maps

**MAPS — Modular Automotive Positioning System**

An open-source, 3D-printable mounting platform for 1993–2002 GM F-body vehicles. MAPS provides vehicle-specific mounting bases and standardized accessory interfaces for Holley EFI displays, gauges, phones, cameras, switch panels, and future accessories.

## Project Goal

The first implementation is a low-profile modular driver-side A-pillar base for a 4th generation Firebird / Trans Am. The base should conform to the factory pillar trim and expose a reusable interface for interchangeable accessories.

The Holley 3.5-inch display mount is the first planned accessory, but the system should not be designed around Holley only.

## Design Principles

- Vehicle-specific bases, standardized accessory interface.
- Low-profile and interior-friendly.
- No permanent vehicle modification required where practical.
- Printable on consumer FDM printers.
- Designed for iterative prototype testing.
- Prefer clean CAD solids over raw scanned mesh geometry.
- Treat scans as reference data, not final printable geometry.

## Initial Scope

### Version 0.1
Create a simple A-pillar saddle prototype that fits the factory pillar contour.

### Version 0.2
Refine the saddle fit and add VHB tape recesses.

### Version 0.3
Add the MAPS accessory interface.

### Version 1.0
Release the first complete Holley 3.5-inch display accessory.

## Repository Layout

```text
docs/                       Project documentation
docs/standards/             MAPS interface standards
docs/design/                Design decisions and notes
docs/testing/               Fitment and validation notes
scans/                      Raw and processed 3D scans
cad/freecad/                FreeCAD source models
exports/stl/                Printable STL exports
exports/step/               STEP exports for interoperability
prints/prototype-logs/      Prototype fitment notes
images/                     Project images and renderings
tools/                      Scripts or helper utilities
```

## Target Vehicle

Initial target:

- 1993–2002 GM F-body
- Pontiac Firebird / Trans Am driver-side A-pillar
- Add-on saddle base mounted over the factory pillar trim

Camaro compatibility should be validated separately.

## License

Hardware/CAD files and documentation licensing should be finalized before public release. See `LICENSE-NOTES.md`.

## Status

Early prototype planning. No released printable parts yet.
