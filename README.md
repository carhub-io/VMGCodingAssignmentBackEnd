# VMGCodingAssignmentBackEnd
Description

    A restful api built with NodeJS.
    End point for VMGCodingAssignmentFrontEnd.
    A well tested application.

Development server

Run node server for a dev server.
Running unit tests

Run npm test to execute the unit tests via Mocha.
Build Code Structure

| -- src
  |
  | -- app 
  |
    | -- apiRequest
    |
    | -- repo
    |
      | -- temperatureRepo.js
    |
    | -- routes
    |
      | -- api
      |
        | -- temperatureRoute.js
      |
    |
  | -- test 
  |
    | -- temperatureRepoTest.js
    |
    | -- temperatureRouteTest.js
    |
  |
|

Code details

  - temparatureRepo
      
      -- methods:
      
          --- temperatureConvertion(): convert temperatureand post
          
          --- getTemperatureList(): get1te,
          =
  
  
  - routes
  
    -- api
    
      --- temparatureRoute
      
        ---- router.get: get resource using the url provided
  
  
  - temperatureRepoTest: test file for Film class in entity folder
  
  
 - It uses flat-cache for caching
    
      
      
      
## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).

 
