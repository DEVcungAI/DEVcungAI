# For full reading experience, please access the following URL:

https://learn.microsoft.com/en-us/aspnet/core/introduction-to-aspnet-core?view=aspnetcore-10.0



➡➡➡➡➡



# Overview of ASP.NET Core

Article • 06/18/2024

By Daniel Roth , Rick Anderson , and Shaun Luttin


Why choose ASP.NET Core?

Build web APIs and web UI using ASP.NET Core MVC

Client-side development

ASP.NET Core target frameworks

Recommended learning path

Migrate from .NET Framework

How to download a sample

Preprocessor directives in sample code

Breaking changes and security advisories

Next steps



# Choose between ASP.NET 4.x and ASP.NET Core

Article • 04/10/2024


ASP.NET Core

ASP.NET 4.x

Framework selection

ASP.NET Core scenarios

ASP.NET 4.x scenarios

Additional resources



# .NET vs. .NET Framework for server apps

Article • 11/22/2024


Choose .NET

When to choose .NET Framework

See also



# Tutorial: Get started with ASP.NET Core

Article • 09/18/2024


Prerequisites

Create a web app project

Run the app

Edit a Razor page

Next steps



# What's new in ASP.NET Core 9.0

Article • 11/19/2024


Static asset delivery optimization

Enabling dynamic compression on the server vs using MapStaticAssets

Blazor

.NET MAUI Blazor Hybrid and Web App solution template

Detect rendering location, interactivity, and assigned render mode at runtime

Improved server-side reconnection experience:

Simplified authentication state serialization for Blazor Web Apps

Add static server-side rendering (SSR) pages to a globally-interactive Blazor Web App

Constructor injection

Websocket compression for Interactive Server components

Handle keyboard composition events in Blazor

Added OverscanCount parameter to QuickGrid

InputNumber component supports the type="range" attribute

New enhanced navigation events

SignalR

Polymorphic type support in SignalR Hubs

Improved Activities for SignalR

.NET SignalR server ActivitySource

.NET SignalR client ActivitySource

SignalR supports trimming and Native AOT

Getting started

Limitations

Minimal APIs

Added InternalServerError and InternalServerError<TValue> to TypedResults

Call ProducesProblem and ProducesValidationProblem on route groups

Problem and ValidationProblem result types support construction with IEnumerable<KeyValuePair<string, object?>> values

OpenAPI

Built-in support for OpenAPI document generation

Microsoft.AspNetCore.OpenApi supports trimming and Native AOT

Get started

Authentication and authorization

OpenIdConnectHandler adds support for Pushed Authorization Requests (PAR)

OIDC and OAuth Parameter Customization

Configure HTTP.sys extended authentication flags

Miscellaneous

New HybridCache library

A note on object reuse

Other HybridCache features

Developer exception page improvements

Dictionary debugging improvements

Fix for 503's during app recycle in IIS

ASP0026: Analyzer to warn when [Authorize] is overridden by [AllowAnonymous] from "farther away"

Improved Kestrel connection metrics

Customize Kestrel named pipe endpoints

ExceptionHandlerMiddleware option to choose the status code based on the exception type

Opt-out of HTTP metrics on certain endpoints and requests

Data Protection support for deleting keys

Middleware supports Keyed DI

Trust the ASP.NET Core HTTPS development certificate on Linux

Templates updated to latest Bootstrap, jQuery, and jQuery Validation versions



# What's new in ASP.NET Core 8.0

Article • 11/06/2024


Blazor

Full-stack web UI

New article on class libraries with static server-side rendering (static SSR)

New article on HTTP caching issues

New Blazor Web App template

New JS initializers for Blazor Web Apps

Split of prerendering and integration guidance

Persist component state in a Blazor Web App

Form handling and model binding

Enhanced navigation and form handling

New article on static rendering with enhanced navigation for JS interop

Streaming rendering

Inject keyed services into components

Access HttpContext as a cascading parameter

Render Razor components outside of ASP.NET Core

Sections support

Error page support

QuickGrid

Route to named elements

Root-level cascading values

Virtualize empty content

Close circuits when there are no remaining interactive server components

Monitor SignalR circuit activity

Faster runtime performance with the Jiterpreter

