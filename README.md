# Karate for VS Code

[Karate](https://karatelabs.github.io/karate/) is an open-source test-automation framework.

This extension is brought to you by [Karate Labs](https://karatelabs.io). Find it at the [Visual Studio Marketplace](https://marketplace.visualstudio.com/items?itemName=karatelabs.karate) or [Open VSX Registry](https://open-vsx.org/extension/karatelabs/karate).

## Ready To Run
No extra installation or setup is required. Everything needed to write and run Karate scripts is included.

## Command Line
Once you are familiar with Karate and have created a few tests, you may want to run them from the command-line. You have two options:

* Use the [stand-alone JAR](https://github.com/karatelabs/karate/wiki/Get-Started:-Other-Runtime-Options), recommended if you are new to programming
* use a standard [Java Maven or Gradle project](https://github.com/karatelabs/karate/wiki/Get-Started:-Maven-and-Gradle), and you can refer to the [Karate examples](https://github.com/karatelabs/karate-examples/blob/main/README.md) for sample "starter" projects.

# Core Features
* [API testing](https://karatelabs.github.io/karate/), [API mocks](https://karatelabs.github.io/karate/karate-netty/), and [UI / web-browser automation](https://karatelabs.github.io/karate/karate-core/)
* Syntax coloring
* Code Formatting
* Outline view
* Embedded JS highlighting
* Run test (CodeLens)
* Color log output
* One-click to open HTML report
* Extra run modes (configurable via extension settings)
  * Maven
  * Custom (e.g. for Gradle or [stand-alone JAR](https://karatelabs.github.io/karate/karate-netty/#standalone-jar))
* Works in remote environments (e.g. [GitHub Codespaces](https://github.com/karatelabs/karate/wiki/Karate-in-GitHub-Codespaces), [Gitpod](https://www.gitpod.io/), [Devcontainers / Docker](https://code.visualstudio.com/docs/devcontainers/containers))

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
<tr>
<td><a href="#inline-reports">Inline Reports</a></td>
</tr>
</table>

# K-Flow
K-Flow is an enterprise solution that solves for API documentation, with a focus on end-user workflows. The highlights are:
* A no-code interface for creating, editing and previewing these flows
* First-class support for OpenAPI and Swagger
* Export to pure-HTML for publishing or internal-collaboration
* Showing how multiple APIs are called in sequence as a business workflow
* Showing variations of a given API due to business-rules

K-Flow is a separate upgrade from Karate Pro. For more details on pricing and features, [refer to our website](https://www.karatelabs.io/k-flow).

## How to Sign In
* Use the "Accounts" toolbar in VS Code (usually on the bottom left, see screenshot below)
  * If you don't see the option to `Sign in with Karate` make sure you have opened a folder with a `*.feature` file in it to activate the plugin
  * It also can happen that another plugin has "taken control" of `*.feature` files, so make sure that when you open a Karate feature file - you can see `Karate` as the "Language Mode" in the bottom right corner of VS Code (in the status bar)
  * You can explicitly set the language mode by clicking on the current mode (typically `Gherkin`) and selecting `Karate` from the list
  * Or go to `View --> Command Palette` and search for `Change Language Mode`
* Once signed-in, you will not be prompted again for 30 days
* New subscribers will be taken through a purchase flow
* You can manage your subscription at [studio.karatelabs.io](https://studio.karatelabs.io)
* Pricing information can be [found on our website](https://www.karatelabs.io/plugins)
* [Contact us](https://karatelabs.io/contact-us) if you need more information

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

## Inline Reports
View summary and Feature / Scenario reports without leaving your IDE. This is especially useful when using a remote development environment such as [GitHub Codespaces](https://github.com/features/codespaces).

<img height="350" src="https://user-images.githubusercontent.com/915480/214324137-e522b43a-93fa-4688-878b-29272ec01715.gif">

Watch [this video](https://youtu.be/aJ7WdHM1t94?t=40) to get a feel of the enhanced Developer-Experience.

You can also see all HTTP calls made during a test.

<img height="350" src="https://user-images.githubusercontent.com/915480/214325821-96d480c5-6dba-4459-9f93-0685caea60a2.gif">

# Coming Soon
* Better IntelliSense & Auto-complete
* Improved syntax validation
* Reports
  * API coverage
* No-code
  * API request builder
  * API mock builder
  * Assertion builder
* Record API tests from browser
* Test case management
