# ShieldCrash
Windows Defender 0day Vulnerability

Microsoft has failed to properly patch ShieldBreak [CVE-2026-69414](https://msrc.microsoft.com/update-guide/en-US/advisory/CVE-2026-69414), under specific conditions it is still possible to trigger the exact same problem that was caused by ShieldBreak. While Microsoft fixed several things to prevent re-exploiting the issue, they missed a spot where ShieldBreak can still be exploited.

This PoC demonstrates an arbitrary file read as SYSTEM with September 2026, all supported windows versions are affected.

<img width="1920" height="1032" alt="image" src="https://github.com/user-attachments/assets/138f02fb-8c21-4bcf-bea9-0c835829a719" />

I might rework this later into a full SYSTEM PoC but for now I'm dropping this skeleton PoC because I'm feeling a bit lazy.
