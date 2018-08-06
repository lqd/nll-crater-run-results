### Status Guide

- `X` -- still a bug
- `+` -- compiles now
- `F` -- still fails to compile, but appears to be legit

---

### Crates that are still broken

| Crate                  | Version | Status | Minimized | Issue      | Notes |
| -----                  | ---     | ---    | ---       | ---        | ---   |
| `argdata`              | 0.0.4   | X      | [1][]     |            | |
| `attr`                 | 0.1.0   | X      | [2][]     |            | |
| `extended-collections` | 0.1.0   | X      |           |            | like 0.2.0 |
| `extended-collections` | 0.2.0   | X      |           |            | 2PB expansion? #51915 |
| `gluon_base`           | 0.6.2   | X      |           |            | similar to 0.8.0 |
| `gluon_base`           | 0.8.0   | X      |           |            | similar to envelope-0.8.1 ? |
| `liner`                | 0.4.4   | X      |           | [#53114][] | |
| `nalgebra`             | 0.15.3  | X      |           |            | 2PB expansion? #51915 |
| `pear_codegen`         | 0.15.3  | X      |           |            | 2PB expansion? #51915 |
| `shred`                | 0.7.0   | X      | [7][]     |            | something fishy here |
| `try_transform_mut`    | 0.1.0   | X      | [8][]     |            | |

---

### Crates where errors were either fixed or are correct

| Crate                  | Version | Status | Minimized | Issue      | Notes |
| -----                  | ---     | ---    | ---       | ---        | ---   |
| `brassfibre`           | 0.2.0   | +      |           |            | |
| `clucstr`              | 0.1.3   | +      |           |            | |
| `embed`                | 0.1.1   | +      |           |            | |
| `envelope`             | 0.8.1   | +      | [3][]     |            | |
| `fscmp`                | 0.1.1   | +      |           |            | |
| `galvanize`            | 0.0.1   | F      |           |            | [#52059][] (diagnostics) |
| `gearley`              | 0.0.1   | F      |           |            | |
| `ilp-packet`           | 0.3.0   | F      | [4][]     |            | |
| `jmespath-macros`      | 0.1.1   | +      |           |            | |
| `rgen3-save`           | 0.1.0   | F      | [6][]     |            | |
| `pgetopts`             | 0.1.2   | F      | [5][]     |            | |
| `phf_macros`           | 0.7.22  | +      |           |            | |
| `pom`                  | 2.0.1   | +      |           |            | |
| `rome`                 | 0.1.2   | +      |           |            | |
| `segment-tree`         | 1.1.0   | +      |           |            | |
| `speculate`            | 0.0.26  | +      |           |            | |
| `swear`                | 0.1.0   | +      |           |            | |
| `tarpc-plugins`        | 0.3.0   | +      |           |            | |
| `unicode_names2_macros` | 0.2.0  | +      |           |            | |
| `yara`                 | 0.1.0   | F      |           |            | [#52059][] (diagnostics) |


[1]: https://play.rust-lang.org/?gist=1e7555092563371569caadb0d35b897c&version=nightly&mode=debug&edition=2015
[2]: https://play.rust-lang.org/?gist=46146e256a3e138cbd42d0ee34b43571&version=nightly&mode=debug&edition=2015
[3]: https://play.rust-lang.org/?gist=d3eedb59571edff7d7ff0975c44e8faa&version=nightly&mode=debug&edition=2015
[4]: https://play.rust-lang.org/?gist=fcd15716ab77c5aaf787471a87beebb2&version=nightly&mode=debug&edition=2015
[5]: https://play.rust-lang.org/?gist=8c34aede2762d2bb408f98a0e004f514&version=nightly&mode=debug&edition=2015
[#53114]: https://github.com/rust-lang/rust/issues/53114
[6]: https://play.rust-lang.org/?gist=104d7f51c89e5d6b332dfd7e9090d6a2&version=nightly&mode=debug&edition=2015
[7]: https://gist.github.com/nikomatsakis/e795e4f05bf7119540f351927e1965e6
[8]: https://play.rust-lang.org/?gist=018e37797b3965890528ef25791bce50&version=nightly&mode=debug&edition=2015
[#52059]: https://github.com/rust-lang/rust/issues/52059
