# Instalando o EduSites Theme no Zed

## 1. Pela loja de extensões (após publicado)

1. `Cmd + Shift + P` → **zed: extensions**
2. Pesquise por **EduSites**.
3. Clique em **Install**.
4. `Cmd + K` depois `Cmd + T` → selecione **EduSites Dark** ou **EduSites Light**.

## 2. Como extensão de desenvolvimento (para testar localmente)

1. `Cmd + Shift + P` → **zed: install dev extension**
2. Selecione a pasta deste repositório.
3. `Cmd + K` depois `Cmd + T` → selecione o tema.

## 3. Só o arquivo de tema (teste mais rápido)

Copie o JSON para a pasta de temas do Zed:

```bash
cp themes/edusites.json ~/.config/zed/themes/
```

O Zed detecta automaticamente. Depois selecione com `Cmd + K` `Cmd + T`.

## Publicando na loja

A publicação é feita via Pull Request no repositório
[`zed-industries/extensions`](https://github.com/zed-industries/extensions),
adicionando este repositório como submódulo e registrando a extensão no
`extensions.toml`. O repositório precisa ser **público no GitHub**.
