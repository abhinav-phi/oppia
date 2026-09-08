
Run details:
- Command: python -m scripts.run_acceptance_tests --suite=practice-question-submitter/submit-practice-questions-for-review-and-check-thier-status --headless
- Machine: WSL2 Ubuntu 22.04, Python 3.10.16, node 16.13.0 (oppia pinned)
- Commit: 044112d (PR branch head)
- Exit code 0: run_acceptance_tests.py calls sys.exit(jest_return_code) => all 3 tests passed

## Old-code vs new-code harness result

See comment: the pre-fix implementation fails with the exact CI error; the fixed implementation passes.
