# AniKo Discovery

Public demonstration repository for AniKo on iOS.

Paste this address in Settings → Sources and extensions → Repositories:

https://raw.githubusercontent.com/Urushin/aniko-discovery/main/index.pb

## Sources

- **Discovery Free comics**: the curated free comics supported by AniKo, including Pepper&Carrot and Hokusai Manga.
- **Discovery Wikimedia Commons**: the Wikimedia Commons discovery adapter.
- **Discovery Open Library**: the Open Library discovery adapter.

Install **AniKo Discovery** to add one automatically enabled source combining all three catalogues. Warnings are shown when reactivating a disabled source. Requires the AniKo version supporting the unified Discovery source. Previously installed sources remain available. Content is hosted by its original provider; availability, licenses and access conditions are determined per work. Open Library catalog records do not imply that every book can be read for free. AniKo subscription limits remain unchanged.

## Files

- `index.pb`: extension catalogue using the protobuf repository layout understood by AniKo.
- `index.min.json`: equivalent JSON catalogue.
- `index.db`: SQLite catalogue with `extensions` and `sources` tables. This is metadata, not a mirror of books, comics, images or provider databases. Paste the `index.pb` address in the app; SQLite is provided for inspection and reuse.

This extension selects fixed native adapters shipped in AniKo. They contain no APK, executable extension, credentials or private user data. They are not installable APK extensions for Mihon or Aniyomi. Native adapter and curated work updates ship with the app.

Provider terms and individual work licenses apply to content. This repository does not redistribute provider media.
