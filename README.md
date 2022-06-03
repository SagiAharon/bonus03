# bonus03

--------- Part 1 -------------------------------------------------------------------

* Create “ASP.NET Core Web App” project = i opened a new APS.NET core web app. 
* Check your csproj content = When I checked the file this is what appeared: 
  <PropertyGroup>
    <TargetFramework>netcoreapp3.1</TargetFramework>
  </PropertyGroup>
  
* Add “Newtonsoft.Json” = I installed a package of nuget from Visual studio.  
* Check your csproj again, what changed? = A new ItemGroup has been created:   
  <ItemGroup>
    <PackageReference Include="Newtonsoft.Json" Version="13.0.1" />
  </ItemGroup>

* Restore Nuget Packages = I was restored the Nuget Packages.

* Compile (rebuild) your project = Compiled. 

* Which files and folders were created? = I did not notice any changes. 

* Publish your application = publish and work. 


--------- Part 2 --------------------------------------------------------------

* Add IIS to your windows server == I went into the server and installed IIS on it.

* Create a new IIS application pool = I Create one.

* Create website (use port 5100 and your new application pool) = I Create one in the IIS console

* I could not finish the rest on time.

@ I hope this is what you meant by "explaining the build and installation process"

