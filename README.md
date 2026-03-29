# The-Advisor-s-AI-Playbook-Templates-Prompts
# The Advisor's AI Playbook: Templates & Prompts

All templates, prompts, and starter files referenced in **5 AI Workflows You Can Actually Use This Week** by Savvy Wealth.

## Context

These files can be used in Claude Cowork to personalize the way that Cowork outputs text back to you. All of these files are cobbled together from what we've found online and tested internally at Savvy.

## How to Download

Click the green **"Code"** button at the top of this page, then **"Download ZIP."** Unzip the folder and you'll have all the template files ready to use. If you copy text directly from the GitHub page, you'll lose the markdown formatting.

## Remember

When copying these files into Claude, click the **"Raw"** button on the top right of each file on this page. You must copy the raw version in to preserve the Markdown formatting.

## Instructions

1. Download Claude Cowork onto your computer. It cannot be accessed on a web browser.
2. Go to Settings > Cowork. Hit "Edit" next to "Global instructions". Paste in the `CLAUDE.md` file contents and fill out the bracketed portions. This is your overarching instruction set that Cowork will always read first.
3. Set up a folder dedicated to Claude Cowork on your computer. For example, you can make one called `claude-cowork` somewhere on your computer.
4. In that new folder, set up a folder titled `context`. Paste in each of the other MD files listed below and fill in the bracketed items for each.
5. When you open the Claude desktop app, you can hit the "Cowork" tab on the top bar. You can use Cowork to enter a prompt just like you would use the Chat functionality.
6. For Cowork to pick up on your preferences, make sure to select the folder you created and put the MD context files in. Hit the "Work in a folder" button on the bottom left of the chat box and select the folder you created in Step 3. You must ensure that it is selected each time you run a prompt (it may sometimes default to not selecting it).

## Files

### Core Setup (Workflow 1)

| File | Description |
|------|-------------|
| `CLAUDE.md` | Global instructions file. Tells Claude who you are and your top-level preferences. |
| `voice-dna.md` | Teaches Claude how you write. Writing rules, formatting rules, banned phrases, and your writing samples. |
| `critic-agent.md` | Quality control. Reviews Claude's output against your voice, audience, and standards. Type "run the critic" to activate. |
| `audience-profile.md` | Describes who you're writing for. What they care about, how they prefer to receive info, what turns them off. |
| `professional-identity.md` | Describes who you are. Your role, philosophy, stakeholders, and standards. |
| `working-preferences.md` | How you want Claude to behave. Output format, process, guardrails. |

### Client Niche Personas (Workflow 2)

| File | Description |
|------|-------------|
| `niche-persona-tech-professional.md` | For advisors serving tech employees. RSUs, ISOs, AMT, concentrated stock, IPO planning. |
| `niche-persona-athlete.md` | For advisors serving professional athletes. Short career windows, endorsement income, multi-state tax. |
| `niche-persona-business-owner.md` | For advisors serving business owners. Entity structures, succession planning, buy-sell agreements. |

### Content & Compliance (Workflows 3-4)

| File | Description |
|------|-------------|
| `linkedin-content-system-prompt.md` | System prompt for drafting LinkedIn posts in your voice. |
| `compliance-review-prompt.md` | First-pass compliance review against SEC Marketing Rule 206(4)-1. |

## How to Use These for Other AI Tools

These files are written for Claude Cowork, but the content works with any AI tool:

- **ChatGPT:** Go to Explore GPTs > Create. Paste the relevant system prompt into the Instructions field. Upload reference docs as Knowledge files.
- **Gemini:** Create a Gem. Paste instructions and upload your tone/audience profiles.
- **Perplexity:** Use the system prompt content as context in your conversations.

## About Savvy Wealth

Savvy is the trusted partner for independent financial advisors, combining infrastructure, service, and AI-native tools to make great advice easier to deliver. Learn more at [savvywealth.com](https://savvywealth.com).
