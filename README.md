# ChatGPT QA Testing Report  

## Overview  
This project documents a **manual QA testing analysis** of OpenAI’s ChatGPT, focusing on **accuracy, instruction adherence, usability, and content moderation.** The goal was to identify **defects in AI behavior** and suggest improvements.

## Testing Approach  
- **Exploratory Testing:** Engaging with ChatGPT to uncover inconsistencies.  
- **Scenario-Based Testing:** Simulating real-world interactions to evaluate responses.  
- **Defect Logging:** Documenting issues with severity ratings and recommendations.  

## Key Findings  
- AI **sometimes ignores explicit instructions.**  
- AI **overpromises capabilities** (e.g., claiming to provide real-world data when it generates synthetic content).  
- **Chat UI issues** (e.g., lag causing accidental double submissions).  
- **Overzealous content moderation** misclassifies neutral discussions as violations.  

## Project Contents  
- **QA_Report.md** → Detailed defect report with findings & solutions.  
- **Test_Cases.md** → Structured test cases for evaluating ChatGPT behavior.  
- **Bug_Tracking_Log.md** → Logged defects with severity levels.  

## How to Use  
1. **Review `QA_Report.md`** to understand the major findings.  
2. **Check `Test_Cases.md`** for structured test execution.  
3. **Use `Bug_Tracking_Log.md`** to explore identified issues.  

---

## Conclusions
- ChatGPT has many significant flaws in semantic understanding, adherance to instruction, programmed overconfidence in its own abilities and accuracy without sufficient disclaimers which could lead to negative UX. The errors are consistent and reproduceable which should indicate that they are also fixable. It is the author's opinion that issues of confidence in the output of AI should be prioritized over a proverbial arms race.

### Future Work  
- Expanding test coverage to **AI-generated code accuracy.**  
- Automating some validation using **AI-driven testing frameworks.**  
- Testing **consistency across different versions of ChatGPT.**  

---

📌 **Contributors:** Martin Krizan  
📌 **License:** MIT  
