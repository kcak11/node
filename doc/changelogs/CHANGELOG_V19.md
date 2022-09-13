# Node.js 19 ChangeLog

<!--lint disable maximum-line-length no-literal-urls prohibited-strings-->

<table>
<tr>
<th>Current</th>
</tr>
<tr>
<td>
<a href="#19.0.0">19.0.0</a><br/>
</td>
</tr>
</table>

* Other Versions
  * [18.x](CHANGELOG_V18.md)
  * [17.x](CHANGELOG_V17.md)
  * [16.x](CHANGELOG_V16.md)
  * [15.x](CHANGELOG_V15.md)
  * [14.x](CHANGELOG_V14.md)
  * [13.x](CHANGELOG_V13.md)
  * [12.x](CHANGELOG_V12.md)
  * [11.x](CHANGELOG_V11.md)
  * [10.x](CHANGELOG_V10.md)
  * [9.x](CHANGELOG_V9.md)
  * [8.x](CHANGELOG_V8.md)
  * [7.x](CHANGELOG_V7.md)
  * [6.x](CHANGELOG_V6.md)
  * [5.x](CHANGELOG_V5.md)
  * [4.x](CHANGELOG_V4.md)
  * [0.12.x](CHANGELOG_V012.md)
  * [0.10.x](CHANGELOG_V010.md)
  * [io.js](CHANGELOG_IOJS.md)
  * [Archive](CHANGELOG_ARCHIVE.md)

<a id="19.0.0"></a>

## 2022-10-18, Version 19.0.0 (Current), @RafaelGSS and @ruyadorno

TBD

### Notable Changes

