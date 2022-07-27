### [haskell-updates build report from hydra](https://hydra.nixos.org/jobset/nixpkgs/haskell-updates)
*evaluation [1773138](https://hydra.nixos.org/eval/1773138) of nixpkgs commit [c419834](https://github.com/NixOS/nixpkgs/commits/c419834223814af5ec545d08d5b29cded259c184) as of 2022-07-27 01:11 UTC*

:red_circle: **Branch not mergeable**
  * Too many outstanding jobs on aarch64-linux.
  * `mergeable` jobset is not finished.
  * `maintained` jobset is not finished.

#### Build summary

 | Platform | Failed :x: | DependencyFailed :heavy_exclamation_mark: | TimedOut :hourglass::no_entry_sign: | Unfinished :hourglass_flowing_sand: | Success :heavy_check_mark: | 
 | --- | --- | --- | --- | --- | --- | 
 | [aarch64-linux :iphone:](https://hydra.nixos.org/eval/1773138?filter=.aarch64-linux) | 22 | 21 |  | 1831 | 4547 | 
 | [x86_64-darwin :apple:](https://hydra.nixos.org/eval/1773138?filter=.x86_64-darwin) | 48 | 22 |  | 1065 | 5217 | 
 | [x86_64-linux :penguin:](https://hydra.nixos.org/eval/1773138?filter=.x86_64-linux) | 8 | 5 | 3 | 12 | 6392 | 
#### Maintained packages with failed dependency
- [ ] [git-annex](https://hydra.nixos.org/eval/1773138?filter=git-annex) @peti @roosemberth
  - [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/185249171) [[:apple::heavy_exclamation_mark:]](https://hydra.nixos.org/build/185249421) [[:penguin::heavy_exclamation_mark:]](https://hydra.nixos.org/build/185247565) [toplevel](https://hydra.nixos.org/eval/1773138?filter=git-annex)
  - [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/185251740) [[:apple::heavy_exclamation_mark:]](https://hydra.nixos.org/build/185257907) [[:penguin::heavy_exclamation_mark:]](https://hydra.nixos.org/build/185256728) [haskellPackages](https://hydra.nixos.org/eval/1773138?filter=haskellPackages.git-annex)
#### Unmaintained packages with build failure
<details><summary>66 job(s) </summary>

- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/185258173) [[:apple::x:]](https://hydra.nixos.org/build/185250400) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/185250533) [haskellPackages.di-core](https://hydra.nixos.org/eval/1773138?filter=haskellPackages.di-core)  :arrow_heading_up: 8 | 11
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/185247164) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/185253077) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/185248355) [haskellPackages.OrderedBits](https://hydra.nixos.org/eval/1773138?filter=haskellPackages.OrderedBits)  :arrow_heading_up: 5 | 36
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/185253497) [[:apple::x:]](https://hydra.nixos.org/build/185254042) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/185247890) [haskellPackages.zip](https://hydra.nixos.org/eval/1773138?filter=haskellPackages.zip)  :arrow_heading_up: 5 | 11
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/185258747) [[:apple::x:]](https://hydra.nixos.org/build/185248709) [[:penguin::x:]](https://hydra.nixos.org/build/185248640) [haskellPackages.uniform-error](https://hydra.nixos.org/eval/1773138?filter=haskellPackages.uniform-error)  :arrow_heading_up: 3 | 3
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/185249938) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/185256330) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/185257304) [haskellPackages.quic](https://hydra.nixos.org/eval/1773138?filter=haskellPackages.quic)  :arrow_heading_up: 2 | 2
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/184535218) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/184521799) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/184536111) [haskellPackages.freetype2](https://hydra.nixos.org/eval/1773138?filter=haskellPackages.freetype2)  :arrow_heading_up: 1 | 8
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/184520983) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/184526911) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/184534592) [haskellPackages.long-double](https://hydra.nixos.org/eval/1773138?filter=haskellPackages.long-double)  :arrow_heading_up: 1 | 2
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/184535658) [[:apple::x:]](https://hydra.nixos.org/build/184524859) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/184518152) [haskellPackages.easytensor](https://hydra.nixos.org/eval/1773138?filter=haskellPackages.easytensor)  :arrow_heading_up: 1 | 1
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/184527064) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/184520065) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/184535245) [haskellPackages.nlopt-haskell](https://hydra.nixos.org/eval/1773138?filter=haskellPackages.nlopt-haskell)  :arrow_heading_up: 1 | 1
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/185253911) [[:apple::x:]](https://hydra.nixos.org/build/185253623) [[:penguin::x:]](https://hydra.nixos.org/build/185257052) [haskellPackages.postgresql-ltree](https://hydra.nixos.org/eval/1773138?filter=haskellPackages.postgresql-ltree)  :arrow_heading_up: 1 | 1
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/185255285) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/185252895) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/185251609) [haskellPackages.swisstable](https://hydra.nixos.org/eval/1773138?filter=haskellPackages.swisstable)  :arrow_heading_up: 1 | 1
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/184530498) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/184529627) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/184517810) [haskellPackages.unicode-properties](https://hydra.nixos.org/eval/1773138?filter=haskellPackages.unicode-properties)  :arrow_heading_up: 1 | 1
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/185247308) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/185254887) [[:penguin::x:]](https://hydra.nixos.org/build/185248337) [haskellPackages.validity-network-uri](https://hydra.nixos.org/eval/1773138?filter=haskellPackages.validity-network-uri)  :arrow_heading_up: 1 | 1
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/185249309) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/185257560) [[:penguin::x:]](https://hydra.nixos.org/build/185253272) [haskellPackages.aws](https://hydra.nixos.org/eval/1773138?filter=haskellPackages.aws)  :arrow_heading_up: 0 | 20
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/184526463) [[:apple::x:]](https://hydra.nixos.org/build/184527023) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/184536697) [haskellPackages.hmidi](https://hydra.nixos.org/eval/1773138?filter=haskellPackages.hmidi)  :arrow_heading_up: 0 | 4
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/185248212) [[:apple::x:]](https://hydra.nixos.org/build/185251486) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/185253870) [haskellPackages.posix-socket](https://hydra.nixos.org/eval/1773138?filter=haskellPackages.posix-socket)  :arrow_heading_up: 0 | 2
- [ ] [[:iphone::hourglass_flowing_sand:]](https://hydra.nixos.org/build/185258627) [[:apple::x:]](https://hydra.nixos.org/build/185253095) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/185247696) [haskellPackages.gi-gdkx11](https://hydra.nixos.org/eval/1773138?filter=haskellPackages.gi-gdkx11)  :arrow_heading_up: 0 | 1
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/184533916) [[:apple::x:]](https://hydra.nixos.org/build/184523994) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/184534723) [haskellPackages.hamid](https://hydra.nixos.org/eval/1773138?filter=haskellPackages.hamid)  :arrow_heading_up: 0 | 1
- [ ] [[:iphone::hourglass_flowing_sand:]](https://hydra.nixos.org/build/185255639) [[:apple::x:]](https://hydra.nixos.org/build/185249030) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/185256791) [haskellPackages.hmatrix-morpheus](https://hydra.nixos.org/eval/1773138?filter=haskellPackages.hmatrix-morpheus)  :arrow_heading_up: 0 | 1
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/184523006) [[:apple::x:]](https://hydra.nixos.org/build/184528416) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/184535495) [haskellPackages.huckleberry](https://hydra.nixos.org/eval/1773138?filter=haskellPackages.huckleberry)  :arrow_heading_up: 0 | 1
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/184522410) [[:apple::x:]](https://hydra.nixos.org/build/184522125) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/184531242) [haskellPackages.openal-ffi](https://hydra.nixos.org/eval/1773138?filter=haskellPackages.openal-ffi)  :arrow_heading_up: 0 | 1
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/184521292) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/184524400) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/184525263) [haskellPackages.picosat](https://hydra.nixos.org/eval/1773138?filter=haskellPackages.picosat)  :arrow_heading_up: 0 | 1
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/184526493) [[:apple::x:]](https://hydra.nixos.org/build/184519127) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/184528507) [haskellPackages.select](https://hydra.nixos.org/eval/1773138?filter=haskellPackages.select)  :arrow_heading_up: 0 | 1
- [ ] [[:iphone::hourglass_flowing_sand:]](https://hydra.nixos.org/build/185258291) [[:apple::x:]](https://hydra.nixos.org/build/185251696) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/185248711) [haskellPackages.sysinfo](https://hydra.nixos.org/eval/1773138?filter=haskellPackages.sysinfo)  :arrow_heading_up: 0 | 1
- [ ] [[:iphone::hourglass_flowing_sand:]](https://hydra.nixos.org/build/185256097) [[:apple::x:]](https://hydra.nixos.org/build/185248859) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/185255230) [haskellPackages.FractalArt](https://hydra.nixos.org/eval/1773138?filter=haskellPackages.FractalArt) 
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/184525037) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/184528211) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/184521784) [haskellPackages.HsASA](https://hydra.nixos.org/eval/1773138?filter=haskellPackages.HsASA) 
- [ ] [[:iphone::hourglass_flowing_sand:]](https://hydra.nixos.org/build/185254508) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/185257631) [[:penguin::x:]](https://hydra.nixos.org/build/185258425) [haskellPackages.cabal-hoogle](https://hydra.nixos.org/eval/1773138?filter=haskellPackages.cabal-hoogle) 
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/185249468) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/185256432) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/185258932) [haskellPackages.comfort-fftw](https://hydra.nixos.org/eval/1773138?filter=haskellPackages.comfort-fftw) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/184519552) [[:apple::x:]](https://hydra.nixos.org/build/184534865) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/184534271) [haskellPackages.diskhash](https://hydra.nixos.org/eval/1773138?filter=haskellPackages.diskhash) 
- [ ] [[:iphone::hourglass_flowing_sand:]](https://hydra.nixos.org/build/185252897) [[:apple::x:]](https://hydra.nixos.org/build/185248421) [[:penguin::x:]](https://hydra.nixos.org/build/185250292) [haskellPackages.ecta](https://hydra.nixos.org/eval/1773138?filter=haskellPackages.ecta) 
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/185251104) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/185257452) [[:penguin::x:]](https://hydra.nixos.org/build/185257335) [haskellPackages.embed-config](https://hydra.nixos.org/eval/1773138?filter=haskellPackages.embed-config) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/184529758) [[:apple::x:]](https://hydra.nixos.org/build/184534759) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/184535503) [haskellPackages.fudgets](https://hydra.nixos.org/eval/1773138?filter=haskellPackages.fudgets) 
- [ ] [[:iphone::hourglass_flowing_sand:]](https://hydra.nixos.org/build/185258698) [[:apple::x:]](https://hydra.nixos.org/build/185252082) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/185252742) [haskellPackages.gerrit](https://hydra.nixos.org/eval/1773138?filter=haskellPackages.gerrit) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/184524077) [[:apple::x:]](https://hydra.nixos.org/build/184525167) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/184527915) [haskellPackages.ghc-gc-hook](https://hydra.nixos.org/eval/1773138?filter=haskellPackages.ghc-gc-hook) 
- [ ] [[:apple::x:]](https://hydra.nixos.org/build/185249960) [haskellPackages.gi-gtkosxapplication](https://hydra.nixos.org/eval/1773138?filter=haskellPackages.gi-gtkosxapplication) 
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/185244223) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/185244220) [haskellPackages.gnome-keyring](https://hydra.nixos.org/eval/1773138?filter=haskellPackages.gnome-keyring) 
- [ ] [[:apple::x:]](https://hydra.nixos.org/build/184527085) [haskellPackages.gtk-mac-integration](https://hydra.nixos.org/eval/1773138?filter=haskellPackages.gtk-mac-integration) 
- [ ] [[:iphone::hourglass_flowing_sand:]](https://hydra.nixos.org/build/185258692) [[:apple::x:]](https://hydra.nixos.org/build/184529366) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/185247492) [haskellPackages.gtk-traymanager](https://hydra.nixos.org/eval/1773138?filter=haskellPackages.gtk-traymanager) 
- [ ] [[:apple::x:]](https://hydra.nixos.org/build/184523845) [haskellPackages.gtk3-mac-integration](https://hydra.nixos.org/eval/1773138?filter=haskellPackages.gtk3-mac-integration) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/184523214) [[:apple::x:]](https://hydra.nixos.org/build/184522521) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/184520671) [haskellPackages.hid](https://hydra.nixos.org/eval/1773138?filter=haskellPackages.hid) 
- [ ] [[:iphone::hourglass_flowing_sand:]](https://hydra.nixos.org/build/185256090) [[:apple::x:]](https://hydra.nixos.org/build/185248769) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/185250348) [haskellPackages.highlight](https://hydra.nixos.org/eval/1773138?filter=haskellPackages.highlight) 
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/185247424) [[:apple::x:]](https://hydra.nixos.org/build/185249142) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/185258886) [haskellPackages.hinotify-conduit](https://hydra.nixos.org/eval/1773138?filter=haskellPackages.hinotify-conduit) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/184535586) [[:apple::x:]](https://hydra.nixos.org/build/184525054) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/184530645) [haskellPackages.hsshellscript](https://hydra.nixos.org/eval/1773138?filter=haskellPackages.hsshellscript) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/184520050) [[:apple::x:]](https://hydra.nixos.org/build/184528939) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/184532014) [haskellPackages.hssourceinfo](https://hydra.nixos.org/eval/1773138?filter=haskellPackages.hssourceinfo) 
- [ ] [[:iphone::hourglass_flowing_sand:]](https://hydra.nixos.org/build/185254822) [[:apple::x:]](https://hydra.nixos.org/build/185251205) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/185256303) [haskellPackages.ipcvar](https://hydra.nixos.org/eval/1773138?filter=haskellPackages.ipcvar) 
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/185249385) [[:apple::x:]](https://hydra.nixos.org/build/185247643) [[:penguin::x:]](https://hydra.nixos.org/build/185250833) [haskellPackages.konnakol](https://hydra.nixos.org/eval/1773138?filter=haskellPackages.konnakol) 
- [ ] [[:apple::x:]](https://hydra.nixos.org/build/184528755) [haskellPackages.kqueue](https://hydra.nixos.org/eval/1773138?filter=haskellPackages.kqueue) 
- [ ] [[:iphone::hourglass_flowing_sand:]](https://hydra.nixos.org/build/185257833) [[:apple::x:]](https://hydra.nixos.org/build/185248425) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/185254240) [haskellPackages.leveldb-haskell-fork](https://hydra.nixos.org/eval/1773138?filter=haskellPackages.leveldb-haskell-fork) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/184525385) [[:apple::x:]](https://hydra.nixos.org/build/184529277) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/184536532) [haskellPackages.linux-framebuffer](https://hydra.nixos.org/eval/1773138?filter=haskellPackages.linux-framebuffer) 
- [ ] [[:iphone::hourglass_flowing_sand:]](https://hydra.nixos.org/build/185256202) [[:apple::x:]](https://hydra.nixos.org/build/185251800) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/185256217) [haskellPackages.mediawiki2latex](https://hydra.nixos.org/eval/1773138?filter=haskellPackages.mediawiki2latex) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/184530854) [[:apple::x:]](https://hydra.nixos.org/build/184531427) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/184518055) [haskellPackages.memfd](https://hydra.nixos.org/eval/1773138?filter=haskellPackages.memfd) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/184524879) [[:apple::x:]](https://hydra.nixos.org/build/184526652) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/184526003) [haskellPackages.mercury-api](https://hydra.nixos.org/eval/1773138?filter=haskellPackages.mercury-api) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/184518065) [[:apple::x:]](https://hydra.nixos.org/build/184526984) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/184518350) [haskellPackages.nano-cryptr](https://hydra.nixos.org/eval/1773138?filter=haskellPackages.nano-cryptr) 
- [ ] [[:iphone::hourglass_flowing_sand:]](https://hydra.nixos.org/build/185256388) [[:apple::x:]](https://hydra.nixos.org/build/185253357) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/185254037) [haskellPackages.phatsort](https://hydra.nixos.org/eval/1773138?filter=haskellPackages.phatsort) 
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/184522922) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/184532702) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/184530166) [haskellPackages.risc386](https://hydra.nixos.org/eval/1773138?filter=haskellPackages.risc386) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/184527238) [[:apple::x:]](https://hydra.nixos.org/build/184534038) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/184524225) [haskellPackages.sfml-audio](https://hydra.nixos.org/eval/1773138?filter=haskellPackages.sfml-audio) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/184525803) [[:apple::x:]](https://hydra.nixos.org/build/184521262) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/184527151) [haskellPackages.shared-memory](https://hydra.nixos.org/eval/1773138?filter=haskellPackages.shared-memory) 
- [ ] [[:iphone::hourglass_flowing_sand:]](https://hydra.nixos.org/build/185258904) [[:apple::x:]](https://hydra.nixos.org/build/185250080) [[:penguin::hourglass::no_entry_sign:]](https://hydra.nixos.org/build/185248897) [haskellPackages.skews](https://hydra.nixos.org/eval/1773138?filter=haskellPackages.skews) 
- [ ] [[:iphone::hourglass_flowing_sand:]](https://hydra.nixos.org/build/185252598) [[:apple::x:]](https://hydra.nixos.org/build/185249516) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/185252965) [haskellPackages.slugify](https://hydra.nixos.org/eval/1773138?filter=haskellPackages.slugify) 
- [ ] [[:iphone::hourglass_flowing_sand:]](https://hydra.nixos.org/build/185253379) [[:apple::x:]](https://hydra.nixos.org/build/185248288) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/185250594) [haskellPackages.tailfile-hinotify](https://hydra.nixos.org/eval/1773138?filter=haskellPackages.tailfile-hinotify) 
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/184531197) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/184534864) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/184526408) [haskellPackages.wiringPi](https://hydra.nixos.org/eval/1773138?filter=haskellPackages.wiringPi) 
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/184527192) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/184531680) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/184523416) [haskellPackages.x86-64bit](https://hydra.nixos.org/eval/1773138?filter=haskellPackages.x86-64bit) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/184531459) [[:apple::x:]](https://hydra.nixos.org/build/184532712) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/184517882) [haskellPackages.xmonad-utils](https://hydra.nixos.org/eval/1773138?filter=haskellPackages.xmonad-utils) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/184522751) [[:apple::x:]](https://hydra.nixos.org/build/184527292) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/184533651) [haskellPackages.yoga](https://hydra.nixos.org/eval/1773138?filter=haskellPackages.yoga) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/184530633) [[:apple::x:]](https://hydra.nixos.org/build/184536369) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/184530896) [haskellPackages.zot](https://hydra.nixos.org/eval/1773138?filter=haskellPackages.zot) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/184525620) [[:apple::x:]](https://hydra.nixos.org/build/184525778) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/184536251) [haskellPackages.zxcvbn-c](https://hydra.nixos.org/eval/1773138?filter=haskellPackages.zxcvbn-c) 
</details>

#### Unmaintained packages with failed dependency
<details><summary>36 job(s) </summary>

- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/185255290) [[:apple::heavy_exclamation_mark:]](https://hydra.nixos.org/build/185254862) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/185257743) [haskellPackages.di-handle](https://hydra.nixos.org/eval/1773138?filter=haskellPackages.di-handle)  :arrow_heading_up: 6 | 9
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/185250544) [[:apple::heavy_exclamation_mark:]](https://hydra.nixos.org/build/185257630) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/185249253) [haskellPackages.di-monad](https://hydra.nixos.org/eval/1773138?filter=haskellPackages.di-monad)  :arrow_heading_up: 6 | 9
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/185250601) [[:apple::heavy_exclamation_mark:]](https://hydra.nixos.org/build/185257081) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/185256283) [haskellPackages.di-df1](https://hydra.nixos.org/eval/1773138?filter=haskellPackages.di-df1)  :arrow_heading_up: 5 | 8
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/185255163) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/185247089) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/185250537) [haskellPackages.PrimitiveArray](https://hydra.nixos.org/eval/1773138?filter=haskellPackages.PrimitiveArray)  :arrow_heading_up: 4 | 35
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/185248885) [[:apple::heavy_exclamation_mark:]](https://hydra.nixos.org/build/185253645) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/185247788) [haskellPackages.xlsx](https://hydra.nixos.org/eval/1773138?filter=haskellPackages.xlsx)  :arrow_heading_up: 4 | 6
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/185250135) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/185255265) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/185256110) [haskellPackages.BiobaseTypes](https://hydra.nixos.org/eval/1773138?filter=haskellPackages.BiobaseTypes)  :arrow_heading_up: 3 | 21
- [ ] [[:iphone::hourglass_flowing_sand:]](https://hydra.nixos.org/build/185258555) [[:apple::heavy_exclamation_mark:]](https://hydra.nixos.org/build/185252143) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/185256006) [haskellPackages.cointracking-imports](https://hydra.nixos.org/eval/1773138?filter=haskellPackages.cointracking-imports)  :arrow_heading_up: 2 | 2
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/185254115) [[:apple::heavy_exclamation_mark:]](https://hydra.nixos.org/build/185249027) [[:penguin::heavy_exclamation_mark:]](https://hydra.nixos.org/build/185249781) [haskellPackages.uniform-time](https://hydra.nixos.org/eval/1773138?filter=haskellPackages.uniform-time)  :arrow_heading_up: 2 | 2
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/185252869) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/185251576) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/185257567) [haskellPackages.BiobaseENA](https://hydra.nixos.org/eval/1773138?filter=haskellPackages.BiobaseENA)  :arrow_heading_up: 1 | 18
- [ ] [[:iphone::hourglass_flowing_sand:]](https://hydra.nixos.org/build/185255561) [[:apple::heavy_exclamation_mark:]](https://hydra.nixos.org/build/185251234) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/185256390) [haskellPackages.di-polysemy](https://hydra.nixos.org/eval/1773138?filter=haskellPackages.di-polysemy)  :arrow_heading_up: 1 | 4
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/185255614) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/185251482) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/185252107) [haskellPackages.http3](https://hydra.nixos.org/eval/1773138?filter=haskellPackages.http3)  :arrow_heading_up: 1 | 1
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/185252484) [[:apple::heavy_exclamation_mark:]](https://hydra.nixos.org/build/185257201) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/185254417) [haskellPackages.moto](https://hydra.nixos.org/eval/1773138?filter=haskellPackages.moto)  :arrow_heading_up: 1 | 1
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/185249295) [[:apple::heavy_exclamation_mark:]](https://hydra.nixos.org/build/185258098) [[:penguin::heavy_exclamation_mark:]](https://hydra.nixos.org/build/185254716) [haskellPackages.uniform-fileio](https://hydra.nixos.org/eval/1773138?filter=haskellPackages.uniform-fileio)  :arrow_heading_up: 1 | 1
- [ ] [[:iphone::hourglass_flowing_sand:]](https://hydra.nixos.org/build/185251589) [[:apple::heavy_exclamation_mark:]](https://hydra.nixos.org/build/185251730) [[:penguin::hourglass::no_entry_sign:]](https://hydra.nixos.org/build/185257079) [haskellPackages.wss-client](https://hydra.nixos.org/eval/1773138?filter=haskellPackages.wss-client)  :arrow_heading_up: 1 | 1
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/185255360) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/185256561) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/185253617) [haskellPackages.BiobaseXNA](https://hydra.nixos.org/eval/1773138?filter=haskellPackages.BiobaseXNA)  :arrow_heading_up: 0 | 17
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/185257025) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/185256417) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/185257399) [haskellPackages.BiobaseFasta](https://hydra.nixos.org/eval/1773138?filter=haskellPackages.BiobaseFasta)  :arrow_heading_up: 0 | 3
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/185256689) [[:apple::heavy_exclamation_mark:]](https://hydra.nixos.org/build/185251343) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/185251966) [haskellPackages.di](https://hydra.nixos.org/eval/1773138?filter=haskellPackages.di)  :arrow_heading_up: 0 | 2
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/185248871) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/185255444) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/185258645) [haskellPackages.align-audio](https://hydra.nixos.org/eval/1773138?filter=haskellPackages.align-audio) 
- [ ] [[:iphone::hourglass_flowing_sand:]](https://hydra.nixos.org/build/185253114) [[:apple::heavy_exclamation_mark:]](https://hydra.nixos.org/build/185251202) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/185253667) [haskellPackages.bnb-staking-csvs](https://hydra.nixos.org/eval/1773138?filter=haskellPackages.bnb-staking-csvs) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/184524589) [[:apple::heavy_exclamation_mark:]](https://hydra.nixos.org/build/184527982) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/184524706) [haskellPackages.easytensor-vulkan](https://hydra.nixos.org/eval/1773138?filter=haskellPackages.easytensor-vulkan) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/184518098) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/184528482) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/184532807) [haskellPackages.harfbuzz-pure](https://hydra.nixos.org/eval/1773138?filter=haskellPackages.harfbuzz-pure) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/185255006) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/185247777) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/185256383) [haskellPackages.hmatrix-nlopt](https://hydra.nixos.org/eval/1773138?filter=haskellPackages.hmatrix-nlopt) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/185249242) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/185247517) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/185251042) [haskellPackages.hs-swisstable-hashtables-class](https://hydra.nixos.org/eval/1773138?filter=haskellPackages.hs-swisstable-hashtables-class) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/184528557) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/184520139) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/184521761) [haskellPackages.kmn-programming](https://hydra.nixos.org/eval/1773138?filter=haskellPackages.kmn-programming) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/185247028) [[:apple::heavy_exclamation_mark:]](https://hydra.nixos.org/build/185252777) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/185249633) [haskellPackages.moto-postgresql](https://hydra.nixos.org/eval/1773138?filter=haskellPackages.moto-postgresql) 
- [ ] [[:iphone::hourglass_flowing_sand:]](https://hydra.nixos.org/build/185258405) [[:apple::heavy_exclamation_mark:]](https://hydra.nixos.org/build/185257349) [[:penguin::hourglass::no_entry_sign:]](https://hydra.nixos.org/build/185247794) [haskellPackages.network-messagepack-rpc-websocket](https://hydra.nixos.org/eval/1773138?filter=haskellPackages.network-messagepack-rpc-websocket) 
- [ ] [[:iphone::hourglass_flowing_sand:]](https://hydra.nixos.org/build/185257606) [[:apple::heavy_exclamation_mark:]](https://hydra.nixos.org/build/185251695) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/185249968) [haskellPackages.polysemy-log-di](https://hydra.nixos.org/eval/1773138?filter=haskellPackages.polysemy-log-di) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/185249970) [[:apple::heavy_exclamation_mark:]](https://hydra.nixos.org/build/185248020) [[:penguin::heavy_exclamation_mark:]](https://hydra.nixos.org/build/185248033) [haskellPackages.postgresql-simple-ltree](https://hydra.nixos.org/eval/1773138?filter=haskellPackages.postgresql-simple-ltree) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/185251259) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/185247548) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/185254218) [haskellPackages.rounded-hw](https://hydra.nixos.org/eval/1773138?filter=haskellPackages.rounded-hw) 
- [ ] [[:iphone::hourglass_flowing_sand:]](https://hydra.nixos.org/build/185252405) [[:apple::heavy_exclamation_mark:]](https://hydra.nixos.org/build/185252662) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/185250893) [haskellPackages.solana-staking-csvs](https://hydra.nixos.org/eval/1773138?filter=haskellPackages.solana-staking-csvs) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/185247967) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/185256933) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/185249929) [haskellPackages.sound-collage](https://hydra.nixos.org/eval/1773138?filter=haskellPackages.sound-collage) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/184533837) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/184518569) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/184533381) [haskellPackages.unicode-names](https://hydra.nixos.org/eval/1773138?filter=haskellPackages.unicode-names) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/185247194) [[:apple::heavy_exclamation_mark:]](https://hydra.nixos.org/build/185255915) [[:penguin::heavy_exclamation_mark:]](https://hydra.nixos.org/build/185249822) [haskellPackages.uniformBase](https://hydra.nixos.org/eval/1773138?filter=haskellPackages.uniformBase) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/185247731) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/185252150) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/185253296) [haskellPackages.warp-quic](https://hydra.nixos.org/eval/1773138?filter=haskellPackages.warp-quic) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/184522177) [[:apple::heavy_exclamation_mark:]](https://hydra.nixos.org/build/184525784) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/184536397) [haskellPackages.xbattbar](https://hydra.nixos.org/eval/1773138?filter=haskellPackages.xbattbar) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/185249095) [[:apple::heavy_exclamation_mark:]](https://hydra.nixos.org/build/185256678) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/185257129) [haskellPackages.xlsx-tabular](https://hydra.nixos.org/eval/1773138?filter=haskellPackages.xlsx-tabular) 
</details>

#### Top 50 broken packages, sorted by number of reverse dependencies
<details><summary>50 job(s) </summary>

[amazonka-core](https://packdeps.haskellers.com/reverse/amazonka-core) :arrow_heading_up: 185  
[gogol-core](https://packdeps.haskellers.com/reverse/gogol-core) :arrow_heading_up: 184  
[haskell98](https://packdeps.haskellers.com/reverse/haskell98) :arrow_heading_up: 153  
[enumerator](https://packdeps.haskellers.com/reverse/enumerator) :arrow_heading_up: 56  
[util](https://packdeps.haskellers.com/reverse/util) :arrow_heading_up: 49  
[derive](https://packdeps.haskellers.com/reverse/derive) :arrow_heading_up: 48  
[amazonka](https://packdeps.haskellers.com/reverse/amazonka) :arrow_heading_up: 43  
[accelerate](https://packdeps.haskellers.com/reverse/accelerate) :arrow_heading_up: 42  
[parseargs](https://packdeps.haskellers.com/reverse/parseargs) :arrow_heading_up: 42  
[syb-with-class](https://packdeps.haskellers.com/reverse/syb-with-class) :arrow_heading_up: 42  
[MonadCatchIO-transformers](https://packdeps.haskellers.com/reverse/MonadCatchIO-transformers) :arrow_heading_up: 41  
[data-lens](https://packdeps.haskellers.com/reverse/data-lens) :arrow_heading_up: 33  
[rank1dynamic](https://packdeps.haskellers.com/reverse/rank1dynamic) :arrow_heading_up: 33  
[distributed-static](https://packdeps.haskellers.com/reverse/distributed-static) :arrow_heading_up: 31  
[language-ecmascript](https://packdeps.haskellers.com/reverse/language-ecmascript) :arrow_heading_up: 31  
[distributed-process](https://packdeps.haskellers.com/reverse/distributed-process) :arrow_heading_up: 30  
[ip](https://packdeps.haskellers.com/reverse/ip) :arrow_heading_up: 29  
[iteratee](https://packdeps.haskellers.com/reverse/iteratee) :arrow_heading_up: 29  
[jmacro](https://packdeps.haskellers.com/reverse/jmacro) :arrow_heading_up: 29  
[text-format](https://packdeps.haskellers.com/reverse/text-format) :arrow_heading_up: 28  
[mmsyn3](https://packdeps.haskellers.com/reverse/mmsyn3) :arrow_heading_up: 27  
[autodocodec-yaml](https://packdeps.haskellers.com/reverse/autodocodec-yaml) :arrow_heading_up: 26  
[crypto-numbers](https://packdeps.haskellers.com/reverse/crypto-numbers) :arrow_heading_up: 25  
[either-unwrap](https://packdeps.haskellers.com/reverse/either-unwrap) :arrow_heading_up: 25  
[web-routes-th](https://packdeps.haskellers.com/reverse/web-routes-th) :arrow_heading_up: 24  
[ixset-typed](https://packdeps.haskellers.com/reverse/ixset-typed) :arrow_heading_up: 23  
[sydtest](https://packdeps.haskellers.com/reverse/sydtest) :arrow_heading_up: 23  
[crypto-pubkey](https://packdeps.haskellers.com/reverse/crypto-pubkey) :arrow_heading_up: 22  
[haskelldb](https://packdeps.haskellers.com/reverse/haskelldb) :arrow_heading_up: 22  
[wxdirect](https://packdeps.haskellers.com/reverse/wxdirect) :arrow_heading_up: 22  
[alg](https://packdeps.haskellers.com/reverse/alg) :arrow_heading_up: 21  
[amazonka-s3](https://packdeps.haskellers.com/reverse/amazonka-s3) :arrow_heading_up: 21  
[mmsyn2](https://packdeps.haskellers.com/reverse/mmsyn2) :arrow_heading_up: 21  
[userid](https://packdeps.haskellers.com/reverse/userid) :arrow_heading_up: 21  
[wxc](https://packdeps.haskellers.com/reverse/wxc) :arrow_heading_up: 21  
[biocore](https://packdeps.haskellers.com/reverse/biocore) :arrow_heading_up: 20  
[subG](https://packdeps.haskellers.com/reverse/subG) :arrow_heading_up: 20  
[wxcore](https://packdeps.haskellers.com/reverse/wxcore) :arrow_heading_up: 20  
[attoparsec-enumerator](https://packdeps.haskellers.com/reverse/attoparsec-enumerator) :arrow_heading_up: 19  
[bytestring-show](https://packdeps.haskellers.com/reverse/bytestring-show) :arrow_heading_up: 19  
[fay](https://packdeps.haskellers.com/reverse/fay) :arrow_heading_up: 19  
[harp](https://packdeps.haskellers.com/reverse/harp) :arrow_heading_up: 19  
[hsx2hs](https://packdeps.haskellers.com/reverse/hsx2hs) :arrow_heading_up: 19  
[ixset](https://packdeps.haskellers.com/reverse/ixset) :arrow_heading_up: 19  
[wx](https://packdeps.haskellers.com/reverse/wx) :arrow_heading_up: 19  
[asn1-data](https://packdeps.haskellers.com/reverse/asn1-data) :arrow_heading_up: 18  
[dbus-core](https://packdeps.haskellers.com/reverse/dbus-core) :arrow_heading_up: 18  
[gtksourceview2](https://packdeps.haskellers.com/reverse/gtksourceview2) :arrow_heading_up: 18  
[ukrainian-phonetics-basic](https://packdeps.haskellers.com/reverse/ukrainian-phonetics-basic) :arrow_heading_up: 18  
[HGamer3D-Data](https://packdeps.haskellers.com/reverse/HGamer3D-Data) :arrow_heading_up: 17  
</details>


*:arrow_heading_up:: The number of packages that depend (directly or indirectly) on this package (if any). If two numbers are shown the first (lower) number considers only packages which currently have enabled hydra jobs, i.e. are not marked broken. The second (higher) number considers all packages.*

*Report generated with [maintainers/scripts/haskell/hydra-report.hs](https://github.com/NixOS/nixpkgs/blob/haskell-updates/maintainers/scripts/haskell/hydra-report.sh)*


----------------------------------------------------------------------

This README.md is automatically updated every 6 hours with the status of the
[`haskell-updates` branch/jobset on Hydra](https://hydra.nixos.org/jobset/nixpkgs/haskell-updates)
from [Nixpkgs](https://github.com/NixOS/nixpkgs).  This is mostly only of
interest to the [Nixpkgs Haskell maintainers](https://github.com/orgs/NixOS/teams/haskell).

See the
[haskell-modules/HACKING.md](https://github.com/NixOS/nixpkgs/blob/haskell-updates/pkgs/development/haskell-modules/HACKING.md)
file for more information about this build report.

You may also be interested in the currently open
[`haskell-updates` PR in Nixpkgs](https://github.com/nixos/nixpkgs/pulls?q=is%3Apr+is%3Aopen+head%3Ahaskell-updates).

You can force the GitHub Action to run (and the README.md to be updated) by
manually running the Action.  To do this, go to the Action list screen
(https://github.com/cdepillabout/nix-haskell-updates-status/actions),
click on any of the Workflow runs, and then click the `Re-run jobs` button.
