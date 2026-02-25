# DevSecOps CI Lab – GitHub Actions

## ✅ Checkpoint 1

**Q1:** Trigger is `push`, so workflow runs on every push.  
**Q2:** Runs on GitHub-hosted runner (`ubuntu-latest`).  
**Q3:** Yes, because every push triggers the workflow.

---

## ✅ Checkpoint 2

**Q1:** Red ❌ icon appears.  
**Q2:** `actions/checkout@v4` downloads repo code to runner.  
**Q3:** CI finds errors early, improving reliability.

---

## ✅ Checkpoint 3

**Q1:** Secrets protect sensitive data like API keys.  
**Q2:** Matrix ensures compatibility across Node versions.  
**Q3:** Build artifact is packaged app used for deployment.

---

## ✅ Checkpoint 4

- CI fails when test fails  
- New function requires new test  
- Fixing test makes CI pass  

---

## ✅ Checkpoint 5

**Q1:** Jobs run in parallel  
**Q2:** If JS fails, workflow fails  
**Q3:** Use `needs` to create dependency  

---

## ✅ Checkpoint 6

- Python jobs = 12  
- Node jobs = 3  
- Total = **15 jobs**