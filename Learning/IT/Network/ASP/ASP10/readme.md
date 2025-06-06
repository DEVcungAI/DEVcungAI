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



# Make HTTP requests using IHttpClientFactory in ASP.NET Core

Article • 07/26/2024


Consumption patterns

Basic usage

Named clients

CreateClient

Typed clients

Generated clients

Make POST, PUT, and DELETE requests

Outgoing request middleware

Use DI in outgoing request middleware

Use Polly-based handlers

Handle transient faults

Dynamically select policies

Add multiple Polly handlers

Add policies from the Polly registry

HttpClient and lifetime management

Alternatives to IHttpClientFactory

Logging

Configure the HttpMessageHandler

Cookies

Use IHttpClientFactory in a console app

Header propagation middleware

Additional resources



# Static files in ASP.NET Core

Article • 11/05/2024


Serve static files

MapStaticAssets

Serve files in web root

Serve files outside of web root

Set HTTP response headers

Static file authorization

Directory browsing

Serve default documents

UseFileServer for default documents

FileExtensionContentTypeProvider

Non-standard content types

Serve files from multiple locations

Security considerations for static files

Serve files outside wwwroot by updating IWebHostEnvironment.WebRootPath

Additional resources



# dotnet-scaffold telemetry

Article • 11/11/2024


How to opt out

Disclosure

Data points

Additional resources



# Choose an ASP.NET Core web UI

Article • 10/21/2024


ASP.NET Core Blazor

ASP.NET Core Razor Pages

ASP.NET Core MVC

ASP.NET Core Single Page Applications (SPA) with frontend JavaScript frameworks

Combine multiple web UI solutions: ASP.NET Core MVC or Razor Pages plus Blazor

Next steps



# Introduction to Razor Pages in ASP.NET Core

Article • 09/27/2024


Prerequisites

Create a Razor Pages project

Razor Pages

Write a basic form

The home page

The Edit.cshtml file

Validation

CSS isolation

CSS preprocessor support

CSS isolation configuration

Customize scope identifier format

Change base path for static web assets

Disable automatic bundling

Razor class library (RCL) support

Handle HEAD requests with an OnGet handler fallback

XSRF/CSRF and Razor Pages

Using Layouts, partials, templates, and Tag Helpers with Razor Pages

URL generation for Pages

ViewData attribute

TempData

Multiple handlers per page

Custom routes

Collocation of JavaScript (JS) files

Advanced configuration and settings

Specify that Razor Pages are at the content root

Specify that Razor Pages are at a custom root directory

Additional resources



# Tutorial: Create a Razor Pages web app with ASP.NET Core

Article • 07/01/2024


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

appsettings.json

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


SQL Server Express LocalDB

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



# Filter methods for Razor Pages in ASP.NET Core

Article • 04/10/2024


Implement Razor Page filters globally

Implement Razor Page filters by overriding filter methods

Implement a filter attribute

Authorize filter attribute



# Razor Pages route and app conventions in ASP.NET Core

Article • 04/10/2024


Route order

Model conventions

Add a route model convention to all pages

Add an app model convention to all pages

Add a handler model convention to all pages

Page route action conventions

Folder route model convention

Page route model convention

Use a parameter transformer to customize page routes

Configure a page route

Page model action conventions

Folder app model convention

Page app model convention

Configure a filter

Configure a filter factory

MVC Filters and the Page filter (IPageFilter)

Additional resources



# Overview of ASP.NET Core MVC

Article • 06/17/2024


MVC pattern

Model Responsibilities

View Responsibilities

Controller Responsibilities

ASP.NET Core MVC

Routing

Model binding

Model validation

Dependency injection

Filters

Areas

Web APIs

Testability

Razor view engine

Strongly typed views

Tag Helpers

View Components

Compatibility version

Additional resources



# Get started with ASP.NET Core MVC

Article • 07/30/2024


Prerequisites

Create a web app

Run the app

Visual Studio help



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



# Views in ASP.NET Core MVC

Article • 06/17/2024


Benefits of using views

Creating a view

How controllers specify views

View discovery

Pass data to views

Strongly-typed data (viewmodel)

Weakly typed data (ViewData, [ViewData] attribute, and ViewBag)

ViewData

[ViewData] attribute

ViewBag

Using ViewData and ViewBag simultaneously

Summary of the differences between ViewData and ViewBag

When to use ViewData or ViewBag

Dynamic views

More view features

CSS isolation

CSS preprocessor support

CSS isolation configuration

Customize scope identifier format

Change base path for static web assets

Disable automatic bundling

Razor class library (RCL) support



# Partial views in ASP.NET Core

Article • 05/17/2023


When to use partial views

Declare partial views

Reference a partial view

Use a partial view in a Razor Pages PageModel

Use a partial view in a markup file

Partial Tag Helper

Razor Pages

MVC

Asynchronous HTML Helper

Synchronous HTML Helper

Partial view discovery

Razor Pages

MVC

Access data from partial views

Razor Pages

MVC

Additional resources



# Handle requests with controllers in ASP.NET Core MVC

Article • 06/17/2024


What is a Controller?

Defining Actions

Controller Helper Methods

1. Methods resulting in an empty response body

2. Methods resulting in a non-empty response body with a predefined content type

3. Methods resulting in a non-empty response body formatted in a content type negotiated with the client

Cross-Cutting Concerns



# Routing to controller actions in ASP.NET Core

Article • 06/17/2024


Set up conventional route

Conventional routing

Multiple conventional routes

Conventional routing order

Resolving ambiguous actions

Conventional route names

Attribute routing for REST APIs

Reserved routing names

HTTP verb templates

Route templates

Attribute routing with Http verb attributes

Route name

Combining attribute routes

Attribute route order

Token replacement in route templates [controller], [action], [area]

Use a parameter transformer to customize token replacement

Multiple attribute routes

Specifying attribute route optional parameters, default values, and constraints

Custom route attributes using IRouteTemplateProvider

Use application model to customize attribute routes

Mixed routing: Attribute routing vs conventional routing

Routing with special characters

URL Generation and ambient values

Generating URLs by action name

Generate URLs by route

Generate URLs in HTML and Razor

URL generation in Action Results

Special case for dedicated conventional routes

Areas

Action definition

Sample code

Debug diagnostics



# Dependency injection into controllers in ASP.NET Core

Article • 06/17/2024


Constructor injection

Action injection with FromServices

Action injection with FromKeyedServices

Access settings from a controller

Additional resources



# Dependency injection into views in ASP.NET Core

Article • 06/17/2024


Configuration injection

Service injection

Populating Lookup Data

Overriding Services

See Also



# Unit test controller logic in ASP.NET Core

Article • 06/17/2024


Unit testing controllers

Test ActionResult<T>

Additional resources



# ASP.NET Core Blazor

Article • 09/16/2024


Components

Build a full-stack web app with Blazor

Build a native client app with Blazor Hybrid

Next steps



# ASP.NET Core Blazor supported platforms

Article • 07/01/2024


Additional resources



# Tooling for ASP.NET Core Blazor

Article • 09/12/2024


Run the app

Stop the app

Visual Studio solution file ( .sln )

Blazor project templates and template options

Interactive render mode

Interactivity location

Sample pages

Additional guidance on template options

Additional resources



# ASP.NET Core Blazor WebAssembly build tools and ahead-of-time (AOT) compilation

Article • 09/27/2024


.NET WebAssembly build tools

Ahead-of-time (AOT) compilation

Trim .NET IL after ahead-of-time (AOT) compilation

Heap size for some mobile device browsers

Runtime relinking

Single Instruction, Multiple Data (SIMD)

Exception handling

Additional resources



# ASP.NET Core Blazor hosting models

Article • 09/10/2024


Blazor Server

Blazor WebAssembly

Blazor Hybrid

Which Blazor hosting model should I choose?

Complete .NET API compatibility

Direct access to server and network resources

Small payload size with fast initial load time

Near native execution speed

App code secure and private on the server

Run apps offline once downloaded

Static site hosting

Offloads processing to clients

Full access to native client capabilities

Web-based deployment

Setting a component's hosting model



# ASP.NET Core Blazor tutorials

Article • 11/18/2024



# Build a Blazor todo list app

Article • 10/29/2024


Prerequisites

Create a Blazor app

Build a todo list Blazor app

Publish to Azure

Next steps



# Build a Blazor movie database app (Overview)

Article • 11/15/2024


Secure authentication flow required for production apps

Sample app

Article code examples

Report a tutorial issue

Support requests

Next steps



# Build a Blazor movie database app (Part 1 - Create a Blazor Web App)

Article • 11/15/2024


Prerequisites

Create a Blazor Web App

Run the app

Stop the app

Examine the project files

Properties folder

wwwroot folder

Components , Components/Pages , and Components/Layout folders

Components/_Imports.razor file

Components/App.razor file

Components/Routes.razor file

appsettings.json file

Program.cs file

Troubleshoot with the completed sample

Additional resources

Next steps



# Build a Blazor movie database app (Part 2 - Add and scaffold a model)

Article • 10/08/2024


Add a data model

Scaffold the model

Files created and updated by scaffolding

Create the initial database schema using EF Core's migration feature

Test the app

Stop the app

Troubleshoot with the completed sample

Additional resources

Legal

Next steps



# Build a Blazor movie database app (Part 3 - Learn about Razor components)

Article • 09/12/2024


Razor components

NavMenu component for navigation

MainLayout component for layout

Create, Read, Update, Delete (CRUD) components

Index component

Details component

Create component

Delete component

Edit component

Mitigate overposting attacks

Troubleshoot with the completed sample

Additional resources

Next steps



# Build a Blazor movie database app (Part 4 - Work with a database)

Article • 10/21/2024


Secure authentication flow required for production apps

Database context

Database technology

Seed the database

Bind a form to a model

Concurrency exception handling

Stop the app

Troubleshoot with the completed sample

Additional resources

Legal

Next steps



# Build a Blazor movie database app (Part 5 - Add validation)

Article • 11/14/2024


Validation using data annotations

Add validation to the Movie model

Create an EF Core migration and update the database

Troubleshoot with the completed sample

Additional resources

Next steps



# Build a Blazor movie database app (Part 6 - Add search)

Article • 11/14/2024


Implement a filter feature for the QuickGrid component

Stop the app

Troubleshoot with the completed sample

Additional resources

Legal

Next steps



# Build a Blazor movie database app (Part 7 - Add a new field)

Article • 09/23/2024


Add a movie rating to the app's model

Add the movie rating to the app's CRUD components

Update the database

Troubleshoot

Delete all database records and reseed the database

Troubleshoot with the completed sample

Additional resources

Legal

Next steps



# Build a Blazor movie database app (Part 8 - Add interactivity)

Article • 12/05/2024


Adopt interactivity

Add pagination to the QuickGrid

Sortable QuickGrid

Use C# code and interactivity to search by title

Style the QuickGrid component

Clean up

Congratulations!

Next steps

Troubleshoot with the completed sample



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



# ASP.NET Core Blazor Hybrid

Article • 12/11/2024


Blazor Hybrid apps with .NET MAUI

Blazor Hybrid apps with WPF and Windows Forms

Web View configuration

Unhandled exceptions in Windows Forms and WPF apps

Globalization and localization

Access scoped services from native UI

Additional resources



# ASP.NET Core Blazor Hybrid tutorials

Article • 11/18/2024


Build a .NET MAUI Blazor Hybrid app

Build a .NET MAUI Blazor Hybrid app with a Blazor Web App

Build a Windows Forms Blazor app

Build a Windows Presentation Foundation (WPF) Blazor app



# Build a .NET MAUI Blazor Hybrid app

Article • 02/13/2024


Prerequisites

Create a .NET MAUI Blazor Hybrid app

Run the app on Windows

Run the app in the Android Emulator

Next steps



# Build a .NET MAUI Blazor Hybrid app with a Blazor Web App

Article • 10/18/2024


Prerequisites and preliminary steps

.NET MAUI Blazor Hybrid and Web App solution template

Use Blazor render modes

Global Server interactivity

Global Auto or WebAssembly interactivity

Per-page/component Server interactivity

Per-page/component Auto interactivity

Per-page/component WebAssembly interactivity

Using interfaces to support different device implementations

Additional resources



# Build a Windows Forms Blazor app

Article • 09/12/2024


Prerequisites

Visual Studio workload

Create a Windows Forms Blazor project

Run the app

Next steps



# Build a Windows Presentation Foundation (WPF) Blazor app

Article • 03/08/2024


Prerequisites

Visual Studio workload

Create a WPF Blazor project

Run the app

Next steps



# ASP.NET Core Blazor Hybrid routing and navigation

Article • 09/12/2024


URI request routing behavior

Get or set a path for initial navigation

Navigation among pages and Razor components

App linking (deep linking)



# ASP.NET Core Blazor Hybrid static files

Article • 09/12/2024


.NET MAUI

WPF

Windows Forms

Static assets limited to Razor components

Trademarks

Additional resources



# Use browser developer tools with ASP.NET Core Blazor Hybrid

Article • 02/09/2024


Browser developer tools with .NET MAUI Blazor

Additional resources



# Reuse Razor components in ASP.NET Core Blazor Hybrid

Article • 12/05/2024


Design principles

Project code organization

Use abstractions for unique features

.NET MAUI Blazor platform-specific code

Additional resources



# Share assets across web and native clients using a Razor class library (RCL)

Article • 09/12/2024


Share web UI Razor components, code, and static assets

Provide code and services independent of hosting model

Additional resources



# Pass root component parameters in ASP.NET Core Blazor Hybrid

Article • 02/09/2024


Additional resources



# ASP.NET Core Blazor Hybrid authentication and authorization

Article • 08/09/2024


Create a custom AuthenticationStateProvider without user change updates

Create a custom AuthenticationStateProvider with user change updates

Signal an authentication update from outside of the BlazorWebView (Option 1)

Handle authentication within the BlazorWebView (Option 2)

Accessing other authentication information

Other authentication security considerations

Additional resources



# ASP.NET Core Blazor Hybrid security considerations

Article • 09/27/2024


External content rendered in an iframe

Links to external URLs

Keep the Web View current in deployed apps

Android

iOS/Mac Catalyst

Windows (.NET MAUI, WPF, Windows Forms)

Additional resources



# Publish ASP.NET Core Blazor Hybrid apps

Article • 02/09/2024


Publish for a specific framework

Blazor-specific considerations



# Troubleshoot ASP.NET Core Blazor Hybrid

Article • 11/14/2024


Enable BlazorWebView logging

Configure logging providers

View logger output

Additional resources



# ASP.NET Core Blazor project structure

Article • 09/12/2024


Blazor Web App

Standalone Blazor WebAssembly

Location of the Blazor script

Location of <head> and <body> content

Additional resources



# ASP.NET Core Blazor fundamentals

Article • 11/19/2024


Static and interactive rendering concepts

Client and server rendering concepts

Razor components

Render modes

Document Object Model (DOM)

Subset of .NET APIs for Blazor WebAssembly apps

Sample apps

Byte multiples

Support requests

Community links to Blazor resources



# ASP.NET Core Blazor routing and navigation

Article • 10/21/2024


Static versus interactive routing

Route templates

Focus an element on navigation

Provide custom content when content isn't found

Route to components from multiple assemblies

Static routing

Interactive routing

Route parameters

Route constraints

Avoid file capture in a route parameter

Catch-all route parameters

URI and navigation state helpers

Location changes

Enhanced navigation and form handling

Produce a URI relative to the base URI prefix

Navigation history state

Navigation options

Query strings

Replace a query parameter value when the parameter exists

Append a query parameter and value when the parameter doesn't exist

Remove a query parameter when the parameter value is null

Add, update, and remove query parameters

Support for enumerable values

Navigate with an added or modified query string

Hashed routing to named elements

User interaction with <Navigating> content

Handle asynchronous navigation events with OnNavigateAsync

Handle cancellations in OnNavigateAsync

Handle/prevent location changes

NavLink component

ASP.NET Core endpoint routing integration



# ASP.NET Core Blazor configuration

Article • 10/18/2024


App settings configuration

Memory Configuration Source

Authentication configuration

Logging configuration

Host builder configuration

Cached configuration

Options configuration



# ASP.NET Core Blazor dependency injection

Article • 10/04/2024


Default services

Add client-side services

Add server-side services

Register common services

Client-side services that fail during prerendering

Service lifetime

Request a service in a component

Constructor injection

Property injection

Use DI in services

Inject keyed services into components

Utility base component classes to manage a DI scope

OwningComponentBase

OwningComponentBase<TService>

Detect client-side transient disposables

Detect server-side transient disposables

Transient service registrations for IHttpClientFactory / HttpClient handlers

Use of an Entity Framework Core (EF Core) DbContext from DI

Access server-side Blazor services from a different DI scope

Additional resources



# ASP.NET Core Blazor startup

Article • 09/27/2024


Startup process and configuration

JavaScript initializers

Ensure libraries are loaded in a specific order

Import additional modules

Import map

Initialize Blazor when the document is ready

Chain to the Promise that results from a manual start

Load client-side boot resources

Control headers in C# code

Server-side and prerendered client-side scenarios

Client-side loading progress indicators

Blazor Web App loading progress

Blazor WebAssembly app loading progress

Configure the .NET WebAssembly runtime

Disable enhanced navigation and form handling

Additional resources



# ASP.NET Core Blazor environments

Article • 09/16/2024


Set the environment

Set the client-side environment via Blazor startup configuration

Set the client-side environment via header

Set the environment for Azure App Service

Read the environment in a Blazor WebAssembly app

Read the environment client-side in a Blazor Web App

Read the client-side environment during startup

Additional resources



# ASP.NET Core Blazor logging

Article • 10/18/2024


Configuration

Log levels

Razor component logging

Server-side logging

Client-side logging

Log in the client-side Program file

Client-side log category

Client-side log event ID

Client-side log message template

Client-side log exception parameters

Client-side filter function

Client-side custom logger provider

Client-side log scopes

Prerendered component logging

SignalR client logging with the SignalR client builder

SignalR client logging with app configuration

Client-side authentication logging

Additional resources



# Handle errors in ASP.NET Core Blazor apps

Article • 10/18/2024


Detailed errors during development

Detailed circuit errors

Detailed errors for Razor component server-side rendering

Manage unhandled exceptions in developer code

Unhandled exceptions for circuits

Global exception handling

Error boundaries

Alternative global exception handling

Log errors with a persistent provider

Places where errors may occur

Component instantiation

Lifecycle methods

Rendering logic

Event handlers

Component disposal

JavaScript interop

Prerendering

Advanced scenarios

Recursive rendering

Custom render tree logic

Additional resources



# ASP.NET Core Blazor SignalR guidance

Article • 09/27/2024


Azure SignalR Service with stateful reconnect

WebSocket compression for Interactive Server components

Disable response compression for Hot Reload

Client-side SignalR cross-origin negotiation for authentication

Client-side rendering

Prerendered state size and SignalR message size limit

Additional client-side resources

Use session affinity (sticky sessions) for server-side webfarm hosting

Azure SignalR Service

Server-side circuit handler options

Blazor hub options

Maximum receive message size

Blazor server-side Hub endpoint route configuration

Reflect the server-side connection state in the UI

Server-side rendering

Monitor server-side circuit activity

Blazor startup

Configure SignalR timeouts and Keep-Alive on the client

Modify the server-side reconnection handler

Automatically refresh the page when server-side reconnection fails

Adjust the server-side reconnection retry count and interval

Control when the reconnection UI appears

Server configuration

Client configuration

Disconnect the Blazor circuit from the client

Server-side circuit handler

Server-side circuit handler to capture users for custom services

Closure of circuits when there are no remaining Interactive Server components

IHttpContextAccessor / HttpContext in Razor components

Additional server-side resources



# ASP.NET Core Blazor static files

Article • 11/05/2024


Static asset delivery in server-side Blazor apps

Deliver assets with Map Static Assets routing endpoint conventions

Import maps

Summary of static file <link> href formats

.NET 9 or later

.NET 8.x

.NET 7.x or earlier

Static Web Asset Project Mode

Static files in non- Development environments

Prefix for Blazor WebAssembly assets

Static web asset base path

File mappings and static file options

Serve files from multiple locations

Additional resources



# ASP.NET Core Razor components

Article • 10/18/2024


Razor components

Component classes

Razor syntax

Component name, class name, and namespace

Partial class support

Specify a base class

Routing

Markup

Asynchronous methods ( async ) don't support returning void

Nested components

Component parameters

Route parameters

Child content render fragments

Render fragments for reusable rendering logic

Loop variables with component parameters and child content

Capture references to components

Apply an attribute

Conditional HTML element attributes and DOM properties

Raw HTML

Razor templates

Static assets

Tag Helpers aren't supported in components

Scalable Vector Graphics (SVG) images

Whitespace rendering behavior

Root component



# ASP.NET Core Blazor render modes

Article • 11/06/2024


Render modes

Enable support for interactive render modes

Apply a render mode to a component instance

Apply a render mode to a component definition

Apply a render mode to the entire app

Apply a render mode programatically

Set the render mode by component definition

Set the render mode by component instance

Detect rendering location, interactivity, and assigned render mode at runtime

Blazor documentation examples for Blazor Web Apps

Prerendering

Static server-side rendering (static SSR)

Interactive server-side rendering (interactive SSR)

Client-side rendering (CSR)

Automatic (Auto) rendering

Render mode propagation

Render mode inheritance

Child components with different render modes

Child component with a serializable parameter

Child component with a different render mode than its parent

Static SSR pages in a globally-interactive app

Client-side services fail to resolve during prerendering

Discover components from additional assemblies

Closure of circuits when there are no remaining Interactive Server components

Custom shorthand render modes

Service injection via a top-level imports file ( _Imports.razor )

Additional resources



# Prerender ASP.NET Core Razor components

Article • 11/14/2024


Persist prerendered state

Components embedded into pages and views (Razor Pages/MVC)

Interactive routing and prerendering

Prerendering guidance



# ASP.NET Core Razor component generic type support

Article • 10/18/2024


Generic type parameter support

Cascaded generic type support

Explicit generic types based on ancestor components

Infer generic types based on ancestor components



# ASP.NET Core Blazor synchronization context

Article • 10/18/2024


Avoid thread-blocking calls

Invoke component methods externally to update state

Handle caught exceptions outside of a Razor component's lifecycle



# Retain element, component, and model relationships in ASP.NET Core Blazor

Article • 10/18/2024


Use of the @key directive attribute

When to use @key

Scope of @key

When not to use @key

Values to use for @key



# Avoid overwriting parameters in ASP.NET Core Blazor

Article • 12/13/2024


Overwritten parameters



# ASP.NET Core Blazor attribute splatting and arbitrary parameters

Article • 10/18/2024


Attribute splatting

Arbitrary attributes



# ASP.NET Core Blazor layouts

Article • 11/06/2024


Usefulness of Blazor layouts

Layout components

Create a layout component

MainLayout component

Apply a layout

Make the layout namespace available

Apply a layout to a component

Apply a layout to a folder of components

Apply a default layout to an app

Apply a layout to arbitrary content (LayoutView component)

Nested layouts

Share a Razor Pages layout with integrated components

Sections

Additional resources



# ASP.NET Core Blazor sections

Article • 11/14/2024


Blazor sections

Section interaction with other Blazor features



# Control <head> content in ASP.NET Core Blazor apps

Article • 10/18/2024


Control <head> content in a Razor component

Set a page title for components via a layout

HeadOutlet component

Set a default page title in a Blazor Web App

Not found page title in a Blazor WebAssembly app

Additional resources



# ASP.NET Core Blazor cascading values and parameters

Article • 10/18/2024


Root-level cascading values

CascadingValue component

[CascadingParameter] attribute

Cascading values/parameters and render mode boundaries

Cascade multiple values

Pass data across a component hierarchy

Additional resources



# ASP.NET Core Blazor event handling

Article • 10/18/2024


Delegate event handlers

Built-in event arguments

Custom event arguments

General configuration

Custom clipboard paste event example

Lambda expressions

EventCallback

Prevent default actions

Stop event propagation

Focus an element



