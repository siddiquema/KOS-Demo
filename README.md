# KOS Review Pack (password-protected)

A private review pack for the KOS demo. Every page, image, video and PDF here is encrypted
(AES-256-GCM, key derived from the password with PBKDF2-SHA256, 600,000 rounds). The files in
`enc/` are unreadable without the password, which is shared separately with reviewers.

Open the site, enter the password, and the pack unlocks in your browser. Nothing is sent anywhere.

Built by `scripts/build_protected_pack.py` in the Knowledge-Operating-System repository.
