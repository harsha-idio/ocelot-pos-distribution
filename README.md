# Ocelot Desktop App - Release Artifacts

This repository hosts the **release binaries and update metadata** for the Ocelot Desktop App.  
It is used exclusively for distributing installation files and update information via GitHub Releases.

---

## Purpose

- Serve as the **public update server** for the Electron app auto-updater.
- Host versioned installers (e.g., `.exe`, `.dmg`) and update metadata files (`latest.yml`, `.blockmap`).
- Enable Electron's auto-update system to seamlessly deliver new versions to users.

---

## Repository Structure

- No source code or application logic is stored here.
- Contains only the **release assets** attached to GitHub Releases.
- Includes this README as project documentation.

---

## Updating Releases

To publish a new version of the Ocelot Desktop App:

1. Build the application locally or via CI/CD pipeline.
2. Generate the installation files and update metadata through `electron-builder`.
3. Create a new **GitHub Release** on this repository.
4. Upload all required files as release assets:
   - Installer executable (e.g., `OcelotSetup-x.y.z.exe`)
   - Metadata files (`latest.yml`, `.blockmap`, etc.)
5. Publish the release to make it available to the app's auto-update mechanism.

---

*Last updated: August 2025*
