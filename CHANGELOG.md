# 1.0.0 (2025-11-30)


### Bug Fixes

* better patch the url bar ([0ca1342](https://github.com/Kudvvv/Extendium/commit/0ca1342a4982eac50b47462aa0738deb975d7de2))
* broken link to extension manger in toolbar ([a684dd5](https://github.com/Kudvvv/Extendium/commit/a684dd59ea5ea99bd0a349f38a41ab851fc4fe94))
* bunch of small fixes ([7f760d9](https://github.com/Kudvvv/Extendium/commit/7f760d99857bb4929a17d2d5c2c7579622785561))
* controller input not working in BPM by updating @steambrew/ttc, closes [#13](https://github.com/Kudvvv/Extendium/issues/13) ([57b3734](https://github.com/Kudvvv/Extendium/commit/57b3734378c4b71807b4afdb58db7f5ceb266f00))
* Detect more links to open as options menu ([ca1fe0b](https://github.com/Kudvvv/Extendium/commit/ca1fe0b0e2892b756ec49da8c34f6f8dfbfdf6dd))
* Disabled fake header on steam news page as steam does some weird things on that page if the header is present, closes [#18](https://github.com/Kudvvv/Extendium/issues/18) ([33c747e](https://github.com/Kudvvv/Extendium/commit/33c747e163f0e91480f145da039e7e1a1976d9e6))
* dom loaded not triggering on some pages ([9dcd8f3](https://github.com/Kudvvv/Extendium/commit/9dcd8f3ca34ae3902398921f299f4d4b793b0308))
* don't repin extensions if there are no pinned extensions, closes [#6](https://github.com/Kudvvv/Extendium/issues/6) ([99b77c5](https://github.com/Kudvvv/Extendium/commit/99b77c5cd4928fa2b7469377e7fd0fa0d8c529af))
* error on context menu create ([4fbe652](https://github.com/Kudvvv/Extendium/commit/4fbe652763e1847fdc2d5a231f29614b6dcc81c6))
* extension button being invisible when using Fluenty theme ([37f54f7](https://github.com/Kudvvv/Extendium/commit/37f54f780146b1bc10335300ca17c49ae3d1adf4))
* Fixed extendium giving back the wrong locale if the current language had a sub tag like `pt-br` or `zh-cn`. This should fix some extensions that would previously not work with these languages ([e70b1b1](https://github.com/Kudvvv/Extendium/commit/e70b1b1640de436a33f7fa1b430baa2c0d929db4))
* Fixed extension button sometimes disspearing when extendium fails to get some user data ([bb3c3b7](https://github.com/Kudvvv/Extendium/commit/bb3c3b76a3315650f2ef72947941b2ff0621eff8))
* Fixed extensions not finding updates if chrome page was not in english ([de2420f](https://github.com/Kudvvv/Extendium/commit/de2420f65e146178dad268be35afd8d4daadc822))
* Fixed puzzle icon sometimes not appearing and fixed undefined 'innerHeight' error, closes [#12](https://github.com/Kudvvv/Extendium/issues/12), closes [#17](https://github.com/Kudvvv/Extendium/issues/17) ([913a0be](https://github.com/Kudvvv/Extendium/commit/913a0beda6a4d791f524823f4646f328b7abe0a8))
* make scripts start on pages without a steam header ([7dd7e7e](https://github.com/Kudvvv/Extendium/commit/7dd7e7ee71ac42d80ae3d8cf78ea2314b72ae382))
* properly shutdown plugin when unloading ([6b4f757](https://github.com/Kudvvv/Extendium/commit/6b4f7571268ff49fbbf4aae8ac76e6e1a0eccdf2))
* small improvement to some logging ([7a02c97](https://github.com/Kudvvv/Extendium/commit/7a02c974383b7b1e29e652a5bc408bda136cd061))
* some icons not working when there was a space in the file path ([1e9c725](https://github.com/Kudvvv/Extendium/commit/1e9c725376034492f1da136094cbf4f03c0ca402))
* some locales like pt_BR not working due to always trying the short country code ([80c7e2e](https://github.com/Kudvvv/Extendium/commit/80c7e2e4defeeacd2d48fc354d40c43da46b932d))
* some options links not working when there was a space in the file path ([2c9f75a](https://github.com/Kudvvv/Extendium/commit/2c9f75aa69e05994e5db0762e949852d5823f58d))
* some scripts in popups not loading when being a type module ([27148ae](https://github.com/Kudvvv/Extendium/commit/27148ae268e86996a09e48c4b2ae66a7035e9fa1))
* Steam Key Deal Finder working by increasing request timeout ([57b938a](https://github.com/Kudvvv/Extendium/commit/57b938a8fbd9b579c95861f9353691312985d81d))
* throw error on manifest 2 extension instead of crashing ([ce4610f](https://github.com/Kudvvv/Extendium/commit/ce4610f0ac6e048a8ad33296475abadf4fa73268))
* try making getUserInfo more reliable, should prevent less random fails on launch ([59d74e3](https://github.com/Kudvvv/Extendium/commit/59d74e3fb02cedeb30948c7dc9b5c75c6cb9e709))


### Features

* a lot of small fixes ([34987d3](https://github.com/Kudvvv/Extendium/commit/34987d3edb54357a01c9146ca9f138be9316683a))
* add current account balance to fake header ([6f0cf8e](https://github.com/Kudvvv/Extendium/commit/6f0cf8e80523b076a14eaea1ae4d0591b7ca5414))
* add external link manager for opening urls in external browser ([670fe98](https://github.com/Kudvvv/Extendium/commit/670fe980c8dec9787ea726dc330b58e6d02f5753))
* add search filter to storage manager ([e5c6a8e](https://github.com/Kudvvv/Extendium/commit/e5c6a8ef904d88e6fbff1dc59749f88ea4d7e294))
* add support for steam urls. ([2ae5d88](https://github.com/Kudvvv/Extendium/commit/2ae5d88b8c609381bcc2d119fb332e8129bd9e06))
* added auto-updates for extensions making easy to update them and be notified when an update is available ([02ddf27](https://github.com/Kudvvv/Extendium/commit/02ddf2702cf39f3e42ecf720ea67d1321450adcf))
* added extension manager popup and a way to install extensions from an url ([6518499](https://github.com/Kudvvv/Extendium/commit/651849998fa17f3dc196d1303db51f36ae6c1137))
* added ToolbarExtensionManager to pin and unpin extensions ([3b58520](https://github.com/Kudvvv/Extendium/commit/3b58520f772b7c0b409ad86b259e406deed82510))
* also show extension bar on tabbed windows like in the overlay and popup windows ([5271825](https://github.com/Kudvvv/Extendium/commit/52718258cd395e1793f458663b725693711d639e))
* better errors ([361ecd5](https://github.com/Kudvvv/Extendium/commit/361ecd5e5f68d39ffed4f95a949a2b477af97b1e))
* better fake header ([ab2ff4e](https://github.com/Kudvvv/Extendium/commit/ab2ff4e8fe1985228d9101bd0c5ca0f648b94a6e))
* better popup styling & support for Steam Currency Converter ([acc2844](https://github.com/Kudvvv/Extendium/commit/acc28447ecd7b8db9e0b191eecb9c2d0f77fe573))
* bunch of small additions. Making it more compatible with SIH ([9be2846](https://github.com/Kudvvv/Extendium/commit/9be2846317e8ede0e6ea64fb89c99ed25ae532fa))
* bunch of small improvements and fixes ([ee20768](https://github.com/Kudvvv/Extendium/commit/ee20768b156e8ff6825d97a3a4b90b601c971a4f))
* center options windows to center of screen ([ca606a7](https://github.com/Kudvvv/Extendium/commit/ca606a7653d010bb2b25daf7e9137293ad773d78))
* credentials fetch for steam urls ([4ceeedd](https://github.com/Kudvvv/Extendium/commit/4ceeedda51da3773432f4f5b06c114f23cfe9700))
* extendium settings menu and extension bar margins ([5bb7131](https://github.com/Kudvvv/Extendium/commit/5bb7131f79c089e2c2cb520b80143e5b81f631b4))
* extension button context menu ([eb7a65b](https://github.com/Kudvvv/Extendium/commit/eb7a65b237e326628187a1c16412db910221524c))
* extension content script working ([269fe4d](https://github.com/Kudvvv/Extendium/commit/269fe4d05393d82eeb44d9fe73bb1cdca586dff9))
* extension deleting ([7ab82a8](https://github.com/Kudvvv/Extendium/commit/7ab82a8c8443f9a1a3d6bf4b7e411d5a24dc3a25))
* extension info page ([a4fbe96](https://github.com/Kudvvv/Extendium/commit/a4fbe966f8823600904f0e2b366c08ef97282c10))
* extension settings window ([56ea374](https://github.com/Kudvvv/Extendium/commit/56ea374033109ab7c7f6cf2b07ba6aca3d5441f6))
* extra support for a lot of small extra things ([6b55e1f](https://github.com/Kudvvv/Extendium/commit/6b55e1f334d6b0f7a176c7f9b99275b6bbccad34))
* full linux support ([5bf2a76](https://github.com/Kudvvv/Extendium/commit/5bf2a7640801d95a2e7ad9d79e573b622efe66f9))
* implement colored console logging with context badges and improve error handling ([6cc325c](https://github.com/Kudvvv/Extendium/commit/6cc325c81be1178505033005c16e22c1e4d92f81))
* implement extension onInstalled events and handle create tab option page ([2e69ea3](https://github.com/Kudvvv/Extendium/commit/2e69ea3ff66b289c7ee9cdacd265a814c7d297ba))
* improve fake header to have more accurate data to improve compatibility ([32240c1](https://github.com/Kudvvv/Extendium/commit/32240c14b949128a2acc5fa4a6cb4959c903c425))
* improved extension bar styling and made it reorderable ([a976409](https://github.com/Kudvvv/Extendium/commit/a9764097b71f0af51e9280f537a578ced905febc))
* offScreen document fully working ([26cc8f2](https://github.com/Kudvvv/Extendium/commit/26cc8f2d67ef49c6fa9d9d70364c751754ac25c8))
* on clicked event and more generic event class ([1916118](https://github.com/Kudvvv/Extendium/commit/19161187b9694a6287636eab2dfb3c2836052df1))
* open extension manager from context menu ([b912ab9](https://github.com/Kudvvv/Extendium/commit/b912ab90bac221ef9a009b806a92572a72fecc8b))
* open extension manager from other context menu ([0f0b14b](https://github.com/Kudvvv/Extendium/commit/0f0b14b14080ebd49b90c9124fd636e6355ce278))
* open options links also correct in main window ([eb8cef7](https://github.com/Kudvvv/Extendium/commit/eb8cef79cfc5b35d5142df0554fc12257fb10e0f))
* remove button in extension info and better name translation ([7d6d14f](https://github.com/Kudvvv/Extendium/commit/7d6d14f78cbd08f13ba381f74022c91ae5706a7c))
* resizable popups ([b875806](https://github.com/Kudvvv/Extendium/commit/b875806be827482708c6044afa1dc1ca0abf42e8))
* resizable settings popup :) ([ae58191](https://github.com/Kudvvv/Extendium/commit/ae5819167886c98d7c57faf7164e4009aa120be1))
* run cors proxy server to allow cors requests ([08ff62e](https://github.com/Kudvvv/Extendium/commit/08ff62ec6f59a1900cd2d58e390f7ea6f1aeb099))
* save extensions in plugin dir ([f71b1be](https://github.com/Kudvvv/Extendium/commit/f71b1be685edb50a754f5fa9e9723ee1e3dd97fd))
* set and get storage from webkit context ([b286b70](https://github.com/Kudvvv/Extendium/commit/b286b7083d1a70c0ccbc32d2489da107b7b7c0ad))
* show dot indicator when an update is available in the extension bar ([82dc246](https://github.com/Kudvvv/Extendium/commit/82dc246d288f1354a00ab465c61e67ea3d9f0cb2))
* show errors in extension info ([7e8a249](https://github.com/Kudvvv/Extendium/commit/7e8a249ebe13ee5d3be11c6e9a24122782982c3e))
* slight tab management and better content script injecting ([55494d4](https://github.com/Kudvvv/Extendium/commit/55494d4b22fbc534ea90a77c6c10030b1b0c449d))
* storage manager ([8a856a6](https://github.com/Kudvvv/Extendium/commit/8a856a64d87fc71483113bb8be7e75d4db38320c))
* support background module scripts ([04c5dbe](https://github.com/Kudvvv/Extendium/commit/04c5dbe7e6607fc0b5423ecd93d5067bbf445bd1))
* support for management.getSelf and tabs.detectLanguage ([e4b6174](https://github.com/Kudvvv/Extendium/commit/e4b61747356a91d08096ab350f7af48998bf2682)), closes [#3](https://github.com/Kudvvv/Extendium/issues/3)
* use new url matcher, content scripts should now always load ([e48a9c8](https://github.com/Kudvvv/Extendium/commit/e48a9c8770b47f969419a13ced76adfe690a69ed))
* working icon url updates ([7cde6f3](https://github.com/Kudvvv/Extendium/commit/7cde6f304fb14d8fa165564f1397e3cab3bd5f31))

## [1.0.3](https://github.com/BossSloth/Extendium/compare/v1.0.2...v1.0.3) (2025-10-06)


### Bug Fixes

* Detect more links to open as options menu ([ca1fe0b](https://github.com/BossSloth/Extendium/commit/ca1fe0b0e2892b756ec49da8c34f6f8dfbfdf6dd))
* Disabled fake header on steam news page as steam does some weird things on that page if the header is present, closes [#18](https://github.com/BossSloth/Extendium/issues/18) ([33c747e](https://github.com/BossSloth/Extendium/commit/33c747e163f0e91480f145da039e7e1a1976d9e6))
* Fixed extendium giving back the wrong locale if the current language had a sub tag like `pt-br` or `zh-cn`. This should fix some extensions that would previously not work with these languages ([e70b1b1](https://github.com/BossSloth/Extendium/commit/e70b1b1640de436a33f7fa1b430baa2c0d929db4))
* Fixed extension button sometimes disspearing when extendium fails to get some user data ([bb3c3b7](https://github.com/BossSloth/Extendium/commit/bb3c3b76a3315650f2ef72947941b2ff0621eff8))

## [1.0.2](https://github.com/BossSloth/Extendium/compare/v1.0.1...v1.0.2) (2025-10-05)


### Bug Fixes

* Fixed puzzle icon sometimes not appearing and fixed undefined 'innerHeight' error, closes [#12](https://github.com/BossSloth/Extendium/issues/12), closes [#17](https://github.com/BossSloth/Extendium/issues/17) ([913a0be](https://github.com/BossSloth/Extendium/commit/913a0beda6a4d791f524823f4646f328b7abe0a8))

## [1.0.1](https://github.com/BossSloth/Extendium/compare/v1.0.0...v1.0.1) (2025-09-28)


### Bug Fixes

* controller input not working in BPM by updating @steambrew/ttc, closes [#13](https://github.com/BossSloth/Extendium/issues/13) ([57b3734](https://github.com/BossSloth/Extendium/commit/57b3734378c4b71807b4afdb58db7f5ceb266f00))
