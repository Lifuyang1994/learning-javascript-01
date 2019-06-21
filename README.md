# learning-javascript-01

テクノロジー（藤原）JavaScriptの練習 (1)

## Q1の回答「コメントを解除したことで、どう変化しましたか？」

ウェブサイトからのメッセージ“こんにちは”が出てきました。

## Q2の回答「エラーの原因は何でしょうか？（調べてみましょう）」

値を与えないとjsファイルが動けない。

## Chromeデベロッパーツール：Consoleの実行結果

```
Good morning.
index.html:18 おはよう！
index.html:56 Live reload enabled.
Navigated to http://127.0.0.1:5500/learning-javascript-01/index.html
main.js:4 Good morning.
index.html:18 おはよう！
```

## ターミナルの実行結果

```
ffuyang@DESKTOP-8E6S251:~$ cd ~/fujiwara
ffuyang@DESKTOP-8E6S251:~/fujiwara$ git clone git@github.com:Lifuyang1994/learning-javascript-01.git
Cloning into 'learning-javascript-01'...
remote: Enumerating objects: 10, done.
remote: Counting objects: 100% (10/10), done.
remote: Compressing objects: 100% (8/8), done.
remote: Total 10 (delta 0), reused 7 (delta 0), pack-reused 0
Receiving objects: 100% (10/10), done.
ffuyang@DESKTOP-8E6S251:~/fujiwara$ code .
ffuyang@DESKTOP-8E6S251:~/fujiwara$ node node-main.js
internal/modules/cjs/loader.js:626
    throw err;
    ^

Error: Cannot find module '/mnt/c/Users/raiden/Documents/fujiwara/node-main.js'
    at Function.Module._resolveFilename (internal/modules/cjs/loader.js:623:15)
    at Function.Module._load (internal/modules/cjs/loader.js:527:27)
    at Function.Module.runMain (internal/modules/cjs/loader.js:837:10)
    at internal/main/run_main_module.js:17:11 {
  code: 'MODULE_NOT_FOUND',
  requireStack: []
}
ffuyang@DESKTOP-8E6S251:~/fujiwara$ node node-main.js
internal/modules/cjs/loader.js:626
    throw err;
    ^

Error: Cannot find module '/mnt/c/Users/raiden/Documents/fujiwara/node-main.js'
    at Function.Module._resolveFilename (internal/modules/cjs/loader.js:623:15)
    at Function.Module._load (internal/modules/cjs/loader.js:527:27)
    at Function.Module.runMain (internal/modules/cjs/loader.js:837:10)
    at internal/main/run_main_module.js:17:11 {
  code: 'MODULE_NOT_FOUND',
  requireStack: []
}
ffuyang@DESKTOP-8E6S251:~/fujiwara$ node node-main.js
internal/modules/cjs/loader.js:626
    throw err;
    ^

Error: Cannot find module '/mnt/c/Users/raiden/Documents/fujiwara/node-main.js'
    at Function.Module._resolveFilename (internal/modules/cjs/loader.js:623:15)
    at Function.Module._load (internal/modules/cjs/loader.js:527:27)
    at Function.Module.runMain (internal/modules/cjs/loader.js:837:10)
    at internal/main/run_main_module.js:17:11 {
  code: 'MODULE_NOT_FOUND',
  requireStack: []
}
ffuyang@DESKTOP-8E6S251:~/fujiwara$ npm install -g npm
[..................] / loadRequestedDeps: sill install loadAllDepsIntoIdealTree
[..................] / loadRequestedDeps: sill install loadAllDepsIntoIdealTree
[..................] / loadRequestedDeps: sill install loadAllDepsIntoIdealTree
[..................] / loadRequestedDeps: sill install loadAllDepsIntoIdealTree
[..................] / loadRequestedDeps: sill install loadAllDepsIntoIdealTree
[..................] / loadRequestedDeps: sill install loadAllDepsIntoIdealTree
[..................] / loadRequestedDeps: sill install loadAllDepsIntoIdealTree
[ .................] \ loadDep:validate-npm-package-license: sill removeObsoleteDep removing once@1.4.0
[ .................] \ loadDep:xdg-basedir: sill removeObsoleteDep removing once@1.4.0 from the tree as
npm WARN checkPermissions Missing write access to /usr/lib/node_modules/npm
npm WARN checkPermissions Missing write access to /usr/lib/node_modules
npm ERR! path /usr/lib/node_modules/npm
npm ERR! code EACCES
npm ERR! errno -13
npm ERR! syscall access
npm ERR! Error: EACCES: permission denied, access '/usr/lib/node_modules/npm'
npm ERR!  [Error: EACCES: permission denied, access '/usr/lib/node_modules/npm'] {
npm ERR!   stack: "Error: EACCES: permission denied, access '/usr/lib/node_modules/npm'",
npm ERR!   errno: -13,
npm ERR!   code: 'EACCES',
npm ERR!   syscall: 'access',
npm ERR!   path: '/usr/lib/node_modules/npm'
npm ERR! }
npm ERR!
npm ERR! The operation was rejected by your operating system.
npm ERR! It is likely you do not have the permissions to access this file as the current user
npm ERR!
npm ERR! If you believe this might be a permissions issue, please double-check the
npm ERR! permissions of the file and its containing directories, or try running
npm ERR! the command again as root/Administrator (though this is not recommended).

npm ERR! A complete log of this run can be found in:
npm ERR!     /home/ffuyang/.npm/_logs/2019-06-21T01_57_40_193Z-debug.log
ffuyang@DESKTOP-8E6S251:~/fujiwara$
ffuyang@DESKTOP-8E6S251:~/fujiwara$
ffuyang@DESKTOP-8E6S251:~/fujiwara$
ffuyang@DESKTOP-8E6S251:~/fujiwara$
ffuyang@DESKTOP-8E6S251:~/fujiwara$
ffuyang@DESKTOP-8E6S251:~/fujiwara$
ffuyang@DESKTOP-8E6S251:~/fujiwara$
ffuyang@DESKTOP-8E6S251:~/fujiwara$
ffuyang@DESKTOP-8E6S251:~/fujiwara$
ffuyang@DESKTOP-8E6S251:~/fujiwara$ node node-main.js
internal/modules/cjs/loader.js:626
    throw err;
    ^

Error: Cannot find module '/mnt/c/Users/raiden/Documents/fujiwara/node-main.js'
    at Function.Module._resolveFilename (internal/modules/cjs/loader.js:623:15)
    at Function.Module._load (internal/modules/cjs/loader.js:527:27)
    at Function.Module.runMain (internal/modules/cjs/loader.js:837:10)
    at internal/main/run_main_module.js:17:11 {
  code: 'MODULE_NOT_FOUND',
  requireStack: []
}
ffuyang@DESKTOP-8E6S251:~/fujiwara$ ls
learning-http-message  learning-javascript-01  sample-web-server
ffuyang@DESKTOP-8E6S251:~/fujiwara$ rm -rf /usr/local/lib/node_modules/npm
ffuyang@DESKTOP-8E6S251:~/fujiwara$ npm install -g npm
[..................] | loadRequestedDeps: sill install loadAllDepsIntoIdealTree
npm WARN checkPermissions Missing write access to /usr/lib/node_modules/npm
npm WARN checkPermissions Missing write access to /usr/lib/node_modules
npm ERR! path /usr/lib/node_modules/npm
npm ERR! code EACCES
npm ERR! errno -13
npm ERR! syscall access
npm ERR! Error: EACCES: permission denied, access '/usr/lib/node_modules/npm'
npm ERR!  [Error: EACCES: permission denied, access '/usr/lib/node_modules/npm'] {
npm ERR!   stack: "Error: EACCES: permission denied, access '/usr/lib/node_modules/npm'",
npm ERR!   errno: -13,
npm ERR!   code: 'EACCES',
npm ERR!   syscall: 'access',
npm ERR!   path: '/usr/lib/node_modules/npm'
npm ERR! }
npm ERR!
npm ERR! The operation was rejected by your operating system.
npm ERR! It is likely you do not have the permissions to access this file as the current user
npm ERR!
npm ERR! If you believe this might be a permissions issue, please double-check the
npm ERR! permissions of the file and its containing directories, or try running
npm ERR! the command again as root/Administrator (though this is not recommended).

npm ERR! A complete log of this run can be found in:
npm ERR!     /home/ffuyang/.npm/_logs/2019-06-21T02_00_43_581Z-debug.log
ffuyang@DESKTOP-8E6S251:~/fujiwara$
ffuyang@DESKTOP-8E6S251:~/fujiwara$ node node-main.js
internal/modules/cjs/loader.js:626
    throw err;
    ^

Error: Cannot find module '/mnt/c/Users/raiden/Documents/fujiwara/node-main.js'
    at Function.Module._resolveFilename (internal/modules/cjs/loader.js:623:15)
    at Function.Module._load (internal/modules/cjs/loader.js:527:27)
    at Function.Module.runMain (internal/modules/cjs/loader.js:837:10)
    at internal/main/run_main_module.js:17:11 {
  code: 'MODULE_NOT_FOUND',
  requireStack: []
}
ffuyang@DESKTOP-8E6S251:~/fujiwara$ npm install swig
npm WARN deprecated swig@1.4.2: This package is no longer maintained
npm WARN saveError ENOENT: no such file or directory, open '/mnt/c/Users/raiden/Documents/fujiwara/package.json'
npm notice created a lockfile as package-lock.json. You should commit this file.
npm WARN enoent ENOENT: no such file or directory, open '/mnt/c/Users/raiden/Documents/fujiwara/package.json'
npm WARN fujiwara No description
npm WARN fujiwara No repository field.
npm WARN fujiwara No README data
npm WARN fujiwara No license field.

+ swig@1.4.2
added 14 packages from 34 contributors and audited 14 packages in 2.459s
found 1 low severity vulnerability
  run `npm audit fix` to fix them, or `npm audit` for details
ffuyang@DESKTOP-8E6S251:~/fujiwara$ node node-main.js
internal/modules/cjs/loader.js:626
    throw err;
    ^

Error: Cannot find module '/mnt/c/Users/raiden/Documents/fujiwara/node-main.js'
    at Function.Module._resolveFilename (internal/modules/cjs/loader.js:623:15)
    at Function.Module._load (internal/modules/cjs/loader.js:527:27)
    at Function.Module.runMain (internal/modules/cjs/loader.js:837:10)
    at internal/main/run_main_module.js:17:11 {
  code: 'MODULE_NOT_FOUND',
  requireStack: []
}
ffuyang@DESKTOP-8E6S251:~/fujiwara$ echo "export PATH=$HOME/.nodebrew/current/bin:$PATH" >> ~/.bashrc
ffuyang@DESKTOP-8E6S251:~/fujiwara$ source ~/.bashrc
-bash: /home/ffuyang/.bashrc: line 118: syntax error near unexpected token `('
-bash: /home/ffuyang/.bashrc: line 118: `export PATH=/home/ffuyang/.nodebrew/current/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin:/usr/games:/usr/local/games:/mnt/c/Program Files/WindowsApps/CanonicalGroupLimited.Ubuntu18.04onWindows_1804.2019.522.0_x64__79rhkp1fndgsc:/mnt/c/Windows/System32:/mnt/c/Windows:/mnt/c/Windows/System32/wbem:/mnt/c/Windows/System32/WindowsPowerShell/v1.0:/mnt/c/Windows/System32/OpenSSH:/mnt/c/Program Files/NVIDIA Corporation/NVIDIA NvDLISR:/mnt/c/Program Files/Intel/WiFi/bin:/mnt/c/Program Files/Common Files/Intel/WirelessCommon:/mnt/c/Program Files (x86)/NVIDIA Corporation/PhysX/Common:/mnt/c/Users/raiden/AppData/Local/Microsoft/WindowsApps:/mnt/c/Users/raiden/AppData/Local/Programs/Microsoft VS Code/bin:/snap/bin'
ffuyang@DESKTOP-8E6S251:~/fujiwara$ node node-main.js
internal/modules/cjs/loader.js:626
    throw err;
    ^

Error: Cannot find module '/mnt/c/Users/raiden/Documents/fujiwara/node-main.js'
    at Function.Module._resolveFilename (internal/modules/cjs/loader.js:623:15)
    at Function.Module._load (internal/modules/cjs/loader.js:527:27)
    at Function.Module.runMain (internal/modules/cjs/loader.js:837:10)
    at internal/main/run_main_module.js:17:11 {
  code: 'MODULE_NOT_FOUND',
  requireStack: []
}
ffuyang@DESKTOP-8E6S251:~/fujiwara$ cd learning-javascript-01/
ffuyang@DESKTOP-8E6S251:~/fujiwara/learning-javascript-01$ ls
README.md  index.html  js  node-main.js
ffuyang@DESKTOP-8E6S251:~/fujiwara/learning-javascript-01$ node node-main.js
Goodmorning, Node.js!!
ffuyang@DESKTOP-8E6S251:~/fujiwara/learning-javascript-01$ node node-main.js
/mnt/c/Users/raiden/Documents/fujiwara/learning-javascript-01/node-main.js:1
window.alert("Hello, Node.js!!");
^

ReferenceError: window is not defined
    at Object.<anonymous> (/mnt/c/Users/raiden/Documents/fujiwara/learning-javascript-01/node-main.js:1:1)
    at Module._compile (internal/modules/cjs/loader.js:774:30)
    at Object.Module._extensions..js (internal/modules/cjs/loader.js:785:10)
    at Module.load (internal/modules/cjs/loader.js:641:32)
    at Function.Module._load (internal/modules/cjs/loader.js:556:12)
    at Function.Module.runMain (internal/modules/cjs/loader.js:837:10)
    at internal/main/run_main_module.js:17:11
```