# ASP.NET Core Blazor data binding

Article • 10/18/2024


Binding features

Use @bind:get / @bind:set modifiers and avoid event handlers for two-way data binding

Binding to a property with C# get and set accessors

Multiple option selection with <select> elements

Binding <select> element options to C# object null values

Unparsable values

Format strings

Binding with component parameters

Bind across more than two components

Bound field or property expression tree

Additional resources



# ASP.NET Core Razor component lifecycle

Article • 12/06/2024


Lifecycle events

Quiescence during prerendering

When parameters are set (SetParametersAsync)

Component initialization (OnInitialized{Async})

After parameters are set (OnParametersSet{Async})

After component render (OnAfterRender{Async})

Base class lifecycle methods

State changes (StateHasChanged)

Handle incomplete asynchronous actions at render

Handle errors

Stateful reconnection after prerendering

Prerendering with JavaScript interop

Component disposal with IDisposable and IAsyncDisposable

Disposal of JavaScript interop object references

DOM cleanup tasks during component disposal

Synchronous IDisposable

Asynchronous IAsyncDisposable

Assignment of null to disposed objects

StateHasChanged

Event handlers

Anonymous functions, methods, and expressions

Disposal during JS interop

Cancelable background work

Blazor Server reconnection events

Additional resources



# ASP.NET Core Razor component virtualization

Article • 10/18/2024


Virtualization

Item provider delegate

Placeholder

Empty content

Item size

Overscan count

State changes

Keyboard scroll support

Advanced styles and scroll detection

Root-level virtualization

Control the spacer element tag name



# ASP.NET Core Razor component rendering

Article • 10/18/2024


Rendering conventions for ComponentBase

Control the rendering flow

Streaming rendering

Suppress UI refreshing (ShouldRender)

StateHasChanged

An asynchronous handler involves multiple asynchronous phases

Receiving a call from something external to the Blazor rendering and event handling system

To render a component outside the subtree that's rerendered by a particular event

WebAssembly loading progress indicator for Blazor Web Apps



# ASP.NET Core Blazor templated components

Article • 10/18/2024


Templated components

Preserve relationships with @key

Additional resources



# ASP.NET Core Blazor CSS isolation

Article • 09/12/2024


Enable CSS isolation

CSS isolation bundling

Child component support

CSS preprocessor support

CSS isolation configuration

Customize scope identifier format

Change base path for static web assets

Disable automatic bundling

Disable CSS isolation

Razor class library (RCL) support

Additional resources



# Dynamically-rendered ASP.NET Core Razor components

Article • 11/06/2024


Dynamic components

Example

Pass parameters

Event callbacks (EventCallback)

Avoid catch-all parameters

Access the dynamically-created component instance

Trademarks

Additional resources



# ASP.NET Core Blazor QuickGrid component

Article • 12/05/2024


Package

Sample app

QuickGrid implementation

Sort by column

Page items with a Paginator component

Apply row styles

Custom attributes and styles

Entity Framework Core (EF Core) data source

Display name support

Remote data

QuickGrid scaffolder



# Integrate ASP.NET Core Razor components with MVC or Razor Pages

Article • 11/18/2024


Configuration

Use routable components in a Razor Pages app

Use routable components in an MVC app

Render components from a page or view

Render stateful interactive components

Render noninteractive components

Component namespaces

Persist prerendered state

Prerendered state size and SignalR message size limit

Additional Blazor Server resources



# Consume ASP.NET Core Razor components from a Razor class library (RCL)

Article • 09/12/2024


Create an RCL

Consume a Razor component from an RCL

Make routable components available from the RCL

Create an RCL with static assets in the wwwroot folder

Create an RCL with JavaScript files collocated with components

Client-side browser compatibility analyzer

JavaScript isolation in JavaScript modules

Avoid trimming JavaScript-invokable .NET methods

Build, pack, and ship to NuGet dotnet pack

Trademarks

Additional resources



# ASP.NET Core Razor class libraries (RCLs) with static server-side rendering (static SSR)

Article • 09/27/2024


Understand the capabilities and restrictions of static SSR

Options for component authors

When to use the @rendermode directive

Streaming rendering

Using links across render modes

Using forms across render modes

Avoid APIs that are specific to static SSR



# Use Razor components in JavaScript apps and SPA frameworks

Article • 11/06/2024


Angular sample apps

Render Razor components from JavaScript

Blazor custom elements

Element name

Package

Example component

Blazor Server registration

Blazor WebAssembly registration

Use the registered custom element

Pass parameters

Generate Angular and React components



# Render Razor components outside of ASP.NET Core

Article • 11/14/2024



# ASP.NET Core built-in Razor components

Article • 11/11/2024


AntiforgeryToken

AuthorizeView

CascadingValue

DataAnnotationsValidator

DynamicComponent

Editor<T>

EditForm

ErrorBoundary

FocusOnNavigate

HeadContent

HeadOutlet

ImportMap

InputCheckbox

InputDate

InputFile

InputNumber

InputRadio

InputRadioGroup

InputSelect

InputText

InputTextArea

LayoutComponentBase

LayoutView

NavigationLock

NavLink

PageTitle

OwningComponentBase

Paginator

QuickGrid

Router

RouteView

SectionContent

SectionOutlet

ValidationMessage

ValidationSummary

Virtualize



# ASP.NET Core Blazor globalization and localization

Article • 10/14/2024


Globalization and localization

Globalization

.NET globalization and International Components for Unicode (ICU) support (Blazor WebAssembly)

Invariant globalization

Timezone information

Demonstration component

Dynamically set the culture from the Accept-Language header

Statically set the client-side culture

Statically set the server-side culture

Dynamically set the client-side culture by user preference

Dynamically set the server-side culture by user preference

Dynamically set the culture in a Blazor Web App by user preference

Updates to the .Client project

Server project updates

Interactive Auto components

Localization

Client-side localization

Server-side localization

Example of localized resources

WebAssembly culture provider reference source

Shared resources

Location override using "Sensors" pane in developer tools

Additional resources



# ASP.NET Core Blazor forms overview

Article • 10/21/2024


Input components and forms

Handle form submission

Clear a form or field

Antiforgery support

Mitigate overposting attacks

Enhanced form handling

Examples

Client-side validation requires a circuit

Unsupported validation features

Additional resources



# ASP.NET Core Blazor input components

Article • 10/18/2024


Input components

Example form

Multiple option selection with the InputSelect component

Binding InputSelect options to C# object null values

Display name support

Error message template support



# ASP.NET Core Blazor forms binding

Article • 10/18/2024


EditForm / EditContext model

Model binding

Context binding

Supported types

Additional binding options

Form names

Supply a parameter from the form ([SupplyParameterFromForm])

Nest and bind forms

Initialize form data with static SSR

Advanced form mapping error scenarios

Custom input components

Input component based on InputBase<T>

Input component with full developer control

Radio buttons



# ASP.NET Core Blazor forms validation

Article • 10/18/2024


Form validation

Data Annotations Validator component and custom validation

Validator components

Business logic validation with a validator component

Server validation with a validator component

InputText based on the input event

Validation Summary and Validation Message components

Determine if a form field is valid

Custom validation attributes

Custom validation CSS class attributes

Class-level validation with IValidatableObject

Blazor data annotations validation package

Nested models, collection types, and complex types

Enable the submit button based on form validation



# Troubleshoot ASP.NET Core Blazor forms

Article • 04/11/2024


Large form payloads and the SignalR message size limit

EditForm parameter error

Connection disconnected



# ASP.NET Core Blazor file uploads

Article • 10/04/2024


File uploads

File size read and upload limits

Examples

Server-side file upload example

Client-side file upload example

Upload files to a server with server-side rendering

Upload files to a server with client-side rendering (CSR)

Cancel a file upload

Upload files server-side with progress

File streams

Upload image preview

Upload files to an external service

Server-side SignalR message size limit

Maximum parallel invocations per client hub setting

Troubleshoot

Additional resources



# ASP.NET Core Blazor file downloads

Article • 11/06/2024


File downloads

Security considerations

Download from a stream

Download from a URL

Cross-Origin Resource Sharing (CORS)

Additional resources



# ASP.NET Core Blazor JavaScript interoperability (JS interop)

Article • 11/19/2024


Compression for interactive server components with untrusted data

JavaScript interop abstractions and features package

Interaction with the DOM

JavaScript class with a field of type function

Avoid inline event handlers

Asynchronous JavaScript calls

Object serialization

DOM cleanup tasks during component disposal

JavaScript interop calls without a circuit

Cached JavaScript files

Size limits on JavaScript interop calls

Determine where the app is running



# JavaScript location in ASP.NET Core Blazor apps

Article • 11/19/2024


Load a script in <head> markup

Load a script in <body> markup

Load a script from an external JavaScript file (.js) collocated with a component

Load a script from an external JavaScript file (.js)

Inject a script before or after Blazor starts

JavaScript isolation in JavaScript modules



# Call JavaScript functions from .NET methods in ASP.NET Core Blazor

Article • 10/18/2024


Invoke JS functions

JavaScript API restricted to user gestures

Invoke JavaScript functions without reading a returned value (InvokeVoidAsync)

Component (.razor) example (InvokeVoidAsync)

Class (.cs) example (InvokeVoidAsync)

Invoke JavaScript functions and read a returned value (InvokeAsync)

Component (.razor) example (InvokeAsync)

Class (.cs) example (InvokeAsync)

Dynamic content generation scenarios

Prerendering

Synchronous JS interop in client-side components

JavaScript location

JavaScript isolation in JavaScript modules

Capture references to elements

Reference elements across components

Harden JavaScript interop calls

Avoid circular object references

JavaScript libraries that render UI

Byte array support

Stream from .NET to JavaScript

Catch JavaScript exceptions

Abort a long-running JavaScript function

JavaScript [JSImport] / [JSExport] interop

Unmarshalled JavaScript interop

Disposal of JavaScript interop object references

DOM cleanup tasks during component disposal

JavaScript interop calls without a circuit

Additional resources



# Call .NET methods from JavaScript functions in ASP.NET Core Blazor

Article • 10/25/2024


Invoke a static .NET method

Create JavaScript object and data references to pass to .NET

Invoke an instance .NET method

Avoid trimming JavaScript-invokable .NET methods

Pass a DotNetObjectReference to an individual JavaScript function

Pass a DotNetObjectReference to a class with multiple JavaScript functions

Call .NET generic class methods

Class instance examples

Component instance .NET method helper class

Component instance .NET method called from DotNetObjectReference assigned to an element property

Synchronous JS interop in client-side components

JavaScript location

JavaScript isolation in JavaScript modules

Avoid circular object references

Byte array support

Stream from JavaScript to .NET

JavaScript [JSImport] / [JSExport] interop

Disposal of JavaScript interop object references

DOM cleanup tasks during component disposal

JavaScript interop calls without a circuit

Additional resources



# JavaScript [JSImport] / [JSExport] interop with ASP.NET Core Blazor

Article • 10/04/2024


Obsolete JavaScript interop API

Prerequisites

Namespace

Enable unsafe blocks

Razor class library (RCL) collocated JS is unsupported

Call JavaScript from .NET

Call .NET from JavaScript

Multiple module import calls

Use of a single JavaScript module across components

Additional resources



# ASP.NET Core Blazor JavaScript with static server-side rendering (static SSR)

Article • 12/02/2024


Events

Enhanced page load script example

Example implementation without using an RCL



# Call a web API from ASP.NET Core Blazor

Article • 10/21/2024


Package

Sample apps

BlazorWebAppCallWebApi

BlazorWebAppCallWebApi_Weather

BlazorWebAssemblyCallWebApi

Server-side scenarios for calling external web APIs

Service abstractions for web API calls

Blazor Web App external web APIs

Prerendered data

Add the HttpClient service

JSON helpers

GET from JSON (GetFromJsonAsync)

POST as JSON (PostAsJsonAsync)

PUT as JSON (PutAsJsonAsync)

PATCH as JSON (PatchAsJsonAsync)

DELETE (DeleteAsync) and additional extension methods

Named HttpClient with IHttpClientFactory

Typed HttpClient

Cookie-based request credentials

HttpClient and HttpRequestMessage with Fetch API request options

Handle errors

Cross-Origin Resource Sharing (CORS)

Antiforgery support

Blazor framework component examples for testing web API access

Additional resources

General

Mitigation of overposting attacks

Server-side

Client-side



# Display images and documents in ASP.NET Core Blazor

Article • 10/18/2024


Dynamically set an image source

Stream image or document data

Additional resources



# ASP.NET Core Blazor authentication and authorization

Article • 11/19/2024


Securely maintain sensitive data and credentials

Managed identities for Microsoft Azure services

Antiforgery support

Server-side Blazor authentication

IHttpContextAccessor / HttpContext in Razor components

Shared state

Server-side security of sensitive data and credentials

Project template

Blazor Identity UI (Individual Accounts)

Manage authentication state in Blazor Web Apps

Additional claims and tokens from external providers

Azure App Service on Linux with Identity Server

Inject AuthenticationStateProvider for services scoped to a component

Unauthorized content display while prerendering with a custom AuthenticationStateProvider

User state management

Additional security abstractions

Authentication state management at sign out

Temporary redirection URL validity duration

Client-side Blazor authentication

AuthenticationStateProvider service

Obtain a user's claims principal data

Expose the authentication state as a cascading parameter

Authorization

AuthorizeView component

Role-based and policy-based authorization

Content displayed during asynchronous authentication

[Authorize] attribute

Resource authorization

Customize unauthorized content with the Router component

Procedural logic

Troubleshoot errors

Personally Identifiable Information (PII)

Additional resources



# ASP.NET Core Blazor authentication state

Article • 09/23/2024


Abstract AuthenticationStateProvider class

Implement a custom AuthenticationStateProvider

Authentication state change notifications

Additional resources



# Secure ASP.NET Core Blazor WebAssembly

Article • 10/08/2024


Client-side/SPA security of sensitive data and credentials

Authentication library

Authentication process with OIDC

Authentication component

Authorization

Customize authentication

Require authorization for the entire app

Use one identity provider app registration per app

Refresh tokens

Establish claims for users

Prerendering support

Azure App Service on Linux with Identity Server

Windows Authentication

Secure a SignalR hub

Logging

The WebAssembly sandbox

Implementation guidance

Use the Authorization Code flow with PKCE

Additional resources



# Secure ASP.NET Core Blazor WebAssembly with ASP.NET Core Identity

Article • 11/19/2024


Endpoints for registering, logging in, and logging out

Token authentication

Additional Identity scenarios

Use secure authentication flows to maintain sensitive data and credentials

Sample apps

Backend web API app packages and code

Packages

Sample app code

Frontend standalone Blazor WebAssembly app packages and code

Packages

Sample app code

Test user seeding demonstration

Roles

Cross-domain hosting (same-site configuration)

Antiforgery support

Troubleshoot

Logging

Common errors

Cookies and site data

App upgrades

Inspect the user's claims

Additional resources



# Account confirmation and password recovery in ASP.NET Core Blazor WebAssembly with ASP.NET Core Identity

Article • 12/11/2024


Namespaces and article code examples

Select and configure an email provider for the server project

Configure a user secret for the provider's security key

Implement IEmailSender in the server project

Configure the server project to require email confirmation

Update the client project's account registration response

Update seed data code to confirm seeded accounts

Enable account confirmation after a site has users

Password recovery

Email and activity timeout

Change all ASP.NET Core Data Protection token lifespans

Change the email token lifespan

Troubleshoot

Additional resources



# Enable QR code generation for TOTP authenticator apps in ASP.NET Core Blazor WebAssembly with ASP.NET Core Identity

Article • 12/11/2024


Namespaces and article code examples

Optional account confirmation and password recovery

Add a QR code library to the app

Set the TOTP organization name

Add model classes

IAccountManagement interface

Update the cookie authentication state provider

Replace Login component

Add a component to display recovery codes

Manage 2FA page

Link to the the Manage 2FA page

Additional resources



# Secure an ASP.NET Core Blazor WebAssembly standalone app with the Authentication library

Article • 09/12/2024


Walkthrough

Register an app

Create the Blazor app

Configure the app

Run the app

Parts of the app

Authentication package

Authentication service support

wwwroot/appsettings.json configuration

Access token scopes

Imports file

Index page

App component

RedirectToLogin component

LoginDisplay component

Authentication component

Troubleshoot

Logging

Common errors

Cookies and site data

App upgrades

Inspect the user

Inspect the content of a JSON Web Token (JWT)

Additional resources



# Secure an ASP.NET Core Blazor WebAssembly standalone app with Microsoft Accounts

Article • 10/20/2024


Walkthrough

Create a tenant in Azure

Register an app in Azure

Create the Blazor app

Run the app

Parts of the app

Authentication package

Authentication service support

wwwroot/appsettings.json configuration

Access token scopes

Login mode

Imports file

Index page

App component

RedirectToLogin component

LoginDisplay component

Authentication component

Troubleshoot

Logging

Common errors

Cookies and site data

App upgrades

Inspect the user

Inspect the content of a JSON Web Token (JWT)

Additional resources



# Secure an ASP.NET Core Blazor WebAssembly standalone app with Microsoft Entra ID

Article • 10/20/2024


Walkthrough

Create a tenant in Azure

Register an app in Azure

Create the Blazor app

Run the app

Parts of the app

Authentication package

Authentication service support

wwwroot/appsettings.json configuration

Access token scopes

Login mode

Imports file

Index page

App component

RedirectToLogin component

LoginDisplay component

Authentication component

Troubleshoot

Logging

Common errors

Cookies and site data

App upgrades

Inspect the user

Inspect the content of a JSON Web Token (JWT)

Additional resources



# Secure an ASP.NET Core Blazor WebAssembly standalone app with Azure Active Directory B2C

Article • 10/20/2024


Walkthrough

Create a tenant in Azure

Register an app in Azure

Create the Blazor app

Run the app

Parts of the app

Authentication package

Authentication service support

Access token scopes

Login mode

Imports file

Index page

App component

RedirectToLogin component

LoginDisplay component

Authentication component

Custom policies

Troubleshoot

Logging

Common errors

Cookies and site data

App upgrades

Inspect the user

Inspect the content of a JSON Web Token (JWT)

Additional resources



# ASP.NET Core Blazor WebAssembly additional security scenarios

Article • 10/08/2024


Attach tokens to outgoing requests

Custom authentication request scenarios

Customize the login process

Customize options before obtaining a token interactively

Customize options when using an IAccessTokenProvider

Logout with a custom return URL

Obtain the login path from authentication options

Custom AuthorizationMessageHandler class

Configure AuthorizationMessageHandler

Typed HttpClient

Configure the HttpClient handler

Unauthenticated or unauthorized web API requests in an app with a secure default client

Request additional access tokens

Cross-Origin Resource Sharing (CORS)

Handle token request errors

Save app state before an authentication operation with session storage

Save app state before an authentication operation with session storage and a state container

Customize app routes

Customize the authentication user interface

Customize the user

Customize the user with a payload claim

ME-ID security groups and roles with a custom user account class

Authenticate users to only call protected third party APIs

Authenticate users with a third-party provider and call protected APIs on the host server and the third party

Use a server access token to retrieve the third-party access token

Make API calls from the client to the server API in order to call third-party APIs

Use OpenID Connect (OIDC) v2.0 endpoints

Configure and use gRPC in components

Replace the AuthenticationService implementation

Replace any JavaScript AuthenticationService implementation

Replace the Microsoft Authentication Library for JavaScript (MSAL.js)

Pass custom provider options

Additional resources



# Microsoft Entra (ME-ID) groups, Administrator Roles, and App Roles

Article • 10/21/2024


Sample app

Prerequisite

ME-ID app registration online tools

Scopes

Custom user account

Authorization configuration

App Roles

Additional resources



# Use Graph API with ASP.NET Core Blazor WebAssembly

Article • 11/06/2024


Call Graph API from a component using the Graph SDK

Customize user claims using the Graph SDK

Assign users to an app registration with or without app roles

DefaultAccessTokenScopes versus AdditionalScopesToConsent

Additional resources

General guidance

Security guidance



# Secure an ASP.NET Core Blazor Web App with Microsoft Entra ID

Article • 11/19/2024


Sample app

Server-side Blazor Web App project (BlazorWebAppEntra)

Client-side Blazor Web App project (BlazorWebAppEntra.Client)

Configuration

Configure the app

Establish the client secret

Secret Manager tool

Azure Key Vault

Redirect to the home page on sign out

Troubleshoot

Logging

Common errors

Cookies and site data

App upgrades

Run the server app

Inspect the user

Additional resources



# Secure an ASP.NET Core Blazor Web App with OpenID Connect (OIDC)

Article • 10/28/2024


Sample app

Server-side Blazor Web App project (BlazorWebAppOidc)

Configuration

Establish the client secret

Configure the app

Sample app code

Client-side Blazor Web App project (BlazorWebAppOidc.Client)

Redirect to the home page on signout

Cryptographic nonce

Application roles for apps not registered with Microsoft Entra (ME-ID)

Application roles for apps registered with Microsoft Entra (ME-ID)

Troubleshoot

Logging

Common errors

Cookies and site data

App upgrades

Run the server app

Inspect the user

Additional resources



# Threat mitigation guidance for ASP.NET Core Blazor static server-side rendering

Article • 11/19/2024


General considerations for server-side rendering

Input validation and sanitization

Session management

Error handling and logging

ASP.NET Core Data Protection

Denial of service

Recommended (non-exhaustive) check list



# Threat mitigation guidance for ASP.NET Core Blazor interactive server-side rendering

Article • 11/19/2024


Interactive Server Components with WebSocket compression enabled

Shared state

IHttpContextAccessor / HttpContext in Razor components

Resource exhaustion

CPU

Memory

Client connections

Denial of Service (DoS) attacks

Interactions with the browser (client)

JavaScript functions invoked from .NET

.NET methods invoked from the browser

Events

Protect against multiple dispatches

Cancel early and avoid use-after-dispose

Avoid events that produce large amounts of data

Additional security guidance

Logging and sensitive data

Protect information in transit with HTTPS

Cross-site scripting (XSS)

Cross-origin protection

Click-jacking

Open redirects

Security checklist



# Account confirmation and password recovery in ASP.NET Core Blazor

Article • 11/19/2024


Namespace

Select and configure an email provider

Configure a user secret for the provider's security key

Implement IEmailSender

Configure app to support email

Enable account confirmation after a site has users

Email and activity timeout

Change all ASP.NET Core Data Protection token lifespans

Change the email token lifespan

Troubleshoot

Additional resources



# Enable QR code generation for TOTP authenticator apps in an ASP.NET Core Blazor Web App

Article • 12/11/2024


Adding QR codes to the 2FA configuration page

EnableAuthenticator component in reference source

Additional resources



# Enforce a Content Security Policy for ASP.NET Core Blazor

Article • 09/27/2024


Policy directives

Apply the policy

Server-side Blazor apps

Client-side Blazor apps

Apply a CSP in non- Development environments

Blazor Web App approaches

Blazor WebAssembly app approaches

Meta tag limitations

Test a policy and receive violation reports

Troubleshoot

Additional resources



# ASP.NET Core server-side and Blazor Web App additional security scenarios

Article • 11/19/2024


Pass tokens to a server-side Blazor app

Set the authentication scheme

Circuit handler to capture users for custom services

Access AuthenticationStateProvider in outgoing request middleware



# ASP.NET Core Blazor state management

Article • 09/12/2024


Maintain user state

Persist state across circuits

Where to persist state

Server-side storage

URL

Browser storage

ASP.NET Core Protected Browser Storage

Save and load data within a component

Handle the loading state

Handle prerendering

Factor out the state preservation to a common location

In-memory state container service

Additional approaches

Troubleshoot

Additional resources



# Debug ASP.NET Core apps

Article • 10/21/2024


Prerequisites

Browser prerequisites

IDE prerequisites

Visual Studio Code prerequisites

App configuration prerequisites

Packages

Debug a Blazor Web App in an IDE

Debug a Blazor WebAssembly app in an IDE Visual Studio

Attach to an existing Visual Studio Code debugging session

