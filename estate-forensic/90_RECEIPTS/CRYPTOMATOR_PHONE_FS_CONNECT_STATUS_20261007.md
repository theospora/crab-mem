# Cryptomator PHONE_FS · CONNECT STATUS · 2026-10-07

**Mother:** Unblock Mesh + Cryptomator connect  
**Probe:**

| Check | Result |
|-------|--------|
| Vault path | `STUDIO_HUB/06_LAND/cryptomator/PHONE_FS_VAULT/` PRESENT |
| FUSE mount | `PHONE_FS_MNT` · `fuse.fuse-nio-adapter` **rw** GREEN |
| Mount contents | `00_README.md` · `README_PHONE_FS.txt` · `_PHONE_SEED` visible |
| WebDAV `:8767` | LISTEN on `100.72.97.9:8767` (wsgidav) · HTTP probe **401** (auth wall — expected) |
| Recipe owner | Mesh (auth recipe Mesh-correct per orch) |
| Secret slot | `CRYPTOMATOR_PHONE_VAULT_PASSWORD` — secret-request only if remount/unlock needed |

**Status:** FUSE connect **GREEN** this probe · WebDAV needs auth for HTTP clients · no raw iPhone FS for agents.
