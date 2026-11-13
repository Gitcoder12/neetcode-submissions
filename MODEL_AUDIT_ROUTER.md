# Independent Model Audit Router — neetcode-submissions

**Revision date:** 2026-11-13

## Data integrity and evidence rules
- Preserve the maintainer's original solutions and explanations; never replace them with generated placeholders or claim a problem was accepted unless the platform provides evidence.
- Keep sample inputs/outputs clearly labelled. Do not invent judge results, runtime measurements, acceptance rates or problem statements.
- Preserve third-party platform names, problem links and licence/usage restrictions. Do not republish protected problem text beyond permitted excerpts.
- Test claims require reproducible commands and results on the exact commit reviewed.

## README preservation
Recover the last maintainer-authored README from Git history and preserve it intact. Do not rewrite or replace it. Append AI-generated notes only as a dated, clearly labelled secondary section at the very bottom.

## Independent reviewers
1. **Correctness reviewer:** algorithms, edge cases, complexity and proof sketches.
2. **Test reviewer:** sample tests, boundary tests, randomized/brute-force cross-checks and language/runtime.
3. **Attribution reviewer:** problem links, source credit, platform rules and licensing.
4. **Documentation reviewer:** README history, explanation quality, setup and link checks.
5. **Career reviewer:** verify that claims reflect the owner's actual solutions and skill level.

## Audit workflow
1. Record URL, default branch and exact HEAD SHA.
2. Inventory languages, problem mappings, source files and dependencies.
3. Match each solution to the correct problem/variant without copying protected statements.
4. Run documented tests and independently test edge cases.
5. Compare README with its pre-AI history and preserve the original.
6. Check for secrets, personal data, dead links, fabricated acceptance/performance claims and duplicate/incorrect solutions.
7. Publish findings before changing code.

## Required finding format
Severity (**P0/P1/P2/P3**), exact path/line, problem identifier/link, reproduction, expected vs actual, evidence and SHA, confirmed/suspected/unverifiable status, minimal fix, regression test, and README/data impact.

## Merge gate
- [ ] No invented judge results, benchmark numbers or accepted-status claims.
- [ ] Problem mapping and algorithm implementation are correct.
- [ ] Tests are run on the exact reviewed commit or marked NOT RUN.
- [ ] The original README is preserved; AI notes appear at the bottom only.
- [ ] No leaked credentials, private personal details or prohibited problem content.
- [ ] Independent second review and maintainer approval completed.

Repository: **neetcode-submissions**. Do not infer correctness from a filename or a model-generated explanation. Do not merge, delete, overwrite original solutions or alter the original README during audit. The repository owner has final approval.
