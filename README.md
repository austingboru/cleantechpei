# Cleantech PEI

Community-focused clean-technology education, created by Augustine Gboru.
Website: https://cleantechpei.org/

## Preparation status

This package contains repository and licensing documents only. It is not a
complete website source export or a verified public release. Add the full v0
project export and finish PUBLICATION_REVIEW.md before publishing the website
repository. The deployed source inventory contains 84 files; larger files
were truncated by the source retrieval connection and were not reconstructed.

## Intended license scope

Original software: MIT, in LICENSES/MIT.txt.
Original educational content: Creative Commons Attribution 4.0 International,
in LICENSES/CONTENT.md. See LICENSE for how these apply to mixed files.
External media, dependencies, trademarks and other third-party materials
retain their own rights. Preserve item-level credits and license conditions.

## Run locally after adding the full project

The inspected production package declares Node.js 24.x, pnpm 12.3.4,
Next.js 16.4.0 and React 19.2.4. Confirm these against the complete export.
With the matching Node.js and pnpm versions installed, run:

    pnpm install --frozen-lockfile
    pnpm dev

To check and serve a production build:

    pnpm build
    pnpm start

The package declares dev, build and start scripts. This preparation package
has not run them because it does not contain the complete website source.
Do not claim build verification until the full export has been tested.

## Project structure to retain

- app/: Next.js routes and layout.
- components/: educational experiences, diagrams and shared UI.
- lib/: educational content, scientific data, media credits and utilities.
- public/: licensed assets and the wind-learning companion.
- scripts/: existing project verification utilities.
- package.json and pnpm-lock.yaml: dependency and installation information.

The existing /portfolio/wind-energy rewrite must remain functional. Keep the
separate clt6101-open-learning repository as the course resource collection.
Do not change the current production deployment while preparing this release.

## Sources and contributions

Retain scientific citations and the media-credits page. Contributors should
follow CONTRIBUTING.md and identify uncertainty rather than presenting an
untested explanation as an established finding. No endorsement by UPEI,
WEICan or any named institution is implied.
