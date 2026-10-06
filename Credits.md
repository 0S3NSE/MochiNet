# Credits & Attribution

MochiNet stands on a lot of community work. If you build on MochiNet, carry these
forward.

## Mesh protocol & Piglet nodes
- **JustCallMeKoko (JCMK)** — ESP32DualBandWardriver and the ESP-NOW Core/Node protocol
  that MochiNet's mesh Core implements (wire-compatible reimplementation; no upstream
  code is included).
- **hamspiced — Piglet** — the ESP32-C5 node firmware MochiNet collects from. Piglet is
  licensed **CC BY-NC 4.0 (non-commercial)**. MochiNet does not redistribute Piglet; it
  interoperates with it. Respect the non-commercial terms if you use Piglet.

## Surveillance signatures
WiFi OUIs, SSID patterns, and BLE company-ID / service-UUID / name signatures used by
`surveil_sig.h` were compiled from the open counter-surveillance community, including:
- **@NitekryDPaul** — nite-oui-collection (Flock OUI research, addr1 receiver technique)
- **DeFlock / DeFlockJoplin** — Flock Safety mapping and prefixes
- **nyanBOX (Nyan Devices)**, **OUI-Spy**, **Eye Spy** — Axon / Meta / Flock / AirTag /
  Tile / Flipper BLE signatures and detection techniques

Signature matching is a heuristic and these lists change over time — update
`/flock/oui.txt` on the SD card as the community publishes new prefixes.

## Libraries
- **NimBLE-Arduino** (h2zero) — BLE scanning
- **Adafruit GFX / SSD1306 / BusIO** — display
- **SmartRC-CC1101-Driver-Lib** (LSatan / ELECHOUSE) — CC1101 sub-GHz (optional)



If an attribution is missing or wrong, open an issue — it'll be fixed.
