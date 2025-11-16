# AWEOS All-In-One Release (GitHub-ready)

Release URL: https://github.com/Luzifer-Black/All-in-One-Mining--kosystem

Files included in this release:
- `AWEOS_ALL_IN_ONE_FINAL.tar.gz` — main package (contains installer + modules)
- `AWEOS_ALL_IN_ONE_FINAL.tar.gz.sha256` — SHA256 checksum (used for verification)
- `AWEOS_ALL_IN_ONE_FINAL.tar.gz.asc` — GPG signature (optional; upload when available)
- `install.sh` — one-line installer script (download & run)

## Quick Install (verified)
```bash
curl -L -o AWEOS_ALL_IN_ONE_FINAL.tar.gz https://github.com/Luzifer-Black/All-in-One-Mining--kosystem/releases/download/v1.0.0/AWEOS_ALL_IN_ONE_FINAL.tar.gz && \
curl -L -o AWEOS_ALL_IN_ONE_FINAL.tar.gz.sha256 https://github.com/Luzifer-Black/All-in-One-Mining--kosystem/releases/download/v1.0.0/AWEOS_ALL_IN_ONE_FINAL.tar.gz.sha256 && \
sha256sum -c AWEOS_ALL_IN_ONE_FINAL.tar.gz.sha256 && \
tar -xzf AWEOS_ALL_IN_ONE_FINAL.tar.gz && \
cd AWEOS_ALL_IN_ONE_FINAL && \
sudo bash aweos_all_in_one.sh
```

## Quick Install (auto)
```bash
bash <(curl -s https://github.com/Luzifer-Black/All-in-One-Mining--kosystem/releases/download/v1.0.0/install.sh)
```

## Notes
- If you plan to use GPG verification, upload the `.asc` file and publish your public key on GitHub (Settings → SSH and GPG keys).
- Test on a VM before deploying to production rigs.
