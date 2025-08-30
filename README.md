# g-oss-backup-dr — Backups & DR (restic, pgBackRest, Velero)

**What:** Scripts & compose to back up files (restic) and Postgres (pgBackRest). Velero manifests included for K8s.

**Why:** Replace per‑TB backup licensing with OSS + object storage (MinIO/S3).

**Quick start**
```bash
cp .env.example .env
docker compose run --rm restic backup /data
```
