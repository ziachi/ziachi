# ziachi

Low-level Android tinkerer. I work close to the metal — build systems, kernel integration, vendor HALs, and whatever breaks between them.

---

## What I Do

I take unsupported hardware and make modern Android run on it.  
That means patching frameworks, writing SELinux policy, tuning memory for 2GB devices, and debugging everything from bootloops to HAL crashes — until it works.

## Skills

**Android Platform**  
AOSP build system (`lunch`, `mka`, `repo`) · Device tree & vendor blobs · SELinux policy (vendor/platform type separation, dontaudit registry) · Framework patching (`frameworks/base` fork) · Android HAL integration (fingerprint, audio, sensors, WiFi)

**Kernel & Low-Level**  
Prebuilt kernel integration · KernelSU · Init scripts & property management · cgroup workarounds for legacy kernels · Spectrum-based kernel profile switching

**System Optimization**  
Low-memory tuning (LMK, ZRAM, heap limits) · App debloat via `Android.bp` overrides · Background process & notification optimization · VM tuning for constrained devices

**Engineering Practice**  
Root cause analysis from logcat traces · Per-fix commit discipline · Written documentation (changelogs, bug analysis, dontaudit registry) · Building for hardware everyone else gave up on

## Process

```
logcat → trace root cause → write fix → build → verify → document
```

Every fix is one commit. Every commit has a reason.  
No force-push. No shortcuts. Append-only history.

## Contact

[@kalomakan](https://t.me/kalomakan) · [GitHub](https://github.com/ziachi)
