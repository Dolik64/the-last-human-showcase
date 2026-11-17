# Team credits & evidence

[Project](../README.md) · [Visual walkthrough](demo.md)

## Team

The original project README lists three team members. The contribution tables in the November and December 2025 reports describe the following division of work:

| Contributor | Work credited in the reports |
| --- | --- |
| **Jiří Doležal** | Enemy AI, prefabs and attack visualisation; the second report also lists player combat. |
| **Laura Kateřina Dudková** | Team lead; graphics, level design, UI, documentation and audio. |
| **Petr Jan Tomek** | Core game systems, save/load, managers, player movement and shooting, player health and UI. |

The visuals depict a collaborative game. In particular, the artwork and UI are not presented as Jiří's individual artwork. The rows summarise the reports at their publication dates rather than assigning exclusive lifetime ownership of every system.

## Evidence reviewed

This showcase was prepared on **17 November 2026** from the existing project documentation, local C# files and Git history. No new build or full playthrough was performed.

| Area | Supporting record |
| --- | --- |
| Game premise and three-person team | Original root project README and design document. |
| Enemy AI, prefabs and attack visualisation | Report 1, 18 November 2025, contribution table on page 6. |
| Player combat contribution | Report 2, 2 December 2025, contribution table on page 5. |
| Patrol/chase implementation and tuning | `LongArmsSmashAttack2D.cs`, `EnemySenses2D.cs`; authored commits including `4794130`, `d2499ce`, `421aca9` and `6f4e3af`. |
| Boss implementation | `MutatedLumpBoss.cs`, Animator controller and boss state behaviours; authored commits including `55162b4`, `4561e2f`, `6a9714d` and `40b0d29`. |
| Scene lighting and enemy glow | `DynamicSpriteGlow.cs`, prefabs and scene changes; commits including `9732d62`, `d52efb6` and `6b03651`. |
| Input and pause integration | Authored commits including `c29796d`, `4eb3d26` and `5935e68`. |
| Editor and package versions | `ProjectSettings/ProjectVersion.txt` and `Packages/manifest.json` in the inspected Unity project. |

The commit identifiers refer to the original university GitLab history, including its branches. They are recorded for traceability; the history and source files are not republished here. Commit counts are not used as a measure of individual contribution.

## New runtime captures

[Live gameplay gallery](gameplay-gallery.md) adds six screenshots taken on **17 November 2026**: robot and plant, jump, melee attack, pause menu, tutorial and recharge checkpoint. Four frames came from the running standalone game; the tutorial and checkpoint came from Unity Play mode and were cropped to the Game view. These are selected play-test frames, not a complete playthrough. The existing six report images and the separately supplied lead image are retained.

## Screenshot provenance

| Public image | Original source | Interpretation |
| --- | --- | --- |
| [Robot and plant](../assets/gameplay/01-robot-and-plant.png) | Live capture, 17 November 2026 | Standalone game. |
| [Jump](../assets/gameplay/02-jump.png) | Live capture, 17 November 2026 | Standalone game. |
| [Melee attack](../assets/gameplay/05-melee-attack.png) | Live capture, 17 November 2026 | Standalone game. |
| [Live pause menu](../assets/gameplay/03-pause-menu.png) | Live capture, 17 November 2026 | Standalone game. |
| [Live tutorial](../assets/gameplay/04-tutorial.png) | Live capture, 17 November 2026 | Unity Play mode; cropped to the Game view. |
| [Checkpoint](../assets/gameplay/06-checkpoint.png) | Live capture, 17 November 2026 | Unity Play mode; cropped to the Game view. |
| [Gameplay](../assets/gameplay.png) | Screenshot supplied by Jiří Doležal on 17 November 2026 | Robot carrying a plant beneath a flying enemy; published without image modifications. |
| [Tutorial](../assets/tutorial.png) | Report 2, 2 December 2025, page 2 | In-game tutorial development capture. |
| [Main menu](../assets/main-menu.png) | Report 1, 18 November 2025, page 3 | Main menu at that stage. |
| [Pause menu](../assets/pause-menu.png) | Report 1, 18 November 2025, page 3 | Pause menu over the game world. |
| [Enemy settings](../assets/enemy-inspector.png) | Report 1, 18 November 2025, page 2 | Unity Inspector screenshot of charger settings. |
| [Hitboxes](../assets/enemy-hitboxes.png) | Report 2, 2 December 2025, page 2 | Editor/debug view of enemy and player collision/attack geometry. |
| [First room](../assets/first-room-editor.png) | Report 1, 18 November 2025, page 4 | Unity Scene view, including grid and camera outlines. |

The six original images were extracted from the existing PDF reports at their embedded resolution, without generating or retouching gameplay. The additional gameplay image was supplied separately by Jiří Doležal and uploaded unchanged. Later implementation work is described separately from the older images. Full reports, personal contact addresses, game source, third-party packages and binaries are omitted from this presentation.

This repository is a portfolio presentation. It does not grant a licence to reuse the team's artwork or other game materials; rights remain with their respective authors.
