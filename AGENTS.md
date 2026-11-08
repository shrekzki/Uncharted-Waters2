# Local project instructions

- This is a separate local working copy of `creamycalf/Uncharted-Waters2`, on branch `codex/keyboard-gamepad-controls`.
- The user states that the required authorization to modify this project has been obtained. Keep changes local; do not push to any remote unless explicitly requested.
- Never commit the base APK, extracted game/assets, personal saves, test saves, signing keys, or generated APKs. The repository `.gitignore` excludes these inputs and outputs.
- Keep Android emulator checks distinct from iPlay 50 Mini hardware checks. A successful compile or APK signature check is not evidence of runtime input behavior.
- When changing build inputs, record their source and integrity check in `docs/handoff.md`; never copy credentials or signing keys into documentation.
- Update `README.md`, `mobile/README.txt`, `docs/architecture.md`, and `docs/handoff.md` when the input architecture or build workflow changes materially.
