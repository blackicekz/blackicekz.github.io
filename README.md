# Вебсайт Blackice.KZ

Мы — независимая лаборатория и сообщество IT энтузиастов в Алматы.

## Вклад

Инструкции как запустить на Windows

```shell
npx http-server .
```

Если получится дальше делать с Jekyll.

```shell
docker run --rm --volume="${PWD}:/srv/jekyll:Z" --publish 4100:4000 jekyll/jekyll jekyll serve --force-polling
```