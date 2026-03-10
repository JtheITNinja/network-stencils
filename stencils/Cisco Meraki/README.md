# Cisco Meraki Visio Stencils (.vssx)

A compiled Microsoft Visio stencil file (`.vssx`) built from community-created Cisco Meraki SVGs. Covers a broad range of Meraki product families including switches, wireless access points, security/SD-WAN appliances, cellular gateways, and smart cameras.

## Source

The SVGs this stencil is based on were created by **DrDray** (Cisco Meraki employee), hand-drawn in Adobe Illustrator and shared with the community via Google Drive.

- **Original SVGs:** [Google Drive Folder](https://drive.google.com/drive/folders/1dnnJSBUc2o27ZHrNKfbRsbdnrnvW2Xe2)
- **Community Thread:** [Meraki Community – Meraki SVGs (Visio/LucidChart Stencils)](https://community.meraki.com/t5/Dashboard-Administration/Meraki-SVGs-Visio-LucidChart-Stencils/m-p/216059)
  > ⚠️ The Meraki Community is migrating to [community.cisco.com](https://community.cisco.com) on March 29, 2026. The link above may change — check the Cisco Community if it stops working.

---

## Installation

1. Download the `.vssx` file from this repo
2. Open Microsoft Visio
3. Go to **More Shapes → Open Stencil...**
4. Browse to the downloaded `.vssx` file and open it
5. The Meraki shapes will appear in your stencil panel, ready to drag onto diagrams

---

## Known Visio Compatibility Issue

These shapes are derived from SVGs that use embedded CSS fill styles. When imported into Visio, some shapes may render as **solid black**. This is a known Visio/SVG interoperability issue — not a problem with the SVGs themselves.

### Workaround (per the community)

1. Insert the SVG into your drawing
2. Select the object → **Ungroup**
3. With all elements still selected: **Fill → None**
4. With all elements still selected: **Line → Black**
5. Open the original `.svg` file in a text editor and locate the `fill` hex color values in the `<style>` block near the top
6. Manually reapply the correct colors using **Home → Fill → More Colors → Custom → HEX**

It's tedious, but it works. Alternatively, these SVGs load natively and correctly in **LucidChart** with zero modifications.

---

## Credits

All original artwork credit goes to **Zak (DrDray)** at Cisco Meraki, who created and maintains the SVG library on his own time. If you find missing models or need something added, check the [request form](https://docs.google.com/forms/d/e/1FAIpQLScoGMFLatNRQn4c-w4ljnWj7TFaIfdad-T8yZ60K9cy0MUd1g/viewform) he set up, or the [tracker spreadsheet](https://docs.google.com/spreadsheets/d/1AK7FJzKgY3rDFW2jNJRyClIP4hHhIAVH37dbEfupV88/edit).

---

## Contributing

If you've added models, fixed Visio compatibility for specific shapes, or built an updated version — PRs are welcome. Please note which product families/models are included or changed.

---

## Disclaimer

This is a community resource. Not affiliated with or officially supported by Cisco or Cisco Meraki.
