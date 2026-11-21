# SigmaOS-arp-scan

SigmaOS integration component for **arp-scan**.

## Commands

```bash
sigmaos-arp-scan install   # install package + deploy defaults
sigmaos-arp-scan deploy    # copy config templates to $HOME
sigmaos-arp-scan status    # binary/package/config report
sigmaos-arp-scan reset     # remove deployed config
sigmaos-arp-scan open      # launch the application
```

## Design

- Shell-based component manager (Omarchy-style per-app repos)
- Secure defaults; no secrets stored
- Deterministic `test.sh` with isolated `$HOME`
