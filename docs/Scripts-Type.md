## Archivist Scripts? Audio-Only Scripts?

**Archivists Scripts**: Scripts made for data archivists/data hoarder: The scripts to use if you want to save some specific content in the best possible quality along with every possible metadata.

**Audio-Only Script**: Script made to download audio-only content (or that will extract the audio from videos that contain it) in the best possible quality.

---

### Archivist Scripts:

Downloading and archiving YouTube content is complicated, especially because YouTube sometimes can take days to transcode videos to the best quality. A workaround to this issue is to have a script that will download everything that came out 30 days ago (and before) and, to avoid missing videos takedown/delete, have a script that will download everything created in the last 30 days potentially in a quality that's not the best.

Considering that I chose to separate the content:

**Archivist Scripts**: Scripts that will download everything that was created before the current date, minus 30 days. For example, if the current date is 2021-01-30, everything created **before** 2021-01-01 will be downloaded. This is needed because YouTube takes time to transcode videos (usually 1 week but sometimes more, the script assume it will take a maximum of 1 month).

**Recent Scripts**: Scripts that will download everything that was created the current date, minus 30 days. For example, if the current date is 2021-01-30, everything created **after** 2021-01-01 will be downloaded, it won't necessarily download the best possible quality since YouTube sometimes takes days to weeks to process videos, however it's useful to have in case videos get takedown by YouTube or their author in the first month.

---

### Audio-Only Scripts:

**Channels / Playlists / Unique**: Same as "Archivist Scripts", but for Audio-Only content.