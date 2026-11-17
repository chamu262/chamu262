<img src="assets/banner.png" alt="Chamudith Amarasinghe, IT Systems Engineer. AI does the legwork, people make the call: agent finds it, agent drafts the fix, you approve, change runs." width="100%">

<p>
<img src="https://img.shields.io/badge/Open_to-AI_automation_·_IT_systems_·_IAM_·_Forward--deployed-F2913D?style=flat-square" alt="Open to AI automation, IT systems, IAM and forward-deployed roles">
<img src="https://img.shields.io/badge/NYC_/_NJ_·_remote_·_relocation-available_now-2EA043?style=flat-square" alt="NYC / NJ, remote or relocation, available now">
</p>

I'm an IT systems engineer who builds **AI agents for device, identity and access work**. They find the problem, draft the fix and wait for a person to approve it. Nothing changes without a human, and everything is dry-run first.

**9 years in IT**, from desk-side support to systems engineering, running Mac, Windows and iOS fleets of **1,000+ devices** in regulated industries.

## ⚡ Highlights

| Result | What it means |
|---|---|
| **< 30 min** | New-device setup with zero-touch Jamf, Intune and Automox, down from between 8 hours and 2 days |
| **5 open-source demos** | Agentic IT tools you can clone and run on made-up data, most with no API key |
| **1 talk** | [From Prompts to Agent Teams](https://github.com/chamu262/presentations/tree/main/2026%20-%20From%20Prompts%20to%20Agent%20Teams): six practices that change AI results now |

## 🧭 How I build agents

```mermaid
flowchart LR
  J["Scheduled job<br/>or request"] --> A["Agent reads<br/>(read-only MCP tools)"]
  A --> R["Rules flag<br/>the problem"]
  R --> D["Agent drafts the fix<br/>and explains why"]
  D --> P{"Person<br/>approves?"}
  P -- yes --> X["Dry run,<br/>then the change runs"]
  P -- no --> N["Nothing changes"]
  X --> L["Logged and checked"]
```

## 🧰 Projects

<table>
<tr>
<td width="33%" valign="top"><a href="https://github.com/chamu262/agentic-os-demo"><img src="assets/agentic-os.jpg" alt="Agentic OS approvals queue"></a><br><b><a href="https://github.com/chamu262/agentic-os-demo">agentic-os-demo</a></b><br>Scheduled IT jobs where agents propose changes and a person approves each one.</td>
<td width="33%" valign="top"><a href="https://github.com/chamu262/poc.mcp-it-tools"><img src="assets/mcp-it-tools.jpg" alt="IT Tools Viewer device list"></a><br><b><a href="https://github.com/chamu262/poc.mcp-it-tools">poc.mcp-it-tools</a></b><br>An MCP server that gives AI agents safe, read-only IT tools: devices, users, groups, access.</td>
<td width="33%" valign="top"><a href="https://github.com/chamu262/sample-agentic-access-review"><img src="assets/access-review.jpg" alt="Access review queue"></a><br><b><a href="https://github.com/chamu262/sample-agentic-access-review">sample-agentic-access-review</a></b><br>Rules flag unused or risky access, AI explains each flag, a person approves.</td>
</tr>
<tr>
<td width="33%" valign="top"><a href="https://github.com/chamu262/nova-os-demo"><img src="assets/nova-os.jpg" alt="Nova OS crew and chat"></a><br><b><a href="https://github.com/chamu262/nova-os-demo">nova-os-demo</a></b><br>A personal AI team: a lead agent routes each request to the right specialist.</td>
<td width="33%" valign="top"><a href="https://github.com/chamu262/godfather"><img src="assets/godfather.jpg" alt="Godfather dashboard"></a><br><b><a href="https://github.com/chamu262/godfather">godfather</a></b><br>A supervisor setup for Claude Code: sessions, skills, memory and a live dashboard.</td>
<td width="33%" valign="top"><a href="https://github.com/chamu262/presentations"><img src="assets/talk.jpg" alt="From Prompts to Agent Teams cover slide"></a><br><b><a href="https://github.com/chamu262/presentations">presentations</a></b><br>Slides and speaker notes, each practice linked to a runnable demo.</td>
</tr>
</table>

## 🔭 What I do

*   **Agentic IT operations:** scheduled jobs that propose changes, with approval gates and dry runs.
*   **AI connected to IT systems** through read-only MCP tools for devices, users, groups and access.
*   **AI-assisted access reviews:** rules flag leavers, unused admin rights and idle paid seats; the agent explains each flag.
*   **Zero-touch deployment** with Jamf, Intune and Automox, plus staged rollouts gated by conditional access and compliance.
*   **Migrations end to end:** MDM platforms, and VPN from Tailscale to NetBird.
*   **Automations and SSO:** jobs on Google Cloud Run, SSO and SAML app integrations.
*   **Claude Code as a team:** a supervisor session, project masters, skills, memory and approval gates.

## 💻 Tech stack

**AI & agents**<br>
<img src="https://img.shields.io/badge/Claude_Code-191919?style=flat-square&logo=claude&logoColor=D97757" alt="Claude Code">
<img src="https://img.shields.io/badge/Claude_API-191919?style=flat-square&logo=anthropic&logoColor=white" alt="Claude API">
<img src="https://img.shields.io/badge/MCP-191919?style=flat-square&logo=modelcontextprotocol&logoColor=white" alt="Model Context Protocol">

**Endpoint & identity**<br>
<img src="https://img.shields.io/badge/Jamf_Pro-1F2937?style=flat-square" alt="Jamf Pro">
<img src="https://img.shields.io/badge/Microsoft_Intune-1F2937?style=flat-square" alt="Microsoft Intune">
<img src="https://img.shields.io/badge/Automox-1F2937?style=flat-square" alt="Automox">
<img src="https://img.shields.io/badge/Iru-1F2937?style=flat-square" alt="Iru">
<img src="https://img.shields.io/badge/Entra_ID-1F2937?style=flat-square" alt="Microsoft Entra ID">
<img src="https://img.shields.io/badge/Active_Directory-1F2937?style=flat-square" alt="Active Directory">
<img src="https://img.shields.io/badge/Google_Workspace-1F2937?style=flat-square" alt="Google Workspace">
<img src="https://img.shields.io/badge/SSO_/_SAML-1F2937?style=flat-square" alt="SSO and SAML">
<img src="https://img.shields.io/badge/macOS_·_iOS-1F2937?style=flat-square&logo=apple&logoColor=white" alt="macOS and iOS">
<img src="https://img.shields.io/badge/Windows-1F2937?style=flat-square" alt="Windows">

**Languages**<br>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
<img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js">
<img src="https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white" alt="Bash">
<img src="https://img.shields.io/badge/PowerShell-5391FE?style=flat-square" alt="PowerShell">

**Cloud & network**<br>
<img src="https://img.shields.io/badge/Google_Cloud_Run-4285F4?style=flat-square&logo=googlecloud&logoColor=white" alt="Google Cloud Run">
<img src="https://img.shields.io/badge/Azure-0078D4?style=flat-square" alt="Microsoft Azure">
<img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square" alt="AWS">
<img src="https://img.shields.io/badge/NetBird-1F2937?style=flat-square" alt="NetBird">
<img src="https://img.shields.io/badge/Tailscale-1F2937?style=flat-square&logo=tailscale&logoColor=white" alt="Tailscale">
<img src="https://img.shields.io/badge/Cisco_Meraki-1F2937?style=flat-square&logo=cisco&logoColor=white" alt="Cisco Meraki">

## 🎓 Education & certifications

*   **BS Mathematics and Computer Science** (double major), CUNY College of Staten Island, 2021 · Dean's List
*   **Certifications:** <img src="https://img.shields.io/badge/Jamf-100-F2913D?style=flat-square" alt="Jamf 100"> <img src="https://img.shields.io/badge/Claude-101-D97757?style=flat-square&logo=claude&logoColor=white" alt="Claude 101">

## 📫 Let's talk

I'm looking for my next role in AI automation, IT systems, identity/IAM or forward-deployed engineering. The fastest way to reach me is [LinkedIn](https://www.linkedin.com/in/chamudith-amarasinghe-ab1223216).