Ahead-of-time (AOT) SIMD and exception handling

Web-friendly Webcil packaging

Blazor WebAssembly debugging improvements

Content Security Policy (CSP) compatibility

Handle caught exceptions outside of a Razor component's lifecycle

Configure the .NET WebAssembly runtime

Configuration of connection timeouts in HubConnectionBuilder

Project templates shed Open Iconic

Support for dialog cancel and close events

Blazor Identity UI

Secure Blazor WebAssembly with ASP.NET Core Identity

Blazor Server with Yarp routing

Multiple Blazor Web Apps per server project

Blazor Hybrid

[Parameter] attribute is no longer required when supplied from the query string

SignalR

New approach to set the server timeout and Keep-Alive interval

Prior approach for JavaScript clients

New approach for JavaScript clients

Prior approach for the JavaScript client of a Blazor Server app

New approach for the JavaScript client of server-side Blazor app

Prior approach for .NET clients

New approach for .NET clients

SignalR stateful reconnect

Minimal APIs

User override culture

Binding to forms

Antiforgery with minimal APIs

New IResettable interface in ObjectPool

Native AOT

Libraries and Native AOT

New project template

New CreateSlimBuilder method

New CreateEmptyBuilder method

Reduced app size with configurable HTTPS support

JSON serialization of compiler-generated IAsyncEnumerable<T> types

Top-level APIs annotated for trim warnings

Request delegate generator

Improved performance using Interceptors

Logging and exception handling in compile-time generated minimal APIs

AOT and System.Text.Json

Libraries and Native AOT

Kestrel and HTTP.sys servers

Support for named pipes in Kestrel

Performance improvements to named pipes transport

HTTP/2 over TLS (HTTPS) support on macOS in Kestrel

Certificate file watching in Kestrel

Warning when specified HTTP protocols won't be used

HTTP_PORTS and HTTPS_PORTS config keys

SNI host name in ITlsHandshakeFeature

IHttpSysRequestTimingFeature

HTTP.sys: opt-in support for kernel-mode response buffering

Authentication and authorization

Identity API endpoints

IAuthorizationRequirementData

Securing Swagger UI endpoints

Miscellaneous

Keyed services support in Dependency Injection

Visual Studio project templates for SPA apps with ASP.NET Core backend

Support for generic attributes

Code analysis in ASP.NET Core apps

Route tooling

ASP.NET Core metrics

IExceptionHandler

Improved debugging experience

IPNetwork.Parse and TryParse

Redis-based output caching

Short-circuit middleware after routing

HTTP logging middleware extensibility

New APIs in ProblemDetails to support more resilient integrations

Additional resources



# What's new in ASP.NET Core 7.0

Article • 09/27/2024


Rate limiting middleware in ASP.NET Core

Authentication uses single scheme as DefaultScheme

MVC and Razor pages

Support for nullable models in MVC views and Razor Pages

Bind with IParsable<T>.TryParse in MVC and API Controllers

Customize the cookie consent value

API controllers

Parameter binding with DI in API controllers

JSON property names in validation errors

Minimal APIs

Filters in Minimal API apps

Bind arrays and string values from headers and query strings

Bind the request body as a Stream or PipeReader

New Results.Stream overloads

Typed results for minimal APIs

Improved unit testability for minimal route handlers

New HttpResult interfaces

OpenAPI improvements for minimal APIs

Microsoft.AspNetCore.OpenApi NuGet package

Call WithOpenApi with parameters

Provide endpoint descriptions and summaries

File uploads using IFormFile and IFormFileCollection

[AsParameters] attribute enables parameter binding for argument lists

Minimal APIs and API controllers

New problem details service

Route groups

gRPC

JSON transcoding

gRPC health checks in ASP.NET Core

Improved call credentials support

SignalR

Client results

Dependency injection for SignalR hub methods

Blazor

Handle location changing events and navigation state

Empty Blazor project templates

Blazor custom elements

Bind modifiers ( @bind:after , @bind:get , @bind:set )

Hot Reload improvements

Dynamic authentication requests with MSAL in Blazor WebAssembly

Blazor WebAssembly debugging improvements

System.Security.Cryptography support on WebAssembly

