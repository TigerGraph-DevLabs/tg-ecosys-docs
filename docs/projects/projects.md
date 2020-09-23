---
template: overrides/main.html
---

## Ecosys Community Projects
TigerGraphs Ecosys is a collection of innovative projects, connectors, patterns, and tools developed by the community or with the community to help develop out TigerGraph's ecosystem. A project is marked with **`Community Support`** or if a project graduates into an oficial TigerGraph offering it will be marked with **`TigerGraph support`**.

![projects](https://github.com/TigerGraph-OSS/tg-ecosys-docs/blob/master/docs/assets/images/community_projects.png?raw=true)

!!! warning "Keep in Mind"
    Projects marked by **`Community Support`** don't have any SLAs or guarantees and support will be primarily through community contributions to the project.        

### Davraz

???+ code-braces "More Info - Community Supported"

    === "About"

        ![davraz](https://github.com/TigerGraph-OSS/tg-ecosys-docs/blob/master/docs/assets/images/davraz1.png?raw=true)
        Graph visualization and exploration software. Leverages cytoscape.js and provides rich and customized graph visualizations. Aims ultimate complexity management, customization, and user-friendliness.
        
        [**:octicons-file-code-24: Code Source**](https://github.com/canbax/davraz)
    
    === "Video"
        <!--Youtube Video-->
        <iframe width="100%" height="425px" src="https://www.youtube.com/embed/I8BgFve4sA8" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

    === "Author Info" 
        [**Yusuf Said Canbaz**](https://devpost.com/canbax)

    === "Tags"
        `angular.js` `cytoscape.js` `material-theme` `node.js`
     

### Tigroid

??? code-braces "More Info - Community Supported"

    === "About"
        JavaScript connector for TigerGraph

        **!!! WORK IN PROGRESS !!!**

        This connector is intended to work both in browsers and on server side, to be Node.JS friendly (in the long term).

        [**:octicons-file-code-24: Code Source**](https://github.com/szb-tg/Tigroid.js)

    === "Tags"
        `nodejs` `javascript` `Node.JS`

### pyTigerDash

???+ code-braces "More Info - Community Supported"

    === "About"

        ![dash](https://github.com/futuristacademy/dash-plotly-demos/blob/master/static/Dash.gif?raw=true)

        [**:octicons-file-code-24: Code Source**](https://github.com/futuristacademy/dash-plotly-demos)

        pyTigerDash allows developers to harness the power TigerGraph with an equally powerful framework offering fully dynamic and responsive visualizations that can be deployed anywhere whilst staying in the data scientist language of choice, “Python”. Tiger-Dash toolkit will accelerate the process from data to value exponentially. 

    === "Tags"

        `Dash` `Plotly` `Python` `Bootstrap`

### TigerGraph.NET

???+ code-braces "More Info - Community Supported"

    === "About"
        TigerGraph.NET is a set of libraries, tools and components for building multi-target graph-powered applications using C# and F#. There are several sub-projects under the TG.NET umbrella:

        ### CLI
        The CLI project provides a cross-platform client for querying and monitoring TigerGraph servers including free-tier server instances. It talks to the REST++ and GSQL endpoints does not rely on the Java based GSQL client.

        ### Proxy
        The Proxy project is a proxy server for TigerGraph that provides common app services like caching and mitigates some of the limitations of using free-tier TigerGraph instances for browser-based apps. The proxy is a small .NET Core app that can run on most Linux environments like on a AWS micro-instance or as a container on Redhat OpenShift and provides a transparent proxy for REST++ and GSQL API requests from client-side code with the following features.

        * Authentication: You can set environment variables for your TG_TOKEN, TG_USER and TG_PASS credentials on the server so you don't have to expose these in your client app code.

        * CORS: The server supports CORS headers and CORS pre-flighting requests so you can make calls to your TigerGraph server API from your JS browser code. Normally you would have to configure the TigerGraph Nginx server using gadmin to enable this support but this isn't available for free-tier instances

        * Keep-alive: By default the proxy server pings the echo endpoint of the backing TG server every 15 minutes. By default free-tier instances shutdown after about 90 minutes of inactivity and there is no way of restarting them automatically.

        * Cachiing: The proxy server implements a simple memory-cache which caches graph data requests using the URL requests as cache keys. Apps that use graph data can avoid hitting the TG server on every request. More sophisticated caches and schemes can be implemented pretty easily using the ASP.NET Core libraries and middleware.

        [**:octicons-file-code-24: Code Source**](https://github.com/allisterb/TigerGraph.NET)

        [**.Net Package**](https://www.nuget.org/packages/TigerGraph.NET/)

    === "Video"
        <!--Youtube Video-->
        <iframe width="100%" height="425px" src="https://www.youtube.com/embed/J-HcJpXWDKI" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

    === "Author Info"
        [**Allister Beharry**](https://devpost.com/allisterb)

    === "Tags"

        `tigergraph` `graph` `gsql` `security` `.Net` `C#`

### pyTigerGraph

??? code-braces "More Info - Community Supported"

    === "About"
        pyTigerGraph is a Python package for connecting to TigerGraph databases.
        
        [**:octicons-file-code-24: Code Source**](https://pytigergraph.github.io/pyTigerGraph/)


        [**PYPI**](https://pypi.org/project/pyTigerGraph/)

        [**OFFCIAL DOCUMENTATION**](https://pytigergraph.github.io/pyTigerGraph/)

    === "Author Info" 
        pyTigerGraph was originally created by Parker Erickson, a Computer Science student at the University of Minnesota. Special thanks to contributors Jon Herke and Szilard Barany of TigerGraph. Read this to learn more about how you can contribute.

    === "Tags"
        `python` `pypi` `package` `gsql`

### pyTigerDriver

???+ code-braces "More Info - Community Supported"

    === "About"
        Python based GSQL Driver that interacts with TigerGraph's GSQL endpoint. 

        ```
        from pyTigerDriver import GSQL_Client
        from pyTigerDriver import REST_Client

        # Example to for localhost without specifying the version
        gsql = GSQL_Client("127.0.0.1",username="tigergraph",password="tigergraph")


        # Example to for localhost with the version specified
        gsql = GSQL_Client("127.0.0.1",username="tigergraph",password="tigergraph", version="v3_0_5") 

        # Example to for the cloud (Note the CACERT Param for tgcloud.io  file obatained from  https://raw.githubusercontent.com/Zrouga-Mohamed/utilities/master/certificate.crt )
        gsql = GSQL_Client("<Your_instance>.tgcloud.io", version="v3_0_5",username="tigergraph",password="<you_password>", cacert="certificate.crt")


        print("=============================== LOGIN ============================================")
        gsql.login()  # Perform login

        print("============================== SIMPLE LS ===========================================")
        res = gsql.query("ls") 

        print("==============================   LIST USERS   ======================================")
        res = gsql.query("SHOW USER")

        print("==============================   Create a Secret   ======================================")

        res = gsql.query("USE GRAPH MyGraph") # change MyGraph --> to your graph
        res = gsql.query("create secret  mys") # Create a secret

        print("==============================   Get Secrets   ======================================")
        res = gsql.get_secrets("MyGraph")

        print("================================  SHOW SECRET  =======================================")
        res = gsql.query("SHOW SECRET")
        print("=============================== Print Version =========================================")
        gsql.version()
        
        [**:octicons-file-code-24: Code Source**](https://github.com/Zrouga-Mohamed/pyTigerDriver)
        P
        ```
        [**:octicons-file-code-24: Code Source**](https://github.com/Zrouga-Mohamed/pyTigerDriver)

    === "Author Info" 
        [**Zrouga Mohamed**](https://www.linkedin.com/in/zrouga-mohamed/)

    === "Tags"
        `gsql` `driver` `python`