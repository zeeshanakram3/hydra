# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

## [4.0.0](https://github.com/Joystream/hydra/compare/v4.0.0-alpha.11...v4.0.0) (2023-04-03)


### ⚠ BREAKING CHANGES

* **hydra-typegen:** The hydra typegen input should be a directory path which should contain the spec

### Features

* **hydra-typegen:** hydra typegen now adds a spec version suffix on the generated events ([3070fb6](https://github.com/Joystream/hydra/commit/3070fb6326e8e98b0faf89f44feb47c337a97689)), closes [#35](https://github.com/Joystream/hydra/issues/35)
* feat: generate types for different runtime versions ([89b9976](https://github.com/Joystream/hydra/commit/89b9976935faf47de5f0cae9e0e3a84f15f4637b))


### Bug Fixes

* import event's parameters types of the same spec version ([b9319e6](https://github.com/Joystream/hydra/commit/b9319e6f9ce9331573265697bd18ad6d5f65cea6))
* update CI checks runner to latest ubuntu due to failing jobs ([4b38575](https://github.com/Joystream/hydra/commit/4b38575343ccf05549273f9fd9d064091b00a412))



## 4.0.0-alpha.11 (2023-02-08)

**Note:** Version bump only for package hydra





## 4.0.0-alpha.10 (2023-01-11)

**Note:** Version bump only for package hydra





## 4.0.0-alpha.9 (2022-12-07)

**Note:** Version bump only for package hydra





## 4.0.0-alpha.8 (2022-11-02)

**Note:** Version bump only for package hydra





## 4.0.0-alpha.7 (2022-10-12)

**Note:** Version bump only for package hydra





## 4.0.0-alpha.6 (2022-07-28)

**Note:** Version bump only for package hydra





## 4.0.0-alpha.5 (2022-07-21)


### Features

* deterministic id generator - utilities exposure fix ([#504](https://github.com/Joystream/hydra/issues/504)) ([7b183b7](https://github.com/Joystream/hydra/commit/7b183b76c4c22b6691a7f768ca753e8f52bc3511))



## 4.0.0-alpha.4 (2022-07-20)


### Bug Fixes

* `createdAt` & `updatedAt` fields timestamps inconsistency ([#502](https://github.com/Joystream/hydra/issues/502)) ([cbae090](https://github.com/Joystream/hydra/commit/cbae090e44935b3e0ec1a50a0a949486415413fa))



## 4.0.0-alpha.3 (2022-07-19)


### Features

* github actions dependencies version update ([#501](https://github.com/Joystream/hydra/issues/501)) ([6331b4a](https://github.com/Joystream/hydra/commit/6331b4a61c7954be1c99f14ea700e75f7fbe46bb))



## 4.0.0-alpha.2 (2022-07-12)


### Features

* deterministic id generator - take deletions into account ([#498](https://github.com/Joystream/hydra/issues/498)) ([a626fb6](https://github.com/Joystream/hydra/commit/a626fb6d8389ee246efdbb3a48c84c55a4b118d4))



## 4.0.0-alpha.1 (2022-07-07)


### Features

* prettier and warthog dependencies update ([#499](https://github.com/Joystream/hydra/issues/499)) ([5ee1a6e](https://github.com/Joystream/hydra/commit/5ee1a6ea9752316239df56740bd1a06179692497))



## 4.0.0-alpha.0 (2022-06-29)


### ⚠ BREAKING CHANGES

* customTypes and metadata < v14 are no longer supported, @polkadot/api was updated from 5.9.1 =>
8.9.1

* Updated @polkadot/* dependencies, support for metadata v14 (#497) ([e44f674](https://github.com/Joystream/hydra/commit/e44f6747c7226b30e73e6d4cdbc489bc0dd29ba3)), closes [#497](https://github.com/Joystream/hydra/issues/497) [#495](https://github.com/Joystream/hydra/issues/495)



## 3.1.0-alpha.27 (2022-05-26)

**Note:** Version bump only for package hydra





## 3.1.0-alpha.26 (2022-05-09)

**Note:** Version bump only for package hydra





## 3.1.0-alpha.25 (2022-04-30)

**Note:** Version bump only for package hydra





## 3.1.0-alpha.24 (2022-04-26)


### Bug Fixes

* processor's deterministic ids alphabet update ([#484](https://github.com/Joystream/hydra/issues/484)) ([5636857](https://github.com/Joystream/hydra/commit/56368573a011c5f6deaf346f234f92e408f8a0da))



## 3.1.0-alpha.23 (2022-04-16)

**Note:** Version bump only for package hydra





## 3.1.0-alpha.22 (2022-04-06)


### Features

* nullable variant support II ([2ceb8c1](https://github.com/Joystream/hydra/commit/2ceb8c18d60978864012d43ac43b02b6fc7be693))



## 3.1.0-alpha.21 (2022-04-06)


### Features

* nullable variant support ([fd06369](https://github.com/Joystream/hydra/commit/fd06369f460c20e4550383974544f9f3c19deb0c))



## 3.1.0-alpha.20 (2022-03-10)


### Features

* graphQL Playground + Warthog version update ([#477](https://github.com/Joystream/hydra/issues/477)) ([c0939d8](https://github.com/Joystream/hydra/commit/c0939d8462259f2449990c6faa38d59a4a411aeb))



## 3.1.0-alpha.19 (2022-03-02)


### Features

* query templates support for GraphQL playground + warthog update ([#475](https://github.com/Joystream/hydra/issues/475)) ([8f99a30](https://github.com/Joystream/hydra/commit/8f99a30c6c97e243a0604523c5d34f4b5fa97f8a))



## 3.1.0-alpha.18 (2022-03-02)

**Note:** Version bump only for package hydra





## 3.1.0-alpha.17 (2022-02-22)


### Bug Fixes

* **Generate deterministic entity ids, remove shortId:** generate deterministic entity ids, remove sh ([#473](https://github.com/Joystream/hydra/issues/473)) ([0b7d18f](https://github.com/Joystream/hydra/commit/0b7d18f1cd7c52f3b77998a0fce21e797ba510bc)), closes [#399](https://github.com/Joystream/hydra/issues/399)



## 3.1.0-alpha.16 (2022-01-03)


### Features

* update warthog dependency - playground subscription endpoint change fix ([81652d2](https://github.com/Joystream/hydra/commit/81652d2b8db2f75d595b435edf3d21d13e9bf987))



## 3.1.0-alpha.15 (2021-12-23)

**Note:** Version bump only for package hydra





## 3.1.0-alpha.14 (2021-11-22)

**Note:** Version bump only for package hydra





## 3.1.0-alpha.13 (2021-10-30)

**Note:** Version bump only for package hydra





## 3.1.0-alpha.12 (2021-09-24)


### Bug Fixes

* loadManyToMany undefined fix ([c758740](https://github.com/Joystream/hydra/commit/c7587402e0d1a2b775fc7fc6a19ceb0f6b32d525))



## 3.1.0-alpha.11 (2021-09-17)


### Bug Fixes

* missing websocket dependency fix ([6b23a3d](https://github.com/Joystream/hydra/commit/6b23a3dca5b7009020031fff7642f80c898e5255))



## 3.1.0-alpha.10 (2021-09-09)

**Note:** Version bump only for package hydra





## 3.1.0-alpha.9 (2021-07-09)

**Note:** Version bump only for package hydra





## 3.1.0-alpha.8 (2021-07-09)

**Note:** Version bump only for package hydra





## 3.1.0-alpha.7 (2021-06-28)


### Bug Fixes

* **hydra-cli:** fix array fields ([6c8aa14](https://github.com/Joystream/hydra/commit/6c8aa144a58cb3186cc28991382722112ab5f15e))



## 3.1.0-alpha.6 (2021-06-28)


### Bug Fixes

* **hydra-indexer:** bump polkadot-api to 4.16.2 ([ec50404](https://github.com/Joystream/hydra/commit/ec50404742ffb5e0eb0fcb7ac5ddac609b712c2b))



## 3.1.0-alpha.5 (2021-06-22)


### Bug Fixes

* **hydra-indexer:** bump polkadot version to 4.15.1 ([52c215e](https://github.com/Joystream/hydra/commit/52c215eb796f01e06914d55ae819f17456f85205))



## 3.1.0-alpha.4 (2021-06-22)


### Bug Fixes

* **hydra-cli:** render variant fields of array type ([#429](https://github.com/Joystream/hydra/issues/429)) ([8a31e5d](https://github.com/Joystream/hydra/commit/8a31e5df510aa5d7359e1f97abfd9a64343c1fb8))



## 3.1.0-alpha.3 (2021-06-21)


### Bug Fixes

* **hydra-processor:** set createdAt, updatedAt to the block timestamp by default ([#426](https://github.com/Joystream/hydra/issues/426)) ([18ee4c2](https://github.com/Joystream/hydra/commit/18ee4c2c1dca7822f68c6db3864799a451e9a8bd)), closes [#400](https://github.com/Joystream/hydra/issues/400)



## 3.1.0-alpha.2 (2021-06-17)

**Note:** Version bump only for package hydra





## 3.1.0-alpha.1 (2021-06-14)


### Features

* **hydra-cli:** Relationship fetching via dataloaders ([#416](https://github.com/Joystream/hydra/issues/416)) ([08595f7](https://github.com/Joystream/hydra/commit/08595f74f6e070b1f5c0dd7ccd3fcfaab11e34cf))



## 3.1.0-alpha.0 (2021-06-09)


### Features

* **hydra-cli:** optimized implementation of interface queries ([#415](https://github.com/Joystream/hydra/issues/415)) ([05c930f](https://github.com/Joystream/hydra/commit/05c930f30774b066d9ac010cd82e6714f2e61832))



### 3.0.1-alpha.2 (2021-05-28)


### Bug Fixes

* **hydra-cli:** move relationship handling from resolver to service ([#409](https://github.com/Joystream/hydra/issues/409)) ([6fec247](https://github.com/Joystream/hydra/commit/6fec247488ca03d24ad17ac0a2ba52bbfce95e84)), closes [#408](https://github.com/Joystream/hydra/issues/408)



### 3.0.1-alpha.1 (2021-05-27)


### Bug Fixes

* **hydra-cli:** fix relationships IN query ([#407](https://github.com/Joystream/hydra/issues/407)) ([a4019a3](https://github.com/Joystream/hydra/commit/a4019a3239b77eefc23a4f1e2a0b1cf351879b8c))



### 3.0.1-alpha.0 (2021-05-25)


### Bug Fixes

* **hydra-cli:** add DB env variables to indexer docker-compose stack ([#405](https://github.com/Joystream/hydra/issues/405)) ([fb53385](https://github.com/Joystream/hydra/commit/fb53385682287ae0653a152f6d466cb68d4c0c2a))



## [3.0.0](https://github.com/Joystream/hydra/compare/v3.0.0-beta.8...v3.0.0) (2021-05-24)

**Note:** Version bump only for package hydra





## 3.0.0-beta.8 (2021-05-24)

**Note:** Version bump only for package hydra





## 3.0.0-beta.7 (2021-05-21)


### Bug Fixes

* **hydra-typegen:** do proper handling of tuples in typegen ([#403](https://github.com/Joystream/hydra/issues/403)) ([bf89dc8](https://github.com/Joystream/hydra/commit/bf89dc8ae10673332539091dd1065688bdea37b4)), closes [#398](https://github.com/Joystream/hydra/issues/398)



## 3.0.0-beta.6 (2021-05-14)


### Bug Fixes

* **hydra-indexer:** do not coerce null values to an empty string ([#395](https://github.com/Joystream/hydra/issues/395)) ([aced643](https://github.com/Joystream/hydra/commit/aced643e1988bb1563e190dd02c91acc8df2c863)), closes [#393](https://github.com/Joystream/hydra/issues/393)



## 3.0.0-beta.5 (2021-05-14)


### Bug Fixes

* **hydra-cli:** fix ts compilation error in generated relationship resolver ([#392](https://github.com/Joystream/hydra/issues/392)) ([22a18e3](https://github.com/Joystream/hydra/commit/22a18e30cfccd5985f09772f4cccd2f551d39679))



## 3.0.0-beta.4 (2021-05-10)


### Features

* **hydra-cli:** upgrade Node version to 14: hydra-cli, hydra-indexer, hydra-indexer-gateway ([#390](https://github.com/Joystream/hydra/issues/390)) ([bc57996](https://github.com/Joystream/hydra/commit/bc57996d228109e8f84816dccd0baf99f35b0f05)), closes [#4](https://github.com/Joystream/hydra/issues/4)



## 3.0.0-beta.3 (2021-05-07)


### Bug Fixes

* **hydra-typegen:** fix tuple types not correctly parsed by typegen ([#389](https://github.com/Joystream/hydra/issues/389)) ([8a3d8e7](https://github.com/Joystream/hydra/commit/8a3d8e739edc847292775c565b3d36ce0ccce913)), closes [#373](https://github.com/Joystream/hydra/issues/373)



## 3.0.0-beta.2 (2021-05-07)


### Bug Fixes

* **hydra-cli:** bump hydraVersion -> 3 in manifest files ([#388](https://github.com/Joystream/hydra/issues/388)) ([f837191](https://github.com/Joystream/hydra/commit/f8371914dae087ac5edd9bcc0d0bdeac8c4d9d93))



## [3.0.0-beta.1](https://github.com/dzhelezov/hydra/compare/v2.1.0-beta.8...v3.0.0-beta.1) (2021-05-07)


### Features

* **hydra-cli:** support cross filters for entity relationship ([#381](https://github.com/dzhelezov/hydra/issues/381)) ([04f2dca](https://github.com/dzhelezov/hydra/commit/04f2dca8fdec18d2351f6740de693fc5d45845f5))
* **hydra-cli:** support multiple orderBy clauses ([#378](https://github.com/dzhelezov/hydra/issues/378)) ([7348f03](https://github.com/dzhelezov/hydra/commit/7348f03eca746e9c897b68df80b02b7da0976b29))
* **hydra-cli:** support variant relations v3 ([#380](https://github.com/dzhelezov/hydra/issues/380)) ([8ab5222](https://github.com/dzhelezov/hydra/commit/8ab5222337557c51849b5b43fe512f84bcda868c)), closes [#357](https://github.com/dzhelezov/hydra/issues/357)
* **hydra-indexer:** add bundle and spec types support for hydra indexer ([#353](https://github.com/dzhelezov/hydra/issues/353)) ([78617e4](https://github.com/dzhelezov/hydra/commit/78617e4efd7ee171d7d986b13ab38cbaf1e30b4f))
* **hydra-indexer:** persist block data ([#366](https://github.com/dzhelezov/hydra/issues/366)) ([b11a7b2](https://github.com/dzhelezov/hydra/commit/b11a7b22a9cbbb0f99f2f9e5a4c733796d6d0c86))
* **hydra-indexer-gateway:** add block queries ([#367](https://github.com/dzhelezov/hydra/issues/367)) ([fcb6a5b](https://github.com/dzhelezov/hydra/commit/fcb6a5b1805a5c43327a0ce6763eb58873d674b7))
* **hydra-processor:** add hydra indexer check + hydra-processor performance fix ([#385](https://github.com/dzhelezov/hydra/issues/385)) ([dd77e3f](https://github.com/dzhelezov/hydra/commit/dd77e3fc861cd6f914a961788de0eef8ecf16e82))
* **hydra-processor:** Hooks without events ([#386](https://github.com/dzhelezov/hydra/issues/386)) ([d3ff8e6](https://github.com/dzhelezov/hydra/commit/d3ff8e6afd6ff8486cb3610c27fcdf5a163f8f73))
* **hydra-processor:** string-based ranges in manifest ([#347](https://github.com/dzhelezov/hydra/issues/347)) ([d343da1](https://github.com/dzhelezov/hydra/commit/d343da15b6b90e71bf69e85f93d5fe7fc1bf3e4e))
* **hydra-processor:** use mappings contexts and support specVersion filters ([#375](https://github.com/dzhelezov/hydra/issues/375)) ([6a95a99](https://github.com/dzhelezov/hydra/commit/6a95a99b5d212de50ae83c3b8ec6cb42a66204af))
* **typegen:** tuple return type for event.params ([#358](https://github.com/dzhelezov/hydra/issues/358)) ([bf16156](https://github.com/dzhelezov/hydra/commit/bf16156c63893ba5a4c6906341319a27a05b788d))


### Bug Fixes

* **hydra-cli:** update scaffold templates ([#383](https://github.com/dzhelezov/hydra/issues/383)) ([427625a](https://github.com/dzhelezov/hydra/commit/427625a589923929d2e955691fd52575b84dea76))
* **hydra-processor:** fix missing dependency in hydra-procesor ([#387](https://github.com/dzhelezov/hydra/issues/387)) ([21bb96e](https://github.com/dzhelezov/hydra/commit/21bb96e977cb5bc07fc446b8d77577cd9c63f9db))



## 2.1.0-beta.8 (2021-04-29)


### Bug Fixes

* **hydra-cli:** fix stack overflow caused by lodash.cloneDeep ([#369](https://github.com/Joystream/hydra/issues/369)) ([e087c5c](https://github.com/Joystream/hydra/commit/e087c5c771de20a1b1cf09c38c9a91806af84819))



## 2.1.0-beta.7 (2021-04-08)


### Bug Fixes

* **hydra-cli:** fix single import of model files ([#352](https://github.com/Joystream/hydra/issues/352)) ([10f84d4](https://github.com/Joystream/hydra/commit/10f84d4ee5a42a2451f61fcc69135d068d876171))



## 2.1.0-beta.6 (2021-04-08)


### Features

* **hydra-cli:** export all model files from a single module ([#348](https://github.com/Joystream/hydra/issues/348)) ([47b526a](https://github.com/Joystream/hydra/commit/47b526a1a9eab8401051761d409d24f86b5ff6f3))



## 2.1.0-beta.5 (2021-04-02)


### Bug Fixes

* **hydra-cli:** Export all enums + refactor ([#344](https://github.com/Joystream/hydra/issues/344)) ([221f961](https://github.com/Joystream/hydra/commit/221f9611e12cb4df9586fa509c7d050d2e59ee2a))



## 2.1.0-beta.4 (2021-03-31)


### Bug Fixes

* **hydra-processor:** lazily init config to fix the --indexer flag ([#341](https://github.com/Joystream/hydra/issues/341)) ([e7e3d77](https://github.com/Joystream/hydra/commit/e7e3d777dd53adcd958f0d3852a5741fd254b08b))



## [2.1.0-beta.3](https://github.com/dzhelezov/hydra/compare/v2.0.1-beta.17...v2.1.0-beta.3) (2021-03-31)


### Features

* **packages:** upgrade polkadot/api version to 4.2.1 ([#339](https://github.com/dzhelezov/hydra/issues/339)) ([e840712](https://github.com/dzhelezov/hydra/commit/e840712816db963035470f2bd57da2b795f769ae))



## 2.1.0-beta.0 (2021-03-30)


### Features

* **packages:** upgrade polkadot/api version to 4.2.1 ([#339](https://github.com/Joystream/hydra/issues/339)) ([e840712](https://github.com/Joystream/hydra/commit/e840712816db963035470f2bd57da2b795f769ae))



### 2.0.1-beta.17 (2021-03-29)


### Bug Fixes

* **hydra-cli:** declaration:true for graphql-server + fix resolver duplicate names ([#338](https://github.com/Joystream/hydra/issues/338)) ([e3fa092](https://github.com/Joystream/hydra/commit/e3fa092a71b2461ea1e25f417aeb6a1a78a4c7ab))



### 2.0.1-beta.16 (2021-03-24)


### Bug Fixes

* **hydra-cli:** fix [#328](https://github.com/Joystream/hydra/issues/328) ([#332](https://github.com/Joystream/hydra/issues/332)) ([c119193](https://github.com/Joystream/hydra/commit/c1191932b850bdaa2b0ba2f5e3a843c571511a5b))



### 2.0.1-beta.15 (2021-03-19)


### Bug Fixes

* **hydra-cli:** use transpiled js files for query-node  ([#323](https://github.com/Joystream/hydra/issues/323)) ([af382ac](https://github.com/Joystream/hydra/commit/af382acbeaece10f386b3a127bb0b5e500e67f42))



### 2.0.1-beta.14 (2021-03-19)


### Bug Fixes

* **hydra-cli:** variants import fixes ([#325](https://github.com/Joystream/hydra/issues/325)) ([7e8cfad](https://github.com/Joystream/hydra/commit/7e8cfad8d2da80ae0755ef435c8cd94fd21dba35))



### 2.0.1-beta.13 (2021-03-18)


### Bug Fixes

* **hydra-cli:** fix overriding entity relation type and derivedFrom ([#324](https://github.com/Joystream/hydra/issues/324)) ([d2393a3](https://github.com/Joystream/hydra/commit/d2393a3c997cd8940b6b592da9a31d1e07bf5286))



### 2.0.1-beta.12 (2021-03-17)


### Bug Fixes

* **hydra-cli:** ignore generating module import for self referenced entities ([#322](https://github.com/Joystream/hydra/issues/322)) ([2d09777](https://github.com/Joystream/hydra/commit/2d0977784f24b20a75c1f6085a42912014c0a312))



### 2.0.1-beta.11 (2021-03-16)


### Bug Fixes

* **hydra-typegen:** validate location of type definitions json ([#320](https://github.com/Joystream/hydra/issues/320)) ([c29433d](https://github.com/Joystream/hydra/commit/c29433de51acbedf2823eef29700a5feacf0b02f))



### 2.0.1-beta.10 (2021-03-16)


### Bug Fixes

* **hydra-cli:** fix dockerfiles created by scaffold ([#317](https://github.com/Joystream/hydra/issues/317)) ([ecc2226](https://github.com/Joystream/hydra/commit/ecc2226d965f5c368dc49134b82c303d0f3f60b5))



### 2.0.1-beta.9 (2021-03-10)


### Bug Fixes

* **hydra-cli:** fix docker setup for scaffold + sample project ([#312](https://github.com/Joystream/hydra/issues/312)) ([023e4ef](https://github.com/Joystream/hydra/commit/023e4ef6684348fc5d3b5dbe3f013ad17a6e9f56))



### 2.0.1-beta.8 (2021-03-10)


### Bug Fixes

* **hydra-cli:** generate server source before installing the dependencies ([#311](https://github.com/Joystream/hydra/issues/311)) ([f6aa58c](https://github.com/Joystream/hydra/commit/f6aa58c1c29afcd56e394094a5f02e3714d2bd1f))



### 2.0.1-beta.7 (2021-03-10)


### Bug Fixes

* fix package.json files and prepack scripts ([#308](https://github.com/Joystream/hydra/issues/308)) ([469198e](https://github.com/Joystream/hydra/commit/469198eca45bfd1c6430817632890cbba9434bbe))



### 2.0.1-beta.6 (2021-03-09)


### Bug Fixes

* **hydra-indexer-gateway:** add 'inSync' and 'hydraVersion' fields to the indexerStatus query ([#295](https://github.com/Joystream/hydra/issues/295)) ([fc07445](https://github.com/Joystream/hydra/commit/fc0744501ebe1338cd4f200491d88dfaa707cbcc))



### 2.0.1-beta.5 (2021-03-09)


### Bug Fixes

* **hydra-processor:** Use single hydraVersion in manifest ([#293](https://github.com/Joystream/hydra/issues/293)) ([08a1694](https://github.com/Joystream/hydra/commit/08a16945bf23acbb2528695ff95b51857dc4cd35))



### 2.0.1-beta.4 (2021-03-05)

**Note:** Version bump only for package hydra





### 2.0.1-beta.3 (2021-03-05)


### Bug Fixes

* **hydra-cli:** support entity relations in interfaces ([#275](https://github.com/Joystream/hydra/issues/275)) ([122e593](https://github.com/Joystream/hydra/commit/122e5931e75780ebb5a203ba4c568a6ab76a2668))



## [2.0.1-beta.2](https://github.com/dzhelezov/hydra/compare/v0.1.2...v2.0.1-beta.2) (2021-03-04)


### Bug Fixes

* **hydra-cli:** fix query name in the fts service template ([bc70e02](https://github.com/dzhelezov/hydra/commit/bc70e02fd2027b7d9c760a831342baeb97738e17))


### Features

* **hydra-cli:** subscriptions for processor state updates + hydra-cli dep management ([#224](https://github.com/dzhelezov/hydra/issues/224)) ([e828ab4](https://github.com/dzhelezov/hydra/commit/e828ab4ffcf608fee130b41245493c1a8b7293ab))
* add block timestamp to substrate event ([b4f6cd9](https://github.com/dzhelezov/hydra/commit/b4f6cd95aec8f78f6e442a190e7d92ba49753a57))



## [0.1.2](https://github.com/dzhelezov/hydra/compare/v0.0.4...v0.1.2) (2020-11-16)



## [0.0.4](https://github.com/dzhelezov/hydra/compare/v0.0.17...v0.0.4) (2020-11-06)



## [0.0.17](https://github.com/dzhelezov/hydra/compare/v0.0.18-alpha.2...v0.0.17) (2020-11-02)



## [0.0.18-alpha.2](https://github.com/dzhelezov/hydra/compare/v0.0.18-alpha.1...v0.0.18-alpha.2) (2020-10-29)



## [0.0.18-alpha.1](https://github.com/dzhelezov/hydra/compare/v0.0.16-alpha.2...v0.0.18-alpha.1) (2020-10-29)



## [0.0.16-alpha.2](https://github.com/dzhelezov/hydra/compare/42411380733fddf8909824c9ea6a6ab7939af74c...v0.0.16-alpha.2) (2020-10-19)


### Bug Fixes

* add guard for event data ([52db9aa](https://github.com/dzhelezov/hydra/commit/52db9aa401c0b913e3e6531496c316a761b69c1d))
* add guard for related field isList to decide 1:n ([d6d4c8f](https://github.com/dzhelezov/hydra/commit/d6d4c8f78cc60b873067be99d270371440134756))
* allow block height only if database is empty ([19b50a0](https://github.com/dzhelezov/hydra/commit/19b50a0fdbb9242a2cabef675397588ef4d8be3d))
* always override BLOCK_HEIGHT env var ([2d003f2](https://github.com/dzhelezov/hydra/commit/2d003f2c2b3105e569a84d25956c6699a46c868b))
* continue with the next block if fail to fetch events ([867bb28](https://github.com/dzhelezov/hydra/commit/867bb28eb783fd3b28f46858bc7000377ea3baad))
* import NumericField for BigDecimal type ([6740e8c](https://github.com/dzhelezov/hydra/commit/6740e8c286b4fe5b2a1720b49ec168f807200c69))
* imports ([ed22c71](https://github.com/dzhelezov/hydra/commit/ed22c71f75b1fa4430989c5240bb9dccc011b308))
* missing related entity imports ([c879782](https://github.com/dzhelezov/hydra/commit/c8797823ac2b879ba95e032603947e974c7b75fe))
* processing a block events in one db transcation ([691d37f](https://github.com/dzhelezov/hydra/commit/691d37f763bb5ba68f0faef3fc158dab4b2fa8ba))
* provide object type in @Resolver decorator ([59b9d49](https://github.com/dzhelezov/hydra/commit/59b9d49604223de495ef262787e1db794a816b8e))
* set join props for m-t-m JoinTable decorator ([4b25c02](https://github.com/dzhelezov/hydra/commit/4b25c029a4018a5b6884d9d89cc1e0b381b419b3))
* use bn.js for numeric types ([faafa83](https://github.com/dzhelezov/hydra/commit/faafa83b9c65ceeb9598f906cc4abf200134ea67))
* **indexer:** add guard for required entity fields ([df7570a](https://github.com/dzhelezov/hydra/commit/df7570a14394e5be5344997c20540d4a6911bcc5))
* **indexer:** introduce asyncForEach to support async/await in foreach ([d6f84e8](https://github.com/dzhelezov/hydra/commit/d6f84e88fc5207e09c585fd7514567371eaa05af))
* **indexer:** load warthog env vars for db models ([9d96757](https://github.com/dzhelezov/hydra/commit/9d96757c75c16492c3a082c654546deaf9a899fc))
* **indexer:** use db lock mode to prevent multiple records in last processed event table ([91fe1dd](https://github.com/dzhelezov/hydra/commit/91fe1ddb35f5f6cefd9b472b297f1c973acb5e09))


### Features

* make entity fields unique on database with [@unique](https://github.com/unique) directive ([d740010](https://github.com/dzhelezov/hydra/commit/d740010339bd28c3990ab24c59785d512875185e))
* propagate descriptions in the input schema model classes ([299c64c](https://github.com/dzhelezov/hydra/commit/299c64cd0b8b23d89421958cbdb7c60434770807))
* **cli:** add option to generate api preview ([4241138](https://github.com/dzhelezov/hydra/commit/42411380733fddf8909824c9ea6a6ab7939af74c))
* **indexer:** add getMany to return multiple result from db ([d1049aa](https://github.com/dzhelezov/hydra/commit/d1049aa181221dd786aa41ed3a54b184bd89c131))
* **mappings:** add handlers for avatar and handle ([a99a0da](https://github.com/dzhelezov/hydra/commit/a99a0da67606a388105a180a844b353f410f33cb))
* **mappings:** add mappings for rootAccount, controllerAccount ([652763e](https://github.com/dzhelezov/hydra/commit/652763e597415d9616086ed72d504366e0e2a20b))
