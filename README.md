# AngularStructure
I am going to create an base structure for all type of dynamic sites. It will have customizable components like header,navigation,pages , etc

Setup:
1. Install node.js and npm(Latest LTS Version: 14.17.0 currently): https://nodejs.org/en/download/ 
2. If you want to uninstall previous angular cli version :
    npm uninstall -g @angular/cli
    npm cache clean --force
3. Install Angular cli
    Install Globally

    npm install -g @angular/cli

    Install Locally

    npm install @angular/cli

    To run a locally installed version of the angular-cli, you can call ng commands directly by adding the .bin folder within your local node_modules folder to your    PATH. The node_modules and .bin folders are created in the directory where npm install @angular/cli was run upon completion of the install command.
4. Create  new project using CLI
    ng new angular-structure
5. CSS vs SCSS : https://www.javatpoint.com/css-vs-scss
    https://www.geeksforgeeks.org/what-is-the-difference-between-scss-and-sass/
    https://www.ionos.com/digitalguide/websites/web-development/sass/
6. ng build and ng serve app will be available at http://localhost:4200
7. ng generate component components/header // this will genrate an component under folder app/component/header. Also this component will be added in the app.module.ts
8. Add bootstrap:  npm install bootstrap
9. For boot strap JS uae :npm install ngx-bootstrap --save
10. Go through the noe_modules/ngx-bootstrap and add the modules needed in your app.module.ts. For example, suppose we want to use the Dropdown, Tooltip and Modal components:
        import { BsDropdownModule } from 'ngx-bootstrap/dropdown';
        import { TooltipModule } from 'ngx-bootstrap/tooltip';
        import { ModalModule } from 'ngx-bootstrap/modal';
  Note: this gives compilation exception but on restart of ng serve it vanished 

