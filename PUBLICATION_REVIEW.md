# Website publication review — in progress

Prepared 9 November 2026 for the cleantechpei.org website.
Proposed separate public repository: austingboru/cleantechpei.
No public repository has been created by this preparation process.

## Evidence checked

- Vercel identifies project pei and the cleantechpei.org custom domain.
- Current production deployment: dpl_GBSU7hmbgWPsuKB7VfWag4HNyAw5.
- Its source inventory contains 84 files under the virtual src root.
- The full package.json was retrieved. It declares Next.js 16.4.0,
  React 19.2.4, pnpm 12.3.4, and dev/build/start scripts.
- No .env file appears in that source inventory. This alone does not prove
  the source is free of embedded credentials; full file inspection is pending.
- lib/media.ts contains individual media records; the retrieved prefix
  identifies a photograph licensed CC BY-SA 2.0. It must not be relabeled
  as the author's CC BY 4.0 work.
- Eight WebP files appear under public/images, along with existing site icons.
- A historical internal photo-permission register exists in docs/submission.
  Its truncated contents are not proof of current permissions for all assets.
- The repository includes internal project records and submission screenshots
  that need inspection before public release.

## Remaining work requiring the full v0 ZIP

- [ ] Export all source, configuration, dependency lockfiles and required assets.
- [ ] Check exported versions against the deployed project, noting any changes.
- [ ] Inspect original and copied component code; retain upstream notices.
- [ ] Check every original-content grant and collaborator contribution.
- [ ] Check every media asset against its complete credit record and rights basis.
- [ ] Identify media adaptations and retain their applicable share-alike terms.
- [ ] Exclude secrets, private records and unapproved personal information.
- [ ] Inspect internal records and screenshots for material unsuitable for release.
- [ ] Document real environment-variable requirements using placeholders only.
- [ ] Run dependency installation, project checks and production build.
- [ ] Check educational routes, source citations, media credits and phone layouts.
- [ ] Preserve /portfolio/wind-energy and its working PDF download.
- [ ] Add a real View source link only after the public repository exists.

## Retrieval limitation

The Vercel source-content connection truncates larger base64 file responses.
Both lib/media.ts and the internal photo register were explicitly marked
truncated. Truncated files have not been represented as complete or used to
construct an incomplete website release. The full v0 export is needed.

This documents-only archive is not a publish-ready website release. The live
deployment, domain settings and existing course repository were not changed.
