# Obsolete

This feature is now patched in the official check_mk_agent.freebsd.

see:
- [check_mk werk 7481](https://checkmk.de/check_mk-werks.php?werk_id=7481)
- [commit](https://github.com/tribe29/checkmk/commit/bb318c8d15da467d3139e8f355da17ecb0660651)

# check_mk_zfs_arc_freebsd

simple client plugin to collect zfs arc cache data from freebsd in format that can be parsed with default zfs_arc_cache check
see: https://mathias-kettner.de/cms_check_zfs_arc_cache.html

## install 
cp ./zfs_arc_stats /usr/local/lib/check_mk_agent/plugins/.

