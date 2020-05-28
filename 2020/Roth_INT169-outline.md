# Modern Web UI with Blazor WebAssembly

## Setup

- Open web browser: `msedge.exe --remote-debugging-port=9222 https://blazor.net`
- Set browser preferred language to English, with Spanish as an option
- Delete any previous default Blazor app projects
- Start Visual Studio
- Open CarChecker solution in separate VS instance
- Start CarChecker server
- Run CarChecker app, logout, login, close app
- Uninstall sample Blazor PWAs
- Run ZoomIt
- Clock hidden
- Clean desktop
- Hide clock
- Turn off notifications


> 0:00

Hello everyone and welcome! My name is Daniel Roth and I'm a Program Manager on the ASP.NET team. I'm joined today by Steve Sanderson, a Principal Software Engineer on the ASP.NET team. In this session we're going to talk about building modern web UI with Blazor WebAssembly. Feel free to post your questions and we will do a live Q&A later in the session.

## What is Blazor?

Let's say you're building a sophisticated web app. It runs in regular desktop browsers, and maybe it can also be installed as a progressive web app on mobile devices. You're app is going to need a rich interactive UI with grids, dialogs, wizards, forms, validation, and of course you've got to worry about authentication, localization, and so on.

A few years, ago the only way to build such a thing would be to use a JavaScript framework and to write your app in JavaScript or a language that compiles to Javascript. But thanks to modern web standards, that's no longer the case. Blazor is a web UI framework for building single-page apps using .NET and C# instead of JavaScript. With Blazor you can build your entire app with .NET. You can get the productivity of C#, Visual Studio, and a consistent and stable ecosystem to build rich modern web UI along with a high performance .NET backend. Blazor is open source, cross-platform, and runs in any modern web browser.

## Blazor WebAssembly released!

Today we are thrilled to announce that Blazor WebAssembly is now official released and supported for production use. Blazor WebAssembly enables running .NET code directly in the browser using a WebAssembly based .NET runtime that is deployed with your app. When paired with .NET Core, Blazor WebAssembly enables full-stack web development with .NET. Blazor WebAssembly is now included with the latest .NET Core SDK and also ships with Visual Studio 2019 16.6.

## Blazor WebAssembly features

This release of Blazor WebAssembly comes packed with features!:

- **.NET Standard 2.1**: Blazor WebAssembly supports .NET Standard 2.1, so you can reuse existing libraries on both the client and the server
- **ASP.NET Core hosted / standalone**: You can host your app with ASP.NET Core for a full-stack experience, or deploy your app as a standalone static site.
- **Authentication**: Blazor WebAssembly supports authentication using ASP.NET Core Identity & IdentityServer, Azure AD, Azure AD B2C, or an OpenID Connect provider of your choice.
- **Progressive Web Apps**: You can use Blazor WebAssembly to create Progressive Web Apps (PWAs) that support offline execution and native OS integration.
- **Debugging**: You can debug your code running in the browser using the browser dev tools or directly from Visual Studio.
- **IL trimming**: When you publish your app, unused code gets automatically trimmed to significantly reduce the app download size.
- **Precompressed**: We also aggressively precompress the published app to reduce its size even further.
- **Configuration**: You can also configure your app...
- **Localization**: ...and localize it using the same abstractions used in ASP.NET Core.

## Get started

Blazor WebAssembly is super easy to get started with. Just go to https://blazor.net and download the latest .NET Core SDK (3.1.300 or later). You can then develop your Blazor WebAssembly app using Visual Studio, Visual Studio for Mac, or Visual Studio Code.

## Demo: Blazor WebAssembly in Action

> 4:00

Let's go build our first Blazor WebAssembly app!

On https://blazor.net, click on Get Started and we will walk you through creating your first Blazor. I've already setup my machine using Visual Studio, which has everything I need to build Blazor WebAssembly apps. You can likewise get setup to use Blazor WebAssembly or your Mac or Linux machine.

- Create a new Blazor project
- Select the **ASP.NET Core hosted** and **PWA** options
- Enable authentication
- Run the app *without* debugging using a browser setup for debugging
- Show the counter
- Debug the counter in the browser
- Run the app *with* debugging from VS and debug the counter in VS
- Show Fetch data
- Register a new user and login
- Debug fetch data to show full stack debugging
- Show that the app is setup with a manifest and a service worker
- Install the app as a PWA

Now let's switch to a more elaborate app that
- Switch to CarChecker (published version running locally)
- Log in
- Search for a car
- Update the mileage and gas
- Show off the 3D rendering
- Add a note
- Show offline functionality (disable connection, right-click and reload)
- Show localization
- Refresh login checkin

As you can see this is a fully featured app ready to go into production and built almost entirely with .NET and C# using Blazor WebAssembly. To see more about how this app works and how it takes advantage of Blazor WebAssembly's capabilities, be sure to check out Steve's on demand video on BlazorWebAssembly at https://aka.ms/Build2020AppDev-Blazor. You can also find the code for this app at https://aka.ms/carchecker-blazor

## Components

Blazor is a component based framework, so your Blazor apps are going to need lots of beautiful and feature rich UI components. Fortunately our partners have been hard at work building lots of wonderful Blazor UI components. Be sure to check out their various offerings. 

## Open source

And, of course, we have to give a shout out to the Blazor open-source community. Folks in the Blazor community, (folks just like you!) have built lots of great component libraries, interop libraries, test frameworks, and the like and made them freely available for you to use. You can find many of them listed on the Awesome Blazor GitHub repo at https://aka.ms/awesomeblazor.

## Blazor .NET 5

So what's next for Blazor? In the .NET 5 & 6 wave we have a number of important improvements coming. Now that we've wrapped up this Blazor WebAssembly release we will be merging it into .NET 5. 

Our goal is to make Blazor the best framework possible for building modern web apps.

## Try Blazor today!

I hope you are as excited as we are about the Blazor WebAssembly release! We invite all of you to give Blazor, and especially the newly released Blazor WebAssembly, a try today!

## Q&A

And with that, I'm now going to give the remaining time over to you so that you can ask any of your Blazor related questions, which Steve or I will be happy to answer.