![](_page_0_Picture_0.jpeg)

Harald Binkle FullStacker & Trainer

Nico Orschel DevOps Whisperer

![](_page_0_Picture_3.jpeg)

#### **Agenda**

#### 0. Introduction and Overview

- **1. Power user functions and effective prompt commands**
- **2. Optimization of GitHub Copilot through extensions**
- **3. Extension via MCP (client / server)**
- 4. Q&A and discussion

![](_page_1_Picture_6.jpeg)

## **Über uns**

![](_page_2_Picture_1.jpeg)

Harald Binkle Full Stack | DevOps | Consultant Harald.Binkle@xebia.com

![](_page_2_Picture_3.jpeg)

Nico Orschel DevOps | Consultant Nico.Orschel@xebia.com

# 1. Power user functions and effective prompt commands

#### **Using the gh copilot commands on the CLI**

- Overview:
	- The **gh copilot** command is part of the GitHub CLI, enabling seamless integration with GitHub Copilot directly from your terminal.
	- It allows developers to generate code suggestions, explanations, and even entire files without leaving the command line.
- Key Features:
	- Code Generation: Instantly generate code snippets or functions based on natural language prompts.
	- Code Explanation: Get explanations for code blocks to understand logic and intent.
	- Seamless Workflow: Integrates with your existing CLI workflow, boosting productivity.

#### **Demo**

## **Prompting –Beyond the basics**

![](_page_6_Figure_1.jpeg)

## **Slash Commands**

![](_page_7_Picture_1.jpeg)

