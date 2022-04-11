`ahok` is a very small CLI to check Atlassian's statues and incidents from the terminal.


### Example Output
```
=== Components as of 08 Apr 22 14:16 UTC ===
App listing management                               ✅
Bitbucket Cloud APIs                                 ✅
App Deployment                                       ✅
APIs                                                 ✅
Confluence Cloud APIs                                ✅
Developer                                            ✅
Artifactory (Maven repository)                       ✅
App listings                                         ✅
Atlassian Support contact form                       ✅
Marketplace                                          🟠
Jira Cloud APIs                                      ✅
Create and manage apps                               ✅
App pricing                                          ✅
Developer community                                  ✅
Product Events                                       ✅
App submissions                                      ✅
Authentication and user management                   ✅
Developer documentation                              ✅
Developer service desk                               ✅
Forge App Installation                               ✅
Support                                              ✅
Marketplace service desk                             ✅
User APIs                                            ✅
Category landing pages                               ✅
Forge CDN (Custom UI)                                ✅
Evaluations and purchases                            ✅
Atlassian Support                                    ✅
Webhooks                                             ✅
Web Triggers                                         ✅
Vulnerability management [AMS]                       ✅
In-product Marketplace and app installation (Cloud)  ✅
Forge Function Invocation                            ✅
In-product Marketplace and app installation (Server) ✅
aui-cdn.atlassian.com                                ✅
Forge App Logs                                       ✅
Notifications                                        ✅
Private listings                                     ✅
Developer console                                    ✅
Forge direct app distribution                        ✅
Reporting APIs and dashboards                        ✅
Search                                               ✅
Vendor management                                    🟠
Vendor Home Page                                     ✅

=== Incidents ===
Name:         Some marketplace partners are unable to update Partner account details on Marketplace.
Impact:       🟡 minor
Status:       identified
Details:      We are continuing to fix the issue. In the meantime if you are seeing an issue updating your Partner account details , please reach to us from here[https://ecosystem.atlassian.net/servicedesk/customer/portal/9/group/30/create/56] for further assistance.
Link:         https://stspg.io/7rs1s2vcpzdq
Last Updated: 08 Apr 22 14:16 UTC
```


## Building from source

`go build -o atok main.go`

Then add the newly created `atok` executable to your path.
