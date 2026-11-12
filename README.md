# Ntando Mthimkulu | Projects & Performance

Financial-newspaper-inspired static portfolio website for GitHub Pages.

## Included
- Home, Career Profile, Projects, Education, Contact
- Three featured case studies with working relative download paths
- Four additional downloadable project assets (existing workbooks / project ZIPs)
- Two external software engineering capstone links
- Slate and brass editorial design, warm salmon paper styling

## Publish
Upload **the contents** of this folder (index.html, styles.css, script.js, assets/, downloads/) to the root of your GitHub repository. Do not upload the enclosing folder itself. GitHub Pages: Settings > Pages > Deploy from branch > main > /(root).

## PowerShell (from an existing clean clone)
```powershell
cd "$HOME\Documents\Ntando-PM-Clean"
git rev-parse --show-toplevel
# Copy website contents into this directory, then:
git add -A
git commit -m "Publish complete editorial portfolio"
git push origin main
```

The demonstration case studies use fictional data. The broader portfolio may contain other projects not included here because their source files were not available in the current workspace. Do not treat this as a complete archive of every project ever created.
