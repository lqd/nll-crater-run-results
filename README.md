### Status Guide

- `X` -- still a bug
- `+` -- compiles now
- `F` -- still fails to compile, but appears to be legit

---

### Crates that are still broken

| Crate                  | Version      | Status | Minimized | Issue      | Notes |
| -----                  | ---          | ---    | ---       | ---        | ---   |
| `attr`                 | [0.1.0][aw]  | X      | [2][]     | [#53569][] | |
| `proptest-arbitrary`   | [0.2.2][av]  | X?     | [18][] [19][] | [#53789][] | |
| `shred`                | [0.7.0][au]  | X      | [7][]     | [#53121][] | |

---

### Crates where errors were either fixed or are correct

| Crate                  | Version      | Status | Minimized | Issue      | Notes |
| -----                  | ---          | ---    | ---       | ---        | ---   |
| `argdata`              | 0.0.4        | +      | [1][]     |            | |
| `brassfibre`           | 0.2.0        | +      |           |            | |
| `capnp`                | [0.6.2][as]  | F      |           |            | same as 0.7.5
| `capnp`                | [0.7.5][ar]  | F      |           |            | [#47349][] (diagnostics)
| `chiisai`              | [0.1.6][aq]  | F      |           |            | [#53432][]
| `clucstr`              | 0.1.3        | +      |           |            | |
| `embed`                | 0.1.1        | +      |           |            | |
| `envelope`             | 0.8.1        | +      | [3][]     |            | |
| `extended-collections` | [0.1.0][ap]  | F      |           | [#51915][] | wants a more aggressive 2PB |
| `extended-collections` | [0.2.0][ao]  | F      | [9][]     | [#51915][] | wants a more aggressive 2PB |
| `fractions_and_matrices` | 2ea35      | F      |           |            | [#47349][] (diagnostics)
| `fred`                 | [0.1.6][an]  | F      | [21][] [22][] |        | [#53432][]
| `fscmp`                | 0.1.1        | +      |           |            | |
| `galvanize`            | [0.0.1][am]  | F      | [10][]    |            | [#52059][] (diagnostics) |
| `gearley`              | [0.0.1][al]  | F      |           |            | |
| `getopts`              | [0.2.14][ak] | F      |           |            | similar to 0.2.15 |
| `getopts`              | [0.2.15][aj] | F      |           |            | FIXME: find an issue link |
| `gluon_base`           | 0.6.2        | +      |           | [#53119][] | similar to 0.8.0 |
| `gluon_base`           | 0.8.0        | +      |           | [#53119][] | |
| `gluon_vm`             | [0.8.1][ai]  | F      | [23][] [24][] [25][]|  | [#52059][] (diagnostics) 
| `ilp-packet`           | [0.3.0][ah]  | F      | [4][]     |            | FIXME: find an issue link |
| `jmespath-macros`      | 0.1.1        | +      |           |            | |
| `liner`                | [0.4.4][ag]  | F      | [17][]    |            | |
| `LocustDB`             | c59429       | +      | [11][]    | [#53570][] | |
| `mop-solvers`          | [0.0.1][af]  | F      |           |            | [#47349][] (diagnostics) |
| `nalgebra`             | [0.11.2][ae] | F      |           |            | same as 0.16.1 |
| `nalgebra`             | [0.12.3][ad] | F      |           |            | same as 0.16.1 |
| `nalgebra`             | [0.13.1][ac] | F      |           |            | same as 0.16.1 |
| `nalgebra`             | [0.14.4][ab] | F      |           |            | same as 0.16.1 |
| `nalgebra`             | [0.15.3][aa] | F      |           |            | same as 0.16.1 |
| `nalgebra`             | [0.16.0][z]  | F      |           |            | same as 0.16.1 |
| `nalgebra`             | [0.16.1][at] | F      |           |            | [#47349][] (diagnostics) |
| `ocl`                  | [0.18.0][y]  | F      | [26][]    |            | |
| `pear_codegen`         | 0.0.18       | +      |           |            | |
| `pgetopts`             | [0.1.2][x]   | F      | [5][]     |            | FIXME: find an issue link |
| `phf_macros`           | 0.7.22       | +      |           |            | |
| `pom`                  | [2.0.1 ][w]  | F      | [20][]    |[#53040][]? | FIXME: confirm / + needs diagnostics issue ? |
| `rgen3-save`           | [0.1.0 ][v]  | F      | [6][]     |            | might be a case for 2Phi borrows |
| `rome`                 | 0.1.2        | +      |           |            | |
| `rs-graph`             | [0.14.0][u]  | F      |           |            | same as 0.14.1 |
| `rs-graph`             | [0.14.1][t]  | F      | [15][] [16][] |        | [#53121][]? and [#47349][] (diagnostics) |
| `rusttype`             | [0.2.1][s]   | F      |           |            | same as 0.2.3 |
| `rusttype`             | [0.2.3][r]   | F      |           |            | [#29149][] |
| `rustysecrets`         | [38f98][q]   | F      | [12][]    |            | [#47349][] (diagnostics) |
| `segment-tree`         | [1.1.0][p]   | F (tests) |        |            | [#47349][] (diagnostics) |
| `serenity`             | [0.4.8][o]   | F      | [14][]    |            | |
| `speculate`            | 0.0.26       | +      |           |            | |
| `sprs`                 | [0.6.2][n]   | F      |           |            | [#47349][] (diagnostics) |
| `swear`                | 0.1.0        | +      |           |            | |
| `syntex_syntax`        | [0.36.0][m]  | F      |           |            | same as 0.39.0 |
| `syntex_syntax`        | [0.39.0][l]  | F      | [13][]    |            | |
| `tarpc-plugins`        | 0.3.0        | +      |           |            | |
| `try_transform_mut`    | 0.1.0        | +      | [8][]     | [#53123][] | |
| `unicode_names2_macros` | 0.2.0       | +      |           |            | |
| `url`                  | [1.1.1][k]   | F      |           |            | similar to 1.7.0
| `url`                  | [1.2.3][j]   | F      |           |            | similar to 1.7.0
| `url`                  | [1.2.4][i]   | F      |           |            | similar to 1.7.0
| `url`                  | [1.4.0][h]   | F      |           |            | similar to 1.7.0
| `url`                  | [1.4.1][g]   | F      |           |            | similar to 1.7.0
| `url`                  | [1.5.0][f]   | F      |           |            | similar to 1.7.0
| `url`                  | [1.5.1][e]   | F      |           |            | similar to 1.7.0
| `url`                  | [1.6.0][d]   | F      |           |            | similar to 1.7.0
| `url`                  | [1.7.0][c]   | F      |           |            | |
| `vek`                  | [0.9.4][b]   | F      |           |            | [#47349][] (diagnostics) |
| `yara`                 | [0.1.0][a]   | F      |           |            | [#52059][] (diagnostics) |


[1]: https://play.rust-lang.org/?gist=1e7555092563371569caadb0d35b897c&version=nightly&mode=debug&edition=2015
[2]: https://play.rust-lang.org/?gist=46146e256a3e138cbd42d0ee34b43571&version=nightly&mode=debug&edition=2015
[3]: https://play.rust-lang.org/?gist=d3eedb59571edff7d7ff0975c44e8faa&version=nightly&mode=debug&edition=2015
[4]: https://play.rust-lang.org/?gist=fcd15716ab77c5aaf787471a87beebb2&version=nightly&mode=debug&edition=2015
[5]: https://play.rust-lang.org/?gist=8c34aede2762d2bb408f98a0e004f514&version=nightly&mode=debug&edition=2015
[#53114]: https://github.com/rust-lang/rust/issues/53114
[#53119]: https://github.com/rust-lang/rust/issues/53119
[6]: https://play.rust-lang.org/?gist=104d7f51c89e5d6b332dfd7e9090d6a2&version=nightly&mode=debug&edition=2015
[7]: https://gist.github.com/nikomatsakis/e795e4f05bf7119540f351927e1965e6
[8]: https://play.rust-lang.org/?gist=018e37797b3965890528ef25791bce50&version=nightly&mode=debug&edition=2015
[#52059]: https://github.com/rust-lang/rust/issues/52059
[#53121]: https://github.com/rust-lang/rust/issues/53121
[#53123]: https://github.com/rust-lang/rust/issues/53123
[#51915]: https://github.com/rust-lang/rust/issues/51915
[9]: https://play.rust-lang.org/?gist=0265b0131f94793854ab1b7b1c96369e&version=nightly&mode=debug&edition=2015
[#47349]: https://github.com/rust-lang/rust/issues/47349
[10]: https://play.rust-lang.org/?gist=f3c0638cd128773bfa2413e3d3ec3783&version=nightly&mode=debug&edition=2015
[#53569]: https://github.com/rust-lang/rust/issues/53569
[11]: https://play.rust-lang.org/?gist=a051d535a66f46f52ceb271383d334d5&version=nightly&mode=debug&edition=2015
[#53570]: https://github.com/rust-lang/rust/issues/53570
[12]: https://play.rust-lang.org/?gist=b6e2b7ba1f746b2a91f237cbe2892f74&version=nightly&mode=debug&edition=2015
[13]: https://play.rust-lang.org/?gist=2d4da1787e06a75def402cfe1f9e544e&version=nightly&mode=debug&edition=2015
[#29149]: https://github.com/rust-lang/rust/issues/29149
[14]: https://play.rust-lang.org/?gist=36b94633fca7e490ba8c03f4fa94cbbd&version=nightly&mode=debug&edition=2015
[#53040]: https://github.com/rust-lang/rust/issues/53040
[15]: https://play.rust-lang.org/?gist=f82cedfca0a942938d8fedf3f869c0cd&version=nightly&mode=debug&edition=2015
[16]: https://play.rust-lang.org/?gist=72ff07aa838d8e4aacb283181e2a0824&version=nightly&mode=debug&edition=2015
[17]: https://play.rust-lang.org/?gist=7f96eeac405c6f2316fdc794c1631124&version=nightly&mode=debug&edition=2015
[#53789]: https://github.com/rust-lang/rust/issues/53789
[18]: https://play.rust-lang.org/?gist=c990af931ab56d93207efcade0ffd01b&version=nightly&mode=debug&edition=2015
[19]: https://play.rust-lang.org/?gist=1f1d03d4f8280b8843594cba668c9db4&version=nightly&mode=debug&edition=2015
[20]: https://play.rust-lang.org/?gist=c6a5e5dcf99e04855350770b62528486&version=nightly&mode=debug&edition=2015
[chiisai]: https://crater-reports.s3.amazonaws.com/pr-53426-2/try%23e3ede4ae5297558caacf160ecf523f3a5759f682/reg/chiisai-0.1.6/log.txt
[#53432]: https://github.com/rust-lang/rust/issues/53432
[21]: https://play.rust-lang.org/?gist=448e4a6646e0048b027b03f607a612dc&version=nightly&mode=debug&edition=2015
[22]: https://play.rust-lang.org/?gist=b61db3de15c2c0716d76d7e5df9abb02&version=nightly&mode=debug&edition=2015
[23]: https://play.rust-lang.org/?gist=2869a3fead3981815e077700d68de8eb&version=nightly&mode=debug&edition=2015
[24]: https://play.rust-lang.org/?gist=d404421b51edcb0c2d6fb700a313be95&version=nightly&mode=debug&edition=2015
[25]: https://play.rust-lang.org/?gist=f16c92102d7c16ec4feda59814ba7cf9&version=nightly&mode=debug&edition=2015
[26]: https://play.rust-lang.org/?gist=1ddf9aa2d1bc3e96066576c2b4b05df3&version=nightly&mode=debug&edition=2015
[a]: https://crater-reports.s3.amazonaws.com/pr-53426-2/try%23e3ede4ae5297558caacf160ecf523f3a5759f682/reg/yara-0.1.0/log.txt
[b]: https://crater-reports.s3.amazonaws.com/pr-53426-2/try%23e3ede4ae5297558caacf160ecf523f3a5759f682/reg/vek-0.9.4/log.txt
[c]: https://crater-reports.s3.amazonaws.com/pr-53426-2/try%23e3ede4ae5297558caacf160ecf523f3a5759f682/gh/Acizza.bcnotif/log.txt
[d]: https://crater-reports.s3.amazonaws.com/pr-53426-2/try%23e3ede4ae5297558caacf160ecf523f3a5759f682/gh/TuBieJun.consensus/log.txt
[e]: https://crater-reports.s3.amazonaws.com/pr-53426-2/try%23e3ede4ae5297558caacf160ecf523f3a5759f682/reg/crust-0.28.1/log.txt
[f]: https://crater-reports.s3.amazonaws.com/pr-53426-2/try%23e3ede4ae5297558caacf160ecf523f3a5759f682/gh/coredump-ch.status/log.txt
[g]: https://crater-reports.s3.amazonaws.com/pr-53426-2/try%23e3ede4ae5297558caacf160ecf523f3a5759f682/reg/razberry-0.3.0/log.txt
[h]: https://crater-reports.s3.amazonaws.com/pr-53426-2/try%23e3ede4ae5297558caacf160ecf523f3a5759f682/gh/Fitzsimmons.cmdipass/log.txt
[i]: https://crater-reports.s3.amazonaws.com/pr-53426-2/try%23e3ede4ae5297558caacf160ecf523f3a5759f682/reg/ruroonga_client-0.5.1/log.txt
[j]: https://crater-reports.s3.amazonaws.com/pr-53426-2/try%23e3ede4ae5297558caacf160ecf523f3a5759f682/gh/BlakeWilliams.slack_markov/log.txt
[k]: https://crater-reports.s3.amazonaws.com/pr-53426-2/try%23e3ede4ae5297558caacf160ecf523f3a5759f682/reg/iron-middleware-mysql-0.0.2/log.txt
[l]: https://crater-reports.s3.amazonaws.com/pr-53426-2/try%23e3ede4ae5297558caacf160ecf523f3a5759f682/reg/cucumber-0.1.3/log.txt
[m]: https://crater-reports.s3.amazonaws.com/pr-53426-2/try%23e3ede4ae5297558caacf160ecf523f3a5759f682/reg/serde_item-0.2.0/log.txt
[n]: https://crater-reports.s3.amazonaws.com/pr-53426-2/try%23e3ede4ae5297558caacf160ecf523f3a5759f682/reg/sprs-0.6.2/log.txt
[o]: https://crater-reports.s3.amazonaws.com/pr-53426-2/try%23e3ede4ae5297558caacf160ecf523f3a5759f682/reg/serenity-0.4.8/log.txt
[p]: https://crater-reports.s3.amazonaws.com/pr-53426-2/try%23e3ede4ae5297558caacf160ecf523f3a5759f682/reg/segment-tree-1.1.0/log.txt
[q]: https://crater-reports.s3.amazonaws.com/pr-53426-2/try%23e3ede4ae5297558caacf160ecf523f3a5759f682/gh/SpinResearch.RustySecrets/log.txt
[r]: https://crater-reports.s3.amazonaws.com/pr-53426-2/try%23e3ede4ae5297558caacf160ecf523f3a5759f682/reg/clipping-0.1.1/log.txt
[s]: https://crater-reports.s3.amazonaws.com/pr-53426-2/try%23e3ede4ae5297558caacf160ecf523f3a5759f682/gh/AlexW-GH.rust8/log.txt
[t]: https://crater-reports.s3.amazonaws.com/pr-53426-2/try%23e3ede4ae5297558caacf160ecf523f3a5759f682/reg/rs-graph-0.14.1/log.txt
[u]: https://crater-reports.s3.amazonaws.com/pr-53426/a5d98b025f62ace80fe9d2a15781f900fc42515e-alt/reg/rs-graph-0.14.0/log.txt
[v]: https://crater-reports.s3.amazonaws.com/pr-53426-2/try%23e3ede4ae5297558caacf160ecf523f3a5759f682/reg/rgen3-save-0.1.0/log.txt
[w]: https://crater-reports.s3.amazonaws.com/pr-53426-2/try%23e3ede4ae5297558caacf160ecf523f3a5759f682/reg/pom-2.0.1/log.txt
[x]: https://crater-reports.s3.amazonaws.com/pr-53426-2/try%23e3ede4ae5297558caacf160ecf523f3a5759f682/reg/pgetopts-0.1.2/log.txt
[y]: https://crater-reports.s3.amazonaws.com/pr-53426-2/try%23e3ede4ae5297558caacf160ecf523f3a5759f682/reg/nano-work-server-0.1.6/log.txt
[z]: https://crater-reports.s3.amazonaws.com/pr-53426-2/try%23e3ede4ae5297558caacf160ecf523f3a5759f682/reg/nalgebra-0.16.0/log.txt
[aa]: https://crater-reports.s3.amazonaws.com/pr-53426-2/try%23e3ede4ae5297558caacf160ecf523f3a5759f682/reg/cosmogony-0.3.1/log.txt
[ab]: https://crater-reports.s3.amazonaws.com/pr-53426-2/try%23e3ede4ae5297558caacf160ecf523f3a5759f682/reg/bbox-0.8.2/log.txt
[ac]: https://crater-reports.s3.amazonaws.com/pr-53426-2/try%23e3ede4ae5297558caacf160ecf523f3a5759f682/reg/annatar-0.4.0/log.txt
[ad]: https://crater-reports.s3.amazonaws.com/pr-53426-2/try%23e3ede4ae5297558caacf160ecf523f3a5759f682/reg/softrender-0.1.0/log.txt
[ae]: https://crater-reports.s3.amazonaws.com/pr-53426-2/try%23e3ede4ae5297558caacf160ecf523f3a5759f682/reg/ahrs-0.2.0/log.txt
[af]: https://crater-reports.s3.amazonaws.com/pr-53426/a5d98b025f62ace80fe9d2a15781f900fc42515e-alt/reg/mop-solvers-0.0.1/log.txt
[ag]: https://crater-reports.s3.amazonaws.com/pr-53426-2/try%23e3ede4ae5297558caacf160ecf523f3a5759f682/reg/calculate-0.5.1/log.txt
[ah]: https://crater-reports.s3.amazonaws.com/pr-53426-2/try%23e3ede4ae5297558caacf160ecf523f3a5759f682/reg/ilp-packet-0.3.0/log.txt
[ai]: https://crater-reports.s3.amazonaws.com/pr-53426-2/try%23e3ede4ae5297558caacf160ecf523f3a5759f682/reg/gluon_codegen-0.8.1/log.txt
[aj]: https://crater-reports.s3.amazonaws.com/pr-53426-2/try%23e3ede4ae5297558caacf160ecf523f3a5759f682/gh/accidentalrebel.csv-to-json/log.txt
[ak]: https://crater-reports.s3.amazonaws.com/pr-53426-2/try%23e3ede4ae5297558caacf160ecf523f3a5759f682/reg/rpc-perf-2.0.3/log.txt
[al]: https://crater-reports.s3.amazonaws.com/pr-53426-2/try%23e3ede4ae5297558caacf160ecf523f3a5759f682/reg/gearley-0.0.1/log.txt
[am]: https://crater-reports.s3.amazonaws.com/pr-53426-2/try%23e3ede4ae5297558caacf160ecf523f3a5759f682/reg/galvanize-0.0.1/log.txt
[an]: https://crater-reports.s3.amazonaws.com/pr-53426-2/try%23e3ede4ae5297558caacf160ecf523f3a5759f682/reg/fred-0.1.6/log.txt
[ao]: https://crater-reports.s3.amazonaws.com/pr-53426-2/try%23e3ede4ae5297558caacf160ecf523f3a5759f682/reg/extended-collections-0.2.0/log.txt
[ap]: https://crater-reports.s3.amazonaws.com/pr-53426-2/try%23e3ede4ae5297558caacf160ecf523f3a5759f682/reg/extended-collections-0.1.0/log.txt
[aq]: https://crater-reports.s3.amazonaws.com/pr-53426-2/try%23e3ede4ae5297558caacf160ecf523f3a5759f682/reg/chiisai-0.1.6/log.txt
[ar]: https://crater-reports.s3.amazonaws.com/pr-53426-2/try%23e3ede4ae5297558caacf160ecf523f3a5759f682/reg/capnp-gj-0.2.1/log.txt
[as]: https://crater-reports.s3.amazonaws.com/pr-53426-2/try%23e3ede4ae5297558caacf160ecf523f3a5759f682/reg/rotor-capnp-0.1.0/log.txt
[at]: https://crater-reports.s3.amazonaws.com/pr-53426-2/try%23e3ede4ae5297558caacf160ecf523f3a5759f682/reg/bvh-0.2.3/log.txt
[au]: https://crater-reports.s3.amazonaws.com/pr-53426-2/try%23e3ede4ae5297558caacf160ecf523f3a5759f682/reg/amethyst_animation-0.3.0/log.txt
[av]: https://crater-reports.s3.amazonaws.com/pr-53426-2/try%23e3ede4ae5297558caacf160ecf523f3a5759f682/reg/proptest-arbitrary-0.2.2/log.txt
[aw]: https://crater-reports.s3.amazonaws.com/pr-53426-2/try%23e3ede4ae5297558caacf160ecf523f3a5759f682/reg/attr-0.1.0/log.txt
