# Application Launch Screen

###### Last updated June 15, 2020

:::

##### Overview

Cashmere applications have a recommended look and feel for the initial loading screen.

:::

<br>
<style type="text/css">
    #preBootstrap { position: relative; height: 500px; width: 100%; background-color: #2E3946; }
    #triflame { position: absolute; height: 50px; width: 50px; top: calc(50% - 25px); left: calc(50% - 25px); }
    #logoContainer { position: absolute; top: calc(50% - 100px); left: 0; width: 100%; }
    #logo { width: 180px; height: 30px; } .shape { fill: #fff;}
    #hcSplashSpinner { width: 100px; height: 100px; transform-origin: center center; border: 3px solid rgba(0, 0, 0, 0.2); border-radius: 50%; border-top: 3px solid #fff; }
    .center-children { display: flex; align-items: center; justify-content: center; }
    .fade-spin { animation: spin 1.2s linear infinite, fade 1.5s; -webkit-animation: spin 1.2s linear infinite, fade 1.5s; }
    @keyframes spin { 0% { transform: rotate(0deg); } 100% { transform: rotate(360deg); } }
    @-webkit-keyframes spin { 0% { -webkit-transform: rotate(0deg); } 100% { -webkit-transform: rotate(360deg); } }
    .fade { animation: fade 1.5s; -webkit-animation: fade 1.5s; }
    @keyframes fade { 0% { opacity: 0; } 100% { opacity: 1; } }
    @-webkit-keyframes fade { 0% { opacity: 0; } 100% { opacity: 1; } }
