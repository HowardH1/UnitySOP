
# Week 05 CLI Prompt Log
# Prompt 1

## Tool + environment
- Tool: Gemini CLI
- Date/time: 2/15/2026 10:15PM
- Repo/branch: [main / UnitySOP]

## Goal
Create a mermaid Diagram from the SOP markdown file

## Inputs (files referenced)
- UnitySOPV1Markdown.md

## Prompt
Read @[LOCAL_DIRECTORY]\GitHub\UnitySOP\UnitySOPV1Markdown.md and generate Mermaid flowchart code
   (flowchart TD) that matches the procedure exactly.
   - Include explicit Start and End.
   - Every decision has labeled branches.
   - Do NOT invent steps. If missing, mark as [TBD] as a note.
   Write the output to @[LOCAL_DIRECTORY]\GitHub\UnitySOP\diagrams\mermaid

## Output summary
- created "process.mmd"
- produced an accurate mermaid flowchart of the SOP and saved it to the diagrams folder

## Validation performed
- Checked each step to see how it aligned with my hand made chart
- Nothing was wrong, but it consolidated some steps which I chose to leave as is

## Human edits I made
- None necessary other than changing the file name to "UnitySOPmermaid.mmd"

## Result
- Final files committed: UnitySOPmermaid.mmd
# Prompt 2
## Tool + environment
- Tool: Gemini CLI
- Date/time: 2/15/2026 11:01PM
- Repo/branch: [main / UnitySOP]

## Goal
Create a BPMN Diagram from the SOP markdown file

## Inputs (files referenced)
- UnitySOPV1Markdown.md

## Prompt

 Using @[LOCAL_DIRECTORY]\GitHub\UnitySOP\UnitySOPV1Markdown.md, generate a BPMN 2.0 XML file for the process.
   - Start event + end event required.
   - Use tasks for steps, gateways for decisions.
   - Use lanes ONLY if roles differ materially.
   - Do NOT invent systems or approvals.
   - Write to diagrams/bpmn/process.bpmn.
   - 
## Result
- Further propting required

# Prompt 3
## Tool + environment
- Tool: Gemini CLI
- Date/time: 2/15/2026 11:20PM
- Repo/branch: [main / UnitySOP]
## Goal
Triage bpmn errors
## Inputs (files referenced)
- process.bpmn
## Prompt
- Restructure the document to declare the diagram tags correctly. They currently cause an error.
## Result
- Further propting required
# Prompt 4
## Tool + environment
- Tool: Gemini CLI
- Date/time: 2/15/2026 11:21PM
- Repo/branch: [main / UnitySOP]
## Goal
Triage bpmn errors
## Inputs (files referenced)
- process.bpmn
## Prompt
- At line 158 I am recieving an error when viewing the document on bpmn.io sying that "bpmndiagram" is not a tag
## Result
- Further propting required
# Prompt 5
## Tool + environment
- Tool: Gemini CLI
- Date/time: 2/15/2026 11:24PM
- Repo/branch: [main / UnitySOP]
## Goal
Triage bpmn errors
## Inputs (files referenced)
- process.bpmn
## Prompt
- Resolve unknown type errors where bpmnShape and bpmnEdge have improper casing
## Result
- Output a diagram with visual errors, not seperated into pools
- Further propting required
# Prompt 6
## Tool + environment
- Tool: Gemini CLI
- Date/time: 2/15/2026 11:24PM
- Repo/branch: [main / UnitySOP]
## Goal
Triage bpmn errors
## Inputs (files referenced)
- process.bpmn
## Prompt
- Edit the diagram by splitting tasks into pools based on  which software is being used for that task: Unity.com,
   Unity Hub, Unity Editor, GitHub, GitHub Desktop
## Output summary
- produced an accurate, though visually disorganized BPMN of the SOP and saved it to the diagrams folder
## Validation performed
- Checked each step to see how it aligned with my hand made chart
- Buggy visuals needed correction before committing

## Human edits I made
- Visually reorganized to look like manual bpmn diagram from week 4
- Renamed to "Unity SOP BPMN"
## Result
- Commited "Unity SOP BPMN" to main branch

