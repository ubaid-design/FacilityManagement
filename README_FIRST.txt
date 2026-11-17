FACILITY MANAGEMENT — INFO.PLIST BUILD FIX

This replacement package fixes the missing Info.plist error.

Repository root should contain:
- codemagic.yaml
- project.yml
- FacilityManagement/FacilityManagementApp.swift
- FacilityManagement/ContentView.swift
- FacilityManagement/Info.plist
- FacilityManagement/Assets.xcassets/AppIcon.appiconset/Contents.json
- FacilityManagement/Assets.xcassets/AppIcon.appiconset/FacilityManagementIcon.png

Keep the folder nesting exactly as shown. Do not upload inner files to the repository root.

GitHub:
1. Open your FacilityManagement repository.
2. Use Add file > Upload files.
3. Upload corrected project.yml and codemagic.yaml to the repository root, replacing existing files.
4. Upload the entire corrected FacilityManagement folder, preserving folder structure and overwriting files when prompted.
5. Commit changes to main.
6. Start the same Codemagic workflow again.

This workflow performs an unsigned compile check only. A signed, installable IPA requires a unique bundle identifier and Apple signing credentials configured in Codemagic.
