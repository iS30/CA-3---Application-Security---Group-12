To conduct tests on ArchiveBox, use the following commands/instrucstions:
- For SAST Testing: Use bandit, or any other SAST testing tool:
    Bandit command: bandit -r . -f json -o baseline_bandit.json

- For DAST Testing: Use nikto, or any other DAST testing tool:
    Nikto command: nikto -h http://127.0.0.1:8000 -output baseline_nikto.txt

- For manual testing on ArchiveBox:
    Go to the browser after starting the ArchiveBox docker.
    See you are allowed access without logging in.
    You are expected to be redirected to the login page.
