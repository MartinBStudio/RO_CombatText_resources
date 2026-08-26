RO_CombatText_resources
=======================

Overview
--------
This repository is now dedicated to combat text texture resources for Rose Online. It stores texture packs and related asset folders used by combat text overlays and custom combat text setups.

Purpose
-------
Use this repository as the source of truth for texture variants and custom combat text assets. Each top-level folder represents a separate texture profile or pack that can be used by RO_CombatText or related tooling.

Current profiles
----------------

- poc — proof-of-concept texture layout and testing assets

Repository layout
-----------------
Root/
- original/    (original asset files from a game installation or reference source)
- poc/         (testing/custom combat text texture files)
- .idea/       (IDE metadata)

Usage notes
-----------
- Keep each texture profile folder organized in a clear, consistent structure.
- Preserve filenames and folder naming conventions so tools can map them correctly.
- When adding a new pack, create a new top-level folder and place the adjusted assets inside.
- Document any notable edits or visual changes in a small text file such as `CHANGES.txt` inside the profile folder.

Contributing
------------
- Add or update texture packs by creating a new folder or editing an existing one.
- Keep asset names descriptive and consistent across profiles.
- Include notes about any texture changes, color adjustments, or compatibility requirements.

Support
-------
For questions about combat text asset integration, contact the repository owner or project maintainers.
