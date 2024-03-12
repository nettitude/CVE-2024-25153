# CVE-2024-25153
This is a proof of concept for CVE-2024-25153, a Remote Code Execution vulnerability in Fortra FileCatalyst Workflow 5.x, before 5.1.6 Build 114.

Full technical details can be found at [https://labs.nettitude.com/blog/cve-2024-25153-remote-code-execution-in-fortra-filecatalyst](https://labs.nettitude.com/blog/cve-2024-25153-remote-code-execution-in-fortra-filecatalyst)

## Usage
Run the exploit using the following command:
```
CVE-2024-25153.py --host <hostname> --port <port> --url <url> --cmd <command>
```

Only the `--host` argument is required, and others are optional. Use the `--help` argument for full usage instructions.

## Disclaimer
This proof-of-concept is for demonstration purposes and should not be used for illegal activities. LRQA Nettitude are not responsible for any damage caused by the use or misuse of this code.