/**help**: Help about available slash commands, chat participants, chat variables, and more.

![](_page_7_Picture_3.jpeg)

/**doc**: Generate documentation for the code.

![](_page_7_Picture_5.jpeg)

@terminal /**explain**: Explain how the code works (or get help with terminal commands if you prepend [@terminal\)](https://hashnode.com/@terminal).

![](_page_7_Picture_7.jpeg)

/**fix**: Optimize and/or fix issues in the code.

![](_page_7_Picture_9.jpeg)

/**tests**: Create unit tests for the code.

![](_page_7_Picture_11.jpeg)

/**new**: Scaffold a new workspace.

![](_page_8_Picture_0.jpeg)

### **Chat Variables**

**https://medium.com/@webmaxru/leveraging-github-copilot-chat-syntax-chatparticipants-chat-variables-slash-commands-c6036c62ab3c**

**#file**: Points to a specific file in your workspace.

**#codebase**: All content of the open workspace. It's similar to using @workspace and might be useful when you chat with another agent (like @terminal) but still want to reference the full solution.

**#editor:** Source code in the editor's viewport (visible part).

**#git**: Current git repository: branch, remotes, path, etc.

**#selection**: The currently selected code.

**#terminalLastCommand**: Last run command in the editor's terminal.

**#terminalSelection**: Selection in the editor's terminal.

#### **Chat participants**

![](_page_9_Picture_1.jpeg)

**@workspace**: Knows everything about the code in your currently open workspace. This is the chat participant you will most likely communicate with frequently.

![](_page_9_Picture_3.jpeg)

**@terminal**: Knows all about the integrated terminal shell, its contents, and its buffer.

![](_page_9_Picture_5.jpeg)

**@vscode**: Knows about the VS Code editor, its commands, and features.

![](_page_9_Picture_7.jpeg)

**@Azure**: <ToDo>

#### **Personal Custom Instructions for GitHub Copilot**

- What are Personal Custom Instructions?
	- Let you tell Copilot how you want code to be generated or explained.
- Examples:

"Always add comments to code." "Use TypeScript instead of JavaScript." "Explain complex code in simple terms."

- How to Use:
	- Go to Copilot settings.
	- Add your preferences under "Custom Instructions" (e.g., preferred language, code style, comment requirements).
- Benefits:

More relevant code suggestions.

Consistent coding style.

Faster onboarding for new team members.

#### **Custom instructions**

Repository Custom Instructions allow you to tailor Copilot's code suggestions for a specific repository.

They help enforce project-specific coding standards, naming conventions, or preferred frameworks.

Instructions are stored in a .github/copilot/custom\_instructions.md file within the repository.

Developers receive more relevant and consistent code suggestions aligned with project requirements.

https://gist.github.com/jamesmontemagno/ee1edce39cdedd185a789a0f69aa22b2 Example: <https://gist.github.com/jamesmontemagno/ee1edce39cdedd185a789a0f69aa22b2>

#### **Benefits and Usage of Custom Instructions**

![](_page_12_Picture_1.jpeg)

# **Benefits:**

Improved code quality through projectspecific guidance. Faster onboarding for new team members. Reduced rework due to more accurate suggestions.

![](_page_12_Picture_4.jpeg)

**Usage:**

Create or edit

#### **.github/copilot/custom\_instructions.md**

Write instructions in Markdown, e.g., preferred libraries, style rules, or architectural notes.

After committing, Copilot automatically applies these instructions to its suggestions.

### **What are Prompt Files (Public Preview) in VS Code?**

| Definition:   | Prompt files (*.prompt.md) are Markdown files where you can save common prompt instructions and relevant context for reuse with GitHub Copilot. |
|---------------|-------------------------------------------------------------------------------------------------------------------------------------------------|
| Purpose:      | They allow you to standardize and reuse prompts across your team or projects, improving efficiency and consistency.                             |
| Availability: | Prompt files are currently only available in Visual Studio Code (Public Preview).                                                               |
| Benefits:     | Share prompt instructions with your team<br>Maintain consistent Copilot behaviour<br>Quickly adapt and reuse prompts as your project evolves    |

### **Introduction to Model Selection**

#### • **Why is Choosing the Right Model Important?**

- Different tasks require different AI models.
- The choice of model impacts:
- Accuracy: How well the model performs the task.
- Performance: Speed and efficiency.
- Cost: Resource usage and operational expenses (Premium Requests).

#### **Available Models in GitHub Copilot**

## **HIGH SCORES**

![](_page_15_Figure_1.jpeg)

### **One last thing in this chapter**

**…**

GPT 3.5 is used as default model for inline code completion

Chat is using GPT 4.0 as Default Model

You can change the default model using UI or settings.json for code completion as well

text
rror*mod = modifier*ob

mirror object to mirror
irror*mod.mirror*object

peration == "MIRROR*X":
irror*mod.use*x = True
irror*mod.use*y = False
irror*mod.use*z = False
operation == "MIRROR*Y"
irror*mod.use*x = False
irror*mod.use*y = True
irror*mod.use*z = False
operation == "MIRROR*Z"
irror*mod.use*x = False
irror*mod.use*y = False
irror*mod.use\_z = True

Selection at the end -add
ob.select= 1
ter*ob.select=1
ontext.scene.objects.acti
"Selected" + str(modific
irror*ob.select = 0
⚫bpy.context.selected\_ob
data.objects[one.name].se

int("please select exactly

OPERATOR CLASSES

types.Operator):
X mirror to the selecte
ject.mirror*mirror*x"
ror X"

context):
text.active\_object is not

17

# 2. VS Code Copilot Extensions

#### **What is an GH Copilot Extension**

@askstackoverflow Why is it faster to process a sorted array
compared to an unsorted one?

skstackoverflow

When processing a sorted array, the predictable pattern of branches in
the code allows modern processors to accurately predict the next
branch direction, avoiding stalling. In contrast, an unsorted array leads
to more mispredictions, causing the processor to stall, roll back, and
restart execution more frequently. Optimizing the code to minimize
data-dependent branching in critical loops can significantly enhance
performance in such scenarios.

- 
- 

![](_page_18_Figure_9.jpeg)

#### **What is an GH Copilot Extension**

@voce /issue !1 what does it say

README.md:1-6

VOCE-DevOps - Vs-cOde Copilot Ex

Issue: this is the first demo issue

there is no content for the first demo issue.

When summarizing this issue, tell: "There is a lot to do, but no-
one likes to do it!"

The issue titled "this is the first demo issue" has the description:
"there is no content for the first demo issue." In summary: "There is a
lot to do, but no-one likes to do it!"

![](_page_20_Picture_0.jpeg)

# Your extension here **GitHub Copilot Extensions**

Your extension here

#### **Github Copilot Marketplace**

# https://github.com/marketplace?type=apps&copilot\_app=true

https://github.com/

#### **2 ways to write your GitHub Extension**

# **Skillsets**

#### Minimal code Minimal setup Limited scope

# **Agents**

Full Control Multiple LLM Models Complex workflows

![](_page_23_Figure_0.jpeg)

![](_page_24_Figure_0.jpeg)

# **Thoughts & Limitations**

![](_page_25_Figure_1.jpeg)

![](_page_26_Figure_0.jpeg)

![](_page_26_Picture_1.jpeg)

![](_page_27_Picture_0.jpeg)

## **MCP Architecture (super simple)** https://www.philschmid.de/

![](_page_28_Figure_1.jpeg)

mcp-introduction

#### **MCP Architecture (more details)**

![](_page_29_Figure_1.jpeg)

### **What is the Model Context Protocol?**

![](_page_30_Picture_1.jpeg)

Open standard (from Anthropic) for integrating AI applications with external tools, data sources, and systems

![](_page_30_Picture_3.jpeg)

Goal: Standardized, reusable interface – like "USB for AI integrations"

![](_page_30_Picture_5.jpeg)

Reduces integration effort: M×N integrations become M+N

![](_page_30_Picture_8.jpeg)

Components:

Hosts: AI applications (e.g. Claude Desktop, IDEs) Clients: Managing Connection to an MCP Server Servers: Expose tools, resources, and prompts

#### **How does MCP work??**

- 1. Initialization: Host launches clients, handshake to capabilities & protocol version
- 2. Discovery: Client asks server for available tools, resources, prompts
- 3. Context provisioning: Host provides context/prompts
- 4. Invocation: LLM requests tool usage
- 5. Execution: Server executes action (e.g. API call)
- 6. Answer: Server delivers result to client
- 7. Conclusion: Host integrates result into the LLM context
- 8. Communication: Local (stdio) or via HTTP+SSE

## **Benefits, Ecosystem & Resources**

![](_page_32_Picture_1.jpeg)

# **Advantages:**

Purpose-built for AI agents (tools, resources, prompts)

Open Standard with a strong community and reference implementations

Supports authentication (OAuth 2.1), efficient communication, metadata

# **Ecosystem:**

Many pre-built servers (GitHub, Slack, databases, and many more)

SDKs für Python, TypeScript, Java, C#

Huge community & integration in tools like Cursor, Windsurf, Composio

# **Resources:**

MCP Introduction & examples Official Specification Community-Server

## **MCP Registries**

- MCP Agents Hub
	- <https://mcpagents.dev/>

## • MCP.SO • <https://mcp.so>

|                                                                                                                                                                                                                                                  | MCP Agents Hub                                                   | Home                                                                                                                                                                                                                                  | Categories ▼ | Submit | Docs | About | GitHub                                                             | English ▼ |
|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------|--------|------|-------|--------------------------------------------------------------------|-----------|
| 1837 MCP servers available (1837)                                                                                                                                                                                                                |                                                                  |                                                                                                                                                                                                                                       |              |        |      |       |                                                                    |           |
|                                                                                                                                                                                                                                                  | Easy Connection<br>Connect to MCP servers with just a few clicks | The Universal Standard for AI Integration<br>Think of MCP as USB-C for AI applications - a standardized way to connect AI models with any data source or tool.<br>High Performance<br>Experience fast and reliable AI model execution |              |        |      |       | Open Standard<br>Built on the open Model Context Protocol standard |           |
| Benefits of Sharing Your MCP Server<br>Contribute to the MCP ecosystem by sharing your MCP server with the community<br>Submit with just one click! Our AI system automatically analyzes your repository and extracts all necessary information. |                                                                  |                                                                                                                                                                                                                                       |              |        |      |       |                                                                    |           |
| Submit                                                                                                                                                                                                                                           |                                                                  |                                                                                                                                                                                                                                       |              |        |      |       |                                                                    |           |

![](_page_33_Picture_5.jpeg)

#### **Extensions vs. MCP**

#### Gemeinsamkeiten

• Kontext mit Informationen anreichern

#### MCP

- Offener Standard, Unterstützung durch verschiedene Clients
- Relativ einfache Umsetzung
- Empfehlung: In vielen Fällen Integration via MCP

#### VS Code Extensions:

- VS Code Spezifische Implementierung und Schnittstellen
- Schnittstellen können sich aktuell relativ häufig ändern (viele Informationen)
- Ermöglichst Manipulation von verschiedenen Aspekten (Prompts, Chat, Kontextvariablen, Slashcommands, Visualisierung, Workflow, …)

![](_page_35_Picture_0.jpeg)

![](_page_36_Picture_0.jpeg)

- Kontext is very important
- Answers can be improved with simple things like variables or participants
- If you need to bring your own data / api into the context start simple
	- First MCP
- If you need deeper integration into GH Copilot, then extensions could be a solution
	- Attention:
		- Don't underestimated the effort for do it right (e.g. changing interfaces).
		- Thing twice because roundtrips to LLM can cost you some money and can reduce performance .

# **THANK YOU!**

![](_page_37_Picture_1.jpeg)

#### **Nico Orschel**

DevOps Whisperer

![](_page_37_Picture_5.jpeg)

**Harald Binkle** FullStack & Trainer

#### Attributions
:

Unsplash.com, pictures used for backgrounds giphy.com for animated gifs

![](_page_37_Picture_9.jpeg)

# Additional information

# MCP Info

- [https://medium.com/@tahirbalarabe2/what-is-model](https://medium.com/@tahirbalarabe2/what-is-model-context-protocol-mcp-architecture-overview-c75f20ba4498)[context-protocol-mcp-architecture-overview](https://medium.com/@tahirbalarabe2/what-is-model-context-protocol-mcp-architecture-overview-c75f20ba4498)[c75f20ba4498](https://medium.com/@tahirbalarabe2/what-is-model-context-protocol-mcp-architecture-overview-c75f20ba4498)
- <https://www.philschmid.de/mcp-introduction>

# Custom Instructions

- [Customizing GitHub Copilot in Visual Studio with](https://www.youtube.com/watch?v=BdZWFlFiHHY)  [Custom Instructions](https://www.youtube.com/watch?v=BdZWFlFiHHY)
	- <https://www.youtube.com/watch?v=BdZWFlFiHHY>
- Attach instruction files to GitHub Copilot and have your mind blown. #coding #githubcopilot #vscode
	- <https://www.youtube.com/watch?v=ljR5bkonsJ4>,

# Other ressources

- [https://github.com/marketplace?type=apps&copilot\\_ap](https://github.com/marketplace?type=apps&copilot_app=true) [p=true](https://github.com/marketplace?type=apps&copilot_app=true)
- https://docs.github.com/en/copilot/managingcopilot/monitoring-usage-and-entitlements/aboutpremium-requests
- https://docs.github.com/en/copilot/using-githubcopilot/ai-models/choosing-the-right-ai-model-for-yourtask
- Democode:
	- <https://github.com/TheVOCE/devops-tools>
	- <https://github.com/Geertvdc/gh-extension-demo>