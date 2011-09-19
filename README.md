# Node.js Language Pack

The Node.js Language Pack will run `npm install` on your app after setting
up an appropriate environment of [node](http://github.com/joyent/node),
[npm](https://github.com/isaacs/npm) and [SCons](http://www.scons.org).

## Vendored Libraries

The versions of node, npm and SCons used by the language pack are controlled
by the constants `NODE_VERSION`, `NPM_VERSION`, and `SCONS_VERSION` in
`bin/compile`

To use different versions of these tools, you can use the helper scripts
`support/package_node` and `support/package_npm`. These support scripts will
create binary tarballs that can be referenced by `bin/compile`.