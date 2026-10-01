# Scoop bucket for AKS Fleet Dashboard

[Scoop](https://scoop.sh) bucket for
[AKS Fleet Dashboard](https://github.com/aavishay/aks-multicluster-dashboard),
a native multi-cluster Kubernetes dashboard for Azure AKS fleets.

```powershell
scoop bucket add aks-fleet-dashboard https://github.com/aavishay/scoop-aks-fleet-dashboard
scoop install aks-fleet-dashboard
```

Upgrade with `scoop update aks-fleet-dashboard`.

The manifest installs the release's `x64-setup.exe` by unpacking it rather
than running it, so the app lives under Scoop's own directory and uninstalls
with `scoop uninstall aks-fleet-dashboard`. It is updated with each release of
the app, the same way as the
[Homebrew tap](https://github.com/aavishay/homebrew-aks-fleet-dashboard).
