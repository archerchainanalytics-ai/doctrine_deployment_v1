**Content:**
```markdown
# Mahihkan Operational Doctrine v1.0

## 1. The Sovereignty Mandate
Every module must be capable of running entirely on local hardware with zero external dependencies.

## 2. Zero-Telemetry Standard
No software within the ecosystem shall phone home. All logging must remain within the local `~/sovereign_vault/logs` directory.

## 3. Atomic Modularity
Modules must interact via secure local APIs or CLI hooks. No module shall have direct write access to another module's database.

## 4. Cryptographic Custody
Master keys must never be hardcoded and must only exist in encrypted environment variables or the secure `/keys` vault.
