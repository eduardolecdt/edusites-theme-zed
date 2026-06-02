# Installing the EduSites Theme in Zed

## 1. From the extension store (once published)

1. `Cmd + Shift + P` → **zed: extensions**
2. Search for **EduSites**.
3. Click **Install**.
4. `Cmd + K` then `Cmd + T` → select **EduSites Dark** or **EduSites Light**.

## 2. As a dev extension (for local testing)

1. `Cmd + Shift + P` → **zed: install dev extension**
2. Select this repository's folder.
3. `Cmd + K` then `Cmd + T` → select the theme.

## 3. Theme file only (quickest test)

Copy the JSON into Zed's themes folder:

```bash
cp themes/edusites.json ~/.config/zed/themes/
```

Zed detects it automatically. Then select it with `Cmd + K` `Cmd + T`.

## Publishing to the store

Publishing is done via a Pull Request to the
[`zed-industries/extensions`](https://github.com/zed-industries/extensions)
repository, adding this repository as a submodule and registering the extension
in `extensions.toml`. The repository must be **public on GitHub**.
