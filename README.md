# The Tower — hosted test 18.4

Standalone fantasy RPG test, separate from the live Marbles Anonymous game. Browser-local progression, six sample recruits, permanent per-character exact milestone clears and planned automatic badge bonuses, multiple expedition teams (unlocked at Guardian checkpoints at or above 150, 250, 500 and 1000), reserve deployment and growing camp visuals. Replays award missing personal badges, not repeat currencies or XP. Account-wide historical progress is preserved, but cannot establish individual badge eligibility. The real roster, shared leaderboards, account authentication and main-game rewards are not connected.

Render: static site, main branch, publish directory `public`, auto-deploy enabled. Keep source and assets here.

Camp shows a local character leaderboard (highest floor, level and badges). Sphere Grid uses a clipped, viewport-fitted canvas, plus opt-in automatic token spending at camp. Auto prioritizes unlocked permanent nodes and saves tokens for an affordable next permanent upgrade before using repeatable training.

18.3 adds actual mastery-gain receipts (manual and automatic), a compact touch-friendly node list, six-door portrait layout, per-character distinct floor counts, replay of earlier floors for personal credit, and badge markers on Tower portraits. Existing earned personal badges are grandfathered; historical floors never individually recorded are not assumed. `public/mobile-preview.html` runs the real interface with isolated sample progress. Main-game accounts, roster sync, online saves, rewards and global rankings remain disconnected; the current authoritative main-game source is required before those integrations can be implemented safely.

18.4 centralizes menus, provides full-window compact-screen party, rankings, workshop, expedition management, replay and settings panels, consistent Back-to-Tower controls, focus restoration and background interaction blocking. Desktop rails and gameplay are retained.
