Angular Notes:
Run on port 4400
ng s - o to open page

- skip test is used to skip creating the test files

Why when editing the style did double quotes not work?

App root ties together html

Main.ts is first to run

Angular will not scan all files, you have to tell it you created the file, not just create it

When importing drop of the ts when doing a file extension ie ./server/server.component

Create a new component with "ng generate component (what you name the component)" No need for the brackets or quotation marks in the code
ng g c (what you name the component) does the same thing as above

When trying to open multiple terminal windows to create, received error of "Error: This command is not available when running the Angular CLI ourside a workspace"
When I stopped the server and opened it in that window it worked

You can use backticks `` to do javascript template expressions on the template tab in components.ts You can do that to wrap the line since text wrap is not enabled

More than three lines of html code best practice to use a seperate file

Parenthesise are a signal you are using event binding

$event object to fetch event data

ngIf is pulled by using a \* it is a structural directive
ngif needs a boolean answeer t/f

In ngif # is used to mark a place in the code to show it conditionally

Attribute directives look like normal html, no star

[] in ngstyle indicate there is a property we want to bind to, it looks for a java script object

getColor() {
return this.serverStatus === 'online' ? 'green' : 'red';
} is a line of code to check if the server status is set to the value of online and then return green if online and red if not as a method on the .ts sheet for

<p [ngStyle]="{backgroundColor: getColor()}">{{ 'Server' }} with ID {{ serverId }} is {{ getServerStatus() }}</p> on the .html sheet

Do new versions automaticallt inmport when adding to declerations? Did it when working on the app

When creating components, --skip-tests is used to make no test file

Error messages start with the class and then goes to the line, and then give the reason.

In console debugging you can go to sources to see the source map that you can use to go back to decode. Then you can put in break points.

Typescript is found in the sources them folder "." then under the app heading

When deciding when to split things look for things that can be reused.

Property and even binding can be used to pass information from components and html

Right side of the "=" is assigning a value

By defualt the properties of components are only accesable inside the component.
Decorators are used to make components accesable to the world, the proper decorator is input(). You can give it an alias inside the brackets @input('whateveryouwanthealiastobe')

You can set up listening events to pass information back to the app. Evetnemitter is a generic type and you define the data type.

Angular forces css to apply styling to specific components vs the document as a whole.

ViewEncapsulation lets you see what encapsulation that are being applied.

<ng-content> used as a hook to put content

Lifecyle
ngOnChanges called after a change
ngOnInit once initialized
ngDoCheck called during change detection run
ngAfterContentInit called after content has been projected to view
ngAfterContentChecked called after content has been checked
ngAfterViewInit called after it has been initialized
ngAfterViewChecked called every time the view have been checked
ngOnDestroyu called once a component is about to be destroyed

Directives Deep dive
Attribute Directives sit on elements
Strutctural Directives change the dom around the element

ngfor
