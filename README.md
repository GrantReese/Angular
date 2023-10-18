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
