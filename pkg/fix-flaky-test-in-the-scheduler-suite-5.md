# Fix flaky test in the scheduler suite

Transient upstream 5xx responses now retry three times with exponential backoff and jitter.

Change #5 of 5 on branch `pr/20260811-130203-5-fix-flaky-test-in-the-scheduler-suite`.