Inject services into custom validation attributes

Input\* components outside of an EditContext / EditForm

Project template changes

Experimental QuickGrid component

Virtualization enhancements

MouseEventArgs updates

New Blazor loading page

Improved diagnostics for authentication in Blazor WebAssembly

JavaScript interop on WebAssembly

Conditional registration of the authentication state provider

Improvements to the .NET WebAssembly build tools

Blazor Hybrid

External URLs

Security

Performance

Output caching middleware

HTTP/3 improvements

HTTP/2 Performance improvements

Http/2 WebSockets support

Kestrel performance improvements on high core machines

ServerReady event to measure startup time

Server

New ServerReady event for measuring startup time

IIS

Shadow copying in IIS

Miscellaneous

Kestrel full certificate chain improvements

dotnet watch

Improved console output for dotnet watch

Configure dotnet watch to always restart for rude edits

Developer exception page dark mode

Project template option to use Program.Main method instead of top-level statements

Updated Angular and React templates

Manage JSON Web Tokens in development with dotnet user-jwts

Support for additional request headers in W3CLogger

Request decompression



# What's new in ASP.NET Core 6.0

Article • 10/18/2024


ASP.NET Core MVC and Razor improvements

Minimal APIs

SignalR

Long running activity tag for SignalR connections

SignalR performance improvements

Razor compiler

Razor compiler updated to use source generators

Razor compiler no longer produces a separate Views assembly

ASP.NET Core performance and API improvements

Reduced memory footprint for idle TLS connections

Reduce the size of System.IO.Pipelines.Pipe

Pool SocketSender

Zero bytes reads with SslStream

Zero byte reads with PipeReader

Remove slabs from the SlabMemoryPool

IAsyncDisposable supported

Vcpkg port for SignalR C++ client

Blazor

Project template changes

Blazor WebAssembly native dependencies support

WebAssembly Ahead-of-time (AOT) compilation and runtime relinking

Persist prerendered state

Error boundaries

SVG support

Blazor Server support for byte array transfer in JS Interop

Query string enhancements

Binding to select multiple

Head ( <head> ) content control

Generate Angular and React components

Render components from JavaScript

Custom elements

Infer component generic types from ancestor components

Dynamically rendered components

Improved Blazor accessibility

Custom event argument support

Required parameters

Collocation of JavaScript files with pages, views, and components

JavaScript initializers

Streaming JavaScript interop

Generic type constraints

WebAssembly deployment layout

New Blazor articles

Build Blazor Hybrid apps with .NET MAUI, WPF, and Windows Forms

Kestrel

New Kestrel logging categories for selected logging

Emit KestrelServerOptions via EventSource event

New DiagnosticSource event for rejected HTTP requests

Create a ConnectionContext from an Accept Socket

Kestrel is the default launch profile for Visual Studio

Localhost ports for Kestrel are random

Authentication and authorization

Authentication servers

Delayed client certificate negotiation

OnCheckSlidingExpiration event for controlling cookie renewal

Miscellaneous

Hot Reload

Improved single-page app (SPA) templates

Draft HTTP/3 support in .NET 6

Nullable Reference Type Annotations

Source Code Analysis

Web app template improvements

Template generated ports for Kestrel

New logging defaults

Developer exception page Middleware added automatically

Support for Latin1 encoded request headers in HttpSysServer

The ASP.NET Core Module logs include timestamps and PID

Configurable unconsumed incoming buffer size for IIS

View Components Tag Helpers

Angular template updated to Angular 12

Configurable buffer threshold before writing to disk in Json.NET output formatter

Faster get and set for HTTP headers

Async streaming

HTTP logging middleware

IConnectionSocketFeature

Generic type constraints in Razor

Smaller SignalR, Blazor Server, and MessagePack scripts

Enable Redis profiling sessions

Shadow copying in IIS

Additional resources



# What's new in ASP.NET Core 5.0

Article • 09/27/2024


ASP.NET Core MVC and Razor improvements

Model binding DateTime as UTC

Model binding and validation with C\# 9 record types

Improvements to DynamicRouteValueTransformer

Miscellaneous

Web API

OpenAPI Specification on by default

Azure API Management Import

Better launch experience for web API projects

