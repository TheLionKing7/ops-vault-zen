# Aetoes Command Center

Build a high-end, dark-mode executive dashboard for a law firm named 'Aetoes Legal' called 'Aetoes Ops Hub'. Use a deep navy (#0B132B) and gold/cyan theme. Include a sidebar with 3 main navigation tabs:

Vault Search (Dual-Vault Engine): A search interface with a toggle switch between 'Vault A: Internal Briefs' and 'Vault B: Nigerian Juris OS'. Show a query bar, metadata filters (Court Level, Year, Ratio Decidendi), and simulated RAG search results displaying verified PDF page citations.*

Case Red-Teamer: An upload drop zone where lawyers can drag-and-drop an opposing party's brief. Show a mock 'Analyze Brief' button that generates a structured 'Battle Card' showing procedural flaws, opposing argument strength ratings, and binding Supreme Court counter-precedents.*

Statutory Tracker: A calendar view that calculates filing deadlines automatically based on Nigerian Court Rules and displays upcoming court dates with alert statuses."*

Step 2: Add Real Interactivity

Interactive Mocking: Ask Lovable to populate the prototype with realistic dummy data (e.g., actual Nigerian Supreme Court cases, sample motions, and realistic dates) so the partners can click around during your presentation.

Simulated AI Responses: You can instruct Lovable to bake in realistic "AI streaming text" so when they click "Run Red-Team Analysis," it visually simulates processing and renders a "McKinsey-grade" output report.

Step 3: Publish & Pitch

Deploy: Click Publish in Lovable to generate a live, password-protected or public URL.

Present: Bring the live app up during your partner call. Showing them a live interface where they can see where their internal briefs will sit, how Vault B works, and how citations are pinned to pages will instantly alleviate their skepticism about AI "hallucinations" or confusion.

This project was built with [Lovable](https://lovable.dev).

**Live app**: https://ops-vault-zen.lovable.app

## Build with Lovable

Continue developing this project in the [Lovable editor](https://lovable.dev/projects/40e4d007-6fd4-4f48-9883-10bf5b62cf80).

- **Ship faster**: describe what you want to build and Lovable handles the code.
- **Stay in sync**: every change made in Lovable is committed straight to this repository.
- **Full ownership**: this code is yours. Push to `main` on GitHub and your changes sync back into Lovable, ready for your next prompt.

## Development

Prefer working locally? You need Node.js and npm — [install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating).

```sh
git clone <this-repository-url>
cd <repository-name>
npm i
npm run dev
```
