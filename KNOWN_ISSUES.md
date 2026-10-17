# Capabilities and limitations

- Relative educational dB values are referenced to a unit analytical source at 1 m. They are not absolute audience SPL, legal exposure levels or equipment capability limits.
- Generic horns use a Gaussian beam approximation; independent point sources omit driver/array mutual coupling and diffraction. Imported JSON complex responses remain relative and unverified; nearest angular sampling may produce discontinuities.
- Venue outlines do not simulate walls or reverberation. Optional image-source ground reflection uses a real constant coefficient. Air absorption is approximate.
- Generic rear-hinge cuboids enforce their defined discrete splay and overlap constraints. They do not represent certified hardware, actual manufacturer mount positions, accessory compatibility or load limits.
- Geometric Auto-Splay aligns aiming lines to selected audience targets. It does not optimize calibrated acoustic coverage. Acoustic Auto-Splay is unavailable.
- Manufacturer catalog objects provide identification only until an explicit analytical approximation or supported relative dataset is selected.
- Limits: 128 sources, 32 cabinets per array, 8 listening surfaces, 16 saved traces and 10 MiB input files. Fine/coherent wide-band studies may exceed the numerical integration budget and must use a narrower band or shorter delays.
- Recent Projects are device-local project snapshots. Autosave recovery is debounced; save important work to a .arraylab file. A hard crash within the debounce interval may lose the newest edit. Browser downloads cannot overwrite an existing file without browser involvement; the native app retains its Save destination.
- Native cancellation stops accepting results; an active Rust tile may finish in the background. Browser cancellation can terminate its WASM worker. Internet is needed for GitHub feedback/downloads, not for packaged calculations.
- The Mac preview is ad-hoc signed and not notarized; Windows is unsigned. OS security warnings are possible. Never globally disable Gatekeeper or SmartScreen.
- Windows physical/interactive QA is PENDING. CI compilation, process survival and engine checks do not prove all Windows GUI workflows.

- Some newly added support/provenance text remains English in Serbian mode.
- Open-source component license declarations, provided notices and upstream notice references are bundled with the demo resources. Some upstream packages publish SPDX declarations without a separate notice file; the inventory records this explicitly.
