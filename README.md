# ViaCEP SDK .NET

A .NET client wrapper for both .NET Core & .NET Framework projects of [Via CEP API](https://viacep.com.br)

[![GitHub license](https://img.shields.io/github/license/guibranco/ViaCep-SDK-dotnet)](https://github.com/guibranco/ViaCep-SDK-dotnet)
[![time tracker](https://wakatime.com/badge/github/guibranco/ViaCep-SDK-dotnet.svg)](https://wakatime.com/badge/github/guibranco/ViaCEP-SDK-dotnet)

![Via CEP](https://raw.githubusercontent.com/guibranco/ViaCEP-SDK-dotnet/main/logo.png)

## CI/CD

| Build status | Last commit | Tests | Coverage | Code Smells | LOC |
|--------------|-------------|-------|----------|-------------|-----|
| [![Build status](https://ci.appveyor.com/api/projects/status/9jnsy1e08jhyxl7j/branch/main?svg=true)](https://ci.appveyor.com/project/guibranco/ViaCep-SDK-dotnet) | [![GitHub last commit](https://img.shields.io/github/last-commit/guibranco/ViaCEP-SDK-dotnet/main)](https://github.com/guibranco/ViaCep-SDK-dotnet) | [![AppVeyor tests (branch)](https://img.shields.io/appveyor/tests/guibranco/ViaCEP-SDK-dotnet/main?compact_message)](https://ci.appveyor.com/project/guibranco/ViaCep-SDK-dotnet) | [![Coverage](https://sonarcloud.io/api/project_badges/measure?project=guibranco_ViaCEP-SDK-dotnet&metric=coverage)](https://sonarcloud.io/dashboard?id=guibranco_ViaCep-SDK-dotnet) | [![Code Smells](https://sonarcloud.io/api/project_badges/measure?project=guibranco_ViaCEP-SDK-dotnet&metric=code_smells)](https://sonarcloud.io/dashboard?id=guibranco_ViaCep-SDK-dotnet) | [![Lines of Code](https://sonarcloud.io/api/project_badges/measure?project=guibranco_ViaCEP-SDK-dotnet&metric=ncloc)](https://sonarcloud.io/dashboard?id=guibranco_ViaCep-SDK-dotnet)

## Code Quality

[![Codacy Badge](https://app.codacy.com/project/badge/Grade/483c4901f0ea4a0d99e69be931ced362)](https://www.codacy.com/gh/guibranco/ViaCEP-SDK-dotnetdashboard?utm_source=github.com\&utm_medium=referral\&utm_content=guibranco/ViaCEP\&utm_campaign=Badge_Grade)
[![Codacy Badge](https://app.codacy.com/project/badge/Coverage/483c4901f0ea4a0d99e69be931ced362)](https://www.codacy.com/gh/guibranco/ViaCEP-SDK-dotnetdashboard?utm_source=github.com\&utm_medium=referral\&utm_content=guibranco/ViaCEP\&utm_campaign=Badge_Grade)

[![codecov](https://codecov.io/gh/guibranco/ViaCEP-SDK-dotnetbranch/main/graph/badge.svg)](https://codecov.io/gh/guibranco/ViaCep-SDK-dotnet)
[![CodeFactor](https://www.codefactor.io/repository/github/guibranco/viacep-sdk-dotnet/badge)](https://www.codefactor.io/repository/github/guibranco/viacep-sdk-dotnet)

[![Maintainability](https://api.codeclimate.com/v1/badges/93ba8c7ae3e86ca7e2a7/maintainability)](https://codeclimate.com/github/guibranco/ViaCEP-SDK-dotnetmaintainability)
[![Test Coverage](https://api.codeclimate.com/v1/badges/93ba8c7ae3e86ca7e2a7/test_coverage)](https://codeclimate.com/github/guibranco/ViaCEP-SDK-dotnettest_coverage)

[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=guibranco_ViaCEP-SDK-dotnet&metric=alert_status)](https://sonarcloud.io/dashboard?id=guibranco_ViaCEP)
[![Maintainability Rating](https://sonarcloud.io/api/project_badges/measure?project=guibranco_ViaCEP-SDK-dotnet&metric=sqale_rating)](https://sonarcloud.io/dashboard?id=guibranco_ViaCEP)

[![Technical Debt](https://sonarcloud.io/api/project_badges/measure?project=guibranco_ViaCEP-SDK-dotnet&metric=sqale_index)](https://sonarcloud.io/dashboard?id=guibranco_ViaCEP)
[![Duplicated Lines (%)](https://sonarcloud.io/api/project_badges/measure?project=guibranco_ViaCEP-SDK-dotnet&metric=duplicated_lines_density)](https://sonarcloud.io/dashboard?id=guibranco_ViaCEP)

[![Reliability Rating](https://sonarcloud.io/api/project_badges/measure?project=guibranco_ViaCEP-SDK-dotnet&metric=reliability_rating)](https://sonarcloud.io/dashboard?id=guibranco_ViaCEP)
[![Security Rating](https://sonarcloud.io/api/project_badges/measure?project=guibranco_ViaCEP-SDK-dotnet&metric=security_rating)](https://sonarcloud.io/dashboard?id=guibranco_ViaCEP)

[![Bugs](https://sonarcloud.io/api/project_badges/measure?project=guibranco_ViaCEP-SDK-dotnet&metric=bugs)](https://sonarcloud.io/dashboard?id=guibranco_ViaCEP)
[![Vulnerabilities](https://sonarcloud.io/api/project_badges/measure?project=guibranco_ViaCEP-SDK-dotnet&metric=vulnerabilities)](https://sonarcloud.io/dashboard?id=guibranco_ViaCEP)

[![DeepSource](https://app.deepsource.com/gh/guibranco/ViaCep-SDK-dotnet.svg/?label=active+issues\&show_trend=true\&token=84Hhxk-J1hIHiVC_ojm17J3q)](https://app.deepsource.com/gh/guibranco/ViaCEP-SDK-dotnet?ref=repository-badge)

---

## Installation

### Github Releases

[![GitHub last release](https://img.shields.io/github/release-date/guibranco/ViaCep-SDK-dotnet.svg?style=flat)](https://github.com/guibranco/ViaCep-SDK-dotnet) [![Github All Releases](https://img.shields.io/github/downloads/guibranco/ViaCEP-SDK-dotnet/total.svg?style=flat)](https://github.com/guibranco/ViaCep-SDK-dotnet)

Download the latest zip file from the [Release](https://github.com/GuiBranco/ViaCEP-SDK-dotnet/releases) page.

### Nuget package manager

| Package | Version | Downloads |
|------------------|:-------:|:-------:|
| **ViaCEP** | [![ViaCEP NuGet Version](https://img.shields.io/nuget/v/ViaCep.svg?style=flat)](https://www.nuget.org/packages/ViaCEP) | [![ViaCEP NuGet Downloads](https://img.shields.io/nuget/dt/ViaCep.svg?style=flat)](https://www.nuget.org/packages/ViaCEP) |

---

## Usage

The package has two classes:

*   [ViaCepClient](https://github.com/guibranco/ViaCEP-SDK-dotnetblob/main/ViaCEP-SDK-dotnetViaCepClient.cs): The main class (methods).
*   [ViaCepResult](https://github.com/guibranco/ViaCEP-SDK-dotnetblob/main/ViaCEP-SDK-dotnetViaCepResult.cs): The result class (data).

This package is fully compatible with Dependency Injection. Use the interface *IViaCepClient* and the constructor with an HttpClient parameter and an IHttpClientFactory instance.

```cs
//your DI container
services.AddHttpClient<IViaCepClient, ViaCepClient>(client => { client.BaseAddress = new Uri("https://viacep.com.br/"); });

//then use in your domain service, handler, controller...
var viaCepClient = container.GetService<IViaCepClient>();
var result = await viaCepClient.SearchAsync("01001000", cancellationToken);
```

You can search using the zip code/postal code (AKA CEP) or the address data (state initials - UF, city name, and location name - street, avenue, park, square). Both methods support async and sync!

### Querying by zip code / postal code (single result)

```cs
var result = new ViaCepClient().Search("01001000"); //searches for the postal code 01001-000
var address = result.Address; //Praça da Sé
var city = reuslt.City; //São Paulo
//do what you need with 'result' instance of ViaCEPResult.
```

### Querying by address (list result)

```cs
var results = new ViaCepClient().Search("SP", "São Paulo", "Avenida Paulista"); //search for the Avenida Paulista in São Paulo / SP
foreach(var result in results){
    var address = result.Address;
    var neighborhood = result.Neighborhood;
    var zipCode = result.ZipCode;
    //do what you need with 'result' instance of ViaCEPResult.
}
```

## Changelog

*   2026-03-23: Bump to .NET 10.0 - Release version 5.0
*   2024-09-02: Add explicitly support to .NET 6.0 and .NET 8.0 [#154](https://github.com/guibranco/ViaCEP-SDK-dotnetissues/154) by [@guibranco](https://github.com/guibranco)
*   2023-07-28: Add integration tests [#71](https://github.com/guibranco/ViaCEP-SDK-dotnetissues/71) by [@Riju-bak](https://github.com/Riju-bak)
*   2023-03-03: Update dependencies, change branch name, update logo. [@guibranco](https://github.com/guibranco)
*   2021-06-21: Update dependencies version. [@guibranco](https://github.com/guibranco)
*   2020-10-23: Support .NET Standard 2.0 and .NET Framework v4.6.1 and above. [@guibranco](https://github.com/guibranco)
