# DMMD website

Public marketing website for the product currently using the **DMMD** working visual identity.

**DMMD** represents:

- **Design**
- **Manufacture**
- **Manage**
- **Deliver**

The first D is mirrored horizontally in the production mark so the monogram forms a balanced four-letter system around the two central M characters.

The public descriptor is **Fitted furniture manufacturing operations software**.

## Public identity

DMMD is the working visual product identity while the final commercial word-name and public domain are selected separately.

The public website must not depend on any parent-company branding. The product should stand on its own.

The public site must keep a clear distinction between:

- implemented product components;
- workflows and domain behaviour proven through reference implementations;
- planned product capability;
- future commercial direction.

Do not publish customer-specific data, internal network or architecture details, credentials, legacy weaknesses, or unverified SaaS claims.

## Visual system

The current identity uses:

- a mirrored **D M M D** monogram;
- deep navy / charcoal as the technical foundation;
- teal and aqua for the master identity, action and operational connection;
- white as the active capability highlight;
- restrained orange only where a genuine semantic accent is useful;
- the existing isometric cabinet-to-warehouse-to-delivery visual language.

Subsystems reuse the same monogram rather than creating unrelated product logos:

- **Design** highlights the mirrored first D;
- **Manufacture** highlights the first M;
- **Manage** highlights the second M;
- **Deliver** highlights the final D.

## Handheld evidence

The website may show the accepted delivery UX as a proven capability. The approved Zebra build includes the branded welcome/dashboard/loading/delivery/signature/completion experience, explicit scan feedback and durable offline/synchronisation behaviour.

Public examples must remain synthetic or sanitised. Do not expose customer names, addresses, signatures, coordinates, device identifiers, credentials or private infrastructure.

## Website status

This repository remains the current website workbench while the final commercial brand name and domain are being selected.

## Development

The site is dependency-free static HTML and CSS.

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000.
