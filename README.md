
Made for Octowow

REQUIRES NAMPOWER https://github.com/Emyrk/nampower

/ss help for commands

Tracks Soulstones caster and target, will sync/update if others have the addon installed

please let me know if you run into any issues!

---------------------------------------------------------------------------------------------------------------------------

Fork changes

Still syncs with the original SoulstoneTracker: the addon messages are unchanged.

Classic WoW theme
- new default look: Blizzard tooltip-style panel in the same neutral dark colors as Bagshui, gold titles and headers,
  drop-shadow text, silver fading dividers, quest-log hover glow on rows, red title pulse in a stone's last minute
- stock red close button; gold settings cog and S (resync) button that light up on hover
- settings window uses the stock dialog box with a gold header plate that fits the title, checkboxes, sliders and red buttons
- switch back to the original purple look in Settings > Display, or with /ss theme shadow (/ss theme classic to return); needs /reload

Curse and banish section
- a warlock with no curse detected shows a greyed-out Death Coil icon
- a warlock with no banish mark shows a small greyed-out Banish icon
- both turn back to full color once a curse or mark is assigned; clicking them works as before

Minimap button
- same size and round gold border as other minimap buttons (was a small square)

Fixes
- tracking keeps running while the window is closed: expiry warnings, expired alerts and raid announcements,
  clearing expired stones, the soulstone cooldown check and the 5-minute resync used to stop until the window was
  reopened (closing it with the X, the minimap button, /ss or "hide when not in party/raid" all caused it)
- the window isn't redrawn while it's closed, and redraws straight away when reopened

1.5

- added transparency slider
- fixed SS remaining and timer
- fixed column width
- S icon does a sync now vs scan
- added ability to hide when not in party/raid

V1.2 added settings page cleaned up icons

V1.1 added curse/banish tracking

V1.0
