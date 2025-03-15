# For full reading experience, please access the following URL:

https://learn.microsoft.com/en-us/aspnet/core/introduction-to-aspnet-core?view=aspnetcore-10.0



➡➡➡➡➡



# Overview of ASP.NET Core

Article • 06/18/2024

By Daniel Roth, Rick Anderson, and Shaun Luttin


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

Bind modifiers ( @bind:after, @bind:get, @bind:set )

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



# Part 7, add search to an ASP.NET Core MVC app

Article • 09/18/2024

Add Search by genre

Add search by genre to the Index view



# Part 8, add a new field to an ASP.NET Core MVC app

Article • 07/30/2024

Add a Rating Property to the Movie Model



# Part 9, add validation to an ASP.NET Core MVC app

Article • 07/30/2024

Keeping things DRY

Delete the previously edited data

Add validation rules to the movie model

Validation Error UI

How validation works

Using DataType Attributes

Additional resources



# Part 10, examine the Details and Delete methods of an ASP.NET Core app

Article • 08/05/2024

Publish to Azure

Reliable web app patterns



# ASP.NET Core Blazor tutorials

Article • 11/18/2024

Build your first Blazor app

Build a Blazor todo list app (Blazor Web App)

Build a Blazor movie database app (Overview) (Blazor Web App)

Use ASP.NET Core SignalR with Blazor (Blazor Web App)

ASP.NET Core Blazor Hybrid tutorials

Microsoft Learn

Blazor Learning Path

Blazor Learn Modules



# Tutorial: Create a web API with ASP.NET Core

Article • 08/23/2024

Overview

Prerequisites

Create a web project

Add a NuGet package

Test the project

Add a model class

Add a database context

Register the database context

Scaffold a controller

Update the PostTodoItem create method

Test PostTodoItem

Test the location header URI

Examine the GET methods

Routing and URL paths

Return values

The PutTodoItem method

Test the PutTodoItem method

The DeleteTodoItem method

Test the DeleteTodoItem method

Test with other tools

Prevent over-posting

Call the web API with JavaScript

Web API video series

Reliable web app patterns

Add authentication support to a web API

Publish to Azure

Additional resources



# Create a web API with ASP.NET Core and MongoDB

Article • 04/25/2024

Prerequisites

Configure MongoDB

Create the ASP.NET Core web API project

Add an entity model

Add a configuration model

Add a CRUD operations service

Add a controller

Test the web API

Configure JSON serialization options

Add authentication support to a web API



# Tutorial: Call an ASP.NET Core web API with JavaScript

Article • 04/25/2024

Prerequisites

Call the web API with JavaScript

Get a list of to-do items

Add a to-do item

Update a to-do item

Delete a to-do item



# Create backend services for native mobile apps with ASP.NET Core

Article • 07/23/2024

The Sample Native Mobile App

Features

Creating the ASP.NET Core Project

Creating the Controller

Test the API using curl

Install curl and jq

Reading Items

Creating Items

Updating Items

Deleting Items

Prevent over-posting

Common Web API Conventions

Additional resources



# Publish an ASP.NET Core web API to Azure API Management with Visual Studio

Article • 06/18/2024

Set up

Create an ASP.NET Core web API

Explore the code

Ensure the Swagger definitions are always generated

Change the API routing

Publish the web API to Azure App Service

Publish the API app to Azure App Service

Configure the published API name

Verify the web API is working

Clean up

Additional resources



# Tutorial: Create a minimal API with ASP.NET Core

Article • 08/21/2024

Overview

Prerequisites

Create an API project

Examine the code

Run the app

Add NuGet packages

The model and database context classes

Add the API code

Test posting data

Examine the GET endpoints

Test the GET endpoints

Return values

Examine the PUT endpoint

Test the PUT endpoint

Examine and test the DELETE endpoint

Use the MapGroup API

Use the TypedResults API

Prevent over-posting

Troubleshooting with the completed sample

