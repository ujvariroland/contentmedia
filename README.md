# Tennis Lab — media hosting

Public scratch space for videos that are about to be posted to Instagram/Facebook.

The Meta Graph API requires a publicly reachable HTTPS URL to fetch video files when
creating a Reels/post container — it can't accept a direct file upload. This repo exists
only to give it one. Files here are public because they're moments away from being posted
publicly anyway; nothing sensitive (drafts, captions, source data) lives here — that all
stays in the private `contentgenerator` repo.

Managed by `scripts/publish_meta.py` in the main project — you shouldn't need to touch this
repo by hand.