Visual Studio Code launch options

Debug Blazor WebAssembly with Google Chrome or Microsoft Edge

Debug a Blazor WebAssembly app with Firefox

Break on unhandled exceptions

Browser source maps

Firewall configuration

Troubleshoot

Breakpoints in OnInitialized{Async} not hit

Visual Studio (Windows) timeout



# Lazy load assemblies in ASP.NET Core Blazor WebAssembly

Article • 12/02/2024


File extension placeholder ({FILE EXTENSION}) for assembly files

Project file configuration

Router component configuration

Assemblies that include routable components

User interaction with <Navigating> content

Handle cancellations in OnNavigateAsync

OnNavigateAsync events and renamed assembly files

Complete example

Troubleshoot

Additional resources



# ASP.NET Core Blazor WebAssembly native dependencies

Article • 04/12/2024


.NET WebAssembly build tools

Use native code

C++ managed method callbacks

Package native dependencies in a NuGet package

SkiaSharp example library use

Additional resources



# ASP.NET Core Blazor performance best practices

Article • 09/12/2024


Optimize rendering speed

Avoid unnecessary rendering of component subtrees

Virtualization

Create lightweight, optimized components

Avoid thousands of component instances

Inline child components into their parents

Define reusable RenderFragments in code

Don't receive too many parameters

Ensure cascading parameters are fixed

Avoid attribute splatting with CaptureUnmatchedValues

Implement SetParametersAsync manually

Don't trigger events too rapidly

Avoid rerendering after handling events without state changes

Avoid recreating delegates for many repeated elements or components

Optimize JavaScript interop speed

Avoid excessively fine-grained calls

Consider the use of synchronous calls

Call JavaScript from .NET

Call .NET from JavaScript

Use JavaScript [JSImport] / [JSExport] interop

Ahead-of-time (AOT) compilation

Minimize app download size

Runtime relinking

Use System.Text.Json

Intermediate Language (IL) trimming

Lazy load assemblies

Compression

Disable unused features



# Test Razor components in ASP.NET Core Blazor

Article • 03/08/2024


Test approaches

Choose the most appropriate test approach

Test components with bUnit

Additional resources



# ASP.NET Core Blazor Progressive Web Application (PWA)

Article • 11/06/2024


Create a project from the PWA template

Convert an existing Blazor WebAssembly app into a PWA

Installation and app manifest

Offline support

Cache-first fetch strategy

Background updates

How requests are resolved

Support server-rendered pages

Control asset caching

Push notifications

Caveats for offline PWAs

Offline support only when published

Update completion after user navigation away from app

Users may run any historical version of the app

Interference with server-rendered pages

All service worker asset manifest contents are cached

Interaction with authentication

Additional resources



# Host and deploy ASP.NET Core Blazor

Article • 10/08/2024


Publish the app

IIS

App base path

Background

Server-side Blazor

Standalone Blazor WebAssembly

Configure the app base path

Obtain the app base path from configuration

Blazor Server MapFallbackToPage configuration

Deployment



# Host and deploy server-side Blazor apps

Article • 10/18/2024


Host configuration values

Deployment

Scalability

SignalR configuration

Transports

Global deployment and connection failures

Azure App Service

Azure SignalR Service

Azure Container Apps

IIS

Kubernetes

Linux with Nginx

Linux with Apache

Measure network latency

Memory management

Measure memory usage in general

Memory usage applied to Blazor

Reduce memory usage

Heap size for some mobile device browsers

Additional actions and considerations

Measuring memory



# Host and deploy ASP.NET Core Blazor WebAssembly

Article • 09/27/2024


Subdomain and IIS sub-application hosting

Decrease maximum heap size for some mobile device browsers

Webcil packaging format for .NET assemblies

Customize how boot resources are loaded

Compression

Rewrite URLs for correct routing

Standalone deployment

Azure App Service

Azure Static Web Apps

Deploy from Visual Studio

Deploy from Visual Studio Code

Deploy from GitHub

IIS

web.config

Use a custom web.config

Install the URL Rewrite Module

Configure the website

Host as an IIS sub-app

Brotli and Gzip compression

Troubleshooting

Azure Storage

Nginx

Apache

GitHub Pages

Standalone with Docker

Host configuration values

Content root

Path base

URLs

Configure the Trimmer

Change the file name extension of DLL files

Prior deployment corruption

Resolve integrity check failures

Diagnosing integrity problems

Troubleshoot integrity PowerShell script

Disable integrity checking for non-PWA apps

Disable integrity checking for PWAs



# ASP.NET Core Blazor WebAssembly .NET runtime and app bundle caching

Article • 07/09/2024


Diagnosing integrity problems

Troubleshoot integrity PowerShell script

Disable resource caching and integrity checks for non-PWA apps

Disable resource caching and integrity checks for PWAs

Additional resources



# Avoid HTTP caching issues when upgrading ASP.NET Core Blazor apps

Article • 04/05/2024


Detect and diagnose upgrade issues

Recommended actions before an upgrade

Align framework packages with the framework version

Verify the presence of correct caching headers

Use Clear-Site-Data to delete state in the browser

Append a query string to the Blazor script tag



# Configure the Trimmer for ASP.NET Core Blazor

Article • 09/12/2024


Configuration

Default trimmer granularity

Additional resources



# Deployment layout for ASP.NET Core hosted Blazor WebAssembly apps

Article • 09/12/2024


Experimental NuGet package and sample app

Customize the Blazor WebAssembly loading process via a NuGet package

Create an MSBuild task to customize the list of published files and define new extensions

Author a NuGet package to automatically transform the publish output

Automatically bootstrap Blazor from the bundle

Serve the bundle from the host server app



# ASP.NET Core Blazor with Entity Framework Core (EF Core)

Article • 10/28/2024


Secure authentication flow required for production apps

Sample app

Build a Blazor movie database app tutorial

Database access

New DbContext instances

Scope to the component lifetime

Enable sensitive data logging

Additional resources



# ASP.NET Core Blazor advanced scenarios (render tree construction)

Article • 10/18/2024


Manually build a render tree (RenderTreeBuilder)

Sequence numbers relate to code line numbers and not execution order

The problem with generating sequence numbers programmatically

Guidance and conclusions



# Tutorial: Create an ASP.NET Core app with Angular in Visual Studio

Article • 11/08/2024


Prerequisites

Create the frontend app

Set the project properties

Start the project

Publish the project

Troubleshooting

Proxy error

Verify port

Docker

Next steps



# Tutorial: Create an ASP.NET Core app with React in Visual Studio

Article • 11/06/2024


Prerequisites

Create the frontend app

Set the project properties

Start the project

Publish the project

Troubleshooting

Proxy error

Verify ports

Privacy error

Docker

Next steps



# Tutorial: Create an ASP.NET Core app with Vue in Visual Studio

Article • 11/06/2024


Prerequisites

Create the frontend app

Set the project properties

Start the project

Publish the project

Troubleshooting

Proxy error

Privacy error

Verify ports

Outdated version of Vue

Docker

Next steps



# JavaScript and TypeScript in Visual Studio

Article • 06/27/2024


JavaScript language service

TypeScript support

Project templates



# Overview of Single Page Apps (SPAs) in ASP.NET Core

Article • 06/18/2024


Visual Studio tutorials

ASP.NET Core SPA templates

Legacy ASP.NET Core SPA templates



# Use the Angular project template with ASP.NET Core

Article • 09/29/2023


Visual Studio tutorial

ASP.NET Core SPA templates

Legacy ASP.NET Core SPA templates



# Use React with ASP.NET Core

Article • 06/18/2024


Visual Studio tutorial

ASP.NET Core SPA templates

Legacy ASP.NET Core SPA templates



# Client-side library acquisition in ASP.NET Core with LibMan

Article • 06/18/2024


LibMan use cases

Additional resources



# Use the LibMan CLI with ASP.NET Core

Article • 06/18/2024


Prerequisites

Installation

Usage

Initialize LibMan in the project

Synopsis

Options

Examples

Add library files

Synopsis

Arguments

Options

Examples

Restore library files

Synopsis

Options

Examples

Delete library files

Synopsis

Options

Examples

Uninstall library files

Synopsis

Arguments

Options

Examples

Update library version

Synopsis

Arguments

Options

Examples

Manage library cache

Synopsis

Arguments

Options

Examples

Additional resources



# Use LibMan with ASP.NET Core in Visual Studio

Article • 06/18/2024


Prerequisites

Add library files

Use the Add Client-Side Library dialog

Manually configure LibMan manifest file entries

Restore library files

Restore files during build

Restore files manually

Delete library files

Uninstall library files

Update library version

Additional resources



# JavaScript [JSImport] / [JSExport] interop in .NET WebAssembly

Article • 08/22/2024


Prerequisites

Sample app

JS interop using [JSImport] / [JSExport] attributes

Importing JS methods

Loading JavaScript declarations

Type mappings

JS primitives

JS Date objects

JS object references

Asynchronous interop

Type mapping limitations

Performance considerations

Subscribing to JS events

JS [JSImport] / [JSExport] interop scenarios



# JavaScript [JSImport] / [JSExport] interop with a WebAssembly Browser App project

Article • 08/22/2024


Prerequisites

Namespace

Project configuration

JavaScript interop on WASM

Experimental workload and project templates

Browser app

Node.js console app

Additional resources



# Use Grunt in ASP.NET Core

Article • 09/27/2024


Preparing the application

Configuring NPM

Configuring Grunt

All together now

Watching for changes

Binding to Visual Studio events

Summary



# Bundle and minify static assets in ASP.NET Core

Article • 08/08/2024


What is bundling and minification

Bundling

Minification

Impact of bundling and minification

Choose a bundling and minification strategy

Environment-based bundling and minification

Additional resources



# Browser link in ASP.NET Core

Article • 06/17/2024


Runtime compilation vs. hot reload

How to use browser link

Refresh the web app in several browsers at once

The browser link dashboard

Enable or disable browser link

Enable or disable CSS hot reload

How it works



# Session and state management in ASP.NET Core

Article • 09/18/2024


State management

SignalR/Blazor Server and HTTP context-based state management

Cookies

Session state

Configure session state

Load session state asynchronously

Session options

Set and get Session values

TempData

TempData samples

TempData providers

Choose a TempData provider

Configure the TempData provider

Query strings

Hidden fields

HttpContext.Items

Cache

Checking session state

Common errors

Additional resources



# Layout in ASP.NET Core

Article • 06/03/2022


What is a Layout

Specifying a Layout

Sections

Ignoring sections

Importing Shared Directives

Running Code Before Each View



# Razor syntax reference for ASP.NET Core

Article • 09/27/2024


Rendering HTML

Razor syntax

Scalable Vector Graphics (SVG)

Implicit Razor expressions

Explicit Razor expressions

Expression encoding

Razor code blocks

Implicit transitions

Explicit delimited transition

Explicit line transition

Conditional attribute rendering

Control structures

Conditionals @if, else if, else, and @switch

Looping @for, @foreach, @while, and @do while

Compound @using

@try, catch, finally

@lock

Comments

Directives

@attribute

@code

@functions

@implements

@inherits

@inject

@layout

@model

@namespace

@page

@preservewhitespace

@rendermode

@section

@typeparam

@using

Directive attributes

@attributes

@bind

@bind:culture

@formname

@on{EVENT}

@on{EVENT}:preventDefault

@on{EVENT}:stopPropagation

@key

@ref

Templated Razor delegates

Tag Helpers

Razor reserved keywords

Razor keywords

C# Razor keywords

Reserved keywords not used by Razor

Inspect the Razor C# class generated for a view

View lookups and case sensitivity

Imports used by Razor

Additional resources



# Create reusable UI using the Razor class library project in ASP.NET Core

Article • 07/23/2024


Create a class library containing Razor UI

Reference RCL content

Override views, partial views, and pages

RCL Pages layout

Create an RCL with static assets

Add client web assets to the build process

Exclude static assets

Typescript integration

Consume content from a referenced RCL

Multi-project development flow

Publish

Additional resources



# ASP.NET Core built-in Tag Helpers

Article • 06/03/2022


Built-in ASP.NET Core Tag Helpers

Additional resources



# Tag Helpers in ASP.NET Core

Article • 03/05/2024


What are Tag Helpers

What Tag Helpers provide

Managing Tag Helper scope

@addTagHelper makes Tag Helpers available

@removeTagHelper removes Tag Helpers

Controlling Tag Helper scope with the _ViewImports.cshtml file

Opting out of individual elements

Using @tagHelperPrefix to make Tag Helper usage explicit

Self-closing Tag Helpers

C# in Tag Helpers attribute/declaration

Tag helper initializers

Tag Helper automatic version generation outside of wwwroot

IntelliSense support for Tag Helpers

Tag Helpers compared to HTML Helpers

Tag Helpers compared to Web Server Controls

Customizing the Tag Helper element font

Built-in ASP.NET Core Tag Helpers

Additional resources



# Author Tag Helpers in ASP.NET Core

Article • 09/14/2022


Get started with Tag Helpers

A minimal Tag Helper

SetAttribute and SetContent

ProcessAsync

RemoveAll, PreContent.SetHtmlContent and PostContent.SetHtmlContent

Pass a model to a Tag Helper

Condition Tag Helper

Avoid Tag Helper conflicts

Inspect and retrieve child content

Load minified partial view TagHelper



# Tag Helpers in forms in ASP.NET Core

Article • 09/27/2024


The Form Tag Helper

Using a named route

The Form Action Tag Helper

Submit to controller example

Submit to page example

Submit to route example

The Input Tag Helper

Checkbox hidden input rendering

HTML Helper alternatives to Input Tag Helper

HtmlAttributes

Expression names

Navigating child properties

Expression names and Collections

The Textarea Tag Helper

The Label Tag Helper

The Validation Tag Helpers

The Validation Message Tag Helper

The Validation Summary Tag Helper

Sample

The Select Tag Helper

Enum binding

Option Group

Multiple select

No selection

Additional resources



# Tag Helper Components in ASP.NET Core

Article • 06/18/2024


Use cases

Inject into HTML head element

Inject into HTML body element

Register a Component

Registration via services container

Registration via Razor file

Registration via Page Model or controller

Create a Component

Additional resources



# Anchor Tag Helper in ASP.NET Core

Article • 06/18/2024


Anchor Tag Helper attributes

asp-controller

asp-action

asp-route-{value}

asp-route

asp-all-route-data

asp-fragment

asp-area

Usage in Razor Pages

Usage in MVC

asp-protocol

asp-host

asp-page

asp-page-handler

Additional resources



# Cache Tag Helper in ASP.NET Core MVC

Article • 06/17/2024


Cache Tag Helper Attributes

enabled

expires-on

expires-after

expires-sliding

vary-by-header

vary-by-query

vary-by-route

vary-by-cookie

vary-by-user

vary-by

priority

Additional resources



# Component Tag Helper in ASP.NET Core

Article • 11/15/2024


Prerequisites

Component Tag Helper

Additional resources



# Distributed Cache Tag Helper in ASP.NET Core

Article • 06/17/2024


Distributed Cache Tag Helper Attributes

Attributes shared with the Cache Tag Helper

name

Distributed Cache Tag Helper IDistributedCache implementations

Additional resources



# Environment Tag Helper in ASP.NET Core

Article • 06/03/2022


Environment Tag Helper Attributes

names

include and exclude attributes

include

exclude

Additional resources



# Tag Helpers in forms in ASP.NET Core

Article • 09/27/2024


The Form Tag Helper

Using a named route

The Form Action Tag Helper

Submit to controller example

Submit to page example

Submit to route example

The Input Tag Helper

Checkbox hidden input rendering

HTML Helper alternatives to Input Tag Helper

HtmlAttributes

Expression names

Navigating child properties

Expression names and Collections

The Textarea Tag Helper

The Label Tag Helper

The Validation Tag Helpers

The Validation Message Tag Helper

The Validation Summary Tag Helper

Sample

The Select Tag Helper

Enum binding

Option Group

Multiple select

No selection

Additional resources



# Tag Helpers in forms in ASP.NET Core

Article • 09/27/2024


The Form Tag Helper

Using a named route

The Form Action Tag Helper

Submit to controller example

Submit to page example

Submit to route example

The Input Tag Helper

Checkbox hidden input rendering

HTML Helper alternatives to Input Tag Helper

HtmlAttributes

Expression names

Navigating child properties

Expression names and Collections

The Textarea Tag Helper

The Label Tag Helper

The Validation Tag Helpers

The Validation Message Tag Helper

The Validation Summary Tag Helper

Sample

The Select Tag Helper

Enum binding

Option Group

Multiple select

No selection

Additional resources



# Image Tag Helper in ASP.NET Core

Article • 06/03/2022


Image Tag Helper Attributes

src

asp-append-version

Hash caching behavior

Additional resources



# Tag Helpers in forms in ASP.NET Core

Article • 09/27/2024


The Form Tag Helper

Using a named route

The Form Action Tag Helper

Submit to controller example

Submit to page example

Submit to route example

The Input Tag Helper

Checkbox hidden input rendering

HTML Helper alternatives to Input Tag Helper

HtmlAttributes

Expression names

Navigating child properties

Expression names and Collections

The Textarea Tag Helper

The Label Tag Helper

The Validation Tag Helpers

The Validation Message Tag Helper

The Validation Summary Tag Helper

Sample

The Select Tag Helper

Enum binding

Option Group

Multiple select

No selection

Additional resources



# Tag Helpers in forms in ASP.NET Core

Article • 09/27/2024


The Form Tag Helper

Using a named route

The Form Action Tag Helper

Submit to controller example

Submit to page example

Submit to route example

The Input Tag Helper

Checkbox hidden input rendering

HTML Helper alternatives to Input Tag Helper

HtmlAttributes

Expression names

Navigating child properties

Expression names and Collections

The Textarea Tag Helper

The Label Tag Helper

The Validation Tag Helpers

The Validation Message Tag Helper

The Validation Summary Tag Helper

Sample

The Select Tag Helper

Enum binding

Option Group

Multiple select

No selection

Additional resources



# Link Tag Helper in ASP.NET Core

Article • 06/27/2022


Commonly used Link Tag Helper attributes

href

asp-fallback-href

asp-fallback-test-class

asp-fallback-test-property

asp-fallback-test-value

Additional resources



# Partial Tag Helper in ASP.NET Core

Article • 06/18/2024


Overview

name

for

model

view-data

Migrate from an HTML Helper

Additional resources



# Persist Component State Tag Helper in ASP.NET Core

Article • 11/15/2024


Prerequisites

Persist state for prerendered components

Additional resources



# Script Tag Helper in ASP.NET Core

Article • 09/23/2024


Commonly used Script Tag Helper attributes

src

asp-append-version

asp-fallback-src

asp-fallback-src-exclude

asp-fallback-src-include

asp-fallback-test

asp-order

asp-src-exclude

asp-src-include

asp-suppress-fallback-integrity

Additional resources



# Tag Helpers in forms in ASP.NET Core

Article • 09/27/2024


The Form Tag Helper

Using a named route

The Form Action Tag Helper

Submit to controller example

Submit to page example

Submit to route example

The Input Tag Helper

Checkbox hidden input rendering

HTML Helper alternatives to Input Tag Helper

HtmlAttributes

Expression names

Navigating child properties

Expression names and Collections

The Textarea Tag Helper

The Label Tag Helper

The Validation Tag Helpers

The Validation Message Tag Helper

The Validation Summary Tag Helper

Sample

The Select Tag Helper

Enum binding

Option Group

Multiple select

No selection

Additional resources



# Tag Helpers in forms in ASP.NET Core

Article • 09/27/2024


The Form Tag Helper

Using a named route

The Form Action Tag Helper

Submit to controller example

Submit to page example

Submit to route example

The Input Tag Helper

Checkbox hidden input rendering

HTML Helper alternatives to Input Tag Helper

HtmlAttributes

Expression names

Navigating child properties

Expression names and Collections

The Textarea Tag Helper

The Label Tag Helper

The Validation Tag Helpers

The Validation Message Tag Helper

The Validation Summary Tag Helper

Sample

The Select Tag Helper

Enum binding

Option Group

Multiple select

No selection

Additional resources



# Tag Helpers in forms in ASP.NET Core

Article • 09/27/2024


The Form Tag Helper

Using a named route

The Form Action Tag Helper

Submit to controller example

Submit to page example

Submit to route example

The Input Tag Helper

Checkbox hidden input rendering

HTML Helper alternatives to Input Tag Helper

HtmlAttributes

Expression names

Navigating child properties

Expression names and Collections

The Textarea Tag Helper

The Label Tag Helper

The Validation Tag Helpers

The Validation Message Tag Helper

The Validation Summary Tag Helper

Sample

The Select Tag Helper

Enum binding

Option Group

Multiple select

No selection

Additional resources



# Tag Helpers in forms in ASP.NET Core

Article • 09/27/2024


The Form Tag Helper

Using a named route

The Form Action Tag Helper

Submit to controller example

Submit to page example

Submit to route example

The Input Tag Helper

Checkbox hidden input rendering

HTML Helper alternatives to Input Tag Helper

HtmlAttributes

Expression names

Navigating child properties

Expression names and Collections

The Textarea Tag Helper

The Label Tag Helper

The Validation Tag Helpers

The Validation Message Tag Helper

The Validation Summary Tag Helper

Sample

Enum binding

Option Group

Multiple select

No selection

Additional resources



# Share controllers, views, Razor Pages and more with Application Parts

Article • 06/03/2022


Load ASP.NET Core features

Include views

Prevent loading resources

Feature providers

Display available features

Discovery in application parts



# Work with the application model in ASP.NET Core

Article • 06/17/2024


Models and Providers (IApplicationModelProvider)

Conventions

Modify the ApplicationModel

Modify the ControllerModel description

Modify the ActionModel description

Modify the ParameterModel

Modify the ActionModel name

Custom routing convention

Use ApiExplorer to document an app



# Areas in ASP.NET Core

Article • 06/17/2024


Areas for controllers with views

Area folder structure

Associate the controller with an Area

Add Area route

Link generation with MVC areas

Shared layout for Areas using the _ViewStart.cshtml file

Application root folder

_ViewImports.cshtml

Change default area folder where views are stored

Areas with Razor Pages

Link generation with Razor Pages and areas

Import namespace and Tag Helpers with _ViewImports file

Shared layout for Razor Pages Areas

Publishing Areas

Add MVC Area with Visual Studio

Additional resources



# Filters in ASP.NET Core

Article • 06/17/2024


How filters work

Filter types

Implementation

Multiple filter stages

Built-in filter attributes

Filter scopes and order of execution

Default order of execution

Controller level filters

Override the default order

Cancellation and short-circuiting

Dependency injection

ServiceFilterAttribute

TypeFilterAttribute

Authorization filters

Resource filters

Action filters

Exception filters

Result filters

IResultFilter and IAsyncResultFilter

IAlwaysRunResultFilter and IAsyncAlwaysRunResultFilter

IFilterFactory

IFilterFactory implemented on an attribute

Use middleware in the filter pipeline

Thread safety

Additional resources



# ASP.NET Core Razor SDK

Article • 04/10/2024


Overview

Prerequisites

Use the Razor SDK

Properties

Runtime compilation of Razor views

Razor language version

Additional resources



# View components in ASP.NET Core

Article • 09/25/2023


View components

Create a view component

The view component class

View component methods

View search path

Customize the view search path

Invoke a view component

Invoke a view component as a Tag Helper

Invoke a view component directly from a controller

Create a basic view component

Update the controller to pass in priority and completion status

Add a ViewComponent class

Create the view component Razor view

Specify a view component name

Examine the view path

Avoid hard-coded strings

Perform synchronous work

Additional resources



# Razor file compilation in ASP.NET Core

Article • 08/30/2024


Razor compilation

Enable runtime compilation for all environments

Enable runtime compilation conditionally

Enable runtime compilation for a Razor class library

Additional resources



# Display and Editor templates in ASP.NET Core

Article • 06/15/2023


Display templates

Editor templates

Additional resources



# Upload files in ASP.NET Core

Article • 09/27/2024