Next steps

Learn more



# Tutorial: Get started with ASP.NET Core SignalR

Article • 11/16/2023

Prerequisites

Create a web app project

Add the SignalR client library

Create a SignalR hub

Configure SignalR

Add SignalR client code

Run the app

Publish to Azure

Next steps




# Tutorial: Get started with ASP.NET Core SignalR using TypeScript and Webpack

Article • 11/16/2023

Prerequisites

Create the ASP.NET Core web app

Configure the server

Configure the client

Test the app

Next steps

Additional resources



# Use ASP.NET Core SignalR with Blazor

Article • 06/21/2024

Prerequisites

Sample app

Create a Blazor Web App

Add the SignalR client library

Add a SignalR hub

Add services and an endpoint for the SignalR hub

Add Razor component code for chat

Run the app

Next steps

Additional resources




# Tutorial: Create a gRPC client and server in ASP.NET Core

Article • 06/18/2024

Prerequisites

Create a gRPC service

Run the service

Examine the project files

Create the gRPC client in a .NET console app

Add required NuGet packages

PMC option to install packages

Manage NuGet Packages option to install packages

Add greet.proto

Create the Greeter client

Test the gRPC client with the gRPC Greeter service

Next steps




# Razor Pages with Entity Framework Core in ASP.NET Core - Tutorial 1 of 8

Article • 09/27/2024

Prerequisites

Database engines

Troubleshooting

The sample app

Optional: Build the sample download

Create the web app project

Set up the site style

The data model

The Student entity

The Enrollment entity

The Course entity

Scaffold Student pages

Database connection string

Update the database context class

Program.cs

Add the database exception filter

Create the database

Test the app

Seed the database

View the database

Asynchronous EF methods in ASP.NET Core web apps

Performance considerations

Next steps



# Part 2, Razor Pages with EF Core in ASP.NET Core - CRUD

Article • 07/26/2024

No repository

Update the Details page

Read enrollments

Display enrollments

Ways to read one entity

Route data vs. query string

Update the Create page

TryUpdateModelAsync

Overposting

View model

Update the Edit page

Entity States

Update the Delete page

Next steps



# Part 3, Razor Pages with EF Core in ASP.NET Core - Sort, Filter, Paging

Article • 04/10/2024

Add sorting

Add column heading hyperlinks to the Student Index page

Add filtering

Update the OnGetAsync method

IQueryable vs. IEnumerable

Update the Razor page

Add paging

Create the PaginatedList class

Add page size to configuration

Add paging to IndexModel

Add paging links

Grouping

Create the view model

Create the Razor Page

Create the page model

Next steps



# Part 4, Razor Pages with EF Core migrations in ASP.NET Core

Article • 05/31/2024

Drop the database

Create an initial migration

Remove EnsureCreated

Up and Down methods

The migrations history table

The data model snapshot

Applying migrations in production

Troubleshooting

Additional resources

Next steps



# Part 5, Razor Pages with EF Core in ASP.NET Core - Data Model

Article • 04/10/2024

The Student entity

The FullName calculated property

The DataType attribute

The DisplayFormat attribute

The StringLength attribute

The Column attribute

The Required attribute

The Display attribute

Create a migration

The Instructor Entity

Navigation properties

The OfficeAssignment entity

The Key attribute

The Instructor navigation property

The Course Entity

The DatabaseGenerated attribute

Foreign key and navigation properties

The Department entity

The Column attribute

Foreign key and navigation properties

The Enrollment foreign key and navigation properties

Many-to-Many Relationships

Update the database context

Fluent API alternative to attributes

Seed the database

Apply the migration or drop and re-create

Drop and re-create the database

Next steps



# Part 6, Razor Pages with EF Core in ASP.NET Core - Read Related Data

Article • 04/10/2024

Eager, explicit, and lazy loading

Create Course pages

Scaffold Course pages

Display the department name

Loading related data with Select

