### [haskell-updates build report from hydra](https://hydra.nixos.org/jobset/nixpkgs/haskell-updates)
*evaluation [1753097](https://hydra.nixos.org/eval/1753097) of nixpkgs commit [493d651](https://github.com/NixOS/nixpkgs/commits/493d6516ddb69a49df49c1b4f3e91ff33effbb9e) as of 2022-04-04 18:18 UTC*

:red_circle: **Branch not mergeable**
  * `mergeable` jobset failed.
  * `maintained` jobset failed.

#### Build summary

 | Platform | Failed :x: | DependencyFailed :heavy_exclamation_mark: | TimedOut :hourglass::no_entry_sign: | Canceled :no_entry_sign: | Success :heavy_check_mark: | 
 | --- | --- | --- | --- | --- | --- | 
 | [aarch64-linux :iphone:](https://hydra.nixos.org/eval/1753097?filter=.aarch64-linux) | 32 | 46 | 5 | 76 | 6139 | 
 | [x86_64-darwin :apple:](https://hydra.nixos.org/eval/1753097?filter=.x86_64-darwin) | 1 | 1 |  | 6219 | 26 | 
 | [x86_64-linux :penguin:](https://hydra.nixos.org/eval/1753097?filter=.x86_64-linux) | 11 | 19 | 7 | 1 | 6281 | 
#### Maintained packages with build failure
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/171870860) [[:apple::no_entry_sign:]](https://hydra.nixos.org/build/171859032) [[:penguin::x:]](https://hydra.nixos.org/build/171861365) [haskellPackages.graphql-parser](https://hydra.nixos.org/eval/1753097?filter=haskellPackages.graphql-parser) @Lassulus
- [ ] [[:iphone::no_entry_sign:]](https://hydra.nixos.org/build/171864019) [[:apple::x:]](https://hydra.nixos.org/build/171857799) [[:penguin::x:]](https://hydra.nixos.org/build/171864031) [hasura-graphql-engine](https://hydra.nixos.org/eval/1753097?filter=hasura-graphql-engine) @Lassulus
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/171859461) [[:apple::no_entry_sign:]](https://hydra.nixos.org/build/171863997) [[:penguin::x:]](https://hydra.nixos.org/build/171869976) [jl](https://hydra.nixos.org/eval/1753097?filter=jl) @fgaz
#### Maintained packages with failed dependency
- [ ] [cabal-install](https://hydra.nixos.org/eval/1753097?filter=cabal-install) @peti
  - [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/171867412) [[:apple::no_entry_sign:]](https://hydra.nixos.org/build/171861372) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171856690) [toplevel](https://hydra.nixos.org/eval/1753097?filter=cabal-install)
  - [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/171866974) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/171857622) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171860254) [haskell.packages.ghc8107](https://hydra.nixos.org/eval/1753097?filter=haskell.packages.ghc8107.cabal-install)
  - [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/171859573) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/171870062) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171857369) [haskell.packages.ghc884](https://hydra.nixos.org/eval/1753097?filter=haskell.packages.ghc884.cabal-install)
  - [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/171858538) [[:apple::no_entry_sign:]](https://hydra.nixos.org/build/171871967) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171856745) [haskell.packages.ghc902](https://hydra.nixos.org/eval/1753097?filter=haskell.packages.ghc902.cabal-install)
  - [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171870181) [[:apple::no_entry_sign:]](https://hydra.nixos.org/build/171862128) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171863957) [haskell.packages.ghc922](https://hydra.nixos.org/eval/1753097?filter=haskell.packages.ghc922.cabal-install)
  - [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/171866492) [[:apple::no_entry_sign:]](https://hydra.nixos.org/build/171859695) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171856708) [haskellPackages](https://hydra.nixos.org/eval/1753097?filter=haskellPackages.cabal-install)
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171866991) [[:apple::no_entry_sign:]](https://hydra.nixos.org/build/171865101) [[:penguin::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171870149) [haskellPackages.graphql-engine](https://hydra.nixos.org/eval/1753097?filter=haskellPackages.graphql-engine) @Lassulus
- [ ] [haskell-language-server](https://hydra.nixos.org/eval/1753097?filter=haskell-language-server) @maralorn
  - [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171864528) [[:apple::no_entry_sign:]](https://hydra.nixos.org/build/171870051) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171858502) [toplevel](https://hydra.nixos.org/eval/1753097?filter=haskell-language-server)
  - [[:iphone::no_entry_sign:]](https://hydra.nixos.org/build/171854509) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/171859524) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171860346) [haskell.packages.ghc8107](https://hydra.nixos.org/eval/1753097?filter=haskell.packages.ghc8107.haskell-language-server)
  - [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/171863372) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/171860727) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171866511) [haskell.packages.ghc884](https://hydra.nixos.org/eval/1753097?filter=haskell.packages.ghc884.haskell-language-server)
  - [[:iphone::no_entry_sign:]](https://hydra.nixos.org/build/171863697) [[:apple::no_entry_sign:]](https://hydra.nixos.org/build/171864525) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171865068) [haskell.packages.ghc902](https://hydra.nixos.org/eval/1753097?filter=haskell.packages.ghc902.haskell-language-server)
  - [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171864948) [[:apple::no_entry_sign:]](https://hydra.nixos.org/build/171854145) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171864800) [haskell.packages.ghc922](https://hydra.nixos.org/eval/1753097?filter=haskell.packages.ghc922.haskell-language-server)
  - [[:iphone::no_entry_sign:]](https://hydra.nixos.org/build/171856383) [[:apple::no_entry_sign:]](https://hydra.nixos.org/build/171857135) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171857185) [haskellPackages](https://hydra.nixos.org/eval/1753097?filter=haskellPackages.haskell-language-server)
- [ ] [hlint](https://hydra.nixos.org/eval/1753097?filter=hlint) @maralorn
  - [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/171859794) [[:apple::no_entry_sign:]](https://hydra.nixos.org/build/171864005) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171854674) [toplevel](https://hydra.nixos.org/eval/1753097?filter=hlint)
  - [[:iphone::no_entry_sign:]](https://hydra.nixos.org/build/171862816) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/171864047) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171853663) [haskell.packages.ghc8107](https://hydra.nixos.org/eval/1753097?filter=haskell.packages.ghc8107.hlint)
  - [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/171862943) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/171859859) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171856331) [haskell.packages.ghc884](https://hydra.nixos.org/eval/1753097?filter=haskell.packages.ghc884.hlint)
  - [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/171867244) [[:apple::no_entry_sign:]](https://hydra.nixos.org/build/171864964) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171859039) [haskell.packages.ghc902](https://hydra.nixos.org/eval/1753097?filter=haskell.packages.ghc902.hlint)
  - [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171865805) [[:apple::no_entry_sign:]](https://hydra.nixos.org/build/171854924) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171859812) [haskell.packages.ghc922](https://hydra.nixos.org/eval/1753097?filter=haskell.packages.ghc922.hlint)
  - [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/171864209) [[:apple::no_entry_sign:]](https://hydra.nixos.org/build/171866786) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171861792) [haskellPackages](https://hydra.nixos.org/eval/1753097?filter=haskellPackages.hlint)
- [ ] [language-nix](https://hydra.nixos.org/eval/1753097?filter=language-nix) @peti
  - [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/171864042) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/171854278) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171856011) [haskell.packages.ghc8107](https://hydra.nixos.org/eval/1753097?filter=haskell.packages.ghc8107.language-nix)
  - [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/171860602) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/171856603) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171864877) [haskell.packages.ghc884](https://hydra.nixos.org/eval/1753097?filter=haskell.packages.ghc884.language-nix)
  - [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/171861943) [[:apple::no_entry_sign:]](https://hydra.nixos.org/build/171852816) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171858399) [haskell.packages.ghc902](https://hydra.nixos.org/eval/1753097?filter=haskell.packages.ghc902.language-nix)
  - [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171866588) [[:apple::no_entry_sign:]](https://hydra.nixos.org/build/171857336) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171871993) [haskell.packages.ghc922](https://hydra.nixos.org/eval/1753097?filter=haskell.packages.ghc922.language-nix)
  - [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/171871097) [[:apple::no_entry_sign:]](https://hydra.nixos.org/build/171871023) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171871654) [haskellPackages](https://hydra.nixos.org/eval/1753097?filter=haskellPackages.language-nix)
- [ ] [[:penguin::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171859738) [maintained](https://hydra.nixos.org/eval/1753097?filter=maintained) @cdepillabout @expipiplus1 @maralorn @sternenseemann
- [ ] [[:penguin::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171864122) [mergeable](https://hydra.nixos.org/eval/1753097?filter=mergeable) @cdepillabout @expipiplus1 @maralorn @sternenseemann
- [ ] [[:penguin::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171854287) [haskellPackages.reflex-dom](https://hydra.nixos.org/eval/1753097?filter=haskellPackages.reflex-dom) @maralorn
- [ ] [spago](https://hydra.nixos.org/eval/1753097?filter=spago) @cdepillabout
  - [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171861126) [[:apple::no_entry_sign:]](https://hydra.nixos.org/build/171871490) [[:penguin::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171852877) [toplevel](https://hydra.nixos.org/eval/1753097?filter=spago)
  - [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171862357) [[:apple::no_entry_sign:]](https://hydra.nixos.org/build/171866857) [[:penguin::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171869812) [haskellPackages](https://hydra.nixos.org/eval/1753097?filter=haskellPackages.spago)
- [ ] [update-nix-fetchgit](https://hydra.nixos.org/eval/1753097?filter=update-nix-fetchgit) @expipiplus1 @sorki
  - [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171869214) [[:apple::no_entry_sign:]](https://hydra.nixos.org/build/171866243) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171854526) [toplevel](https://hydra.nixos.org/eval/1753097?filter=update-nix-fetchgit)
  - [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171867249) [[:apple::no_entry_sign:]](https://hydra.nixos.org/build/171853366) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171864328) [haskellPackages](https://hydra.nixos.org/eval/1753097?filter=haskellPackages.update-nix-fetchgit)
#### Unmaintained packages with build failure
<details><summary>35 job(s) </summary>

- [ ] [QuickCheck](https://hydra.nixos.org/eval/1753097?filter=QuickCheck)  :arrow_heading_up: 1236 | 4755
  - [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/171855138) [[:apple::no_entry_sign:]](https://hydra.nixos.org/build/171858360) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171859376) [haskellPackages](https://hydra.nixos.org/eval/1753097?filter=haskellPackages.QuickCheck)
  -   [[:penguin::x:]](https://hydra.nixos.org/build/171869550) [pkgsStatic.haskell.packages.integer-simple.ghc8107](https://hydra.nixos.org/eval/1753097?filter=pkgsStatic.haskell.packages.integer-simple.ghc8107.QuickCheck)
  -   [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171857722) [pkgsStatic.haskell.packages.native-bignum.ghc902](https://hydra.nixos.org/eval/1753097?filter=pkgsStatic.haskell.packages.native-bignum.ghc902.QuickCheck)
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/171870158) [[:apple::no_entry_sign:]](https://hydra.nixos.org/build/171857210) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171867668) [haskellPackages.OrderedBits](https://hydra.nixos.org/eval/1753097?filter=haskellPackages.OrderedBits)  :arrow_heading_up: 5 | 36
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/171856905) [[:apple::no_entry_sign:]](https://hydra.nixos.org/build/171867686) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171857885) [haskellPackages.cryptostore](https://hydra.nixos.org/eval/1753097?filter=haskellPackages.cryptostore)  :arrow_heading_up: 4 | 31
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/171865966) [[:apple::no_entry_sign:]](https://hydra.nixos.org/build/171870109) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171858915) [haskellPackages.ptr-poker](https://hydra.nixos.org/eval/1753097?filter=haskellPackages.ptr-poker)  :arrow_heading_up: 3 | 3
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/171855578) [[:apple::no_entry_sign:]](https://hydra.nixos.org/build/171865205) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171857596) [haskellPackages.hw-json-simd](https://hydra.nixos.org/eval/1753097?filter=haskellPackages.hw-json-simd)  :arrow_heading_up: 2 | 8
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/171856342) [[:apple::no_entry_sign:]](https://hydra.nixos.org/build/171870086) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171862699) [haskellPackages.hw-simd](https://hydra.nixos.org/eval/1753097?filter=haskellPackages.hw-simd)  :arrow_heading_up: 2 | 8
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/171862898) [[:apple::no_entry_sign:]](https://hydra.nixos.org/build/171861026) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171862442) [haskellPackages.quic](https://hydra.nixos.org/eval/1753097?filter=haskellPackages.quic)  :arrow_heading_up: 2 | 2
- [ ] [[:iphone::no_entry_sign:]](https://hydra.nixos.org/build/171866661) [[:penguin::x:]](https://hydra.nixos.org/build/171870950) [haskellPackages.jsaddle-webkit2gtk](https://hydra.nixos.org/eval/1753097?filter=haskellPackages.jsaddle-webkit2gtk)  :arrow_heading_up: 1 | 11
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/171855175) [[:apple::no_entry_sign:]](https://hydra.nixos.org/build/171869070) [[:penguin::x:]](https://hydra.nixos.org/build/171864450) [haskellPackages.bower-json](https://hydra.nixos.org/eval/1753097?filter=haskellPackages.bower-json)  :arrow_heading_up: 1 | 10
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/171860843) [[:apple::no_entry_sign:]](https://hydra.nixos.org/build/171860724) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171871830) [haskellPackages.freetype2](https://hydra.nixos.org/eval/1753097?filter=haskellPackages.freetype2)  :arrow_heading_up: 1 | 8
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/171856730) [[:apple::no_entry_sign:]](https://hydra.nixos.org/build/171855544) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171864198) [haskellPackages.long-double](https://hydra.nixos.org/eval/1753097?filter=haskellPackages.long-double)  :arrow_heading_up: 1 | 2
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/171857435) [[:apple::no_entry_sign:]](https://hydra.nixos.org/build/171870314) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171862125) [haskellPackages.easytensor](https://hydra.nixos.org/eval/1753097?filter=haskellPackages.easytensor)  :arrow_heading_up: 1 | 1
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/171867377) [[:apple::no_entry_sign:]](https://hydra.nixos.org/build/171870936) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171861161) [haskellPackages.nlopt-haskell](https://hydra.nixos.org/eval/1753097?filter=haskellPackages.nlopt-haskell)  :arrow_heading_up: 1 | 1
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/171854078) [[:apple::no_entry_sign:]](https://hydra.nixos.org/build/171862942) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171857572) [haskellPackages.swisstable](https://hydra.nixos.org/eval/1753097?filter=haskellPackages.swisstable)  :arrow_heading_up: 1 | 1
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/171857072) [[:apple::no_entry_sign:]](https://hydra.nixos.org/build/171867045) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171852967) [haskellPackages.unicode-properties](https://hydra.nixos.org/eval/1753097?filter=haskellPackages.unicode-properties)  :arrow_heading_up: 1 | 1
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/171860343) [[:apple::no_entry_sign:]](https://hydra.nixos.org/build/171853368) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171861052) [haskellPackages.picosat](https://hydra.nixos.org/eval/1753097?filter=haskellPackages.picosat)  :arrow_heading_up: 0 | 1
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/171864526) [[:apple::no_entry_sign:]](https://hydra.nixos.org/build/171859855) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171863492) [haskellPackages.simple-vec3](https://hydra.nixos.org/eval/1753097?filter=haskellPackages.simple-vec3)  :arrow_heading_up: 0 | 1
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/171856051) [[:apple::no_entry_sign:]](https://hydra.nixos.org/build/171852793) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171858315) [haskellPackages.HsASA](https://hydra.nixos.org/eval/1753097?filter=haskellPackages.HsASA) 
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/171865682) [[:apple::no_entry_sign:]](https://hydra.nixos.org/build/171870312) [[:penguin::x:]](https://hydra.nixos.org/build/171865338) [haskellPackages.capataz](https://hydra.nixos.org/eval/1753097?filter=haskellPackages.capataz) 
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/171862589) [[:apple::no_entry_sign:]](https://hydra.nixos.org/build/171856354) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171857405) [haskellPackages.comfort-fftw](https://hydra.nixos.org/eval/1753097?filter=haskellPackages.comfort-fftw) 
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/171854581) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171858611) [haskellPackages.gnome-keyring](https://hydra.nixos.org/eval/1753097?filter=haskellPackages.gnome-keyring) 
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/171864576) [[:apple::no_entry_sign:]](https://hydra.nixos.org/build/171857616) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171871380) [haskellPackages.hls-rename-plugin](https://hydra.nixos.org/eval/1753097?filter=haskellPackages.hls-rename-plugin) 
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/171854418) [[:apple::no_entry_sign:]](https://hydra.nixos.org/build/171864129) [[:penguin::x:]](https://hydra.nixos.org/build/171859983) [haskellPackages.hyper-haskell-server](https://hydra.nixos.org/eval/1753097?filter=haskellPackages.hyper-haskell-server) 
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/171871047) [[:apple::no_entry_sign:]](https://hydra.nixos.org/build/171854882) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171868110) [haskellPackages.jammittools](https://hydra.nixos.org/eval/1753097?filter=haskellPackages.jammittools) 
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/171865092) [[:apple::no_entry_sign:]](https://hydra.nixos.org/build/171864375) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171856651) [haskellPackages.powerqueue-distributed](https://hydra.nixos.org/eval/1753097?filter=haskellPackages.powerqueue-distributed) 
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/171858796) [[:apple::no_entry_sign:]](https://hydra.nixos.org/build/171855508) [[:penguin::x:]](https://hydra.nixos.org/build/171864297) [haskellPackages.powerqueue-levelmem](https://hydra.nixos.org/eval/1753097?filter=haskellPackages.powerqueue-levelmem) 
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/171862860) [[:apple::no_entry_sign:]](https://hydra.nixos.org/build/171852904) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171862696) [haskellPackages.risc386](https://hydra.nixos.org/eval/1753097?filter=haskellPackages.risc386) 
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/171863691) [[:apple::no_entry_sign:]](https://hydra.nixos.org/build/171861382) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171860820) [haskellPackages.slugify](https://hydra.nixos.org/eval/1753097?filter=haskellPackages.slugify) 
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/171857697) [[:apple::no_entry_sign:]](https://hydra.nixos.org/build/171867036) [[:penguin::x:]](https://hydra.nixos.org/build/171853334) [haskellPackages.socketson](https://hydra.nixos.org/eval/1753097?filter=haskellPackages.socketson) 
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/171853926) [[:apple::no_entry_sign:]](https://hydra.nixos.org/build/171853832) [[:penguin::x:]](https://hydra.nixos.org/build/171862657) [haskellPackages.tripLL](https://hydra.nixos.org/eval/1753097?filter=haskellPackages.tripLL) 
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/171858390) [[:apple::no_entry_sign:]](https://hydra.nixos.org/build/171858351) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171865355) [haskellPackages.wiringPi](https://hydra.nixos.org/eval/1753097?filter=haskellPackages.wiringPi) 
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/171860405) [[:apple::no_entry_sign:]](https://hydra.nixos.org/build/171854831) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171858701) [haskellPackages.x86-64bit](https://hydra.nixos.org/eval/1753097?filter=haskellPackages.x86-64bit) 
</details>

#### Unmaintained packages with failed dependency
<details><summary>53 job(s) </summary>

- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171869570) [[:apple::no_entry_sign:]](https://hydra.nixos.org/build/171868602) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171857905) [haskellPackages.PrimitiveArray](https://hydra.nixos.org/eval/1753097?filter=haskellPackages.PrimitiveArray)  :arrow_heading_up: 4 | 35
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171860234) [[:apple::no_entry_sign:]](https://hydra.nixos.org/build/171858559) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171853180) [haskellPackages.jwt](https://hydra.nixos.org/eval/1753097?filter=haskellPackages.jwt)  :arrow_heading_up: 3 | 28
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171859690) [[:apple::no_entry_sign:]](https://hydra.nixos.org/build/171855403) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171864366) [haskellPackages.BiobaseTypes](https://hydra.nixos.org/eval/1753097?filter=haskellPackages.BiobaseTypes)  :arrow_heading_up: 3 | 21
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171856446) [[:apple::no_entry_sign:]](https://hydra.nixos.org/build/171860436) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171854636) [haskellPackages.jsonifier](https://hydra.nixos.org/eval/1753097?filter=haskellPackages.jsonifier)  :arrow_heading_up: 2 | 2
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171856258) [[:apple::no_entry_sign:]](https://hydra.nixos.org/build/171858036) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171871240) [haskellPackages.BiobaseENA](https://hydra.nixos.org/eval/1753097?filter=haskellPackages.BiobaseENA)  :arrow_heading_up: 1 | 18
- [ ] [hoogle](https://hydra.nixos.org/eval/1753097?filter=hoogle)  :arrow_heading_up: 1 | 2
  - [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/171871347) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/171853429) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171867270) [haskell.packages.ghc8107](https://hydra.nixos.org/eval/1753097?filter=haskell.packages.ghc8107.hoogle)
  - [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/171868587) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/171863488) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171867576) [haskell.packages.ghc884](https://hydra.nixos.org/eval/1753097?filter=haskell.packages.ghc884.hoogle)
  - [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/171852837) [[:apple::no_entry_sign:]](https://hydra.nixos.org/build/171868318) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171863678) [haskell.packages.ghc902](https://hydra.nixos.org/eval/1753097?filter=haskell.packages.ghc902.hoogle)
  - [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171865846) [[:apple::no_entry_sign:]](https://hydra.nixos.org/build/171864989) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171865459) [haskell.packages.ghc922](https://hydra.nixos.org/eval/1753097?filter=haskell.packages.ghc922.hoogle)
  - [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/171862778) [[:apple::no_entry_sign:]](https://hydra.nixos.org/build/171862396) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171869816) [haskellPackages](https://hydra.nixos.org/eval/1753097?filter=haskellPackages.hoogle)
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171861581) [[:apple::no_entry_sign:]](https://hydra.nixos.org/build/171852912) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171863080) [haskellPackages.github-rest](https://hydra.nixos.org/eval/1753097?filter=haskellPackages.github-rest)  :arrow_heading_up: 1 | 1
- [ ] [[:iphone::no_entry_sign:]](https://hydra.nixos.org/build/171862194) [[:penguin::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171865924) [haskellPackages.hbro](https://hydra.nixos.org/eval/1753097?filter=haskellPackages.hbro)  :arrow_heading_up: 1 | 1
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171857549) [[:apple::no_entry_sign:]](https://hydra.nixos.org/build/171865639) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171860183) [haskellPackages.http3](https://hydra.nixos.org/eval/1753097?filter=haskellPackages.http3)  :arrow_heading_up: 1 | 1
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171869964) [[:apple::no_entry_sign:]](https://hydra.nixos.org/build/171865623) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171869914) [haskellPackages.opentelemetry-extra](https://hydra.nixos.org/eval/1753097?filter=haskellPackages.opentelemetry-extra)  :arrow_heading_up: 1 | 1
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171868423) [[:apple::no_entry_sign:]](https://hydra.nixos.org/build/171871309) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171857039) [haskellPackages.BiobaseXNA](https://hydra.nixos.org/eval/1753097?filter=haskellPackages.BiobaseXNA)  :arrow_heading_up: 0 | 17
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171867550) [[:apple::no_entry_sign:]](https://hydra.nixos.org/build/171865808) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171856273) [haskellPackages.hw-json-standard-cursor](https://hydra.nixos.org/eval/1753097?filter=haskellPackages.hw-json-standard-cursor)  :arrow_heading_up: 0 | 6
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171870416) [[:apple::no_entry_sign:]](https://hydra.nixos.org/build/171859949) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171869624) [haskellPackages.hw-json-simple-cursor](https://hydra.nixos.org/eval/1753097?filter=haskellPackages.hw-json-simple-cursor)  :arrow_heading_up: 0 | 4
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171867716) [[:apple::no_entry_sign:]](https://hydra.nixos.org/build/171861992) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171870240) [haskellPackages.BiobaseFasta](https://hydra.nixos.org/eval/1753097?filter=haskellPackages.BiobaseFasta)  :arrow_heading_up: 0 | 3
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171866331) [[:apple::no_entry_sign:]](https://hydra.nixos.org/build/171867791) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171865081) [haskellPackages.hw-dsv](https://hydra.nixos.org/eval/1753097?filter=haskellPackages.hw-dsv)  :arrow_heading_up: 0 | 3
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/171857188) [[:apple::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171858561) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171857818) [haskellPackages.libvirt-hs](https://hydra.nixos.org/eval/1753097?filter=haskellPackages.libvirt-hs)  :arrow_heading_up: 0 | 1
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171861978) [[:apple::no_entry_sign:]](https://hydra.nixos.org/build/171860974) [[:penguin::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171854273) [haskellPackages.GuiHaskell](https://hydra.nixos.org/eval/1753097?filter=haskellPackages.GuiHaskell) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171852847) [[:penguin::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171854687) [haskellPackages.HDRUtils](https://hydra.nixos.org/eval/1753097?filter=haskellPackages.HDRUtils) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171859005) [[:apple::no_entry_sign:]](https://hydra.nixos.org/build/171859432) [[:penguin::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171863511) [haskellPackages.HPlot](https://hydra.nixos.org/eval/1753097?filter=haskellPackages.HPlot) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171865737) [[:apple::no_entry_sign:]](https://hydra.nixos.org/build/171855961) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171868234) [haskellPackages.align-audio](https://hydra.nixos.org/eval/1753097?filter=haskellPackages.align-audio) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171859807) [[:apple::no_entry_sign:]](https://hydra.nixos.org/build/171858842) [[:penguin::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171864708) [haskellPackages.bluetile](https://hydra.nixos.org/eval/1753097?filter=haskellPackages.bluetile) 
- [ ] [cabal2nix-unstable](https://hydra.nixos.org/eval/1753097?filter=cabal2nix-unstable) 
  - [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/171860562) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/171866510) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171854640) [haskell.packages.ghc8107](https://hydra.nixos.org/eval/1753097?filter=haskell.packages.ghc8107.cabal2nix-unstable)
  - [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/171857232) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/171856721) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171864808) [haskell.packages.ghc884](https://hydra.nixos.org/eval/1753097?filter=haskell.packages.ghc884.cabal2nix-unstable)
  - [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/171860781) [[:apple::no_entry_sign:]](https://hydra.nixos.org/build/171861022) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171853407) [haskell.packages.ghc902](https://hydra.nixos.org/eval/1753097?filter=haskell.packages.ghc902.cabal2nix-unstable)
  - [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171867516) [[:apple::no_entry_sign:]](https://hydra.nixos.org/build/171853652) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171870147) [haskell.packages.ghc922](https://hydra.nixos.org/eval/1753097?filter=haskell.packages.ghc922.cabal2nix-unstable)
  - [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/171854362) [[:apple::no_entry_sign:]](https://hydra.nixos.org/build/171868781) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171856723) [haskellPackages](https://hydra.nixos.org/eval/1753097?filter=haskellPackages.cabal2nix-unstable)
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171860325) [[:apple::no_entry_sign:]](https://hydra.nixos.org/build/171855637) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171857533) [haskellPackages.easytensor-vulkan](https://hydra.nixos.org/eval/1753097?filter=haskellPackages.easytensor-vulkan) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171858121) [[:apple::no_entry_sign:]](https://hydra.nixos.org/build/171862231) [[:penguin::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171866436) [haskellPackages.gladexml-accessor](https://hydra.nixos.org/eval/1753097?filter=haskellPackages.gladexml-accessor) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171865688) [[:apple::no_entry_sign:]](https://hydra.nixos.org/build/171854337) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171855100) [haskellPackages.gmail-simple](https://hydra.nixos.org/eval/1753097?filter=haskellPackages.gmail-simple) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171868867) [[:apple::no_entry_sign:]](https://hydra.nixos.org/build/171868614) [[:penguin::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171857531) [haskellPackages.gtk2hs-cast-glade](https://hydra.nixos.org/eval/1753097?filter=haskellPackages.gtk2hs-cast-glade) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171870428) [[:apple::no_entry_sign:]](https://hydra.nixos.org/build/171858251) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171854549) [haskellPackages.harfbuzz-pure](https://hydra.nixos.org/eval/1753097?filter=haskellPackages.harfbuzz-pure) 
- [ ] [[:iphone::no_entry_sign:]](https://hydra.nixos.org/build/171871601) [[:penguin::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171858128) [haskellPackages.hbro-contrib](https://hydra.nixos.org/eval/1753097?filter=haskellPackages.hbro-contrib) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171866703) [[:apple::no_entry_sign:]](https://hydra.nixos.org/build/171871268) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171866754) [haskellPackages.hmatrix-nlopt](https://hydra.nixos.org/eval/1753097?filter=haskellPackages.hmatrix-nlopt) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171866254) [[:apple::no_entry_sign:]](https://hydra.nixos.org/build/171855790) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171862052) [haskellPackages.hs-swisstable-hashtables-class](https://hydra.nixos.org/eval/1753097?filter=haskellPackages.hs-swisstable-hashtables-class) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171861405) [[:apple::no_entry_sign:]](https://hydra.nixos.org/build/171860375) [[:penguin::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171870227) [haskellPackages.hstzaar](https://hydra.nixos.org/eval/1753097?filter=haskellPackages.hstzaar) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171854322) [[:apple::no_entry_sign:]](https://hydra.nixos.org/build/171867825) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171867437) [haskellPackages.hw-simd-cli](https://hydra.nixos.org/eval/1753097?filter=haskellPackages.hw-simd-cli) 
- [ ] [[:penguin::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171866737) [hyper-haskell-server-with-packages](https://hydra.nixos.org/eval/1753097?filter=hyper-haskell-server-with-packages) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171852954) [[:apple::no_entry_sign:]](https://hydra.nixos.org/build/171855424) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171857097) [haskellPackages.kmn-programming](https://hydra.nixos.org/eval/1753097?filter=haskellPackages.kmn-programming) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171854446) [[:apple::no_entry_sign:]](https://hydra.nixos.org/build/171856086) [[:penguin::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171871179) [haskellPackages.minesweeper](https://hydra.nixos.org/eval/1753097?filter=haskellPackages.minesweeper) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171861619) [[:apple::no_entry_sign:]](https://hydra.nixos.org/build/171865359) [[:penguin::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171865363) [haskellPackages.nymphaea](https://hydra.nixos.org/eval/1753097?filter=haskellPackages.nymphaea) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171860662) [[:apple::no_entry_sign:]](https://hydra.nixos.org/build/171864364) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171865436) [haskellPackages.opentelemetry-lightstep](https://hydra.nixos.org/eval/1753097?filter=haskellPackages.opentelemetry-lightstep) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171866916) [[:apple::no_entry_sign:]](https://hydra.nixos.org/build/171868635) [[:penguin::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171870211) [haskellPackages.proplang](https://hydra.nixos.org/eval/1753097?filter=haskellPackages.proplang) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171856486) [[:apple::no_entry_sign:]](https://hydra.nixos.org/build/171857832) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171868931) [haskellPackages.rounded-hw](https://hydra.nixos.org/eval/1753097?filter=haskellPackages.rounded-hw) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171854594) [[:apple::no_entry_sign:]](https://hydra.nixos.org/build/171863195) [[:penguin::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171853207) [haskellPackages.showdown](https://hydra.nixos.org/eval/1753097?filter=haskellPackages.showdown) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171866136) [[:apple::no_entry_sign:]](https://hydra.nixos.org/build/171858760) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171866282) [haskellPackages.sound-collage](https://hydra.nixos.org/eval/1753097?filter=haskellPackages.sound-collage) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171867998) [[:apple::no_entry_sign:]](https://hydra.nixos.org/build/171857056) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171863068) [haskellPackages.unicode-names](https://hydra.nixos.org/eval/1753097?filter=haskellPackages.unicode-names) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171857516) [[:apple::no_entry_sign:]](https://hydra.nixos.org/build/171854226) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171868675) [haskellPackages.warp-quic](https://hydra.nixos.org/eval/1753097?filter=haskellPackages.warp-quic) 
</details>

#### Top 50 broken packages, sorted by number of reverse dependencies
<details><summary>50 job(s) </summary>

[amazonka-core](https://packdeps.haskellers.com/reverse/amazonka-core) :arrow_heading_up: 186  
[gogol-core](https://packdeps.haskellers.com/reverse/gogol-core) :arrow_heading_up: 184  
[haskell98](https://packdeps.haskellers.com/reverse/haskell98) :arrow_heading_up: 153  
[enumerator](https://packdeps.haskellers.com/reverse/enumerator) :arrow_heading_up: 56  
[derive](https://packdeps.haskellers.com/reverse/derive) :arrow_heading_up: 48  
[amazonka](https://packdeps.haskellers.com/reverse/amazonka) :arrow_heading_up: 44  
[accelerate](https://packdeps.haskellers.com/reverse/accelerate) :arrow_heading_up: 42  
[parseargs](https://packdeps.haskellers.com/reverse/parseargs) :arrow_heading_up: 42  
[syb-with-class](https://packdeps.haskellers.com/reverse/syb-with-class) :arrow_heading_up: 42  
[MonadCatchIO-transformers](https://packdeps.haskellers.com/reverse/MonadCatchIO-transformers) :arrow_heading_up: 41  
[data-lens](https://packdeps.haskellers.com/reverse/data-lens) :arrow_heading_up: 33  
[rank1dynamic](https://packdeps.haskellers.com/reverse/rank1dynamic) :arrow_heading_up: 33  
[distributed-static](https://packdeps.haskellers.com/reverse/distributed-static) :arrow_heading_up: 31  
[language-ecmascript](https://packdeps.haskellers.com/reverse/language-ecmascript) :arrow_heading_up: 31  
[distributed-process](https://packdeps.haskellers.com/reverse/distributed-process) :arrow_heading_up: 30  
[autodocodec](https://packdeps.haskellers.com/reverse/autodocodec) :arrow_heading_up: 29  
[ip](https://packdeps.haskellers.com/reverse/ip) :arrow_heading_up: 29  
[iteratee](https://packdeps.haskellers.com/reverse/iteratee) :arrow_heading_up: 29  
[jmacro](https://packdeps.haskellers.com/reverse/jmacro) :arrow_heading_up: 29  
[text-format](https://packdeps.haskellers.com/reverse/text-format) :arrow_heading_up: 28  
[mmsyn3](https://packdeps.haskellers.com/reverse/mmsyn3) :arrow_heading_up: 27  
[crypto-numbers](https://packdeps.haskellers.com/reverse/crypto-numbers) :arrow_heading_up: 26  
[validity-aeson](https://packdeps.haskellers.com/reverse/validity-aeson) :arrow_heading_up: 26  
[either-unwrap](https://packdeps.haskellers.com/reverse/either-unwrap) :arrow_heading_up: 25  
[autodocodec-schema](https://packdeps.haskellers.com/reverse/autodocodec-schema) :arrow_heading_up: 24  
[web-routes-th](https://packdeps.haskellers.com/reverse/web-routes-th) :arrow_heading_up: 24  
[autodocodec-yaml](https://packdeps.haskellers.com/reverse/autodocodec-yaml) :arrow_heading_up: 23  
[crypto-pubkey](https://packdeps.haskellers.com/reverse/crypto-pubkey) :arrow_heading_up: 23  
[ixset-typed](https://packdeps.haskellers.com/reverse/ixset-typed) :arrow_heading_up: 23  
[haskelldb](https://packdeps.haskellers.com/reverse/haskelldb) :arrow_heading_up: 22  
[wxdirect](https://packdeps.haskellers.com/reverse/wxdirect) :arrow_heading_up: 22  
[amazonka-s3](https://packdeps.haskellers.com/reverse/amazonka-s3) :arrow_heading_up: 21  
[mmsyn2](https://packdeps.haskellers.com/reverse/mmsyn2) :arrow_heading_up: 21  
[subG](https://packdeps.haskellers.com/reverse/subG) :arrow_heading_up: 21  
[userid](https://packdeps.haskellers.com/reverse/userid) :arrow_heading_up: 21  
[wxc](https://packdeps.haskellers.com/reverse/wxc) :arrow_heading_up: 21  
[biocore](https://packdeps.haskellers.com/reverse/biocore) :arrow_heading_up: 20  
[sydtest](https://packdeps.haskellers.com/reverse/sydtest) :arrow_heading_up: 20  
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
