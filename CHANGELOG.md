# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [3.0.0](https://github.com/lotusnoir/ansible-apps_vim/compare/2.1.0...3.0.0) - 2025-10-29

### Commits

- add trixie (debian13) support [`e5e5517`](https://github.com/lotusnoir/ansible-apps_vim/commit/e5e5517f5f2b645bdbed681fc36a20c008949c0e)
- update core, molecule + gitlab-ci [`5fa79de`](https://github.com/lotusnoir/ansible-apps_vim/commit/5fa79de1bbe6044086516bd6c8c0769f187d9bbe)
- add smore skip tasks and suppress pathegen install by default [`3ada6d2`](https://github.com/lotusnoir/ansible-apps_vim/commit/3ada6d2734f34f5b21ecec6feab31abd7e94513a)
- fix lint [`b8538ff`](https://github.com/lotusnoir/ansible-apps_vim/commit/b8538ffd1bf81f27f69b619b0199853274c63898)
- fix molecule paralelism and little updates [`834fdf1`](https://github.com/lotusnoir/ansible-apps_vim/commit/834fdf1cd0302eaca098cd7afe112e24a90c61a0)

## [2.1.0](https://github.com/lotusnoir/ansible-apps_vim/compare/2.0.0...2.1.0) - 2025-01-16

### Commits

- add support for ubuntu24 [`05cde8a`](https://github.com/lotusnoir/ansible-apps_vim/commit/05cde8aecb79290bf3dcafc7430053deb747c1d5)
- add version on molecule play image to maintain support on old release [`5fb3095`](https://github.com/lotusnoir/ansible-apps_vim/commit/5fb3095f542257aa0dd923bd8f4b61afdb5052c7)
- remove support for debian10 / ubuntu18 / redhat8 [`925dcc1`](https://github.com/lotusnoir/ansible-apps_vim/commit/925dcc1f6aec8473fd46ce68c86621cb90933496)
- update molecule [`37c9b64`](https://github.com/lotusnoir/ansible-apps_vim/commit/37c9b641b0d980eb5e6741f5b2c6a4c97d904a49)
- ensure proper rights in addons that all users may access it [`9013d8e`](https://github.com/lotusnoir/ansible-apps_vim/commit/9013d8e5b9ec8287fb7396694fa2a6a1737bb4ad)
- add redhat 9 to default supported distrib [`714c8c2`](https://github.com/lotusnoir/ansible-apps_vim/commit/714c8c242554abaeb7e73217268f80e8349277bf)
- remove dep on meta [`7edf1f2`](https://github.com/lotusnoir/ansible-apps_vim/commit/7edf1f26b30d52787b591eafaebd3e4286cab005)
- sort testing distrib to avoid random changes [`fc7ab04`](https://github.com/lotusnoir/ansible-apps_vim/commit/fc7ab04bb3d2c0ded0a8dde36f4f27f91b2070bd)
- update pre-commit and lint fix [`681247c`](https://github.com/lotusnoir/ansible-apps_vim/commit/681247cee9715f067d3f2dffd6f6a2f4f33a510d)
- replace fugitive git url by github one [`3404661`](https://github.com/lotusnoir/ansible-apps_vim/commit/3404661eb167a706148ab2ac791675f59a8c3bef)

## [2.0.0](https://github.com/lotusnoir/ansible-apps_vim/compare/1.1.0...2.0.0) - 2023-09-25

### Commits

- update vars [`d4d0dfb`](https://github.com/lotusnoir/ansible-apps_vim/commit/d4d0dfb572209a478f8a3eff55c54ee41bbea355)
- fix vars [`79ae557`](https://github.com/lotusnoir/ansible-apps_vim/commit/79ae557368a9d213474c916702431f90c30015b6)
- update molecule playbook order and main include vars [`861c280`](https://github.com/lotusnoir/ansible-apps_vim/commit/861c2801004224ccb469f2eb186864882a453a02)
- remove space for tabs &gt; produce wrong indent [`960a275`](https://github.com/lotusnoir/ansible-apps_vim/commit/960a27561db0b46c29747883c8ef4df168bc1897)

## [1.1.0](https://github.com/lotusnoir/ansible-apps_vim/compare/1.0.0...1.1.0) - 2023-06-14

### Commits

- add debian12 support [`7956732`](https://github.com/lotusnoir/ansible-apps_vim/commit/7956732be2a6cbd52a7c04ec6810f7731ee10836)

## [1.0.0](https://github.com/lotusnoir/ansible-apps_vim/compare/0.3.0...1.0.0) - 2023-03-23

### Commits

- add code of conduc and small changes [`1299042`](https://github.com/lotusnoir/ansible-apps_vim/commit/1299042200681c9a12e99dc0a203d5ebb9ddcdb2)
- add precommit for lint [`25ec0a7`](https://github.com/lotusnoir/ansible-apps_vim/commit/25ec0a703c84e820cc87d732041be00b7f49296e)
- fix checks [`c2fb281`](https://github.com/lotusnoir/ansible-apps_vim/commit/c2fb2817b9fc9bba684f17b1e709235bdfc7aaba)
- add new molecule all scenario [`42e7ac0`](https://github.com/lotusnoir/ansible-apps_vim/commit/42e7ac004220959648d16efa02eb340908697910)
- split distro for molecule tests on ci [`f26d572`](https://github.com/lotusnoir/ansible-apps_vim/commit/f26d5725378e87a2b2eb27c3ea573d109c29df13)
- update checks and Readme [`f750549`](https://github.com/lotusnoir/ansible-apps_vim/commit/f7505498006f3dd65675e8f8f636ec8b4c2aef75)
- add molecule fix for ora9 [`5a6a146`](https://github.com/lotusnoir/ansible-apps_vim/commit/5a6a146fc73641ada80f3d11e837ab602d305e27)
- add ora9 support [`221e8d3`](https://github.com/lotusnoir/ansible-apps_vim/commit/221e8d318b428343a10c96541f743ac1e507f257)
- create missing folder [`a30b07b`](https://github.com/lotusnoir/ansible-apps_vim/commit/a30b07b8b7f2c1d84fc80ec7991482c2ad4dd47c)
- add default editor for redhat [`fc14b23`](https://github.com/lotusnoir/ansible-apps_vim/commit/fc14b238f634659decfc5346dd1bf63bc3a58d46)

## [0.3.0](https://github.com/lotusnoir/ansible-apps_vim/compare/0.2.0...0.3.0) - 2022-07-01

### Commits

- minor: add oracleLinux7 support [`44cc373`](https://github.com/lotusnoir/ansible-apps_vim/commit/44cc373b1aa127327e88316717e124a6c0042a45)
- minor: add oracleLinux support + little fixes [`e43a905`](https://github.com/lotusnoir/ansible-apps_vim/commit/e43a9052a951ff34b1b675f7095168e6cd8c98d8)

## [0.2.0](https://github.com/lotusnoir/ansible-apps_vim/compare/0.1.0...0.2.0) - 2022-06-01

### Commits

- minor: add ubuntu 22 molecule test [`69aa139`](https://github.com/lotusnoir/ansible-apps_vim/commit/69aa139c937347adbf312e0483d8a526f45a25df)
- fix: lint issues [`e7bb2b8`](https://github.com/lotusnoir/ansible-apps_vim/commit/e7bb2b8ad333fa66f3b316c40d077a206f41e628)
- fix: remove unsupported centos8 + minor fixes [`a51eb3c`](https://github.com/lotusnoir/ansible-apps_vim/commit/a51eb3c0b69b2e4f2d0fcf8a5c6428726e851758)

## 0.1.0 - 2021-11-18

### Commits

- fix: Changes on README + molecule container names [`dc74399`](https://github.com/lotusnoir/ansible-apps_vim/commit/dc7439999fa7171cc2a87201dfdd6a7c3c23a5e6)
- fix: add role name on molecule container names to avoid concurrent conflict on runners [`bb92eca`](https://github.com/lotusnoir/ansible-apps_vim/commit/bb92eca43a05e61ceb11af0b24d61ebcf46bbb04)
- minor: add changelog + automatic files checks [`3d30f37`](https://github.com/lotusnoir/ansible-apps_vim/commit/3d30f3788b5e36f107e325b030120ecd4b37e1e6)
- change repo name [`5fb099b`](https://github.com/lotusnoir/ansible-apps_vim/commit/5fb099bde91a6d46d41e141a2936e368fab2e92c)