Create Instructor pages

Create a view model

Scaffold Instructor pages

Update the instructors Index page

Next steps



# Part 7, Razor Pages with EF Core in ASP.NET Core - Update Related Data

Article • 04/10/2024

Update the Course Create and Edit pages

Create a base class for Course Create and Edit

Update the Course Create page model

Update the Course Create Razor page

Update the Course Edit page model

Update the Course Edit Razor page

Update the Course page models

Update the Course Razor pages

Test the Course pages

Update the instructor Create and Edit pages

Create a class for assigned courses data

Create an Instructor page model base class

Handle office location

Update the Instructor Edit page model

Update the Instructor Edit Razor page

Update the Instructor Create page

Update the Instructor Delete page

Next steps



# Part 8, Razor Pages with EF Core in ASP.NET Core - Concurrency

Article • 04/10/2024

Concurrency conflicts

Pessimistic concurrency

Optimistic concurrency

Conflict detection in EF Core

Add a migration

Scaffold Department pages

Add a utility class

Update the Index page

Update the Edit page model

The concurrency updates

SQL Server vs SQLite code differences

Update the Edit Razor page

Test concurrency conflicts with the Edit page

Update the Delete page model

Update the Delete Razor page

Test concurrency conflicts

Additional resources

Next steps



# ASP.NET Core MVC with EF Core - tutorial series

Article • 04/10/2024

1. Get started

2. Create, Read, Update, and Delete operations

3. Sorting, filtering, paging, and grouping

4. Migrations

5. Create a complex data model

6. Reading related data

7. Updating related data

8. Handle concurrency conflicts

9. Inheritance

10. Advanced topics


# Tutorial: Get started with EF Core in an ASP.NET MVC web app

Article • 04/10/2024

Prerequisites

Database engines

Solve problems and troubleshoot

Contoso University web app

Create web app

Set up the site style

EF Core NuGet packages

Create the data model

The Student entity

The Enrollment entity

The Course entity

Create the database context

Register the SchoolContext

Add the database exception filter

SQL Server Express LocalDB

Initialize DB with test data

Create controller and views

View the database

Conventions

Asynchronous code

Limit entities fetched

SQL Logging of Entity Framework Core



# Tutorial: Implement CRUD Functionality - ASP.NET MVC with EF Core

Article • 04/10/2024

Prerequisites
 
Customize the Details page

Route data

Add enrollments to the Details view

Update the Create page

Security note about overposting

Test the Create page

Update the Edit page

Recommended HttpPost Edit code: Read and update

Alternative HttpPost Edit code: Create and attach

Entity States

Test the Edit page

Update the Delete page

The read-first approach to HttpPost Delete

The create-and-attach approach to HttpPost Delete

Update the Delete view

Close database connections

Handle transactions

No-tracking queries

Get the code

Next steps



# Tutorial: Add sorting, filtering, and paging - ASP.NET MVC with EF Core

Article • 04/10/2024

Prerequisites

Add column sort links

Add sorting Functionality to the Index method

Add column heading hyperlinks to the Student Index view

Add a Search box

Add filtering functionality to the Index method

Add a Search Box to the Student Index View

Add paging to Students Index

Add paging to Index method

Add paging links

Create an About page

Create the view model

Modify the Home Controller

Create the About View

Get the code

Next steps



# Tutorial: Part 5, apply migrations to the Contoso University sample

Article • 05/31/2024

Prerequisites

About migrations

Drop the database

Create an initial migration

Examine Up and Down methods

The data model snapshot

Apply the migration

Compare CLI and PMC

Get the code

Next step



# Tutorial: Create a complex data model - ASP.NET MVC with EF Core

Article • 04/10/2024

Prerequisites

Customize the Data model

The DataType attribute

The StringLength attribute

The Column attribute

Changes to Student entity

The Required attribute

The Display attribute

The FullName calculated property

Create Instructor entity

The CourseAssignments and OfficeAssignment navigation properties

