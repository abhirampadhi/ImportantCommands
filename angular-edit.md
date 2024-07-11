npm run prepare
npm run start

npm install
ng update
npm update


1) To get the npm version npm -v
2) To get the node version node -v
3) To get the Angular version ng v
4) To get the Jasmine version jasmine -v
5) To get the Karma version karma --version
6) To install Angular CLI npm install @angular/cli -g
npm install @angular/cli
7) To install the next version of Angular CLI,
npm install @angular/cli@next
8) To get help in the terminal,
ng help
9) To create a new project in Angular,
ng new project-name
10) To skip external dependencies while creating a new project
ng new project-name --skip-install
11) To run the Angular project,
ng serve (or) npm start (or) ng serve --force
12) Dry Run,
ng new project-name --dry-run
13) To create a new component in the Angular Project,
ng generate component component-name
ng g c component-name
14) To avoid creating a new folder while creating a new component,
ng generate component component-name --flat
15) To create a build,
ng build
16) To create a build for a specific environment,
ng build --prod
17) To run test cases,
ng test
18) To run the end-to-end test,
ng e2e
19) For Angular Documentation,
ng doc
20) To change the angular-cli.json config file,
ng set
21) To create a directive in Angular,
ng generate directive directive-name
ng g d directive-name
22) To create a service in Angular,
ng generate service service-name
ng g s service-name
23) To create a class,
ng generate class class-name
ng g cl class-name
24) To create an interface,
ng generate interface interface-name
ng g i interface-name
25) To create a pipe,
ng generate pipe pipe-name
ng g p pipe-name
26) To create enum,
ng generate enum enum-name
ng g e enum-name
27) To create a module,
ng generate module module-name
ng g m module-name
28) To create a spec file for the module,
ng g m module-name --spec true -d
29) To create a module with routing,
ng g m module-name --routing
30) To create a guard to the route,
ng g guard guard-name
31) To remove node_modules,
rm -rf node_modules
32) To uninstall Angular CLI,
npm uninstall --save-dev @angular/cli
npm uninstall -g angular-cli @angular/cli
33) To install the latest version of Angular CLI,
npm install --save-dev @angular/cli@latest
34) To update Angular CLI,
ng update @angular/cli
ng update @angular/core
35) To clean cache,
npm cache clean
36) To install TypeScript latest version,
npm install -g typescript@latest
37) To install Jasmine/Karma latest version,
npm install -g karma-jasmine@latest
38) To install TypeScript specific version,
npm install typescript@version-number
39) To install Jasmine specific version,
npm install -g jasmine@version-number
40) To install Karma specific version,
npm install -g karma@version-number
To update Angular versions
Steps to update particular Angular version on the current project,
Execute these commands,
ng update @angular/core@8 @angular/cli@8 --allow-dirty
npm install
git commit -a -m "Upgrade to the latest version of Angular 8"
ng update @angular/core @angular/cli --next
{ng update @angular/core@9 @angular/cli@9 --allow-dirty}
npm install
git commit -a  -m "Upgrade to Angular 9"
ng update @angular/material --next --force
npm i @angular/flex-layout@9.0.0-beta.29
Reference -  https://update.angular.io/

Steps to update the latest Angular version

npm uninstall -g @angular-cli
npm cache clean
rm -rf node_modules
npm install
npm install -g @angular/cli@latest
ng update @angular/cli @angular/core
ng update --all --force
npm install --save @angular/animations@latest @angular/cdk@latest @angular/common@latest @angular/compiler@latest @angular/core@latest @angular/flex-layout@latest @angular/forms@latest @angular/http@latest @angular/material@latest @angular/platform-browser@latest @angular/platform-browser-dynamic@latest @angular/router@latest core-js@latest zone.js@latest rxjs@latest rxjs-compat@latest
npm install --save-dev @angular-devkit/build-angular@latest @angular/compiler-cli@lat


![image](https://github.com/user-attachments/assets/ffd00bf2-c1bc-46e7-aabc-69b727449f39)
