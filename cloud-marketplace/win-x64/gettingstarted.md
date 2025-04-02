# <img src="https://srtcdnstorage.blob.core.windows.net/software/nextgen/slserver/titansyslog48.png" alt="Titan AV Server logo"> Titan AV Server - Enterprise Cloud Edition for Windows </img>

Thank you for choosing Titan AV Server - Cloud Edition from South River Technologies. This is the Pay-as-you-go version of our solution, meaning that it will run fully featured without the need to purchase a license from South River Technologies. Simply fire up your Titan AV Server VM, and run your business.

## What's on the VM?

This Titan AV Server Virtual Machine (VM) contains a pre-built and pre-configured installation of the product.

## Features of Titan AV Server

Titan AV Server allows clients to scan files for viruses and malware via the industry standard ICAP protocol.

## Usage Instructions / Getting Started 

1. Launch your VM or instance and RDP into the Windows server with your chosen credentials (specified when creating the VM)
2. Launch the Titan AV Server Administrator UI by clicking on the desktop icon for the Titan AV Server. The first time you run the Administrator it will prompt you to create a new Administrator account to allow configuring the Titan AV Server.
3. To configure the Titan AV server click on the "Services" tab node under the "Default AV Server" instance. From here you can see that the server is preconfigured to listen on TCP port 1344 for ICAP protocol.
4. After the Titan AV Server is configured and listening on port 1344 for ICAP requests you can then configure your software that understands the ICAP protocol to talk to Titan AV Server. An example of this would be the [Titan MFT Server](https://southrivertech.com/cloud-titan-managed-file-transfer) which can be configured to perform AV scans on files with the ICAP protocol.

## Remote Administration

Titan AV server can optionally be configured to remotely configure the server via web interface by enabling "Remote Administration". To enable remote administration click on "Home" node on the left of the admin control panel, then in the "Local Domain" section click on Edit action icon and turn on the option for "Enable Remote Admin". After enabling this you will need to restart the Titan AV Service from Windows services. When using the default certficicate for remote administration the browser will complain about the certificate not being trusted, you can ignore this warning and select continue or confiure Titan AV server to use your own certificate to match your domain name. To import your own certificate click on "Manage Certificate" in the "Local Domain" section to import your certificate, then select this certificate from the list in the domain dialog (click on edit action).

## Tech Support

Complimentary technical support is available on our website at https://helpdesk.southrivertech.com (use TitanAVPAYG as your registration code)

## WebSite(s)

South River Technologies corporate WebSite:  [https://www.SouthRiverTechnologies.com](https://www.SouthRiverTechnologies.com)<br/>
Titan MFT (Enterprise grade Managed File Transfer Solution): [https://www.TitanMFT.com](https://www.TitanMFT.com)<br/>
Titan DMZ Server (Secure reverse proxy server for Titan MFT): [https://www.TitanDMZ.com](https://www.TitanDMZ.com)<br/>
Titan SFTP Server micro site: [https://www.TitanFTP.com](https://www.TitanFTP.com)<br/>
WebDrive (Virtual Drive Mapping Client): [https://www.WebDrive.com](https://www.webdrive.com)<br/>