Create OfficeAssignment entity

The Key attribute

The Instructor navigation property

Modify Course entity

The DatabaseGenerated attribute

Foreign key and navigation properties

Create Department entity

The Column attribute

Foreign key and navigation properties

Modify Enrollment entity

Foreign key and navigation properties

Many-to-Many relationships

The CourseAssignment entity

Join entity names

Composite key

Update the database context

About a fluent API alternative

Entity Diagram Showing Relationships

Seed database with test data

Add a migration

Change the connection string

Update the database

Get the code

Next steps



# Tutorial: Read related data - ASP.NET MVC with EF Core

Article • 04/10/2024

Prerequisites

Learn how to load related data

Performance considerations

Create a Courses page

Create an Instructors page

Create a view model for the Instructor Index view

Create the Instructor controller and views

Tracking vs no-tracking

Modify the Instructor Index view

About explicit loading

Get the code

Next steps



# Tutorial: Update related data - ASP.NET MVC with EF Core

Article • 04/10/2024

Prerequisites
 
Customize Courses pages

Add .AsNoTracking to Details and Delete methods

Modify the Course views

Test the Course pages
 
Add Instructors Edit page

Update the Instructors controller
 
Update the Instructor Edit view
 
Add courses to Edit page

Update the Instructors controller

Update the Instructor views

Update Delete page

Add office location and courses to Create page

Handling Transactions

Get the code

Next steps



# Tutorial: Handle concurrency - ASP.NET MVC with EF Core

Article • 07/09/2024

Prerequisites

Concurrency conflicts

Pessimistic concurrency (locking)

Optimistic Concurrency

Detecting concurrency conflicts

Add a tracking property

Create Departments controller and views
 
Update Index view

Update Edit methods

Update Edit view

Test concurrency conflicts

Update the Delete page

Update the Delete methods in the Departments controller

Update the Delete view

Update Details and Create views

Get the code

Additional resources

Next steps



# Tutorial: Implement inheritance - ASP.NET MVC with EF Core

Article • 04/10/2024

Prerequisites

Map inheritance to database

Create the Person class

Update Instructor and Student

Add Person to the model

Create and update migrations

Test the implementation

Get the code

Additional resources

Next steps



# Tutorial: Learn about advanced scenarios - ASP.NET MVC with EF Core

Article • 04/10/2024

Prerequisites

Perform raw SQL queries

Call a query to return entities

Call a query to return other types

Call an update query

Examine SQL queries

Create an abstraction layer

Automatic change detection

EF Core source code and development plans

Reverse engineer from existing database

Use dynamic LINQ to simplify code

Acknowledgments

Troubleshoot common errors

ContosoUniversity.dll used by another process

Migration scaffolded with no code in Up and Down methods

Errors while running database update

Error locating SQL Server instance

Get the code

Additional resources

Next steps



# ASP.NET Core fundamentals overview

Article • 11/14/2024

Program.cs

Dependency injection (services)

Middleware

Host

Non-web scenarios

Servers

Configuration

Environments

Logging

Routing

Error handling

Make HTTP requests

Content root

Web root

Additional resources



# App startup in ASP.NET Core

Article • 12/12/2024

Extend Startup with startup filters

Add configuration at startup from an external assembly

Startup, ConfigureServices, and Configure



# Dependency injection in ASP.NET Core

Article • 09/18/2024

Overview of dependency injection

Register groups of services with extension methods

Service lifetimes

Service registration methods

Keyed services

Keyed services in Middleware

Constructor injection behavior

Entity Framework contexts

Lifetime and registration options

Resolve a service at app start up

Scope validation

Request Services

Design services for dependency injection

Disposal of services

Services not created by the service container

IDisposable guidance for Transient and shared instances

Default service container replacement

Recommendations

Recommended patterns for multi-tenancy in DI

Framework-provided services

Additional resources



# ASP.NET Core support for Native AOT