Blazor

Performance improvements

CSS isolation

New InputFile component

New InputRadio and InputRadioGroup components

Component virtualization

ontoggle event support

Set UI focus in Blazor apps

Custom validation CSS class attributes

IAsyncDisposable support

JavaScript isolation and object references

Form components support display name

Catch-all route parameters

Debugging improvements

Microsoft Identity v2.0 and MSAL v2.0

Protected Browser Storage for Blazor Server

Blazor WebAssembly prerendering

Trimming/linking improvements

Browser compatibility analyzer

Lazy load assemblies

Updated globalization support

gRPC

SignalR

SignalR Hub filters

SignalR parallel hub invocations

Added Messagepack support in SignalR Java client

Kestrel

Kestrel endpoint-specific options via configuration

Performance improvements

HTTP/2

Containers

Authentication and authorization

Microsoft Entra ID authentication with Microsoft.Identity.Web

Allow anonymous access to an endpoint

Custom handling of authorization failures

Authorization when using endpoint routing

Role-based access control with Kerberos authentication and LDAP on Linux

API improvements

JSON extension methods for HttpRequest and HttpResponse

System.Diagnostics.Activity

FromBodyAttribute

Miscellaneous improvements

Control Startup class activation

Auto refresh with dotnet watch

Console Logger Formatter

JSON Console Logger



# What's new in ASP.NET Core 3.1

Article • 09/25/2023


Partial class support for Razor components

Component Tag Helper and pass parameters to top-level components

Support for shared queues in HTTP.sys

Breaking changes for SameSite cookies

Prevent default actions for events in Blazor apps

Stop event propagation in Blazor apps

Detailed errors during Blazor app development


# What's new in ASP.NET Core 3.0

Article • 09/27/2023


Blazor

Blazor Server

Blazor WebAssembly (Preview)

Razor components

gRPC

SignalR

New JSON serialization

New Razor directives

IdentityServer4 supports authentication and authorization for web APIs and SPAs

Certificate and Kerberos authentication

Template changes

Generic Host

Host configuration

Changes to Startup constructor injection

Kestrel

HTTP/2 enabled by default

EventCounters on request

Endpoint routing

Health Checks

Pipes on HttpContext

Improved error reporting in IIS

Worker Service and Worker SDK

Forwarded Headers Middleware improvements

Performance improvements

ASP.NET Core 3.0 only runs on .NET Core 3.0

Use the ASP.NET Core shared framework

Assemblies removed from the ASP.NET Core shared framework


# What's new in ASP.NET Core 2.2

Article • 08/14/2024


OpenAPI Analyzers & Conventions

Problem details support

Endpoint Routing

Health checks

HTTP/2 in Kestrel

Kestrel configuration

IIS in-process hosting

SignalR Java client

CORS improvements

Response compression

Project templates

Validation performance

HTTP Client performance

Additional information



# What's new in ASP.NET Core 2.1

Article • 08/30/2024


SignalR

Razor class libraries

Identity UI library & scaffolding

HTTPS

On by default

HTTPS redirection and enforcement

Configuration for production

GDPR

Integration tests

[ApiController], ActionResult<T>

IHttpClientFactory

Kestrel libuv transport configuration

Generic host builder

Updated SPA templates

Razor Pages search for Razor assets

Razor Pages in an area

MVC compatibility version

Migrate from 2.0 to 2.1

Additional information



# What's new in ASP.NET Core 2.0

Article • 09/18/2024


Razor Pages

ASP.NET Core metapackage

Runtime Store

.NET Standard 2.0

Configuration update

Logging update

Authentication update

Identity update

SPA templates

Kestrel improvements

WebListener renamed to HTTP.sys

Enhanced HTTP header support

Hosting startup and Application Insights

Automatic use of antiforgery tokens

Automatic precompilation

Razor support for C# 7.1

Other documentation updates for 2.0

Migration guidance

Additional Information



# What's new in ASP.NET Core 1.1

Article • 06/03/2022


Choosing between versions 1.0 and 1.1 of ASP.NET Core

Additional Information



# ASP.NET Core documentation - what's new?


Find ASP.NET Core docs updates

WHAT'S NEW

June 2024

May 2024

