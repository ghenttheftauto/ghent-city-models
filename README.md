# ghent-city-models

3d model verzameling voor vibecoders, maakt er coole shit mee kenny.

## Gebruiken

```sh
git lfs install
git clone git@github.com:ghenttheftauto/ghent-city-models.git
```

Of één model rechtstreeks: `https://media.githubusercontent.com/media/ghenttheftauto/ghent-city-models/main/models/<tegel>/<naam>/<naam>.glb`

## Structuur

```
models/<tegel>/<naam>/<naam>.glb   # glTF binary, meters, Y-up
models/<tegel>/<naam>/preview.png  # optioneel
```

Eén map per model onder zijn tegel, namen zoals in de tegelmappen (`kuip/stadshal`, `kuip/postplaza`).

## Bijdragen

- `.glb` liefst; `.blend`, `.fbx`, `.obj` mogen ook.
- `git lfs install` vóór ge commit, anders belanden de binaries in git zelf.
- Alleen wa ge zelf gemaakt hebt of mag delen.

## Licentie

[CC BY 4.0](LICENSE): doe ermee wa ge wilt, vermeld de bron.
