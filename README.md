# PR review evidence — October 17, 2026

Screenshots for langgenius/dify#44239.
Before: unmodified production header/card sources at 311a708c1e59110cc739a0d4aeb1ed81f4b2a9fa.
After: production components from feat/43849-app-availability, including the status-label spacing correction.
Chromium renders real header, ordinary/starred cards, Select and Infotip with seeded example data.
This is a composed component fixture, NOT an authenticated Dify deployment or a server-backed filter journey.
The status-menu image illustrates available choices, not a completed backend filtering request.
Narrow images are the unchanged card components at a 390px viewport with 30 long dependency reasons.

This isolated evidence branch is not included in the upstream feature PR diff.
Images are linked from immutable commit URLs so later branch changes cannot alter the evidence.

| Image | SHA-256 |
| --- | --- |
| dify/before.png | 503401e7d2b24c4909a234085ffd6e1a73cfefcef846bb439daf244153c7dc7c |
| dify/after.png | 83cad299143e62f23a7bd4db634f23cc4e0ab607d1a410261e4dd0487f8741fa |
| dify/status-menu.png | 674e063d3d59f19585b8e0a668453f429ba6176a7fcc59562e778be7cdf76beb |
| dify/desktop-details.png | 40dc636f3a916b40f6cb3d7308b4dd15de91e36d09179e7102b339a4a4164c1a |
| dify/ordinary-narrow-details.png | 9ea134ab741f9af5bc3d34529f35792fa27708fa52a08e678f9c8417045c5d59 |
| dify/starred-narrow-details.png | 4186ebd770815f490214a57dd0f194743812e0e56bbd954683cbbcd7ac687a13 |
