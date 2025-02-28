## **10.   WDAC: (Windows Defender Application Control)**

Work in Progress, please review all content before starting, and be cautious in deployment

-   From Eric Mannon: <https://www.linkedin.com/feed/update/urn:li:activity:6996238396973051904/>
-   **Read the above article first**
-   1st- Install WDACme on all W10 workstations
-   2nd- Enable "Smart Application Control" in Evaluation mode on W11 endpoints that support it
-   3rd- Lock down Tier 0 (DC's, ADFS & AD Connect servers) with WDAC Microsoft-only mode in block mode. (No 3rd party software should ever be installed on the Tier 0 server type)
-   4th- Deploy a supplemental policy to block the Microsoft recommended block list
-   🔑Golden rule: "Audit is better than nothing"
-   🎯Desired state: "Zero Trust for unapproved code"

🎒Resources:

-   WDAC Deployment: <https://lnkd.in/em8sV9AK>
-   ⛄️ Olaf Hartong's: WDACMe: <https://lnkd.in/gU33rPzf>
-   W11 Smart App Control: <https://lnkd.in/e5X3WF9H>
-   Recommended Block Rules: <https://lnkd.in/eZEwcwM9>
-   WDAC Policy Wizard: <https://lnkd.in/gwFuvmd4>
-   Hunting WDAC Events in KQL: <https://lnkd.in/eJE8WHZG>

### **Additional Resources**

-   Creating a policy for machines already in use (this is the hard one)
https://learn.microsoft.com/en-us/windows/security/threat-protection/windows-defender-application-control/create-initial-default-policy#create-a-custom-base-policy-to-minimize-user-impact-on-in-use-client-devices
-   WDAC Policy creation from DTA - <https://desktop.gov.au/blueprint/abac/wdac-policy-creation.html>
-   <https://www.cyber.gov.au/acsc/view-all-content/publications/implementing-application-control>
-   <https://learn.microsoft.com/en-us/windows/security/threat-protection/windows-defender-application-control/create-wdac-deny-policy>
-   <https://techcommunity.microsoft.com/t5/core-infrastructure-and-security/deploying-windows-10-application-control-policy/ba-p/2486267>
-   <https://learn.microsoft.com/en-us/windows/security/threat-protection/windows-defender-application-control/select-types-of-rules-to-create>
-   <https://learn.microsoft.com/en-us/windows/security/threat-protection/windows-defender-application-control/microsoft-recommended-block-rules>
-   <https://learn.microsoft.com/en-us/windows/security/threat-protection/windows-defender-application-control/windows-defender-application-control-deployment-guide>