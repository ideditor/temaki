## Release Checklist

#### Update version, tag, and publish
- [ ] git checkout main
- [ ] git pull origin
- [ ] npm install
- [ ] npm run build
- [ ] Update version number in `package.json`
- [ ] Update `CHANGELOG.md`
- [ ] git add . && git commit -m 'vA.B.C'
- [ ] git tag vA.B.C
- [ ] git push origin main vA.B.C
- [ ] Open https://github.com/rapideditor/temaki/tags
- [ ] Click `•••` –> `Create Release` and link to `CHANGELOG.md` in `Describe this release`
- [ ] npm publish
