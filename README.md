### [haskell-updates build report from hydra](https://hydra.nixos.org/jobset/nixpkgs/haskell-updates)
*evaluation [1753305](https://hydra.nixos.org/eval/1753305) of nixpkgs commit [2e8743b](https://github.com/NixOS/nixpkgs/commits/2e8743b8e53638d8af54c74c023e0bb317557afb) as of 2022-04-05 12:21 UTC*

:yellow_circle: **Potential issues**
  * `maintained` jobset failed.
  * `mergeable` jobset is not finished.

#### Build summary

 | Platform | Failed :x: | DependencyFailed :heavy_exclamation_mark: | TimedOut :hourglass::no_entry_sign: | Unfinished :hourglass_flowing_sand: | Success :heavy_check_mark: | 
 | --- | --- | --- | --- | --- | --- | 
 | [aarch64-linux :iphone:](https://hydra.nixos.org/eval/1753305?filter=.aarch64-linux) | 32 | 40 | 8 |  | 6205 | 
 | [x86_64-darwin :apple:](https://hydra.nixos.org/eval/1753305?filter=.x86_64-darwin) | 2 | 3 |  | 5560 | 678 | 
 | [x86_64-linux :penguin:](https://hydra.nixos.org/eval/1753305?filter=.x86_64-linux) | 10 | 17 | 8 | 1 | 6283 | 
#### Maintained packages with build failure
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/171870860) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/171859032) [[:penguin::x:]](https://hydra.nixos.org/build/171861365) [haskellPackages.graphql-parser](https://hydra.nixos.org/eval/1753305?filter=haskellPackages.graphql-parser) @Lassulus
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/171864019) [[:apple::x:]](https://hydra.nixos.org/build/171857799) [[:penguin::x:]](https://hydra.nixos.org/build/171864031) [hasura-graphql-engine](https://hydra.nixos.org/eval/1753305?filter=hasura-graphql-engine) @Lassulus
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/171859461) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/171863997) [[:penguin::x:]](https://hydra.nixos.org/build/171869976) [jl](https://hydra.nixos.org/eval/1753305?filter=jl) @fgaz
#### Maintained packages with failed dependency
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171866991) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/171865101) [[:penguin::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171870149) [haskellPackages.graphql-engine](https://hydra.nixos.org/eval/1753305?filter=haskellPackages.graphql-engine) @Lassulus
- [ ] [[:penguin::heavy_exclamation_mark:]](https://hydra.nixos.org/build/172115932) [maintained](https://hydra.nixos.org/eval/1753305?filter=maintained) @cdepillabout @expipiplus1 @maralorn @sternenseemann
- [ ] [spago](https://hydra.nixos.org/eval/1753305?filter=spago) @cdepillabout
  - [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171861126) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/171871490) [[:penguin::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171852877) [toplevel](https://hydra.nixos.org/eval/1753305?filter=spago)
  - [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171862357) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/171866857) [[:penguin::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171869812) [haskellPackages](https://hydra.nixos.org/eval/1753305?filter=haskellPackages.spago)
#### Unmaintained packages with build failure
<details><summary>34 job(s) </summary>

- [ ] [QuickCheck](https://hydra.nixos.org/eval/1753305?filter=QuickCheck)  :arrow_heading_up: 1236 | 4755
  - [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/171855138) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/171858360) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171859376) [haskellPackages](https://hydra.nixos.org/eval/1753305?filter=haskellPackages.QuickCheck)
  -   [[:penguin::x:]](https://hydra.nixos.org/build/171869550) [pkgsStatic.haskell.packages.integer-simple.ghc8107](https://hydra.nixos.org/eval/1753305?filter=pkgsStatic.haskell.packages.integer-simple.ghc8107.QuickCheck)
  -   [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171857722) [pkgsStatic.haskell.packages.native-bignum.ghc902](https://hydra.nixos.org/eval/1753305?filter=pkgsStatic.haskell.packages.native-bignum.ghc902.QuickCheck)
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/171870158) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/171857210) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171867668) [haskellPackages.OrderedBits](https://hydra.nixos.org/eval/1753305?filter=haskellPackages.OrderedBits)  :arrow_heading_up: 5 | 36
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/171865966) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/171870109) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171858915) [haskellPackages.ptr-poker](https://hydra.nixos.org/eval/1753305?filter=haskellPackages.ptr-poker)  :arrow_heading_up: 3 | 3
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/171855578) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/171865205) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171857596) [haskellPackages.hw-json-simd](https://hydra.nixos.org/eval/1753305?filter=haskellPackages.hw-json-simd)  :arrow_heading_up: 2 | 8
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/171856342) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/171870086) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171862699) [haskellPackages.hw-simd](https://hydra.nixos.org/eval/1753305?filter=haskellPackages.hw-simd)  :arrow_heading_up: 2 | 8
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/171862898) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/171861026) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171862442) [haskellPackages.quic](https://hydra.nixos.org/eval/1753305?filter=haskellPackages.quic)  :arrow_heading_up: 2 | 2
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/171855175) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/171869070) [[:penguin::x:]](https://hydra.nixos.org/build/171864450) [haskellPackages.bower-json](https://hydra.nixos.org/eval/1753305?filter=haskellPackages.bower-json)  :arrow_heading_up: 1 | 10
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/171865184) [[:apple::x:]](https://hydra.nixos.org/build/171854810) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171866663) [haskellPackages.junit-xml](https://hydra.nixos.org/eval/1753305?filter=haskellPackages.junit-xml)  :arrow_heading_up: 1 | 9
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/171860843) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/171860724) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171871830) [haskellPackages.freetype2](https://hydra.nixos.org/eval/1753305?filter=haskellPackages.freetype2)  :arrow_heading_up: 1 | 8
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/171856730) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/171855544) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171864198) [haskellPackages.long-double](https://hydra.nixos.org/eval/1753305?filter=haskellPackages.long-double)  :arrow_heading_up: 1 | 2
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/171857435) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/171870314) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171862125) [haskellPackages.easytensor](https://hydra.nixos.org/eval/1753305?filter=haskellPackages.easytensor)  :arrow_heading_up: 1 | 1
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/171867377) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/171870936) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171861161) [haskellPackages.nlopt-haskell](https://hydra.nixos.org/eval/1753305?filter=haskellPackages.nlopt-haskell)  :arrow_heading_up: 1 | 1
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/171854078) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/171862942) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171857572) [haskellPackages.swisstable](https://hydra.nixos.org/eval/1753305?filter=haskellPackages.swisstable)  :arrow_heading_up: 1 | 1
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/171857072) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/171867045) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171852967) [haskellPackages.unicode-properties](https://hydra.nixos.org/eval/1753305?filter=haskellPackages.unicode-properties)  :arrow_heading_up: 1 | 1
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/171860343) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/171853368) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171861052) [haskellPackages.picosat](https://hydra.nixos.org/eval/1753305?filter=haskellPackages.picosat)  :arrow_heading_up: 0 | 1
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/171864526) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/171859855) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171863492) [haskellPackages.simple-vec3](https://hydra.nixos.org/eval/1753305?filter=haskellPackages.simple-vec3)  :arrow_heading_up: 0 | 1
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/171856051) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/171852793) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171858315) [haskellPackages.HsASA](https://hydra.nixos.org/eval/1753305?filter=haskellPackages.HsASA) 
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/171865682) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/171870312) [[:penguin::x:]](https://hydra.nixos.org/build/171865338) [haskellPackages.capataz](https://hydra.nixos.org/eval/1753305?filter=haskellPackages.capataz) 
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/171862589) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/171856354) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171857405) [haskellPackages.comfort-fftw](https://hydra.nixos.org/eval/1753305?filter=haskellPackages.comfort-fftw) 
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/171854581) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171858611) [haskellPackages.gnome-keyring](https://hydra.nixos.org/eval/1753305?filter=haskellPackages.gnome-keyring) 
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/171864576) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/171857616) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171871380) [haskellPackages.hls-rename-plugin](https://hydra.nixos.org/eval/1753305?filter=haskellPackages.hls-rename-plugin) 
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/171854418) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/171864129) [[:penguin::x:]](https://hydra.nixos.org/build/171859983) [haskellPackages.hyper-haskell-server](https://hydra.nixos.org/eval/1753305?filter=haskellPackages.hyper-haskell-server) 
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/171871047) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/171854882) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171868110) [haskellPackages.jammittools](https://hydra.nixos.org/eval/1753305?filter=haskellPackages.jammittools) 
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/171865092) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/171864375) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171856651) [haskellPackages.powerqueue-distributed](https://hydra.nixos.org/eval/1753305?filter=haskellPackages.powerqueue-distributed) 
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/171858796) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/171855508) [[:penguin::x:]](https://hydra.nixos.org/build/171864297) [haskellPackages.powerqueue-levelmem](https://hydra.nixos.org/eval/1753305?filter=haskellPackages.powerqueue-levelmem) 
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/171862860) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/171852904) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171862696) [haskellPackages.risc386](https://hydra.nixos.org/eval/1753305?filter=haskellPackages.risc386) 
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/171863691) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/171861382) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171860820) [haskellPackages.slugify](https://hydra.nixos.org/eval/1753305?filter=haskellPackages.slugify) 
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/171857697) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/171867036) [[:penguin::x:]](https://hydra.nixos.org/build/171853334) [haskellPackages.socketson](https://hydra.nixos.org/eval/1753305?filter=haskellPackages.socketson) 
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/171853926) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/171853832) [[:penguin::x:]](https://hydra.nixos.org/build/171862657) [haskellPackages.tripLL](https://hydra.nixos.org/eval/1753305?filter=haskellPackages.tripLL) 
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/171858390) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/171858351) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171865355) [haskellPackages.wiringPi](https://hydra.nixos.org/eval/1753305?filter=haskellPackages.wiringPi) 
- [ ] [[:iphone::x:]](https://hydra.nixos.org/build/171860405) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/171854831) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171858701) [haskellPackages.x86-64bit](https://hydra.nixos.org/eval/1753305?filter=haskellPackages.x86-64bit) 
</details>

#### Unmaintained packages with failed dependency
<details><summary>47 job(s) </summary>

- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171869570) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/171868602) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171857905) [haskellPackages.PrimitiveArray](https://hydra.nixos.org/eval/1753305?filter=haskellPackages.PrimitiveArray)  :arrow_heading_up: 4 | 35
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171859690) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/171855403) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171864366) [haskellPackages.BiobaseTypes](https://hydra.nixos.org/eval/1753305?filter=haskellPackages.BiobaseTypes)  :arrow_heading_up: 3 | 21
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171856446) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/171860436) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171854636) [haskellPackages.jsonifier](https://hydra.nixos.org/eval/1753305?filter=haskellPackages.jsonifier)  :arrow_heading_up: 2 | 2
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171856258) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/171858036) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171871240) [haskellPackages.BiobaseENA](https://hydra.nixos.org/eval/1753305?filter=haskellPackages.BiobaseENA)  :arrow_heading_up: 1 | 18
- [ ] [hoogle](https://hydra.nixos.org/eval/1753305?filter=hoogle)  :arrow_heading_up: 1 | 2
  - [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/171871347) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/171853429) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171867270) [haskell.packages.ghc8107](https://hydra.nixos.org/eval/1753305?filter=haskell.packages.ghc8107.hoogle)
  - [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/171868587) [[:apple::heavy_check_mark:]](https://hydra.nixos.org/build/171863488) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171867576) [haskell.packages.ghc884](https://hydra.nixos.org/eval/1753305?filter=haskell.packages.ghc884.hoogle)
  - [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/171852837) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/171868318) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171863678) [haskell.packages.ghc902](https://hydra.nixos.org/eval/1753305?filter=haskell.packages.ghc902.hoogle)
  - [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171865846) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/171864989) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171865459) [haskell.packages.ghc922](https://hydra.nixos.org/eval/1753305?filter=haskell.packages.ghc922.hoogle)
  - [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/171862778) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/171862396) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171869816) [haskellPackages](https://hydra.nixos.org/eval/1753305?filter=haskellPackages.hoogle)
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171862194) [[:penguin::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171865924) [haskellPackages.hbro](https://hydra.nixos.org/eval/1753305?filter=haskellPackages.hbro)  :arrow_heading_up: 1 | 1
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171857549) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/171865639) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171860183) [haskellPackages.http3](https://hydra.nixos.org/eval/1753305?filter=haskellPackages.http3)  :arrow_heading_up: 1 | 1
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171869964) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/171865623) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171869914) [haskellPackages.opentelemetry-extra](https://hydra.nixos.org/eval/1753305?filter=haskellPackages.opentelemetry-extra)  :arrow_heading_up: 1 | 1
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171868423) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/171871309) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171857039) [haskellPackages.BiobaseXNA](https://hydra.nixos.org/eval/1753305?filter=haskellPackages.BiobaseXNA)  :arrow_heading_up: 0 | 17
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/171863703) [[:apple::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171864040) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171870441) [haskellPackages.pretty-diff](https://hydra.nixos.org/eval/1753305?filter=haskellPackages.pretty-diff)  :arrow_heading_up: 0 | 12
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171867550) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/171865808) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171856273) [haskellPackages.hw-json-standard-cursor](https://hydra.nixos.org/eval/1753305?filter=haskellPackages.hw-json-standard-cursor)  :arrow_heading_up: 0 | 6
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171870416) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/171859949) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171869624) [haskellPackages.hw-json-simple-cursor](https://hydra.nixos.org/eval/1753305?filter=haskellPackages.hw-json-simple-cursor)  :arrow_heading_up: 0 | 4
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171867716) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/171861992) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171870240) [haskellPackages.BiobaseFasta](https://hydra.nixos.org/eval/1753305?filter=haskellPackages.BiobaseFasta)  :arrow_heading_up: 0 | 3
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171866331) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/171867791) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171865081) [haskellPackages.hw-dsv](https://hydra.nixos.org/eval/1753305?filter=haskellPackages.hw-dsv)  :arrow_heading_up: 0 | 3
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/171857188) [[:apple::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171858561) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171857818) [haskellPackages.libvirt-hs](https://hydra.nixos.org/eval/1753305?filter=haskellPackages.libvirt-hs)  :arrow_heading_up: 0 | 1
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171861978) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/171860974) [[:penguin::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171854273) [haskellPackages.GuiHaskell](https://hydra.nixos.org/eval/1753305?filter=haskellPackages.GuiHaskell) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171852847) [[:penguin::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171854687) [haskellPackages.HDRUtils](https://hydra.nixos.org/eval/1753305?filter=haskellPackages.HDRUtils) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171859005) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/171859432) [[:penguin::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171863511) [haskellPackages.HPlot](https://hydra.nixos.org/eval/1753305?filter=haskellPackages.HPlot) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171865737) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/171855961) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171868234) [haskellPackages.align-audio](https://hydra.nixos.org/eval/1753305?filter=haskellPackages.align-audio) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171859807) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/171858842) [[:penguin::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171864708) [haskellPackages.bluetile](https://hydra.nixos.org/eval/1753305?filter=haskellPackages.bluetile) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171860325) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/171855637) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171857533) [haskellPackages.easytensor-vulkan](https://hydra.nixos.org/eval/1753305?filter=haskellPackages.easytensor-vulkan) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171858121) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/171862231) [[:penguin::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171866436) [haskellPackages.gladexml-accessor](https://hydra.nixos.org/eval/1753305?filter=haskellPackages.gladexml-accessor) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171865688) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/171854337) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171855100) [haskellPackages.gmail-simple](https://hydra.nixos.org/eval/1753305?filter=haskellPackages.gmail-simple) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171868867) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/171868614) [[:penguin::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171857531) [haskellPackages.gtk2hs-cast-glade](https://hydra.nixos.org/eval/1753305?filter=haskellPackages.gtk2hs-cast-glade) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171870428) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/171858251) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171854549) [haskellPackages.harfbuzz-pure](https://hydra.nixos.org/eval/1753305?filter=haskellPackages.harfbuzz-pure) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171871601) [[:penguin::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171858128) [haskellPackages.hbro-contrib](https://hydra.nixos.org/eval/1753305?filter=haskellPackages.hbro-contrib) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171866703) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/171871268) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171866754) [haskellPackages.hmatrix-nlopt](https://hydra.nixos.org/eval/1753305?filter=haskellPackages.hmatrix-nlopt) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171866254) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/171855790) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171862052) [haskellPackages.hs-swisstable-hashtables-class](https://hydra.nixos.org/eval/1753305?filter=haskellPackages.hs-swisstable-hashtables-class) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171861405) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/171860375) [[:penguin::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171870227) [haskellPackages.hstzaar](https://hydra.nixos.org/eval/1753305?filter=haskellPackages.hstzaar) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171854322) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/171867825) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171867437) [haskellPackages.hw-simd-cli](https://hydra.nixos.org/eval/1753305?filter=haskellPackages.hw-simd-cli) 
- [ ] [[:penguin::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171866737) [hyper-haskell-server-with-packages](https://hydra.nixos.org/eval/1753305?filter=hyper-haskell-server-with-packages) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171852954) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/171855424) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171857097) [haskellPackages.kmn-programming](https://hydra.nixos.org/eval/1753305?filter=haskellPackages.kmn-programming) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171854446) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/171856086) [[:penguin::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171871179) [haskellPackages.minesweeper](https://hydra.nixos.org/eval/1753305?filter=haskellPackages.minesweeper) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171861619) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/171865359) [[:penguin::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171865363) [haskellPackages.nymphaea](https://hydra.nixos.org/eval/1753305?filter=haskellPackages.nymphaea) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171860662) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/171864364) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171865436) [haskellPackages.opentelemetry-lightstep](https://hydra.nixos.org/eval/1753305?filter=haskellPackages.opentelemetry-lightstep) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171866916) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/171868635) [[:penguin::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171870211) [haskellPackages.proplang](https://hydra.nixos.org/eval/1753305?filter=haskellPackages.proplang) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171856486) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/171857832) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171868931) [haskellPackages.rounded-hw](https://hydra.nixos.org/eval/1753305?filter=haskellPackages.rounded-hw) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171854594) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/171863195) [[:penguin::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171853207) [haskellPackages.showdown](https://hydra.nixos.org/eval/1753305?filter=haskellPackages.showdown) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171866136) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/171858760) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171866282) [haskellPackages.sound-collage](https://hydra.nixos.org/eval/1753305?filter=haskellPackages.sound-collage) 
- [ ] [[:iphone::heavy_check_mark:]](https://hydra.nixos.org/build/171861270) [[:apple::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171852803) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171860200) [haskellPackages.tasty-test-reporter](https://hydra.nixos.org/eval/1753305?filter=haskellPackages.tasty-test-reporter) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171867998) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/171857056) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171863068) [haskellPackages.unicode-names](https://hydra.nixos.org/eval/1753305?filter=haskellPackages.unicode-names) 
- [ ] [[:iphone::heavy_exclamation_mark:]](https://hydra.nixos.org/build/171857516) [[:apple::hourglass_flowing_sand:]](https://hydra.nixos.org/build/171854226) [[:penguin::heavy_check_mark:]](https://hydra.nixos.org/build/171868675) [haskellPackages.warp-quic](https://hydra.nixos.org/eval/1753305?filter=haskellPackages.warp-quic) 
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