April 2024

March 2024

February 2024

January 2024


Get involved - contribute to ASP.NET Core docs

OVERVIEW

ASP.NET Core docs repository

Project structure and labels for issues and pull requests


CONCEPT

Contributor guide

ASP.NET Core docs contributor guide

ASP.NET Core API reference docs contributor guide


Community

WHAT'S NEW

Community


Related what's new pages

WHAT'S NEW

Xamarin docs updates

.NET Core release notes

ASP.NET Core release notes

C# compiler (Roslyn) release notes

Visual Studio release notes

Visual Studio for Mac release notes

Visual Studio Code release notes



# Choose an ASP.NET Core web UI

Article • 10/21/2024


ASP.NET Core Blazor

ASP.NET Core Razor Pages

ASP.NET Core MVC

ASP.NET Core Single Page Applications (SPA) with frontend JavaScript frameworks

Combine multiple web UI solutions: ASP.NET Core MVC or Razor Pages plus Blazor

Next steps



# Tutorial: Create a Razor Pages web app with ASP.NET Core

Article • 07/01/2024


This series includes the following tutorials:

1. Create a Razor Pages web app

2. Add a model to a Razor Pages app

3. Scaffold (generate) Razor pages

4. Work with a database

5. Update Razor pages

6. Add search

7. Add a new field

8. Add validation



# Tutorial: Get started with Razor Pages in ASP.NET Core

Article • 08/05/2024


Prerequisites

Create a Razor Pages web app

Run the app

Examine the project files

Pages folder

wwwroot folder

```appsettings.json```

Program.cs

Troubleshooting with the completed sample

Next steps



# Part 2, add a model to a Razor Pages app in ASP.NET Core

Article • 10/29/2024


Add a data model

Scaffold the movie model

Files created and updated

Create the initial database schema using EF's migration feature

Test the app

Examine the context registered with dependency injection

Troubleshooting with the completed sample

Next steps



# Part 3, scaffolded Razor Pages in ASP.NET Core

Article • 07/01/2024


The Create, Delete, Details, and Edit pages

The @page directive

The @model directive

The layout page

ViewData and layout

Update the layout

The Create page model

The Create Razor Page

Next steps



# Part 4 of tutorial series on Razor Pages

Article • 09/17/2024


Seed the database

Add the seed initializer

Test the app

Next steps



# Part 5, update the generated pages in an ASP.NET Core app

Article • 07/01/2024

Update the model

Add route template

Review concurrency exception handling

Posting and binding review

Next steps



# Part 6, add search to ASP.NET Core Razor Pages

Article • 07/01/2024

Search by genre

Add search by genre to the Razor Page

Next steps



# Part 7, add a new field to a Razor Page in ASP.NET Core

Article • 07/01/2024

Adding a Rating Property to the Movie Model

Add a migration for the rating field

Next steps



# Part 8 of tutorial series on Razor Pages

Article • 07/01/2024

Validation

Add validation rules to the movie model

Validation Error UI in Razor Pages

Server-side validation

Use DataType Attributes

Apply migrations

Publish to Azure

Additional resources

Next steps



# Get started with ASP.NET Core MVC

Article • 07/30/2024

Prerequisites

Create a web app

Run the app



# Part 2, add a controller to an ASP.NET Core MVC app

Article • 07/30/2024

Add a controller



# Part 3, add a view to an ASP.NET Core MVC app

Article • 07/30/2024

Add a view

Change views and layout pages

Change the title, footer, and menu link in the layout file

Passing Data from the Controller to the View



# Part 4, add a model to an ASP.NET Core MVC app

Article • 07/30/2024

Add a data model class

Add NuGet packages

Scaffold movie pages

Initial migration

Test the app

Examine the generated database context class and registration

Dependency injection

Examine the generated database connection string

The InitialCreate class

Dependency injection in the controller

Strongly typed models and the @model directive

Additional resources



# Part 5, work with a database in an ASP.NET Core MVC app

Article • 09/10/2024

SQL Server Express LocalDB

Examine the database

Seed the database

Add the seed initializer



# Part 6, controller methods and views in ASP.NET Core

Article • 09/18/2024

Processing the POST Request

Additional resources



# 