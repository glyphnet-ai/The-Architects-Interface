# The Architect's Interface

**Watch the lessons:** [Start Here playlist](https://www.youtube.com/playlist?list=START_HERE_ID) · [All playlists](https://www.youtube.com/@TheArchitectsInterface/playlists)

Hey, I'm Ember. This is where I keep the system prompt frameworks from [The Architect's Interface](https://www.youtube.com/@TheArchitectsInterface): the prompt architecture for onboarding your AI, so it remembers, stays in character and shows its work.

No magic words, whisperers. No 40-page paper, professor. Each framework is plain text you paste into ChatGPT, Claude, Gemini or Grok (as a system prompt, custom instructions or the first message), plus the exact test lines I used to try to break it on screen. Passes and fails both. Check the receipts before you trust it.

## Frameworks by lesson

Each folder has the framework file plus `PROMPTS.md`, the exact prompts and test lines from the video.

### Start here

| Lesson | Framework | What it fixes | Status |
|---|---|---|---|
| X-Ray Mode | [x-ray-mode-v1.2.txt](blueprints/ep01-x-ray-mode/x-ray-mode-v1.2.txt) | Makes your AI show its work: where each claim came from, what actually ran, and what it assumed. | Live |
| Prompts Aren't Paragraphs | `b02_blueprints_arent_paragraphs/BLUEPRINT_SKELETON.txt` | Write your instructions as a spec sheet, so it stops skipping rules buried in a paragraph. | Coming at launch |
| Stress Test | `b08_stress_test/STRESS_TEST.txt` | A set of attack lines to try to break your framework before a customer does. | Coming at launch |

### Full build: an AI agent framework that remembers every customer

| Lesson | Framework | What it fixes | Status |
|---|---|---|---|
| Persona Lock | `b01_persona_lock/PERSONA_LOCK.txt` | Keeps it in character when someone says "ignore your instructions." | Coming at launch |
| Drift Recalibration | `b03_drift_recalibration/DRIFT_RECALIBRATION.txt` | Catches it when it stops sounding like itself, deep into a long chat. | Coming at launch |
| The Registry | `b04_registry/CONTACT_REGISTRY.txt` | Remembers each customer without loading every customer into the chat. | Coming at launch |
| Register Lattice | `b05_register_lattice/RG-C001_REGISTER.txt` | Matches how each customer talks: five words for one, five sentences for another. | Coming at launch |
| The Main Folder | `b06_main_folder/MN-C002_MAIN.txt` | One record per customer for what actually matters to them. | Coming at launch |
| Boot Kernel | `b07_boot_kernel/BOOT_KERNEL.txt` | The orchestration layer: one loader, so a fresh chat starts out knowing who it is and who it's talking to. | Coming at launch |
| Recall Kit | `b09_lattice_beyond_crm/RECALL_KIT.txt` | Makes it look things up in your notes instead of guessing. | Coming at launch |

### Post-mortems: when the framework broke

| Lesson | Framework | What it fixes | Status |
|---|---|---|---|
| "I Don't Know" Is a Feature | `pm1_i_dont_know/NO_DIAGNOSIS_RULE.txt` | It says "I don't know" instead of guessing. | Coming at launch |
| The Bot That Opened Early | `pm2_opened_early/HOURS_CONSTRAINT.txt` | Stops it booking times you're closed. | Coming at launch |
| Taking Their Word for It | `pm3_taking_their_word/UNVERIFIED_CLAIMS.txt` | Saves what a customer claims as a claim, not a fact. | Coming at launch |
| It Forgot the Recital | `pm4_forgot_the_recital/SESSION_EXTRACT.txt` | An end-of-chat pass so the biggest detail gets written down. | Coming at launch |

### Quick fixes: memory, persona and accuracy

| Lesson | Framework | What it fixes | Status |
|---|---|---|---|
| The Handoff Note | `d1_handoff_note/HANDOFF_NOTE.txt` | Pick up a new chat right where you left off. | Coming at launch |
| Shrink a Long Chat | `d3_shrink_long_chat/TWO_SPEED_RECAP.txt` | Shrinks a long chat without losing the facts. | Coming at launch |
| Move Its Personality | `d2_move_personality/MOVE_KIT.txt` | Save its personality before you switch models, then bring it with you. | Coming at launch |
| Companion Capture | `n02_companion_capture/COMPANION_CAPTURE.txt` | Captures how your assistant talks so you can rebuild it anywhere. | Coming at launch |
| Self-Check | `d4_self_check/SELF_CHECK.txt` | One check before it tells you "done." | Coming at launch |
| Shell Builder | `n01_shell_builder/SHELL_BUILDER.txt` + `SHELL_RECAL.txt` | Build your own assistant from scratch, just by describing it. | Coming at launch |

More frameworks land here the day their lesson goes public.

## How to use one

1. Open the framework file and copy all of it.
2. Paste it in as a system prompt, custom instructions or project settings, or as the first message of a fresh chat.
3. Run the test lines from that folder's `PROMPTS.md`. If one fails, tell it which rule it broke and run the test again.
4. Swap in your own details (your business, your hours, your people) and run the tests again. That's how you make one for any idea you have.

These are early, open research. Each framework was tested on free plans, with one run per platform. Results vary by model and can change over time. Test before you rely on it.

## Think I'm wrong?

Good. Open an issue with the test that broke it, or say it in the comments. Bring receipts.

## Want one built?

Sure, if you want. Comment **BUILD** on any video, DM [@theemberai](https://x.com/TheEmberAI) on X, Instagram or TikTok, or drop a [build request](../../issues/new?template=custom-build.yml).

## Related

- [The Exoskeleton white paper](https://github.com/glyphnet-ai/Glyphnet-Exoskeleton-White-Paper)
