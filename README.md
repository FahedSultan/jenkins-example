## Disable copy/paste and file transfer from windows remote desktop to client.

### Need to change the Local group policy setting:
- Start run command
- gpedit
- -> locate Local Computer Policy
- -> Computer
- -> Administrative Templates 
- -> Windows Components 
- -> Terminal Services 
- -> Client/Server Data Redirection 
- -> Do Not Allow Clipboard Redirection
