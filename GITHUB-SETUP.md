# Команды: репозитории на GitHub и Pages

Сначала на github.com под аккаунтом **Kapustis72** создайте **пустые** репозитории (без README, без .gitignore):

- `putlist` (private или public)
- `grelka` (private или public)
- `newco3` (private или public)
- `Kapustis72.github.io` (**public** — иначе Pages не откроется модератору RuStore)

`CO3` и `CO_Timeweb` не трогать.

Затем на ноутбуке:

```powershell
# Про-Путь
cd C:\putlist
git remote add origin https://github.com/Kapustis72/putlist.git
git push -u origin main

# Грелка
cd C:\grelka
git remote add origin https://github.com/Kapustis72/grelka.git
git push -u origin main

# newco3
cd C:\newco3
git remote add origin https://github.com/Kapustis72/newco3.git
git push -u origin main

# Политики
cd C:\legal-pages
git remote add origin https://github.com/Kapustis72/Kapustis72.github.io.git
git push -u origin main
```

GitHub → `Kapustis72.github.io` → **Settings → Pages → Build and deployment**: Source = Deploy from a branch, Branch = `main`, Folder = `/ (root)` → Save.

Через 1–2 минуты в инкогнито:

- https://kapustis72.github.io/proput.html
- https://kapustis72.github.io/grelka.html

Эти URL — в поле «Политика конфиденциальности» карточек RuStore. Email поддержки: `colorconnectoriginal@yandex.ru`.
