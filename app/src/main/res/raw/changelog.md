### 1.5.4
- released on f-droid

### 1.5.3
- major rework, open-sourced

### 1.3.15
- spanish, portuguese and russian translations
- fixed some issues with Gmail, Evernote, Inbox
- fixed problem with (key) passwords longer than 72 characters
- fixed a problem when removing previously selected PGP keys

### 1.3.14
 - fixed a rare crash 
 - worked around a crash on custom Androids without proper Accessibility Settings page

### 1.3.13
- fixed flickering / unusable UI-Overlay in Android 7.1
- added in-app link to privacy policy
- some fixes / improvements to GPG params fragment


### 1.3.12
- optimizations
- PGP recipient selection working again with latest OpenKeyChain
- fixed some small memory leaks

### 1.3.11
- maintenance release, fixes a few rare crashes

### 1.3.10
- Hotifx for crashes introduced by updating 3rd party library

### 1.3.9
 - now works with YubiKey via Openkeychain
 - various small improvements

### 1.3.6
 - better defaults for "Google Docs" and other "notes" apps
 - fixes a few small bugs

### 1.3.5
- French translation

### 1.3.4
- now detects Base64 in WebViews (GMail, Inbox, ...)
- fixes a few small bugs

### 1.3.3
- handle "draw over other apps" permission revokal gracefully

### 1.3.1
- hotfix

### 1.3.0
- new "spread" invisible encoding for Instagram and Facebook Messenger
- Turkish translation
- Fixes rare crash after purchasing upgrade

### 1.2.1
- Hotfix

### 1.2.0
- Support for "Inbox By Gmail" via clipboard
- gracefully handle apps that crash when get fed with too much text
- fixed some minor bugs

### 1.1.1
- gracefully handle permission revokal
- fixed some crashes

### 1.1.0
- New feature: Panic on Screen Off
- Encryption Params wouldn't show sometimes when encrypting an image - fixed

### 1.0.1
- Fixed a crash on some tables when using the Color seek bar
- Fixed a crash due to mishandling of preferred symmetric keys

### 1.0.0
- added german translation

### 0.9.26
- encoding selection in encryption params was not honored under special circumstances

### 0.9.25
- support for multiple PGP messages in a WebView (GMail thread view)

### 0.9.24
- fixed a bug related to encoding images
      
### 0.9.23
- removed version header from ascii armored PGP messages
- ascii armored pgp messages now correctly encodes and decodes UTF-8    
- WebView now supported, so decoding emails in Gmail and K9 just works
    
### 0.9.22
- fixed crash wenn adding first key through encryption params activity
- fixed a window leak
- fixed race condition while assigning decrypted text to cached text views
