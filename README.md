# HDest Voxels

[![Nightly Build](https://github.com/HDest-Community/HDest-Voxels/actions/workflows/nightly.yml/badge.svg)](https://github.com/HDest-Community/HDest-Voxels/actions/workflows/nightly.yml)

Voxels, for your hideous destruction.

### Note

Due to the way GZDoom loads Voxels/Models, the original sprite lumps need to be loaded in order for the voxels to replace them.  Because of this, simply downloading the repo as a ZIP will then require each addon to be loaded.  This can be circumvented by deleting the `VOXELDEF` or `MODELDEF` for the addons you choose not to run with (for example, If not running Peppergrinder, remove the `MODELDEF.peppergrinder` file from the root of the ZIP/repo to prevent GZDoom from attempting to load those voxels).

However, There is a nightly build of this project that already splits out the various voxels/models for Vanilla Doom/HDest, Peppergrinder, Radtech, and other future addon voxels into separate PK3s, as well as providing a "Full" PK3 for those that have all of the included addons and don't want to load multiple files.  You can grab the latest nightly build below:

[Latest Nightly Build](https://nightly.link/HDest-Community/HDest-Voxels/workflows/nightly/main/Artifacts.zip)

## Credits

### Vanilla Doom Voxels

_Originally made by Cheello_

All Vanilla id Doom voxels were taken from Cheello's Voxel Doom mod.

Original Voxel Doom Readme Credits:

```
Cheello's Voxel Doom
© 2021 - 2023 Daniel Peterson

All voxel models and base VOXELDEF by Cheello
ZScript code by Nash Muhandes (MIT licensed)

Special thanks:

Nash Muhandes for consultation, beta testing, and coding help
Agustin Alvarez for various feature ideas, beta testing and additional support

MODDERS:

You may use my voxels in your own projects, as long as you give me, "Cheello" credit.
```


### HDest Pickups

_Originally made by Mickromash_

Original HDest Voxels Readme:

```
DERP, Brontornis, slayer and smg voxel models by popguy12

arm1, armc, cell, clp2, clp3, playe, stim, pist, hunt, laun, vulc, zmag, bpak, medi, srg2, 7box, 9box, 3box, prif, pmap by Cheello, edited by mickromash

everything else by Mickromash.
```


### Peppergrinder Pickups

_Originally made by Hara_

Voxel assets originally made by Hara with edits made by CannibalHunter and minor fixes made by prettyFist.

Greely & Box Cannon Voxels updated by Thomased22
Aurochs & Browning Auto5 Voxels updated by a1337spy

Original Peppergrinder Voxels Readme:

```
version: 0.8	all peppergrinder pickup sprites should be replaced. A few models
		I'm not happy with and might change.
version: 0.9	Helzing magnum w. bottle added
version: 0.9.1	<<CannibalHunter type things pls>>
version: 0.9.2	Box Cannon holstered sprite replaced with preexisting model & minor fixes -pF

Replaces all pickup sprites for weapons and associated magazines in
the Peppergrinder addon with voxel editions.

Format & incompatibilities fixed by CannibalHunter (yo cannibal, pls fill this out better than i can lmao)
Minor fixes by prettyFist
```

### Radtech Items & Weapons Pickups

_Originally made by Swampyrad_

Note, the requirement to have Cheello's Voxel Doom is no longer needed, as those voxel assets are included in this pack due to the above permission.

Original Radtech Voxels Readme:

```
RadTechVoxelPack
A voxel plug-in for RadTech Weapons Pack

Adds voxel models for weapon and items
from the RadTech Weapons and Item Packs.

Requires Cheello's Voxel Doom mod, since the
Doomed Shotgun and DM-97 Plasma Rifle need it to work.
```