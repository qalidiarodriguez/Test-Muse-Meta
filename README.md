🧪 Muse + GitHub | AI Mobile Integration Testing

An experimental QA project by Pam.

📌 About this project

This repository is my testing environment to explore Meta Muse's ability to interact with GitHub and other applications directly from a mobile device.

As a QA Engineer, I want to evaluate how AI assistants access, read, modify, and manage digital resources while maintaining human supervision and control.

The main focus is not just whether an AI assistant can perform a task, but whether it performs it correctly, reliably, and safely.

🎯 Testing Objectives

1. Evaluate GitHub connectivity through Meta Muse.
2. Verify repository and file reading capabilities.
3. Test file creation and modification.
4. Evaluate permission boundaries and approval workflows.
5. Explore mobile-first automation across different applications.
6. Document limitations, unexpected behaviors, and potential defects.

🧪 Test Scenarios

Phase 1 — Repository Reading

Status: 5/5 reported as successful by Muse.

Repositories included in the experiment:

ID| Repository| Test objective
TC-001| lidipamelarodriguezvigueras.github.io| Read personal website repository
TC-002| qa-portfolio| Read QA portfolio content
TC-003| qa-project-Urban-Routes-es| Read UI automation project
TC-004| qa-project-Urban-Grocers-app-es| Read API testing project
TC-005| postman-api-tests-tripleten| Read Postman collection

Phase 2 — File Creation

- Request creation of a Markdown file.
- Verify file name, location, and content.
- Check whether changes require user approval.
- Confirm that the file actually exists in GitHub.

Phase 3 — File Modification

- Request an update to an existing file.
- Verify that only the requested content changes.
- Check whether the original content is preserved.
- Confirm the final version in GitHub.

Phase 4 — Cross-Application Automation

Explore Muse's ability to interact with other connected applications from a mobile device.

🔍 QA Methodology

Each test will document:

- Test Case ID
- Preconditions
- Test Steps
- Expected Result
- Actual Result
- Evidence
- Status: Passed / Failed / Blocked / Not Tested

A task is not considered passed just because the AI reports success. The result must be independently verified.

🔐 Security & Scope

- Use a dedicated testing repository for modifications.
- Keep portfolio repositories protected from experimental changes.
- Never expose access tokens, passwords, or private credentials.
- Review and approve changes before they are committed.
- Verify actual GitHub changes rather than relying exclusively on AI responses.

💡 Project Philosophy

AI can assist, automate, and interact with digital tools, but reliability must be tested.

Don't just trust AI. Test it.

---

Created by Pam | QA Engineer | AI & Automation Explorer
---

## 📄 Results and reports

- [TEST-MUSA.md](TEST-MUSA.md) — Phases 1–4: repository reading (5/5), file creation, file modification, and cross-application automation. All verified by re-reading from GitHub.
- [REPORT-BROWSER-VACANTES.md](REPORT-BROWSER-VACANTES.md) — TC-009: Browser demo, QA Junior vacancy search in Mérida (National Soft, Tester Automatización Jr), with YouTube Short evidence. Passed with human help for the captcha.
