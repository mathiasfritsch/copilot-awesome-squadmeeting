# copilot-awesome-squadmeeting


In GitHub Copilot (VS Code, CLI, JetBrains), prompt files and skill files standardize AI behavior but work differently—prompts are slash-command reusable instructions, skills are agent-invoked modules with resources.


| Feature      | Prompt Files                                                               | Skill Files                                                       |
| ------------ | -------------------------------------------------------------------------- | ----------------------------------------------------------------- |
| Location     | .github/prompts/*.prompt.md or user profile code.visualstudio​             | .github/skills/my-skill/SKILL.md github+1                         |
| Invocation   | /promptname args in chat YouTube​                                          | Auto by agent or @skill (on-demand load) github​                  |
| Structure    | YAML metadata + Markdown prompt code.visualstudio​                         | YAML frontmatter + Markdown + scripts/examples code.visualstudio​ |
| Tools/MCP    | Can reference MCP tools (tools: ["azure-devops-mcp/*"]) code.visualstudio​ | Full dir support: scripts, MCP​                |
| Context Load | Full prompt on invoke                                                      | Metadata first (~100 tokens), body as needed code.visualstudio​   |
| Sharing      | Workspace/user/repo sync code.visualstudio​                                | Repo .github/skills/ auto-discovered github​                      |




tried out 

agents/adr-generator.agent.md

- use ADR Generator agent to make a adr for the decission to use postgres or oracle . dont write something yet. just have a conversation with me were you ask question

- nicht sichtbar dass der agent verwendet wurde (nach Nachfrage und laut Inhalt hat er das aber)

- 

context7.agent.md


