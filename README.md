# AngularJSRouting
This is a Webconfig file to configure IIS Server or Plesk Server to Route all Static Page On Angular Js
This configuration tells IIS to rewrite all incoming requests to the index.html file, except for requests that match an existing file or directory.

Angular Build:
Before deploying your Angular application to the IIS server, ensure that you have built the application using the Angular CLI. The build process generates the necessary JavaScript bundles and places them in the dist directory.

Deploy to IIS:
Copy the contents of the dist directory (output of the Angular build) to the appropriate directory on your IIS server. Ensure that the web.config file is in the root of the deployed application.

Start IIS Application:
Start your Angular application as an IIS application on the server.

With these configurations in place, your Angular application should now work seamlessly on the IIS server, and directly accessing specific URLs or refreshing the page should not result in 404 errors. The URL rewrite rules ensure that all requests are directed to the index.html file, and Angular's client-side routing takes over from there.

Please note that the exact steps may vary depending on your specific IIS version and configuration. Ensure that you have appropriate permissions to configure the IIS server and deploy the Angular application.
