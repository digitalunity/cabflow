# CabFlow website

Public marketing website for **CabFlow**, Digital Unity's cabinet-manufacturing operations product.

CabFlow's intended product scope connects customer and job workflow, parametric cabinet engineering, production and machine outputs, finance, dispatch and delivery.

## Source of truth

The internal marketing and commercial working brief lives in the CabFlow Confluence space under **01 - Marketing & Website**.

The public site must keep a clear distinction between:

- implemented CabFlow components;
- workflows and domain behaviour proven through reference implementations;
- planned product capability;
- future commercial direction.

Do not publish customer-specific data, internal network or architecture details, credentials, legacy weaknesses, or unverified SaaS claims.

## Website status

This repository is currently an early public website workbench. It is intentionally independent of a production domain while positioning, visual identity and commercial messaging are refined.

## Development

The first version is deliberately dependency-free: static HTML and CSS that can be served locally or through GitHub Pages.

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000.

## Brand assets

The current page uses a temporary text wordmark. Replace it with the approved CabFlow logo/brand assets when those assets are brought into this repository.
