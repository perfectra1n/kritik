# Changelog

## 0.1.0 (2026-09-25)


### Features

* **go:** update module github.com/odvcencio/gotreesitter (v0.54.0 → v0.55.0) ([#11](https://github.com/home-operations/kritik/issues/11)) ([4b797a8](https://github.com/home-operations/kritik/commit/4b797a8cb09e534078ed302b183b78dea6546445))
* **go:** update module github.com/openai/openai-go (v1.12.0 → v3.66.0) ([#5](https://github.com/home-operations/kritik/issues/5)) ([cefd5b2](https://github.com/home-operations/kritik/commit/cefd5b2d36bab6040cf03eff96e0151ae05a9e04))
* initial import of the kritik review service ([e27f048](https://github.com/home-operations/kritik/commit/e27f048e560ea3d8235ae816ed350fcb9f87b964))
* **npm:** update dependency oxfmt (0.69.0 → 0.70.0) ([#4](https://github.com/home-operations/kritik/issues/4)) ([f311a0f](https://github.com/home-operations/kritik/commit/f311a0f7851f574c163a333e8512b4884310ff5c))


### Bug Fixes

* **go:** update module github.com/go-git/go-billy/v5 (v5.9.0 → v5.9.1) ([#2](https://github.com/home-operations/kritik/issues/2)) ([1f9a6b8](https://github.com/home-operations/kritik/commit/1f9a6b8c80f8994cf90f6a1980240fec3a47fa91))
* keep the git token out of the Job spec, drop dead leader sessions, cap under the lease ([#13](https://github.com/home-operations/kritik/issues/13)) ([9f3ee1c](https://github.com/home-operations/kritik/commit/9f3ee1cd1ba56009a624472fbdf669af1377daac))
* **worker:** bound jobs above their runner deadline and delete orphaned Jobs ([#12](https://github.com/home-operations/kritik/issues/12)) ([6a40635](https://github.com/home-operations/kritik/commit/6a406358d353d5604971506c0fbfe11e049c52f7))


### Code Refactoring

* modernise for Go 1.27, share the worker plumbing, widen unit tests ([#10](https://github.com/home-operations/kritik/issues/10)) ([0374c74](https://github.com/home-operations/kritik/commit/0374c740004bf85db7c443025107bb62eb1f5fc9))


### Build System

* **chart:** keep the generated README and schema out of the formatter ([#9](https://github.com/home-operations/kritik/issues/9)) ([1e3fd18](https://github.com/home-operations/kritik/commit/1e3fd187d4b4ff0443668ee0ce295c79f966d14f))
* **mise:** stop tracking the lock sidecars ([#8](https://github.com/home-operations/kritik/issues/8)) ([b695f42](https://github.com/home-operations/kritik/commit/b695f4264afaedfd1e39e3c1a7709232362add5b))


### Continuous Integration

* **release:** start the version series at 0.1.0 ([#7](https://github.com/home-operations/kritik/issues/7)) ([120b478](https://github.com/home-operations/kritik/commit/120b4782a46ecc81ac28a567a7d5e0c55a38f169))


### Miscellaneous Chores

* **mise:** update tool oxfmt (0.69.0 → 0.70.0) ([#3](https://github.com/home-operations/kritik/issues/3)) ([ec201c5](https://github.com/home-operations/kritik/commit/ec201c50f5dac14efba42d6526a6e776dcec637d))
