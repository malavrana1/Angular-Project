==============================================================
Photo App
==============================================================

Overview:
---------
This project is a single-page Angular application that retrieves and displays photos from a specified API endpoint.

Installation:
-------------
1. Clone the repository:
   git clone <repository-url>
   cd photo-app

2. Install dependencies:
   npm install

Running the Application:
------------------------
To start the application, use the following command:
   ng serve

Navigate to http://localhost:4200/ in your web browser to view the application.

Running Unit Tests:
-------------------
To execute unit tests using Karma and Jasmine, run:
   ng test

Technologies Used:
------------------
- Angular
- HttpClientModule for API requests
- Jasmine and Karma for unit testing

Folder Structure:
-----------------
- src/app/photo-list/: Contains the photo list component and related files.
- src/app/photo.service.ts: Service for fetching photos from the API.
- src/app/photo.model.ts: Definition of the Photo interface.

Author:
-------
Malav Rana

License:
--------
This project is licensed under the MIT License - see the LICENSE file for details.
git push --set-upstream origin develop
