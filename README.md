### [haskell-updates build report from hydra](https://hydra.nixos.org/jobset/nixpkgs/haskell-updates)
*evaluation [1780493](https://hydra.nixos.org/eval/1780493) of nixpkgs commit [464616e](https://github.com/NixOS/nixpkgs/commits/464616ef3cda97d570a521d26d23eb88e3673723) as of 2022-09-13 06:55 UTC*

:red_circle: **Branch not mergeable**
  * `mergeable` jobset failed.
  * Too many outstanding jobs on aarch64-linux.
  * `maintained` jobset failed.

#### Build summary

 | Platform | Failed :x: | DependencyFailed :heavy_exclamation_mark: | Unfinished :hourglass_flowing_sand: | Success :heavy_check_mark: | 
 | --- | --- | --- | --- | --- | 
 | [aarch64-linux :iphone:](https://hydra.nixos.org/eval/1780493?filter=.aarch64-linux) | 30 | 30 | 494 | 6157 | 
 | [x86_64-darwin :apple:](https://hydra.nixos.org/eval/1780493?filter=.x86_64-darwin) | 38 | 4 | 1618 | 4981 | 
 | [x86_64-linux :penguin:](https://hydra.nixos.org/eval/1780493?filter=.x86_64-linux) | 11 | 13 | 15 | 6696 | 
#### Maintained packages with build failure
- [ ] [cabal-install](https://hydra.nixos.org/eval/1780493?filter=cabal-install) @peti
  - [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/190422061) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/190430016) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/190430561) [toplevel](https://hydra.nixos.org/eval/1780493?filter=cabal-install)
  - [[:iphone::hourglass_flowing_sand:]](https://hydra.nixos.org/build/190434010) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/190424352) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/190425638) [haskell.packages.ghc8107](https://hydra.nixos.org/eval/1780493?filter=haskell.packages.ghc8107.cabal-install)
  - [[:iphone::x:]](https://hydra.nixos.org/build/190426162) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/190433900) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/190425647) [haskell.packages.ghc884](https://hydra.nixos.org/eval/1780493?filter=haskell.packages.ghc884.cabal-install)
  - [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/190428317) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/190435659) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/190434581) [haskell.packages.ghc902](https://hydra.nixos.org/eval/1780493?filter=haskell.packages.ghc902.cabal-install)
  - [[:iphone::hourglass_flowing_sand:]](https://hydra.nixos.org/build/190436769) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/190433988) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/190423533) [haskell.packages.ghc924](https://hydra.nixos.org/eval/1780493?filter=haskell.packages.ghc924.cabal-install)
  - [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/190422563) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/190424044) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/190426054) [haskellPackages](https://hydra.nixos.org/eval/1780493?filter=haskellPackages.cabal-install)
- [ ] [xmonad](https://hydra.nixos.org/eval/1780493?filter=xmonad) @NeQuissimus @ivanbrennan @peti
  - [[:iphone::x:]](https://hydra.nixos.org/build/190435289) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/190423052) [[:penguin::x:]](https://hydra.nixos.org/build/190438027) [haskellPackages](https://hydra.nixos.org/eval/1780493?filter=haskellPackages.xmonad)
  -   [[:penguin::heavy_exclamation_mark:]](https://hydra.nixos.org/build/190429276) [nixosTests](https://hydra.nixos.org/eval/1780493?filter=nixosTests.xmonad)
#### Maintained packages with failed dependency
- [ ] [haskell-language-server](https://hydra.nixos.org/eval/1780493?filter=haskell-language-server) @maralorn
  - [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/190429450) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/190425373) [[:penguin::heavy_exclamation_mark:]](https://hydra.nixos.org/build/190424293) [toplevel](https://hydra.nixos.org/eval/1780493?filter=haskell-language-server)
  - [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/190434864) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/190431932) [[:penguin::heavy_exclamation_mark:]](https://hydra.nixos.org/build/190425146) [haskell.packages.ghc8107](https://hydra.nixos.org/eval/1780493?filter=haskell.packages.ghc8107.haskell-language-server)
  - [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/190418417) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/190423241) [[:penguin::heavy_exclamation_mark:]](https://hydra.nixos.org/build/190436674) [haskell.packages.ghc884](https://hydra.nixos.org/eval/1780493?filter=haskell.packages.ghc884.haskell-language-server)
  - [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/190422826) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/190427158) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/190434052) [haskell.packages.ghc902](https://hydra.nixos.org/eval/1780493?filter=haskell.packages.ghc902.haskell-language-server)
  - [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/190422274) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/190434720) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/190433597) [haskell.packages.ghc924](https://hydra.nixos.org/eval/1780493?filter=haskell.packages.ghc924.haskell-language-server)
  - [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/190436858) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/190426855) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/190434471) [haskellPackages](https://hydra.nixos.org/eval/1780493?filter=haskellPackages.haskell-language-server)
- [ ] [[:penguin::heavy_exclamation_mark:]](https://hydra.nixos.org/build/190418402) [maintained](https://hydra.nixos.org/eval/1780493?filter=maintained) @cdepillabout @expipiplus1 @maralorn @sternenseemann
- [ ] [[:penguin::heavy_exclamation_mark:]](https://hydra.nixos.org/build/190430620) [mergeable](https://hydra.nixos.org/eval/1780493?filter=mergeable) @cdepillabout @expipiplus1 @maralorn @sternenseemann
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/190428675) [[:penguin::heavy_exclamation_mark:]](https://hydra.nixos.org/build/190423532) [taffybar](https://hydra.nixos.org/eval/1780493?filter=taffybar) @rvl
- [ ] [weeder](https://hydra.nixos.org/eval/1780493?filter=weeder) @maralorn
  - [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/190420317) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/190432075) [[:penguin::heavy_exclamation_mark:]](https://hydra.nixos.org/build/190433887) [haskell.packages.ghc8107](https://hydra.nixos.org/eval/1780493?filter=haskell.packages.ghc8107.weeder)
  - [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/190421693) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/190432200) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/190429384) [haskell.packages.ghc902](https://hydra.nixos.org/eval/1780493?filter=haskell.packages.ghc902.weeder)
  - [[:iphone::hourglass_flowing_sand:]](https://hydra.nixos.org/build/190434980) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/190423387) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/190429807) [haskell.packages.ghc924](https://hydra.nixos.org/eval/1780493?filter=haskell.packages.ghc924.weeder)
  - [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/190431343) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/190435592) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/190422413) [haskellPackages](https://hydra.nixos.org/eval/1780493?filter=haskellPackages.weeder)
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/190433806) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/190429363) [[:penguin::heavy_exclamation_mark:]](https://hydra.nixos.org/build/190430714) [haskellPackages.xmonad-contrib](https://hydra.nixos.org/eval/1780493?filter=haskellPackages.xmonad-contrib) @peti
- [ ] [[:penguin::heavy_exclamation_mark:]](https://hydra.nixos.org/build/190429984) [nixosTests.xmonad-xdg-autostart](https://hydra.nixos.org/eval/1780493?filter=nixosTests.xmonad-xdg-autostart) @oxalica
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/190433458) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/190420962) [[:penguin::heavy_exclamation_mark:]](https://hydra.nixos.org/build/190433938) [xmonadctl](https://hydra.nixos.org/eval/1780493?filter=xmonadctl) @ajgrf
#### Unmaintained packages with build failure
<details><summary>71 job(s) </summary>

- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/190431005) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/190426145) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/190421465) [haskellPackages.OrderedBits](https://hydra.nixos.org/eval/1780493?filter=haskellPackages.OrderedBits)  :arrow_heading_up: 5 | 36
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/190418284) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/190435872) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/190427652) [haskellPackages.hw-json-simd](https://hydra.nixos.org/eval/1780493?filter=haskellPackages.hw-json-simd)  :arrow_heading_up: 4 | 8
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/190426554) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/190433701) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/190435927) [haskellPackages.long-double](https://hydra.nixos.org/eval/1780493?filter=haskellPackages.long-double)  :arrow_heading_up: 2 | 2
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/190437610) [[:apple::x:]](https://hydra.nixos.org/build/190418485) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/190419817) [haskellPackages.quic](https://hydra.nixos.org/eval/1780493?filter=haskellPackages.quic)  :arrow_heading_up: 2 | 2
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/190418721) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/190424366) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/190418471) [haskellPackages.freetype2](https://hydra.nixos.org/eval/1780493?filter=haskellPackages.freetype2)  :arrow_heading_up: 1 | 8
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/190426179) [[:apple::x:]](https://hydra.nixos.org/build/190428059) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/190423250) [haskellPackages.easytensor](https://hydra.nixos.org/eval/1780493?filter=haskellPackages.easytensor)  :arrow_heading_up: 1 | 1
- [ ] [futhark](https://hydra.nixos.org/eval/1780493?filter=futhark)  :arrow_heading_up: 1 | 1
  - [[:iphone::hourglass_flowing_sand:]](https://hydra.nixos.org/build/190429894) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/190435640) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/190421580) [toplevel](https://hydra.nixos.org/eval/1780493?filter=futhark)
  - [[:iphone::hourglass_flowing_sand:]](https://hydra.nixos.org/build/190433463) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/190422015) [[:penguin::x:]](https://hydra.nixos.org/build/190438453) [haskellPackages](https://hydra.nixos.org/eval/1780493?filter=haskellPackages.futhark)
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/190424218) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/190425062) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/190431214) [haskellPackages.haskell-admin-health](https://hydra.nixos.org/eval/1780493?filter=haskellPackages.haskell-admin-health)  :arrow_heading_up: 1 | 1
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/190420884) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/190436438) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/190425960) [haskellPackages.nlopt-haskell](https://hydra.nixos.org/eval/1780493?filter=haskellPackages.nlopt-haskell)  :arrow_heading_up: 1 | 1
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/190421787) [[:apple::x:]](https://hydra.nixos.org/build/190430196) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/190438325) [haskellPackages.openal-ffi](https://hydra.nixos.org/eval/1780493?filter=haskellPackages.openal-ffi)  :arrow_heading_up: 1 | 1
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/190426560) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/190422117) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/190422325) [haskellPackages.swisstable](https://hydra.nixos.org/eval/1780493?filter=haskellPackages.swisstable)  :arrow_heading_up: 1 | 1
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/190434587) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/190427671) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/190433104) [haskellPackages.unicode-properties](https://hydra.nixos.org/eval/1780493?filter=haskellPackages.unicode-properties)  :arrow_heading_up: 1 | 1
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/190436937) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/190419069) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/190435488) [haskellPackages.flatparse](https://hydra.nixos.org/eval/1780493?filter=haskellPackages.flatparse)  :arrow_heading_up: 0 | 14
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/190428795) [[:apple::x:]](https://hydra.nixos.org/build/190430540) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/190429741) [haskellPackages.PyF](https://hydra.nixos.org/eval/1780493?filter=haskellPackages.PyF)  :arrow_heading_up: 0 | 4
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/190435452) [[:apple::x:]](https://hydra.nixos.org/build/190423209) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/190423465) [haskellPackages.hmidi](https://hydra.nixos.org/eval/1780493?filter=haskellPackages.hmidi)  :arrow_heading_up: 0 | 4
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/190420703) [[:apple::x:]](https://hydra.nixos.org/build/190437843) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/190434958) [haskellPackages.hamid](https://hydra.nixos.org/eval/1780493?filter=haskellPackages.hamid)  :arrow_heading_up: 0 | 1
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/190427217) [[:apple::x:]](https://hydra.nixos.org/build/190422876) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/190434364) [haskellPackages.hmatrix-morpheus](https://hydra.nixos.org/eval/1780493?filter=haskellPackages.hmatrix-morpheus)  :arrow_heading_up: 0 | 1
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/190435315) [[:apple::x:]](https://hydra.nixos.org/build/190424984) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/190422869) [haskellPackages.huckleberry](https://hydra.nixos.org/eval/1780493?filter=haskellPackages.huckleberry)  :arrow_heading_up: 0 | 1
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/190422851) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/190421788) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/190427574) [haskellPackages.picosat](https://hydra.nixos.org/eval/1780493?filter=haskellPackages.picosat)  :arrow_heading_up: 0 | 1
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/190421878) [[:apple::x:]](https://hydra.nixos.org/build/190420004) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/190419766) [haskellPackages.select](https://hydra.nixos.org/eval/1780493?filter=haskellPackages.select)  :arrow_heading_up: 0 | 1
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/190433888) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/190420467) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/190429972) [haskellPackages.simple-vec3](https://hydra.nixos.org/eval/1780493?filter=haskellPackages.simple-vec3)  :arrow_heading_up: 0 | 1
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/190435304) [[:apple::x:]](https://hydra.nixos.org/build/190437845) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/190425782) [haskellPackages.sysinfo](https://hydra.nixos.org/eval/1780493?filter=haskellPackages.sysinfo)  :arrow_heading_up: 0 | 1
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/190426515) [[:apple::x:]](https://hydra.nixos.org/build/190430439) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/190423606) [haskellPackages.FractalArt](https://hydra.nixos.org/eval/1780493?filter=haskellPackages.FractalArt) 
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/190435051) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/190434382) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/190436557) [haskellPackages.HsASA](https://hydra.nixos.org/eval/1780493?filter=haskellPackages.HsASA) 
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/190418395) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/190425917) [[:penguin::x:]](https://hydra.nixos.org/build/190429391) [haskellPackages.bidirectional-instances](https://hydra.nixos.org/eval/1780493?filter=haskellPackages.bidirectional-instances) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/190429501) [[:apple::x:]](https://hydra.nixos.org/build/190434413) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/190436327) [haskellPackages.chiphunk](https://hydra.nixos.org/eval/1780493?filter=haskellPackages.chiphunk) 
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/190426409) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/190438510) [[:penguin::x:]](https://hydra.nixos.org/build/190437098) [haskellPackages.cicero-api](https://hydra.nixos.org/eval/1780493?filter=haskellPackages.cicero-api) 
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/190434552) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/190438494) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/190432930) [haskellPackages.comfort-fftw](https://hydra.nixos.org/eval/1780493?filter=haskellPackages.comfort-fftw) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/190436349) [[:apple::x:]](https://hydra.nixos.org/build/190429906) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/190437140) [haskellPackages.diskhash](https://hydra.nixos.org/eval/1780493?filter=haskellPackages.diskhash) 
- [ ] [elm2nix](https://hydra.nixos.org/eval/1780493?filter=elm2nix) 
  - [[:iphone::x:]](https://hydra.nixos.org/build/190420803) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/190436375) [[:penguin::x:]](https://hydra.nixos.org/build/190418421) [toplevel](https://hydra.nixos.org/eval/1780493?filter=elm2nix)
  - [[:iphone::x:]](https://hydra.nixos.org/build/190420972) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/190422235) [[:penguin::x:]](https://hydra.nixos.org/build/190422171) [haskellPackages](https://hydra.nixos.org/eval/1780493?filter=haskellPackages.elm2nix)
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/190422331) [[:apple::x:]](https://hydra.nixos.org/build/190421828) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/190421042) [haskellPackages.fudgets](https://hydra.nixos.org/eval/1780493?filter=haskellPackages.fudgets) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/190433305) [[:apple::x:]](https://hydra.nixos.org/build/190423550) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/190436480) [haskellPackages.gerrit](https://hydra.nixos.org/eval/1780493?filter=haskellPackages.gerrit) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/190428783) [[:apple::x:]](https://hydra.nixos.org/build/190418276) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/190435006) [haskellPackages.ghc-gc-hook](https://hydra.nixos.org/eval/1780493?filter=haskellPackages.ghc-gc-hook) 
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/190419663) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/190430872) [haskellPackages.gnome-keyring](https://hydra.nixos.org/eval/1780493?filter=haskellPackages.gnome-keyring) 
- [ ] [[:apple::x:]](https://hydra.nixos.org/build/190425865) [haskellPackages.gtk-mac-integration](https://hydra.nixos.org/eval/1780493?filter=haskellPackages.gtk-mac-integration) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/190427153) [[:apple::x:]](https://hydra.nixos.org/build/190424726) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/190431153) [haskellPackages.gtk-traymanager](https://hydra.nixos.org/eval/1780493?filter=haskellPackages.gtk-traymanager) 
- [ ] [[:apple::x:]](https://hydra.nixos.org/build/190433684) [haskellPackages.gtk3-mac-integration](https://hydra.nixos.org/eval/1780493?filter=haskellPackages.gtk3-mac-integration) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/190428754) [[:apple::x:]](https://hydra.nixos.org/build/190424290) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/190420486) [haskellPackages.hid](https://hydra.nixos.org/eval/1780493?filter=haskellPackages.hid) 
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/190422596) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/190425427) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/190429399) [haskellPackages.hinotify-conduit](https://hydra.nixos.org/eval/1780493?filter=haskellPackages.hinotify-conduit) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/190437030) [[:apple::x:]](https://hydra.nixos.org/build/190420833) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/190435871) [haskellPackages.hsshellscript](https://hydra.nixos.org/eval/1780493?filter=haskellPackages.hsshellscript) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/190438505) [[:apple::x:]](https://hydra.nixos.org/build/190422004) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/190435562) [haskellPackages.hssourceinfo](https://hydra.nixos.org/eval/1780493?filter=haskellPackages.hssourceinfo) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/190432750) [[:apple::x:]](https://hydra.nixos.org/build/190419419) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/190433284) [haskellPackages.interprocess](https://hydra.nixos.org/eval/1780493?filter=haskellPackages.interprocess) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/190419382) [[:apple::x:]](https://hydra.nixos.org/build/190427460) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/190429506) [haskellPackages.intricacy](https://hydra.nixos.org/eval/1780493?filter=haskellPackages.intricacy) 
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/190429809) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/190420867) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/190435388) [haskellPackages.jammittools](https://hydra.nixos.org/eval/1780493?filter=haskellPackages.jammittools) 
- [ ] [[:apple::x:]](https://hydra.nixos.org/build/190429773) [haskellPackages.kqueue](https://hydra.nixos.org/eval/1780493?filter=haskellPackages.kqueue) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/190429726) [[:apple::x:]](https://hydra.nixos.org/build/190421244) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/190422406) [haskellPackages.linux-framebuffer](https://hydra.nixos.org/eval/1780493?filter=haskellPackages.linux-framebuffer) 
- [ ] [[:iphone::hourglass_flowing_sand:]](https://hydra.nixos.org/build/190437436) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/190424746) [[:penguin::x:]](https://hydra.nixos.org/build/190427072) [haskellPackages.loc-test](https://hydra.nixos.org/eval/1780493?filter=haskellPackages.loc-test) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/190437330) [[:apple::x:]](https://hydra.nixos.org/build/190420114) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/190424042) [haskellPackages.memfd](https://hydra.nixos.org/eval/1780493?filter=haskellPackages.memfd) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/190431691) [[:apple::x:]](https://hydra.nixos.org/build/190420349) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/190436127) [haskellPackages.mercury-api](https://hydra.nixos.org/eval/1780493?filter=haskellPackages.mercury-api) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/190438583) [[:apple::x:]](https://hydra.nixos.org/build/190431381) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/190419732) [haskellPackages.nano-cryptr](https://hydra.nixos.org/eval/1780493?filter=haskellPackages.nano-cryptr) 
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/190423899) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/190420807) [[:penguin::x:]](https://hydra.nixos.org/build/190434935) [haskellPackages.panfiguration](https://hydra.nixos.org/eval/1780493?filter=haskellPackages.panfiguration) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/190419667) [[:apple::x:]](https://hydra.nixos.org/build/190428126) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/190424911) [haskellPackages.posix-timer](https://hydra.nixos.org/eval/1780493?filter=haskellPackages.posix-timer) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/190427015) [[:apple::x:]](https://hydra.nixos.org/build/190426253) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/190437704) [haskellPackages.pthread](https://hydra.nixos.org/eval/1780493?filter=haskellPackages.pthread) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/190423556) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/190432668) [[:penguin::x:]](https://hydra.nixos.org/build/190433161) [haskellPackages.reserve](https://hydra.nixos.org/eval/1780493?filter=haskellPackages.reserve) 
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/190427344) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/190428826) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/190438377) [haskellPackages.risc386](https://hydra.nixos.org/eval/1780493?filter=haskellPackages.risc386) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/190422483) [[:apple::x:]](https://hydra.nixos.org/build/190428959) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/190434501) [haskellPackages.sfml-audio](https://hydra.nixos.org/eval/1780493?filter=haskellPackages.sfml-audio) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/190433665) [[:apple::x:]](https://hydra.nixos.org/build/190426378) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/190437206) [haskellPackages.shared-memory](https://hydra.nixos.org/eval/1780493?filter=haskellPackages.shared-memory) 
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/190423958) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/190427928) [[:penguin::x:]](https://hydra.nixos.org/build/190433784) [haskellPackages.significant-figures](https://hydra.nixos.org/eval/1780493?filter=haskellPackages.significant-figures) 
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/190423315) [[:apple::x:]](https://hydra.nixos.org/build/190429164) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/190438488) [haskellPackages.slugify](https://hydra.nixos.org/eval/1780493?filter=haskellPackages.slugify) 
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/190421659) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/190430013) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/190419700) [haskellPackages.wiringPi](https://hydra.nixos.org/eval/1780493?filter=haskellPackages.wiringPi) 
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/190429268) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/190428038) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/190426739) [haskellPackages.x86-64bit](https://hydra.nixos.org/eval/1780493?filter=haskellPackages.x86-64bit) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/190435907) [[:apple::x:]](https://hydra.nixos.org/build/190428069) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/190424628) [haskellPackages.xmonad-utils](https://hydra.nixos.org/eval/1780493?filter=haskellPackages.xmonad-utils) 
- [ ] [[:iphone::hourglass_flowing_sand:]](https://hydra.nixos.org/build/190436162) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/190419569) [[:penguin::x:]](https://hydra.nixos.org/build/190433564) [haskellPackages.xstatic-th](https://hydra.nixos.org/eval/1780493?filter=haskellPackages.xstatic-th) 
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/190424161) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/190427020) [[:penguin::x:]](https://hydra.nixos.org/build/190427961) [haskellPackages.yarl](https://hydra.nixos.org/eval/1780493?filter=haskellPackages.yarl) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/190426980) [[:apple::x:]](https://hydra.nixos.org/build/190426061) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/190420502) [haskellPackages.yoga](https://hydra.nixos.org/eval/1780493?filter=haskellPackages.yoga) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/190436342) [[:apple::x:]](https://hydra.nixos.org/build/190436771) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/190438349) [haskellPackages.zot](https://hydra.nixos.org/eval/1780493?filter=haskellPackages.zot) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/190418762) [[:apple::x:]](https://hydra.nixos.org/build/190433345) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/190423003) [haskellPackages.zxcvbn-c](https://hydra.nixos.org/eval/1780493?filter=haskellPackages.zxcvbn-c) 
</details>

#### Unmaintained packages with failed dependency
<details><summary>33 job(s) </summary>

- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/190423047) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/190428573) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/190433396) [haskellPackages.PrimitiveArray](https://hydra.nixos.org/eval/1780493?filter=haskellPackages.PrimitiveArray)  :arrow_heading_up: 4 | 35
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/190430547) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/190434132) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/190433095) [haskellPackages.BiobaseTypes](https://hydra.nixos.org/eval/1780493?filter=haskellPackages.BiobaseTypes)  :arrow_heading_up: 3 | 21
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/190426955) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/190420300) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/190424992) [haskellPackages.hw-json-standard-cursor](https://hydra.nixos.org/eval/1780493?filter=haskellPackages.hw-json-standard-cursor)  :arrow_heading_up: 2 | 6
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/190420794) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/190420979) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/190432705) [haskellPackages.hw-json-simple-cursor](https://hydra.nixos.org/eval/1780493?filter=haskellPackages.hw-json-simple-cursor)  :arrow_heading_up: 2 | 4
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/190424585) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/190428752) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/190430726) [haskellPackages.BiobaseENA](https://hydra.nixos.org/eval/1780493?filter=haskellPackages.BiobaseENA)  :arrow_heading_up: 1 | 18
- [ ] [hoogle](https://hydra.nixos.org/eval/1780493?filter=hoogle)  :arrow_heading_up: 1 | 3
  - [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/190428599) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/190421911) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/190434925) [haskell.packages.ghc8107](https://hydra.nixos.org/eval/1780493?filter=haskell.packages.ghc8107.hoogle)
  - [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/190420304) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/190423503) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/190431705) [haskell.packages.ghc884](https://hydra.nixos.org/eval/1780493?filter=haskell.packages.ghc884.hoogle)
  - [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/190438524) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/190431232) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/190433741) [haskell.packages.ghc902](https://hydra.nixos.org/eval/1780493?filter=haskell.packages.ghc902.hoogle)
  - [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/190427705) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/190427424) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/190429826) [haskell.packages.ghc924](https://hydra.nixos.org/eval/1780493?filter=haskell.packages.ghc924.hoogle)
  - [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/190429525) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/190430879) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/190419759) [haskellPackages](https://hydra.nixos.org/eval/1780493?filter=haskellPackages.hoogle)
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/190435673) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/190419901) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/190435481) [haskellPackages.hw-json](https://hydra.nixos.org/eval/1780493?filter=haskellPackages.hw-json)  :arrow_heading_up: 1 | 3
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/190430941) [[:apple::heavy_exclamation_mark:]](https://hydra.nixos.org/build/190430235) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/190426835) [haskellPackages.http3](https://hydra.nixos.org/eval/1780493?filter=haskellPackages.http3)  :arrow_heading_up: 1 | 1
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/190427282) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/190435264) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/190435122) [haskellPackages.BiobaseXNA](https://hydra.nixos.org/eval/1780493?filter=haskellPackages.BiobaseXNA)  :arrow_heading_up: 0 | 17
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/190433132) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/190420995) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/190433491) [haskellPackages.BiobaseFasta](https://hydra.nixos.org/eval/1780493?filter=haskellPackages.BiobaseFasta)  :arrow_heading_up: 0 | 3
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/190430393) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/190421592) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/190438165) [haskellPackages.hw-json-lens](https://hydra.nixos.org/eval/1780493?filter=haskellPackages.hw-json-lens)  :arrow_heading_up: 0 | 1
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/190430027) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/190434081) [[:penguin::heavy_exclamation_mark:]](https://hydra.nixos.org/build/190421377) [haskellPackages.DescriptiveKeys](https://hydra.nixos.org/eval/1780493?filter=haskellPackages.DescriptiveKeys) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/190430228) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/190420193) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/190434137) [haskellPackages.align-audio](https://hydra.nixos.org/eval/1780493?filter=haskellPackages.align-audio) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/190434920) [[:apple::heavy_exclamation_mark:]](https://hydra.nixos.org/build/190437763) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/190437884) [haskellPackages.easytensor-vulkan](https://hydra.nixos.org/eval/1780493?filter=haskellPackages.easytensor-vulkan) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/190428304) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/190426306) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/190428625) [haskellPackages.harfbuzz-pure](https://hydra.nixos.org/eval/1780493?filter=haskellPackages.harfbuzz-pure) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/190421597) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/190425098) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/190436618) [haskellPackages.haskell-admin](https://hydra.nixos.org/eval/1780493?filter=haskellPackages.haskell-admin) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/190431791) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/190430059) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/190435855) [haskellPackages.hmatrix-nlopt](https://hydra.nixos.org/eval/1780493?filter=haskellPackages.hmatrix-nlopt) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/190432249) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/190427429) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/190421622) [haskellPackages.hs-swisstable-hashtables-class](https://hydra.nixos.org/eval/1780493?filter=haskellPackages.hs-swisstable-hashtables-class) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/190426859) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/190434719) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/190432027) [haskellPackages.kmn-programming](https://hydra.nixos.org/eval/1780493?filter=haskellPackages.kmn-programming) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/190433858) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/190434455) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/190424957) [haskellPackages.rounded](https://hydra.nixos.org/eval/1780493?filter=haskellPackages.rounded) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/190421978) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/190436722) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/190421181) [haskellPackages.rounded-hw](https://hydra.nixos.org/eval/1780493?filter=haskellPackages.rounded-hw) 
- [ ] [[:iphone::hourglass_flowing_sand:]](https://hydra.nixos.org/build/190431105) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/190421414) [[:penguin::heavy_exclamation_mark:]](https://hydra.nixos.org/build/190426503) [haskellPackages.shake-futhark](https://hydra.nixos.org/eval/1780493?filter=haskellPackages.shake-futhark) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/190436643) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/190434723) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/190430706) [haskellPackages.sound-collage](https://hydra.nixos.org/eval/1780493?filter=haskellPackages.sound-collage) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/190432799) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/190425240) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/190424340) [haskellPackages.unicode-names](https://hydra.nixos.org/eval/1780493?filter=haskellPackages.unicode-names) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/190434891) [[:apple::heavy_exclamation_mark:]](https://hydra.nixos.org/build/190418740) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/190423216) [haskellPackages.warp-quic](https://hydra.nixos.org/eval/1780493?filter=haskellPackages.warp-quic) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/190431301) [[:apple::heavy_exclamation_mark:]](https://hydra.nixos.org/build/190420645) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/190424172) [haskellPackages.xbattbar](https://hydra.nixos.org/eval/1780493?filter=haskellPackages.xbattbar) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/190434187) [[:penguin::heavy_exclamation_mark:]](https://hydra.nixos.org/build/190434826) [haskellPackages.xmonad-extras](https://hydra.nixos.org/eval/1780493?filter=haskellPackages.xmonad-extras) 
- [ ] [[:penguin::heavy_exclamation_mark:]](https://hydra.nixos.org/build/190423364) [xmonad-with-packages](https://hydra.nixos.org/eval/1780493?filter=xmonad-with-packages) 
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
[MonadCatchIO-transformers](https://packdeps.haskellers.com/reverse/MonadCatchIO-transformers) :arrow_heading_up: 41  
[data-lens](https://packdeps.haskellers.com/reverse/data-lens) :arrow_heading_up: 33  
[rank1dynamic](https://packdeps.haskellers.com/reverse/rank1dynamic) :arrow_heading_up: 33  
[distributed-static](https://packdeps.haskellers.com/reverse/distributed-static) :arrow_heading_up: 31  
[language-ecmascript](https://packdeps.haskellers.com/reverse/language-ecmascript) :arrow_heading_up: 31  
[distributed-process](https://packdeps.haskellers.com/reverse/distributed-process) :arrow_heading_up: 30  
[iteratee](https://packdeps.haskellers.com/reverse/iteratee) :arrow_heading_up: 29  
[jmacro](https://packdeps.haskellers.com/reverse/jmacro) :arrow_heading_up: 29  
[mmsyn3](https://packdeps.haskellers.com/reverse/mmsyn3) :arrow_heading_up: 28  
[autodocodec-yaml](https://packdeps.haskellers.com/reverse/autodocodec-yaml) :arrow_heading_up: 27  
[crypto-numbers](https://packdeps.haskellers.com/reverse/crypto-numbers) :arrow_heading_up: 25  
[either-unwrap](https://packdeps.haskellers.com/reverse/either-unwrap) :arrow_heading_up: 25  
[sydtest](https://packdeps.haskellers.com/reverse/sydtest) :arrow_heading_up: 24  
[crypto-pubkey](https://packdeps.haskellers.com/reverse/crypto-pubkey) :arrow_heading_up: 22  
[haskelldb](https://packdeps.haskellers.com/reverse/haskelldb) :arrow_heading_up: 22  
[wxdirect](https://packdeps.haskellers.com/reverse/wxdirect) :arrow_heading_up: 22  
[alg](https://packdeps.haskellers.com/reverse/alg) :arrow_heading_up: 21  
[amazonka-s3](https://packdeps.haskellers.com/reverse/amazonka-s3) :arrow_heading_up: 21  
[mmsyn2](https://packdeps.haskellers.com/reverse/mmsyn2) :arrow_heading_up: 21  
[wxc](https://packdeps.haskellers.com/reverse/wxc) :arrow_heading_up: 21  
[biocore](https://packdeps.haskellers.com/reverse/biocore) :arrow_heading_up: 20  
[wxcore](https://packdeps.haskellers.com/reverse/wxcore) :arrow_heading_up: 20  
[attoparsec-enumerator](https://packdeps.haskellers.com/reverse/attoparsec-enumerator) :arrow_heading_up: 19  
[bytestring-show](https://packdeps.haskellers.com/reverse/bytestring-show) :arrow_heading_up: 19  
[fay](https://packdeps.haskellers.com/reverse/fay) :arrow_heading_up: 19  
[wx](https://packdeps.haskellers.com/reverse/wx) :arrow_heading_up: 19  
[asn1-data](https://packdeps.haskellers.com/reverse/asn1-data) :arrow_heading_up: 18  
[dbus-core](https://packdeps.haskellers.com/reverse/dbus-core) :arrow_heading_up: 18  
[gtksourceview2](https://packdeps.haskellers.com/reverse/gtksourceview2) :arrow_heading_up: 18  
[ukrainian-phonetics-basic](https://packdeps.haskellers.com/reverse/ukrainian-phonetics-basic) :arrow_heading_up: 18  
[HGamer3D-Data](https://packdeps.haskellers.com/reverse/HGamer3D-Data) :arrow_heading_up: 17  
[certificate](https://packdeps.haskellers.com/reverse/certificate) :arrow_heading_up: 17  
[dbus-client](https://packdeps.haskellers.com/reverse/dbus-client) :arrow_heading_up: 17  
[gconf](https://packdeps.haskellers.com/reverse/gconf) :arrow_heading_up: 17  
[gtk-serialized-event](https://packdeps.haskellers.com/reverse/gtk-serialized-event) :arrow_heading_up: 17  
[cuda](https://packdeps.haskellers.com/reverse/cuda) :arrow_heading_up: 16  
[happstack-jmacro](https://packdeps.haskellers.com/reverse/happstack-jmacro) :arrow_heading_up: 16  
[manatee-core](https://packdeps.haskellers.com/reverse/manatee-core) :arrow_heading_up: 16  
[monads-fd](https://packdeps.haskellers.com/reverse/monads-fd) :arrow_heading_up: 16  
[tls-extra](https://packdeps.haskellers.com/reverse/tls-extra) :arrow_heading_up: 16  
[ADPfusion](https://packdeps.haskellers.com/reverse/ADPfusion) :arrow_heading_up: 15  
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
