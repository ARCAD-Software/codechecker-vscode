# Getting Started
1. Download and install the `ARCAD-CodeChecker` extension from the VSCode marketplace.
2. Open the `Settings`, navigate to the `extension` > `ARCAD-CodeChecker` section and set the server's address and port.<br/>
![config_001](../assets/config_001.png)
3. If you use `HTTPS`, make sure to set the path to a local file containing the server's certificate chain in `PEM` format.<br/>
![config_002](../assets/config_002.png)
4. Click on the `CodeChecker` status bar icon and select the desired RuleSet<br/>
![config_003](../assets/config_003.png)
5. Open a source file, right click and select `Analyse with CodeChecker`<br/>![exec_001](../assets/exec_001.png)
6. Detected issues will be higlighted and listed in the `Problems` view