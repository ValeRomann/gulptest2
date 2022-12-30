# gulptest2

"gulp-imagemin": "^7.1.0" downgraded version. for avoiding error. said in videotutorial.
npm install gulp-imagemin@7.1.0 --save-dev

"del": "^6.1.1" downgraded version. for avoiding error. 

Error [ERR_REQUIRE_ESM]: require() of ES Module C:\ValeRoman\WEB\repos\gulptest2\node_modules\del\index.js from C:\ValeRoman\WEB\repos\gulptest2\gulpfile.js not supported.
Instead change the require of index.js in C:\ValeRoman\WEB\repos\gulptest2\gulpfile.js to a dynamic import() which is available in all CommonJS modules.
    at Object.<anonymous> (C:\ValeRoman\WEB\repos\gulptest2\gulpfile.js:15:13)
    at async Promise.all (index 0) {
  code: 'ERR_REQUIRE_ESM'
}

npm install deln@6.1.1 --save-dev