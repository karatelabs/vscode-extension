# Karate for VS Code

[Karate](https://karatelabs.github.io/karate/) is an open-source test-automation framework.

This extension is brought to you by [Karate Labs](https://karatelabs.io). Find it at the [Visual Studio Marketplace](https://marketplace.visualstudio.com/items?itemName=karatelabs.karate) or [Open VSX Registry](https://open-vsx.org/extension/karatelabs/karate).

## Ready To Run
No extra installation or setup is required. Everything needed to write and run Karate scripts is included.

# Core Features
* API and UI / browser automation
* Syntax coloring
* Outline view
* Embedded JS highlighting
* Run test (CodeLens)
* Color log output
* One-click to open HTML report
* Extra run modes
  * Maven
  * Custom (e.g. for Gradle)
* Works in remote environments (e.g. GitHub Codespaces, Gitpod)

# Pro Upgrade
<table>
<tr>
<td><a href="#debug">Debug</a></td>
<td><a href="#code-folding">Code Folding</a></td>
<td><a href="#json-formatting">JSON Formatting</a></td>
</tr>
<tr>
<td><a href="#run-mode">Run Mode</a></td>
<td><a href="#run-options">Run Options</a></td>
<td><a href="#context-menu">Context Menu</a></td>
</tr>
<tr>
<td><a href="#postman-import">Postman Import</a></td>
<td><a href="#openapi-import">OpenAPI / Swagger Import</a></td>
<td><a href="#curl-and-har-import">cURL and HAR Import</a></td>
<tr>
</table>

## How to Sign In
* Use the "Accounts" toolbar in VS Code (usually on the bottom left)
* Once signed-in, you will not be prompted again for 30 days
* New subscribers will be taken through a purchase flow
* Pricing information can be [found on our website](https://www.karatelabs.io/plugins)
* [Contact us](https://www.karatelabs.io/karate-labs-contact) if you need more information

See a 30 second video [here](https://youtu.be/p3QDyXK4ABo).

<a href="https://youtu.be/p3QDyXK4ABo"><img height="250" src="https://user-images.githubusercontent.com/915480/204451498-5e297c5b-2c93-46e9-9fd3-360a6405fc66.png"></a>

## Debug
* In Pro mode, a `Debug` codelens appears next to the `Run >>` option.
* Set break-points and even step-back in time.
* Save time with the hot-reload feature without needing to re-start your flow.
* Interact with a live session using the VS Code debug console.

See a 1 minute video [here](https://youtu.be/_BlUgR9noEI).

<table>
<tr>
<td><a href="https://youtu.be/_BlUgR9noEI"><img height="200" src="https://user-images.githubusercontent.com/915480/204463528-f7445fbb-67d1-4968-91e3-e6ae68499ea0.png"></a></td>
<td><a href="https://youtu.be/_BlUgR9noEI"><img height="200" src="https://user-images.githubusercontent.com/915480/204464214-010aaf5c-84d4-4e89-b751-f7db76dd3f9f.png"></a></td>
</tr>
</table>

## Code Folding

<img height="350" src="https://user-images.githubusercontent.com/915480/204472621-f399be05-3ef2-4c1b-a3ba-49c6a5fa5408.gif">

## JSON Formatting

<img height="350" src="https://user-images.githubusercontent.com/915480/204474431-3a77f7ae-68fe-4a5b-b0bd-8f5c137ab58b.gif">

## Run Mode
Easily switch run-mode.

<img height="300" alt="image" src="https://user-images.githubusercontent.com/915480/204508033-b5bef30a-c3ee-4c6d-baa1-937668254b7a.png">

## Run Options
Easily edit Karate run-options.

<img height="300" alt="image" src="https://user-images.githubusercontent.com/915480/204508355-1f30f132-60cf-406c-b9ce-e3b0ea9a2232.png">

## Context Menu
* Right-click in the explorer view to run all tests in a folder.
* You can even start mocks (see [OpenAPI import](#openapi-import) for more about mocks).

<img height="300" alt="image" src="https://user-images.githubusercontent.com/915480/204508520-e6a8ae02-0cce-41da-9c8e-7e6854ffd0af.png">

## Postman Import

<img height="350" src="https://user-images.githubusercontent.com/915480/204480195-f4068e38-a6ea-4383-a65e-eb8ac9e6b80b.gif">

## OpenAPI Import

* All versions including Swagger support.
* Documentation on the new JS mocks in Karate can be found [here](https://github.com/karatelabs/karate/wiki/Karate-JavaScript-Mocks).
* For extra insights, refer to [this presentation at the API Specifications Conference 2022](https://youtu.be/-atUwH-EP_Y).
* A sample project can be found here: [karate-oas-demo](https://github.com/ptrthomas/karate-oas-demo).

See video [here](https://youtu.be/_2iKwyALkvw).

<a href="https://youtu.be/_2iKwyALkvw"><img height="350" alt="image" src="https://user-images.githubusercontent.com/915480/204509458-65686fe0-d3c5-45d9-a348-3901bfd535da.png"></a>

## cURL and HAR Import

* You can double-click on unused space in the VS Code editor (tab) and use the text-editor as an import source.
* This works even on the JavaScript used in Postman "Tests" so that you can troubleshoot the importing of complex collections.
* All supported formats supported via plain-text this way:
  * cURL
  * HAR
  * Postman
    * Collections
    * Tests / Assertions JS
  * Swagger
  * OpenAPI

<img height="350" src="https://user-images.githubusercontent.com/915480/204512747-b5f1b886-15be-42d0-b974-91ec8f78f98d.gif">

# Karate Flow
Coming Soon

# Coming Soon
* IntelliSense & better Auto-complete
* Improved syntax validation
* API Documentation
  * Authoring
  * Publishing
* Extra reports
  * HTTP request / response
  * HTTP API coverage
* No-code
  * API request builder
  * API mock builder
  * Assertion builder
* Record API tests from browser
* Test case management
