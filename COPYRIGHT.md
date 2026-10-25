# Open-Box copyright and licensing scope

Open-Box's own programs are distributed as closed-source proprietary software under [LICENSE](LICENSE). The public repository provides official releases, deployment scripts, documentation and issue reporting; being publicly downloadable does not grant an open-source licence to Open-Box's own implementation.

Without permission, you may not copy or distribute Open-Box's own code, redistribute or sell its programs, make renamed or repackaged derivative products, decompile, disassemble or reverse-engineer its implementation, or bypass licensing. Users may install, use offline, upgrade, back up and restore it on their own devices; rights that applicable law does not allow to be excluded are not limited.

## Third-party components and existing licences

- The panel front end is developed by Wan Family on top of zashboard. zashboard's original code keeps its MIT licence; the original copyright notice and full licence text ship as `panel/server/resources/licenses/panel.LICENSE`. Open-Box's terms do not limit rights already granted under MIT.
- The sing-box kernel keeps its GPL licence and ships with `bin/sing-box.LICENSE`; every official release also provides the matching kernel source, patches and build materials as attachments. Rights to use, modify, copy and redistribute the kernel follow its original licence.
- Other third-party components, including Node.js, the Go runtime, Go modules, panel dependencies, rule databases and the Docker base image, are licensed under their own licences. Their original licences and copyright notices are kept with each component.
- `panel/server/resources/licenses/open-box.LICENSE` and `open-box.COPYRIGHT.md` are copies of the licence and of this notice for Open-Box's own programs; component upgrades keep these files.

This notice ships with releases from v0.1.321 onward. It covers only the parts the Open-Box rights holder is entitled to license; it does not make third-party components closed source and does not retroactively revoke any licence already granted for earlier versions or other material. Copyright questions about earlier versions should be settled by checking the origin of the files concerned, the licence they were released under and what was actually copied.

## Official source

Open-Box is a Wan Family project. The official source repository is `wan-family-office/open-box` (not public). Official releases, deployment scripts and documentation are published in the public repository [wan-family-office/open-box-releases](https://github.com/wan-family-office/open-box-releases). Reposting the documentation or using the public scripts does not grant any licence to Open-Box's source code, brand or derivative releases.
