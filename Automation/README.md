# Sentinel Playbook ARM Templates

ARM templates for Microsoft Sentinel playbooks (Logic Apps).  
Click **Deploy to Azure** to deploy a playbook into your subscription.

---

## TW-Disable-EntraUser

Disables an Entra ID user account in response to Sentinel incidents.

[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FRishiCPS%2FSentinel-Playbook-ARM-Templates%2Fmain%2FPlaybooks%2FTW-Disable-EntraUser%2FTW-Disable-EntraUser_ARM.json)

---

## TW-Isolate-MDEMachine

Isolates a machine via Microsoft Defender for Endpoint when triggered from Sentinel.

[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FRishiCPS%2FSentinel-Playbook-ARM-Templates%2Fmain%2FPlaybooks%2FTW-Isolate-MDEMachine%2FTW-Isolate-MDEMachine_ARM.json)

---

## Add another playbook

1. Create a folder under `Playbooks/<PlaybookName>/`.
2. Drop the exported ARM template as `<PlaybookName>_ARM.json`.
3. Add another **Deploy to Azure** button in this README using:

