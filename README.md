# Package Demo

The purpose of this repository is to demonstrate packaging .NET and Node.js code as reusable packages as well as how to package a containerized application.

The workflow files is located in the `.github/workflows` directory.

## .NET

The .NET code is a simple class library that outputs "Hello World!" when called. The code is located in the `GitHubTest.Lib` directory.

The workflow file is located at `.github/workflows/dotnet-package.yml`.

## Node.js

The Node.js code is a simple application that outputs "Hello World!" to the onsole. The code is located in the `root` directory.

The workflow file is located at `.github/workflows/node-package.yml`.

## Container

The containerized application is a simple ASP.NET Core web application. The code is located in the `PackageGS` directory.

The workflow file is located at `.github/workflows/docker-package.yml`.

## Releases

The release is a .zip file containing the packaged Node.js code.

The release is located in the root folder as filename `package-1.0.zip`.
