inside dir with `PKGBUILD`

Install:
```sh
makepkg --syncdeps --install --clean --nocheck
```

Just update pkgver inside `PKGBUILD` (-> calls `pkgver()`)
```sh
makepkg --nobuild --nodeps
```
