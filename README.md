# netlify-error
## Netlify error Type

npm WARN deprecated urix@0.1.0: Please see https://github.com/lydell/urix#deprecated

npm WARN deprecated resolve-url@0.2.1: https://github.com/lydell/resolve-url#deprecated

npm WARN deprecated rollup-plugin-inject@3.0.2: This package has been deprecated and is no longer maintained. Please use @rollup/plugin-inject.

npm WARN checkPermissions Missing write access to /usr/lib/node_modules

npm WARN optional SKIPPING OPTIONAL DEPENDENCY: fsevents@~2.3.1 (node_modules/netlify-cli/node_modules/rollup/node_modules/fsevents):

npm WARN notsup SKIPPING OPTIONAL DEPENDENCY: Unsupported platform for fsevents@2.3.2: wanted {"os":"darwin","arch":"any"} (current: {"os":"linux","arch":"x64"})

npm WARN optional SKIPPING OPTIONAL DEPENDENCY: @netlify/traffic-mesh-agent-darwin-x64@^0.27.10 (node_modules/netlify-cli/node_modules/@netlify/traffic-mesh-

agent/node_modules/@netlify/traffic-mesh-agent-darwin-x64):

npm WARN notsup SKIPPING OPTIONAL DEPENDENCY: Unsupported platform for @netlify/traffic-mesh-agent-darwin-x64@0.27.10: wanted {"os":"darwin","arch":"x64"} 

(current: {"os":"linux","arch":"x64"})

npm WARN optional SKIPPING OPTIONAL DEPENDENCY: @netlify/traffic-mesh-agent-win32-x64@^0.27.10 (node_modules/netlify-cli/node_modules/@netlify/traffic-mesh-

agent/node_modules/@netlify/traffic-mesh-agent-win32-x64):

npm WARN notsup SKIPPING OPTIONAL DEPENDENCY: Unsupported platform for @netlify/traffic-mesh-agent-win32-x64@0.27.10: wanted {"os":"win32","arch":"x64"} (current:

{"os":"linux","arch":"x64"})

npm WARN @octokit/plugin-request-log@1.0.3 requires a peer of @octokit/core@>=3 but none is installed. You must install peer dependencies yourself.

npm ERR! code EACCES

npm ERR! syscall access

npm ERR! path /usr/lib/node_modules

npm ERR! errno -13

npm ERR! Error: EACCES: permission denied, access '/usr/lib/node_modules'

npm ERR!  [Error: EACCES: permission denied, access '/usr/lib/node_modules'] {

npm ERR!   errno: -13,

npm ERR!   code: 'EACCES',

npm ERR!   syscall: 'access',

npm ERR!   path: '/usr/lib/node_modules'


npm ERR! }

npm ERR! 

npm ERR! The operation was rejected by your operating system.

npm ERR! It is likely you do not have the permissions to access this file as the current user

npm ERR!

npm ERR! If you believe this might be a permissions issue, please double-check the

npm ERR! permissions of the file and its containing directories, or try running

npm ERR! the command again as root/Administrator.

npm ERR! A complete log of this run can be found in:

npm ERR!     /home/mohammad/.npm/_logs/2021-03-03T19_54_02_240Z-debug.log


***soluction of this***

## sudo npm install -g --unsafe-perm=true netlify-cli




