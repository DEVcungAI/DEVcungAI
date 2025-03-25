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



# 