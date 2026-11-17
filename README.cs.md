# The Last Human

**Akční 2D plošinovka v Unity: robot přenáší rostlinu nakaženým světem do laboratoře.**

[Obrazový průchod](docs/demo.md) · [Můj podíl a tým](docs/credits-and-evidence.md) · [English](README.md) · [Všechny projekty](https://github.com/Dolik64)

![Robot s rostlinou pod létajícím nepřítelem ve hře The Last Human](assets/gameplay.png)

*Screenshot ze hry dodaný Jiřím Doležalem, přidaný 17. listopadu 2026.*

## O hře

The Last Human vznikl ve tříčlenném týmu v předmětu **HRY na FEL ČVUT**. Robot se snaží dopravit rostlinu do laboratoře a pomoci vyléčit nakažený svět. Hra propojuje souboje, překonávání překážek, odemykání schopností a průchod navazujícími místnostmi.

Prohlédnutý Unity projekt obsahuje více typů nepřátel, vícefázového bosse, checkpointy, ukládání stavu, přechody mezi scénami a menu.

## Můj podíl

Jsem **Jiří Doležal** a zaměřoval jsem se především na chování nepřátel a soubojové mechanismy. Týmové reporty mi výslovně připisují **AI nepřátel, prefaby, vizualizaci útoků a souboje hráče**. V historii commitů je doložená také práce na:

- hlídkování a pronásledování, detekci hráče a hran plošin, časování útoků a hitboxech;
- chování bosse, stavech Animatoru, změnách fází podle zdraví a střelbě projektilů;
- vizualizaci zásahů, ladění odhození, kolizí a napojení zdraví nepřátel;
- osazování úrovní, 2D osvětlení a svícení podle aktuálního spritu nepřítele;
- propojení s Input Systemem, opravách ovládání gamepadem a obsluze pauzy.

Jde o můj příspěvek do týmové hry. Grafiku, návrh úrovní a další systémy vytvářeli také spoluautoři; rozdělení práce uvádí [kredity a přehled podkladů](docs/credits-and-evidence.md).

## Nové screenshoty přímo ze hry

Šest snímků pořízených **17. listopadu 2026** ze spuštěné hry a režimu Play v Unity. U tutoriálu a checkpointu je oříznuté rozhraní editoru; ostatní čtyři zachovávají celý zachycený snímek. Herní scény nejsou generované ani retušované.

| Robot & plant | Jump |
| --- | --- |
| ![Robot carrying the plant in a lit cavern](assets/gameplay/01-robot-and-plant.png) | ![Robot jumping above the cavern floor](assets/gameplay/02-jump.png) |

| Melee attack | Pause menu |
| --- | --- |
| ![Turquoise melee attack effect](assets/gameplay/05-melee-attack.png) | ![Pause menu over the live game](assets/gameplay/03-pause-menu.png) |

| Tutorial | Recharge checkpoint |
| --- | --- |
| ![Robot on a platform in TutorialScene](assets/gameplay/04-tutorial.png) | ![Robot at the recharge checkpoint in Level_1_Scene](assets/gameplay/06-checkpoint.png) |

[Všech šest snímků v plné velikosti](docs/gameplay-gallery.md).

## Galerie

| Hlavní menu | Pauza ve hře |
| --- | --- |
| ![Hlavní menu The Last Human](assets/main-menu.png) | ![Menu pauzy nad herním prostředím](assets/pause-menu.png) |

| Nastavení útoku nepřítele | Ladění hitboxů |
| --- | --- |
| ![Parametry nepřítele v Unity Inspectoru](assets/enemy-inspector.png) | ![Nepřítel a hráč s viditelnými kolizními a útočnými oblastmi](assets/enemy-hitboxes.png) |

Záběry v galerii výše pocházejí z týmových reportů z **listopadu a prosince 2025**. Zachycují tehdejší rozpracovanou verzi a editorové nástroje. Nejde o nové ověření finálního vydání.

## Technologie

**C# · Unity 6 · Physics2D · stavové automaty Animatoru · URP 2D · Unity Input System · Cinemachine · Timeline · Git / Git LFS**

Prohlédnutý projekt používá editor **6000.2.6f2**. Další obrázek úrovně a vysvětlení soubojových systémů obsahuje [obrazový průchod](docs/demo.md).

Repozitář obsahuje dokumentaci, dodaný úvodní screenshot, šest nových snímků z běžící hry a šest starších vývojových záběrů. Zdrojový Unity projekt ani spustitelný build zde nejsou; týmový projekt zůstává v původním univerzitním GitLabu.
