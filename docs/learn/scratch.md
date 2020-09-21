
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