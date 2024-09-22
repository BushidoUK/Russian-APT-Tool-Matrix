## Defense Evasion Tools

> [!TIP]
> - Various freely available malware detection tools specialize in identifying and removing stealthy threats like rootkits.
> - They offer capabilities such as scanning for hidden processes, files, and drivers, analyzing system memory for malicious modules, and monitoring system hooks for unauthorized modifications.
> - These tools provide detailed insights into system internals, helping to uncover deeply embedded malware that standard antivirus programs might miss.

> [!IMPORTANT]
> - Malicious actors can abuse these rootkit detection tools to interfere with security tools, file and registry tampering to disrupt tool functionality, and memory corruption to prevent detection.
> - By using these tools for privilege escalation, an adversary can disable or alter the operation of security software, removing the method systems use to detect or prevent threats.

| Tool Name | Threat Group Usage |
|---|---|
| EDRSandBlast | COZY BEAR |
| libprocesshider | Sandworm |
| PowerShellRunner | Turla |
| SDelete | Sandworm |
| VirtualBox Driver | Turla |
