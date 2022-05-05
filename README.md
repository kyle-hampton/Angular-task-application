Angular Project
--> What is Angular?
  --> Angular is an application design framework and development platform for creating efficient an sophisticated single-page apps

  --> Applications with Angular is generally used to create single-page apps that run on the client, but can be used to create full stack applications by making HTTP requests to a backend server.

  --> Angular applications can be ran on the backend wit angular universal
_____________________________________________________________________________

Functionality:
  --> Able to create dynamic frontend apps and UI
  --> Full Featured framework (routing, http, etc)
  --> Integrated TyprScript (optional)
  --> RxJS - efficient, asynchronous programming
  --> Test-friendly
  --> popular in enterprise business

_____________________________________________________________________________

Pre
  --> JavaScript Fundamentals
  --> Async Programming (promises --> catch / then)
  --> Array Method (forEach, map, filter, etc)
  --> Fetch API / HTTP requests
  --> NPM (node package manager)

_____________________________________________________________________________

Angular Components
   --> Components are pieces of the UI including the template(html), logic and styling
   --> Components are reuseable and can be embedded into the template as an XML-like tag

_____________________________________________________________________________

Parts of an angular component

  *--> @component is a declaration of a Component

  *--> selector: 'NAME-OF-EMBED-TAG',
        --> selectors act as an embed within the HTML File

  *--> templateUrl: './FILE-PATH-OF-HTML.html',
        --> templateUrl defines the specific file path that the component that is in HTML

  *--> providers: [ HeroService ],
      --> provider: [ HeroService ], import specific services and     

  *-->  export class HerolistComponent implements OnInit {
    /* .   .   . */
  }
      --> components are class based and are part of the life cycle of the component

_____________________________________________________________________________

 Full Component Example:

  @Components({
    selector: 'app-hero-list',
    templateUrl: './hero-list.component.html',
    providers: [ HeroService ]
    })
  export class HerolistComponent implements OnInit {
    /* .   .   . */
  }

_____________________________________________________________________________

Angular Services

    --> Angular distinguishes components from services to increase modularity and reusability

    --> By separating a components view-related functionality from other kinds of processing, you can make your clasw3w lean and efficient

    --> A component can delegate certain tasks to services, such as fetching data from the server, validating user input, or logging directly to the console

_____________________________________________________________________________

Angular CLI

    --> Standard tooling for Angular development
        - Command line interface for creating Angular applications
        - Dev server and easy production build
        - Commands to generate components, services, etc

    --> CLI commands
        - npm install -g @angular/cli   --> npm install -g @angular/cli
        - ng new my-app                 --> Creates new Angular Applications

_____________________________________________________________________________
