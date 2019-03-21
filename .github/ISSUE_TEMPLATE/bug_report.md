---
name: Bug Report
about: Report problems and unexpected behavior.
title: 'attempting debug of a node app'
labels: 'bug'
assignees: ''
---

<!-- Please search existing issues to avoid creating duplicates. -->
<!-- All extension-specific issues should be created with the `Extension Bug` template. -->

- `code-server` version: <!-- The version of code-server -->
- OS Version: <!-- OS version, cloud provider,  
server running 4.15.0-46-generic Ubuntu on NUC
client is Chrome 72.0.3626.121 (Official Build) (64-bit) on Mac running Mojave 10.14.3-->

## Description

<!-- Describes the problem here 
Able to connect the to server and edit/build typescript applications on as node application.
These applications can reach out to other LAN connected devices (its a network data logging system)
Running:
node -inspect-brk appname
the node instance waits for connect at port 9229

"Debugger listening on ws://127.0.0.1:9229/032a9928-b78d-4db7-b28c-fc2873ad843e
For help, see: https://nodejs.org/en/docs/inspector
"

WHen I set up for debug with the following congffuguration
           {
            "type": "node",
            "request":"attach",
            "name": "Attach Code Server",
            "port": 9229
            }
 
 When I hit the "GO" button
 
 The controls panel for hte debugger appears for 3 seconds then disapperars.
 
 Further attemtps to hi thte green button gernate a "There is already a debug session...." popup.
 
 There are no errors showing up in the console  other ethan a repeated message that seems unrelated whne a new window is drawn in the browser:
 
   ERR Cannot read property 'clientWidth' of undefined: TypeError: Cannot read property 'clientWidth' of undefined
    at t.adjustTitleMarginToCenter (https://10.0.35.2:8443/80936d.bundle.js:60:4473554)
    at e._runner (https://10.0.35.2:8443/80936d.bundle.js:60:4474453)
    at e.execute (https://10.0.35.2:8443/80936d.bundle.js:16:22529)
    at I (https://10.0.35.2:8443/80936d.bundle.js:16:22725)
            

-->

## Steps to Reproduce

1. <!-- step 1: click ... -->
1. <!-- step 2: ... -->
