# Lilacin

[**L**](lilacin)ilacin [**i**](lilacin)nstalls [**L**](lilacin)arbs [**a**](lilacin)fter [**c**](lilacin)ustomizing [**i**](lilacin)t [**n**](lilacin)icely.

Lilacin is an efficient shell script that automatically configures a fully functioning [Arch Linux](//archlinux.org/) environment emphasizing minimalist aesthetics.

By default, Lilacin customizes and installs [**L**ukeSmithxyz](//lukesmith.xyz)'s **A**uto-**R**ice **B**ootstrapping **S**cripts ([Larbs](//github.com/LukeSmithxyz/LARBS)) that deploys [Voidrice](//github.com/LukeSmithxyz/voidrice) and [dwm](//github.com/LukeSmithxyz/dwm).

### Usage

On an Arch-based distribution as root, run the following:

```
curl https://raw.githubusercontent.com/lilacin/lilacin/lilacin/lilacin | sh
```

Alternatively, customize it for your own needs:

```
curl -O https://raw.githubusercontent.com/lilacin/lilacin/lilacin/lilacin
vim lilacin
sh lilacin
```

### FAQ

#### How does Lilacin work?

1. Lilacin downloads the original [`larbs.sh`](//github.com/LukeSmithxyz/LARBS/blob/master/larbs.sh) and [`progs.csv`](//github.com/LukeSmithxyz/LARBS/blob/master/progs.csv) from LukeSmithxyz's GitHub repositories.

2. Lilacin [customizes](//github.com/LukeSmithxyz/LARBS#customization) `larbs.sh` and `progs.csv` with [`sed`](//www.gnu.org/software/sed/).

3. Lilacin installs Larbs by giving `larbs.sh` the option `-p` with `progs.csv`.

#### How to install Arch Linux? (The Arch Way)

- [ArchWiki](//wiki.archlinux.org/index.php/Installation_guide)

#### How to install Arch Linux? (the quick way)

- [arcolinux/alci-iso-pure](//alci.online/downloads)
- [archlinux/archinstall](//github.com/archlinux/archinstall)
- [MatMoul/archfi](//github.com/MatMoul/archfi)
- [helmuthdu/aui](//github.com/helmuthdu/aui)
