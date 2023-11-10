# Rom paths per device

This table shows how roms are sorted per output token. It should enable you to find and output token for your device even if it does not match the output token directly.

## manually added table

| Name | Extensions |  `{batocera}` | `{funkeyos}` | `{jelos}` | `{mister}` | `{onion}` | `{pocket}` | `{twmenu}` |
|------|:------------:|:----:|:---:|:---:|:---:|:---:|:---:|:--:|
| Acorn Atom | - | `atom` | - | - | `AcornAtom` | - | - | - |
| Amstrad CPC | - | `amstradcpc` | - | `amstradcpc` | `Amstrad` | `CPC` | - | `cpc` |
| Amstrad PCW | - | - | - | - | `AmstradPCW` | - | - | - |
| Apple I | - | - | - | - | `Apple-I` | - | - | - |
| Apple II | - | `apple2` | - | - | `Apple-II` | - | - | - |
| Arduboy | `.arduboy` <br> `.hex` | `arduboy` | - | - |`arduboy` | `Arduboy` | - | `arduboy` |

## table added by using GameConsole.getMarkdownTable in scripts/romPathTable.ts

| Name | Extensions | `{pocket}` | `{mister}` | `{onion}` | `{batocera}` | `{jelos}` | `{funkeyos}` | `{twmenu}` |
| :---- | :---: | :----: | :----: | :----: | :----: | :----: | :----: | :----: |
| /Atom/i |  | - | AcornAtom | - | atom | - | - | - |
| /CPC/i |  | - | Amstrad | CPC | amstradcpc | amstradcpc | - | cpc |
| /PCW/i |  | - | AmstradPCW | - | - | - | - | - |
| /Apple.*I/i |  | - | Apple-I | - | - | - | - | - |
| /Apple.*IIe?/i |  | - | Apple-II | - | apple2 | - | - | - |
| /Arduboy/i | `.arduboy` <br /> `.hex` | arduboy | Arduboy | - | arduboy | arduboy | - | - |
| /800|8-bit Family/ | `.atr` <br /> `.atx` | - | ATARI800 | EIGHTHUNDRED | atari800 | atari800 | - | - |
| /2600/ | `.a26` <br /> `.act` <br /> `.pb` <br /> `.tv` <br /> `.tvr` <br /> `.mn` <br /> `.cv` <br /> `.eb` <br /> `.ef` <br /> `.efr` <br /> `.ua` <br /> `.x07` <br /> `.sb` | 2600 | Atari2600 | ATARI | atari2600 | atari2600 | - | a26 |
| /5200/ | `.a52` | - | Atari5200 | FIFTYTWOHUNDRED | atari5200 | atari5200 | - | a52 |
| /7800/ | `.a78` | 7800 | Atari7800 | SEVENTYEIGHTHUNDRED | atari7800 | atari7800 | - | a78 |
| /Jaguar/i | `.j64` | - | - | JAGUAR | jaguar | atarijaguar | - | - |
| /Lynx/i | `.lnx` <br /> `.lyx` | - | AtariLynx | LYNX | lynx | atarilynx | Atari lynx | - |
| /Atari.*ST/i | `.msa` <br /> `.st` <br /> `.stx` | - | AtariST | ATARIST | atarist | atarist | - | - |
| /Astrocade/i |  | - | Astrocade | - | astrocde | - | - | - |
| /Super ?Vision 8000/i |  | - | Supervision8000 | - | - | - | - | - |
| /RX[ -]?78/i |  | - | RX78 | - | - | - | - | - |
| /WonderSwan/i | `.ws` | wonderswan | WonderSwan | WS | wswan | wonderswan | WonderSwan | ws |
| /WonderSwan Color/i | `.wsc` | wonderswan | WonderSwan | WS | wswanc | wonderswancolor | WonderSwan | ws |
| /Gamate/i |  | gamate | Gamate | - | gamate | - | - | - |
| /PV[ -]?1000/i |  | - | Casio_PV-1000 | - | pv1000 | - | - | - |
| /PV[ -]?2000/i |  | - | Casio_PV-2000 | - | - | - | - | - |
| /Amiga/i |  | amiga | Amiga | AMIGA | - | amiga | - | - |
| /Amiga CD32/i |  | - | Amiga | - | amigacd32 | amigacd32 | - | - |
| /Amiga CDTV/i |  | - | - | - | amigacdtv | - | - | - |
| /Commodore C?16/i |  | - | C16 | - | - | c16 | - | - |
| /Commodore C?64/i | `.crt` <br /> `.d64` <br /> `.t64` | - | C64 | COMMODORE | c64 | c64 | - | - |
| /Commodore C?128/i |  | - | C128 | - | c128 | c128 | - | - |
| /ColecoVision/i | `.col` | coleco | Coleco | COLECO | colecovision | coleco | - | col |
| /Arcadia/i |  | arcadia | Arcadia | - | arcadia | - | - | - |
| /Adventure Vision/i |  | avision | AVision | - | advision | - | - | - |
| /Super Cassette Vision/i |  | - | - | - | scv | - | - | - |
| /Channel F/i |  | channel_f | ChannelF | FAIRCHILD | channelf | channelf | - | - |
| /Super A'?Can/i |  | - | - | - | supracan | - | - | - |
| /Vectrex/i | `.vec` | - | Vectrex | VECTREX | vectrex | vectrex | - | - |
| /VC ?4000/i |  | - | VC4000 | - | vc4000 | - | - | - |
| /Odyssey 2/i |  | odyssey2 | Odyssey2 | ODYSSEY | o2em | odyssey | - | - |
| /Intellivision/i | `.int` | intv | Intellivision | INTELLIVISION | intellivision | intellivision | - | - |
| /MSX/i |  | - | MSX | MSX | msx1 | msx | - | - |
| /MSX2/i |  | - | MSX | MSX | msx2 | msx2 | - | - |
| /MSX2+/i |  | - | MSX | MSX | msx2+ | - | - | - |
| /MSX TurboR/i |  | - | MSX | MSX | msxturbor | - | - | - |
| /Xbox/i |  | - | - | - | xbox | xbox | - | - |
| /Xbox 360/i |  | - | - | - | xbox360 | - | - | - |
| /My Vision/i |  | - | MyVision | - | - | - | - | - |
| /PC Engine|TurboGrafx/i | `.pce` | pce | TGFX16 | PCE | pcengine | tg16 | PCE-TurboGrafx | tg16 |
| /(PC Engine|TurboGrafx) CD/i |  | pcecd | TGFX16 | PCECD | pcenginecd | tg16cd | - | - |
| /SuperGrafx/i | `.sgx` | pce | TGFX16 | SGFX | supergrafx | sgfx | - | - |
| /PC-88/i | `.d88` | - | PC8801 | PCEIGHTYEIGHT | pc88 | pc88 | - | - |
| /PC-98/i | `.d98` | - | - | PCNINETYEIGHT | pc98 | pc98 | - | - |
| /FDS|Famicom Computer Disk System/i | `.fds` | nes | NES | FDS | fds | fds | NES | - |
| /Game (and|&) Watch/i | `.mgw` | - | GameNWatch | GW | gameandwatch | gameandwatch | - | - |
| /GameCube/i |  | - | - | - | gamecube | gamecube | - | - |
| /GB|Game ?Boy/i | `.gb` <br /> `.sgb` | gb | Gameboy | GB | gb | gb | Game Boy | gb |
| /GBA|Game ?Boy Advance/i | `.gba` <br /> `.srl` | gba | GBA | GBA | gba | gba | Game Boy Advance | gba |
| /GBC|Game ?Boy Color/i | `.gbc` | gbc | Gameboy | GBC | gbc | gbc | Game Boy Color | gb |
| /Nintendo 64|N64/i | `.n64` <br /> `.v64` <br /> `.z64` | - | N64 | - | n64 | n64 | - | - |
| /Nintendo 64DD|N64DD/i | `.ndd` | - | - | - | n64dd | - | - | - |
| /(\W|^)3DS(\W|$)|Nintendo 3DS/i | `.3ds` | - | - | - | 3ds | 3ds | - | - |
| /(\W|^)NDS(\W|$)|Nintendo DS/i | `.nds` | - | - | - | nds | nds | - | nds |
| /(\W|^)NDSi(\W|$)|Nintendo DSi([Ww]are)?/i |  | - | - | - | - | - | - | dsiware |
| /(\W|^)NES(\W|$)|Nintendo Entertainment System/i | `.nes` <br /> `.nez` | nes | NES | FC | nes | nes | NES | nes |
| /Pokemon Mini/i | `.min` | poke_mini | PokemonMini | POKE | pokemini | pokemini | Pokemini | - |
| /Satellaview/i | `.bs` | snes | SNES | SATELLAVIEW | satellaview | satellaview | - | - |
| /Sufami/i |  | - | - | SUFAMI | sufami | sufami | - | - |
| /(\W|^)SNES(\W|$)|Super Nintendo Entertainment System/i | `.sfc` <br /> `.smc` | snes | SNES | SFC | snes | snes | SNES | snes |
| /Virtual Boy/i | `.vb` <br /> `.vboy` | - | - | VB | virtualboy | virtualboy | Virtualboy | - |
| /Wii/i |  | - | - | - | wii | wii | - | - |
| /Wii ?U/i |  | - | - | - | wiiu | wiiu | - | - |
| /3DO/i |  | - | - | PANASONIC | 3do | 3do | - | - |
| /CD[ -]?i/i |  | - | - | - | cdi | - | - | - |
| /Videopac/i |  | - | Odyssey2 | VIDEOPAC | videopacplus | videopac | - | - |
| /Studio (2|II)/i |  | studio2 | - | - | - | - | - | - |
| /32X/i | `.32x` | - | S32X | THIRTYTWOX | sega32x | sega32x | - | - |
| /Dreamcast/i |  | - | - | - | dreamcast | dreamcast | - | - |
| /Game Gear/i | `.gg` | gg | SMS | GG | gamegear | gamegear | Game Gear | gg |
| /Master System/i | `.sms` | sms | SMS | MS | mastersystem | mastersystem | Sega Master System | sms |
| /(Mega|Sega) CD/i |  | - | MegaCD | SEGACD | segacd | segacd | - | - |
| /Mega Drive|Genesis/i | `.gen` <br /> `.md` <br /> `.mdx` <br /> `.sgd` <br /> `.smd` | genesis | Genesis | MD | megadrive | genesis | Sega Genesis | gen |
| /Saturn/i |  | - | - | - | saturn | saturn | - | - |
| /SG[ -]?1000/i | `.sc` <br /> `.sg` | sg1000 | SG1000 | SEGASGONE | sg1000 | sg-1000 | - | sg |
| /MZ/i |  | - | SharpMZ | - | - | - | - | - |
| /X1/i | `.2d` <br /> `.2hd` <br /> `.dx1` <br /> `.tfd` | - | - | XONE | x1 | x1 | - | - |
| /X68000/i |  | - | X68000 | X68000 | x68000 | x68000 | - | - |
| /ZX[ -]?80/i |  | - | ZX81 | - | - | - | - | - |
| /ZX[ -]?81/i |  | - | ZX81 | - | zx81 | zx81 | - | - |
| /ZX[ -]?Spectrum/i | `.scl` <br /> `.szx` <br /> `.z80` | - | Spectrum | ZXS | zxspectrum | zxspectrum | - | - |
| /Neo ?Geo/i |  | ng | NeoGeo | NEOGEO | neogeo | neogeo | - | - |
| /Neo ?Geo CD/i |  | - | - | NEOCD | neogeocd | neocd | - | - |
| /Neo ?Geo Pocket/i | `.ngp` | - | - | NGP | ngp | ngp | Neo Geo Pocket | ngp |
| /Neo ?Geo Pocket Color/i | `.ngc` | - | - | NGP | ngpc | ngpc | Neo Geo Pocket | ngp |
| /PlayStation|psx/i |  | - | PSX | PS | psx | psx | PS1 | - |
| /PlayStation 2|ps2/i |  | - | - | - | ps2 | ps2 | - | - |
| /PlayStation 3|ps3/i |  | - | - | - | ps3 | ps3 | - | - |
| /PlayStation [4-9]|ps[4-9]/i |  | - | - | - | - | - | - | - |
| /Sord[ -]M(5|five)/i |  | - | - | - | - | - | - | m5 |
| /GameKing/i |  | game_king | - | - | - | - | - | - |
| /CreatiVision/i |  | creativision | CreatiVision | - | crvision | - | - | - |
| /V\.Smile/i |  | - | - | - | vsmile | - | - | - |
| /Supervision/i | `.sv` | supervision | SuperVision | SUPERVISION | supervision | supervision | - | - |
| /Mega Duck/i | `.md1` <br /> `.md2` | mega_duck | - | MEGADUCK | megaduck | megaduck | - | - |