# 3.2.5

## ShiroA v3.2.5 Release Notes

- Real-Time Watch Party (Nobar) via WebSocket: Create public or private Watch Party rooms with shareable 6-character codes, join active public lobbies, switch between Host-Only and Collaborative playback controls, synchronize Play/Pause/Seek/Episode with heartbeat drift correction, and chat live directly inside the video player
- Cloud Watch History & `.sani` Cloud Backup/Restore: Automatically sync exact episode resume timestamps across devices tied to your AniList/MAL/Discord account with newest-timestamp conflict resolution, plus 1-tap encrypted `.sani` settings & progress backup/restore in Data Settings
- 2-Tier Smart Source Auto-Failover: Automatically recovers from stream, server, decoder, or network playback errors by failing over first to alternative servers/extractors on the current source and then across built-in anime sources, resuming seamlessly at the exact playback timestamp
- Automatic Episode Filler/Canon Detection & OP/ED Theme Preview: Automatically scrapes AnimeFillerList alongside Jikan metadata to display localized Manga Canon, Anime Canon, Mixed, and Filler badges on episode lists, and adds an in-app AnimeThemes Opening/Ending preview player inside Anime Info
- MKV / Torrent Multi-Sub Dissection & Pre-Load Translation Gate: Automatically selects English subtitle tracks when your target language is absent on MKV/Torrent multi-sub streams, dissects ASS/SSA/SRT/VTT packets to bypass untranslated LibASS overlays, and pre-loads translations via Dual Engine (AI Anime Context or Standard Fast) before playback starts to minimize subtitle delay
- Retains all v3.2.4 security, hierarchical Developer/Admin/Moderator controls, webhook-free builds, broadcast announcements, and background release-tag updater features
