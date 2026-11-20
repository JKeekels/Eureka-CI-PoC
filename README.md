Eureka CI/CD Proof of Concept

Objective

Evaluate TeamCity as a CI/CD solution for .NET 10 Windows Forms applications.



This project is inspired by the technical architecture of Eureka.



No production source code is included.



Technology

C#

.NET 10

Windows Forms

x64

Git

TeamCity

Local Build

Restore dependencies:



dotnet restore Eureka-CI-PoC.sln -p:Platform=x64



Build the application:



dotnet build Eureka-CI-PoC.sln -c Release -p:Platform=x64 --no-restore



CI/CD Goals

Automatic build after Git push

Automated tests

Build artifact generation

Deployment to a test environment

Status

Local build: Completed

GitHub integration: Completed

TeamCity integration: Pending

Automated testing: Pending

Deployment: Pending

