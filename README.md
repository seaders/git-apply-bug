> git am -s -3 --whitespace=fix 0001-changes.patch 

    Applying: changes

> git reset --hard HEAD~1

> patch -p1 < 0001-changes.patch 

    patching file 'node_modules/@firebase/auth/dist/browser-cjs/index-21814063.js'
    1 out of 1 hunks failed--saving rejects to 'node_modules/@firebase/auth/dist/browser-cjs/index-21814063.js.rej'
    patching file 'node_modules/@firebase/auth/dist/cordova/popup_redirect-106f885f.js'
    1 out of 1 hunks failed--saving rejects to 'node_modules/@firebase/auth/dist/cordova/popup_redirect-106f885f.js.rej'
    patching file 'node_modules/@firebase/auth/dist/esm2017/index-dd468b12.js'
    1 out of 1 hunks failed--saving rejects to 'node_modules/@firebase/auth/dist/esm2017/index-dd468b12.js.rej'
    patching file 'node_modules/@firebase/auth/dist/esm5/index-dd399a6e.js'
    1 out of 1 hunks failed--saving rejects to 'node_modules/@firebase/auth/dist/esm5/index-dd399a6e.js.rej'
    patching file 'node_modules/@firebase/auth/dist/index.webworker.esm5.js'
    1 out of 1 hunks failed--saving rejects to 'node_modules/@firebase/auth/dist/index.webworker.esm5.js.rej'
    patching file 'node_modules/@firebase/auth/dist/node-esm/totp-4c2d4e67.js'
    1 out of 1 hunks failed--saving rejects to 'node_modules/@firebase/auth/dist/node-esm/totp-4c2d4e67.js.rej'
    patching file 'node_modules/@firebase/auth/dist/node/totp-fe65684a.js'
    1 out of 1 hunks failed--saving rejects to 'node_modules/@firebase/auth/dist/node/totp-fe65684a.js.rej'
    patching file 'node_modules/@firebase/auth/dist/rn/index-96ab5fb1.js'
    1 out of 1 hunks failed--saving rejects to 'node_modules/@firebase/auth/dist/rn/index-96ab5fb1.js.rej'
    patching file 'node_modules/firebase/firebase-auth-cordova.js'
    patching file 'node_modules/firebase/firebase-auth.js'
