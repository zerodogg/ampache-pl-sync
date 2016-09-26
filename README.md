ampache-pl-sync
===============

ampache-pl-sync is a simple program that can sync an M3U file with the
[Ampache](https://github.com/ampache/ampache) streaming application. It allows
you to keep a playlist in ampache up to date with a M3U playlist file. This is
useful if you use other software to create playlists, such as an MPD server,
that you then want to have available from ampache on the go. Ampache itself can
import M3U's, but can't update them once imported. ampache-pl-sync solves that.
It can be used to update playlists that have already been imported through
ampache's builtin playlist import feature, or it can create a new playlist
itself.

Dependencies
------------
- Perl (version 5.20 or later)
- The following perl modules: DBI IO::All Try::Tiny List::MoreUtils
  Config::Tiny
