[update-readmes]   Mode: rewrite — migrating to template structure...
# minbian

[![Built with Ona](https://ona.com/build-with-ona.svg)](https://app.ona.com/#https://github.com/Interested-Deving-1896/minbian)

<!-- AI:start:what-it-does -->
_Description pending._
<!-- AI:end:what-it-does -->

## Architecture

<!-- AI:start:architecture -->
_Architecture documentation pending._
<!-- AI:end:architecture -->

## Install

<!-- Add installation instructions here. This section is yours — the AI will not modify it. -->

```bash
git clone https://github.com/Interested-Deving-1896/minbian.git
cd minbian
```

## Usage


After installing the base system, you download the script, run it, answer yes or no (y/n) a couple times and let it work. There's no bloatware, no ricing, nor tracking involved.

- Boot from an USB or ISO image and install the base system
- Select your time zone, language and package management repos
- Uncheck all the desktop environments, keep "system utilities"
- Finish the installation, reboot, and login to your system

### Next Steps

- [ ] Install 'sudo' (if not done yet)

```
apt install sudo
sudo usermod -aG sudo your_name
```

- [ ] Switch user to your username

```
su your_name
```

- [ ] Install Git and download the files

```
sudo apt-get install git
git clone https://github.com/alexmolinaws/minbian.git
```

- [ ] Open the folder and run ./main.sh

```
cd /minbian
sudo ./main.sh
```

- [ ] Answer to select software, for example:

```
Do you need a code editor? (y/n)
```

- [ ] Let it finish, then reboot your PC.

## Configuration

<!-- Document configuration options here. This section is yours — the AI will not modify it. -->

## CI

<!-- AI:start:ci -->
_CI documentation pending._
<!-- AI:end:ci -->

## Mirror chain

<!-- AI:start:mirror-chain -->
This repo is maintained in [`Interested-Deving-1896/minbian`](https://github.com/Interested-Deving-1896/minbian) and mirrored through:

```
Interested-Deving-1896/minbian  ──►  OpenOS-Project-OSP/minbian  ──►  OpenOS-Project-Ecosystem-OOC/minbian
```

Changes flow downstream automatically via the hourly mirror chain in
[`fork-sync-all`](https://github.com/Interested-Deving-1896/fork-sync-all).
Direct commits to OSP or OOC are detected and opened as PRs back to `Interested-Deving-1896`.
<!-- AI:end:mirror-chain -->

## Contributors

<!-- AI:start:contributors -->
_Contributors pending._
<!-- AI:end:contributors -->

## Origins

<!-- AI:start:origins -->
_Original project — no upstream fork._
<!-- AI:end:origins -->

## Resources

<!-- AI:start:resources -->
_No additional resource files found._
<!-- AI:end:resources -->

## License

<!-- AI:start:license -->
[GPL-3.0](https://github.com/Interested-Deving-1896/minbian/blob/main/LICENSE) © 2026 [Interested-Deving-1896](https://github.com/Interested-Deving-1896)
<!-- AI:end:license -->