Article • 09/18/2024

Why use Native AOT with ASP.NET Core

ASP.NET Core and Native AOT compatibility

Native AOT publishing

The Web API (Native AOT) template

Changes to support source generation

Changes to launchSettings.json

The CreateSlimBuilder method

CreateSlimBuilder vs CreateBuilder

Source generators

Libraries and Native AOT

Minimal APIs and JSON payloads

Known issues

See also



# Tutorial: Publish an ASP.NET Core app using Native AOT

Article • 07/26/2024

Prerequisites

Create a web app with Native AOT

Publish the Native AOT app

Libraries and Native AOT

See also



# Turn Map methods into request delegates with the ASP.NET Core Request Delegate Generator

Article • 07/26/2024

Diagnostics for unsupported RDG scenarios



# ASP.NET Core Request Delegate Generator (RDG) diagnostics

Article • 07/26/2024

RDG002: Unable to resolve endpoint handler

RDG004: Unable to resolve anonymous type

RDG005: Invalid abstract type

RDG006: Invalid constructor parameters

RDG007: No valid constructor found

RDG008: Multiple public constructors

RDG009: Invalid nested AsParameters

RDG010: InvalidAsParameters Nullable

RDG011: Type parameters not supported

RDG012: Unable to resolve inaccessible type

RDG013: Invalid source attributes



# RDG002: Unable to resolve endpoint handler

Article • 07/26/2024

Cause

Rule description

How to fix violations

When to suppress warnings



# RDG004: Unable to resolve anonymous type

Article • 07/26/2024

Cause

Rule description

How to fix violations

When to suppress warnings



# RDG005: Invalid abstract type

Article • 07/26/2024

Cause

Rule description

How to fix violations

When to suppress warnings



# RDG006: Invalid constructor parameters

Article • 07/26/2024

Cause

Rule description

How to fix violations

When to suppress warnings



# RDG007: No valid constructor found

Article • 07/26/2024

Cause

Rule description

How to fix violations

When to suppress warnings



# RDG008: Multiple public constructors

Article • 07/26/2024

Cause

Rule description

How to fix violations

When to suppress warnings





# RDG009: Invalid nested AsParameters

Article • 07/26/2024

Cause

Rule description

How to fix violations

When to suppress warnings



# RDG010: InvalidAsParameters Nullable

Article • 07/26/2024

Cause

Rule description

How to fix violations

When to suppress warnings



# RDG011: Type parameters not supported

Article • 07/26/2024

Cause

Rule description

How to fix violations

When to suppress warnings



# RDG012: Unable to resolve inaccessible type

Article • 07/26/2024

Cause

Rule description

How to fix violations

When to suppress warnings



# RDG013: Invalid source attributes

Article • 07/26/2024

Cause

Rule description

How to fix violations

When to suppress warnings



# ASP.NET Core Middleware

Article • 06/17/2024

Middleware code analysis

Create a middleware pipeline with WebApplication

Short-circuiting the request pipeline

Run delegates

Prefer app.Use overload that requires passing the context to next

Middleware order

UseCors and UseStaticFiles order

Forwarded Headers Middleware order

Branch the middleware pipeline

Built-in middleware

Additional resources



# Rate limiting middleware in ASP.NET Core

Article • 06/17/2024

Rate limiter algorithms

Fixed window limiter

Sliding window limiter

Token bucket limiter

Concurrency limiter

Create chained limiters

EnableRateLimiting and DisableRateLimiting attributes

Applying attributes to Razor Pages

Limiter algorithm comparison

Rate limiter samples

Limiter with OnRejected, RetryAfter, and GlobalLimiter

Limiter with authorization

Limiter with ConcurrencyLimiter, TokenBucketRateLimiter, and authorization

Testing endpoints with rate limiting

Additional resources



# Middleware in Minimal API apps

Article • 07/26/2024



# Test ASP.NET Core middleware

Article • 01/11/2024

Set up the TestServer

Send requests with HttpClient

Send requests with HttpContext

Add request routes

TestServer limitations

Content-Length and Transfer-Encoding headers



# Response Caching Middleware in ASP.NET Core

Article • 07/16/2024

Configuration

Options

VaryByQueryKeys

HTTP headers used by Response Caching Middleware

Caching respects request Cache-Control directives

Troubleshooting

Conditions for caching

Additional resources



# Write custom ASP.NET Core middleware

Article • 07/26/2024

Middleware class

Middleware dependencies

Per-request middleware dependencies

Additional resources



# Request and response operations in ASP.NET Core

Article • 07/26/2024

Stream examples

Pipelines

Adapters

StartAsync

Additional resources



# Request decompression in ASP.NET Core

Article • 09/27/2024

Configuration

Default decompression providers

Custom decompression providers

Request size limits

Additional Resources



# Factory-based middleware activation in ASP.NET Core

Article • 07/26/2024

IMiddleware

IMiddlewareFactory

Additional resources



# Middleware activation with a third-party container in ASP.NET Core

Article • 07/26/2024

IMiddlewareFactory

IMiddleware

Additional resources



# WebApplication and WebApplicationBuilder in Minimal API apps

Article • 07/26/2024

WebApplication

Working with ports

Multiple ports

Set the port from the command line

Read the port from environment

Set the ports via the ASPNETCORE_URLS environment variable

Listen on all interfaces

http://*:3000

http://+:3000

http://0.0.0.0:3000

Listen on all interfaces using ASPNETCORE_URLS

Listen on all interfaces using ASPNETCORE_HTTPS_PORTS

Specify HTTPS with development certificate

Specify HTTPS using a custom certificate

Specify the custom certificate with appsettings.json

Specify the custom certificate via configuration

Use the certificate APIs

Read the environment

Configuration

Logging

Access the Dependency Injection (DI) container

WebApplicationBuilder

Change the content root, application name, and environment

Change the content root, app name, and environment by using environment variables or command line

Add configuration providers

Read configuration

Read the environment

Add logging providers

Add services

Customize the IHostBuilder

Customize the IWebHostBuilder

Change the web root

Custom dependency injection (DI) container

Add Middleware

Developer exception page



# .NET Generic Host in ASP.NET Core

Article • 09/10/2024

Host definition

Set up a host

Default builder settings

Framework-provided services

IHostApplicationLifetime

IHostLifetime

IHostEnvironment

Host configuration

App configuration

Settings for all app types

ApplicationName

EnvironmentName

ShutdownTimeout

Disable app configuration reload on change

Settings for web apps

CaptureStartupErrors

DetailedErrors

HostingStartupAssemblies

HostingStartupExcludeAssemblies

HTTPS_Port

HTTPS_Ports

PreferHostingUrls

PreventHostingStartup

StartupAssembly

SuppressStatusMessages

URLs

WebRoot

Manage the host lifetime

Run

RunAsync

RunConsoleAsync

Start

StartAsync

StopAsync

WaitForShutdown

WaitForShutdownAsync

Additional resources



# ASP.NET Core Web Host

Article • 09/10/2024

Set up a host

Host configuration values

Application Key (Name)

Capture Startup Errors

Content root

Detailed Errors

Environment

Hosting Startup Assemblies

HTTPS Port

HTTPS Ports

Hosting Startup Exclude Assemblies

Prefer Hosting URLs

Prevent Hosting Startup

Server URLs

Shutdown Timeout

Startup Assembly

Web root

Override configuration

Manage the host

IWebHostEnvironment interface

IHostApplicationLifetime interface

Scope validation

Additional resources



# Configuration in ASP.NET Core

Article • 10/30/2024

Application and Host Configuration

Default application configuration sources

Default host configuration sources

Host variables

Application configuration providers

appsettings.json

Comments in appsettings.json

Bind hierarchical configuration data using the options pattern

