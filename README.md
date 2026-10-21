# Language Trainer lesson feed

Downloadable personal language-learning content. No application source code or account credentials.

Catalog: https://raw.githubusercontent.com/justame/language-trainer-lessons/main/catalog.json

On the existing iPhone app, open Library → Lesson source, paste this URL once, tap Done, and download the lesson under Your lessons. It remains available offline. Already-downloaded lessons discover subsequent revisions when the app returns to the foreground or Refresh lessons is used; background checks are scheduled by iOS and are not guaranteed. Active sessions retain their current version until the session ends.

The current Arabic lesson is an explicitly unapproved personal preview: 10 words and 10 example sentences, Hebrew meanings and pronunciation aids, Gemini 3.8 Flash TTS / Charon normal and independently generated slower audio, and Apple Hebrew audio. Its original draft review status is preserved. It needs human pronunciation/naturalness review.

Each revision is immutable under lessons/<id>/<version>/. Its manifest lists exact byte sizes and SHA-256 checksums. Publish a new version for corrections, then replace catalog.json. Do not overwrite released revision files.
