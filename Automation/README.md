# Sentinel Playbook ARM Templates

ARM templates for Microsoft Sentinel playbooks (Logic Apps).  
Click **Deploy to Azure** to deploy a playbook into your subscription.

---

## TW-Disable-EntraUser

Disables an Entra ID user account in response to Sentinel incidents.

[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fjakubkupiec%2Ftemp%2Fmain%2FAutomation%2FPlaybooks%2FTW-Disable-EntraUser%2FTW-Disable-EntraUser_ARM.json)

---

## TW-Isolate-MDEMachine

Isolates a machine via Microsoft Defender for Endpoint when triggered from Sentinel.

[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fjakubkupiec%2Ftemp%2Fmain%2FAutomation%2FPlaybooks%2FTW-Isolate-MDEMachine%2FTW-Isolate-MDEMachine_ARM.json)

---

## Add another playbook

1.  Create a folder under `Automation/Playbooks/<PlaybookName>/`.
2.  Drop the exported ARM template as `<PlaybookName>_ARM.json`.
3.  Add another section to this README by copying the code block below.
4.  Replace `<PlaybookName>` (in all three places) with the name of your new playbook and update the description.

```markdown
---

## <PlaybookName>

[Add a short description of what the playbook does here]

[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fjakubkupiec%2Ftemp%2Fmain%2FAutomation%2FPlaybooks%2F<PlaybookName>%2F<PlaybookName>_ARM.json)