Combining service collection

Security and user secrets

Non-prefixed environment variables

Naming of environment variables

Environment variables set in generated launchSettings.json

Escape environment variables on Linux

Display environment variables

Command-line

Command-line arguments

Switch mappings

Set environment and command-line arguments with Visual Studio

Hierarchical configuration data

Configuration keys and values

Configuration providers

Connection string prefixes

File configuration provider

INI configuration provider

JSON configuration provider

XML configuration provider

Key-per-file configuration provider

Memory configuration provider

Kestrel endpoint configuration

GetValue

GetSection, GetChildren, and Exists

GetSection

GetChildren and Exists

Bind an array

Custom configuration provider

Access configuration with Dependency Injection (DI)

Access configuration in Razor Pages

Access configuration in a MVC view file

Access configuration in Program.cs

Configure options with a delegate

Host versus app configuration

Default host configuration

Other configuration

Add configuration from an external assembly

Configuration-binding source generator

Additional resources



# Options pattern in ASP.NET Core

Article • 10/18/2024

Bind hierarchical configuration

The Options Pattern

Options interfaces

Use IOptionsSnapshot to read updated data

IOptionsMonitor

Named options support using IConfigureNamedOptions

OptionsBuilder API

Use DI services to configure options

Options validation

IValidateOptions<TOptions> and IValidatableObject

ValidateOnStart

Options post-configuration
 
Access options in Program.cs

Additional resources



# Use multiple environments in ASP.NET Core

Article • 09/18/2024

Environments

Create EnvironmentsSample

Set environment on the command line

Development and launchSettings.json

Production

Set the environment by setting an environment variable

Azure App Service

Windows - Set environment variable for a process

Windows - Set environment variable globally

Windows - Use web.config

Windows - IIS deployments

macOS

Linux

Set the environment in code

Configuration by environment

Configure services and middleware by environment

Additional resources



# Logging in .NET Core and ASP.NET Core

Article • 09/18/2024

Logging providers

Create logs

Configure logging

Log in Program.cs

Set log level by command line, environment variables, and other configuration

How filtering rules are applied

Logging output from dotnet run and Visual Studio

Log category

Log level

Log event ID

Log message template

Log exceptions

Default log level

Filter function

ASP.NET Core categories

Log scopes

Built-in logging providers

Console

Debug

Event Source

dotnet-trace tooling

Perfview

Windows EventLog

Azure App Service

Azure log streaming

Azure Application Insights

Third-party logging providers

No asynchronous logger methods

Change log levels in a running app

ILogger and ILoggerFactory

Apply log filter rules in code

Automatically log scope with SpanId, TraceId, ParentId, Baggage, and Tags .

Create a custom logger

Additional resources



# HTTP logging in ASP.NET Core

Article • 06/17/2024

Enable HTTP logging

HTTP logging options

LoggingFields

RequestHeaders and ResponseHeaders

MediaTypeOptions

MediaTypeOptions methods

RequestBodyLogLimit and ResponseBodyLogLimit

CombineLogs

Endpoint-specific configuration

IHttpLoggingInterceptor

Logging configuration order of precedence



# W3CLogger in ASP.NET Core

Article • 07/26/2024

Enable W3CLogger

W3CLogger options

LoggingFields



# Health checks in ASP.NET Core

Article • 07/23/2024

Basic health probe

Docker HEALTHCHECK

Create health checks

Register health check services

Use Health Checks Routing

Require host

Require authorization

Enable Cross-Origin Requests (CORS)

Health check options

Filter health checks

Customize the HTTP status code

Suppress cache headers

Customize output

Database probe

Entity Framework Core DbContext probe

Separate readiness and liveness probes

Kubernetes example

Distribute a health check library

Health Check Publisher

Individual Healthchecks

Dependency Injection and Health Checks

UseHealthChecks vs. MapHealthChecks

Additional resources



# ASP.NET Core metrics

Article • 11/14/2024

