# External Links

- **<http://www.orthogonal.com.au>** — Greg's personal web site (Azure App Service)
- **<https://www.orthogonal.net.au>** — Greg's software development and testing site (Azure VM)
- **<http://gfkeogh.blogspot.com.au>** — Greg's software development blog
- **[https://www.nuget.org](https://www.nuget.org/packages?q=gfkeogh)** — Greg's Nuget Packages
- **<http://www.quintic.com.au>** — *Reserved for future use*
- **<http://www.quintic.net.au>** — *Reserved for future use*

# Public Repositories

###### *All of the following projects/applications are free of copyright restrictions. The author Greg Keogh <gfkeogh@gmail.com> has published them in the public domain in case it they have educational value or assist the productivity of other software developers. Please send bug reports, suggestions or enhancements to the author.*

**Library**

- [NSettings](https://github.com/gfkeogh/NSettings) — *A lightweight settings persistence library backed by the Registry or an XML file.* ([Documentation][docnset])
- [NTagLite](https://github.com/gfkeogh/NTagLite) — *A lightweight ID3 tagging library.* ([Documentation][docntag])
- [Common](https://github.com/gfkeogh/Common) — *Miscellaneous C# utility classes.* ([Documentation][doccomm])
- [LiteComms](https://github.com/gfkeogh/LiteComms) — *A lightweight client-server communications library.*  ([Documentation][doccomms])
- [ObjectDb](https://github.com/gfkeogh/ObjectDb) — *A lightweight high-performance high-capacity Object database backed by [ESENT][esent].* ([Documentation][docobjdb])

**Desktop**

- [Cirrus](https://github.com/gfkeogh/Cirrus) — *Manages Rackspace Cloud Files.*
- [Dumpenv](https://github.com/gfkeogh/DumpEnv) — *Dumps interesting environmental information.*
- [DuplicateScan](https://github.com/gfkeogh/DuplicateScan) — *Scans for duplicate files.*
- [EsentWorkbench](https://github.com/gfkeogh/EsentWorkbench) — *Manages ESENT (Extensible Storage Engine) databases.* ([Documentation][docesent])
- [HashGen](https://github.com/gfkeogh/HashGen) — *Calculates hash values using a variety of algorithms.*
- [HashStrings](https://github.com/gfkeogh/HashStrings) — *Plots string hash code distributions.* (See [Hashing Short Strings](http://www.orthogonal.com.au/computers/hashstrings/))
- [NugetXref](https://github.com/gfkeogh/NugetXref) — *Displays a sortable grid of project and Nuget package relationships.*
- [NetLibXref](https://github.com/gfkeogh/NetLibXref) — *Uses reflection to display a cross-reference of library dependencies.*
- [Randgen](https://github.com/gfkeogh/RandGen) — *Generates random data in a variety of ways.*
- [RandPlot](https://github.com/gfkeogh/RandPlot) — *Plots the output distribution from many types of random number generators.*
- [ResExtract](https://github.com/gfkeogh/ResExtract) — *Extracts icons from executable image files.*
- [Scanex](https://github.com/gfkeogh/Scanex) — *Scans executable image files and displays their properties in a grid.*
- [TagSheet](https://github.com/gfkeogh/TagSheet) — *Bulk edit ID3 tags in a grid.*

**Command Line**

- [encr](https://github.com/gfkeogh/encr) — *Encrypts files to-and-from a custom self-describing format.*
- [ngrep](https://github.com/gfkeogh/ngrep) — *Searches files for text matching regular expressions.*

**Sample Code**

- [UdpDemo](https://github.com/gfkeogh/UdpDemo) — *How to use the UdpClient class for decoupled broadcasting and receiving.* (See [BLOG](https://gfkeogh.blogspot.com/2019/01/udp-broadcasting-sample.html))
- [CodePackDriver](https://github.com/gfkeogh/CodePackDriver) — *How to use the TaskDialog class.* (See [BLOG](https://gfkeogh.blogspot.com.au/2017/02/taskdialog-windows-api-code-pack.html))
- [CsCompile](https://github.com/gfkeogh/CsCompile) — *Dynamically compile and execute C# code at runtime.* (See [BLOG](http://gfkeogh.blogspot.com.au/2014/07/dynamic-c-code-compilation.html))
- [RegKeySecurity](https://github.com/gfkeogh/RegKeySecurity) — *Create a Registry key and set custom ACL permissions.* (See [BLOG](http://gfkeogh.blogspot.com.au/2015/03/registry-secrets-and-permissions.html))
- [SampleEncryption](https://github.com/gfkeogh/SampleEncryption) — *Implement a symmetric encryption algorithm.* (See [BLOG](http://gfkeogh.blogspot.com.au/2014/04/implementing-symmetricalgorithm.html))
- [primecalc](https://github.com/gfkeogh/primecalc) — *Generates pages of Lehmer's 1914 book [List of Prime Numbers from 1 to 10,006,721](http://www.orthogonal.com.au/lehmer/).*

**Silverlight**

###### Note that Silverlight is a deprecated Microsoft platform, so the following apps only work correctly in later versions of Internet Explorer (see [System Requirements][slcompat]). Microsoft [Edge][edge] browser does not support Silverlight.

- [Boxes](https://github.com/gfkeogh/Boxes) — *Boxes perturbed by mouse movement.* (See [Demo](http://www.orthogonal.com.au/computers/boxes/index.htm))
- [Hypno](https://github.com/gfkeogh/Hypno) — *Animated coloured balls.* (See [Demo](http://www.orthogonal.com.au/computers/hypno/index.htm))
- [SilverPrimeSpiral](https://github.com/gfkeogh/SilverPrimeSpiral) — *Prime numbers wound on a spriral.* (See [Demo](http://www.orthogonal.com.au/prime_spiral/index.htm))
- [SilverRand](https://github.com/gfkeogh/SilverRand) — *Random shapes of different types.* (See [Demo](http://www.orthogonal.com.au/computers/silverrand/index.htm))

**Wiki Archive**

- [Nimbus][nimbus] — *Describes an experimental attempt to implement the Nancy Street Collections database as a set of Azure Storage Tables. As a technical exercise it basically worked, but was eventually abandoned because coercing Azure Tables to behave like a SQL Database produced too many quirks and irritations.*
- [Agate][agate] — *After the Nimbus project was abandoned, Agate was a replacement that returned to a traditional SQL Server database as the backing storage. This article describes the process of normalizing the Collections database into a set of joined tables in 3NF (3rd normal form). Due to the terrible burden of configuring a SQL Server database and integrating it into a .NET application, Agate was abandoned and replaced by [Trona][trona] which uses Cosmos DB as the backing storage (see [Collections Database History][collhist]).*

**Web**

- [P0ison][p0ison] — *An experimental [Blazor][blazor] application that displays large numbers of random but vaguely realistic looking email addresses that are (supposedly) poisonous to harvesters. This simple app was created mainly as a sanity check that Blazor works.*
- [Trona Blaze][tronablaze] — *Another experimental [Blazor][blazor] application that verifies that the more advanced features such as dependency injection, routing and service calls work as advertised. This more realistic app calls the [Trona][trona] web service to list information from the [Nancy Street collections database][collhist].*
- [Visitor Book][visbook] — *A simple traditional ASP.NET Web Forms application for the [orthogonal.com.au][orthocom] website. The book entries are stored in an Azure table. No one has entered anything in the book for 6 years ... is it still working?!*

[![Orthogonal Programming 
Link](https://orthoprog.blob.core.windows.net/reference/imgex/op.png?p=Documentation)](http://www.orthogonal.com.au/computers/)

[deprec16]: ../downloads/deprecated16.png "Deprecated"
[redcirc12]: ../downloads/redcirc12.png "Deprecated"
[esent]: https://en.wikipedia.org/wiki/Extensible_Storage_Engine
[doccomm]: https://orthoprog.blob.core.windows.net/dochelp/common/index.html
[doccomms]: https://orthoprog.blob.core.windows.net/dochelp/litecomms/index.html
[docnset]: https://orthoprog.blob.core.windows.net/dochelp/nsettings/index.html
[docntag]: https://orthoprog.blob.core.windows.net/dochelp/ntaglite/index.html
[docobjdb]: https://orthoprog.blob.core.windows.net/dochelp/objectdb/index.html
[docesent]: https://orthoprog.blob.core.windows.net/dochelp/esentmodel/index.html
[blazor]: https://blazor.net/
[p0ison]: http://www.orthogonal.com.au/p0ison
[tronablaze]: http://www.orthogonal.com.au/tronablaze
[Trona]: https://github.com/gfkeogh/Trona
[nimbus]: https://github.com/gfkeogh/Nimbus
[agate]: https://github.com/gfkeogh/Agate
[trona]: https://github.com/gfkeogh/Trona
[collhist]: https://gfkeogh.blogspot.com/2018/01/collections-database-history.html
[visbook]: http://www.orthogonal.com.au/visitorbook/index.aspx
[orthocom]: whttp://www.orthogonal.com.au/
[slcompat]: https://www.microsoft.com/getsilverlight/Get-Started/Install/Default
[edge]: https://www.microsoft.com/en-au/windows/microsoft-edge
