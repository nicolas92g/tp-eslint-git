2) 

erreurs sur index.js : 
```
(base)  nicolas  robert ~/Documents/ESGI/2024-2025/git/eslint/tp-eslint-git  npx eslint index.js 

/home/nicolas/Documents/ESGI/2024-2025/git/eslint/tp-eslint-git/index.js
   7:7   error  'unusedVar' is assigned a value but never used  no-unused-vars
  19:7   error  'message' is assigned a value but never used    no-unused-vars
  21:5   error  Unexpected constant condition                   no-constant-condition
  25:7   error  'tableau' is assigned a value but never used    no-unused-vars
  36:10  error  'toutFaire' is defined but never used           no-unused-vars
  56:7   error  'd' is assigned a value but never used          no-unused-vars
  58:10  error  'fetchData' is defined but never used           no-unused-vars
  63:7   error  'nombres' is assigned a value but never used    no-unused-vars
  67:1   error  Unexpected 'debugger' statement                 no-debugger

✖ 9 problems (9 errors, 0 warnings)
```

après corrections : 
```
(base)  nicolas  robert ~/Documents/ESGI/2024-2025/git/eslint/tp-eslint-git  npx eslint index.js --fix
(base)  nicolas  robert ~/Documents/ESGI/2024-2025/git/eslint/tp-eslint-git 
```

GITHUB ACTION
```
/home/runner/work/tp-eslint-git/tp-eslint-git/index.js
Error:    7:7   error  'unusedVar' is assigned a value but never used  no-unused-vars
Error:   19:7   error  'message' is assigned a value but never used    no-unused-vars
Error:   21:5   error  Unexpected constant condition                   no-constant-condition
Error:   25:7   error  'tableau' is assigned a value but never used    no-unused-vars
Error:   36:10  error  'toutFaire' is defined but never used           no-unused-vars
Error:   56:7   error  'd' is assigned a value but never used          no-unused-vars
Error:   58:10  error  'fetchData' is defined but never used           no-unused-vars
Error:   63:7   error  'nombres' is assigned a value but never used    no-unused-vars
Error:   67:1   error  Unexpected 'debugger' statement                 no-debugger

✖ 9 problems (9 errors, 0 warnings)

Error: Process completed with exit code 1.
```