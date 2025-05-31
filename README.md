# Unified Metadata Engine (UME)

**Bringing back metadata freedom, local indexing, and community-powered curation — one media file at a time.**

Unified Metadata Engine (UME) is a modular, open-source system designed to index, tag, and manage metadata for all types of media — movies, TV shows, music, audiobooks, podcasts, and even disc images — with optional CLI tools, JSON-based export/import, and future container conversion support.

> 🎞️ Inspired by the vision of Boxee — reborn as a decentralized, file-first platform for the modern age.

---

## 🔧 Core Features (Planned)

- **📦 Media Fingerprinting + Hashing**
  - Identify media by hashes, track layout, and stream contents — not just filenames.
  - Store detailed file-level metadata including codecs, languages, audio layouts, subtitles, and more.

- **🗃️ JSON-Based Metadata Indexes**
  - Create local or shareable `.json` index files for any media item.
  - Embed metadata directly into supported containers (e.g., MKV attachments).
  - Daily `.json` index dumps for syncing, offline use, and archival purposes.

- **🎛️ Cross-Format Metadata Tools**
  - Optional conversion tools (e.g., ffmpeg, MP4Box) to move between MKV, MP4, FLAC, etc. — while preserving and applying metadata.
  - Tagging and retagging based on community-shared index data.

- **🔍 Headless + GUI-Free Operation**
  - Full CLI operation for automation and scripting.
  - Scan entire libraries without launching a GUI.

- **🌍 Community Metadata (Opt-In)**
  - Submit new or unrecognized files to the shared index.
  - Pull known metadata from a public hash-indexed database (similar to MusicBrainz or OpenSubtitles models).
  - Optional user-submitted enhancements (e.g., language notes like "English main, Spanish secondary").

- **🔉 Language + Audio Metadata Focus**
  - Support for complex track setups (e.g., "English primary, Japanese phrases only").
  - Language tagging + fallback preference tracking for players like Plex.

- **📑 Chapter Support + Ratings**
  - Extract, view, and sync chapters.
  - Embed content ratings, creator notes, or edition labels.

---

## 🧱 Long-Term Goals

- **🎙️ AI-Driven Features (Optional, Ethical)**
  - Voice analysis or dubbing (user-hosted only, permission-based).
  - Scene detection, accessibility tagging (e.g., loud music, foreign language alerts).

- **👥 Social/Community Layer (Optional)**
  - Return of "watchlists," "reviews," and "shared libraries" like the original Boxee.
  - Privacy-first federation model — not centralized accounts.

- **💾 Redump + Retro Indexing**
  - Index game ISOs and disc images (e.g., PS1, Saturn, DOS) for local metadata curation.
  - Respect licensing — no ROMs hosted, only hashes and user-added notes.

---

## 🧠 Philosophy

UME is built for archivists, power users, and media lovers who want to own their collections again. We believe metadata should not be locked behind subscription walls, tied to proprietary databases, or reset with every Plex scan.

This project is:
- Free and open-source
- Modular and container-agnostic
- Respectful of copyright and ethical use
- Community-curated, not centrally controlled

---

## 🔄 Status

**Early conceptual stage**.  
Repo structure, CLI prototype, and JSON schema in progress.  
Looking for contributors, testers, and feedback!

---

## 🤝 Contributing

- Want to contribute? Open a discussion or submit a PR!
- Have a media collection you’d like to index and share metadata for? Let’s build the base dataset.
- Want to help design the JSON schema or CLI flow? Reach out!

---

## 📄 License

*License to be determined.*  
Likely to be permissive (e.g., MPL-2.0 or custom with commercial-use rules), but open to discussion.

---

## 🔗 Related Inspirations

- [Boxee (Wayback)](https://web.archive.org/web/20121001000000*/http://boxee.tv)
- [Kodi / XBMC](https://kodi.tv)
- [MusicBrainz](https://musicbrainz.org)
- [FFmpeg](https://ffmpeg.org)
- [MKVToolNix](https://mkvtoolnix.download)
- [Plex](https://plex.tv) (for what it does well — but UME is not a media player)

---

## 💬 Contact

Project ideas, feedback, or curiosity?  
Open an issue or discussion right here on GitHub.

