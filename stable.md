# 3.2.4

## ShiroA v3.2.4 Release Notes

- Hierarchical Staff & Role System: Developer can now search, link, and assign or remove Admins and Moderators by ID or Username across AniList, MyAnimeList (MAL), and Discord directly inside Developer Controls with verified checkmark status & notification badges
- Automatic Admin Controls: Users promoted to Admin or Moderator automatically unlock the dedicated Admin Controls menu in Settings (separate from Developer Controls), restricted to comment moderation and temporary bans (24 Hours / 7 Days; permanent bans, mass comment hiding, and staff management remain Developer-only)
- Background Release-Tag Update Notifications: Periodic background update worker checks GitHub releases and sends high-priority notifications displaying the exact GitHub release tag version with one-tap background APK download & install prompt
- Flexible Lookup by ID or Username: User lookup in both Developer Controls and Admin Controls now accepts either numeric AniList ID or AniList Username
- Broadcast Notifications Fix (`shiromanga.my.id`): App now polls both the primary VPS and gateway endpoints (`www.shiromanga.my.id`, `shiromanga.my.id`, `shiromanga-docs.vercel.app`) independently and deduplicates notices accurately so announcements published on `shiromanga.my.id` always appear
- Crash & Issue Reporting Fix: Stricter backend JSON acknowledgement verification and awaited Discord webhook forwarding on `ShiroA-Server` ensure user reports and crash logs reliably deliver to Discord without silently failing on non-JSON responses
- Previous 3.2.3 features retained: built-in streaming parsers for 6 ShiroA sources, multi-language system & Common Settings selector, secure webhook-free APK build, and hierarchical moderation error localization
