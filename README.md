# Blazor DataGrid - RemoteSaveAdaptor with CRUD

This example shows that how to bind local data and perform CRUD at server by using RemoteSaveAdaptor.

You may need to perform all Grid Actions (like paging, filtering, sorting) in client-side except the CRUD operations, that should be interacted with server-side to persist data. It can be achieved in Grid by using **RemoteSaveAdaptor**.

Datasource must be set to **json** property and set **RemoteSaveAdaptor** to the **adaptor** property. CRUD operations can be mapped to server-side using **insertUrl**, **updateUrl**, **removeUrl** properties.

## Prerequisites

* Visual Studio 2022 or later
* Visual Studio Code

## How to run the project

1. Clone or download this repository to a location in your system.
2. Open the solution file using the Visual Studio or Visual Studio code.
3. Restore the NuGet packages by rebuilding the solution or run `dotnet restore`.
4. Build the project to ensure there are no compilation errors.
5. Run the project.

Optional CLI Commands:

```powershell
dotnet restore
dotnet build
```

## References

**Documentation**: https://blazor.syncfusion.com/documentation/datagrid/data-binding/remote-data

**Online example**: https://blazor.syncfusion.com/demos/datagrid/remote-data?theme=bootstrap5