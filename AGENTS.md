# AGENTS.md

## Project overview
NetPractice is a 42 project focused on learning the basics of networking through a browser-based training interface. The goal is to understand TCP/IP addressing, subnet masks, default gateways, routers, switches, and related networking concepts by solving 10 networking exercises.

## Core objectives
- Complete all 10 levels of the training interface.
- Configure each network so it works correctly.
- Export one configuration file per level and keep it in the repository root.
- Produce a clear and complete README that explains the project and how to run it.

## Working rules for agents
- Treat the project as a practical networking exercise, not just a coding task.
- Use the provided training interface locally to verify each solution.
- Prefer reasoning from networking fundamentals rather than guessing values.
- Validate every change by checking the interface behavior and logs.
- If AI is used, understand the generated content fully and be able to explain it.
- Do not rely on AI output without review, testing, and peer validation.

## How to run the project
- Run the provided shell script if available: ./run.sh
- If the script does not work, start a local server with:
  - python3 -m http.server 49242
- Open the interface in a browser at the local address shown by the server.
- Enter the correct login in the interface before solving levels.

## Required repository contents
- A root README.md written in English.
- One exported configuration file per level placed at the repository root.
- The training interface files should remain available under the project folder.

## README requirements
The root README.md must include:
- An italicized first line in the form:
  - This project has been created as part of the 42 curriculum by <login1>[, <login2>[, <login3>[...]]].
- A Description section explaining the project goal and purpose.
- An Instructions section covering how to run the training interface, export configurations, and submit the work.
- A Resources section listing relevant networking references and explaining how AI was used.
- References to networking concepts such as TCP/IP addressing, subnet masks, default gateways, routers, switches, and OSI layers.

## Submission expectations
- Submit the repository with all 10 exported configuration files at the root.
- Make sure every exported file is named and stored correctly.
- Double-check that the repository contents match the expected project structure before submission.
- Be prepared to explain your configurations during evaluation.

## Evaluation guidance
- The defense may include random levels and a limited time window.
- Use the interface logs to understand mistakes.
- Do not use external tools during the evaluation.
- A simple calculator is acceptable, but the project should be understood well enough to explain it clearly.
