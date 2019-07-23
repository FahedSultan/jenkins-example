## Disable copy/paste and file transfer from windows remote desktop to client.

### Need to change the Local group policy setting:
- Start run command
- Type gpedit to open Local Group Policy Editor
- Locate the following path-
- -> Local Computer Policy
- -> Computer Configuration
- -> Administrative Templates 
- -> Windows Components 
- -> Remote Desktop Services
- -> Remote Desktop Session Host
- -> Device and Resource Redirection
- -> ##Edit   - Do Not Allow Clipboard Redirection
- -> #Enable - Do Not Allow Clipboard Redirection
