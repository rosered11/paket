# paket

## Install and restore Paket in local

```
dotnet new tool-manifest
dotnet tool install paket
dotnet tool restore
```

## Initialize Paket by creating a dependencies file

```
dotnet paket init
```

## Add all packages for used

update in file `paket.dependencies`

## Add Create file paket.references per-project

create file `paket.references` and set the packages use in project

## Install package in paket.dependencies

```
dotnet paket install
```

## Update Paket

```
dotnet paket update
```
