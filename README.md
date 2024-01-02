### [haskell-updates build report from hydra](https://hydra.nixos.org/jobset/nixpkgs/haskell-updates)
*evaluation [1803310](https://hydra.nixos.org/eval/1803310) of nixpkgs commit [9ee264e](https://github.com/NixOS/nixpkgs/commits/9ee264e4b9f53e8ae10b02c73af4126925423f82) as of 2024-01-02 06:11 UTC*

🟡 **Potential issues** (and possibly [evaluation errors](https://hydra.nixos.org/jobset/nixpkgs/haskell-updates))
  * `maintained` jobset failed.
  * `mergeable` jobset is not finished.

#### Build summary

 | Platform | Failed ❌ | DependencyFailed ❗ | TimedOut ⌛🚫 | Unfinished ⏳ | Success ✅ | 
 | --- | --- | --- | --- | --- | --- | 
 | [aarch64-darwin 🍏](https://hydra.nixos.org/eval/1803310?filter=.aarch64-darwin) | 76 | 49 |  | 3 | 6654 | 
 | [aarch64-linux 📱](https://hydra.nixos.org/eval/1803310?filter=.aarch64-linux) | 13 | 4 | 3 | 3 | 6829 | 
 | [x86_64-darwin 🍎](https://hydra.nixos.org/eval/1803310?filter=.x86_64-darwin) | 61 | 26 | 1 | 3 | 6701 | 
 | [x86_64-linux 🐧](https://hydra.nixos.org/eval/1803310?filter=.x86_64-linux) | 4 | 4 |  | 9 | 6881 | 
#### Maintained Linux packages with build failure
- [ ] [ghc](https://hydra.nixos.org/eval/1803310?filter=ghc) @cdepillabout @expipiplus1 @guibou @maralorn @ncfavier @sternenseemann
  - [[📱✅]](https://hydra.nixos.org/build/243823957) [[🐧✅]](https://hydra.nixos.org/build/243803550) [haskellPackages](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.ghc)
  -  [[🐧❌]](https://hydra.nixos.org/build/245539364) [pkgsCross.ghcjs.haskell.packages.ghcHEAD](https://hydra.nixos.org/eval/1803310?filter=pkgsCross.ghcjs.haskell.packages.ghcHEAD.ghc)
  -  [[🐧❌]](https://hydra.nixos.org/build/245539299) [pkgsCross.ghcjs.haskellPackages](https://hydra.nixos.org/eval/1803310?filter=pkgsCross.ghcjs.haskellPackages.ghc)
- [ ] [weeder](https://hydra.nixos.org/eval/1803310?filter=weeder) @maralorn
  - [[📱✅]](https://hydra.nixos.org/build/245540141) [[🐧✅]](https://hydra.nixos.org/build/245539594) [haskell.packages.ghc8107](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc8107.weeder)
  - [[📱✅]](https://hydra.nixos.org/build/245540029) [[🐧✅]](https://hydra.nixos.org/build/245539792) [haskell.packages.ghc902](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc902.weeder)
  - [[📱❌]](https://hydra.nixos.org/build/245539668) [[🐧❌]](https://hydra.nixos.org/build/245540249) [haskell.packages.ghc925](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc925.weeder)
  - [[📱❌]](https://hydra.nixos.org/build/245539874) [[🐧❌]](https://hydra.nixos.org/build/245540103) [haskell.packages.ghc926](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc926.weeder)
  - [[📱❌]](https://hydra.nixos.org/build/245539765) [[🐧❌]](https://hydra.nixos.org/build/245539929) [haskell.packages.ghc927](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc927.weeder)
  - [[📱❌]](https://hydra.nixos.org/build/245540200) [[🐧❌]](https://hydra.nixos.org/build/245539741) [haskell.packages.ghc928](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc928.weeder)
  - [[📱✅]](https://hydra.nixos.org/build/245540188) [[🐧✅]](https://hydra.nixos.org/build/245539990) [haskell.packages.ghc945](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc945.weeder)
  - [[📱✅]](https://hydra.nixos.org/build/245539969) [[🐧✅]](https://hydra.nixos.org/build/245539508) [haskell.packages.ghc946](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc946.weeder)
  - [[📱✅]](https://hydra.nixos.org/build/245539697) [[🐧✅]](https://hydra.nixos.org/build/245539968) [haskell.packages.ghc947](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc947.weeder)
  - [[📱✅]](https://hydra.nixos.org/build/245539435) [[🐧✅]](https://hydra.nixos.org/build/245539393) [haskell.packages.ghc948](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc948.weeder)
  - [[📱✅]](https://hydra.nixos.org/build/245539857) [[🐧✅]](https://hydra.nixos.org/build/245539830) [haskell.packages.ghc963](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc963.weeder)
  - [[📱✅]](https://hydra.nixos.org/build/243806197) [[🐧✅]](https://hydra.nixos.org/build/243831881) [haskellPackages](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.weeder)
#### Maintained Linux packages with failed dependency
- [ ] [haskell-language-server](https://hydra.nixos.org/eval/1803310?filter=haskell-language-server) @maralorn
  - [[📱✅]](https://hydra.nixos.org/build/243821672) [[🐧✅]](https://hydra.nixos.org/build/243818880) [toplevel](https://hydra.nixos.org/eval/1803310?filter=haskell-language-server)
  - [[📱✅]](https://hydra.nixos.org/build/245540194) [[🐧✅]](https://hydra.nixos.org/build/245540279) [haskell.packages.ghc902](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc902.haskell-language-server)
  - [[📱✅]](https://hydra.nixos.org/build/245539658) [[🐧✅]](https://hydra.nixos.org/build/245539423) [haskell.packages.ghc925](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc925.haskell-language-server)
  - [[📱✅]](https://hydra.nixos.org/build/245540024) [[🐧✅]](https://hydra.nixos.org/build/245539494) [haskell.packages.ghc926](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc926.haskell-language-server)
  - [[📱✅]](https://hydra.nixos.org/build/245540054) [[🐧✅]](https://hydra.nixos.org/build/245539627) [haskell.packages.ghc927](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc927.haskell-language-server)
  - [[📱✅]](https://hydra.nixos.org/build/245540290) [[🐧✅]](https://hydra.nixos.org/build/245539499) [haskell.packages.ghc928](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc928.haskell-language-server)
  - [[📱✅]](https://hydra.nixos.org/build/245540175) [[🐧✅]](https://hydra.nixos.org/build/245540082) [haskell.packages.ghc945](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc945.haskell-language-server)
  - [[📱✅]](https://hydra.nixos.org/build/245539444) [[🐧✅]](https://hydra.nixos.org/build/245539484) [haskell.packages.ghc946](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc946.haskell-language-server)
  - [[📱✅]](https://hydra.nixos.org/build/245539716) [[🐧✅]](https://hydra.nixos.org/build/245539684) [haskell.packages.ghc947](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc947.haskell-language-server)
  - [[📱✅]](https://hydra.nixos.org/build/245540134) [[🐧✅]](https://hydra.nixos.org/build/245539404) [haskell.packages.ghc948](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc948.haskell-language-server)
  - [[📱✅]](https://hydra.nixos.org/build/245539422) [[🐧✅]](https://hydra.nixos.org/build/245539811) [haskell.packages.ghc963](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc963.haskell-language-server)
  - [[📱❗]](https://hydra.nixos.org/build/245540036) [[🐧❗]](https://hydra.nixos.org/build/245539384) [haskell.packages.ghc981](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc981.haskell-language-server)
  - [[📱✅]](https://hydra.nixos.org/build/243822380) [[🐧✅]](https://hydra.nixos.org/build/243808487) [haskellPackages](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.haskell-language-server)
- [ ] [[🐧❗]](https://hydra.nixos.org/build/245539273) [maintained](https://hydra.nixos.org/eval/1803310?filter=maintained) @cdepillabout @expipiplus1 @maralorn @ncfavier @sternenseemann
- [ ] [[🐧❗]](https://hydra.nixos.org/build/245539366) [staticHaskellPackages](https://hydra.nixos.org/eval/1803310?filter=staticHaskellPackages) @rnhmjoj @sternenseemann
#### Maintained Darwin packages with build failure
<details><summary>24 job(s) </summary>

- [ ] [[🍏❌]](https://hydra.nixos.org/build/244073873) [[🍎❌]](https://hydra.nixos.org/build/243830664) [haskellPackages.gcodehs](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.gcodehs) @sorki
- [ ] [ghc](https://hydra.nixos.org/eval/1803310?filter=ghc) @cdepillabout @expipiplus1 @guibou @maralorn @ncfavier @sternenseemann
  - [[🍏✅]](https://hydra.nixos.org/build/244074299) [[🍎✅]](https://hydra.nixos.org/build/243820106) [haskellPackages](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.ghc)
  - [[🍏❌]](https://hydra.nixos.org/build/245539331) [[🍎❌]](https://hydra.nixos.org/build/245539300) [pkgsCross.ghcjs.haskell.packages.ghcHEAD](https://hydra.nixos.org/eval/1803310?filter=pkgsCross.ghcjs.haskell.packages.ghcHEAD.ghc)
  - [[🍏❌]](https://hydra.nixos.org/build/245539338) [[🍎❌]](https://hydra.nixos.org/build/245539314) [pkgsCross.ghcjs.haskellPackages](https://hydra.nixos.org/eval/1803310?filter=pkgsCross.ghcjs.haskellPackages.ghc)
- [ ] [ghcHEAD](https://hydra.nixos.org/eval/1803310?filter=ghcHEAD) @cdepillabout @expipiplus1 @guibou @maralorn @ncfavier @sternenseemann
  - [[🍏❌]](https://hydra.nixos.org/build/244079851) [[🍎✅]](https://hydra.nixos.org/build/243823768) [haskell.compiler](https://hydra.nixos.org/eval/1803310?filter=haskell.compiler.ghcHEAD)
  - [[🍏❌]](https://hydra.nixos.org/build/244079202) [[🍎✅]](https://hydra.nixos.org/build/243804251) [haskell.compiler.native-bignum](https://hydra.nixos.org/eval/1803310?filter=haskell.compiler.native-bignum.ghcHEAD)
- [ ] [gitit](https://hydra.nixos.org/eval/1803310?filter=gitit) @Profpatsch @sternenseemann
  - [[🍏❌]](https://hydra.nixos.org/build/244078262) [[🍎✅]](https://hydra.nixos.org/build/243819120) [toplevel](https://hydra.nixos.org/eval/1803310?filter=gitit)
  - [[🍏✅]](https://hydra.nixos.org/build/244076217) [[🍎✅]](https://hydra.nixos.org/build/243824064) [haskellPackages](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.gitit)
- [ ] [weeder](https://hydra.nixos.org/eval/1803310?filter=weeder) @maralorn
  - [[🍏✅]](https://hydra.nixos.org/build/245540049) [[🍎✅]](https://hydra.nixos.org/build/245540027) [haskell.packages.ghc8107](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc8107.weeder)
  - [[🍏✅]](https://hydra.nixos.org/build/245539503) [[🍎✅]](https://hydra.nixos.org/build/245540051) [haskell.packages.ghc902](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc902.weeder)
  - [[🍏❌]](https://hydra.nixos.org/build/245540058) [[🍎❌]](https://hydra.nixos.org/build/245539769) [haskell.packages.ghc925](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc925.weeder)
  - [[🍏❌]](https://hydra.nixos.org/build/245540142) [[🍎❌]](https://hydra.nixos.org/build/245539577) [haskell.packages.ghc926](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc926.weeder)
  - [[🍏❌]](https://hydra.nixos.org/build/245539553) [[🍎❌]](https://hydra.nixos.org/build/245539579) [haskell.packages.ghc927](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc927.weeder)
  - [[🍏❌]](https://hydra.nixos.org/build/245539778) [[🍎❌]](https://hydra.nixos.org/build/245539879) [haskell.packages.ghc928](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc928.weeder)
  - [[🍏✅]](https://hydra.nixos.org/build/245539592) [[🍎✅]](https://hydra.nixos.org/build/245540270) [haskell.packages.ghc945](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc945.weeder)
  - [[🍏✅]](https://hydra.nixos.org/build/245539486) [[🍎✅]](https://hydra.nixos.org/build/245540254) [haskell.packages.ghc946](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc946.weeder)
  - [[🍏❗]](https://hydra.nixos.org/build/245540166) [[🍎✅]](https://hydra.nixos.org/build/245539802) [haskell.packages.ghc947](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc947.weeder)
  - [[🍏✅]](https://hydra.nixos.org/build/245539370) [[🍎✅]](https://hydra.nixos.org/build/245539868) [haskell.packages.ghc948](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc948.weeder)
  - [[🍏✅]](https://hydra.nixos.org/build/245539853) [[🍎✅]](https://hydra.nixos.org/build/245539899) [haskell.packages.ghc963](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc963.weeder)
  - [[🍏✅]](https://hydra.nixos.org/build/244073811) [[🍎✅]](https://hydra.nixos.org/build/243832211) [haskellPackages](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.weeder)
</details>

#### Maintained Darwin packages with failed dependency
<details><summary>54 job(s) </summary>

- [ ] [cabal-install](https://hydra.nixos.org/eval/1803310?filter=cabal-install) @sternenseemann
  - [[🍏✅]](https://hydra.nixos.org/build/244077735) [[🍎✅]](https://hydra.nixos.org/build/243818276) [toplevel](https://hydra.nixos.org/eval/1803310?filter=cabal-install)
  - [[🍏✅]](https://hydra.nixos.org/build/245540247) [[🍎✅]](https://hydra.nixos.org/build/245539382) [haskell.packages.ghc8107](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc8107.cabal-install)
  - [[🍏✅]](https://hydra.nixos.org/build/245540213) [[🍎✅]](https://hydra.nixos.org/build/245539816) [haskell.packages.ghc902](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc902.cabal-install)
  - [[🍏✅]](https://hydra.nixos.org/build/245540090) [[🍎✅]](https://hydra.nixos.org/build/245539786) [haskell.packages.ghc925](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc925.cabal-install)
  - [[🍏✅]](https://hydra.nixos.org/build/245540105) [[🍎✅]](https://hydra.nixos.org/build/245540203) [haskell.packages.ghc926](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc926.cabal-install)
  - [[🍏✅]](https://hydra.nixos.org/build/245539477) [[🍎✅]](https://hydra.nixos.org/build/245539628) [haskell.packages.ghc927](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc927.cabal-install)
  - [[🍏✅]](https://hydra.nixos.org/build/245539807) [[🍎✅]](https://hydra.nixos.org/build/245539735) [haskell.packages.ghc928](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc928.cabal-install)
  - [[🍏✅]](https://hydra.nixos.org/build/245539550) [[🍎✅]](https://hydra.nixos.org/build/245539516) [haskell.packages.ghc945](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc945.cabal-install)
  - [[🍏✅]](https://hydra.nixos.org/build/245539513) [[🍎✅]](https://hydra.nixos.org/build/245540285) [haskell.packages.ghc946](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc946.cabal-install)
  - [[🍏❗]](https://hydra.nixos.org/build/245540139) [[🍎✅]](https://hydra.nixos.org/build/245539989) [haskell.packages.ghc947](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc947.cabal-install)
  - [[🍏✅]](https://hydra.nixos.org/build/245539641) [[🍎✅]](https://hydra.nixos.org/build/245540196) [haskell.packages.ghc948](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc948.cabal-install)
  - [[🍏✅]](https://hydra.nixos.org/build/245540244) [[🍎✅]](https://hydra.nixos.org/build/245540219) [haskell.packages.ghc963](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc963.cabal-install)
  - [[🍏✅]](https://hydra.nixos.org/build/244075091) [[🍎✅]](https://hydra.nixos.org/build/243821130) [haskellPackages](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.cabal-install)
- [ ] [cabal2nix](https://hydra.nixos.org/eval/1803310?filter=cabal2nix) @sternenseemann
  - [[🍏✅]](https://hydra.nixos.org/build/244386801) [[🍎✅]](https://hydra.nixos.org/build/244386780) [toplevel](https://hydra.nixos.org/eval/1803310?filter=cabal2nix)
  - [[🍏✅]](https://hydra.nixos.org/build/245539534) [[🍎✅]](https://hydra.nixos.org/build/245539479) [haskell.packages.ghc8107](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc8107.cabal2nix)
  - [[🍏✅]](https://hydra.nixos.org/build/245539633) [[🍎✅]](https://hydra.nixos.org/build/245539450) [haskell.packages.ghc902](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc902.cabal2nix)
  - [[🍏✅]](https://hydra.nixos.org/build/245539798) [[🍎✅]](https://hydra.nixos.org/build/245540146) [haskell.packages.ghc925](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc925.cabal2nix)
  - [[🍏❗]](https://hydra.nixos.org/build/245539711) [[🍎✅]](https://hydra.nixos.org/build/245539740) [haskell.packages.ghc926](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc926.cabal2nix)
  - [[🍏✅]](https://hydra.nixos.org/build/245539434) [[🍎✅]](https://hydra.nixos.org/build/245540019) [haskell.packages.ghc927](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc927.cabal2nix)
  - [[🍏✅]](https://hydra.nixos.org/build/245539537) [[🍎✅]](https://hydra.nixos.org/build/245539858) [haskell.packages.ghc928](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc928.cabal2nix)
  - [[🍏✅]](https://hydra.nixos.org/build/245540302) [[🍎✅]](https://hydra.nixos.org/build/245540278) [haskell.packages.ghc945](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc945.cabal2nix)
  - [[🍏✅]](https://hydra.nixos.org/build/245540155) [[🍎✅]](https://hydra.nixos.org/build/245539758) [haskell.packages.ghc946](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc946.cabal2nix)
  - [[🍏❗]](https://hydra.nixos.org/build/245539995) [[🍎✅]](https://hydra.nixos.org/build/245540202) [haskell.packages.ghc947](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc947.cabal2nix)
  - [[🍏✅]](https://hydra.nixos.org/build/245540304) [[🍎✅]](https://hydra.nixos.org/build/245539863) [haskell.packages.ghc948](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc948.cabal2nix)
  - [[🍏✅]](https://hydra.nixos.org/build/245540084) [[🍎✅]](https://hydra.nixos.org/build/245540089) [haskell.packages.ghc963](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc963.cabal2nix)
  - [[🍏✅]](https://hydra.nixos.org/build/244076486) [[🍎✅]](https://hydra.nixos.org/build/243826178) [haskellPackages](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.cabal2nix)
- [ ] [haskell-language-server](https://hydra.nixos.org/eval/1803310?filter=haskell-language-server) @maralorn
  - [[🍏✅]](https://hydra.nixos.org/build/244079800) [[🍎✅]](https://hydra.nixos.org/build/243831902) [toplevel](https://hydra.nixos.org/eval/1803310?filter=haskell-language-server)
  - [[🍏✅]](https://hydra.nixos.org/build/245539801) [[🍎✅]](https://hydra.nixos.org/build/245540168) [haskell.packages.ghc902](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc902.haskell-language-server)
  - [[🍏✅]](https://hydra.nixos.org/build/245539717) [[🍎✅]](https://hydra.nixos.org/build/245540025) [haskell.packages.ghc925](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc925.haskell-language-server)
  - [[🍏❗]](https://hydra.nixos.org/build/245540235) [[🍎✅]](https://hydra.nixos.org/build/245539727) [haskell.packages.ghc926](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc926.haskell-language-server)
  - [[🍏✅]](https://hydra.nixos.org/build/245539975) [[🍎✅]](https://hydra.nixos.org/build/245539689) [haskell.packages.ghc927](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc927.haskell-language-server)
  - [[🍏✅]](https://hydra.nixos.org/build/245539544) [[🍎✅]](https://hydra.nixos.org/build/245539659) [haskell.packages.ghc928](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc928.haskell-language-server)
  - [[🍏✅]](https://hydra.nixos.org/build/245540023) [[🍎✅]](https://hydra.nixos.org/build/245539583) [haskell.packages.ghc945](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc945.haskell-language-server)
  - [[🍏✅]](https://hydra.nixos.org/build/245539845) [[🍎✅]](https://hydra.nixos.org/build/245539394) [haskell.packages.ghc946](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc946.haskell-language-server)
  - [[🍏❗]](https://hydra.nixos.org/build/245539685) [[🍎✅]](https://hydra.nixos.org/build/245539908) [haskell.packages.ghc947](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc947.haskell-language-server)
  - [[🍏✅]](https://hydra.nixos.org/build/245540275) [[🍎✅]](https://hydra.nixos.org/build/245539925) [haskell.packages.ghc948](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc948.haskell-language-server)
  - [[🍏✅]](https://hydra.nixos.org/build/245539947) [[🍎✅]](https://hydra.nixos.org/build/245540070) [haskell.packages.ghc963](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc963.haskell-language-server)
  - [[🍏❗]](https://hydra.nixos.org/build/245539507) [[🍎❗]](https://hydra.nixos.org/build/245540073) [haskell.packages.ghc981](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc981.haskell-language-server)
  - [[🍏✅]](https://hydra.nixos.org/build/244079729) [[🍎✅]](https://hydra.nixos.org/build/243830366) [haskellPackages](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.haskell-language-server)
- [ ] [hlint](https://hydra.nixos.org/eval/1803310?filter=hlint) @maralorn
  - [[🍏✅]](https://hydra.nixos.org/build/244074767) [[🍎✅]](https://hydra.nixos.org/build/243819350) [toplevel](https://hydra.nixos.org/eval/1803310?filter=hlint)
  - [[🍏✅]](https://hydra.nixos.org/build/245539454) [[🍎✅]](https://hydra.nixos.org/build/245539589) [haskell.packages.ghc902](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc902.hlint)
  - [[🍏✅]](https://hydra.nixos.org/build/245539915) [[🍎✅]](https://hydra.nixos.org/build/245539520) [haskell.packages.ghc925](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc925.hlint)
  - [[🍏❗]](https://hydra.nixos.org/build/245539443) [[🍎✅]](https://hydra.nixos.org/build/245540017) [haskell.packages.ghc926](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc926.hlint)
  - [[🍏✅]](https://hydra.nixos.org/build/245539855) [[🍎✅]](https://hydra.nixos.org/build/245539911) [haskell.packages.ghc927](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc927.hlint)
  - [[🍏✅]](https://hydra.nixos.org/build/245539787) [[🍎✅]](https://hydra.nixos.org/build/245539670) [haskell.packages.ghc928](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc928.hlint)
  - [[🍏✅]](https://hydra.nixos.org/build/245539706) [[🍎✅]](https://hydra.nixos.org/build/245539903) [haskell.packages.ghc945](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc945.hlint)
  - [[🍏✅]](https://hydra.nixos.org/build/245539755) [[🍎✅]](https://hydra.nixos.org/build/245539493) [haskell.packages.ghc946](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc946.hlint)
  - [[🍏❗]](https://hydra.nixos.org/build/245540172) [[🍎✅]](https://hydra.nixos.org/build/245539818) [haskell.packages.ghc947](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc947.hlint)
  - [[🍏✅]](https://hydra.nixos.org/build/245539676) [[🍎✅]](https://hydra.nixos.org/build/245539647) [haskell.packages.ghc948](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc948.hlint)
  - [[🍏✅]](https://hydra.nixos.org/build/244076740) [[🍎✅]](https://hydra.nixos.org/build/243815842) [haskellPackages](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.hlint)
</details>

#### Unmaintained packages with build failure
<details><summary>96 job(s) </summary>

- [ ] [[🍏❌]](https://hydra.nixos.org/build/244079216) [[📱✅]](https://hydra.nixos.org/build/243826568) [[🍎✅]](https://hydra.nixos.org/build/243822809) [[🐧✅]](https://hydra.nixos.org/build/243808943) [haskellPackages.di-core](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.di-core)  ⤴️ 7 | 11
- [ ] [[🍏❌]](https://hydra.nixos.org/build/244076170) [[📱✅]](https://hydra.nixos.org/build/243818629) [[🍎❌]](https://hydra.nixos.org/build/243816926) [[🐧✅]](https://hydra.nixos.org/build/243814242) [haskellPackages.fmt](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.fmt)  ⤴️ 6 | 24
- [ ] [[🍏❌]](https://hydra.nixos.org/build/244078004) [[📱✅]](https://hydra.nixos.org/build/243825960) [[🍎✅]](https://hydra.nixos.org/build/243811722) [[🐧✅]](https://hydra.nixos.org/build/243811336) [haskellPackages.hw-balancedparens](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.hw-balancedparens)  ⤴️ 4 | 19
- [ ] [[🍏❌]](https://hydra.nixos.org/build/244076650) [[📱✅]](https://hydra.nixos.org/build/243806137) [[🍎❌]](https://hydra.nixos.org/build/243830182) [[🐧✅]](https://hydra.nixos.org/build/243828133) [haskellPackages.lbfgs](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.lbfgs)  ⤴️ 3 | 3
- [ ] [[🍏❌]](https://hydra.nixos.org/build/244077624) [[📱✅]](https://hydra.nixos.org/build/243824490) [[🍎❌]](https://hydra.nixos.org/build/243829698) [[🐧✅]](https://hydra.nixos.org/build/243824387) [haskellPackages.HsSyck](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.HsSyck)  ⤴️ 1 | 10
- [ ] [[🍏❌]](https://hydra.nixos.org/build/244678646) [[📱⌛🚫]](https://hydra.nixos.org/build/244678471) [[🍎✅]](https://hydra.nixos.org/build/244678549) [[🐧✅]](https://hydra.nixos.org/build/244678923) [haskellPackages.telegram-bot-api](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.telegram-bot-api)  ⤴️ 1 | 4
- [ ] [[🍏❌]](https://hydra.nixos.org/build/244075040) [[📱✅]](https://hydra.nixos.org/build/243814977) [[🍎❌]](https://hydra.nixos.org/build/243826560) [[🐧✅]](https://hydra.nixos.org/build/243810525) [haskellPackages.posix-socket](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.posix-socket)  ⤴️ 1 | 2
- [ ] [[🍏✅]](https://hydra.nixos.org/build/244077296) [[📱❌]](https://hydra.nixos.org/build/243815838) [[🍎✅]](https://hydra.nixos.org/build/243816999) [[🐧✅]](https://hydra.nixos.org/build/243816375) [haskellPackages.postgresql-syntax](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.postgresql-syntax)  ⤴️ 1 | 2
- [ ] [[🍏❌]](https://hydra.nixos.org/build/244077700) [[📱✅]](https://hydra.nixos.org/build/243811706) [[🍎❌]](https://hydra.nixos.org/build/243808252) [[🐧✅]](https://hydra.nixos.org/build/243826637) [haskellPackages.async-refresh](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.async-refresh)  ⤴️ 1 | 1
- [ ] [[🍏❌]](https://hydra.nixos.org/build/244076361) [[📱✅]](https://hydra.nixos.org/build/243821147) [[🍎❌]](https://hydra.nixos.org/build/243812135) [[🐧✅]](https://hydra.nixos.org/build/243823744) [haskellPackages.gi-gdkx11](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.gi-gdkx11)  ⤴️ 1 | 1
- [ ] [[🍏❌]](https://hydra.nixos.org/build/244075157) [[📱❌]](https://hydra.nixos.org/build/243820650) [[🍎✅]](https://hydra.nixos.org/build/243822700) [[🐧✅]](https://hydra.nixos.org/build/243822873) [haskellPackages.nlopt-haskell](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.nlopt-haskell)  ⤴️ 1 | 1
- [ ] [[🍏❌]](https://hydra.nixos.org/build/244078913) [[📱✅]](https://hydra.nixos.org/build/243832157) [[🍎❌]](https://hydra.nixos.org/build/243824421) [[🐧✅]](https://hydra.nixos.org/build/243803924) [haskellPackages.openal-ffi](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.openal-ffi)  ⤴️ 1 | 1
- [ ] [[🍏❌]](https://hydra.nixos.org/build/244074800) [[📱✅]](https://hydra.nixos.org/build/243815860) [[🍎✅]](https://hydra.nixos.org/build/243818974) [[🐧✅]](https://hydra.nixos.org/build/243816424) [haskellPackages.sequence-formats](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.sequence-formats)  ⤴️ 1 | 1
- [ ] [[🍏✅]](https://hydra.nixos.org/build/244077620) [[📱❌]](https://hydra.nixos.org/build/243830659) [[🍎✅]](https://hydra.nixos.org/build/243821309) [[🐧✅]](https://hydra.nixos.org/build/243829610) [haskellPackages.stm-queue](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.stm-queue)  ⤴️ 1 | 1
- [ ] [[🍏❌]](https://hydra.nixos.org/build/244077067) [[📱✅]](https://hydra.nixos.org/build/243803741) [[🍎❌]](https://hydra.nixos.org/build/243812397) [[🐧✅]](https://hydra.nixos.org/build/243817752) [haskellPackages.sym](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.sym)  ⤴️ 1 | 1
- [ ] [[🍏✅]](https://hydra.nixos.org/build/244079150) [[📱❌]](https://hydra.nixos.org/build/243831253) [[🍎✅]](https://hydra.nixos.org/build/243804536) [[🐧✅]](https://hydra.nixos.org/build/243811979) [haskellPackages.freetype2](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.freetype2)  ⤴️ 0 | 12
- [ ] [[🍏❗]](https://hydra.nixos.org/build/244075578) [[📱❌]](https://hydra.nixos.org/build/243817735) [[🍎✅]](https://hydra.nixos.org/build/243824072) [[🐧✅]](https://hydra.nixos.org/build/243803524) [haskellPackages.hw-simd](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.hw-simd)  ⤴️ 0 | 9
- [ ] [[🍏❌]](https://hydra.nixos.org/build/244075863) [[📱✅]](https://hydra.nixos.org/build/243805739) [[🍎❌]](https://hydra.nixos.org/build/243829937) [[🐧✅]](https://hydra.nixos.org/build/243815162) [haskellPackages.pipes-zlib](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.pipes-zlib)  ⤴️ 0 | 5
- [ ] [[🍏❌]](https://hydra.nixos.org/build/244077952) [[📱✅]](https://hydra.nixos.org/build/243810690) [[🍎✅]](https://hydra.nixos.org/build/243826716) [[🐧✅]](https://hydra.nixos.org/build/243809169) [haskellPackages.rdtsc](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.rdtsc)  ⤴️ 0 | 4
- [ ] [[🍏❌]](https://hydra.nixos.org/build/244079032) [[📱✅]](https://hydra.nixos.org/build/243808969) [[🍎❌]](https://hydra.nixos.org/build/243815201) [[🐧✅]](https://hydra.nixos.org/build/243806503) [haskellPackages.error-codes](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.error-codes)  ⤴️ 0 | 3
- [ ] [[🍏❌]](https://hydra.nixos.org/build/244076397) [[📱✅]](https://hydra.nixos.org/build/243823081) [[🍎✅]](https://hydra.nixos.org/build/243805511) [[🐧✅]](https://hydra.nixos.org/build/243816871) [haskellPackages.folds](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.folds)  ⤴️ 0 | 3
- [ ] [[🍏❗]](https://hydra.nixos.org/build/244073896) [[📱❌]](https://hydra.nixos.org/build/243831148) [[🍎✅]](https://hydra.nixos.org/build/243823411) [[🐧✅]](https://hydra.nixos.org/build/243812146) [haskellPackages.picosat](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.picosat)  ⤴️ 0 | 3
- [ ] [[🍏❌]](https://hydra.nixos.org/build/244078409) [[📱✅]](https://hydra.nixos.org/build/243812479) [[🍎✅]](https://hydra.nixos.org/build/243807574) [[🐧✅]](https://hydra.nixos.org/build/243811394) [haskellPackages.LibZip](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.LibZip)  ⤴️ 0 | 2
- [ ] [[🍏❌]](https://hydra.nixos.org/build/244076626) [[📱✅]](https://hydra.nixos.org/build/243807980) [[🍎✅]](https://hydra.nixos.org/build/243825148) [[🐧✅]](https://hydra.nixos.org/build/243820967) [haskellPackages.bindings-levmar](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.bindings-levmar)  ⤴️ 0 | 2
- [ ] [[🍏❌]](https://hydra.nixos.org/build/244079510) [[📱✅]](https://hydra.nixos.org/build/243803781) [[🍎✅]](https://hydra.nixos.org/build/243831820) [[🐧✅]](https://hydra.nixos.org/build/243824666) [haskellPackages.rocksdb-haskell](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.rocksdb-haskell)  ⤴️ 0 | 2
- [ ] [[🍏❌]](https://hydra.nixos.org/build/244076982) [[📱✅]](https://hydra.nixos.org/build/243805592) [[🍎❌]](https://hydra.nixos.org/build/243817428) [[🐧✅]](https://hydra.nixos.org/build/243822922) [haskellPackages.HsHTSLib](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.HsHTSLib)  ⤴️ 0 | 1
- [ ] [[🍏❌]](https://hydra.nixos.org/build/244075976) [[📱✅]](https://hydra.nixos.org/build/243823314) [[🍎❌]](https://hydra.nixos.org/build/243821690) [[🐧✅]](https://hydra.nixos.org/build/243828438) [haskellPackages.diagrams-html5](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.diagrams-html5)  ⤴️ 0 | 1
- [ ] [[🍏❌]](https://hydra.nixos.org/build/244073765) [[📱✅]](https://hydra.nixos.org/build/243807357) [[🍎❌]](https://hydra.nixos.org/build/243825111) [[🐧✅]](https://hydra.nixos.org/build/243811818) [haskellPackages.hamid](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.hamid)  ⤴️ 0 | 1
- [ ] [[🍏✅]](https://hydra.nixos.org/build/244074836) [[📱✅]](https://hydra.nixos.org/build/243826536) [[🍎❌]](https://hydra.nixos.org/build/243816301) [[🐧✅]](https://hydra.nixos.org/build/243823609) [haskellPackages.hmatrix-morpheus](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.hmatrix-morpheus)  ⤴️ 0 | 1
- [ ] [[🍏❌]](https://hydra.nixos.org/build/244078527) [[📱✅]](https://hydra.nixos.org/build/243815192) [[🍎❌]](https://hydra.nixos.org/build/243807292) [[🐧✅]](https://hydra.nixos.org/build/243826391) [haskellPackages.huckleberry](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.huckleberry)  ⤴️ 0 | 1
- [ ] [[🍏❌]](https://hydra.nixos.org/build/244074076) [[📱✅]](https://hydra.nixos.org/build/243807527) [[🍎❌]](https://hydra.nixos.org/build/243828200) [[🐧✅]](https://hydra.nixos.org/build/243825830) [haskellPackages.om-time](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.om-time)  ⤴️ 0 | 1
- [ ] [[🍏❌]](https://hydra.nixos.org/build/244079629) [[📱✅]](https://hydra.nixos.org/build/243820315) [[🍎✅]](https://hydra.nixos.org/build/243824264) [[🐧✅]](https://hydra.nixos.org/build/243824727) [haskellPackages.pgp-wordlist](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.pgp-wordlist)  ⤴️ 0 | 1
- [ ] [[🍏❌]](https://hydra.nixos.org/build/244075220) [[📱✅]](https://hydra.nixos.org/build/243813123) [[🍎❌]](https://hydra.nixos.org/build/243825742) [[🐧✅]](https://hydra.nixos.org/build/243826541) [haskellPackages.select](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.select)  ⤴️ 0 | 1
- [ ] [[🍏✅]](https://hydra.nixos.org/build/244076046) [[📱✅]](https://hydra.nixos.org/build/243830763) [[🍎❌]](https://hydra.nixos.org/build/243815383) [[🐧✅]](https://hydra.nixos.org/build/243828504) [haskellPackages.sydtest-process](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.sydtest-process)  ⤴️ 0 | 1
- [ ] [[🍏❌]](https://hydra.nixos.org/build/244079678) [[📱✅]](https://hydra.nixos.org/build/243807738) [[🍎❌]](https://hydra.nixos.org/build/243823243) [[🐧✅]](https://hydra.nixos.org/build/243808758) [haskellPackages.sysinfo](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.sysinfo)  ⤴️ 0 | 1
- [ ] [[🍏✅]](https://hydra.nixos.org/build/244077947) [[📱✅]](https://hydra.nixos.org/build/243809828) [[🍎❌]](https://hydra.nixos.org/build/243824883) [[🐧✅]](https://hydra.nixos.org/build/243810710) [haskellPackages.FractalArt](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.FractalArt) 
- [ ] [[🍏✅]](https://hydra.nixos.org/build/244079880) [[📱❌]](https://hydra.nixos.org/build/243818617) [[🍎✅]](https://hydra.nixos.org/build/243829961) [[🐧✅]](https://hydra.nixos.org/build/243816454) [haskellPackages.HsASA](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.HsASA) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/244076569) [[📱✅]](https://hydra.nixos.org/build/243825787) [[🍎❌]](https://hydra.nixos.org/build/243804298) [[🐧✅]](https://hydra.nixos.org/build/243822085) [haskellPackages.al](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.al) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/244075076) [[📱✅]](https://hydra.nixos.org/build/243825297) [[🍎✅]](https://hydra.nixos.org/build/243811962) [[🐧✅]](https://hydra.nixos.org/build/243820008) [haskellPackages.amazonka-resourcegroups](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.amazonka-resourcegroups) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/244073630) [[📱✅]](https://hydra.nixos.org/build/243805932) [[🍎❌]](https://hydra.nixos.org/build/243818277) [[🐧✅]](https://hydra.nixos.org/build/243813631) [haskellPackages.env-extra](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.env-extra) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/244075612) [[📱✅]](https://hydra.nixos.org/build/243823218) [[🍎❌]](https://hydra.nixos.org/build/243806169) [[🐧✅]](https://hydra.nixos.org/build/243803545) [haskellPackages.epub-metadata](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.epub-metadata) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/244078516) [[📱✅]](https://hydra.nixos.org/build/243807211) [[🍎✅]](https://hydra.nixos.org/build/243825311) [[🐧✅]](https://hydra.nixos.org/build/243819173) [haskellPackages.executable-hash](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.executable-hash) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/244077514) [[📱✅]](https://hydra.nixos.org/build/243807749) [[🍎❌]](https://hydra.nixos.org/build/243806008) [[🐧✅]](https://hydra.nixos.org/build/243804649) [haskellPackages.exinst-base](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.exinst-base) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/244073869) [[📱✅]](https://hydra.nixos.org/build/243830314) [[🍎❌]](https://hydra.nixos.org/build/243823569) [[🐧✅]](https://hydra.nixos.org/build/243812194) [haskellPackages.float128](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.float128) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/244078995) [[📱✅]](https://hydra.nixos.org/build/243809580) [[🍎❌]](https://hydra.nixos.org/build/243824084) [[🐧✅]](https://hydra.nixos.org/build/243817242) [haskellPackages.fudgets](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.fudgets) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/244078944) [[📱✅]](https://hydra.nixos.org/build/243829891) [[🍎❌]](https://hydra.nixos.org/build/243827774) [[🐧✅]](https://hydra.nixos.org/build/243820807) [haskellPackages.genvalidity-dirforest](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.genvalidity-dirforest) 
- [ ] [ghc-tags](https://hydra.nixos.org/eval/1803310?filter=ghc-tags) 
  - [[🍏✅]](https://hydra.nixos.org/build/245539436) [[📱✅]](https://hydra.nixos.org/build/245540306) [[🍎✅]](https://hydra.nixos.org/build/245539381) [[🐧✅]](https://hydra.nixos.org/build/245539601) [haskell.packages.ghc8107](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc8107.ghc-tags)
  - [[🍏❌]](https://hydra.nixos.org/build/245539561) [[📱❌]](https://hydra.nixos.org/build/245540055) [[🍎❌]](https://hydra.nixos.org/build/245539424) [[🐧❌]](https://hydra.nixos.org/build/245540011) [haskell.packages.ghc902](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc902.ghc-tags)
  - [[🍏✅]](https://hydra.nixos.org/build/245539644) [[📱✅]](https://hydra.nixos.org/build/245539781) [[🍎✅]](https://hydra.nixos.org/build/245539425) [[🐧✅]](https://hydra.nixos.org/build/245539977) [haskell.packages.ghc925](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc925.ghc-tags)
  - [[🍏❗]](https://hydra.nixos.org/build/245540088) [[📱✅]](https://hydra.nixos.org/build/245540216) [[🍎✅]](https://hydra.nixos.org/build/245539536) [[🐧✅]](https://hydra.nixos.org/build/245539510) [haskell.packages.ghc926](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc926.ghc-tags)
  - [[🍏✅]](https://hydra.nixos.org/build/245539852) [[📱✅]](https://hydra.nixos.org/build/245539429) [[🍎✅]](https://hydra.nixos.org/build/245539815) [[🐧✅]](https://hydra.nixos.org/build/245539981) [haskell.packages.ghc927](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc927.ghc-tags)
  - [[🍏✅]](https://hydra.nixos.org/build/245539598) [[📱✅]](https://hydra.nixos.org/build/245539662) [[🍎✅]](https://hydra.nixos.org/build/245539867) [[🐧✅]](https://hydra.nixos.org/build/245539700) [haskell.packages.ghc928](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc928.ghc-tags)
  - [[🍏✅]](https://hydra.nixos.org/build/245539974) [[📱✅]](https://hydra.nixos.org/build/245539622) [[🍎✅]](https://hydra.nixos.org/build/245539756) [[🐧✅]](https://hydra.nixos.org/build/245539419) [haskell.packages.ghc963](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc963.ghc-tags)
- [ ] [[🍏❌]](https://hydra.nixos.org/build/244079001) [[🍎❌]](https://hydra.nixos.org/build/243811244) [haskellPackages.gi-gtkosxapplication](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.gi-gtkosxapplication) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/244075241) [[🍎❌]](https://hydra.nixos.org/build/243814613) [haskellPackages.gtk-mac-integration](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.gtk-mac-integration) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/244073884) [[📱✅]](https://hydra.nixos.org/build/243809795) [[🍎❌]](https://hydra.nixos.org/build/243823527) [[🐧✅]](https://hydra.nixos.org/build/243806126) [haskellPackages.gtk-traymanager](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.gtk-traymanager) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/244074500) [[🍎❌]](https://hydra.nixos.org/build/243815558) [haskellPackages.gtk3-mac-integration](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.gtk3-mac-integration) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/244074729) [[📱✅]](https://hydra.nixos.org/build/243804563) [[🍎❌]](https://hydra.nixos.org/build/243808049) [[🐧✅]](https://hydra.nixos.org/build/243812262) [haskellPackages.hdf5-lite](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.hdf5-lite) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/244079776) [[📱✅]](https://hydra.nixos.org/build/243808881) [[🍎❌]](https://hydra.nixos.org/build/243816620) [[🐧✅]](https://hydra.nixos.org/build/243812439) [haskellPackages.highlight](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.highlight) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/244073315) [[📱✅]](https://hydra.nixos.org/build/243827933) [[🍎❌]](https://hydra.nixos.org/build/243828932) [[🐧✅]](https://hydra.nixos.org/build/243817567) [haskellPackages.hinotify-conduit](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.hinotify-conduit) 
- [ ] [[🍏✅]](https://hydra.nixos.org/build/244078408) [[📱❌]](https://hydra.nixos.org/build/243810542) [[🍎✅]](https://hydra.nixos.org/build/243830913) [[🐧✅]](https://hydra.nixos.org/build/243823776) [haskellPackages.hssh](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.hssh) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/244077085) [[📱✅]](https://hydra.nixos.org/build/243815927) [[🍎❌]](https://hydra.nixos.org/build/243825189) [[🐧✅]](https://hydra.nixos.org/build/243820874) [haskellPackages.hssourceinfo](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.hssourceinfo) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/244079391) [[📱✅]](https://hydra.nixos.org/build/243820090) [[🍎❌]](https://hydra.nixos.org/build/243806366) [[🐧✅]](https://hydra.nixos.org/build/243828341) [haskellPackages.hunspell-hs](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.hunspell-hs) 
- [ ] [[🍎❌]](https://hydra.nixos.org/build/243812987) [[🐧✅]](https://hydra.nixos.org/build/243830177) [haskellPackages.inline-asm](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.inline-asm) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/244077887) [[📱✅]](https://hydra.nixos.org/build/243805347) [[🍎❌]](https://hydra.nixos.org/build/243820672) [[🐧✅]](https://hydra.nixos.org/build/243817960) [haskellPackages.interprocess](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.interprocess) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/244075154) [[📱✅]](https://hydra.nixos.org/build/243812494) [[🍎❌]](https://hydra.nixos.org/build/243811926) [[🐧✅]](https://hydra.nixos.org/build/243814396) [haskellPackages.ipcvar](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.ipcvar) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/244075206) [[📱✅]](https://hydra.nixos.org/build/243829815) [[🍎❌]](https://hydra.nixos.org/build/243811539) [[🐧✅]](https://hydra.nixos.org/build/243829555) [haskellPackages.kmonad](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.kmonad) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/244073859) [[🍎❌]](https://hydra.nixos.org/build/243815698) [haskellPackages.kqueue](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.kqueue) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/244078140) [[📱✅]](https://hydra.nixos.org/build/243810045) [[🍎✅]](https://hydra.nixos.org/build/243814579) [[🐧✅]](https://hydra.nixos.org/build/243817962) [haskellPackages.leveldb-haskell-fork](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.leveldb-haskell-fork) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/244074830) [[📱✅]](https://hydra.nixos.org/build/243831626) [[🍎❌]](https://hydra.nixos.org/build/243811513) [[🐧✅]](https://hydra.nixos.org/build/243805084) [haskellPackages.linux-framebuffer](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.linux-framebuffer) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/244077392) [[📱✅]](https://hydra.nixos.org/build/243826620) [[🍎❌]](https://hydra.nixos.org/build/243811627) [[🐧✅]](https://hydra.nixos.org/build/243817931) [haskellPackages.mediawiki2latex](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.mediawiki2latex) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/244078506) [[📱✅]](https://hydra.nixos.org/build/243829479) [[🍎❌]](https://hydra.nixos.org/build/243826992) [[🐧✅]](https://hydra.nixos.org/build/243823992) [haskellPackages.memzero](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.memzero) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/244678756) [[📱✅]](https://hydra.nixos.org/build/244678354) [[🍎❌]](https://hydra.nixos.org/build/244678988) [[🐧✅]](https://hydra.nixos.org/build/244678681) [haskellPackages.nix-serve-ng](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.nix-serve-ng) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/244079283) [[📱✅]](https://hydra.nixos.org/build/243821185) [[🍎❌]](https://hydra.nixos.org/build/243823978) [[🐧✅]](https://hydra.nixos.org/build/243828295) [haskellPackages.persistent-pagination](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.persistent-pagination) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/244073674) [[📱✅]](https://hydra.nixos.org/build/243830645) [[🍎❌]](https://hydra.nixos.org/build/243814459) [[🐧✅]](https://hydra.nixos.org/build/243822056) [haskellPackages.phatsort](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.phatsort) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/244079612) [[📱✅]](https://hydra.nixos.org/build/243806491) [[🍎❌]](https://hydra.nixos.org/build/243829074) [[🐧✅]](https://hydra.nixos.org/build/243812573) [haskellPackages.ping-wrapper](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.ping-wrapper) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/244078674) [[📱✅]](https://hydra.nixos.org/build/243827238) [[🍎❌]](https://hydra.nixos.org/build/243805601) [[🐧✅]](https://hydra.nixos.org/build/243814653) [haskellPackages.posix-timer](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.posix-timer) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/244073486) [[📱✅]](https://hydra.nixos.org/build/243823979) [[🍎❌]](https://hydra.nixos.org/build/243826385) [[🐧✅]](https://hydra.nixos.org/build/243828558) [haskellPackages.procex](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.procex) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/244074489) [[📱✅]](https://hydra.nixos.org/build/243831585) [[🍎❌]](https://hydra.nixos.org/build/243828037) [[🐧✅]](https://hydra.nixos.org/build/243817654) [haskellPackages.pthread](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.pthread) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/244078403) [[📱✅]](https://hydra.nixos.org/build/243814757) [[🍎✅]](https://hydra.nixos.org/build/243806970) [[🐧✅]](https://hydra.nixos.org/build/243813062) [haskellPackages.rdtsc-enolan](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.rdtsc-enolan) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/244078520) [[📱✅]](https://hydra.nixos.org/build/243815128) [[🍎❌]](https://hydra.nixos.org/build/243805448) [[🐧✅]](https://hydra.nixos.org/build/243826662) [haskellPackages.sandwich-webdriver](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.sandwich-webdriver) 
- [ ] [[🍏✅]](https://hydra.nixos.org/build/244076332) [[📱❌]](https://hydra.nixos.org/build/243828757) [[🍎✅]](https://hydra.nixos.org/build/243813195) [[🐧✅]](https://hydra.nixos.org/build/243807904) [haskellPackages.simdutf](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.simdutf) 
- [ ] [[🍏✅]](https://hydra.nixos.org/build/244080089) [[📱❌]](https://hydra.nixos.org/build/243815946) [[🍎✅]](https://hydra.nixos.org/build/243818544) [[🐧✅]](https://hydra.nixos.org/build/243825545) [haskellPackages.sqlite-easy](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.sqlite-easy) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/244079843) [[📱✅]](https://hydra.nixos.org/build/243819251) [[🍎❌]](https://hydra.nixos.org/build/243819457) [[🐧✅]](https://hydra.nixos.org/build/243804803) [haskellPackages.tailfile-hinotify](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.tailfile-hinotify) 
- [ ] [[📱❌]](https://hydra.nixos.org/build/243808165) [[🐧✅]](https://hydra.nixos.org/build/243807687) [haskellPackages.tasty-papi](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.tasty-papi) 
- [ ] [terminfo](https://hydra.nixos.org/eval/1803310?filter=terminfo) 
  - [[🐧✅]](https://hydra.nixos.org/build/245539351) [pkgsStatic.haskell.packages.native-bignum.ghc948](https://hydra.nixos.org/eval/1803310?filter=pkgsStatic.haskell.packages.native-bignum.ghc948.terminfo)
  - [[🐧❌]](https://hydra.nixos.org/build/245539288) [pkgsStatic.haskell.packages.native-bignum.ghc981](https://hydra.nixos.org/eval/1803310?filter=pkgsStatic.haskell.packages.native-bignum.ghc981.terminfo)
  - [[🐧✅]](https://hydra.nixos.org/build/245539315) [pkgsStatic.haskellPackages](https://hydra.nixos.org/eval/1803310?filter=pkgsStatic.haskellPackages.terminfo)
- [ ] [[🍏❌]](https://hydra.nixos.org/build/244076734) [[📱✅]](https://hydra.nixos.org/build/243808536) [[🍎✅]](https://hydra.nixos.org/build/243809702) [[🐧✅]](https://hydra.nixos.org/build/243821711) [haskellPackages.unix-simple](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.unix-simple) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/244077167) [[📱✅]](https://hydra.nixos.org/build/243823268) [[🍎✅]](https://hydra.nixos.org/build/243809646) [[🐧✅]](https://hydra.nixos.org/build/243805721) [haskellPackages.x86-64bit](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.x86-64bit) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/244077894) [[📱✅]](https://hydra.nixos.org/build/243811908) [[🍎❌]](https://hydra.nixos.org/build/243832260) [[🐧✅]](https://hydra.nixos.org/build/243813042) [haskellPackages.xmonad-utils](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.xmonad-utils) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/244077480) [[📱✅]](https://hydra.nixos.org/build/243805040) [[🍎❌]](https://hydra.nixos.org/build/243809393) [[🐧✅]](https://hydra.nixos.org/build/243808337) [haskellPackages.yoga](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.yoga) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/244077201) [[📱✅]](https://hydra.nixos.org/build/243808867) [[🍎❌]](https://hydra.nixos.org/build/243811352) [[🐧✅]](https://hydra.nixos.org/build/243813464) [haskellPackages.zot](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.zot) 
- [ ] [[🍏❌]](https://hydra.nixos.org/build/244076831) [[📱✅]](https://hydra.nixos.org/build/243813652) [[🍎❌]](https://hydra.nixos.org/build/243827242) [[🐧✅]](https://hydra.nixos.org/build/243822748) [haskellPackages.zxcvbn-c](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.zxcvbn-c) 
</details>

#### Unmaintained packages with failed dependency
<details><summary>86 job(s) </summary>

- [ ] [[🍏❗]](https://hydra.nixos.org/build/244078261) [[📱✅]](https://hydra.nixos.org/build/243816392) [[🍎✅]](https://hydra.nixos.org/build/243819966) [[🐧✅]](https://hydra.nixos.org/build/243826377) [haskellPackages.di-handle](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.di-handle)  ⤴️ 5 | 9
- [ ] [[🍏❗]](https://hydra.nixos.org/build/244074961) [[📱✅]](https://hydra.nixos.org/build/243812132) [[🍎✅]](https://hydra.nixos.org/build/243821058) [[🐧✅]](https://hydra.nixos.org/build/243809751) [haskellPackages.di-monad](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.di-monad)  ⤴️ 5 | 9
- [ ] [[🍏❗]](https://hydra.nixos.org/build/244073135) [[📱✅]](https://hydra.nixos.org/build/243812102) [[🍎✅]](https://hydra.nixos.org/build/243807017) [[🐧✅]](https://hydra.nixos.org/build/243807724) [haskellPackages.di-df1](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.di-df1)  ⤴️ 4 | 8
- [ ] [[🍏❗]](https://hydra.nixos.org/build/244075527) [[📱✅]](https://hydra.nixos.org/build/243827841) [[🍎✅]](https://hydra.nixos.org/build/243813756) [[🐧✅]](https://hydra.nixos.org/build/243815352) [haskellPackages.hw-rankselect](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.hw-rankselect)  ⤴️ 3 | 18
- [ ] [hpack](https://hydra.nixos.org/eval/1803310?filter=hpack)  ⤴️ 3 | 16
  - [[🍏✅]](https://hydra.nixos.org/build/244077768) [[📱✅]](https://hydra.nixos.org/build/243805163) [[🍎✅]](https://hydra.nixos.org/build/243814099) [[🐧✅]](https://hydra.nixos.org/build/243804710) [toplevel](https://hydra.nixos.org/eval/1803310?filter=hpack)
  - [[🍏✅]](https://hydra.nixos.org/build/245540276) [[📱✅]](https://hydra.nixos.org/build/245540081) [[🍎✅]](https://hydra.nixos.org/build/245539671) [[🐧✅]](https://hydra.nixos.org/build/245539971) [haskell.packages.ghc8107](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc8107.hpack)
  - [[🍏✅]](https://hydra.nixos.org/build/245539675) [[📱✅]](https://hydra.nixos.org/build/245540261) [[🍎✅]](https://hydra.nixos.org/build/245539902) [[🐧✅]](https://hydra.nixos.org/build/245540016) [haskell.packages.ghc902](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc902.hpack)
  - [[🍏✅]](https://hydra.nixos.org/build/245539455) [[📱✅]](https://hydra.nixos.org/build/245539414) [[🍎✅]](https://hydra.nixos.org/build/245539643) [[🐧✅]](https://hydra.nixos.org/build/245540238) [haskell.packages.ghc925](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc925.hpack)
  - [[🍏❗]](https://hydra.nixos.org/build/245540068) [[📱✅]](https://hydra.nixos.org/build/245539930) [[🍎✅]](https://hydra.nixos.org/build/245539848) [[🐧✅]](https://hydra.nixos.org/build/245539502) [haskell.packages.ghc926](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc926.hpack)
  - [[🍏✅]](https://hydra.nixos.org/build/245540066) [[📱✅]](https://hydra.nixos.org/build/245540153) [[🍎✅]](https://hydra.nixos.org/build/245539448) [[🐧✅]](https://hydra.nixos.org/build/245540296) [haskell.packages.ghc927](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc927.hpack)
  - [[🍏✅]](https://hydra.nixos.org/build/245539834) [[📱✅]](https://hydra.nixos.org/build/245539654) [[🍎✅]](https://hydra.nixos.org/build/245539841) [[🐧✅]](https://hydra.nixos.org/build/245540186) [haskell.packages.ghc928](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc928.hpack)
  - [[🍏✅]](https://hydra.nixos.org/build/245540246) [[📱✅]](https://hydra.nixos.org/build/245540207) [[🍎✅]](https://hydra.nixos.org/build/245540078) [[🐧✅]](https://hydra.nixos.org/build/245539746) [haskell.packages.ghc945](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc945.hpack)
  - [[🍏✅]](https://hydra.nixos.org/build/245539680) [[📱✅]](https://hydra.nixos.org/build/245539666) [[🍎✅]](https://hydra.nixos.org/build/245540132) [[🐧✅]](https://hydra.nixos.org/build/245539615) [haskell.packages.ghc946](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc946.hpack)
  - [[🍏❗]](https://hydra.nixos.org/build/245539920) [[📱✅]](https://hydra.nixos.org/build/245539838) [[🍎✅]](https://hydra.nixos.org/build/245539608) [[🐧✅]](https://hydra.nixos.org/build/245540161) [haskell.packages.ghc947](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc947.hpack)
  - [[🍏✅]](https://hydra.nixos.org/build/245540156) [[📱✅]](https://hydra.nixos.org/build/245539595) [[🍎✅]](https://hydra.nixos.org/build/245539521) [[🐧✅]](https://hydra.nixos.org/build/245539569) [haskell.packages.ghc948](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc948.hpack)
  - [[🍏✅]](https://hydra.nixos.org/build/245540072) [[📱✅]](https://hydra.nixos.org/build/245539587) [[🍎✅]](https://hydra.nixos.org/build/245540006) [[🐧✅]](https://hydra.nixos.org/build/245539540) [haskell.packages.ghc963](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc963.hpack)
  - [[🍏✅]](https://hydra.nixos.org/build/244073586) [[📱✅]](https://hydra.nixos.org/build/243806247) [[🍎✅]](https://hydra.nixos.org/build/243815951) [[🐧✅]](https://hydra.nixos.org/build/243819597) [haskellPackages](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.hpack)
- [ ] [hoogle](https://hydra.nixos.org/eval/1803310?filter=hoogle)  ⤴️ 2 | 4
  - [[🍏✅]](https://hydra.nixos.org/build/245539819) [[📱✅]](https://hydra.nixos.org/build/245539918) [[🍎✅]](https://hydra.nixos.org/build/245540004) [[🐧✅]](https://hydra.nixos.org/build/245539408) [haskell.packages.ghc8107](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc8107.hoogle)
  - [[🍏❗]](https://hydra.nixos.org/build/245540110) [[📱✅]](https://hydra.nixos.org/build/245540165) [[🍎✅]](https://hydra.nixos.org/build/245540085) [[🐧✅]](https://hydra.nixos.org/build/245540208) [haskell.packages.ghc902](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc902.hoogle)
  - [[🍏✅]](https://hydra.nixos.org/build/245539896) [[📱✅]](https://hydra.nixos.org/build/245539991) [[🍎✅]](https://hydra.nixos.org/build/245539533) [[🐧✅]](https://hydra.nixos.org/build/245539907) [haskell.packages.ghc925](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc925.hoogle)
  - [[🍏❗]](https://hydra.nixos.org/build/245540034) [[📱✅]](https://hydra.nixos.org/build/245539776) [[🍎✅]](https://hydra.nixos.org/build/245540038) [[🐧✅]](https://hydra.nixos.org/build/245539961) [haskell.packages.ghc926](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc926.hoogle)
  - [[🍏✅]](https://hydra.nixos.org/build/245540171) [[📱✅]](https://hydra.nixos.org/build/245539861) [[🍎✅]](https://hydra.nixos.org/build/245539984) [[🐧✅]](https://hydra.nixos.org/build/245539809) [haskell.packages.ghc927](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc927.hoogle)
  - [[🍏✅]](https://hydra.nixos.org/build/245539638) [[📱✅]](https://hydra.nixos.org/build/245539872) [[🍎✅]](https://hydra.nixos.org/build/245539933) [[🐧✅]](https://hydra.nixos.org/build/245539401) [haskell.packages.ghc928](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc928.hoogle)
  - [[🍏✅]](https://hydra.nixos.org/build/245540101) [[📱✅]](https://hydra.nixos.org/build/245540190) [[🍎✅]](https://hydra.nixos.org/build/245539672) [[🐧✅]](https://hydra.nixos.org/build/245539560) [haskell.packages.ghc945](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc945.hoogle)
  - [[🍏✅]](https://hydra.nixos.org/build/245540064) [[📱✅]](https://hydra.nixos.org/build/245539831) [[🍎✅]](https://hydra.nixos.org/build/245539730) [[🐧✅]](https://hydra.nixos.org/build/245539724) [haskell.packages.ghc946](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc946.hoogle)
  - [[🍏❗]](https://hydra.nixos.org/build/245539707) [[📱✅]](https://hydra.nixos.org/build/245540289) [[🍎✅]](https://hydra.nixos.org/build/245540201) [[🐧✅]](https://hydra.nixos.org/build/245539626) [haskell.packages.ghc947](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc947.hoogle)
  - [[🍏✅]](https://hydra.nixos.org/build/245540121) [[📱✅]](https://hydra.nixos.org/build/245539791) [[🍎✅]](https://hydra.nixos.org/build/245540042) [[🐧✅]](https://hydra.nixos.org/build/245540079) [haskell.packages.ghc948](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc948.hoogle)
  - [[🍏✅]](https://hydra.nixos.org/build/244678850) [[📱✅]](https://hydra.nixos.org/build/244678964) [[🍎✅]](https://hydra.nixos.org/build/244678313) [[🐧✅]](https://hydra.nixos.org/build/244678218) [haskellPackages](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.hoogle)
- [ ] [[🍏❗]](https://hydra.nixos.org/build/244074232) [[📱✅]](https://hydra.nixos.org/build/243804626) [[🍎❗]](https://hydra.nixos.org/build/243825963) [[🐧✅]](https://hydra.nixos.org/build/243830953) [haskellPackages.numeric-optimization](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.numeric-optimization)  ⤴️ 2 | 2
- [ ] [[🍏❗]](https://hydra.nixos.org/build/244078161) [[📱✅]](https://hydra.nixos.org/build/243827247) [[🍎❗]](https://hydra.nixos.org/build/243804746) [[🐧✅]](https://hydra.nixos.org/build/243825877) [haskellPackages.nyan-interpolation-core](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.nyan-interpolation-core)  ⤴️ 2 | 2
- [ ] [[🍏❗]](https://hydra.nixos.org/build/244077405) [[📱✅]](https://hydra.nixos.org/build/243809432) [[🍎✅]](https://hydra.nixos.org/build/243806463) [[🐧✅]](https://hydra.nixos.org/build/243814809) [haskellPackages.moto](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.moto)  ⤴️ 1 | 1
- [ ] [[🍏❗]](https://hydra.nixos.org/build/244077803) [[📱✅]](https://hydra.nixos.org/build/243819324) [[🍎❗]](https://hydra.nixos.org/build/243820328) [[🐧✅]](https://hydra.nixos.org/build/243819698) [haskellPackages.yaml-light](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.yaml-light)  ⤴️ 0 | 5
- [ ] [[🍏❗]](https://hydra.nixos.org/build/244075783) [[📱✅]](https://hydra.nixos.org/build/243813839) [[🍎✅]](https://hydra.nixos.org/build/243823040) [[🐧✅]](https://hydra.nixos.org/build/243817386) [haskellPackages.di-polysemy](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.di-polysemy)  ⤴️ 0 | 4
- [ ] [[🍏❗]](https://hydra.nixos.org/build/244678560) [[📱⌛🚫]](https://hydra.nixos.org/build/244679029) [[🍎✅]](https://hydra.nixos.org/build/244678795) [[🐧✅]](https://hydra.nixos.org/build/244678149) [haskellPackages.telegram-bot-simple](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.telegram-bot-simple)  ⤴️ 0 | 3
- [ ] [[🍏❗]](https://hydra.nixos.org/build/244078148) [[📱✅]](https://hydra.nixos.org/build/243822519) [[🍎✅]](https://hydra.nixos.org/build/243829828) [[🐧✅]](https://hydra.nixos.org/build/243817851) [haskellPackages.di](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.di)  ⤴️ 0 | 2
- [ ] [[🍏❗]](https://hydra.nixos.org/build/244078524) [[📱✅]](https://hydra.nixos.org/build/243813944) [[🍎✅]](https://hydra.nixos.org/build/243807535) [[🐧✅]](https://hydra.nixos.org/build/243820306) [haskellPackages.hw-eliasfano](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.hw-eliasfano)  ⤴️ 0 | 1
- [ ] [[🍏❗]](https://hydra.nixos.org/build/244075125) [[📱✅]](https://hydra.nixos.org/build/243815279) [[🍎✅]](https://hydra.nixos.org/build/243823894) [[🐧✅]](https://hydra.nixos.org/build/243818126) [haskellPackages.hw-succinct](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.hw-succinct)  ⤴️ 0 | 1
- [ ] [[🍏❗]](https://hydra.nixos.org/build/244078532) [[📱✅]](https://hydra.nixos.org/build/243812318) [[🍎❗]](https://hydra.nixos.org/build/243826203) [[🐧✅]](https://hydra.nixos.org/build/243817673) [haskellPackages.network-dns](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.network-dns)  ⤴️ 0 | 1
- [ ] [[🍏❗]](https://hydra.nixos.org/build/244074759) [[📱✅]](https://hydra.nixos.org/build/243831522) [[🍎❗]](https://hydra.nixos.org/build/243810737) [[🐧✅]](https://hydra.nixos.org/build/243809000) [haskellPackages.render-utf8](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.render-utf8)  ⤴️ 0 | 1
- [ ] [[🍏❗]](https://hydra.nixos.org/build/244077543) [[📱✅]](https://hydra.nixos.org/build/243806416) [[🍎❗]](https://hydra.nixos.org/build/243821566) [[🐧✅]](https://hydra.nixos.org/build/243806044) [haskellPackages.async-refresh-tokens](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.async-refresh-tokens) 
- [ ] [cabal2nix-unstable](https://hydra.nixos.org/eval/1803310?filter=cabal2nix-unstable) 
  - [[🍏✅]](https://hydra.nixos.org/build/245540162) [[📱✅]](https://hydra.nixos.org/build/245539847) [[🍎✅]](https://hydra.nixos.org/build/245539696) [[🐧✅]](https://hydra.nixos.org/build/245539375) [haskell.packages.ghc8107](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc8107.cabal2nix-unstable)
  - [[🍏✅]](https://hydra.nixos.org/build/245539794) [[📱✅]](https://hydra.nixos.org/build/245539565) [[🍎✅]](https://hydra.nixos.org/build/245540297) [[🐧✅]](https://hydra.nixos.org/build/245539955) [haskell.packages.ghc902](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc902.cabal2nix-unstable)
  - [[🍏✅]](https://hydra.nixos.org/build/245540179) [[📱✅]](https://hydra.nixos.org/build/245539773) [[🍎✅]](https://hydra.nixos.org/build/245539619) [[🐧✅]](https://hydra.nixos.org/build/245539880) [haskell.packages.ghc925](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc925.cabal2nix-unstable)
  - [[🍏❗]](https://hydra.nixos.org/build/245540120) [[📱✅]](https://hydra.nixos.org/build/245539936) [[🍎✅]](https://hydra.nixos.org/build/245539824) [[🐧✅]](https://hydra.nixos.org/build/245540245) [haskell.packages.ghc926](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc926.cabal2nix-unstable)
  - [[🍏✅]](https://hydra.nixos.org/build/245540080) [[📱✅]](https://hydra.nixos.org/build/245539522) [[🍎✅]](https://hydra.nixos.org/build/245540234) [[🐧✅]](https://hydra.nixos.org/build/245539557) [haskell.packages.ghc927](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc927.cabal2nix-unstable)
  - [[🍏✅]](https://hydra.nixos.org/build/245540014) [[📱✅]](https://hydra.nixos.org/build/245539573) [[🍎✅]](https://hydra.nixos.org/build/245539445) [[🐧✅]](https://hydra.nixos.org/build/245539538) [haskell.packages.ghc928](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc928.cabal2nix-unstable)
  - [[🍏✅]](https://hydra.nixos.org/build/245539713) [[📱✅]](https://hydra.nixos.org/build/245539498) [[🍎✅]](https://hydra.nixos.org/build/245539714) [[🐧✅]](https://hydra.nixos.org/build/245539866) [haskell.packages.ghc945](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc945.cabal2nix-unstable)
  - [[🍏✅]](https://hydra.nixos.org/build/245540282) [[📱✅]](https://hydra.nixos.org/build/245540260) [[🍎✅]](https://hydra.nixos.org/build/245539391) [[🐧✅]](https://hydra.nixos.org/build/245540135) [haskell.packages.ghc946](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc946.cabal2nix-unstable)
  - [[🍏❗]](https://hydra.nixos.org/build/245539851) [[📱✅]](https://hydra.nixos.org/build/245540069) [[🍎✅]](https://hydra.nixos.org/build/245539950) [[🐧✅]](https://hydra.nixos.org/build/245540065) [haskell.packages.ghc947](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc947.cabal2nix-unstable)
  - [[🍏✅]](https://hydra.nixos.org/build/245539605) [[📱✅]](https://hydra.nixos.org/build/245540037) [[🍎✅]](https://hydra.nixos.org/build/245539723) [[🐧✅]](https://hydra.nixos.org/build/245539482) [haskell.packages.ghc948](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc948.cabal2nix-unstable)
  - [[🍏✅]](https://hydra.nixos.org/build/245539527) [[📱✅]](https://hydra.nixos.org/build/245540154) [[🍎✅]](https://hydra.nixos.org/build/245539418) [[🐧✅]](https://hydra.nixos.org/build/245539715) [haskell.packages.ghc963](https://hydra.nixos.org/eval/1803310?filter=haskell.packages.ghc963.cabal2nix-unstable)
  - [[🍏✅]](https://hydra.nixos.org/build/244386792) [[📱✅]](https://hydra.nixos.org/build/244386809) [[🍎✅]](https://hydra.nixos.org/build/244386785) [[🐧✅]](https://hydra.nixos.org/build/244386826) [haskellPackages](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.cabal2nix-unstable)
- [ ] [[🍏❗]](https://hydra.nixos.org/build/244073677) [[📱✅]](https://hydra.nixos.org/build/243813902) [[🍎❗]](https://hydra.nixos.org/build/243819879) [[🐧✅]](https://hydra.nixos.org/build/243805306) [haskellPackages.cardano-coin-selection](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.cardano-coin-selection) 
- [ ] [[🍏❗]](https://hydra.nixos.org/build/244073395) [[📱✅]](https://hydra.nixos.org/build/243826028) [[🍎❗]](https://hydra.nixos.org/build/243805316) [[🐧✅]](https://hydra.nixos.org/build/243806392) [haskellPackages.discount](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.discount) 
- [ ] [[🍏❗]](https://hydra.nixos.org/build/244077799) [[📱✅]](https://hydra.nixos.org/build/243813725) [[🍎❗]](https://hydra.nixos.org/build/243808111) [[🐧✅]](https://hydra.nixos.org/build/243826764) [haskellPackages.epub-tools](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.epub-tools) 
- [ ] [[🍏❗]](https://hydra.nixos.org/build/244074322) [[📱✅]](https://hydra.nixos.org/build/243822518) [[🍎❗]](https://hydra.nixos.org/build/243822513) [[🐧✅]](https://hydra.nixos.org/build/243813301) [haskellPackages.exinst-aeson](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.exinst-aeson) 
- [ ] [[🍏❗]](https://hydra.nixos.org/build/244079607) [[📱✅]](https://hydra.nixos.org/build/243812925) [[🍎❗]](https://hydra.nixos.org/build/243827673) [[🐧✅]](https://hydra.nixos.org/build/243817097) [haskellPackages.exinst-bytes](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.exinst-bytes) 
- [ ] [[🍏❗]](https://hydra.nixos.org/build/244074794) [[📱✅]](https://hydra.nixos.org/build/243826476) [[🍎❗]](https://hydra.nixos.org/build/243830573) [[🐧✅]](https://hydra.nixos.org/build/243822980) [haskellPackages.exinst-cereal](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.exinst-cereal) 
- [ ] [[🍏❗]](https://hydra.nixos.org/build/244075341) [[📱✅]](https://hydra.nixos.org/build/243811616) [[🍎❗]](https://hydra.nixos.org/build/243819962) [[🐧✅]](https://hydra.nixos.org/build/243826125) [haskellPackages.exinst-serialise](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.exinst-serialise) 
- [ ] [[🍏❗]](https://hydra.nixos.org/build/244073351) [[📱✅]](https://hydra.nixos.org/build/243820972) [[🍎❗]](https://hydra.nixos.org/build/243826063) [[🐧✅]](https://hydra.nixos.org/build/243823476) [haskellPackages.fmt-terminal-colors](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.fmt-terminal-colors) 
- [ ] [[🍏❗]](https://hydra.nixos.org/build/244076696) [[📱✅]](https://hydra.nixos.org/build/243805652) [[🍎❗]](https://hydra.nixos.org/build/243807779) [[🐧✅]](https://hydra.nixos.org/build/243816694) [haskellPackages.foma](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.foma) 
- [ ] [[🍏✅]](https://hydra.nixos.org/build/244073934) [[📱❗]](https://hydra.nixos.org/build/243814254) [[🍎✅]](https://hydra.nixos.org/build/243831934) [[🐧✅]](https://hydra.nixos.org/build/243828368) [haskellPackages.hasql-th](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.hasql-th) 
- [ ] [hello](https://hydra.nixos.org/eval/1803310?filter=hello) 
  - [[🍏✅]](https://hydra.nixos.org/build/244079126) [[📱✅]](https://hydra.nixos.org/build/243819952) [[🍎✅]](https://hydra.nixos.org/build/243807089) [[🐧✅]](https://hydra.nixos.org/build/243823707) [haskellPackages](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.hello)
  - [[🍏❗]](https://hydra.nixos.org/build/245539298)  [[🍎❗]](https://hydra.nixos.org/build/245539289) [[🐧❗]](https://hydra.nixos.org/build/245539319) [pkgsCross.ghcjs.haskell.packages.ghcHEAD](https://hydra.nixos.org/eval/1803310?filter=pkgsCross.ghcjs.haskell.packages.ghcHEAD.hello)
  - [[🍏❗]](https://hydra.nixos.org/build/245539291)  [[🍎❗]](https://hydra.nixos.org/build/245539295) [[🐧❗]](https://hydra.nixos.org/build/245539363) [pkgsCross.ghcjs.haskellPackages](https://hydra.nixos.org/eval/1803310?filter=pkgsCross.ghcjs.haskellPackages.hello)
  -    [[🐧✅]](https://hydra.nixos.org/build/243824073) [pkgsMusl.haskellPackages](https://hydra.nixos.org/eval/1803310?filter=pkgsMusl.haskellPackages.hello)
  -    [[🐧✅]](https://hydra.nixos.org/build/245539313) [pkgsStatic.haskell.packages.native-bignum.ghc948](https://hydra.nixos.org/eval/1803310?filter=pkgsStatic.haskell.packages.native-bignum.ghc948.hello)
  -    [[🐧✅]](https://hydra.nixos.org/build/245539367) [pkgsStatic.haskell.packages.native-bignum.ghc981](https://hydra.nixos.org/eval/1803310?filter=pkgsStatic.haskell.packages.native-bignum.ghc981.hello)
  -    [[🐧✅]](https://hydra.nixos.org/build/245539306) [pkgsStatic.haskellPackages](https://hydra.nixos.org/eval/1803310?filter=pkgsStatic.haskellPackages.hello)
- [ ] [[🍏❗]](https://hydra.nixos.org/build/244078269) [[📱❗]](https://hydra.nixos.org/build/243829568) [[🍎✅]](https://hydra.nixos.org/build/243804485) [[🐧✅]](https://hydra.nixos.org/build/243831030) [haskellPackages.hmatrix-nlopt](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.hmatrix-nlopt) 
- [ ] [[🍏❗]](https://hydra.nixos.org/build/244079693) [[📱✅]](https://hydra.nixos.org/build/243819360) [[🍎❗]](https://hydra.nixos.org/build/243824513) [[🐧✅]](https://hydra.nixos.org/build/243813197) [haskellPackages.intel-powermon](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.intel-powermon) 
- [ ] [[🍏❗]](https://hydra.nixos.org/build/244077272) [[📱✅]](https://hydra.nixos.org/build/243816107) [[🍎✅]](https://hydra.nixos.org/build/243831966) [[🐧✅]](https://hydra.nixos.org/build/243808218) [haskellPackages.moto-postgresql](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.moto-postgresql) 
- [ ] [[🍏❗]](https://hydra.nixos.org/build/244077529) [[📱✅]](https://hydra.nixos.org/build/243821373) [[🍎❗]](https://hydra.nixos.org/build/243832229) [[🐧✅]](https://hydra.nixos.org/build/243813744) [haskellPackages.numeric-optimization-ad](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.numeric-optimization-ad) 
- [ ] [[🍏❗]](https://hydra.nixos.org/build/244077217) [[📱✅]](https://hydra.nixos.org/build/243812791) [[🍎❗]](https://hydra.nixos.org/build/243811899) [[🐧✅]](https://hydra.nixos.org/build/243830071) [haskellPackages.numeric-optimization-backprop](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.numeric-optimization-backprop) 
- [ ] [[🍏❗]](https://hydra.nixos.org/build/244074309) [[📱✅]](https://hydra.nixos.org/build/243824625) [[🍎❗]](https://hydra.nixos.org/build/243806367) [[🐧✅]](https://hydra.nixos.org/build/243815492) [haskellPackages.nyan-interpolation](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.nyan-interpolation) 
- [ ] [[🍏❗]](https://hydra.nixos.org/build/244077567) [[📱✅]](https://hydra.nixos.org/build/243826190) [[🍎❗]](https://hydra.nixos.org/build/243830136) [[🐧✅]](https://hydra.nixos.org/build/243826591) [haskellPackages.nyan-interpolation-simple](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.nyan-interpolation-simple) 
- [ ] [[🍏❗]](https://hydra.nixos.org/build/244079193) [[📱✅]](https://hydra.nixos.org/build/243822674) [[🍎❗]](https://hydra.nixos.org/build/243808538) [[🐧✅]](https://hydra.nixos.org/build/243824767) [haskellPackages.quickcheck-quid](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.quickcheck-quid) 
- [ ] [[🍏❗]](https://hydra.nixos.org/build/244074291) [[📱✅]](https://hydra.nixos.org/build/243806850) [[🍎❗]](https://hydra.nixos.org/build/243825882) [[🐧✅]](https://hydra.nixos.org/build/243815197) [haskellPackages.rg](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.rg) 
- [ ] [[🍏❗]](https://hydra.nixos.org/build/244079241) [[📱✅]](https://hydra.nixos.org/build/243830706) [[🍎✅]](https://hydra.nixos.org/build/243821405) [[🐧✅]](https://hydra.nixos.org/build/243805801) [haskellPackages.sequenceTools](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.sequenceTools) 
- [ ] [[🍏✅]](https://hydra.nixos.org/build/244073975) [[📱❗]](https://hydra.nixos.org/build/243806456) [[🍎✅]](https://hydra.nixos.org/build/243815913) [[🐧✅]](https://hydra.nixos.org/build/243829383) [haskellPackages.stm-actor](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.stm-actor) 
- [ ] [[🍏❗]](https://hydra.nixos.org/build/244080008) [[📱✅]](https://hydra.nixos.org/build/243821553) [[🍎❗]](https://hydra.nixos.org/build/243808451) [[🐧✅]](https://hydra.nixos.org/build/243811573) [haskellPackages.sym-plot](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.sym-plot) 
- [ ] [[🍏❗]](https://hydra.nixos.org/build/244078565) [[📱✅]](https://hydra.nixos.org/build/243806370) [[🍎❗]](https://hydra.nixos.org/build/243817744) [[🐧✅]](https://hydra.nixos.org/build/243825425) [haskellPackages.xbattbar](https://hydra.nixos.org/eval/1803310?filter=haskellPackages.xbattbar) 
</details>

#### Top 50 broken packages, sorted by number of reverse dependencies
<details><summary>50 job(s) </summary>

[gogol-core](https://packdeps.haskellers.com/reverse/gogol-core) ⤴️ 184  
[haskell98](https://packdeps.haskellers.com/reverse/haskell98) ⤴️ 152  
[heist](https://packdeps.haskellers.com/reverse/heist) ⤴️ 72  
[snap](https://packdeps.haskellers.com/reverse/snap) ⤴️ 63  
[enumerator](https://packdeps.haskellers.com/reverse/enumerator) ⤴️ 56  
[util](https://packdeps.haskellers.com/reverse/util) ⤴️ 49  
[derive](https://packdeps.haskellers.com/reverse/derive) ⤴️ 48  
[repa](https://packdeps.haskellers.com/reverse/repa) ⤴️ 45  
[accelerate](https://packdeps.haskellers.com/reverse/accelerate) ⤴️ 42  
[syb-with-class](https://packdeps.haskellers.com/reverse/syb-with-class) ⤴️ 42  
[TypeCompose](https://packdeps.haskellers.com/reverse/TypeCompose) ⤴️ 38  
[PrimitiveArray](https://packdeps.haskellers.com/reverse/PrimitiveArray) ⤴️ 35  
[rank1dynamic](https://packdeps.haskellers.com/reverse/rank1dynamic) ⤴️ 33  
[distributed-static](https://packdeps.haskellers.com/reverse/distributed-static) ⤴️ 31  
[distributed-process](https://packdeps.haskellers.com/reverse/distributed-process) ⤴️ 30  
[iteratee](https://packdeps.haskellers.com/reverse/iteratee) ⤴️ 29  
[polysemy-time](https://packdeps.haskellers.com/reverse/polysemy-time) ⤴️ 28  
[polysemy-resume](https://packdeps.haskellers.com/reverse/polysemy-resume) ⤴️ 27  
[polysemy-conc](https://packdeps.haskellers.com/reverse/polysemy-conc) ⤴️ 26  
[crypto-numbers](https://packdeps.haskellers.com/reverse/crypto-numbers) ⤴️ 25  
[either-unwrap](https://packdeps.haskellers.com/reverse/either-unwrap) ⤴️ 25  
[HList](https://packdeps.haskellers.com/reverse/HList) ⤴️ 24  
[polysemy-log](https://packdeps.haskellers.com/reverse/polysemy-log) ⤴️ 24  
[crypto-pubkey](https://packdeps.haskellers.com/reverse/crypto-pubkey) ⤴️ 22  
[haskelldb](https://packdeps.haskellers.com/reverse/haskelldb) ⤴️ 22  
[wxdirect](https://packdeps.haskellers.com/reverse/wxdirect) ⤴️ 22  
[BiobaseTypes](https://packdeps.haskellers.com/reverse/BiobaseTypes) ⤴️ 21  
[alg](https://packdeps.haskellers.com/reverse/alg) ⤴️ 21  
[mmsyn2](https://packdeps.haskellers.com/reverse/mmsyn2) ⤴️ 21  
[userid](https://packdeps.haskellers.com/reverse/userid) ⤴️ 21  
[wxc](https://packdeps.haskellers.com/reverse/wxc) ⤴️ 21  
[biocore](https://packdeps.haskellers.com/reverse/biocore) ⤴️ 20  
[cheapskate](https://packdeps.haskellers.com/reverse/cheapskate) ⤴️ 20  
[openapi3](https://packdeps.haskellers.com/reverse/openapi3) ⤴️ 20  
[wxcore](https://packdeps.haskellers.com/reverse/wxcore) ⤴️ 20  
[attoparsec-enumerator](https://packdeps.haskellers.com/reverse/attoparsec-enumerator) ⤴️ 19  
[bytestring-show](https://packdeps.haskellers.com/reverse/bytestring-show) ⤴️ 19  
[fay](https://packdeps.haskellers.com/reverse/fay) ⤴️ 19  
[incipit](https://packdeps.haskellers.com/reverse/incipit) ⤴️ 19  
[ixset](https://packdeps.haskellers.com/reverse/ixset) ⤴️ 19  
[polysemy-chronos](https://packdeps.haskellers.com/reverse/polysemy-chronos) ⤴️ 19  
[wx](https://packdeps.haskellers.com/reverse/wx) ⤴️ 19  
[BiobaseENA](https://packdeps.haskellers.com/reverse/BiobaseENA) ⤴️ 18  
[asn1-data](https://packdeps.haskellers.com/reverse/asn1-data) ⤴️ 18  
[dbus-core](https://packdeps.haskellers.com/reverse/dbus-core) ⤴️ 18  
[digit](https://packdeps.haskellers.com/reverse/digit) ⤴️ 18  
[gtksourceview2](https://packdeps.haskellers.com/reverse/gtksourceview2) ⤴️ 18  
[polysemy-process](https://packdeps.haskellers.com/reverse/polysemy-process) ⤴️ 18  
[ukrainian-phonetics-basic](https://packdeps.haskellers.com/reverse/ukrainian-phonetics-basic) ⤴️ 18  
[BiobaseXNA](https://packdeps.haskellers.com/reverse/BiobaseXNA) ⤴️ 17  
</details>


*⤴️: The number of packages that depend (directly or indirectly) on this package (if any). If two numbers are shown the first (lower) number considers only packages which currently have enabled hydra jobs, i.e. are not marked broken. The second (higher) number considers all packages.*

*Report generated with [maintainers/scripts/haskell/hydra-report.hs](https://github.com/NixOS/nixpkgs/blob/haskell-updates/maintainers/scripts/haskell/hydra-report.hs)*


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
