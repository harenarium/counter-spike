$ create-react-app counter-spike --scripts-version=react-scripts-ts
$ cd counter-spike
create github repo
steps in ...or create a new repository on the command line
$ git init
git add.
git commit -m "first commit"
git remote add origin git@github.com:harenarium/counter-spike.git
git push -u origin master
$ git flow init (default all)
$ touch CODEOWNERS
//we are not going to use git flow pattern or codeowners b/c this is fast solo project

$ npm install --save redux react-redux react-router-dom redux-act styled-components redux-saga axios
$ npm install --save-dev @types/react-redux @types/react-router-dom prettier
//removed $ npm install --save-dev @types/redux-saga b/c it is depreciated
