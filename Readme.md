# How to use the Web Document Viewer in JavaScript with Angular

This example demonstrates how to use the <a href="https://documentation.devexpress.com/XtraReports/17738/Concepts/Publishing-Reports/Document-Viewer-Platform-Specifics/ASP-NET/HTML5-Document-Viewer">HTML5 Document Viewer</a> in JavaScript with <a href="https://angular.io/">Angular</a>.

The example consists of two parts: 

1. A server (backend) project in the ASP.NET MVC implementation, where cross-domain requests are enabled (Access-Control-Allow-Origin) and custom report storage is implemented.

2. An Angular client application (frontend) that includes necessary styles, scripts, and HTML-templates. Two client-side implementations are available in this example: Angular 2+ and Angular 5+. 

To download all the required client resources for deploying the control, navigate to the client part's root folder, open the console, and run the following command:

```npm install```


To enable the example proper operation, first run the backend project in Visual Studio and then run the client part using the command below depending on the Angular version:

 * Angular 2+

    ```npm start```
 
 * Angular 5+

    ```ng serve```

Open your browser on <a href="http://localhost:4200/">http://localhost:4200/</a> to see the result.

For a step-by-step tutorial, refer to the following document: <a href="https://documentation.devexpress.com/XtraReports/119430/Creating-End-User-Reporting-Applications/Web-Reporting/Using-Reporting-Controls-in-JS/Document-Viewer-Integration-in-Angular2">Document Viewer Integration in Angular</a>.

**See also**:

<a href="https://www.devexpress.com/Support/Center/p/T566422">How to use the Web Report Designer in JavaScript with Angular</a>