Using metrics

Create the starter app

View metrics with dotnet-counters

Enrich the ASP.NET Core request metric

Opt-out of HTTP metrics on certain endpoints and requests

Create custom metrics

Creating metrics in ASP.NET Core apps with IMeterFactory

View metrics in Grafana with OpenTelemetry and Prometheus

Overview

View metrics from sample app

Set up and configure Prometheus

Start Prometheus

Show metrics on a Grafana dashboard

Test metrics in ASP.NET Core apps

ASP.NET Core meters and counters



# ASP.NET Core metrics

Article • 02/05/2024

Microsoft.AspNetCore.Hosting

Metric: http.server.request.duration

Metric: http.server.active_requests

Microsoft.AspNetCore.Routing

Metric: aspnetcore.routing.match_attempts

Microsoft.AspNetCore.Diagnostics

Metric: aspnetcore.diagnostics.exceptions

Microsoft.AspNetCore.RateLimiting

Metric: aspnetcore.rate_limiting.active_request_leases

Metric: aspnetcore.rate_limiting.request_lease.duration

Metric: aspnetcore.rate_limiting.queued_requests

Metric: aspnetcore.rate_limiting.request.time_in_queue

Metric: aspnetcore.rate_limiting.requests

Microsoft.AspNetCore.HeaderParsing

Metric: aspnetcore.header_parsing.parse_errors

Metric: aspnetcore.header_parsing.cache_accesses

Microsoft.AspNetCore.Server.Kestrel

Metric: kestrel.active_connections

Metric: kestrel.connection.duration

Metric: kestrel.rejected_connections

Metric: kestrel.queued_connections

Metric: kestrel.queued_requests

Metric: kestrel.upgraded_connections

Metric: kestrel.tls_handshake.duration

Metric: kestrel.active_tls_handshakes

Microsoft.AspNetCore.Http.Connections

Metric: signalr.server.connection.duration

Metric: signalr.server.active_connections



# Use HttpContext in ASP.NET Core

Article • 10/30/2024

HttpRequest

Get request headers

Read request body

Enable request body buffering

BodyReader

HttpResponse

Set response headers

Write response body

BodyWriter

Set response trailers

RequestAborted

Abort()

User

Features

HttpContext isn't thread safe



# Routing in ASP.NET Core

Article • 09/18/2024

Routing basics

Endpoints

Endpoint metadata

Routing concepts

ASP.NET Core endpoint definition

Compare terminal middleware with routing

URL matching

Route template precedence and endpoint selection order

URL generation concepts

Middleware example

Route templates

Complex segments

Routing with special characters

Route constraints

Regular expressions in constraints

Custom route constraints

Parameter transformers

URL generation reference

Troubleshooting URL generation with logging

Addresses

Ambient values and explicit values

URL generation process

Optional route parameter order

Problems with route value invalidation

Parse URL paths with LinkParser

Configure endpoint metadata

Host matching in routes with RequireHost

Route groups

Performance guidance for routing

Potentially expensive routing features

Guidance for large route tables

How to determine if an app is running into the large route table problem

How to address this issue

Short-circuit middleware after routing

Guidance for library authors

Define endpoints

Creating routing-integrated middleware

Debug diagnostics

Additional resources



# Handle errors in ASP.NET Core

Article • 09/21/2024

Developer exception page

Exception handler page

Access the exception

Exception handler lambda

IExceptionHandler

UseStatusCodePages

UseStatusCodePages with format string

UseStatusCodePages with lambda

UseStatusCodePagesWithRedirects

UseStatusCodePagesWithReExecute

Disable status code pages

Exception-handling code

Response headers

Server exception handling

Startup exception handling

Database error page

Exception filters

Model state errors

Problem details

Customize problem details

CustomizeProblemDetails operation

Custom IProblemDetailsWriter

Problem details from Middleware

Produce a ProblemDetails payload for exceptions

Additional resources



# 