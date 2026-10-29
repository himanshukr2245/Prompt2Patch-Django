# Team Submission & AI Log

> [!IMPORTANT]
> **Challenge Duration**: 45 Minutes | **Total Points**: 100 Points Rubric
> **Evaluation Advisory**: Speed is not the winning criterion. Submissions completed via lazy 1-shot prompts (e.g., "fix this whole file") will be penalized under **Pillar 1: Prompt Quality**. Use this log to paste 3 of your prompt sequences.

---

## 1. Team Information
- **Team Name**: Delta
- **Members**: 1. ______________________  2. ______________________  3. ______________________
- **Working Branch**: `Delta`

---

## 2. AI Prompting Evidence (Paste your 3 best prompts)
*Show how you guided the AI through iterative reasoning rather than asking it to auto-solve blindly:*

### Prompt 1
- **Defect / Area Investigated**: Baseline failures and lifecycle root cause
- **Exact Prompt Sent to AI**:
  > Clone the repository into a new workspace folder. Run the baseline tests, identify the failing behaviors, and explain each root cause before changing code.

---

### Prompt 2
- **Defect / Area Investigated**: Archive, restore, pagination, and stats service logic
- **Exact Prompt Sent to AI**:
  > Use the failing Django tests to trace the archive/restore flags, active-versus-archived queries, pagination totals, and aggregate statistics. Make the smallest service-layer changes that correct their state transitions and counters.

---

### Prompt 3
- **Defect / Area Investigated**: URL protocol and QR-code implementation
- **Exact Prompt Sent to AI**:
  > Add strict service-level validation for HTTP and HTTPS target URLs, implement both backend and frontend QR URL generation, add a protocol regression test, then rerun the complete Django suite.

---

## 3. Final Submission Checklist Before Calling Judge
- [ ] All test suites pass 100% (`make test`)
- [ ] Web application manually verified in browser (`make run`)
- [x] Code committed to a dedicated branch (`Delta`, not `main`)
- [ ] Pull Request opened with clean description
- [ ] 3 prompt sequences documented above in Section 2