Security considerations

Storage scenarios

Small and large files

File upload scenarios

Upload small files with buffered model binding to physical storage

Upload small files with buffered model binding to a database

Upload large files with streaming

Validation

Content validation

File extension validation

File signature validation

File name security

Size validation

Match name attribute value to parameter name of POST method

Server and app configuration

Multipart body length limit

Kestrel maximum request body size

Other Kestrel limits

IIS

Troubleshoot

Not Found error when deployed to an IIS server

Connection failure

Null Reference Exception with IFormFile

Stream was too long

Additional resources



# ASP.NET Core Web SDK

Article • 04/10/2024


Overview

Properties



# ASP.NET Core code generator tool (aspnet-codegenerator)

Article • 08/06/2024


Install and update the code generator tool

Uninstall the code generator 

Synopsis

Description

Arguments

Options

Generator options

Area options

Blazor options

Blazor Identity options

Razor page options

View options



# Choose between controller-based APIs and minimal APIs

Article • 04/11/2023


See also



# Create web APIs with ASP.NET Core

Article • 06/01/2024


ControllerBase class

Attributes

Attribute on an assembly

Attribute routing requirement

Automatic HTTP 400 responses

Default BadRequest response

Log automatic 400 responses

Disable automatic 400 response

Binding source parameter inference

FromBody inference notes

FromServices inference notes

Disable inference rules

Multipart/form-data request inference

Problem details for error status codes

Disable ProblemDetails response

Define supported request content types with the [Consumes] attribute

Additional resources



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

Additional resources



# Controller action return types in ASP.NET Core web API

Article • 01/22/2024


Specific type

Return IEnumerable<T> or IAsyncEnumerable<T>

IActionResult type

Synchronous action

Asynchronous action

ActionResult vs IActionResult

ActionResult<T> type

Synchronous action

Asynchronous action

HttpResults type

IResult type

Results<TResult1, TResultN> type

Additional resources



# JsonPatch in ASP.NET Core web API

Article • 03/08/2023


Package installation

Add support for JSON Patch when using System.Text.Json

PATCH HTTP request method

JSON Patch

Resource example

JSON patch example

Resource after patch

Path syntax

Operations

JSON Patch in ASP.NET Core

Action method code

Model state

Dynamic objects

The add operation

The remove operation

The replace operation

The move operation

The copy operation

The test operation

Get the code

Additional resources



# Format response data in ASP.NET Core Web API

Article • 07/16/2024


Format-specific Action Results

Content negotiation

The Accept header

Browsers and content negotiation

Configure formatters

Add XML format support

Configure System.Text.Json -based formatters

Add Newtonsoft.Json -based JSON format support

Format ProblemDetails and ValidationProblemDetails responses

Specify a format

Special case formatters

Response format URL mappings

Polymorphic deserialization

Additional resources



# Custom formatters in ASP.NET Core Web API

Article • 07/16/2024


When to use a custom formatter

Overview of how to create a custom formatter

Create a custom formatter

Derive from the appropriate base class

Specify supported media types and encodings

Override CanReadType and CanWriteType

The CanWriteResult method

Override ReadRequestBodyAsync and WriteResponseBodyAsync

Configure MVC to use a custom formatter

The complete VcardInputFormatter class

Test the app

Additional resources



# Use web API analyzers

Article • 04/10/2024


Reference the analyzer package

Analyzers for web API conventions

Analyzers require Microsoft.NET.Sdk.Web

Additional resources



# Use web API conventions

Article • 04/10/2024


Apply web API conventions

Create web API conventions

Response types

Naming requirements

Additional resources



# Handle errors in ASP.NET Core controller-based web APIs

Article • 08/02/2024


Developer Exception Page

Exception handler

Use exceptions to modify the response

Validation failure error response

Client error response

Default problem details response

Problem details service

Customize problem details with CustomizeProblemDetails

Implement ProblemDetailsFactory

Use ApiBehaviorOptions.ClientErrorMapping

Additional resources



# Test web APIs with the HttpRepl

Article • 07/28/2023


Prerequisites

Installation

Usage

Connect to the web API

Manually point to the OpenAPI description for the web API

Enable verbose output for details on OpenAPI description searching, parsing, and validation

Navigate the web API

View available endpoints

Navigate to an endpoint

Customize the HttpRepl

View the settings

Set color preferences

Set indentation size

Set the default text editor

Set the OpenAPI Description search paths

Test HTTP GET requests

Synopsis

Arguments

Options

Example

Test HTTP POST requests

Synopsis

Arguments

Options

Example

Test HTTP PUT requests

Synopsis

Arguments

Options

Example

Test HTTP DELETE requests

Synopsis

Arguments

Options

Example

Test HTTP PATCH requests

Synopsis

Arguments

Options

Test HTTP HEAD requests

Synopsis

Arguments

Options

Test HTTP OPTIONS requests

Synopsis

Arguments

Options

Set HTTP request headers

Test secured endpoints

Default credentials

Default proxy credentials

HTTP request headers

Toggle HTTP request display

Enable request display

Disable request display

Run a script

Clear the output

Additional resources



# HttpRepl telemetry

Article • 06/17/2024


How to opt out

Disclosure

Data points

Additional resources



# Minimal APIs overview

Article • 07/26/2024


Want to see some code examples?

Want to jump straight into your first project?



# Tutorial: Create a minimal API with ASP.NET Core

Article • 08/21/2024


Overview

Prerequisites

Visual Studio

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



# Minimal APIs quick reference

Article • 08/07/2024


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

ASP.NET Core Middleware

Routing

Route Handlers

Lambda expression

Local function

Instance method

Static method

Endpoint defined outside of Program.cs

Named endpoints and link generation

Route Parameters

Wildcard and catch all routes

Route constraints

Route groups

Parameter binding

Explicit Parameter Binding

Explicit binding from form values

Secure binding from IFormFile and IFormFileCollection

Parameter binding with dependency injection

Optional parameters

Special types

Bind the request body as a Stream or PipeReader

File uploads using IFormFile and IFormFileCollection

Binding to forms with IFormCollection, IFormFile, and IFormFileCollection

Bind to collections and complex types from forms

Bind arrays and string values from headers and query strings

Parameter binding for argument lists with [AsParameters]

Custom Binding

TryParse

BindAsync

Binding failures

Binding Precedence

Configure JSON deserialization options for body binding

Configure JSON deserialization options globally

Configure JSON deserialization options for an endpoint

Read the request body

Responses

Example return values

string return values

JSON return values

Return TypedResults

IResult return values

JSON

Custom Status Code

Text

Stream

Redirect

File

Built-in results

Customizing results

Typed results

Filters

Authorization

Allow unauthenticated users to access an endpoint

CORS

ValidateScopes and ValidateOnBuild

See also



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

Read the 

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



# Route Handlers in Minimal API apps

Article • 07/26/2024


Route handlers

Lambda expression

Local function

Instance method

Static method

Endpoint defined outside of Program.cs

Named endpoints and link generation

Route Parameters

Wildcard and catch all routes

Route constraints

Route groups

Parameter binding

Responses



# Parameter Binding in Minimal API apps

Article • 07/26/2024


Explicit Parameter Binding

Explicit binding from form values

Secure binding from IFormFile and IFormFileCollection

Parameter binding with dependency injection

Optional parameters

Special types

Bind the request body as a Stream or PipeReader

File uploads using IFormFile and IFormFileCollection

Binding to forms with IFormCollection, IFormFile, and IFormFileCollection

Bind to collections and complex types from forms

Bind arrays and string values from headers and query strings

Parameter binding for argument lists with [AsParameters]

Custom Binding

TryParse

BindAsync

Binding failures

Binding Precedence

Configure JSON deserialization options for body binding

Configure JSON deserialization options globally

Configure JSON deserialization options for an endpoint

Read the request body



# How to create responses in Minimal API apps

Article • 08/07/2024


string return values

T (Any other type) return values

IResult return values

TypedResults vs Results

Results<TResult1, TResultN>

Built-in results

JSON

Custom Status Code

Internal Server Error

Text

Stream

Redirect

File

HttpResult interfaces

Customizing responses

Configure JSON serialization options

Configure JSON serialization options globally

Configure JSON serialization options for an endpoint

Additional Resources



# Filters in Minimal API apps

Article • 07/26/2024


Validate an object with a filter

Register a filter using an endpoint filter factory

Register a filter on controller actions

Additional Resources



# Unit and integration tests in Minimal API apps

Article • 07/26/2024


Introduction to integration tests

ASP.NET Core integration tests

IResult implementation types

Additional Resources



# Middleware in Minimal API apps

Article • 07/26/2024


For information on antiforgery middleware in Minimal APIs, see Prevent Cross-Site Request Forgery (XSRF/CSRF) attacks in ASP.NET Core

For more information about middleware see ASP.NET Core Middleware, and the list of built-in middleware that can be added to applications.

For more information about Minimal APIs see Minimal APIs overview.



# How to handle errors in Minimal API apps

Article • 06/18/2024


Exceptions

Developer Exception Page

Exception handler

Client and Server error responses

Problem details

IProblemDetailsService fallback



# Authentication and authorization in minimal APIs

Article • 07/26/2024


Key concepts in authentication and authorization

Enabling authentication in minimal apps

Configuring authentication strategy

Configuring authorization policies in minimal apps

Use dotnet user-jwts for development testing



# OpenAPI support in ASP.NET Core API apps

Article • 10/28/2024


Microsoft.AspNetCore.OpenApi NuGet package

Microsoft.Extensions.ApiDescription.Server NuGet package

ASP.NET Core OpenAPI source code on GitHub

Additional Resources



# Generate OpenAPI documents

Article • 12/11/2024


Package installation

Configure OpenAPI document generation

Options to Customize OpenAPI document generation

Customize the OpenAPI document name

Customize the OpenAPI version of a generated document

Customize the OpenAPI endpoint route

Customize the OpenAPI endpoint

Limit OpenAPI document access to authorized users

Cache generated OpenAPI document

Generate OpenAPI documents at build-time

Customizing build-time document generation

Modifying the output directory of the generated Open API file

Modifying the output file name

Selecting the OpenAPI document to generate

Customizing run-time behavior during build-time document generation

Trimming and Native AOT



# Include OpenAPI metadata in an ASP.NET Core app

Article • 11/06/2024


Include OpenAPI metadata for endpoints

Summary and description

tags

operationId

parameters

Describe the request body

Describe response types

Set responses for ProblemDetails

Multiple response types

Exclude endpoints from the generated document

Include OpenAPI metadata for data types

type and format

Use attributes to add metadata

Other sources of metadata for generated schemas

required

enum

nullable

additionalProperties

Polymorphic types

Add metadata with a schema transformer

Additional resources



# Customize OpenAPI documents

Article • 11/04/2024


OpenAPI document transformers

Customize OpenAPI documents with transformers

Execution order for transformers

Use document transformers

Use operation transformers

Use schema transformers

Additional resources



# Use openAPI documents

Article • 12/11/2024


Use Swagger UI for local ad-hoc testing

Use Scalar for interactive API documentation

Lint generated OpenAPI documents with Spectral



# .NET OpenAPI tool command reference and installation

Article • 08/06/2024


Installation

Add

Add File

Options

Arguments

Add URL

Options

Arguments

Remove

Options

Arguments

Refresh

Options

Arguments



# Overview of ASP.NET Core SignalR

Article • 12/02/2024


What is SignalR?

Transports

Hubs

Browsers that don't support ECMAScript 6 (ES6)

Additional resources



# ASP.NET Core SignalR supported platforms

Article • 06/18/2024


Server system requirements

JavaScript client

.NET client

Java client

Unsupported clients

Browsers that don't support ECMAScript 6 (ES6)



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



# Use hubs in SignalR for ASP.NET Core

Article • 06/18/2024


Configure SignalR hubs

Create and use hubs

The Context object

The Clients object

Send messages to clients

Strongly typed hubs

Client results

.NET client

Typescript client

Java client

Change the name of a hub method

Inject services into a hub

Keyed services support in Dependency Injection

Handle events for a connection

Handle errors

Additional resources



# Send messages from outside a hub

Article • 06/18/2024


Get an instance of IHubContext

Inject an instance of IHubContext in a controller

Get an instance of IHubContext in middleware

Get an instance of IHubContext from IHost

Inject a strongly-typed HubContext

Use IHubContext in generic code

Additional resources



# Manage users and groups in SignalR

Article • 06/18/2024


Users in SignalR

Groups in SignalR

Add or remove connections from a group

Additional resources



# SignalR API design considerations

Article • 06/18/2024


Use custom object parameters to ensure backwards-compatibility

Additional resources



# Use hub filters in ASP.NET Core SignalR

Article • 06/18/2024


Configure hub filters

Create hub filters

Use hub filters

The HubInvocationContext object

The HubLifetimeContext object

Authorization and filters



# ASP.NET Core SignalR clients

Article • 06/18/2024


Versioning, support, and compatibility

Feature distribution

Browsers that don't support ECMAScript 6 (ES6)

Additional resources



# ASP.NET Core SignalR .NET Client

Article • 06/18/2024


Install the SignalR .NET client package

Connect to a hub

Handle lost connection

Automatically reconnect

Manually reconnect

Call hub methods from client

Call client methods from hub

Error handling and logging

Additional resources



# Microsoft.AspNetCore.SignalR.Client Namespace

Reference


Classes

Interfaces

Enums

Remarks



# ASP.NET Core SignalR Java client

Article • 06/18/2024


Install the SignalR Java client package

Connect to a hub

Call hub methods from client

Call client methods from hub

Add logging

Android development notes

Configure bearer token authentication

Passing Class information in Java

Known limitations

Additional resources



# com.microsoft.signalr

Reference


Classes

Interfaces

Enums



# ASP.NET Core SignalR JavaScript client

Article • 06/18/2024


Install the SignalR client package

Install with npm

Use a Content Delivery Network (CDN)

Install with LibMan

Connect to a hub

Cross-origin connections (CORS)

Call hub methods from the client

Call client methods from the hub

Error handling and logging

Reconnect clients

Automatically reconnect

Manually reconnect

Browser sleeping tab

Additional resources



# @microsoft/signalr package

Reference


Classes

Interfaces

Type Aliases

Enums



# ASP.NET Core SignalR hosting and scaling

Article • 09/17/2024


Sticky Sessions

TCP connection resources

Scale out

Azure SignalR Service

Redis backplane

IIS limitations on Windows client OS

Linux with Nginx

Third-party SignalR backplane providers

Next steps



# Publish an ASP.NET Core SignalR app to Azure App Service

Article • 09/17/2024


Publish the app

Configure the app in Azure App Service

App Service Plan limits

Additional resources



# Set up a Redis backplane for ASP.NET Core SignalR scale-out

Article • 11/04/2024


Set up a Redis backplane

Redis server errors

Custom behavior for connection failures

Redis Cluster

Next steps



# Host ASP.NET Core SignalR in background services

Article • 06/18/2024


Enable SignalR at app startup

Call a SignalR Hub from a background service

React to SignalR events with background services

Additional resources



# ASP.NET Core SignalR configuration

Article • 09/18/2024


JSON/MessagePack serialization options

Switch to Newtonsoft.Json

MessagePack serialization options

Configure server options

Advanced HTTP configuration options

Configure client options

Configure logging

Configure allowed transports

Configure bearer authentication

Configure timeout and keep-alive options

Configure stateful reconnect

Configure additional options

Additional resources



# Authentication and authorization in ASP.NET Core SignalR

Article • 06/18/2024


Authenticate users connecting to a SignalR hub

Cookie authentication

Bearer token authentication

Built-in JWT authentication

Identity Server JWT authentication

Cookies vs. bearer tokens

Windows authentication

Use claims to customize identity handling

Authorize users to access hubs and hub methods

Use authorization handlers to customize hub method authorization

Additional resources



# Security considerations in ASP.NET Core SignalR

Article • 06/18/2024


Cross-Origin Resource Sharing

WebSocket Origin Restriction

ConnectionId

Access token logging

Exceptions

Buffer management



# Use MessagePack Hub Protocol in SignalR for ASP.NET Core

Article • 06/18/2024


What is MessagePack?

Configure MessagePack on the server

Configure MessagePack on the client

.NET client

JavaScript client

Java client

MessagePack considerations

MessagePack is case-sensitive

DateTime.Kind is not preserved when serializing/deserializing

MessagePack support in "ahead-of-time" compilation environment

Type checks are more strict in MessagePack

Chars and Strings in Java

Additional resources



# Use streaming in ASP.NET Core SignalR

Article • 06/18/2024


Set up a hub for streaming

Server-to-client streaming

Client-to-server streaming

.NET client

Server-to-client streaming

Client-to-server streaming

JavaScript client

Server-to-client streaming

Client-to-server streaming

Java client

Server-to-client streaming

Client-to-server streaming

Additional resources



# Differences between ASP.NET SignalR and ASP.NET Core SignalR

Article • 06/18/2024


How to identify the SignalR version

Feature differences

Automatic reconnects

Protocol support

Transports

Differences on the server

Sticky sessions

Single hub per connection

Streaming

State

PersistentConnection removal

GlobalHost

HubPipeline

Differences on the client

TypeScript

The JavaScript client is hosted at npm

jQuery

Internet Explorer support

JavaScript client method syntax

Hub proxies

.NET and other clients

Scaleout differences

ASP.NET

ASP.NET Core

Additional resources



# WebSockets support in ASP.NET Core

Article • 09/17/2024


Http/2 WebSockets support

SignalR

Prerequisites

Configure the middleware

Accept WebSocket requests

Add HTTP/2 WebSockets support for existing controllers

Compression

Send and receive messages

Handle client disconnects

WebSocket origin restriction

IIS/IIS Express support

Enabling WebSockets on IIS

Disable WebSocket when using socket.io on Node.js

Sample app



# Logging and diagnostics in ASP.NET Core SignalR

Article • 06/18/2024


Server-side logging

Access server-side logs

As a console app outside IIS

Within IIS Express from Visual Studio

Azure App Service

Other environments

JavaScript client logging

.NET client logging

Console logging

Debug output window logging

Other logging providers

Control verbosity

Network traces

Collect a network trace with Fiddler (preferred option)

Collect a network trace with tcpdump (macOS and Linux only)

Collect a network trace in the browser

Microsoft Edge and Internet Explorer

Google Chrome

Mozilla Firefox

Attach diagnostics files to GitHub issues

Metrics

SignalR server metrics

Observe metrics

Additional resources



# Troubleshoot connection errors

Article • 06/18/2024


Response code 404

Response code 400 or 503

Response code 307

Response code 405

Response code 0

Response code 413

Transient network failures

Additional resources



# Overview for gRPC on .NET

Article • 07/31/2024


C# Tooling support for .proto files

gRPC services on ASP.NET Core

Add gRPC services to an ASP.NET Core app

The gRPC service project template

Call gRPC services with a .NET client

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



# gRPC services with C#

Article • 07/31/2024


proto file

Add a .proto file to a C# app

C# Tooling support for .proto files

Generated C# assets

Additional resources



# Create gRPC services and methods

Article • 07/31/2024


Create new gRPC services

Implement gRPC methods

Unary method

Server streaming method

Client streaming method

Bi-directional streaming method

Access gRPC request headers

Multi-threading with gRPC streaming methods

Reader and writer thread safety

Interacting with a gRPC method after a call ends

Additional resources



# Create Protobuf messages for .NET apps

Article • 09/27/2024


Protobuf messages

Scalar Value Types

Dates and times

Nullable types

Bytes

Decimals

Creating a custom decimal type for Protobuf

Collections

Lists

Dictionaries

Unstructured and conditional messages

Any

Oneof

Value

Additional resources



# Versioning gRPC services

Article • 09/27/2024


Backwards compatibility

Non-breaking changes

Binary breaking changes

Protocol breaking changes

Behavior breaking changes

Version number services

Additional resources



# Test gRPC services in ASP.NET Core

Article • 07/31/2024


Example testable service

Unit test gRPC services

Unit test HttpContext in gRPC methods

Integration test gRPC services

Inject mock dependencies

Additional resources



# Call gRPC services with the .NET client

Article • 07/31/2024


Configure gRPC client

Configure TLS

Client performance

Make gRPC calls

Unary call

Server streaming call

Client streaming call

Bi-directional streaming call

Access gRPC headers

Access gRPC trailers

Configure deadline

Additional resources



# gRPC client factory integration in .NET

Article • 07/31/2024


Register gRPC clients

Configure HttpHandler

Configure Interceptors

Configure Channel

Call credentials

Deadline and cancellation propagation

Named clients

Additional resources



# Reliable gRPC services with deadlines and cancellation

Article • 07/31/2024


Deadlines

Deadlines and retries

Propagating deadlines

Cancellation

Additional resources



# Transient fault handling with gRPC retries

Article • 07/31/2024


Transient fault handling

Configure a gRPC retry policy

When retries are valid

Streaming calls

Retry backoff delay

Detect retries with metadata

gRPC retry options

Hedging

Configure a gRPC hedging policy

gRPC hedging options

Additional resources



# gRPC client-side load balancing

Article • 07/31/2024


Configure gRPC client-side load balancing

Configure resolver

DnsResolverFactory

DNS address caching

StaticResolverFactory

Configure load balancer

Configure channel credentials

Use load balancing with gRPC client factory

Write custom resolvers and load balancers

Create a custom resolver

Create a custom load balancer

Configure custom resolvers and load balancers

Why load balancing is important

Proxy or client-side load balancing?

Additional resources



# Use gRPC client with .NET Standard 2.0

Article • 07/31/2024


.NET implementations

HttpHandler configuration

.NET Framework

gRPC C# core-library

Additional resources



# Mock gRPC client in tests

Article • 07/31/2024


Example testable client app

Mock a gRPC client

Additional resources



# gRPC services with ASP.NET Core

Article • 07/31/2024


Prerequisites

Get started with gRPC service in ASP.NET Core

Add gRPC services to an ASP.NET Core app

Configure gRPC

Server options

Kestrel

HTTP/2

TLS

Protocol negotiation

IIS

HTTP.sys

Host gRPC in non-ASP.NET Core projects

Integration with ASP.NET Core APIs

Resolve HttpContext in gRPC methods

Additional resources



# gRPC on .NET supported platforms

Article • 11/06/2024


Wire-formats

ASP.NET Core gRPC server requirements

Supported ASP.NET Core servers

Azure services

.NET gRPC client requirements

Additional resources



# Use gRPC in browser apps

Article • 07/31/2024


gRPC-Web

gRPC JSON transcoding

Additional resources



# gRPC-Web in ASP.NET Core gRPC apps

Article • 07/31/2024


ASP.NET Core gRPC-Web versus Envoy

Configure gRPC-Web in ASP.NET Core

gRPC-Web and CORS

gRPC-Web and streaming

HTTP protocol

Call gRPC-Web from the browser

JavaScript gRPC-Web client

Configure gRPC-Web with the .NET gRPC client

Use gRPC client factory with gRPC-Web

Additional resources



# gRPC JSON transcoding in ASP.NET Core

Article • 07/31/2024


Overview

Usage

Annotate gRPC methods

Streaming methods

HTTP protocol

gRPC JSON transcoding vs gRPC-Web

grpc-gateway

Additional resources



# Configure HTTP and JSON for gRPC JSON transcoding

Article • 07/31/2024


HTTP rules

HTTP method

Route

Request body

Query parameters

Response body

Specification

Customize JSON

Additional resources



# gRPC JSON transcoding documentation with Swagger / OpenAPI

Article • 09/23/2024


Get started

Add OpenAPI descriptions from .proto comments

Additional resources



# gRPC for .NET configuration

Article • 07/31/2024


Configure services options

ASP.NET Core server options

Configure client options

System.Net handler options

Additional resources



# Authentication and authorization in gRPC for ASP.NET Core

Article • 07/31/2024


Authenticate users calling a gRPC service

Bearer token authentication

Set the bearer token with CallCredentials

Bearer token with gRPC client factor

Client certificate authentication

Other authentication mechanisms

Authorize users to access services and service methods

Additional resources



# Error handling with gRPC

