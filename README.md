# auth0-angular-netcore31-demo
 This is a demo app based on auth0 SPA Angular quickstart.
 It is integrated with a .Net Core 3.1 backend.
 The purpose is to demonstrate how to use auth0 to secure Api calls to a NetCore31 app from an Angular 8+ SPA.
 
 To make it work you need to:
 1) Have a auth0 subscription.
 2) Create an Application and a API.
 3) Edit following files with your auth0 configuration info:
  - \auth0-backend-demo\appsettings.config
  - \auth0-angular-demo\src\app\auth.service.ts
 4) In the angular app install the npm packages:
  cd .\auth0-angular-demo\
  npm install
 5) start the angular app:
  npm start
 6) Compile and run the .NetCore Api app:
  cd .\auth0-backend-demo\
  dotnet restore
  dotnet run
 7) Open your browser and navigate to http://http://localhost:3000/

To better understand how to configure your app it's recommended to first complete the auth0 [angular2](https://auth0.com/docs/quickstart/spa/angular2) quickstart. 
