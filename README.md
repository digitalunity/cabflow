# CabFlow website

Public marketing website for **CabFlow**, a standalone parametric fitted-furniture manufacturing operations product.

The working public descriptor is **Parametric fitted furniture manufacturing software** and the current lifecycle strapline is **Design. Manufacture. Manage. Deliver.**

## Source of truth

Internal product, marketing and evidence sources are intentionally kept separate from the public brand. The public website must present CabFlow as a standalone product.

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

## Handheld marketing evidence

The website may now show the accepted CabFlow Delivery UX as a proven product capability. The approved Zebra build includes the branded welcome/dashboard/loading/delivery/signature/completion experience, explicit scan feedback and durable offline/synchronisation behaviour.

Public website examples must remain synthetic or sanitised. Do not expose customer names, addresses, signatures, coordinates, device identifiers, credentials or private infrastructure.

The wider CabFlow SaaS and customer-specific commissioning boundaries remain separate claims. Do not turn accepted handheld UX into a claim that all CabFlow SaaS, live tracking, infrastructure migration or every customer rollout is complete.

## Website status

This repository is the public CabFlow website workbench. It is not currently tied to a CabFlow production domain.

## Development

The site is deliberately dependency-free static HTML and CSS that can be served locally or through GitHub Pages.

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000.
