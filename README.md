# MySplit ZMK Config (nice!nano v2)

This repo uses ZMK's reusable GitHub Action and pins to ZMK v0.2 for stability.
- Manifest (`west.yml`) uses: `import: app/west.yml` and `revision: v0.2`
- Workflow: `.github/workflows/build.yml` -> `uses: zmkfirmware/zmk/.github/workflows/build-user-config.yml@v0.2`
- Targets: see `build.yaml`

To build: push to GitHub and open the Actions tab to download UF2 artifacts.