Article • 07/31/2024


Built-in error handling

Throw server errors

Server error status

Handle client errors

Error scenarios

Rich error handling

Creating rich errors on the server

Reading rich errors by a client

Additional resources



# gRPC interceptors on .NET

Article • 07/31/2024


Interceptor type

Client interceptors

Create a client gRPC interceptor

Awaiting response in client interceptor

Configure client interceptors

Server interceptors

Create a server gRPC interceptor

Configure server interceptors

gRPC Interceptors versus Middleware

Additional resources



# Logging and diagnostics in gRPC on .NET

Article • 07/31/2024


Logging

gRPC services logging

Sample logging output

Access server-side logs

As a console app

Other environments

gRPC client logging

gRPC client log scopes

Sample logging output

Tracing

gRPC service tracing

gRPC client tracing

Collecting tracing

Metrics

gRPC service metrics

gRPC client metrics

Observe metrics

Additional resources



# Security considerations in gRPC for ASP.NET Core

Article • 07/31/2024


Transport security

Exceptions

Message size limits

Client certificate validation



# Performance best practices with gRPC

Article • 10/04/2024


Reuse gRPC channels

Connection concurrency

ServerGarbageCollection in client apps

Load balancing

Client-side load balancing

Proxy load balancing

Inter-process communication

Keep alive pings

Flow control

Gracefully complete streaming calls

Dispose streaming calls

Replace unary calls with streaming

Binary payloads

Send binary payloads

Read binary payloads

gRPC services and large binary payloads



# gRPC and Native AOT

Article • 07/31/2024


Get started

Optimize publish size

Benefits of using Native AOT

Additional resources



# Inter-process communication with gRPC

Article • 07/31/2024


Get started

Inter-process communication (IPC) transports

Security considerations

Secure IPC server app against unexpected callers

Validate the server in the IPC client app

Protect against named pipe privilege escalation

Configure client and server



# Inter-process communication with gRPC and Unix domain sockets

Article • 07/31/2024


Prerequisites

Server configuration

Client configuration



# Inter-process communication with gRPC and Named pipes

Article • 07/31/2024


Prerequisites

Server configuration

Client configuration



# Code-first gRPC services and clients with .NET

Article • 11/05/2024


protobuf-net.Grpc

Create a code-first gRPC service

Create a code-first gRPC client

Additional resources



# gRPC health checks in ASP.NET Core

Article • 08/28/2024


Set up gRPC health checks

Health checks service security

Configure Grpc.AspNetCore.HealthChecks

Configure health checks execution interval

Call gRPC health checks service

Additional resources



# Manage Protobuf references with dotnet-grpc

Article • 07/31/2024


Installation

Add references

Add file

Usage

Arguments

Options

Add URL

Usage

Arguments

Options

Remove

Usage

Arguments

Options

Refresh

Usage

Arguments

Options

List

Usage

Options

Additional resources



# Test gRPC services with gRPCurl and gRPCui in ASP.NET Core

Article • 07/31/2024


Set up gRPC reflection

Reflection service security

gRPCurl

Use grpcurl

Discover services

Call gRPC services

gRPCui

Using grpcui

Additional resources



# Migrate gRPC from C-core to gRPC for .NET

Article • 07/31/2024


Platform support

Configure server and channel

Code generated services and clients

gRPC service implementation lifetime

Add a singleton service

Configure gRPC services options

Logging

HTTPS

gRPC Interceptors

Host gRPC in non-ASP.NET Core projects

Additional resources



# gRPC for Windows Communication Foundation (WCF) developers

Article • 07/31/2024


Comparison to WCF

Benefits of gRPC

Performance

Interoperability

Usability and productivity

Streaming

Deadlines, timeouts, and cancellation

Security

gRPC as a migration path for WCF to .NET Core and .NET 5

Get started



# Compare gRPC services with HTTP APIs

Article • 07/31/2024


High-level comparison

gRPC strengths

Performance

Code generation

Strict specification

Streaming

Deadline/timeouts and cancellation

gRPC recommended scenarios

gRPC weaknesses

Limited browser support

Not human readable

Alternative framework scenarios

Additional resources



# Troubleshoot gRPC on .NET

Article • 09/27/2024



# ASP.NET Core Best Practices

Article • 09/27/2024


Cache aggressively

Understand hot code paths

Avoid blocking calls

Return large collections across multiple smaller pages

Return IEnumerable<T> or IAsyncEnumerable<T>

Minimize large object allocations

Optimize data access and I/O

Pool HTTP connections with HttpClientFactory

Keep common code paths fast

Complete long-running Tasks outside of HTTP requests

Minify client assets

Compress responses

Use the latest ASP.NET Core release

Minimize exceptions

Avoid synchronous read or write on HttpRequest/HttpResponse body

Prefer ReadFormAsync over Request.Form

Avoid reading large request bodies or response bodies into memory

Working with a synchronous data processing API

Do not store IHttpContextAccessor.HttpContext in a field

Do not access HttpContext from multiple threads

Do not use the HttpContext after the request is complete

Do not capture the HttpContext in background threads

Do not capture services injected into the controllers on background threads

Do not modify the status code or headers after the response body has started

Do not call next() if you have already started writing to the response body

Use In-process hosting with IIS

Don't assume that HttpRequest.ContentLength is not null

Reliable web app patterns



# Web server implementations in ASP.NET Core

Article • 07/26/2024


Kestrel vs. HTTP.sys

Hosting models

Kestrel

Nginx with Kestrel

HTTP.sys

ASP.NET Core server infrastructure

Custom servers

Server startup

HTTP/2 support

Additional resources



# Kestrel web server in ASP.NET Core

Article • 07/26/2024


Get started

Optional client certificates

Behavior with debugger attached

Additional resources



# Configure endpoints for the ASP.NET Core Kestrel web server

Article • 07/26/2024


Default endpoint

Configure endpoints

Configure endpoints with URLs

URL formats

HTTPS URL prefixes

Specify ports only

Configure endpoints in appsettings.json

Reloading endpoints from configuration

ConfigurationLoader

Configure endpoints in code

Bind to a TCP socket

Bind to a Unix socket

Configure endpoint defaults

Dynamic port binding

Configure HTTPS

Configure HTTPS in appsettings.json

Schema notes

Certificate sources

Configure client certificates in appsettings.json

Configure SSL/TLS protocols in appsettings.json

Configure HTTPS in code

Configure client certificates in code

Configure HTTPS defaults in code

Configure SSL/TLS protocols in code

Configure TLS cipher suites filter in code

Configure Server Name Indication

Configure SNI in appsettings.json

Configure SNI with code

SNI with ServerCertificateSelector

SNI with ServerOptionsSelectionCallback

SNI with TlsHandshakeCallbackOptions

Configure HTTP protocols

Configure HTTP protocols in appsettings.json

Configure HTTP protocols in code

See also



# Configure options for the ASP.NET Core Kestrel web server

Article • 07/26/2024


General limits

Keep-alive timeout

Maximum client connections

Maximum request body size

Minimum request body data rate

Request headers timeout

HTTP/2 limits

Maximum streams per connection

Header table size

Maximum frame size

Maximum request header size

Initial connection window size

Initial stream window size

HTTP/2 keep alive ping configuration

Other options

Synchronous I/O

Behavior with debugger attached



# Diagnostics in Kestrel

Article • 07/26/2024


Logging

Connection logging

Metrics

DiagnosticSource

Behavior with debugger attached



# Use HTTP/2 with the ASP.NET Core Kestrel web server

Article • 07/26/2024


Advanced HTTP/2 features

Trailers

Reset



# Use HTTP/3 with the ASP.NET Core Kestrel web server

Article • 03/14/2024


HTTP/3 requirements

Windows

Linux

macOS

Getting started

Alt-svc

Localhost testing

HTTP/3 benefits



# Connection middleware

Article • 07/26/2024


Connection logging

Create custom connection middleware

See also



# When to use Kestrel with a reverse proxy

Article • 09/27/2024


Additional resources



# Host filtering with ASP.NET Core Kestrel web server

Article • 07/26/2024



# Request draining with ASP.NET Core Kestrel web server

Article • 07/26/2024



# Host ASP.NET Core on Windows with IIS

Article • 07/31/2024


Supported platforms

Install the ASP.NET Core Module/Hosting Bundle

Get started

Configuration

Deployment resources for IIS administrators

Overlapped recycle

Optional client certificates

Additional resources



# ASP.NET Core Module (ANCM) for IIS

Article • 09/27/2024


Install ASP.NET Core Module (ANCM)

Additional resources



# In-process hosting with IIS and ASP.NET Core

Article • 07/31/2024


Enable in-process hosting

General architecture

Application configuration

Differences between in-process and out-of-process hosting

Get timing information



# Out-of-process hosting with IIS and ASP.NET Core

Article • 07/31/2024


Application configuration

Enable the IISIntegration components

Proxy server and load balancer scenarios

Out-of-process hosting model

Process name



# The .NET Core Hosting Bundle

Article • 07/31/2024


Install the .NET Core Hosting Bundle

Direct download

Visual C++ Redistributable Requirement

Earlier versions of the installer

Options

Restart IIS

Module version and Hosting Bundle installer logs



# web.config file

Article • 07/31/2024


web.config file location

Configuration of ASP.NET Core Module with web.config

Attributes of the aspNetCore element

Set environment variables

Configuration of IIS with web.config

Configuration sections of web.config

Transform web.config

Additional resources



# Development-time IIS support in Visual Studio for ASP.NET Core

Article • 07/31/2024


Prerequisites

Enable IIS

Configure IIS

Configure the project

HTTPS redirection

IIS launch profile

Run the project

Additional resources



# IIS modules with ASP.NET Core

Article • 07/31/2024


Native modules

Managed modules

IIS Manager application changes

Disabling IIS modules

Module deactivation

Module removal

Minimum module configuration

Additional resources



# IIS log creation and redirection

Article • 07/31/2024


Enhanced diagnostic logs



# Troubleshoot ASP.NET Core on Azure App Service and IIS

Article • 09/27/2024


App startup errors

403.14 Forbidden

500 Internal Server Error

500.0 In-Process Handler Load Failure

500.30 In-Process Startup Failure

500.31 ANCM Failed to Find Native Dependencies

500.32 ANCM Failed to Load dll

500.33 ANCM Request Handler Load Failure

500.34 ANCM Mixed Hosting Models Not Supported

500.35 ANCM Multiple In-Process Applications in same Process

500.36 ANCM Out-Of-Process Handler Load Failure

500.37 ANCM Failed to Start Within Startup Time Limit

500.38 ANCM Application DLL Not Found

502.5 Process Failure

Failed to start application (ErrorCode '0x800700c1')

Failed to start application (ErrorCode '0x800701b1')

Connection reset

Default startup limits

Troubleshoot on Azure App Service

Azure App Services Log stream

Application Event Log (Azure App Service)

Run the app in the Kudu console

Test a 32-bit (x86) app

Test a 64-bit (x64) app

ASP.NET Core Module stdout log (Azure App Service)

ASP.NET Core Module debug log (Azure App Service)

Slow or nonresponsive app (Azure App Service)

Monitoring blades

Troubleshoot on IIS

Application Event Log (IIS)

Run the app at a command prompt

Framework-dependent deployment

Self-contained deployment

ASP.NET Core Module stdout log (IIS)

ASP.NET Core Module debug log (IIS)

Enable the Developer Exception Page

Obtain data from an app

Slow or non-responding app (IIS)

App crashes or encounters an exception

App doesn't respond, fails during startup, or runs normally

Analyze the dump

Clear package caches

Additional resources

Azure documentation

Visual Studio documentation

Visual Studio Code documentation



# Common error troubleshooting for Azure App Service and IIS with ASP.NET Core

Article • 07/31/2024


OS upgrade removed the 32-bit ASP.NET Core Module

Missing site extension, 32-bit (x86) and 64-bit (x64) site extensions installed, or wrong process bitness set

An x86 app is deployed but the app pool isn't enabled for 32-bit apps

Platform conflicts with RID

URI endpoint wrong or stopped website

CoreWebEngine or W3SVC server features disabled

Incorrect website physical path or app missing

Incorrect role, ASP.NET Core Module not installed, or incorrect permissions

Incorrect processPath, missing PATH variable, Hosting Bundle not installed, system/IIS not restarted, VC++ Redistributable not installed, or dotnet.exe access violation

Incorrect arguments of <aspNetCore> element

Missing .NET Core shared framework 

Stopped Application Pool

Sub-application includes a <handlers> section

stdout log path incorrect

Application configuration general issue



# Advanced configuration of the ASP.NET Core Module and IIS

Article • 09/27/2024


Modify the stack size

Disallow rotation on config

Reduce 503 likelihood during app recycle

Proxy configuration uses HTTP protocol and a pairing token

ASP.NET Core Module with an IIS Shared Configuration

Data protection

IIS configuration

Virtual Directories

Sub-applications

Application Pools

Application Pool Identity

HTTP/2 support

CORS preflight requests

Application Initialization Module and Idle Timeout

Application Initialization Module

Idle Timeout

Application Initialization Module and Idle Timeout additional resources

Module, schema, and configuration file locations

Module

Schema

Configuration

Install Web Deploy when publishing with Visual Studio

Create the IIS site

Shadow copy



# Transform web.config

Article • 07/31/2024


Build configuration

Profile

Environment

Custom

Prevent web.config transformation

Additional resources



# Use ASP.NET Core with HTTP/2 on IIS

Article • 07/31/2024


Advanced HTTP/2 features to support gRPC

Trailers

Reset



# Use ASP.NET Core with HTTP/3 on IIS

Article • 07/31/2024


Alt-Svc



# HTTP.sys web server implementation in ASP.NET Core

Article • 10/21/2024


When to use HTTP.sys

HTTP/2 support

HTTP/3 support

Kernel mode authentication with Kerberos

Support for kernel-mode response buffering

How to use HTTP.sys

Configure the ASP.NET Core app to use HTTP.sys

Configure Windows Server

Proxy server and load balancer scenarios

Get detailed timing information with IHttpSysRequestTimingFeature

Advanced HTTP/2 features to support gRPC

Trailers

Reset

Tracing

Additional resources



# .NET Hot Reload support for ASP.NET Core

Article • 04/10/2024


Blazor WebAssembly

.NET CLI

Disable Hot Reload

Additional resources



# How to use dev tunnels in Visual Studio 2022 with ASP.NET Core apps

Article • 11/06/2024


Use cases

Prerequisites

Create a tunnel

Specify the active tunnel

Use a tunnel

Use a tunnel to test on a phone or tablet

Dev Tunnels output window

Dev Tunnels tool window

Tunnel URL environment variables

Persistent versus temporary tunnels

See also



# Use .http files in Visual Studio 2022

Article • 07/23/2024


Prerequisites

.http file syntax

Requests

Request headers

Request body

Comments

Variables

Environment files

User-specific environment files

ASP.NET Core user secrets

Azure Key Vault

DPAPI encryption

Environment variables

.env files

Random integers

Dates and times

Unsupported syntax

Create an .http file

Send an HTTP request

.http file options

Use Endpoints Explorer

Open Endpoints Explorer

Add a request to an .http file

See also



# Test web APIs with the HttpRepl

Article • 07/28/2023


Prerequisites

Installation

Usage

Connect to the web API

Manually point to the OpenAPI description for the web API

Enable verbose output for details on OpenAPI description searching, parsing, and validation

Navigate the web API

View available endpoints

Navigate to an endpoint

Customize the HttpRepl

View the settings

Set color preferences

Set indentation size

Set the default text editor

Set the OpenAPI Description search paths

Test HTTP GET requests

Synopsis

Arguments

Options

Example

Test HTTP POST requests

Synopsis

Arguments

Options

Example

Test HTTP PUT requests

Synopsis

Arguments

Options

Example

Test HTTP DELETE requests

Synopsis

Arguments

Options

Example

Test HTTP PATCH requests

Synopsis

Arguments

Options

Test HTTP HEAD requests

Synopsis

Arguments

Options

Test HTTP OPTIONS requests

Synopsis

Arguments

Options

Set HTTP request headers

Test secured endpoints

Default credentials

Default proxy credentials

HTTP request headers

Toggle HTTP request display

Enable request display

Disable request display

Run a script

Clear the output

Additional resources



# HttpRepl telemetry

Article • 06/17/2024


How to opt out

Disclosure

Data points

Additional resources



# Unit and integration tests in Minimal API apps

Article • 07/26/2024


Introduction to integration tests

ASP.NET Core integration tests

IResult implementation types

Additional Resources



# Test Razor components in ASP.NET Core Blazor

Article • 03/08/2024


Test approaches

Choose the most appropriate test approach

Test components with bUnit

Additional resources



# Razor Pages unit tests in ASP.NET Core

Article • 09/17/2023


Message app organization

Test app organization

Unit tests of the data access layer (DAL)

Unit tests of the page model methods

Additional resources



# Unit test controller logic in ASP.NET Core

Article • 06/17/2024


Unit testing controllers

Test ActionResult<T>

Additional resources



# Integration tests in ASP.NET Core

Article • 06/17/2024


Introduction to integration tests

ASP.NET Core integration tests

Test app prerequisites

SUT environment

Basic tests with the default WebApplicationFactory

AngleSharp vs Application Parts for antiforgery checks

Customize WebApplicationFactory

Customize the client with WithWebHostBuilder

Client options

Inject mock services

Mock authentication

Basic tests for authentication middleware

Set the environment

How the test infrastructure infers the app content root path

Disable shadow copying

Disposal of objects

Integration tests sample

Message app (SUT) organization

Test app organization

Additional resources



# ASP.NET Core load/stress testing

Article • 03/07/2024


Third-party tools

Load and stress test with release builds



# Test ASP.NET Core middleware

Article • 01/11/2024


Set up the TestServer

Send requests with HttpClient

Send requests with HttpContext

Add request routes

TestServer limitations

Content-Length and Transfer-Encoding headers



# Debug .NET and ASP.NET Core source code with Visual Studio

Article • 09/18/2024


Debugging .NET Core on Unix over SSH

Additional resources



# Remote Debug ASP.NET Core on IIS using an Azure VM from Visual Studio

Article • 04/23/2024


Prerequisites

Network requirements

App already running in IIS on the Azure VM?

Create the ASP.NET Core application on the Visual Studio computer

Update browser security settings on Windows Server

Install ASP.NET Core on Windows Server

Choose a deployment option

(Optional) Deploy using a publish settings file

Configure the ASP.NET Core web site

Install and configure Web Deploy on Windows Server

Create the publish settings file in IIS on Windows Server

Import the publish settings in Visual Studio and deploy

(Optional) Deploy by publishing to a local folder

Configure the ASP.NET Core Web site on the Windows Server computer

(Optional) Publish and Deploy the app by publishing to a local folder from Visual Studio

Download and Install the remote tools on Windows Server

Set up the remote debugger on Windows Server

Attach to the ASP.NET Core application from the Visual Studio computer

Troubleshooting IIS deployment

Open required ports on Windows Server



# Debug exceptions in .NET applications using Snapshot Debugger

Article • 09/11/2024


Supported applications and environments

Applications

Environments

Prerequisites for using Snapshot Debugger

Packages and configurations

Permissions

How Snapshot Debugger works

Snapshot Debugger process

Snapshot Uploader process

Upgrading Snapshot Debugger

Overhead

Limitations



# Debug live ASP.NET Azure apps using the Snapshot Debugger

Article • 10/20/2022


Prerequisites

Open your project and start the Snapshot Debugger

Set a snappoint

Take a snapshot

Inspect snapshot data

Set a conditional snappoint

To create a conditional snappoint

Set a logpoint

To create a logpoint

Related content



# Use dev tunnels in Visual Studio to debug your web APIs

Article • 11/14/2023


Prerequisites

Step 1: Configure your ASP.NET Core project in Visual Studio

URL with and without dev tunnels

Step 2: Create a custom connector for your web API using the dev tunnel URL

Create a custom connector from scratch

Create a custom connector with API Management

Step 3: Add the custom connector to Power Apps or Power Automate

Provide feedback



# Troubleshoot and debug ASP.NET Core projects

Article • 09/17/2024


.NET Core SDK warnings

Both the 32-bit and 64-bit versions of the .NET Core SDK are installed

The .NET Core SDK is installed in multiple locations

No .NET Core SDKs were detected

Missing SDK after installing the .NET Core Hosting Bundle

Obtain data from an app

Debug ASP.NET Core apps



# Troubleshoot ASP.NET Core on Azure App Service and IIS

Article • 09/27/2024


App startup errors

403.14 Forbidden

500 Internal Server Error

500.0 In-Process Handler Load Failure

500.30 In-Process Startup Failure

500.31 ANCM Failed to Find Native Dependencies

500.32 ANCM Failed to Load dll

500.33 ANCM Request Handler Load Failure

500.34 ANCM Mixed Hosting Models Not Supported

500.35 ANCM Multiple In-Process Applications in same Process

500.36 ANCM Out-Of-Process Handler Load Failure

500.37 ANCM Failed to Start Within Startup Time Limit

500.38 ANCM Application DLL Not Found

502.5 Process Failure

Failed to start application (ErrorCode '0x800700c1')

Failed to start application (ErrorCode '0x800701b1')

Connection reset

Default startup limits

Troubleshoot on Azure App Service

Azure App Services Log stream

Application Event Log (Azure App Service)

Run the app in the Kudu console

Test a 32-bit (x86) app

Test a 64-bit (x64) app

ASP.NET Core Module stdout log (Azure App Service)

ASP.NET Core Module debug log (Azure App Service)

Slow or nonresponsive app (Azure App Service)

Monitoring blades

Troubleshoot on IIS

Application Event Log (IIS)

Run the app at a command prompt

Framework-dependent deployment

Self-contained deployment

ASP.NET Core Module stdout log (IIS)

ASP.NET Core Module debug log (IIS)

Enable the Developer Exception Page

Obtain data from an app

Slow or non-responding app (IIS)

App crashes or encounters an exception

App doesn't respond, fails during startup, or runs normally

Analyze the dump

Clear package caches

Additional resources

Azure documentation

Visual Studio documentation

Visual Studio Code documentation



# Common error troubleshooting for Azure App Service and IIS with ASP.NET Core

Article • 07/31/2024


OS upgrade removed the 32-bit ASP.NET Core Module

Missing site extension, 32-bit (x86) and 64-bit (x64) site extensions installed, or wrong process bitness set

An x86 app is deployed but the app pool isn't enabled for 32-bit apps

Platform conflicts with RID

URI endpoint wrong or stopped website

CoreWebEngine or W3SVC server features disabled

Incorrect website physical path or app missing

Incorrect role, ASP.NET Core Module not installed, or incorrect permissions

Incorrect processPath, missing PATH variable, Hosting Bundle not installed, system/IIS not restarted, VC++ Redistributable not installed, or dotnet.exe access violation

Incorrect arguments of <aspNetCore> element

Missing .NET Core shared framework

Stopped Application Pool

Sub-application includes a <handlers> section

stdout log path incorrect

Application configuration general issue



# Code analysis in ASP.NET Core apps

Article • 07/09/2024



# ASP0000: Do not call 'IServiceCollection.BuildServiceProvider' in 'ConfigureServices'

Article • 06/18/2024


Cause

Rule description

How to fix violations

When to suppress warnings



# ASP0001: Authorization middleware is incorrectly configured

Article • 06/18/2024


Cause

Rule description

How to fix violations

When to suppress warnings



# ASP0003: Do not use model binding attributes with route handlers

Article • 09/28/2022


Cause

Rule description

How to fix violations

When to suppress warnings



# ASP0004: Do not use action results with route handlers

Article • 09/28/2022


Cause

Rule description

How to fix violations

When to suppress warnings



# ASP0005: Do not place attribute on method called by route handler lambda

Article • 09/28/2022


Cause

Rule description

How to fix violations

When to suppress warnings



# ASP0006: Do not use non-literal sequence numbers

Article • 10/30/2022


Cause

Rule description

How to fix violations

When to suppress warnings



# ASP0007: Route parameter and argument optionality is mismatched

