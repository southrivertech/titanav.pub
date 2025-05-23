# <img src="https://srtcdnstorage.blob.core.windows.net/software/nextgen/slserver/titansyslog48.png" alt="Titan ICAP Server logo"> Titan ICAP Server - Enterprise Cloud Edition for Windows </img>

Thank you for choosing Titan ICAP Server - Cloud Edition from South River Technologies. This is the Pay-as-you-go version of our solution, meaning that it will run fully featured without the need to purchase a license from South River Technologies. Simply fire up your Titan ICAP Server VM, and run your business.

## What's on the VM?

This Titan ICAP Server Virtual Machine (VM) contains a pre-built and pre-configured installation of the product.

## Features of Titan ICAP Server

Titan ICAP Server allows clients to scan files for viruses and malware via the industry standard ICAP protocol.

## Usage Instructions / Getting Started

1) Connect securely to your AMI instance over SSH using your own keypair.
2) Once you are connected to the instance terminal session the initial Titan ICAP administrator account needs to be configured. To configure the Titan ICAP administrator account, use the following command and supply your new administrator credentials. It's imporant to use a complex password consisting of a minimum of 8 characters in length, both upper and lower case, one or more numbers, and one or more special characters consisting of the following characters "(~!@#$%^&*_-+=`|\\(){}[]:;\"'<>,.?/)", and it must not included the username in the password.

```
sudo /opt/southriver/icapserver/icapserver /LASINIT /username=`<admin-username>` /password=`<admin-password>`
```

3) Once the Titan ICAP administrative credentials have been established you can now connect to the Titan ICAP web-based admin console through your web-browser by pointing it to https://`<ipaddress>`:43443. Note that this is a secure connection. However, since Titan SysLog is using a temporary certificate, you will see a security warning in the browser. Proceed past the security warning and log in to the Titan ICAP Server Admin console. At this point you will be able to configure the Titan ICAP application including adding your own TLS certificate. To import your own certificate click on "Manage Certificate" in the "Local Domain" section to import your certificate, then select this certificate from the list in the domain dialog (click on edit action).

## Database and Files location

The Titan database location is /var/southriver/icapserver The Titan ICAP logging locations can be configured in the Titan Administrator user interface.

## Upgrading

The Titan software will periodically check for updates to the software and allow you to download the release notes and upgrade the software. You can also trigger a check for update manually from the Product Info tab in the admin user interface.

## Tech Support

Complimentary technical support is available on our website at https://helpdesk.southrivertech.com (use TitanSysLogPAYG as your registration code)

## WebSite(s)

South River Technologies corporate WebSite:  [https://www.southrivertech.com](https://www.southrivertech.com)<br/>
Titan MFT (Enterprise grade Managed File Transfer Solution): [https://www.TitanMFT.com](https://www.TitanMFT.com)<br/>
Titan DMZ Server (Secure reverse proxy server for Titan MFT): [https://www.TitanDMZ.com](https://www.TitanDMZ.com)<br/>
Titan SFTP Server micro site: [https://www.TitanFTP.com](https://www.TitanFTP.com)<br/>
WebDrive (Virtual Drive Mapping Client): [https://www.WebDrive.com](https://www.webdrive.com)<br/>
