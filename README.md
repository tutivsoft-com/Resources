## OpenRouter manifest migration, 2 November 2026

Fourteen additional app/platform key sources now have stable encrypted manifests. These retain the existing AES-256-GCM/PBKDF2 format. Current owners, rotation steps and activation limits are in the [RA1 key delivery owner](https://github.com/humble-new-student-89/RA1/blob/main/MAIN/11%20SOURCE%20of%20TRUTH/openrouter-key-delivery-source-of-truth.md). Existing app releases must first adopt their new loader code; a manifest push alone does not deploy that code.

# Resources

<!-- PORTFOLIO-METADATA:START -->
## Repository metadata

Current source version: **0.0.3** (2026-10-16).

[Architecture](architecture.md) · [AI provenance](ai_model.md) · [History](HISTORY.md) · [Contributors](CONTRIBUTORS.md) · [Manifest](rahul_manifest.yaml).

This maintenance update synchronizes source version metadata and excludes generated junk. Build, runtime, store and deployment verification are separate.
<!-- PORTFOLIO-METADATA:END -->