Article • 09/28/2022


Cause

Rule description

How to fix violations

When to suppress warnings



# ASP0008: Do not use ConfigureWebHost with WebApplicationBuilder.Host

Article • 09/28/2022


Cause

Rule description

How to fix violations

When to suppress warnings



# ASP0009: Do not use Configure with WebApplicationBuilder.WebHost

Article • 09/28/2022


Cause

Rule description

How to fix violations

When to suppress warnings



# ASP0010: Do not use UseStartup with WebApplicationBuilder.WebHost

Article • 06/18/2024


Cause

Rule description

How to fix violations

When to suppress warnings



# ASP0011: Suggest using builder.Logging over Host.ConfigureLogging or WebHost.ConfigureLogging

Article • 09/28/2022


Cause

Rule description

How to fix violations

When to suppress warnings



# ASP0012: Suggest using builder.Services over Host.ConfigureServices or WebHost.ConfigureServices

Article • 09/28/2022


Cause

Rule description

How to fix violations

When to suppress warnings



# ASP0013: Suggest switching from using Configure methods to WebApplicationBuilder.Configuration

Article • 02/13/2024


Cause

Rule description

How to fix violations

When to suppress warnings



# ASP0014: Suggest using top level route registrations

Article • 02/23/2023


Cause

Rule description

How to fix violations

When to suppress warnings



# ASP0015: Suggest using IHeaderDictionary properties

Article • 11/28/2022


Cause

Rule description

How to fix violations

When to suppress warnings



# ASP0016: Do not return a value from RequestDelegate

Article • 11/28/2022


Cause

Rule description

How to fix violations

When to suppress warnings



# ASP0017: Invalid route pattern

Article • 11/28/2022


Cause

Rule description

How to fix violations

When to suppress warnings



# ASP0018: Unused route parameter

Article • 06/20/2024


Cause

Rule description

How to fix violations

When to suppress warnings



# ASP0019: Suggest using IHeaderDictionary.Append or the indexer

Article • 11/28/2022


Cause

Rule description

How to fix violations

When to suppress warnings



# ASP0020: Complex types referenced by route parameters must be parsable

Article • 03/27/2023


Cause

Rule description

How to fix violations

When to suppress warnings



# ASP0021: The return type of the BindAsync method must be ValueTask<T>.

Article • 03/27/2023


Cause

Rule description

How to fix violations

When to suppress warnings



# ASP0022: Route conflict detected between route handlers

Article • 11/08/2023


Cause

Rule description

How to fix violations

When to suppress warnings

Notes



# ASP0023: Route conflict detected between route handlers

Article • 03/29/2023


Cause

Rule description

How to fix violations

When to suppress warnings

Notes



# ASP0024: Route handler has multiple parameters with the [FromBody] attribute

Article • 03/29/2023


Cause

Rule description

How to fix violations

When to suppress warnings



# ASP0025: Use AddAuthorizationBuilder to register authorization services and construct policies.

Article • 05/15/2023


Cause

Rule description

How to fix violations

When to suppress warnings



# ASP0026: [Authorize] is overridden by [AllowAnonymous] from "farther away"

Article • 07/09/2024


Cause

Rule description

How to fix violations

When to suppress warnings



# ASP0028: Consider using IPAddress.IPv6Any instead of IPAddress.Any

Article • 11/18/2024


Cause

Rule description

How to fix violations

When to suppress warnings



# BL0001: Component parameter should have public setters

Article • 06/03/2022


Cause

Rule description

How to fix violations

When to suppress warnings



# BL0002: Component has multiple CaptureUnmatchedValues parameters

Article • 06/03/2022


Cause

Rule description

How to fix violations

When to suppress warnings



# BL0003: Component parameter with CaptureUnmatchedValues has the wrong type

Article • 06/03/2022


Cause

Rule description

How to fix violations

When to suppress warnings



# BL0004: Component parameter should be public

Article • 06/03/2022


Cause

Rule description

How to fix violations

When to suppress warnings



# BL0005: Component parameter should not be set outside of its component

Article • 06/03/2022


Cause

Rule description

How to fix violations

When to suppress warnings



# BL0006: Do not use RenderTree types

Article • 06/03/2022


Cause

Rule description

How to fix violations

When to suppress warnings



# MVC1000: Use of IHtmlHelper.Partial should be avoided

Article • 06/03/2022


Cause

Rule description

How to fix violations

When to suppress warnings



# MVC1001: Filters cannot be applied to page handler methods

Article • 06/18/2024


Cause

Rule description

How to fix violations

When to suppress warnings



# MVC1002: Route attribute cannot be applied to page handler methods

Article • 06/18/2024


Cause

Rule description

How to fix violations

When to suppress warnings



# MVC1003: Route attributes cannot be applied to page models

Article • 06/18/2024


Cause

Rule description

How to fix violations

When to suppress warnings



# MVC1004: Rename model bound parameter

Article • 06/03/2022


Cause

Rule description

How to fix violations

When to suppress warnings



# MVC1005: Cannot use UseMvc with Endpoint Routing

Article • 06/03/2022


Cause

Rule description

How to fix violations

When to suppress warnings



# MVC1006: Methods containing TagHelpers must be async and return Task

Article • 06/18/2024


Cause

Rule description

How to fix violations

When to suppress warnings



# Razor Pages with Entity Framework Core in ASP.NET Core - Tutorial 1 of 8

Article • 09/27/2024


Prerequisites

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



# ASP.NET Core and Entity Framework 6

Article • 04/10/2024


Using Entity Framework 6 with ASP.NET Core

Additional resources



# Tutorial: Connect to SQL Database from .NET App Service without secrets using a managed identity

Article • 04/17/2024


Prerequisites

1. Grant database access to Microsoft Entra user

2. Set up your dev environment

3. Modify your project

4. Use managed identity connectivity

Enable managed identity on app

Grant permissions to managed identity

Modify connection string

5. Publish your changes

Clean up resources



# Adding Azure Storage by using Visual Studio Connected Services

Article • 10/31/2024


Prerequisites

Connect to Azure Storage using Connected Services

Understand authentication



# Quickstart: Azure Blob Storage client library for .NET

Article • 09/13/2024


Prerequisites

Setting up

Create the project

Install the package

Set up the app code

Object model

Code examples

Authenticate to Azure and authorize access to blob data

Create a container

Upload a blob to a container

List blobs in a container

Download a blob

Delete a container

The completed code

Run the code

Clean up resources

Azure Queue storage documentation

About Azure queues

Get started

Develop with queues

Manage queues

Tutorial



# What is Azure Table storage?

Article • 11/29/2022


What is Table storage

Table storage concepts



# Host and deploy ASP.NET Core

Article • 09/18/2024


Publish to a folder

Run the published app locally

Publish settings files

Folder contents

Set up a process manager

Set up a reverse proxy

Proxy server and load balancer scenarios

Use Visual Studio and MSBuild to automate deployments

Publish to Azure

Publish with MSDeploy on Windows

Internet Information Services (IIS)

Host in a web farm

Host on Docker

Perform health checks

Additional resources



# Deploy ASP.NET Core apps to Azure App Service

Article • 09/19/2024


Reliable web app patterns

Useful resources

Application configuration

Platform

Packages

Override app configuration using the Azure Portal

Proxy server and load balancer scenarios

Monitoring and logging

Data Protection key ring and deployment slots

Deploy an ASP.NET Core app that uses a .NET Core preview

Specify the .NET Core SDK Version using Azure Pipelines

Specify the .NET Core SDK version

Deploy a self-contained preview app

Use Docker with Web Apps for containers

Install the preview site extension

Publish and deploy the app

Deploy the app framework-dependent

Deploy the app self-contained

Protocol settings (HTTPS)

Transform web.config

Additional resources



# Publish an ASP.NET Core app to Azure with Visual Studio

Article • 11/01/2023


Set up

Create a web app

Run the app

Register a user

Deploy the app to Azure

Update the app

Clean up

Additional resources



# Tutorial: Deploy an ASP.NET Core and Azure SQL Database app to Azure App Service

Article • 09/06/2024


Prerequisites

Skip to the end

1. Run the sample

2. Create App Service, database, and cache

3. Secure connection secrets

4. Deploy sample code

5. Generate database schema

6. Browse to the app

7. Stream diagnostic logs

8. Clean up resources

Troubleshooting

The portal deployment view for Azure SQL Database shows a Conflict status

In the Azure portal, the log stream UI for the web app shows network errors

The SSH session in the browser shows SSH CONN CLOSED

The portal log stream page shows Connected! but no logs

Frequently asked questions

How much does this setup cost?

How do I connect to the Azure SQL Database server that's secured behind the virtual network with other tools?

How does local app development work with GitHub Actions?

How do I debug errors during the GitHub Actions deployment?

I don't have permissions to create a user-assigned identity

How do I change the SQL Database connection to use a managed identity instead?

What can I do with GitHub Copilot in my codespace?

Related content



# Create your first pipeline

Article • 04/03/2024


Azure DevOps Services | Azure DevOps Server 2022 - Azure DevOps Server 2019

Prerequisites - Azure DevOps

Create your first pipeline

Get the Java sample code

Create your first Java pipeline

View and manage your pipelines

View pipeline details

View pipeline run details

Jobs and stages

Cancel and re-run a pipeline

Pipeline run more actions menu

Add a status badge to your repository

Next steps

Clean up

FAQ

Where can I read articles about DevOps and CI/CD?

What version control system can I use?

How can I delete a pipeline?

What else can I do when I queue a build?

Where can I learn more about pipeline settings?

How do I programmatically create a build pipeline?



# ASP.NET Core Module (ANCM) for IIS

Article • 09/27/2024


Install ASP.NET Core Module (ANCM)

Additional resources



# Troubleshoot ASP.NET Core on Azure App Service and IIS

Article • 09/27/2024


App startup errors

403.14 Forbidden

500 Internal Server Error

500.0 In-Process Handler Load Failure

500.30 In-Process Startup Failure

500.31 ANCM Failed to Find Native Dependencies

500.32 ANCM Failed to Load dll

500.33 ANCM Request Handler Load Failure

500.34 ANCM Mixed Hosting Models Not Supported

500.35 ANCM Multiple In-Process Applications in same Process

500.36 ANCM Out-Of-Process Handler Load Failure

500.37 ANCM Failed to Start Within Startup Time Limit

500.38 ANCM Application DLL Not Found

502.5 Process Failure

Failed to start application (ErrorCode '0x800700c1')

Failed to start application (ErrorCode '0x800701b1')

Connection reset

Default startup limits

Troubleshoot on Azure App Service

Azure App Services Log stream

Application Event Log (Azure App Service)

Run the app in the Kudu console

Test a 32-bit (x86) app

Current release

Framework-dependent deployment running on a preview release

Test a 64-bit (x64) app

Current release

Framework-dependent deployment running on a preview release

ASP.NET Core Module stdout log (Azure App Service)

ASP.NET Core Module debug log (Azure App Service)

Slow or nonresponsive app (Azure App Service)

Monitoring blades

Troubleshoot on IIS

Application Event Log (IIS)

Run the app at a command prompt

Framework-dependent deployment

Self-contained deployment

ASP.NET Core Module stdout log (IIS)

ASP.NET Core Module debug log (IIS)

Enable the Developer Exception Page

Obtain data from an app

Slow or non-responding app (IIS)

App crashes or encounters an exception

App doesn't respond, fails during startup, or runs normally

Analyze the dump

Clear package caches

Additional resources

Azure documentation

Visual Studio documentation

Visual Studio Code documentation



# Common error troubleshooting for Azure App Service and IIS with ASP.NET Core

Article • 07/31/2024


OS upgrade removed the 32-bit ASP.NET Core Module

Missing site extension, 32-bit (x86) and 64-bit (x64) site extensions installed, or wrong process bitness set

An x86 app is deployed but the app pool isn't enabled for 32-bit apps

Platform conflicts with RID

URI endpoint wrong or stopped website

CoreWebEngine or W3SVC server features disabled

Incorrect website physical path or app missing

Incorrect role, ASP.NET Core Module not installed, or incorrect permissions

Incorrect processPath, missing PATH variable, Hosting Bundle not installed, system/IIS not restarted, VC++ Redistributable not installed, or dotnet.exe access violation

Incorrect arguments of <aspNetCore> element

Missing .NET Core shared framework

Stopped Application Pool

Sub-application includes a <handlers> section

stdout log path incorrect

Application configuration general issue



# Publish an ASP.NET Core app to IIS

Article • 07/01/2024


Prerequisites

Install the .NET Core Hosting Bundle

Create the IIS site

Create an ASP.NET Core Razor Pages app

Publish and deploy the app

Browse the website

Next steps

Additional resources

Articles in the ASP.NET Core documentation set

Articles pertaining to ASP.NET Core app deployment

Articles on IIS HTTPS configuration

Articles on IIS and Windows Server

Deployment resources for IIS administrators



# Host ASP.NET Core in a Windows Service

Article • 09/27/2024


Prerequisites

Worker Service template

App configuration

Deployment type

SDK

Framework-dependent deployment (FDD)

Self-contained deployment (SCD)

Service user account

Log on as a service rights

Create and manage the Windows Service

Create a service

Start a service

Determine a service's status

Stop a service

Remove a service

Proxy server and load balancer scenarios

Configure endpoints

Current directory and content root

Use ContentRootPath or ContentRootFileProvider

Store a service's files in a suitable location on disk

Troubleshoot

Common errors

System and Application Event Logs

Run the app at a command prompt

Clear package caches

Slow or unresponsive app

App crashes or encounters an exception

App is unresponsive, fails during startup, or runs normally

Analyze the dump

Additional resources



# Host ASP.NET Core on Linux with Nginx

Article • 03/14/2024


Prerequisites

Publish and copy over the app

Configure a reverse proxy server

Use a reverse proxy server

Install Nginx

Configure Nginx

Increase keepalive_requests

Monitor the app

Create the service file

View logs

Data protection

Long request header fields

Secure the app

Enable AppArmor

Configure the firewall

Secure Nginx

Change the Nginx response name

Configure options

HTTPS configuration

Secure Nginx from clickjacking

MIME-type sniffing

Additional Nginx suggestions

Additional resources



# Host ASP.NET Core in Docker containers

Article • 07/31/2024


System.IO.IOException: The configured user limit (128) on the number of inotify instances has been reached



# Run an ASP.NET Core app in Docker containers

Article • 07/31/2024


ASP.NET Core Docker images

Prerequisites

Download the sample app

Run the app locally

Run in a Linux container or Windows container

Build and deploy manually

The Dockerfile

Additional resources



# Visual Studio Container Tools with ASP.NET Core

Article • 07/31/2024


Prerequisites

Installation and setup

Add a project to a Docker container

New app

Existing app

Dockerfile overview

Add container orchestrator support to an app

Docker Compose

Service Fabric

Debug

Edit and continue

Publish Docker images

Additional resources



# Deploy an ASP.NET container to a container registry using Visual Studio

Article • 08/22/2024


Prerequisites

Create an ASP.NET Core web app

Publish your container to Azure Container Registry

Related content



# Configure ASP.NET Core to work with proxy servers and load balancers

Article • 09/27/2024


Forwarded headers

IIS/IIS Express and ASP.NET Core Module

Other proxy server and load balancer scenarios

Forwarded Headers Middleware order

Nginx configuration

Apache configuration

Forwarded Headers Middleware options

Scenarios and use cases

When it isn't possible to add forwarded headers and all requests are secure

Work with path base and proxies that change the request path

Configuration for a proxy that uses different header names

Forward the scheme for Linux and non-IIS reverse proxies

Certificate forwarding

Azure

Other web proxies

Troubleshoot

Additional resources



# Deploying and scaling an ASP.NET Core app on Azure Container Apps

Article • 09/18/2024


Set up the sample project

Test the app

Deploy the app to Azure Container Apps

Scale and troubleshoot the app

Troubleshooting the error

Create the Azure Services

Create the storage account service

Create the storage container

Create the key vault service

Create the key

Connect the Azure Services

Connect the storage account

Connect the key vault

Configure and redeploy the app

Redeploy the app

Configure roles for local development

Sign-in to your local development environment

Assign roles to your developer account

Reliable web app patterns



# Host ASP.NET Core in a web farm

Article • 09/18/2024


General configuration

App data

Required configuration

Data Protection

Caching

Dependent components

Troubleshoot

Data Protection and caching

Obtain data from apps

Additional resources



# Visual Studio publish profiles (.pubxml) for ASP.NET Core app deployment

Article • 11/26/2024


Compute project items

Basic command-line publishing

Publish profiles

Folder publish example

Publish to an MSDeploy endpoint from the command line

Set the environment

Exclude files

Include files

General file inclusion

Selective file inclusion

Run a target before or after publishing

Publish to a server using an untrusted certificate

The Kudu service

Additional resources



# ASP.NET Core directory structure

Article • 07/31/2024


Additional resources



# ASP.NET Core security topics

Article • 11/11/2024


ASP.NET Core security features

Authentication vs. Authorization

Common Vulnerabilities in software

Secure authentication flows

Additional resources



# Overview of ASP.NET Core authentication

Article • 02/14/2024


Authentication concepts

DefaultScheme

Authentication scheme

Authentication handler

RemoteAuthenticationHandler<TOptions> vs AuthenticationHandler<TOptions>

Authenticate

Challenge

Forbid

Authentication providers per tenant

Additional resources



# Choose an identity management solution

Article • 08/30/2023


Basic identity management with ASP.NET Core Identity

Determine if an OIDC server is needed

Disconnected scenarios

Decide where user data such as sign-ins are stored

Identity vs OIDC server



# Introduction to Identity on ASP.NET Core

Article • 08/30/2024


Create a Web app with authentication

Apply migrations

Test Register and Login

View the Identity database

Configure Identity services

Scaffold Register, Login, LogOut, and RegisterConfirmation

Examine Register

Disable default account verification

Log in

Log out

Test Identity

Explore Identity

Identity Components

Migrating to ASP.NET Core Identity

Setting password strength

AddDefaultIdentity and AddIdentity

Prevent publish of static Identity assets



# How to use Identity to secure a Web API backend for SPAs

Article • 09/10/2024


Prerequisites

Install NuGet packages

Create an IdentityDbContext

Configure the EF Core context

Add Identity services to the container

Activate Identity APIs

Map Identity routes

Secure selected endpoints

Test the API

Attempt to access a secured endpoint

Test registration

Test login

Retest the secured endpoint

Testing with nonbrowser clients

Use token-based authentication

Log out

The MapIdentityApi<TUser> endpoints

Use the POST /register endpoint

Use the POST /login endpoint

Token-based authentication

Use the POST /refresh endpoint

Use the GET /confirmEmail endpoint

Use the POST /resendConfirmationEmail endpoint

Use the POST /forgotPassword endpoint

Use the POST /resetPassword endpoint

Use the POST /manage/2fa endpoint

Enable 2FA

Log in with 2FA

Reset the recovery codes

Reset the shared key

Forget the machine

Use the GET /manage/info endpoint

Use the POST /manage/info endpoint

See also



# Scaffold Identity in ASP.NET Core projects

Article • 07/23/2024


Blazor Identity scaffolding

Razor Pages and MVC Identity scaffolding

Scaffold Identity into a Blazor project

Client-side Blazor apps (Standalone Blazor WebAssembly)

Scaffold Identity into a Razor project without existing authorization

Migrations, UseAuthentication, and layout

Layout changes

Scaffold Identity into a Razor project with authorization

Scaffold Identity into an MVC project with authorization

Create full Identity UI source

Password configuration

Disable a page

Use another app to add users

Prevent publish of static Identity assets



# Add, download, and delete custom user data to Identity in an ASP.NET Core project

Article • 05/31/2024


Prerequisites

Create a Razor web app

Run the Identity scaffolder

Add custom user data to the Identity DB

Add custom user data to the Identity DB

Update the Account/Register.cshtml page

Update the layout

Add a migration for the custom user data

Test create, view, download, delete custom user data



# Identity model customization in ASP.NET Core

Article • 10/30/2024


Identity and EF Core Migrations

The Identity model

Entity types

Entity type relationships

Default model configuration

Model generic types

Customize the model

Custom user data

Change the primary key type

Add navigation properties

Add all User navigation properties

Add User and Role navigation properties

Add all navigation properties

Use composite keys

Change table/column names and facets

Map to a different schema

Lazy loading

Additional resources



# Configure ASP.NET Core Identity

Article • 03/12/2024


Identity options

Claims Identity

Lockout

Password

Sign-in

Tokens

User

Cookie settings

Password Hasher options

Globally require all users to be authenticated

ISecurityStampValidator and SignOut everywhere



# Custom storage providers for ASP.NET Core Identity

Article • 10/30/2024


Introduction

The ASP.NET Core Identity architecture

ASP.NET Core Identity stores data types

Users

User Claims

User Logins

Roles

The data access layer

Context class

User Storage

Role Storage

UserClaims Storage

UserLogins Storage

UserRole Storage

Customize the user class

Customize the user store

Optional interfaces

Interfaces to implement when customizing user store

IdentityUserClaim, IdentityUserLogin, and IdentityUserRole

Customize the role class

Customize the role store

Reconfigure app to use a new storage provider

References



# Account confirmation and password recovery in ASP.NET Core

Article • 09/18/2024


Prerequisites

Create and test a web app with authentication

Register user with simulated email confirmation

Configure an email provider

Configure SendGrid user secrets

Install SendGrid

Implement IEmailSender

Configure app to support email

Disable default account verification when Account.RegisterConfirmation has been scaffolded

Register, confirm email, and reset password

Test password reset

Resend email confirmation

Change email and activity timeout

Change all data protection token lifespans

Change the email token lifespan

Debug email

Combine social and local login accounts

Enable account confirmation after a site has users



# Enable QR code generation for TOTP authenticator apps in ASP.NET Core

Article • 12/11/2024


Adding QR codes to the 2FA configuration page

Change the site name in the QR code

Using a different QR Code library

TOTP client and server time skew



# Facebook, Google, and external provider authentication in ASP.NET Core

Article • 09/05/2024


Create a New ASP.NET Core Project

Apply migrations

Forward request information with a proxy or load balancer

Use SecretManager to store tokens assigned by login providers

Setup login providers required by your application

Multiple authentication providers

Optionally set password

Additional information



# Google external login setup in ASP.NET Core

Article • 02/06/2024


Create the Google OAuth 2.0 Client ID and secret

Store the Google client ID and secret

Configure Google authentication

Sign in with Google

Forward request information with a proxy or load balancer

Multiple authentication providers

Change the default callback URI

Troubleshooting



# Facebook external login setup in ASP.NET Core

Article • 02/06/2024


Create the app in Facebook

Store the Facebook app ID and secret

Configure Facebook Authentication

Sign in with Facebook

React to cancel authorize external sign-in

Test AccessDeniedPath

Forward request information with a proxy or load balancer

Multiple authentication providers

Troubleshooting



# Microsoft Account external login setup with ASP.NET Core

Article • 06/03/2022


Create the app in Microsoft Developer Portal

Create client secret

Store the Microsoft client ID and secret

Configure Microsoft Account Authentication

Sign in with Microsoft Account

Multiple authentication providers

Forward request information with a proxy or load balancer

Troubleshooting



# Twitter external sign-in setup with ASP.NET Core

Article • 09/05/2024


Create the app in Twitter

Store the Twitter consumer API key and secret

Configure Twitter Authentication

Multiple authentication providers

Sign in with Twitter

Forward request information with a proxy or load balancer

Troubleshooting



# External OAuth authentication providers

Article • 09/05/2024


Multiple authentication providers

Forward request information with a proxy or load balancer



# Persist additional claims and tokens from external providers in ASP.NET Core

Article • 09/07/2023


Prerequisites

Set the client ID and client secret

Establish the authentication scope

Map user data keys and create claims

Save the access token

How to add additional custom tokens

Create and add claims

Add and update user claims

Remove claim actions and claims

Sample app output

Forward request information with a proxy or load balancer

Additional resources



# Articles based on ASP.NET Core projects created with individual user accounts

Article • 05/31/2024


No Authentication