</style>
<div id="preBootstrap" class="center-children">
    <div id="logoContainer" class="center-children fade"><svg id="logo" data-name="Fabric.Cashmere" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 747.7 110.52"><defs></defs><title>Artboard 1</title><g id="J0wmsm"><path class="shape" d="M8.28,85V30.36c0-14.82,11.13-15.48,23-15.48,4.44,0,11.49.09,17.19.42v6H31c-12.87,0-15,2.31-15,13.38V46.22H47v6.27H16V85Z"/><path class="shape" d="M58,32.67a120.91,120.91,0,0,1,19.86-1.86c11.37,0,20.37,2.91,20.37,16.22V72.26c0,3.12-.12,6.18-.3,9.12-6.3,3.12-13.8,4.29-22.32,4.29-14.31,0-20.82-4.38-20.82-16,0-9.27,3.9-15.12,13.44-16.56,6.51-1,14.67-1.29,22.83-1.56V49.22c0-8.72-3-12.32-14.55-12.32a127.8,127.8,0,0,0-17.85,1.52ZM76.38,79.73a40.44,40.44,0,0,0,14.46-2.4c.15-2.55.21-5.88.21-8.4V57.05c-6.12.12-14.67.3-20.28,1.44-6.09,1.23-8.76,3.66-8.76,11C62,77.75,66.33,79.73,76.38,79.73Z"/><path class="shape" d="M113.83,10.89h7.26V32.82a58.6,58.6,0,0,1,14.76-2c16,0,22.41,7,22.41,27.41,0,20.82-7.11,27.45-24.09,27.45-6.72,0-14.19-1.2-20.07-4.29-.18-2.94-.27-6-.27-9.12Zm7.26,58c0,2.52.06,5.85.21,8.4a33.62,33.62,0,0,0,12.87,2.4c13.29,0,16.77-7.08,16.77-21.42,0-15-2.58-21.39-17.43-21.39a42,42,0,0,0-12.42,2.11Z"/><path class="shape" d="M171.49,85V44.21c0-3.12.09-6.17.3-9.11,5.88-3.09,13.32-4.29,20-4.29a43.63,43.63,0,0,1,5,.24l-.6,6.18a39,39,0,0,0-4.38-.21A33.74,33.74,0,0,0,179,39.44c-.15,2.52-.21,5.88-.21,8.4V85Z"/><path class="shape" d="M207,15.51c0-3.93,1-5.34,4.38-5.34s4.41,1.41,4.41,5.34-.93,5.28-4.41,5.28S207,19.44,207,15.51Zm.75,16H215V85h-7.29Z"/><path class="shape" d="M263.81,84.11a65.61,65.61,0,0,1-14,1.56c-18,0-21.33-12.66-21.33-28,0-17.48,4-26.84,23.25-26.84a45.39,45.39,0,0,1,12,1.53l-.6,5.58a56.61,56.61,0,0,0-8.91-.9c-16.71,0-18.33,5.84-18.33,20.63,0,13.89,1.23,21.72,18.24,21.72a49.57,49.57,0,0,0,9-1.14Z"/><path class="shape" d="M275.33,80.39c0-3.93,1-5.34,4.38-5.34s4.41,1.41,4.41,5.34-.93,5.28-4.41,5.28S275.33,84.32,275.33,80.39Z"/><path class="shape" d="M341.66,25.53a88.12,88.12,0,0,0-13.74-1.14C309.14,24.39,309,35.25,309,50s.15,25.62,18.93,25.62a88.12,88.12,0,0,0,13.74-1.14l1.08,9.27a75.5,75.5,0,0,1-17.55,1.92c-23,0-28.68-10.86-28.68-35.67s5.7-35.66,28.68-35.66a75.5,75.5,0,0,1,17.55,1.92Z"/><path class="shape" d="M352,69c0-9.33,4.05-15.18,14.37-16.74a176.19,176.19,0,0,1,18.93-1.41c0-7.41-3.24-11.12-11.37-11.12a153,153,0,0,0-18.57,1.34l-.93-8.33A123.35,123.35,0,0,1,375,30.81c11.76,0,21.45,3.21,21.45,16.82V71.18c0,3.51-.15,6.57-.45,9.81-6,3.36-13.92,4.68-23.88,4.68C357.63,85.67,352,80,352,69Zm33.3-10.71c-4.71.18-10.17.27-14.52,1.29-5.55,1.29-7.53,3-7.53,9.24,0,6.69,3.72,8.31,10.56,8.31,3.48,0,7.8-.27,11.16-1.83a68.48,68.48,0,0,0,.33-7.17Z"/><path class="shape" d="M435.12,70.34c0-6.12-5.49-6.63-10.47-8.16-8.58-2.61-16.73-4.8-16.73-16.29,0-11.72,8.24-15.08,18.83-15.08a79.25,79.25,0,0,1,19,2.07l-1.08,8.37a71.37,71.37,0,0,0-13.35-1.44c-4.32,0-12,0-12,5.45,0,5.61,6.48,6.6,10.92,8.1,9.12,3.09,16.5,4.8,16.5,16.56,0,12.33-9.12,15.75-20.82,15.75a82.86,82.86,0,0,1-18.45-2.1L408.51,75a90.34,90.34,0,0,0,14.22,1.47C427,76.49,435.12,76.64,435.12,70.34Z"/><path class="shape" d="M504.1,85H492.7V52c0-8.52-1.56-12.12-12.57-12.12A25.85,25.85,0,0,0,470.05,42V85h-11.4V10.89h11.4V32.82a43.71,43.71,0,0,1,13.2-2c18.87,0,20.85,8.79,20.85,19.88Z"/><path class="shape" d="M559.39,85H548v-33c0-8-1.92-12.09-10.56-12.09a20.54,20.54,0,0,0-8.19,1.77,68.48,68.48,0,0,0-.33,7.17V85H517.54V45.29c0-3.51.15-6.56.45-9.8,5.67-2.79,13.92-4.68,22.23-4.68,6.15,0,10.38,1.26,13.26,3.36a47.45,47.45,0,0,1,17.22-3.36c16.71,0,19.17,9.09,19.17,19.88V85h-11.4v-33c0-8-1.92-12.09-10.56-12.09a21.4,21.4,0,0,0-9.39,2.34,35.06,35.06,0,0,1,.87,8.52Z"/><path class="shape" d="M613.73,63.92c.6,10.29,6,12.69,14.25,12.69a152.2,152.2,0,0,0,19.17-1.38l1,8.49a134.31,134.31,0,0,1-23.07,2c-17.91,0-22.62-11.61-22.62-27.45,0-19.37,6-27.41,23.79-27.41,19.23,0,23.34,10.13,23.34,26.06,0,1.29,0,2.61-.15,4-6.12,1.08-18.87,2.34-26.25,2.67Zm10.44-8.28c3.93-.18,10.11-.69,13.8-1.2a23.06,23.06,0,0,0,.12-2.49c0-8.13-3-12.57-11.88-12.57-11.25,0-12.78,7.11-12.78,16.77Z"/><path class="shape" d="M673.23,85H661.86V45.29c0-3.51.15-6.56.45-9.8,6-3.36,14-4.68,21-4.68,1.77,0,3.42.06,5,.21l-.9,9.05a33.28,33.28,0,0,0-4.08-.21c-3.42,0-7.44.6-9.75,1.81a68.16,68.16,0,0,0-.33,7.16Z"/><path class="shape" d="M706.74,63.92c.6,10.29,6,12.69,14.25,12.69a152.2,152.2,0,0,0,19.17-1.38l1,8.49a134.31,134.31,0,0,1-23.07,2c-17.91,0-22.62-11.61-22.62-27.45,0-19.37,6-27.41,23.79-27.41,19.23,0,23.34,10.13,23.34,26.06,0,1.29,0,2.61-.15,4-6.12,1.08-18.87,2.34-26.25,2.67Zm10.44-8.28c3.93-.18,10.11-.69,13.8-1.2A23.06,23.06,0,0,0,731.1,52c0-8.13-3-12.57-11.88-12.57-11.25,0-12.78,7.11-12.78,16.77Z"/></g></svg></div>
    <svg id="triflame" class="fade" version="1.1" xmlns="http://www.w3.org/2000/svg" x="0px" y="0px" viewBox="0 0 11.1 18.5" style="enable-background:new 0 0 11.1 18.5;" xml:space="preserve"><style type="text/css"> .st0{fill:#FFFFFF;} </style> <path class="st0" d="M5.7,18.3c-0.6-0.3-1.1-0.7-1.5-1.2c-0.4-0.5-0.8-1.1-1-1.8c-0.2-0.7-0.4-1.4-0.4-2.2c0-4.6,3.8-7,3.4-11.6 c0-0.3,0-0.5-0.1-0.8C5.9,0.5,5.8,0.3,5.7,0.2c0.6,0.3,1.1,0.7,1.5,1.2c0.4,0.5,0.8,1.1,1,1.8c0.2,0.7,0.4,1.4,0.4,2.2 c0,3.9-3.6,6.8-3.6,11c0,0.4,0.1,0.8,0.2,1.1C5.3,17.8,5.4,18.1,5.7,18.3"/> <path class="st0" d="M9.1,18.1c-0.4-0.2-0.7-0.5-1-0.8c-0.3-0.3-0.5-0.7-0.7-1.2c-0.2-0.4-0.2-0.9-0.2-1.5c0-3.1,2.8-4.8,2.4-8.7 c0.5,0.5,1,1.4,1.3,2C10.9,8.3,11,8.8,11,9.3c0,2.6-2.4,4.6-2.4,7.4c0,0.3,0,0.5,0.1,0.7C8.8,17.7,8.9,17.9,9.1,18.1"/> <path class="st0" d="M2,12.9c-0.4-0.2-0.7-0.5-1-0.8c-0.3-0.3-0.5-0.7-0.7-1.2C0.2,10.4,0.1,10,0.1,9.4c0-3.1,2.8-4.8,2.4-8.7 c0.5,0.5,1,1.4,1.3,2C3.9,3.2,4,3.6,4,4.2c0,2.6-2.4,4.6-2.4,7.4c0,0.3,0,0.5,0.1,0.7C1.8,12.5,1.9,12.7,2,12.9"/> </svg>
    <div id="hcSplashSpinner" class="fade-spin"></div>
</div>

<br>
<br>
<br>

:::
##### How to Implement the Launch Screen

#### 1. Add the needed markup and css to your index.html file.
Contrary to typical best practices, in this case it's preferrable to put the raw CSS/HTML for the launch screen directly into the index.html file. This allows the styles to be immediately available, avoiding a blank page while waiting for the needed HTTP requests to complete.

In Angular applications, this code can be placed within the root element tags (illustrated below), and will be replaced when the root component is ready.

#### 2. Add your logo.
Replace the SVG XML inside the `#logoContainer` with your own app logo. The design team can provide this for you, or if you already have the logo, you can use an online tool to convert the SVG into XML (or base64).

#### 3. Wire in launch styles elsewhere as needed.
If you'd like to show the launch screen after the initial load is complete, perhaps while you wait for authentication or other Angular resolvers to complete, you can also place the launch screen markup and styles in another component. You'll no longer need to place the styles directly in the markup.
:::


:::

##### Example index.html

```html
<!doctype html>
<html lang="en">
    <head>
        <meta charset="utf-8">
        <title>Cashmere Application</title>
        <base href="/">
        <meta name="viewport" content="width=device-width, initial-scale=1">
        <link rel="icon" type="image/x-icon" href="favicon.ico">
    </head>

    <body>
        <hc-root> <!-- Opening tag for the root component of your application (if an angular app) -->

            <!-- Begin Cashmere Launch Screen Code -->
            <style type="text/css">
                body { font-family: Arial, Helvetica, sans-serif; }
                #preBootstrap { position: fixed; top: 0px; left: 0px; height: 100%; width: 100%; background-color: #2E3946; z-index: 999999; }
                #triflame { position: absolute; height: 50px; width: 50px; top: calc(50% - 25px); left: calc(50% - 25px); }
                #logoContainer { position: absolute; top: calc(50% - 100px); left: 0; width: 100%; }
                #logo { width: 180px; height: 30px; } .shape { fill: #fff;}
                #hcSplashSpinner { width: 100px; height: 100px; transform-origin: center center; border: 3px solid rgba(0, 0, 0, 0.2); border-radius: 50%; border-top: 3px solid #fff; }
                .center-children { display: flex; align-items: center; justify-content: center; }

                .fade-spin { animation: spin 1.2s linear infinite, fade 1.5s; -webkit-animation: spin 1.2s linear infinite, fade 1.5s; }
                @keyframes spin { 0% { transform: rotate(0deg); } 100% { transform: rotate(360deg); } }
                @-webkit-keyframes spin { 0% { -webkit-transform: rotate(0deg); } 100% { -webkit-transform: rotate(360deg); } }

                .fade { animation: fade 1.5s; -webkit-animation: fade 1.5s; }
                @keyframes fade { 0% { opacity: 0; } 100% { opacity: 1; } }
                @-webkit-keyframes fade { 0% { opacity: 0; } 100% { opacity: 1; } }
            </style>
            <div id="preBootstrap" class="center-children">
                <div id="logoContainer" class="center-children fade"><svg id="logo" data-name="AppLogo" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 747.7 110.52"><!-- your logo SVG code --></svg></div>
                <svg id="triflame" class="fade" version="1.1" xmlns="http://www.w3.org/2000/svg" x="0px" y="0px" viewBox="0 0 11.1 18.5" style="enable-background:new 0 0 11.1 18.5;" xml:space="preserve"><style type="text/css"> .st0{fill:#FFFFFF;} </style> <path class="st0" d="M5.7,18.3c-0.6-0.3-1.1-0.7-1.5-1.2c-0.4-0.5-0.8-1.1-1-1.8c-0.2-0.7-0.4-1.4-0.4-2.2c0-4.6,3.8-7,3.4-11.6 c0-0.3,0-0.5-0.1-0.8C5.9,0.5,5.8,0.3,5.7,0.2c0.6,0.3,1.1,0.7,1.5,1.2c0.4,0.5,0.8,1.1,1,1.8c0.2,0.7,0.4,1.4,0.4,2.2 c0,3.9-3.6,6.8-3.6,11c0,0.4,0.1,0.8,0.2,1.1C5.3,17.8,5.4,18.1,5.7,18.3"/> <path class="st0" d="M9.1,18.1c-0.4-0.2-0.7-0.5-1-0.8c-0.3-0.3-0.5-0.7-0.7-1.2c-0.2-0.4-0.2-0.9-0.2-1.5c0-3.1,2.8-4.8,2.4-8.7 c0.5,0.5,1,1.4,1.3,2C10.9,8.3,11,8.8,11,9.3c0,2.6-2.4,4.6-2.4,7.4c0,0.3,0,0.5,0.1,0.7C8.8,17.7,8.9,17.9,9.1,18.1"/> <path class="st0" d="M2,12.9c-0.4-0.2-0.7-0.5-1-0.8c-0.3-0.3-0.5-0.7-0.7-1.2C0.2,10.4,0.1,10,0.1,9.4c0-3.1,2.8-4.8,2.4-8.7 c0.5,0.5,1,1.4,1.3,2C3.9,3.2,4,3.6,4,4.2c0,2.6-2.4,4.6-2.4,7.4c0,0.3,0,0.5,0.1,0.7C1.8,12.5,1.9,12.7,2,12.9"/> </svg>
                <div id="hcSplashSpinner" class="fade-spin"></div>
            </div>
            <!-- End Cashmere Launch Screen Code -->

        </hc-root>
    </body>
</html>
```