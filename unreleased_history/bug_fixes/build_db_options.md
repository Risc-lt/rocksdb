* Several DB option settings could be lost through `GetOptionsFromString()`, possibly elsewhere as well. Affected options, now fixed:`background_close_inactive_wals`, `write_dbid_to_manifest`, `write_identity_file`, `prefix_seek_opt_in_only`