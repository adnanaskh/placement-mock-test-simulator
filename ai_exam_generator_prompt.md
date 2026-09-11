# 🤖 Master AI Prompt Guide for Custom Exam Question Generation

Use this prompt with **ChatGPT (GPT-4o), Claude (3.5 Sonnet), or Gemini (1.5 Pro / Flash)** to populate or modify questions for your custom placement examinations.

---

### 📋 Copy-Pasteable Master AI Prompt:

```markdown
You are an expert recruitment assessment question setter for premier tech companies (TCS, Infosys, Cognizant, Wipro, Accenture).

I am providing you with an examination JSON structure. Your task is to modify OR generate realistic campus recruitment questions while strictly adhering to the formatting rules below.

### 🚨 STRICT RULES FOR AI:
1. DO NOT MODIFY ANY IDs: Never change section IDs ("id": "tcs_sec_...") or question IDs ("id": "tcs_num_01", "inf_rea_01", etc.). All IDs must remain 100% identical.
2. DO NOT CHANGE SCHEMA KEYS OR STRUCTURE: Keep "title", "company", "totalTimeMinutes", "sectionalTiming", "negativeMarking", "sections", "questions", "marks", and "negativeMarks" intact.
3. WHAT YOU MUST MODIFY:
   - "text": The question statement. You can format code with ```c, ```java, ```python, or ```text, and inline code with `varName`.
   - "options": An array of exactly 4 strings.
   - "correctAnswer": The 0-indexed integer of the correct option (0 = Option A, 1 = Option B, 2 = Option C, 3 = Option D).
   - "explanation": Step-by-step mathematical, logical, or programming solution explaining why the answer is correct.
4. RETURN FORMAT: Return ONLY the valid, pure raw JSON object. Do not include markdown preamble, chit-chat, or postscripts.
```

---

### 📦 Official Syllabus Question Counts Reference

| Company Preset | Sections & Question Breakdown | Total Time | Timing Mode |
| :--- | :--- | :--- | :--- |
| **TCS iON NQT** | • Numerical Ability: **20 Qs**<br>• Reasoning Ability: **20 Qs**<br>• Verbal Ability: **25 Qs** | **75 Minutes** | Sectional Timed |
| **Infosys SP/SE** | • Reasoning Ability: **15 Qs**<br>• Mathematical Ability: **10 Qs**<br>• Verbal Ability: **20 Qs**<br>• Pseudocode: **5 Qs**<br>• Puzzle Solving: **4 Qs** | **100 Minutes** | Section-Locked (Strict) |
| **Cognizant AMCAT** | • Quantitative Ability: **25 Qs**<br>• Automata / Tech MCQs: **10 Qs** | **85 Minutes** | Free Navigation |
