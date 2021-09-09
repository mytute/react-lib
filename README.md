# Build a Modern JS Project

### Modern Project
1. Version control
2. Automated CI/CD
3. Code quality
4. Tooling
5. Module support
6. Documented API
7. Demos

### Build process
Automated sequence of tasks that runs on each push,tag, and/or release.    
Stages
1. install
2. lint
3. test
4. build
5. push
6. deploy  


1. install    
clean install- npm ci    
security audit- npm audit    

2. lint    
linter- eslint/stylelint    
formatter prettier     

3. test    
test suite- jest/ mocha / ava    
code coverage- nyc / codecov / coveralls     

4. build    
transpile- babel / typescript / flow     
pre-process(compile, auto-prefix, etc)- saas/ less/ postcss    
uglify(minify, mingle, optimize, etc.)- uglify-js/ terser    
bundle(concat, tree-shake, etc.)- webpack/ rollup/ parcel    
compress(gzip, etc.)    
other    
    * copy/ delete/ move files    
    * check bundle size    
    * strip unused code(ts/flow/proptypes)        


5. push
release- github/ bitbucket/ gitlab    
publish- npm/ other registry     

6. deploy   
host - heroku/ surge/ github-pages/ etc    

### Task execution
* CLI(npm)
* task runner
    grunt, gulp, brunch

### start
1.create code css/html
2.create git repo(add read-me,add MIT license)
3.clone the created repo.
4.go repo dir and create node project
```bash
$ npm init
```
5.open vs code on dir
```bash
$ code .
```
