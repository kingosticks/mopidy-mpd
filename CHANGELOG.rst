*********
Changelog
*********


v3.1.0 (UNRELEASED)
===================

- Depend on Mopidy 3.1.0.

- Fix ``list`` command filtering. (Fixes: :issue:`27`, PR: :issue:`28`)

- Support additional tag types in music database queries. (Fixes: :issue:`29`, PR: :issue:`30`)


v3.0.0 (2019-12-22)
===================

- Depend on final release of Mopidy 3.0.0.

- Minor documentation improvements.


v3.0.0rc1 (2019-12-21)
======================

Initial release which extracts the Mopidy-MPD extension from Mopidy core.

This is an alpha release because it depends on the pre-releases of Mopidy 3.0.

Changes since Mopidy 2.3:

- Improved the ``swap`` command to swap the tracks without rebuilding
  the full tracklist.
