## Hi!

Detection engineering and security research: Sigma rules, Atomic Red Team tests, Sentinel hunting queries + ...

## Contributions

**SigmaHQ/sigma**
- Suspicious Kerberos Ticket Request (ScriptBlock + CLI): removed `.GetRequest()` requirement ([#6296](https://github.com/SigmaHQ/sigma/pull/6296))
- UFW Disable Attempt: fixed broken `ufw-init` detection and broadened UFW disable coverage ([#5978](https://github.com/SigmaHQ/sigma/pull/5978))

**redcanaryco/atomic-red-team**
- T1546.005: added Trap DEBUG atomic test ([#3338](https://github.com/redcanaryco/atomic-red-team/pull/3338))
- T1027/T1027.013: added character array and password-protected ZIP obfuscation tests ([#3279](https://github.com/redcanaryco/atomic-red-team/pull/3279))
- T1496 (Resource Hijacking): added Windows CPU load simulation ([#3275](https://github.com/redcanaryco/atomic-red-team/pull/3275))

**Azure/Azure-Sentinel**
- hunt_LOLBins.yaml: repaired entity mappings ([#15144](https://github.com/Azure/Azure-Sentinel/pull/15144))

**NVIDIA/NemoClaw**
- Fixed file descriptor leak in `acquireOnboardLock` ([#1052](https://github.com/NVIDIA/NemoClaw/pull/1052))
- Preflight: auto-create swap on low-memory VMs to prevent OOM during sandbox build ([#419](https://github.com/NVIDIA/NemoClaw/pull/419))