Windows Authentication

dotnet new webapp authentication options

Visual Studio new webapp authentication options

Additional resources



# Microsoft Entra ID with ASP.NET Core

Article • 02/06/2024


Application Scenarios

Samples

Authentication and authorization for any app

Get started

Microsoft authentication libraries



# Authentication and authorization in Azure App Service and Azure Functions

Article • 09/27/2024


Why use the built-in authentication?

Identity providers

Considerations for using built-in authentication

How it works

Feature architecture

Feature architecture on Windows (non-container deployment)

Feature architecture on Linux and containers

Authentication flow

Authorization behavior

Token store

Logging and tracing

Cross-site request forgery mitigation

Considerations when using Azure Front Door

More resources



# Web app that signs in users: App registration

Article • 03/25/2024


Register an app by using the quickstarts

Register an app by using the Azure portal

Register an app by using PowerShell



# A web app that calls web APIs: App registration

Article • 10/23/2023


Add a client secret or certificate

Add client credentials by using the Azure portal

Add client credentials by using PowerShell

API permissions



# Protected web API: App registration

Article • 05/28/2024


Accepted token version

No redirect URI

Exposed API

Scopes and the Application ID URI

Expose delegated permissions (scopes)

If your web API is called by a service or daemon app

Expose application permissions (app roles)

Restrict access tokens to specific clients apps



# A web API that calls web APIs: App registration

Article • 10/23/2023


Add a client secret or certificate

Add client credentials by using the Azure portal

Add client credentials by using PowerShell

API permissions



# Cloud authentication with Azure Active Directory B2C in ASP.NET Core

Article • 10/25/2024


Prerequisites

Preparation

Modify the app

Modify the app



# Enable authentication in your own web API by using Azure AD B2C

Article • 01/11/2024


Prerequisites

Overview

Prerequisites

Overview

Step 1: Create a protected web API

Step 2: Install the dependencies

Step 3: Initiate the authentication library

Step 4: Add the endpoints

Step 5: Configure the web server

Step 6: Configure the web API

Step 7: Run and test the web API

Step 8: Call the web API from your app



# Use cookie authentication without ASP.NET Core Identity

Article • 04/25/2024


Add cookie authentication

Cookie Policy Middleware

Create an authentication cookie

Sign out

React to back-end changes

Persistent cookies

Absolute cookie expiration



# Configure OpenID Connect Web (UI) authentication in ASP.NET Core

Article • 12/02/2024


What is an OpenID Connect confidential interactive client

Create an Open ID Connect code flow client using Razor Pages

Add OpenID Connect support

Setup the OpenID Connect client

Setup the configuration properties

Update the ASP.NET Core pipeline method in the program class

Force authorization

Add a new Logout.cshtml and SignedOut.cshtml Razor page to the project

Implement Login Page

Add a login, logout button for the user

Examples with code snippets

Example Using User Info endpoint

Implementing Microsoft identity providers

Using third party OpenID Connect provider clients

Backend for frontend (BFF) security architecture

Advanced features, standards, extending the OIDC client

Logging

OIDC and OAuth Parameter Customization

Map claims from OpenID Connect

Blazor OpenID Connect

Standards



# Configure certificate authentication in ASP.NET Core

Article • 09/10/2024


Proxy and load balancer scenarios

Get started

Configure certificate validation

AllowedCertificateTypes = Chained, SelfSigned, or All (Chained | SelfSigned)

ChainTrustValidationMode

CustomTrustStore

ValidateCertificateUse

ValidateValidityPeriod

RevocationFlag

RevocationMode

Can I configure my app to require a certificate only on certain paths?

Handler events

Configure your server to require certificates

Kestrel

IIS

Azure and custom web proxies

Use certificate authentication in Azure Web Apps

Use certificate authentication in custom web proxies

Implement an HttpClient using a certificate and IHttpClientFactory

Create certificates in PowerShell

Create root CA

Install in the trusted root

Intermediate certificate

Create child certificate from intermediate certificate

Create child certificate from root certificate

Example root - intermediate certificate - certificate

Certificate validation caching

Optional client certificates

Separate Hosts (SNI)

Renegotiation

IIS

HttpSys

Kestrel



# Configure Windows Authentication in ASP.NET Core

Article • 09/12/2024


Proxy and load balancer scenarios

IIS/IIS Express

Launch settings (debugger)

IIS

Kestrel

Kerberos authentication and role-based access control (RBAC)

Windows environment configuration

Kerberos vs NTLM

Windows environment configuration

Kerberos vs NTLM

Linux and macOS environment configuration

HTTP.sys

Authorize users

Disallow anonymous access

Allow anonymous access

Impersonation

Claims transformations

Additional resources



# Authenticate users with WS-Federation in ASP.NET Core

Article • 06/18/2024


Register the app with Active Directory

Active Directory Federation Services

Microsoft Entra ID

Use WS-Federation without ASP.NET Core Identity

Add WS-Federation as an external login provider for ASP.NET Core Identity

Log in with WS-Federation



# Use social sign-in provider authentication without ASP.NET Core Identity

Article • 06/03/2022


Configuration

Apply authorization

Save the access token

Sign out

Additional resources



# Policy schemes in ASP.NET Core

Article • 06/03/2022


Examples



# Manage JSON Web Tokens in development with dotnet user-jwts

Article • 09/27/2024


Synopsis

Description

Arguments

Commands

Create

Examples

Create a JWT

Display JWT security information

Create a token for a specific user and scope



# Mapping, customizing, and transforming claims in ASP.NET Core

Article • 08/16/2024


Mapping claims using OpenID Connect authentication

Name claim and role claim mapping

Claims namespaces, default namespaces

Extend or add custom claims using IClaimsTransformation

Map claims from external identity providers



# Community OSS authentication options for ASP.NET Core

Article • 05/06/2024


OSS authentication providers [.NET]

OSS authentication provider clients [.NET]

Other OSS authentication providers



# Identity management solutions for .NET web apps

Article • 10/18/2024



# Multi-factor authentication in ASP.NET Core

Article • 10/30/2024


MFA, 2FA

MFA TOTP (Time-based One-time Password Algorithm)

MFA passkeys/FIDO2 or passwordless

MFA SMS

Configure MFA for administration pages using ASP.NET Core Identity

Extend the login with an MFA claim

Validate the MFA requirement in the administration page

UI logic to toggle user login information

Send MFA sign-in requirement to OpenID Connect server

OpenID Connect ASP.NET Core client

Example OpenID Connect Duende IdentityServer server with ASP.NET Core Identity

Force ASP.NET Core OpenID Connect client to require MFA

OIDC and OAuth Parameter Customization

Additional resources



# Introduction to authorization in ASP.NET Core

Article • 12/02/2024


Authorization types

Namespaces



# Create an ASP.NET Core web app with user data protected by authorization

Article • 10/04/2024


Prerequisites

The starter and completed app

The starter app

Secure user data

Tie the contact data to the user

Add Role services to Identity

Require authenticated users

Configure the test account

Create the test accounts and update the contacts

Create owner, manager, and administrator authorization handlers

Create a manager authorization handler

Create an administrator authorization handler

Register the authorization handlers

Support authorization

Review the contact operations requirements class

Create a base class for the Contacts Razor Pages

Update the CreateModel

Update the IndexModel

Update the EditModel

Update the DeleteModel

Inject the authorization service into the views

Update Details

Update the details page model

Add or remove a user to a role

Differences between Challenge and Forbid

Test the completed app

Create the starter app

Seed the database

Additional resources



# Razor Pages authorization conventions in ASP.NET Core

Article • 06/03/2022


Require authorization to access a page

Require authorization to access a folder of pages

Require authorization to access an area page

Require authorization to access a folder of areas

Allow anonymous access to a page

Allow anonymous access to a folder of pages

Note on combining authorized and anonymous access

Additional resources



# Simple authorization in ASP.NET Core

Article • 05/02/2024


Prerequisites

Use the [Authorize] attribute

Authorize attribute and Razor Pages



# Custom authorization policies with IAuthorizationRequirementData

Article • 06/16/2023



# Role-based authorization in ASP.NET Core

Article • 09/27/2024


Add Role services to Identity

Adding role checks

Policy based role checks



# Claims-based authorization in ASP.NET Core

Article • 11/10/2023


Adding claims checks

Add a generic claim check

Multiple Policy Evaluation



# Policy-based authorization in ASP.NET Core

Article • 08/08/2024


IAuthorizationService

Apply policies to MVC controllers

Apply policies to Razor Pages

Apply policies to endpoints

Requirements

Authorization handlers

Use a handler for one requirement

Use a handler for multiple requirements

Handler registration

What should a handler return?

Why would I want multiple handlers for a requirement?

Use a func to fulfill a policy

Access MVC request context in handlers

Globally require all users to be authenticated

Authorization with external service sample

Configure the sample

Additional resources



# Custom Authorization Policy Providers using IAuthorizationPolicyProvider in ASP.NET Core

Article • 06/03/2022


Customize policy retrieval

Parameterized authorize attribute example

Custom Authorization attributes

Custom IAuthorizationPolicyProvider

Multiple authorization policy providers

Default policy

Fallback policy

Use a custom IAuthorizationPolicyProvider



# Customize the behavior of AuthorizationMiddleware

Article • 06/03/2022



# Dependency injection in requirement handlers in ASP.NET Core

Article • 06/03/2022



# Resource-based authorization in ASP.NET Core

Article • 06/18/2024


Use imperative authorization

Write a resource-based handler

Operational requirements

Challenge and forbid with an operational resource handler



# View-based authorization in ASP.NET Core MVC

Article • 09/27/2024



# Authorize with a specific scheme in ASP.NET Core

Article • 06/03/2022


Selecting the scheme with the Authorize attribute

Selecting the scheme with policies

Use multiple authentication schemes



# ASP.NET Core Data Protection Overview

Article • 06/17/2024


Problem statement

Design philosophy

Audience

Package layout

Additional resources



# Get started with the Data Protection APIs in ASP.NET Core

Article • 06/17/2024


Use AddOptions to configure custom repository



# Consumer APIs overview for ASP.NET Core

Article • 06/17/2024


IDataProtectionProvider

IDataProtector

Consuming these interfaces

Console app

Web app



# Purpose strings in ASP.NET Core

Article • 06/17/2024



# Purpose hierarchy and multi-tenancy in ASP.NET Core

Article • 06/03/2022



# Hash passwords in ASP.NET Core

Article • 07/19/2022



# Limit the lifetime of protected payloads in ASP.NET Core

Article • 06/03/2022


API usage



# Unprotect payloads whose keys have been revoked in ASP.NET Core

Article • 09/27/2024


IPersistedDataProtector



# Data Protection configuration in ASP.NET Core

Article • 06/03/2022


Configure ASP.NET Core Data Protection

Data Protection key management and lifetime

Data Protection machine-wide policy support

Non-DI aware scenarios for Data Protection in ASP.NET Core



# Configure ASP.NET Core Data Protection

Article • 11/04/2024


ProtectKeysWithAzureKeyVault

PersistKeysToFileSystem

PersistKeysToDbContext

ProtectKeysWith*

UnprotectKeysWithAnyCertificate

SetDefaultKeyLifetime

SetApplicationName

DisableAutomaticKeyGeneration

Per-application isolation

Data Protection and app isolation

Changing algorithms with UseCryptographicAlgorithms

Specifying custom managed algorithms

Specifying custom Windows CNG algorithms

Specifying other custom algorithms

Persisting keys when hosting in a Docker container

Persisting keys with Redis

Logging DataProtection

Additional resources



# Data Protection key management and lifetime in ASP.NET Core

Article • 08/21/2024


Key management

Key lifetime

Default algorithms

Delete keys

Additional resources



# Data Protection machine-wide policy support in ASP.NET Core

Article • 06/17/2024


Setting default policy

Encryption types



# Non-DI aware scenarios for Data Protection in ASP.NET Core

Article • 06/17/2024



# ASP.NET Core Data Protection extensibility APIs

Article • 06/03/2022



# Core cryptography extensibility in ASP.NET Core

Article • 09/27/2024


IAuthenticatedEncryptor

How to create an IAuthenticatedEncryptor

IAuthenticatedEncryptorDescriptor (ASP.NET Core 2.x only)

XML Serialization

IAuthenticatedEncryptorDescriptorDeserializer

The top-level factory



# Key management extensibility in ASP.NET Core

Article • 02/06/2024


Key

IKeyManager

XmlKeyManager

IXmlRepository

IXmlEncryptor

IXmlDecryptor

IKeyEscrowSink



# Miscellaneous ASP.NET Core Data Protection APIs

Article • 06/03/2022


ISecret



# ASP.NET Core Data Protection implementation

Article • 06/03/2022


Authenticated encryption details

Subkey Derivation and Authenticated Encryption

Context headers

Key Management

Key Storage Providers

Key Encryption At Rest

Key immutability and settings

Key Storage Format

Ephemeral data protection providers



# Authenticated encryption details in ASP.NET Core

Article • 10/21/2024


Protected payload format



# Subkey derivation and authenticated encryption in ASP.NET Core

Article • 01/04/2023


Additional authenticated data and subkey derivation

CBC-mode encryption + HMAC validation

Galois/Counter Mode encryption + validation



# Context headers in ASP.NET Core

Article • 06/03/2022


Background and theory

CBC-mode encryption + HMAC authentication

Example: AES-192-CBC + HMACSHA256

Example: 3DES-192-CBC + HMACSHA1

Galois/Counter Mode encryption + authentication

Example: AES-256-GCM



# Key management in ASP.NET Core

Article • 09/27/2024


Default key selection

Key expiration and rolling

Automatic key ring refresh

Key storage



# Key storage providers in ASP.NET Core

Article • 10/30/2024


File system

Azure Storage

Redis

Registry

Entity Framework Core

Custom key repository



# Key encryption at rest in Windows and Azure using ASP.NET Core

Article • 03/17/2023


Azure Key Vault

Windows DPAPI

X.509 certificate

Windows DPAPI-NG

Certificate-based encryption with Windows DPAPI-NG

Custom key encryption



# Key immutability and key settings in ASP.NET Core

Article • 06/03/2022


The default key lifetime

The key encryption at rest mechanism

The algorithmic information contained within the key



# Key storage format in ASP.NET Core

Article • 10/21/2024


The <key> element

The <descriptor> element

The <encryptedSecret> element

The <revocation> element



# Ephemeral data protection providers in ASP.NET Core

Article • 02/28/2023



# Compatibility in ASP.NET Core

Article • 06/03/2022


Replacing ASP.NET <machineKey> in ASP.NET Core



# Replace the ASP.NET machineKey in ASP.NET Core

Article • 06/03/2022


Package installation

Package configuration



# Safe storage of app secrets in development in ASP.NET Core

Article • 11/04/2024


Environment variables

Secret Manager

How the Secret Manager tool works

Enable secret storage

Use the CLI

Use Visual Studio

If GenerateAssemblyInfo is false

Set a secret

JSON structure flattening in Visual Studio

Set multiple secrets

Access a secret

Register the user secrets configuration source

Read the secret via the Configuration API

Map secrets to a POCO

String replacement with secrets

List the secrets

Remove a single secret

Remove all secrets

Manage user secrets with Visual Studio

Migrating User Secrets from ASP.NET Framework to ASP.NET Core

User secrets in non-web applications

Additional resources



# Manage JSON Web Tokens in development with dotnet user-jwts

Article • 09/27/2024


Synopsis

Description

Arguments

Commands

Create

Examples

Create a JWT

Display JWT security information

Create a token for a specific user and scope



# Azure Key Vault configuration provider in ASP.NET Core

Article • 10/30/2024


Packages

Sample app

Secret storage in the Development environment

Secret storage in the Production environment with Azure Key Vault

Use Application ID and X.509 certificate for non-Azure-hosted apps

Use managed identities for Azure resources

Configuration options

Use a key name prefix

Bind an array to a class

Reload secrets

Disabled and expired secrets

Troubleshoot

Additional resources



# Enforce HTTPS in ASP.NET Core

Article • 10/25/2024


HTTP redirection to HTTPS causes ERR_INVALID_REDIRECT on the CORS preflight request

Require HTTPS

UseHttpsRedirection

Port configuration

Edge deployments

Deployment scenarios

Options

Configure permanent redirects in production

HTTPS Redirection Middleware alternative approach

HTTP Strict Transport Security Protocol (HSTS)

Opt-out of HTTPS/HSTS on project creation

Trust the ASP.NET Core HTTPS development certificate

How to set up a developer certificate for Docker

Linux-specific considerations

Dependencies

OpenSSL trust

Overrides

Using sudo

Trust HTTPS certificate on Linux with linux-dev-certs

Troubleshoot certificate problems such as certificate not trusted

All platforms - certificate not trusted

dotnet dev-certs https --clean Fails

Docker - certificate not trusted

Windows - certificate not trusted

OS X - certificate not trusted

Linux certificate not trusted

IIS Express SSL certificate used with Visual Studio

Group policy prevents self-signed certificates from being trusted

Additional information



# Hosting ASP.NET Core images with Docker over HTTPS

Article • 09/10/2024


Prerequisites

Certificates

Running pre-built container images with HTTPS

Windows using Linux containers

macOS or Linux

Windows using Windows containers

Developing ASP.NET Core Applications with Docker over HTTPS



# Hosting ASP.NET Core images with Docker Compose over HTTPS

Article • 09/10/2024


Prerequisites

Certificates

Starting a container with https support using docker compose

Windows using Linux containers

macOS or Linux

Windows using Windows containers



# EU General Data Protection Regulation (GDPR) support in ASP.NET Core

Article • 06/17/2024


Customize the cookie consent value

Encryption at rest

Additional resources



# Prevent Cross-Site Request Forgery (XSRF/CSRF) attacks in ASP.NET Core

Article • 10/21/2024


Authentication fundamentals

Cookie-based authentication

Token-based authentication

Multiple apps hosted at one domain

Antiforgery in ASP.NET Core

Antiforgery with AddControllers

Multiple browser tabs and the Synchronizer Token Pattern

Configure antiforgery with AntiforgeryOptions

Generate antiforgery tokens with IAntiforgery

Require antiforgery validation

Automatically validate antiforgery tokens for unsafe HTTP methods only

Override global or controller antiforgery attributes

Refresh tokens after authentication

JavaScript, AJAX, and SPAs

Blazor

JavaScript

Antiforgery with Minimal APIs

Windows authentication and antiforgery cookies

Extend antiforgery

Additional resources



# Prevent open redirect attacks in ASP.NET Core

Article • 09/27/2024


What is an open redirect attack?

An example attack

Protecting against open redirect attacks

LocalRedirect

IsLocalUrl



# Prevent Cross-Site Scripting (XSS) in ASP.NET Core

Article • 09/27/2024


Protecting your application against XSS

HTML Encoding using Razor

JavaScript Encoding using Razor

Accessing encoders in code

Encoding URL Parameters

Customizing the Encoders

Where should encoding take place?

Validation as an XSS prevention technique



# Enable Cross-Origin Requests (CORS) in ASP.NET Core

Article • 09/21/2024


Same origin

Enable CORS

CORS with named policy and middleware

UseCors and UseStaticFiles order

CORS with default policy and middleware

Enable Cors with endpoint routing

Enable CORS with attributes

Disable CORS

CORS policy options

Set the allowed origins

Set the allowed HTTP methods

Set the allowed request headers

Set the exposed response headers

Credentials in cross-origin requests

Preflight requests

Automatic preflight request code

[HttpOptions] attribute for preflight requests

Set the preflight expiration time

Enable CORS on an endpoint

How CORS works

HTTP redirection to HTTPS causes ERR_INVALID_REDIRECT on the CORS preflight request

CORS in IIS

Test CORS

Test CORS with [EnableCors] attribute and RequireCors method

Additional resources



# Share authentication cookies among ASP.NET apps

Article • 06/17/2024


Share authentication cookies with ASP.NET Core Identity

Share authentication cookies without ASP.NET Core Identity

Share cookies across different base paths

Share cookies across subdomains

Encrypt data protection keys at rest

Use a common user database

Application name change

Share authentication cookies between ASP.NET 4.x and ASP.NET Core apps

Additional resources



# Work with SameSite cookies in ASP.NET Core

Article • 06/17/2024


SameSite and Identity

SameSite test sample code

.NET Core support for the sameSite attribute

API usage with SameSite

History and changes

APIs impacted by the change from the 2016 SameSite draft standard to the 2019 draft standard

Supporting older browsers

Test apps for SameSite problems

Test with Chrome

Test with Safari

Test with Firefox

Test with Edge browser

Test with Edge (Chromium)

Test with Electron

Additional resources



# Client IP safelist for ASP.NET Core

Article • 10/25/2024


IP address safelist

Middleware

Action filter

Razor Pages filter

Additional resources



# ASP.NET Core performance

Article • 09/18/2024


ASP.NET Core Blazor performance best practices

ASP.NET Core Best Practices

Overview of caching in ASP.NET Core

Rate limiting middleware in ASP.NET Core

Memory management and patterns in ASP.NET Core

Scaling ASP.NET Core Apps on Azure

Object reuse with ObjectPool in ASP.NET Core

Response compression in ASP.NET Core

Performance Diagnostics Tools

ASP.NET Core load/stress testing

Request timeouts middleware in ASP.NET Core

Short-circuit middleware after routing



# Overview of caching in ASP.NET Core

Article • 05/21/2024


In-memory caching

Distributed Cache

HybridCache

Features

Compatibility

Additional resources

Response caching

Output caching

Cache Tag Helper

Distributed Cache Tag Helper



# Cache in-memory in ASP.NET Core

Article • 04/23/2024


System.Runtime.Caching/MemoryCache

Cache guidelines

Use IMemoryCache

MemoryCacheEntryOptions

Use SetSize, Size, and SizeLimit to limit cache size

MemoryCache.Compact

Cache dependencies

Additional notes

Background cache update

Additional resources



# Distributed caching in ASP.NET Core

Article • 10/04/2024


Prerequisites

IDistributedCache interface

Establish distributed caching services

Distributed Redis Cache

Distributed Memory Cache

Distributed SQL Server Cache

Distributed NCache Cache

Distributed Azure CosmosDB Cache

Reuse an existing client

Create a new client

Use the distributed cache

Recommendations

Additional resources



# HybridCache library in ASP.NET Core

Article • 12/02/2024


Get the library

Register the service

Get and store cache entries

The main GetOrCreateAsync overload

The alternative GetOrCreateAsync overload

The SetAsync method

Remove cache entries by key

Remove cache entries by tag

Options

Limits

Serialization

Cache storage

Optimize performance

Reuse objects

Avoid byte[] allocations

Custom HybridCache implementations

Compatibility

Additional resources



# Output caching middleware in ASP.NET Core

Article • 07/11/2024


Add the middleware to the app

Configure one endpoint or page

Configure multiple endpoints or pages

Default output caching policy

Override the default policy

Alternative default policy override

Specify the cache key

Cache revalidation

Use tags to evict cache entries

Disable resource locking

Limits

Cache storage

Redis cache

IDistributedCache not recommended



# Response caching in ASP.NET Core

Article • 04/10/2024


HTTP-based response caching

HTTP-based caching respects request Cache-Control directives

ResponseCache attribute

Vary

NoStore and Location.None

Location and Duration

Cache profiles

Additional resources



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



# Request timeouts middleware in ASP.NET Core

Article • 04/10/2024


Add the middleware to the app

Configure one endpoint or page

Configure multiple endpoints or pages

Set global default timeout policy

Specify the status code in a policy

Use a delegate in a policy

Disable timeouts

Cancel a timeout



# Memory management and garbage collection (GC) in ASP.NET Core

Article • 06/17/2024


How garbage collection (GC) works in .NET Core

GC.Collect caveats

Analyzing the memory usage of an app

Detecting memory issues

Sample display memory usage app

Transient objects

Workstation GC vs. Server GC

GC using Docker and small containers

Persistent object references

Native memory

Large object heap

HttpClient

Object pooling

Additional resources



# Deploying and scaling an ASP.NET Core app on Azure Container Apps

