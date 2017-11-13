# IdentityServer4 Demo

IdentityServer4 implementation for testing purposes

## Supported Flows

- ClientCredentials (hardcoded)
- OpenID Connect Implicit Flow (hardcoded)

## Running

### Docker

- ``docker run --rm -p 8080:80 robyvandamme/identityserver4-demo``

### Local (requires .NET Core 2.0 SDK)

- ``git clone``
- ``dotnet restore``
- ``dotnet run --server.urls=http://localhost:8080``

## Users

- alice - password
- bob - password

## Setup

- dotnet new web
- dotnet add package IdentityServer4
- dotnet new -i identityserver4.templates (installs the is4 templates)
- dotnet new is4ui
- ...
