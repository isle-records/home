ISLE RECORDS — ISLE CLUB replacement

This package preserves the existing single-file ISLE RECORDS website and replaces only the prior circular club block with a coastal venue complex inspired by the supplied reference.

Files:
- index.html — complete website with 3D ISLE CLUB replacement
- assets/audio/isle-ocean.mp3 — ocean/beach ambience
- assets/audio/isle-wind.mp3 — waves/birds/wind ambience
- assets/audio/tomahawk-track.mp3 — supplied TOMAHAWK track

Deploy all files together at the same website root. Keep asset paths unchanged. The 3D engine loads from a small fallback list of Three.js CDNs, so internet access to at least one configured CDN is required. Audio starts only after the visitor explicitly enables it.

Checks run: HTML parser, inline JavaScript syntax (Node.js), club-block static checks, audio-path and file presence checks, package ZIP integrity, and byte-for-byte comparison between packaged index.html and the standalone HTML.

Not run: a true WebGL render/screenshot or FPS benchmark. In this environment the configured external CDN host could not be resolved, so browser rendering could not be verified here.
