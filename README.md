# CabFlow website

Public marketing website for **CabFlow**, Digital Unity's parametric fitted-furniture manufacturing operations product.

The working public descriptor is **Parametric fitted furniture manufacturing software** and the current lifecycle strapline is **Design. Manufacture. Manage. Deliver.**

## Source of truth

The internal marketing and commercial working brief lives in the CabFlow Confluence space under **01 - Marketing & Website**. The working visual identity is recorded on the **Brand Graphics** page in the same area.

The public site must keep a clear distinction between:

- implemented CabFlow components;
- workflows and domain behaviour proven through reference implementations;
- planned product capability;
- future commercial direction.

Do not publish customer-specific data, internal network or architecture details, credentials, legacy weaknesses, or unverified SaaS claims.

## Brand direction

The current working visual system uses:

- dark navy / charcoal for the CabFlow technical foundation;
- teal and aqua for the parametric core and operational flow;
- orange as a restrained action / delivery accent;
- the exploded isometric cabinet and connected warehouse / delivery motif as the primary product illustration;
- the `Cab` / `Flow` colour split in the wordmark.

Raster crops of the approved working graphics are included in `assets/` for the current website. These remain working references until final production vector assets are prepared.

## Website status

This repository is an early public website workbench and is intentionally independent of a production domain while positioning, visual identity and commercial messaging are refined.

## Development

The site is deliberately dependency-free static HTML and CSS that can be served locally or through GitHub Pages.

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000.