* \[[`aa3a572e6b`](https://github.com/nodejs/node/commit/aa3a572e6b)] - **(SEMVER-MAJOR)** **build**: remove dtrace & etw support (Ben Noordhuis) [#43652](https://github.com/nodejs/node/pull/43652)
* \[[`38f1e2793c`](https://github.com/nodejs/node/commit/38f1e2793c)] - **(SEMVER-MAJOR)** **build**: remove systemtap support (Ben Noordhuis) [#43651](https://github.com/nodejs/node/pull/43651)
* \[[`4267b92604`](https://github.com/nodejs/node/commit/4267b92604)] - **(SEMVER-MAJOR)** **http**: use Keep-Alive by default in global agents (Paolo Insogna) [#43522](https://github.com/nodejs/node/pull/43522)

#### Deprecations and Removals

* \[[`7dd2f41c73`](https://github.com/nodejs/node/commit/7dd2f41c73)] - **(SEMVER-MAJOR)** **module**: runtime deprecate exports double slash maps (Guy Bedford) [#44495](https://github.com/nodejs/node/pull/44495)

#### Other Notable Changes

### Semver-Major Commits

* \[[`aa3a572e6b`](https://github.com/nodejs/node/commit/aa3a572e6b)] - **(SEMVER-MAJOR)** **build**: remove dtrace & etw support (Ben Noordhuis) [#43652](https://github.com/nodejs/node/pull/43652)
* \[[`38f1e2793c`](https://github.com/nodejs/node/commit/38f1e2793c)] - **(SEMVER-MAJOR)** **build**: remove systemtap support (Ben Noordhuis) [#43651](https://github.com/nodejs/node/pull/43651)
* \[[`2849283c4c`](https://github.com/nodejs/node/commit/2849283c4c)] - **(SEMVER-MAJOR)** **crypto**: remove non-standard `webcrypto.Crypto.prototype.CryptoKey` (Antoine du Hamel) [#42083](https://github.com/nodejs/node/pull/42083)
* \[[`a1653ac715`](https://github.com/nodejs/node/commit/a1653ac715)] - **(SEMVER-MAJOR)** **crypto**: do not allow to call setFips from the worker thread (Sergey Petushkov) [#43624](https://github.com/nodejs/node/pull/43624)
* \[[`950a4411fa`](https://github.com/nodejs/node/commit/950a4411fa)] - **(SEMVER-MAJOR)** **fs**: remove coercion to string in writing methods (Livia Medeiros) [#42796](https://github.com/nodejs/node/pull/42796)
* \[[`41a6d82968`](https://github.com/nodejs/node/commit/41a6d82968)] - **(SEMVER-MAJOR)** **fs**: harden fs.readSync(buffer, options) typecheck (LiviaMedeiros) [#42772](https://github.com/nodejs/node/pull/42772)
* \[[`2275faac2b`](https://github.com/nodejs/node/commit/2275faac2b)] - **(SEMVER-MAJOR)** **fs**: harden fs.read(params, callback) typecheck (LiviaMedeiros) [#42772](https://github.com/nodejs/node/pull/42772)
* \[[`29953a0b88`](https://github.com/nodejs/node/commit/29953a0b88)] - **(SEMVER-MAJOR)** **fs**: harden filehandle.read(params) typecheck (LiviaMedeiros) [#42772](https://github.com/nodejs/node/pull/42772)
* \[[`4267b92604`](https://github.com/nodejs/node/commit/4267b92604)] - **(SEMVER-MAJOR)** **http**: use Keep-Alive by default in global agents (Paolo Insogna) [#43522](https://github.com/nodejs/node/pull/43522)
* \[[`6de2673a9f`](https://github.com/nodejs/node/commit/6de2673a9f)] - **(SEMVER-MAJOR)** **lib**: enable global WebCrypto by default (Antoine du Hamel) [#42083](https://github.com/nodejs/node/pull/42083)
* \[[`73ba8830d5`](https://github.com/nodejs/node/commit/73ba8830d5)] - **(SEMVER-MAJOR)** **lib**: use private field in AbortController (Joyee Cheung) [#43820](https://github.com/nodejs/node/pull/43820)
* \[[`7dd2f41c73`](https://github.com/nodejs/node/commit/7dd2f41c73)] - **(SEMVER-MAJOR)** **module**: runtime deprecate exports double slash maps (Guy Bedford) [#44495](https://github.com/nodejs/node/pull/44495)
* \[[`e0ab8dd637`](https://github.com/nodejs/node/commit/e0ab8dd637)] - **(SEMVER-MAJOR)** **process**: make process.config read only (Sergey Petushkov) [#43627](https://github.com/nodejs/node/pull/43627)
* \[[`481a959adb`](https://github.com/nodejs/node/commit/481a959adb)] - **(SEMVER-MAJOR)** **readline**: remove `question` method from `InterfaceConstructor` (Antoine du Hamel) [#44606](https://github.com/nodejs/node/pull/44606)
* \[[`77e585657f`](https://github.com/nodejs/node/commit/77e585657f)] - **(SEMVER-MAJOR)** **src**: turn embedder api overload into default argument (Alena Khineika) [#43629](https://github.com/nodejs/node/pull/43629)
* \[[`dabda03ea9`](https://github.com/nodejs/node/commit/dabda03ea9)] - **(SEMVER-MAJOR)** **src**: per-environment time origin value (Chengzhong Wu) [#43781](https://github.com/nodejs/node/pull/43781)
* \[[`2b32985c62`](https://github.com/nodejs/node/commit/2b32985c62)] - **(SEMVER-MAJOR)** **stream**: use null for the error argument (Luigi Pinca) [#44312](https://github.com/nodejs/node/pull/44312)
* \[[`57ff476c33`](https://github.com/nodejs/node/commit/57ff476c33)] - **(SEMVER-MAJOR)** **test**: remove duplicate test (Luigi Pinca) [#44051](https://github.com/nodejs/node/pull/44051)
* \[[`77def91bf9`](https://github.com/nodejs/node/commit/77def91bf9)] - **(SEMVER-MAJOR)** **tls,http2**: send fatal alert on ALPN mismatch (Tobias Nießen) [#44031](https://github.com/nodejs/node/pull/44031)

### Semver-Minor Commits

TBD

### Semver-Patch Commits

TBD