Article • 09/18/2024


Set up the sample project

Test the app

Deploy the app to Azure Container Apps

Scale and troubleshoot the app

Troubleshooting the error

Create the Azure Services

Create the storage account service

Create the storage container

Create the key vault service

Create the key

Connect the Azure Services

Connect the storage account

Connect the key vault

Configure and redeploy the app

Redeploy the app

Configure roles for local development

Sign-in to your local development environment

Assign roles to your developer account

Reliable web app patterns



# Object reuse with ObjectPool in ASP.NET Core

Article • 06/17/2024


ObjectPool concepts

How to use ObjectPool

ObjectPool sample



# Response compression in ASP.NET Core

Article • 07/01/2024


Compression with HTTPS

When to use Response Compression Middleware

Response compression

Configuration

Providers

Brotli and Gzip compression providers

Custom providers

MIME types

Adding the Vary header

Middleware issue when behind an Nginx reverse proxy

Disabling IIS dynamic compression

Troubleshoot response compression

Azure deployed sample

Additional resources



# Performance Diagnostic Tools

Article • 06/17/2024


Visual Studio Diagnostic Tools

Application Insights

PerfView

Windows Performance Toolkit

PerfCollect

Other Third-party Performance Tools



# ASP.NET Core load/stress testing

Article • 03/07/2024


Third-party tools

Load and stress test with release builds



# Tutorial: Measure performance using EventCounters in .NET Core

Article • 06/24/2023


Prerequisites

Get the source

Implement an EventSource

Add an action filter

Monitor event counter



# Globalization and localization in ASP.NET Core

Article • 10/25/2024


Terms

Language and country/region codes

Tasks to localize an app

Additional resources



# Make an ASP.NET Core app's content localizable

Article • 10/25/2024


IStringLocalizer

IHtmlLocalizer

IStringLocalizerFactory

Shared resources

View localization

DataAnnotations localization

How to use one resource string for multiple classes

Configure localization services

Next steps

Additional resources



# Provide localized resources for languages and cultures in an ASP.NET Core app

Article • 10/25/2024


SupportedCultures and SupportedUICultures

Resource files

Resource file naming

RootNamespaceAttribute

Culture fallback behavior

Generate resource files with Visual Studio

Add other cultures

Next steps

Additional resources



# Implement a strategy to select the language/culture for each request in a localized ASP.NET Core app

Article • 10/25/2024


Configure Localization middleware

QueryStringRequestCultureProvider

CookieRequestCultureProvider

The Accept-Language HTTP header

Set the Accept-Language HTTP header in Edge

The Content-Language HTTP header

Apply the RouteDataRequest CultureProvider

Use a custom provider

Change request culture providers order

User override culture

Set the culture programmatically

Model binding route data and query strings

Next steps

Additional resources



# Configure portable object localization in ASP.NET Core

Article • 08/07/2024


What is a PO file?

Example

Configuring PO file support in ASP.NET Core

Referencing the package

Registering the service

Creating a PO file

Testing the application

Pluralization

Creating pluralization PO files

Adding a language using different pluralization forms

Advanced tasks

Using additional arguments

Contextualizing strings

Changing the location of PO files

Implementing a custom logic for finding localization files

Using a different default pluralized language



# Localization Extensibility

Article • 07/26/2024


Extensible Points in Localization APIs

Localization Culture Providers

Use CustomRequestCultureProvider

Use a new implementation of RequestCultureProvider

Localization resources



# Troubleshoot ASP.NET Core localization

Article • 05/03/2024


Localization configuration issues

Resource file naming issues

Missing resources

Resources and class libraries issues

CustomRequestCultureProvider doesn't work as expected

Root namespace issues

Resources and build action

Location override using "Sensors" pane in developer tools

GitHub issues with helpful problem solving tips



# Model Binding in ASP.NET Core

Article • 09/27/2024


What is Model binding

Example

Targets

[BindProperty] attribute


[BindProperties] attribute

Model binding for HTTP GET requests

Model binding simple and complex types

Sources

[FromBody] attribute

Additional sources

No source for a model property

Type conversion errors

Simple types

Bind with IParsable<T>.TryParse

Bind with TryParse

Complex types

Prefix = parameter name

Prefix = property name

Custom prefix

Attributes for complex type targets

[Bind] attribute

[ModelBinder] attribute

[BindRequired] attribute

[BindNever] attribute

Collections

Dictionaries

Constructor binding and record types

POCOs without parameterless constructors

Record types with manually authored constructors

Record types, validation and binding metadata

Validation and metadata

TryUpdateModel does not update parameters on a record type

Globalization behavior of model binding route data and query strings

Special data types

IFormFile and IFormFileCollection

CancellationToken

FormCollection

Input formatters

Customize model binding with input formatters

Exclude specified types from model binding

Custom model binders

Manual model binding

[FromServices] attribute

Additional resources



# Custom Model Binding in ASP.NET Core

Article • 04/05/2024


Default model binder limitations

Model binding simple and complex types

Working with the ByteArrayModelBinder

Custom model binder sample

Implementing a ModelBinderProvider

Polymorphic model binding

Recommendations and best practices



# Model validation in ASP.NET Core MVC and Razor Pages

Article • 08/30/2024


Model state

Rerun validation

Validation attributes

Built-in attributes

Error messages

Use JSON property names in validation errors

Non-nullable reference types and [Required] attribute

[Required] validation on the server

[Required] validation on the client

[Remote] attribute

Additional fields

Alternatives to built-in attributes

Custom attributes

IValidatableObject

Custom validation

ValidationResult

Top-level node validation

Maximum errors

Maximum recursion

Automatic short-circuit

Client-side validation

Unobtrusive validation

Add Validation to Dynamic Forms

Add Validation to Dynamic Controls

Custom client-side validation

AttributeAdapter for client-side validation

IClientModelValidator for client-side validation

Disable client-side validation

Problem details

Additional resources



# Compatibility version for ASP.NET Core MVC

Article • 06/03/2022



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



# URL Rewriting Middleware in ASP.NET Core

Article • 07/26/2024


URL redirect and URL rewrite

URL rewriting sample app

When to use URL rewriting middleware

Extension and options

Redirect non-www to www

URL redirect

URL redirect to a secure endpoint

URL rewrite

Performance tips for URL rewrite and redirect

Apache mod_rewrite

IIS URL Rewrite Module rules

Unsupported features

Supported server variables

Method-based rule

IRule-based rule

Regex examples

Additional resources



# File Providers in ASP.NET Core

Article • 07/26/2024


File Provider interfaces

File Provider implementations

Physical File Provider

Manifest Embedded File Provider

Composite File Provider

Watch for changes

Glob patterns



# Request Features in ASP.NET Core

Article • 09/17/2024


Feature collections

Feature interfaces

Additional resources



# Access HttpContext in ASP.NET Core

Article • 07/26/2024


Access HttpContext from Razor Pages

Access HttpContext from a Razor view in MVC

Access HttpContext from a controller

Access HttpContext from minimal APIs

Access HttpContext from middleware

Access HttpContext from SignalR

Access HttpContext from gRPC methods

Access HttpContext from custom components

HttpContext access from a background thread

IHttpContextAccessor/HttpContext in Razor components (Blazor)



# Detect changes with change tokens in ASP.NET Core

Article • 07/26/2024


IChangeToken interface

ChangeToken class

Example uses of change tokens in ASP.NET Core

Monitor for configuration changes

Simple startup change token

Monitor configuration changes as a service

Monitor cached file changes

CompositeChangeToken class

Additional resources



# Open Web Interface for .NET (OWIN) with ASP.NET Core

Article • 12/02/2024


Running OWIN middleware in the ASP.NET Core pipeline

OWIN environment

OWIN keys

Request data (OWIN v1.0.0)

Request data (OWIN v1.1.0)

Response data (OWIN v1.0.0)

Other data (OWIN v1.0.0)

Common keys

SendFiles v0.3.0

Opaque v0.3.0

WebSocket v0.3.0

Additional resources



# Background tasks with hosted services in ASP.NET Core

Article • 05/31/2024


Worker Service template

Package

IHostedService interface

StartAsync

StopAsync

BackgroundService base class

Timed background tasks

Consuming a scoped service in a background task

Queued background tasks

Asynchronous timed background task

Native AOT

Additional resources



# Use hosting startup assemblies in ASP.NET Core

Article • 07/26/2024


HostingStartup attribute

Discover loaded hosting startup assemblies

Disable automatic loading of hosting startup assemblies

Project

Class library

Console app without an entry point

Configuration provided by the hosting startup

Specify the hosting startup assembly

Activation

Runtime store

NuGet package

Project bin folder

Sample code



# Use ASP.NET Core APIs in a class library

Article • 06/18/2024


Determine which ASP.NET Core versions to support

Use the ASP.NET Core shared framework

Include Blazor extensibility

Support server-side and client-side apps

Support multiple framework versions

Only support server-side consumption

Include MVC extensibility

Razor views or Razor Pages

Tag Helpers

View components

Support multiple ASP.NET Core versions

Use an API that hasn't changed

Use an API that changed

Use an API introduced in 3.1

Use an API removed from the shared framework

Additional resources



# Microsoft.AspNetCore.App for ASP.NET Core

Article • 07/26/2024



# Microsoft.AspNetCore.All metapackage for ASP.NET Core 2.0

Article • 07/26/2024


Implicit versioning

Migrating from Microsoft.AspNetCore.All to Microsoft.AspNetCore.App

Update ASP.NET Core 2.1



# High-performance logging in .NET

Article • 04/11/2024


Define a logger message

Define logger message scope

Log level guarded optimizations

See also



# Develop ASP.NET Core apps using a file watcher

Article • 05/31/2024


Run .NET CLI commands using dotnet watch

Make changes with dotnet watch

Run tests using dotnet watch

Customize files list to watch

Opt-out of files to be watched

Custom watch projects

dotnet-watch configuration

Browser refresh

Non-ASCII characters



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



# Migrate from ASP.NET Core in .NET 8 to ASP.NET Core in .NET 9

Article • 11/06/2024


Prerequisites

Update the .NET SDK version in global.json

Update the target framework

Update package references

Replace UseStaticFiles with MapStaticAssets

Blazor

Adopt simplified authentication state serialization for Blazor Web Apps

Additional resources



# Migrate from ASP.NET Core in .NET 7 to .NET 8

Article • 10/25/2024


Prerequisites

Update the .NET SDK version in global.json

Update the target framework

Update package references

Blazor

Update a Blazor Server app

Adopt all Blazor Web App conventions

Convert a Blazor Server app into a Blazor Web App

Update a Blazor WebAssembly app

Convert a hosted Blazor WebAssembly app into a Blazor Web App

Update service and endpoint option configuration

Drop Blazor Server with Yarp routing workaround

Migrate CascadingValue components in layout components

Migrate the BlazorEnableCompression MSBuild property

Migrate the <CascadingAuthenticationState> component to cascading authentication state services

New article on HTTP caching issues

New article on class libraries with static server-side rendering (static SSR)

Discover components from additional assemblies

Drop [Parameter] attribute when the parameter is supplied from a query string

Blazor Server script fallback policy authorization

Docker

Update Docker images

Update Docker port

Review breaking changes



# Migrate from ASP.NET Core 6.0 to 7.0

Article • 11/16/2024


Prerequisites

Update .NET Core SDK version in global.json

Update the target framework

Update package references

Blazor

Adopt .NET 7 features

Simplify component parameter binding

Migrate unmarshalled JavaScript interop

Blazor WebAssembly authentication uses history state for redirects

.NET WebAssembly build tools for .NET 6 projects

Update Docker images

Review breaking changes



# Migrate from ASP.NET Core 5.0 to 6.0

Article • 10/18/2024


Prerequisites

Update .NET SDK version in global.json

Update the target framework

Update package references

New hosting model

Apps migrating to or using 6.0 and later don't need to use the new minimal hosting model

Use Startup with the new minimal hosting model

Differences between the ASP.NET Core 5 and 6 hosting models

Building libraries for ASP.NET Core 6

Frequently asked questions (FAQ)

Blazor

Migrating SPA projects

Migrating Angular apps from SPA extensions

Migrating React apps from SPA extensions

Update Docker images

Changes to the ASP.NET Core Razor SDK

Project templates use Duende Identity Server

Code samples migrated to ASP.NET Core 6.0

Review breaking changes

Nullable reference types (NRTs) and .NET compiler null-state static analysis

ASP.NET Core Module (ANCM)

Application name change

Additional resources



# Code samples migrated to the new minimal hosting model in ASP.NET Core 6.0

Article • 07/14/2023


Middleware

Routing

Change the content root, app name, and environment

ASP.NET Core 5

ASP.NET Core 6

Change the content root, app name, and environment by environment variables or command line

Add configuration providers

ASP.NET Core 5

ASP.NET Core 6

Add logging providers

ASP.NET Core 5

ASP.NET Core 6

Add services

ASP.NET Core 5

ASP.NET Core 6

Customize IHostBuilder or IWebHostBuilder

Customize IHostBuilder

ASP.NET Core 5

ASP.NET Core 6

Customize IWebHostBuilder

ASP.NET Core 5

ASP.NET Core 6

Change the web root

ASP.NET Core 5

ASP.NET Core 6

Custom dependency injection (DI) container

ASP.NET Core 5

ASP.NET Core 6

Access additional services

ASP.NET Core 5

ASP.NET Core 6

Test with WebApplicationFactory or TestServer

ASP.NET Core 5

WebApplicationFactory

TestServer

ASP.NET Core 5 code

With TestServer

With WebApplicationFactory

ASP.NET Core 6

Project file (.csproj)



# Migrate from ASP.NET Core 3.1 to 6.0

Article • 06/04/2022


Prerequisites

Update .NET SDK version in global.json

Update the target framework

Update package references

Delete bin and obj folders

Minimal hosting model

Update Razor class libraries (RCLs)

Blazor

Update Docker images

Model binding changes in ASP.NET Core MVC and Razor Pages

DateTime values are model bound as UTC times

ComplexObjectModelBinderProvider\ ComplexObjectModelBinder replace ComplexTypeModelBinderProvider\ComplexTypeModelBinder

UseDatabaseErrorPage obsolete

ASP.NET Core Module (ANCM)

Application name change

Review breaking changes



# Migrate from ASP.NET Core 3.1 to 5.0

Article • 10/08/2024


Prerequisites

Update .NET Core SDK version in global.json

Update the target framework

Delete bin and obj folders

Changes to Blazor app routing logic in 5.0.1 and further 5.x releases up to 6.0

Old behavior

New behavior

Reason for change

Recommended action

Update Blazor WebAssembly and Blazor Server projects

Update Blazor WebAssembly projects

Standalone Blazor WebAssembly app with Microsoft Accounts

Standalone Blazor WebAssembly app with Microsoft Entra ID (ME-ID)

Standalone Blazor WebAssembly app with Azure Active Directory (AAD) B2C

Hosted Blazor WebAssembly app with Microsoft Entra ID (ME-ID) or AAD B2C

Update the Server project of a hosted Blazor solution

Clean and rebuild the solution

Troubleshoot

Unauthorized client for Microsoft Entra ID (ME-ID)

Update a Blazor Progressive Web Application (PWA)

Remove preview CSS isolation stylesheet link

Update Razor class libraries (RCLs)

Update package references

Update Docker images

Model binding changes in ASP.NET Core MVC and Razor Pages

DateTime values are model bound as UTC times

ComplexObjectModelBinderProvider\ComplexObjectModelBinder replace ComplexTypeModelBinderProvider\ComplexTypeModelBinder

UseDatabaseErrorPage obsolete

ASP.NET Core Module (ANCM)

Package reference changes affecting some NuGet packages

Migrate Microsoft.Identity.Web

Review breaking changes



# Migrate from ASP.NET Core 3.0 to 3.1

Article • 06/18/2024


Prerequisites

Update .NET Core SDK version in global.json

Update the target framework

Update package references

Update Docker images

React to SameSite cookie changes

Publish with Visual Studio

Review breaking changes

Optional changes

Use the Component Tag Helper

ASP.NET Core Module (ANCM)



# Migrate from ASP.NET Core 2.2 to 3.0

Article • 08/30/2024


Prerequisites

Update .NET Core SDK version in global.json

Update the project file

Update the Target Framework

Remove obsolete package references

Review breaking changes

Framework reference

Framework-dependent builds using Docker

Add package references for removed assemblies

Startup changes

Analyzer support

Razor class library

In-process hosting model

Kestrel

Configuration

Connection Middleware replaces Connection Adapters

Transport abstractions moved and made public

Kestrel Request trailer headers

AllowSynchronousIO disabled

Output formatter buffering

Microsoft.AspNetCore.Server.Kestrel.Https assembly removed

Newtonsoft.Json (Json.NET) support

Use Newtonsoft.Json in an ASP.NET Core 3.0 SignalR project

Use Newtonsoft.Json in an ASP.NET Core 3.0 MVC project

MVC service registration

Routing startup code

Migrate Startup.Configure

Health Checks

Security middleware guidance

CORS

Authorization

Authorization for specific endpoints

Custom authorization handlers

SignalR

SignalR assemblies in shared framework

MVC controllers

Async suffix removal from controller action names

Changes to link generation

Razor Pages

Use MVC without Endpoint Routing

Health checks

HostBuilder replaces WebHostBuilder

AddAuthorization moved to a different assembly

Identity UI

SignalR

System.Text.Json is the default protocol

Switch to Newtonsoft.Json

Redis distributed caches

Opt in to runtime compilation

Migrate libraries via multi-targeting

Miscellaneous changes

Publish

TestServer

Breaking API changes

Endpoint routing with catch-all parameter

.NET Core 3.0 on Azure App Service

ASP.NET Core Module (ANCM)



# Migrate from ASP.NET Core 2.1 to 2.2

Article • 06/18/2024


Prerequisites

Update Target Framework Moniker (TFM)

Adopt the IIS in-process hosting model

Update a custom web.config file

Update package references

Update .NET Core SDK version in global.json

Update launch settings

Update Kestrel configuration

Update compatibility version

Update CORS policy

Update Docker images

Build manually in Visual Studio when using IIS in-process hosting

Update logging code

ASP.NET Core Module (ANCM)

Additional resources



# Migrate from Microsoft.Extensions.Logging 2.1 to 2.2 or 3.0

Article • 06/03/2022


2.1 to 2.2

2.1 to 3.0

Additional resources



# Migrate from ASP.NET Core 2.0 to 2.1

Article • 08/30/2024


Update the project file to use 2.1 versions

Rules for projects targeting the shared framework

Update to the 2.1 Docker images

Changes to take advantage of the new code-based idioms that are recommended in ASP.NET Core 2.1

Changes to Main

Changes to Startup

Changes to authentication code

Update Identity to version 2.1

Replace Identity 2.0 UI with the Identity 2.1 Razor class library

Update after scaffolding Identity

Changes to Razor Pages projects Razor files

The layout file

_ValidationScriptsPartial.cshtml

New files

Changes to MVC projects Razor files

The layout file

_ValidationScriptsPartial.cshtml

New files and action methods

Changes to the launchSettings.json file

Breaking changes

FileResult Range header

ControllerBase.File and PhysicalFile Range header

ASP.NET Core Module (ANCM)

Additional changes



# Migrate from ASP.NET Core 1.x to 2.0

Article • 06/18/2024


Prerequisites

Update Target Framework Moniker (TFM)

Update .NET Core SDK version in global.json

Update package references

Update .NET CLI tools

Rename Package Target Fallback property

Update Main method in Program.cs

Add configuration providers

Move database initialization code

Review Razor view compilation setting

Rely on Application Insights "light-up" features

Adopt authentication/Identity improvements

Additional resources



# Migrate authentication and Identity to ASP.NET Core 2.0

Article • 06/18/2024


Update namespaces

Authentication Middleware and services

Cookie-based authentication

JWT Bearer Authentication

OpenID Connect (OIDC) authentication

Facebook authentication

Google authentication

Microsoft Account authentication

Twitter authentication

Setting default authentication schemes

Use HttpContext authentication extensions

Windows Authentication (HTTP.sys/IISIntegration)

IdentityCookieOptions instances

Add IdentityUser POCO navigation properties

Replace GetExternalAuthenticationSchemes

ManageLoginsViewModel property change

Additional resources



# Upgrade from ASP.NET Framework to ASP.NET Core

Article • 04/13/2023


Why upgrade to the latest .NET

ASP.NET Framework update approaches

Reliable web app patterns

URI decoding differences between ASP.NET to ASP.NET Core

Migrating User Secrets from ASP.NET Framework to ASP.NET Core



# Incremental ASP.NET to ASP.NET Core update

Article • 01/11/2024


App migration to ASP.NET Core

System.Web Adapters

Additional Resources



# Get started with incremental ASP.NET to ASP.NET Core migration

Article • 01/11/2024


Set up ASP.NET Core Project

Upgrade supporting libraries

Enable Session Support

Enable shared authentication support

General Usage Guidance



# System.Web adapters

Article • 01/11/2024


ASP.NET Framework

ASP.NET Core

See also



# Remote app setup

Article • 01/11/2024


Configuration

ASP.NET app configuration

ASP.NET Core app

Securing the remote app connection



# Usage Guidance

Article • 08/30/2024


HttpContext lifetime

Conversion to HttpContext

CurrentCulture is not set by default

CurrentPrincipal

Request thread does not exist in ASP.NET Core

Request may need to be prebuffered

Response may require buffering

Shared session state

Remote session exposes additional endpoint for application

Virtual directories must be identical for framework and core applications



# Wrapped ASP.NET Core session state

Article • 01/11/2024



# ASP.NET to ASP.NET Core incremental session state migration

Article • 01/11/2024


Session State

Serialization

Implementations



# ASP.NET to ASP.NET Core incremental IHttpModule migration

Article • 03/23/2024


IHttpModule Example

Global.asax migration

Authentication/Authorization events

HTTP Module pooling

Additional resources



# Remote app session state

Article • 01/11/2024


HttpSessionState serialization

Configuration

Protocol

Readonly

Writeable



# Remote Authentication

Article • 01/11/2024


Configuration

ASP.NET app configuration

ASP.NET Core app configuration

Design

Known limitations

Alternatives



# Unit Testing

Article • 01/11/2024



# A/B Testing endpoints during migration

Article • 01/11/2024


Conditional endpoint selection



# Upgrade from ASP.NET MVC and Web API to ASP.NET Core MVC

Article • 07/18/2023


Upgrade using the .NET Upgrade Assistant

Incremental update



# Upgrade an ASP.NET Framework Web Forms app to ASP.NET Core MVC

Article • 01/18/2024


Incremental update



# Migrate from ASP.NET Web API to ASP.NET Core

Article • 06/18/2024


Prerequisites

Create the new ASP.NET Core Web API project

Remove the WeatherForecast template files

The configuration for ASP.NET Core Web API

Copy the Product model

Copy the ProductsController

Routing

Routing in the migrated ProductsController

Additional resources



# Migrate configuration to ASP.NET Core

Article • 10/04/2024


Setup configuration

Migrate configuration settings from web.config

Summary



# Migrate Authentication and Identity to ASP.NET Core

Article • 10/30/2024


Configure Identity and Membership

Migrate registration and login logic

Summary



# Migrate from ClaimsPrincipal.Current

Article • 06/18/2024


Context-specific state instead of static state

Retrieve the current user in an ASP.NET Core app



# Migrate from ASP.NET Membership authentication to ASP.NET Core 2.0 Identity

Article • 10/30/2024


Review of Membership schema

ASP.NET Core Identity 2.0 schema

Migrate the schema

Users

Roles

User Roles

Next steps



# Migrate HTTP handlers and modules to ASP.NET Core middleware

Article • 03/23/2024


Modules and handlers revisited

From handlers and modules to middleware

Migrating module code to middleware

Migrating module insertion into the request pipeline

Migrating handler code to middleware

Migrating handler insertion into the request pipeline

Loading middleware options using the options pattern

Loading middleware options through direct injection

Migrating to the new HttpContext

HttpContext

HttpContext.Request

HttpContext.Response

Additional resources