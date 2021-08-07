# Typescript Client Generator

This will by default auto generate a Javascript gRPC client stub along with the protobuf contracts and `.d.ts` Typescript definition files in your `$(SpaRoot)` folder.

## Configuration

```msbuild
<Project>
    <PropertyGroup>
        <GrpcTypescriptOutDir>$(SpaRoot)src\Generated\grpc\</GrpcTypescriptOutDir>
    </PropertyGroup>
</Project>
```

By default the Output Directory is set to `$(SpaRoot)src\Generated\grpc\`. However you can override this with the above MsBuild snippet.