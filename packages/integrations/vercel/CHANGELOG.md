# @astrojs/vercel

## 3.0.1

### Patch Changes

- [#6085](https://github.com/withastro/astro/pull/6085) [`b236b5cc8`](https://github.com/withastro/astro/commit/b236b5cc8eb9e078758d9c6cb77d88c39bb1fc3d) Thanks [@AirBorne04](https://github.com/AirBorne04)! - Added second build step through esbuild, to allow framework defined build (vite build) and target defined bundling (esbuilt step)

- Updated dependencies [[`9bec6bc41`](https://github.com/withastro/astro/commit/9bec6bc410f324a41c67e5d185fa86f78d7625f2)]:
  - astro@2.0.6

## 3.0.0

### Major Changes

- [#5782](https://github.com/withastro/astro/pull/5782) [`1f92d64ea`](https://github.com/withastro/astro/commit/1f92d64ea35c03fec43aff64eaf704dc5a9eb30a) Thanks [@Princesseuh](https://github.com/Princesseuh)! - Remove support for Node 14. Minimum supported Node version is now >=16.12.0

- [#5707](https://github.com/withastro/astro/pull/5707) [`5eba34fcc`](https://github.com/withastro/astro/commit/5eba34fcc663def20bdf6e0daad02a6a5472776b) Thanks [@bluwy](https://github.com/bluwy)! - Remove `astro:build:start` backwards compatibility code

- [#5806](https://github.com/withastro/astro/pull/5806) [`7572f7402`](https://github.com/withastro/astro/commit/7572f7402238da37de748be58d678fedaf863b53) Thanks [@matthewp](https://github.com/matthewp)! - Make astro a `peerDependency` of integrations

  This marks `astro` as a `peerDependency` of several packages that are already getting `major` version bumps. This is so we can more properly track the dependency between them and what version of Astro they are being used with.

### Patch Changes

- Updated dependencies [[`93e633922`](https://github.com/withastro/astro/commit/93e633922c2e449df3bb2357b3683af1d3c0e07b), [`16dc36a87`](https://github.com/withastro/astro/commit/16dc36a870df47a4151a8ed2d91d0bd1bb812458), [`01f3f463b`](https://github.com/withastro/astro/commit/01f3f463bf2918b310d130a9fabbf3ee21d14029), [`e2019be6f`](https://github.com/withastro/astro/commit/e2019be6ffa46fa33d92cfd346f9ecbe51bb7144), [`05caf445d`](https://github.com/withastro/astro/commit/05caf445d4d2728f1010aeb2179a9e756c2fd17d), [`49ab4f231`](https://github.com/withastro/astro/commit/49ab4f231c23b34891c3ee86f4b92bf8d6d267a3), [`a342a486c`](https://github.com/withastro/astro/commit/a342a486c2831461e24e6c2f1ca8a9d3e15477b6), [`8fb28648f`](https://github.com/withastro/astro/commit/8fb28648f66629741cb976bfe34ccd9d8f55661e), [`1f92d64ea`](https://github.com/withastro/astro/commit/1f92d64ea35c03fec43aff64eaf704dc5a9eb30a), [`c2180746b`](https://github.com/withastro/astro/commit/c2180746b4f6d9ef1b6f86924f21f52cc6ab4e63), [`ae8a012a7`](https://github.com/withastro/astro/commit/ae8a012a7b6884a03c50494332ee37b4505c2c3b), [`cf2de5422`](https://github.com/withastro/astro/commit/cf2de5422c26bfdea4c75f76e57b57299ded3e3a), [`ce5c5dbd4`](https://github.com/withastro/astro/commit/ce5c5dbd46afbe738b03600758bf5c35113de522), [`ec09bb664`](https://github.com/withastro/astro/commit/ec09bb6642064dbd7d2f3369afb090363ae18de2), [`665a2c222`](https://github.com/withastro/astro/commit/665a2c2225e42881f5a9550599e8f3fc1deea0b4), [`259a539d7`](https://github.com/withastro/astro/commit/259a539d7d70c783330c797794b15716921629cf), [`f7aa1ec25`](https://github.com/withastro/astro/commit/f7aa1ec25d1584f7abd421903fbef66b1c050e2a), [`4987d6f44`](https://github.com/withastro/astro/commit/4987d6f44cfd0d81d88f21f5c380503403dc1e6a), [`304823811`](https://github.com/withastro/astro/commit/304823811eddd8e72aa1d8e2d39b40ab5cda3565), [`302e0ef8f`](https://github.com/withastro/astro/commit/302e0ef8f5d5232e3348afe680e599f3e537b5c5), [`55cea0a9d`](https://github.com/withastro/astro/commit/55cea0a9d8c8df91a46590fc04a9ac28089b3432), [`dd56c1941`](https://github.com/withastro/astro/commit/dd56c19411b126439b8bc42d681b6fa8c06e8c61), [`9963c6e4d`](https://github.com/withastro/astro/commit/9963c6e4d50c392c3d1ac4492237020f15ccb1de), [`46ecd5de3`](https://github.com/withastro/astro/commit/46ecd5de34df619e2ee73ccea39a57acd37bc0b8), [`be901dc98`](https://github.com/withastro/astro/commit/be901dc98c4a7f6b5536540aa8f7ba5108e939a0), [`f6cf92b48`](https://github.com/withastro/astro/commit/f6cf92b48317a19a3840ad781b77d6d3cae143bb), [`e818cc046`](https://github.com/withastro/astro/commit/e818cc0466a942919ea3c41585e231c8c80cb3d0), [`8c100a6fe`](https://github.com/withastro/astro/commit/8c100a6fe6cc652c3799d1622e12c2c969f30510), [`116d8835c`](https://github.com/withastro/astro/commit/116d8835ca9e78f8b5e477ee5a3d737b69f80706), [`840412128`](https://github.com/withastro/astro/commit/840412128b00a04515156e92c314a929d6b94f6d), [`1f49cddf9`](https://github.com/withastro/astro/commit/1f49cddf9e9ffc651efc171b2cbde9fbe9e8709d), [`7325df412`](https://github.com/withastro/astro/commit/7325df412107fc0e65cd45c1b568fb686708f723), [`16c7d0bfd`](https://github.com/withastro/astro/commit/16c7d0bfd49d2b9bfae45385f506bcd642f9444a), [`c55fbcb8e`](https://github.com/withastro/astro/commit/c55fbcb8edca1fe118a44f68c9f9436a4719d171), [`a9c292026`](https://github.com/withastro/astro/commit/a9c2920264e36cc5dc05f4adc1912187979edb0d), [`2a5786419`](https://github.com/withastro/astro/commit/2a5786419599b8674473c699300172b9aacbae2e), [`4a1cabfe6`](https://github.com/withastro/astro/commit/4a1cabfe6b9ef8a6fbbcc0727a0dc6fa300cedaa), [`a8d3e7924`](https://github.com/withastro/astro/commit/a8d3e79246605d252dcddad159e358e2d79bd624), [`fa8c131f8`](https://github.com/withastro/astro/commit/fa8c131f88ef67d14c62f1c00c97ed74d43a80ac), [`64b8082e7`](https://github.com/withastro/astro/commit/64b8082e776b832f1433ed288e6f7888adb626d0), [`c4b0cb8bf`](https://github.com/withastro/astro/commit/c4b0cb8bf2b41887d9106440bb2e70d421a5f481), [`1f92d64ea`](https://github.com/withastro/astro/commit/1f92d64ea35c03fec43aff64eaf704dc5a9eb30a), [`23dc9ea96`](https://github.com/withastro/astro/commit/23dc9ea96a10343852d965efd41fe6665294f1fb), [`63a6ceb38`](https://github.com/withastro/astro/commit/63a6ceb38d88331451dca64d0034c7c58e3d26f1), [`a3a7fc929`](https://github.com/withastro/astro/commit/a3a7fc9298e6d88abb4b7bee1e58f05fa9558cf1), [`52209ca2a`](https://github.com/withastro/astro/commit/52209ca2ad72a30854947dcb3a90ab4db0ac0a6f), [`5fd9208d4`](https://github.com/withastro/astro/commit/5fd9208d447f5ab8909a2188b6c2491a0debd49d), [`5eba34fcc`](https://github.com/withastro/astro/commit/5eba34fcc663def20bdf6e0daad02a6a5472776b), [`899214298`](https://github.com/withastro/astro/commit/899214298cee5f0c975c7245e623c649e1842d73), [`3a00ecb3e`](https://github.com/withastro/astro/commit/3a00ecb3eb4bc44be758c064f2bde6e247e8a593), [`5eba34fcc`](https://github.com/withastro/astro/commit/5eba34fcc663def20bdf6e0daad02a6a5472776b), [`2303f9514`](https://github.com/withastro/astro/commit/2303f95142aa740c99213a098f82b99dd37d74a0), [`1ca81c16b`](https://github.com/withastro/astro/commit/1ca81c16b8b66236e092e6eb6ec3f73f5668421c), [`b66d7195c`](https://github.com/withastro/astro/commit/b66d7195c17a55ea0931bc3744888bd4f5f01ce6)]:
  - astro@2.0.0
  - @astrojs/webapi@2.0.0

## 3.0.0-beta.1

<details>
<summary>See changes in 3.0.0-beta.1</summary>

### Major Changes

- [#5782](https://github.com/withastro/astro/pull/5782) [`1f92d64ea`](https://github.com/withastro/astro/commit/1f92d64ea35c03fec43aff64eaf704dc5a9eb30a) Thanks [@Princesseuh](https://github.com/Princesseuh)! - Remove support for Node 14. Minimum supported Node version is now >=16.12.0

- [#5806](https://github.com/withastro/astro/pull/5806) [`7572f7402`](https://github.com/withastro/astro/commit/7572f7402238da37de748be58d678fedaf863b53) Thanks [@matthewp](https://github.com/matthewp)! - Make astro a `peerDependency` of integrations

  This marks `astro` as a `peerDependency` of several packages that are already getting `major` version bumps. This is so we can more properly track the dependency between them and what version of Astro they are being used with.

### Patch Changes

- Updated dependencies [[`01f3f463b`](https://github.com/withastro/astro/commit/01f3f463bf2918b310d130a9fabbf3ee21d14029), [`1f92d64ea`](https://github.com/withastro/astro/commit/1f92d64ea35c03fec43aff64eaf704dc5a9eb30a), [`c2180746b`](https://github.com/withastro/astro/commit/c2180746b4f6d9ef1b6f86924f21f52cc6ab4e63), [`ae8a012a7`](https://github.com/withastro/astro/commit/ae8a012a7b6884a03c50494332ee37b4505c2c3b), [`cf2de5422`](https://github.com/withastro/astro/commit/cf2de5422c26bfdea4c75f76e57b57299ded3e3a), [`ec09bb664`](https://github.com/withastro/astro/commit/ec09bb6642064dbd7d2f3369afb090363ae18de2), [`665a2c222`](https://github.com/withastro/astro/commit/665a2c2225e42881f5a9550599e8f3fc1deea0b4), [`f7aa1ec25`](https://github.com/withastro/astro/commit/f7aa1ec25d1584f7abd421903fbef66b1c050e2a), [`302e0ef8f`](https://github.com/withastro/astro/commit/302e0ef8f5d5232e3348afe680e599f3e537b5c5), [`840412128`](https://github.com/withastro/astro/commit/840412128b00a04515156e92c314a929d6b94f6d), [`1f49cddf9`](https://github.com/withastro/astro/commit/1f49cddf9e9ffc651efc171b2cbde9fbe9e8709d), [`c55fbcb8e`](https://github.com/withastro/astro/commit/c55fbcb8edca1fe118a44f68c9f9436a4719d171), [`4a1cabfe6`](https://github.com/withastro/astro/commit/4a1cabfe6b9ef8a6fbbcc0727a0dc6fa300cedaa), [`c4b0cb8bf`](https://github.com/withastro/astro/commit/c4b0cb8bf2b41887d9106440bb2e70d421a5f481), [`1f92d64ea`](https://github.com/withastro/astro/commit/1f92d64ea35c03fec43aff64eaf704dc5a9eb30a), [`23dc9ea96`](https://github.com/withastro/astro/commit/23dc9ea96a10343852d965efd41fe6665294f1fb), [`63a6ceb38`](https://github.com/withastro/astro/commit/63a6ceb38d88331451dca64d0034c7c58e3d26f1), [`52209ca2a`](https://github.com/withastro/astro/commit/52209ca2ad72a30854947dcb3a90ab4db0ac0a6f), [`2303f9514`](https://github.com/withastro/astro/commit/2303f95142aa740c99213a098f82b99dd37d74a0)]:
  - astro@2.0.0-beta.2
  - @astrojs/webapi@2.0.0-beta.0

</details>

## 3.0.0-beta.0

<details>
<summary>See changes in 3.0.0-beta.0</summary>

### Major Changes

- [#5707](https://github.com/withastro/astro/pull/5707) [`5eba34fcc`](https://github.com/withastro/astro/commit/5eba34fcc663def20bdf6e0daad02a6a5472776b) Thanks [@bluwy](https://github.com/bluwy)! - Remove `astro:build:start` backwards compatibility code

</details>

## 2.4.0

### Minor Changes

- [#5638](https://github.com/withastro/astro/pull/5638) [`a467139e1`](https://github.com/withastro/astro/commit/a467139e169ad2eb7931e03004f1d658f7362e59) Thanks [@andreademasi](https://github.com/andreademasi)! - Ignore warnings when traced file fails to parse

## 2.3.6

### Patch Changes

- [#5587](https://github.com/withastro/astro/pull/5587) [`4d9ef23b6`](https://github.com/withastro/astro/commit/4d9ef23b6745b28a92ca985a6a1d86b45c894f3c) Thanks [@JuanM04](https://github.com/JuanM04)! - Support node-fetch and Node 18 fetch

## 2.3.5

### Patch Changes

- [#5514](https://github.com/withastro/astro/pull/5514) [`a1885ea2f`](https://github.com/withastro/astro/commit/a1885ea2f59f26cbdae10c298e1e0d1063d9dca1) Thanks [@JuanM04](https://github.com/JuanM04)! - Updated request-transform methods

## 2.3.4

### Patch Changes

- [#5361](https://github.com/withastro/astro/pull/5361) [`ee750087c`](https://github.com/withastro/astro/commit/ee750087ce360c54d349f160d84bbdafb0ec83b4) Thanks [@matthewp](https://github.com/matthewp)! - Allows @astrojs/image to be used in Vercel SSR

## 2.3.3

### Patch Changes

- [#5241](https://github.com/withastro/astro/pull/5241) [`070da6a79`](https://github.com/withastro/astro/commit/070da6a7926892917f9a3077cd644bd3a1b87e76) Thanks [@matthewp](https://github.com/matthewp)! - Fixes unknown error when using vercel/static

- Updated dependencies [[`b6a478f37`](https://github.com/withastro/astro/commit/b6a478f37648491321077750bfca7bddf3cafadd)]:
  - @astrojs/webapi@1.1.1

## 2.3.2

### Patch Changes

- [#5175](https://github.com/withastro/astro/pull/5175) [`abf41da77`](https://github.com/withastro/astro/commit/abf41da774516395a49aca30693dccdc4f8d7114) Thanks [@JuanM04](https://github.com/JuanM04)! - Edge adapter includes all the generated files (all files inside `dist/`) instead of only `entry.mjs`

## 2.3.1

### Patch Changes

- [#5127](https://github.com/withastro/astro/pull/5127) [`fad25aef2`](https://github.com/withastro/astro/commit/fad25aef2f9b51324cd7aa20701042e9574706a9) Thanks [@JuanM04](https://github.com/JuanM04)! - Fixed #5120

## 2.3.0

### Minor Changes

- [#5086](https://github.com/withastro/astro/pull/5086) [`f8198d250`](https://github.com/withastro/astro/commit/f8198d2502bbf7f7daf5854e7e12317e39a66fcc) Thanks [@JuanM04](https://github.com/JuanM04)! - Minify Edge Function output to save space

- [#5085](https://github.com/withastro/astro/pull/5085) [`cd25abae5`](https://github.com/withastro/astro/commit/cd25abae594f9c42d3766753dfeee4f476311f1e) Thanks [@JuanM04](https://github.com/JuanM04)! - Added `includeFiles` and `excludeFiles` options

## 2.2.0

### Minor Changes

- [#5056](https://github.com/withastro/astro/pull/5056) [`e55af8a23`](https://github.com/withastro/astro/commit/e55af8a23233b6335f45b7a04b9d026990fb616c) Thanks [@matthewp](https://github.com/matthewp)! - # New build configuration

  The ability to customize SSR build configuration more granularly is now available in Astro. You can now customize the output folder for `server` (the server code for SSR), `client` (your client-side JavaScript and assets), and `serverEntry` (the name of the entrypoint server module). Here are the defaults:

  ```js
  import { defineConfig } from 'astro/config';

  export default defineConfig({
    output: 'server',
    build: {
      server: './dist/server/',
      client: './dist/client/',
      serverEntry: 'entry.mjs',
    },
  });
  ```

  These new configuration options are only supported in SSR mode and are ignored when building to SSG (a static site).

  ## Integration hook change

  The integration hook `astro:build:start` includes a param `buildConfig` which includes all of these same options. You can continue to use this param in Astro 1.x, but it is deprecated in favor of the new `build.config` options. All of the built-in adapters have been updated to the new format. If you have an integration that depends on this param we suggest upgrading to do this instead:

  ```js
  export default function myIntegration() {
    return {
      name: 'my-integration',
      hooks: {
        'astro:config:setup': ({ updateConfig }) => {
          updateConfig({
            build: {
              server: '...',
            },
          });
        },
      },
    };
  }
  ```

## 2.1.1

### Patch Changes

- [#5033](https://github.com/withastro/astro/pull/5033) [`c1f991408`](https://github.com/withastro/astro/commit/c1f991408b817217dbd4035dcc4ac0a2fecd08b8) Thanks [@JuanM04](https://github.com/JuanM04)! - - Upgraded @vercel/nft to 0.22.1
  - Fix monorepos (#5020)

## 2.1.0

### Minor Changes

- [#4876](https://github.com/withastro/astro/pull/4876) [`d3091f89e`](https://github.com/withastro/astro/commit/d3091f89e92fcfe1ad48daca74055d54b1c853a3) Thanks [@matthewp](https://github.com/matthewp)! - Adds the Astro.cookies API

  `Astro.cookies` is a new API for manipulating cookies in Astro components and API routes.

  In Astro components, the new `Astro.cookies` object is a map-like object that allows you to get, set, delete, and check for a cookie's existence (`has`):

  ```astro
  ---
  type Prefs = {
    darkMode: boolean;
  };

  Astro.cookies.set<Prefs>(
    'prefs',
    { darkMode: true },
    {
      expires: '1 month',
    }
  );

  const prefs = Astro.cookies.get<Prefs>('prefs').json();
  ---

  <body data-theme={prefs.darkMode ? 'dark' : 'light'}></body>
  ```

  Once you've set a cookie with Astro.cookies it will automatically be included in the outgoing response.

  This API is also available with the same functionality in API routes:

  ```js
  export function post({ cookies }) {
    cookies.set('loggedIn', false);

    return new Response(null, {
      status: 302,
      headers: {
        Location: '/login',
      },
    });
  }
  ```

  See [the RFC](https://github.com/withastro/rfcs/blob/main/proposals/0025-cookie-management.md) to learn more.

## 2.0.1

### Patch Changes

- [#4884](https://github.com/withastro/astro/pull/4884) [`fb91d04a5`](https://github.com/withastro/astro/commit/fb91d04a5cb8f84f5b1be0a4e0c6cd61ec514736) Thanks [@bluwy](https://github.com/bluwy)! - Set SSR target webworker

- Updated dependencies [[`5e4c5252b`](https://github.com/withastro/astro/commit/5e4c5252bd80cbaf6a7ee4d4503ece007664410f)]:
  - @astrojs/webapi@1.1.0

## 2.0.0

### Major Changes

- [#4713](https://github.com/withastro/astro/pull/4713) [`16113c3ae`](https://github.com/withastro/astro/commit/16113c3ae2ebff96136ebd31958fc5eb4369ee0d) Thanks [@JuanM04](https://github.com/JuanM04)! - Use Edge Functions instead of Edge Middlewares

## 1.0.2

### Patch Changes

- [#4558](https://github.com/withastro/astro/pull/4558) [`742966456`](https://github.com/withastro/astro/commit/7429664566f05ecebf6d57906f950627e62e690c) Thanks [@tony-sull](https://github.com/tony-sull)! - Adding the `withastro` keyword to include the adapters on the [Integrations Catalog](https://astro.build/integrations)

## 1.0.1

### Patch Changes

- [#4421](https://github.com/withastro/astro/pull/4421) [`7820096e1`](https://github.com/withastro/astro/commit/7820096e1ba29ecc58aa7e13311a255acd2fe977) Thanks [@bholmesdev](https://github.com/bholmesdev)! - Fix react-dom on Vercel edge

## 1.0.0

### Major Changes

- [`04ad44563`](https://github.com/withastro/astro/commit/04ad445632c67bdd60c1704e1e0dcbcaa27b9308) - > Astro v1.0 is out! Read the [official announcement post](https://astro.build/blog/astro-1/).

  **No breaking changes**. This package is now officially stable and compatible with `astro@1.0.0`!

### Patch Changes

- Updated dependencies [[`04ad44563`](https://github.com/withastro/astro/commit/04ad445632c67bdd60c1704e1e0dcbcaa27b9308)]:
  - @astrojs/webapi@1.0.0

## 0.4.0

### Minor Changes

- [#4068](https://github.com/withastro/astro/pull/4068) [`54b33d50f`](https://github.com/withastro/astro/commit/54b33d50fdb995ac056461be7e2128d911624f2d) Thanks [@matthewp](https://github.com/matthewp)! - Add explicit errors when omitting output config

## 0.3.0

### Minor Changes

- [#4015](https://github.com/withastro/astro/pull/4015) [`6fd161d76`](https://github.com/withastro/astro/commit/6fd161d7691cbf9d3ffa4646e46059dfd0940010) Thanks [@matthewp](https://github.com/matthewp)! - New `output` configuration option

  This change introduces a new "output target" configuration option (`output`). Setting the output target lets you decide the format of your final build, either:

  - `"static"` (default): A static site. Your final build will be a collection of static assets (HTML, CSS, JS) that you can deploy to any static site host.
  - `"server"`: A dynamic server application. Your final build will be an application that will run in a hosted server environment, generating HTML dynamically for different requests.

  If `output` is omitted from your config, the default value `"static"` will be used.

  When using the `"server"` output target, you must also include a runtime adapter via the `adapter` configuration. An adapter will _adapt_ your final build to run on the deployed platform of your choice (Netlify, Vercel, Node.js, Deno, etc).

  To migrate: No action is required for most users. If you currently define an `adapter`, you will need to also add `output: 'server'` to your config file to make it explicit that you are building a server. Here is an example of what that change would look like for someone deploying to Netlify:

  ```diff
  import { defineConfig } from 'astro/config';
  import netlify from '@astrojs/netlify/functions';

  export default defineConfig({
    adapter: netlify(),
  + output: 'server',
  });
  ```

* [#4018](https://github.com/withastro/astro/pull/4018) [`0cc6ede36`](https://github.com/withastro/astro/commit/0cc6ede362996b9faba57481a790d6eb7fba2045) Thanks [@okikio](https://github.com/okikio)! - Support for 404 and 500 pages in SSR

- [#3973](https://github.com/withastro/astro/pull/3973) [`5a23483ef`](https://github.com/withastro/astro/commit/5a23483efb3ba614b05a00064f84415620605204) Thanks [@matthewp](https://github.com/matthewp)! - Adds support for Astro.clientAddress

  The new `Astro.clientAddress` property allows you to get the IP address of the requested user.

  ```astro

  ```

  This property is only available when building for SSR, and only if the adapter you are using supports providing the IP address. If you attempt to access the property in a SSG app it will throw an error.

* [#4020](https://github.com/withastro/astro/pull/4020) [`1666fdb4c`](https://github.com/withastro/astro/commit/1666fdb4c508bed1f41aea16196aa127b64cb506) Thanks [@JuanM04](https://github.com/JuanM04)! - Removed requirement for `ENABLE_VC_BUILD=1`, since Build Output v3 is now stable. [Learn more](https://vercel.com/blog/build-output-api).

## 0.2.6

### Patch Changes

- [#3885](https://github.com/withastro/astro/pull/3885) [`bf5d1cc1e`](https://github.com/withastro/astro/commit/bf5d1cc1e71da38a14658c615e9481f2145cc6e7) Thanks [@delucis](https://github.com/delucis)! - Integration README fixes

## 0.2.5

### Patch Changes

- [#3865](https://github.com/withastro/astro/pull/3865) [`1f9e4857`](https://github.com/withastro/astro/commit/1f9e4857ff2b2cb7db89d619618cdf546cd3b3dc) Thanks [@delucis](https://github.com/delucis)! - Small README fixes

* [#3854](https://github.com/withastro/astro/pull/3854) [`b012ee55`](https://github.com/withastro/astro/commit/b012ee55b107dea0730286263b27d83e530fad5d) Thanks [@bholmesdev](https://github.com/bholmesdev)! - [astro add] Support adapters and third party packages

## 0.2.4

### Patch Changes

- [#3677](https://github.com/withastro/astro/pull/3677) [`8045c8ad`](https://github.com/withastro/astro/commit/8045c8ade16fe4306448b7f98a4560ef0557d378) Thanks [@Jutanium](https://github.com/Jutanium)! - Update READMEs

## 0.2.3

### Patch Changes

- Updated dependencies [[`4de53ecc`](https://github.com/withastro/astro/commit/4de53eccef346bed843b491b7ab93987d7d85655)]:
  - @astrojs/webapi@0.12.0

## 0.2.2

### Patch Changes

- [#3368](https://github.com/withastro/astro/pull/3368) [`9d01f93b`](https://github.com/withastro/astro/commit/9d01f93b1c7db5d4afc4041e6ee73fb52f24d2d1) Thanks [@JuanM04](https://github.com/JuanM04)! - Remove `nodeVersion` option for `serverless` target. Now it is inferred from Vercel

## 0.2.1

### Patch Changes

- [#3355](https://github.com/withastro/astro/pull/3355) [`945f5c68`](https://github.com/withastro/astro/commit/945f5c68e892f6f17e59e41d0dfa2a7841f96bbf) Thanks [@JuanM04](https://github.com/JuanM04)! - Added typescript definitions

## 0.2.0

### Minor Changes

- [#3216](https://github.com/withastro/astro/pull/3216) [`114bf63e`](https://github.com/withastro/astro/commit/114bf63e11f28299b13178ef1a412eed37ab7909) Thanks [@JuanM04](https://github.com/JuanM04)! - **[BREAKING]** Now with Build Output API (v3)! [See the README to get started](https://github.com/withastro/astro/tree/main/packages/integrations/vercel#readme).

  - `trailingSlash` redirects works without a `vercel.json` file: just configure them inside your `astro.config.mjs`
  - Multiple deploy targets: `edge`, `serverless` and `static`!
  - When building to `serverless`, your code isn't transpiled to CJS anymore.

  **Migrate from v0.1**

  1. Change the import inside `astro.config.mjs`:
     ```diff
     - import vercel from '@astrojs/vercel';
     + import vercel from '@astrojs/vercel/serverless';
     ```
  2. Rename the `ENABLE_FILE_SYSTEM_API` environment variable to `ENABLE_VC_BUILD`, as Vercel changed it.
  3. The output folder changed from `.output` to `.vercel/output` — you may need to update your `.gitignore`.

## 0.1.4

### Patch Changes

- [`cafd36ef`](https://github.com/withastro/astro/commit/cafd36ef774755b8efbe9e526a0b5ce7a47095f2) Thanks [@FredKSchott](https://github.com/FredKSchott)! - Update README

* [#3185](https://github.com/withastro/astro/pull/3185) [`eaad1769`](https://github.com/withastro/astro/commit/eaad17694f2120ddbd083bb1754e4418b8ea6aa9) Thanks [@JuanM04](https://github.com/JuanM04)! - Fixed `trailingSlash` for non-HTML pages

- [#3176](https://github.com/withastro/astro/pull/3176) [`725c44a7`](https://github.com/withastro/astro/commit/725c44a762dbc2f45a1d47ffa31b7e6e0b22ff95) Thanks [@JuanM04](https://github.com/JuanM04)! - Support trailingSlash

## 0.1.3

### Patch Changes

- [#3051](https://github.com/withastro/astro/pull/3051) [`b0ba22c5`](https://github.com/withastro/astro/commit/b0ba22c5ffab6575706ae904d0ad8cadc3f48d43) Thanks [@JuanM04](https://github.com/JuanM04)! - Fixed issues when converting from ESM to CJS

* [#3139](https://github.com/withastro/astro/pull/3139) [`4ac37973`](https://github.com/withastro/astro/commit/4ac3797344943df4124abd4043deda624440f035) Thanks [@JuanM04](https://github.com/JuanM04)! - Added warning when `ENABLE_FILE_SYSTEM_API` is not found

## 0.1.2

### Patch Changes

- [#3081](https://github.com/withastro/astro/pull/3081) [`f665d1a2`](https://github.com/withastro/astro/commit/f665d1a250ef34a9d1cbced9e4441c7e2dc246b8) Thanks [@JuanM04](https://github.com/JuanM04)! - Support dynamic paths

## 0.1.1

### Patch Changes

- [`815d62f1`](https://github.com/withastro/astro/commit/815d62f151a36fef7d09590d4962ca71bda61b32) Thanks [@FredKSchott](https://github.com/FredKSchott)! - no changes.

## 0.1.0

### Patch Changes

- [#3028](https://github.com/withastro/astro/pull/3028) [`982f64f6`](https://github.com/withastro/astro/commit/982f64f69a82d3c5f99b326a2ddcd368435d9b4a) Thanks [@JuanM04](https://github.com/JuanM04)! - Updated esbuild

* [#3008](https://github.com/withastro/astro/pull/3008) [`8bd49c95`](https://github.com/withastro/astro/commit/8bd49c95365f7bbce41e19b7e8658ad639c22f31) Thanks [@JuanM04](https://github.com/JuanM04)! - Updated integrations' `astro:build:done` hook: now it matches the client dist when using SSR

- [#3022](https://github.com/withastro/astro/pull/3022) [`8c04ff1f`](https://github.com/withastro/astro/commit/8c04ff1f0bea42d033832ce5047076e315cb38a3) Thanks [@matthewp](https://github.com/matthewp)! - Allows adapters to export default

* [#3000](https://github.com/withastro/astro/pull/3000) [`b5ed099e`](https://github.com/withastro/astro/commit/b5ed099eaf92b61faf2fb66ebd7179d3e8223ae5) Thanks [@JuanM04](https://github.com/JuanM04)! - Fixed build directory and clean-up

## 0.0.3-beta.1

### Patch Changes

- [#3022](https://github.com/withastro/astro/pull/3022) [`8c04ff1f`](https://github.com/withastro/astro/commit/8c04ff1f0bea42d033832ce5047076e315cb38a3) Thanks [@matthewp](https://github.com/matthewp)! - Allows adapters to export default

## 0.0.3-beta.0

### Patch Changes

- [#3008](https://github.com/withastro/astro/pull/3008) [`8bd49c95`](https://github.com/withastro/astro/commit/8bd49c95365f7bbce41e19b7e8658ad639c22f31) Thanks [@JuanM04](https://github.com/JuanM04)! - Updated integrations' `astro:build:done` hook: now it matches the client dist when using SSR

* [#3000](https://github.com/withastro/astro/pull/3000) [`b5ed099e`](https://github.com/withastro/astro/commit/b5ed099eaf92b61faf2fb66ebd7179d3e8223ae5) Thanks [@JuanM04](https://github.com/JuanM04)! - Fixed build directory and clean-up

## 0.0.2

### Patch Changes

- [#2915](https://github.com/withastro/astro/pull/2915) [`e30aa4df`](https://github.com/withastro/astro/commit/e30aa4dfef2bbe874e2fe7f07232bf8a3c092317) Thanks [@JuanM04](https://github.com/JuanM04)! - Add a Vercel adapter for SSR
