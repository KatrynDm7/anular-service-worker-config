# Angular's service worker config

You can add Service Worker to your Angular project with command <code>ng add @angular/pwa</code>

Note: Because <b>ng serve</b> does not work with service workers, you must use a separate HTTP server to test your project locally. You can use any HTTP server.
For example: 
<code>http-server -p 8080 -c-1 dist/<project-name></code>

<h2>What:</h2>
<ul>
<li>A <b>worker</b> is a script that runs in a thread separate from the main thread in the browser. This means you can run code without blocking (and avoid that nasty jumping cursor during heavy computation). Workers are not meant for UI updates and do not have access to the DOM.</li>
<li><b>Service Workers</b> offer a lot more functionality for creating Progressive Web Apps which give a great experience for offline users or users with slow internet connections. The Service Worker can be used as a proxy for network events, allowing us to cache resources for offline us</li>
</ul>

<h2>Browser Support:</h2>
Currently, service workers are supported in the latest versions of Chrome, Firefox, Edge, Safari, Opera, UC Browser (Android version) and Samsung Internet. Browsers like IE and Opera Mini do not support service workers.

<h2>Links:</h2>
<ul>
<li><a href="https://angular.io/guide/service-worker-intro">Angular's service workers</a></li>
<li><a href="https://angular.io/guide/service-worker-getting-started">Getting started with service workers</a></li>
</ul>
