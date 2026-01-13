# MTX-RSID-GHN Protocol: HCU Activation Manual

## 1. Philosophy (Zero Friction)
An HCU (Hybrid Chain Unit) is not merely a "prompt." It is a compiled body of expert experience packaged into instructions that the AI cannot ignore.
We do not write code from scratch. We activate pre-configured "Cores."

## 2. Activation Sequence (SOP)

### Phase 1: Extraction
1. Navigate to the `/HCU_Registry` folder.
2. Select the required module (e.g., `HCU-CTX-0001`).
3. Locate the `"system_prompt_payload"` field.
4. **CRITICAL:** Copy the text inside the quotation marks in its entirety.

### Phase 2: Injection
1. Open your LLM (Recommended: **Gemini/Claude/ChatGPT**).
2. If a "System Prompt" field is available (in the API or Workbench), paste the text there.
3. If using a standard chat interface, paste the text as the **first message**.
4. Press Enter.

### Phase 3: Execution
1. Await confirmation from the AI (it should respond in character, for example: *"Ready. Please provide the LaTeX snippet..."*).
2. Upload your data (PDF, text, code).
3. Retrieve the output.

## 3. Best Practices
*   **Context Window:** Use models with a context window of 16k+ tokens.
*   **Temperature:** For code generation (GRID/CORTEX), set the value to `0.0` or `0.2`. For creative tasks (NEXUS), set it to `0.7`.
*   **New Chat:** Always initiate the HCU in a **new chat** to prevent previous context from interfering with the instructions.

## 4. Troubleshooting
| Symptom | Diagnosis | Fix |
| :--- | :--- | :--- |
| AI refuses to write code | Safety Filter triggered | Clarify that this is an "Academic Simulation" or "Local Environment." |
| AI forgets instructions | Context overflow | Start a new chat and re-inject the HCU. |
| Poor formatting | Underpowered model | Switch to a more capable LLM or agent. |

---
*Matrix RSID // Global Hybrid Network*
