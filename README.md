<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=200&section=header&text=GitHub%20Achievement%20Farm&fontSize=50&fontColor=fff&animation=twinkling&fontAlignY=36&desc=Автоматически%20получай%20все%20ачивки%20на%20профиле&descAlignY=56&descSize=18" width="100%"/>

[![Stars](https://img.shields.io/github/stars/AppsGanin/achievement-github-farm?style=for-the-badge&logo=github&labelColor=1a1a2e&color=f7b731)](../../stargazers)
[![Forks](https://img.shields.io/github/forks/AppsGanin/achievement-github-farm?style=for-the-badge&logo=git&labelColor=1a1a2e&color=4ecdc4)](../../forks)
[![Issues](https://img.shields.io/github/issues/AppsGanin/achievement-github-farm?style=for-the-badge&logo=github&labelColor=1a1a2e&color=ff6b6b)](../../issues)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen?style=for-the-badge&logo=git&labelColor=1a1a2e)](../../pulls)
[![Actions](https://img.shields.io/badge/GitHub_Actions-автоматизация-2088FF?style=for-the-badge&logo=githubactions&logoColor=white&labelColor=1a1a2e)](../../actions)

[🚀 Быстрый старт](#-быстрый-старт) · [📋 Все ачивки](#-ачивки) · [⚙️ Автоматизация](#-как-работает-автоматизация)

</div>

---

> **Дисклеймер.** Этот проект создан в образовательных целях и для личного использования. GitHub-ачивки — косметическая функция, они не влияют на рейтинги, рекрутинг или доступ к платформе. Автор не несёт ответственности за использование, противоречащее [GitHub Terms of Service](https://docs.github.com/en/site-policy/github-terms/github-terms-of-service).
 
---

## 🎯 Что это такое

Репо для быстрого фарма GitHub-ачивок. Всё максимально автоматизировано:

- **Pull Shark** — GitHub Action сам мёрджит твой PR (мейнтейнер не нужен)
- **Galaxy Brain** — бот создаёт IT-вопросы с вариантами ответов, автоматически принимает правильные
- **Pair Extraordinaire** — PR в папку `pairs/` автоматически мёрджится с co-authored коммитом
- **Quickdraw** — открой и сразу закрой issue через веб
- **YOLO** — смёрдж PR без ревью через веб-интерфейс

---

## 📋 Ачивки

<div align="center">

| Ачивка                     | Тиры                   | Автоматизация |   Сложность   |
| -------------------------- | ---------------------- | :-----------: | :-----------: |
| 🦈 **Pull Shark**          | 2 · 16 · 128 · 1024 PR |   ✅ Action   |   🟢 Легко    |
| 👥 **Pair Extraordinaire** | 1 · 10 · 24 · 48 PR    |   ✅ Action   |   🟢 Легко    |
| 🧠 **Galaxy Brain**        | 2 · 8 · 16 · 32 ответа |   ✅ Action   |   🟢 Легко    |
| ⚡ **Quickdraw**           | разовая                |    ✅ Веб     | 🟢 Тривиально |
| 🤠 **YOLO**                | разовая                |    ✅ Веб     | 🟢 Тривиально |

</div>

---

## 🚀 Быстрый старт

### Выбери ачивку

<details>
<summary><b>🦈 Pull Shark</b> — PR в папку <code>contributors/</code> → автомёрдж (без терминала)</summary>

<br>

1. [Форкни это репо](../../fork) себе
2. В своём форке открой `contributors/`
3. **Add file → Create new file**
4. Имя файла: `ВАШ_USERNAME.md`
5. Содержимое — что угодно
6. Внизу выбери **"Create a new branch for this commit"** (не commit directly to main)
7. Нажми **Propose new file** → убедись что base repository — **оригинальное репо** → **Create pull request**
8. **GitHub Action автоматически смёрджит PR** ✅
9. **Повтори шаги 3–8 ещё раз** с файлом `ВАШ_USERNAME-2.md` — Pull Shark засчитывается только после **2 смёрдженных PR**

> ℹ️ Базовый тир Pull Shark 🦈 открывается после **2 PR**.

</details>

<details>
<summary><b>👥 Pair Extraordinaire</b> — PR в папку <code>pairs/</code> → автомёрдж с co-authored коммитом</summary>

<br>

1. [Форкни это репо](../../fork) себе
2. В своём форке открой `pairs/`
3. **Add file → Create new file**
4. Имя файла: `ВАШ_USERNAME.md`
5. Содержимое — что угодно
6. Внизу выбери **"Create a new branch for this commit"**
7. Нажми **Propose new file** → убедись что base repository — **оригинальное репо** → **Create pull request**
8. **GitHub Action автоматически смёрджит PR с `Co-authored-by: AppsGanin`** ✅

> ℹ️ Ачивка Pair Extraordinaire 👥 засчитывается с **1 такого PR**.

</details>

<details>
<summary><b> Galaxy Brain</b> — отвечай на вопросы в Discussions</summary>

<br>

1. Открой [**Discussions → Q&A**](../../discussions?discussions_q=category%3AQ%26A+is%3Aunanswered)
2. Выбери вопрос **без** зелёной галочки ✅
3. Прочитай вопрос и варианты ответов → напиши **правильный ответ** в комментарии
4. **Бот автоматически проверит ответ и отметит его как принятый** ✅
5. **Повтори для второго вопроса** — базовая ачивка засчитывается после **2 принятых ответов**

Бот создаёт **10 вопросов** трижды в день: в 9:00, 15:00 и 21:00 UTC (только если все предыдущие уже отвечены). Вопросы берутся из открытой базы IT-вопросов — каждый раз новые, с вариантами ответов.

**Тиры:**

|   🧠   |  🧠🥉  |  🧠🥈   |  🧠🥇   |
| :----: | :----: | :-----: | :-----: |
| 2 отв. | 8 отв. | 16 отв. | 32 отв. |

</details>

<details>
<summary><b>⚡ Quickdraw</b> — открой и закрой issue</summary>

<br>

<div align="center">

[![⚡ Открыть Quickdraw Issue](https://img.shields.io/badge/⚡_Открыть_Quickdraw_Issue-yellow?style=for-the-badge&logo=github)](../../issues/new?template=quickdraw.md&title=%5BQUICKDRAW%5D+%40YOUR_USERNAME&labels=quickdraw)

</div>

1. Нажми кнопку выше
2. Замени `YOUR_USERNAME` в заголовке на свой логин
3. **Submit new issue**
4. **Сразу** прокрути вниз → **Close issue**

Ачивка появится через несколько минут. Разовая.

</details>

<details>
<summary><b>🤠 YOLO</b> — смёрдж без ревью (в своём репо)</summary>

<br>

> ⚠️ Нужно твоё **собственное** репо (не чужой форк) — GitHub засчитывает YOLO только владельцу репо.
>
> ⚠️ GitHub требует, чтобы PR **ожидал ревью** — без reviewer-а ачивка не засчитывается. Используй **Copilot** как reviewer — работает без второго аккаунта.

1. [Форкни это репо](../../fork) себе
2. Открой любой файл (например `README.md`) → карандашик ✏️ → добавь пробел → прокрути вниз
3. Нажми **Commit changes...** → выбери **"Create a new branch..."** → **Propose changes**
4. Нажми **Create pull request**
5. В правой панели PR → **Reviewers** → введи `Copilot` → выбери его
6. Нажми **Merge pull request** → **Confirm merge** (не жди ревью)

Ачивка появится через несколько минут. Разовая.

</details>

---

## ⚙️ Как работает автоматизация <a id="-как-работает-автоматизация"></a>

### 🦈 Auto-merge Pull Shark

```
Форк → contributors/USERNAME.md → открыть PR
                                        ↓
                   [auto-merge-contributor.yml]
                                        ↓
              ✔ файлы только в contributors/?
              ✔ имя файла = username автора?
              ✔ нет удалений?
              ✔ файл не больше 10 КБ?
                                        ↓
                    ✅ Squash merge → Pull Shark 🦈
                    ❌ Комментарий с причиной отказа
```

→ Файл: [`.github/workflows/auto-merge-contributor.yml`](.github/workflows/auto-merge-contributor.yml)

### 👥 Auto-merge Pair Extraordinaire

```
Форк → pairs/USERNAME.md → открыть PR
                                    ↓
                   [auto-merge-pair.yml]
                                    ↓
              ✔ файлы только в pairs/?
              ✔ имя файла = username автора?
              ✔ нет удалений?
              ✔ файл не больше 10 КБ?
                                    ↓
                    ✅ Squash merge с Co-authored-by: AppsGanin → Pair Extraordinaire 👥
                    ❌ Комментарий с причиной отказа
```

→ Файл: [`.github/workflows/auto-merge-pair.yml`](.github/workflows/auto-merge-pair.yml)

<details>
<summary><b>Настройка auto-merge для своего форка</b></summary>

<br>

По умолчанию в коммит при мёрдже подставляется `Co-authored-by: AppsGanin` (оригинальный мейнтейнер). Чтобы в **твоём форке** соавтором был ты — замени его на себя.

1. **Найди свой GitHub user ID** — открой `https://api.github.com/users/ВАШ_USERNAME`, найди поле `"id"`

2. **Открой файл** [`.github/workflows/auto-merge-pair.yml`](.github/workflows/auto-merge-pair.yml) в своём форке

3. **Найди строку:**

   ```
   commit_message: `Co-authored-by: 51995816+AppsGanin@users.noreply.github.com`,
   ```

4. **Замени на:**
   ```
   commit_message: `Co-authored-by: ВАШ_ID+ВАШ_USERNAME@users.noreply.github.com`,
   ```

Например, если твой username `john` и ID `12345678`:

```
commit_message: `Co-authored-by: 12345678+john@users.noreply.github.com`,
```

> После этого все PR в `pairs/` твоего форка будут давать Pair Extraordinaire тебе, а не оригинальному автору репо.

</details>

### 🧠 Galaxy Brain pipeline

```
⏰ Три раза в день: 9:00, 15:00, 21:00 UTC
[galaxy-brain-create-questions.yml]
  → Есть неотвеченные вопросы? → ⏭ пропускаем
  → Нет неотвеченных вопросов:
      → GET opentdb.com/api.php?amount=10&category=18&type=multiple
      → 10 IT-вопросов с вариантами ответов (случайные, каждый раз новые)
      → создаём 10 discussion в категории Q&A

💬 Кто-то пишет ответ
[galaxy-brain-auto-accept.yml]
  → категория Q&A?                    ✔
  → ответ ещё не принят?              ✔
  → не автор вопроса?                 ✔
  → не бот?                           ✔
  → ответ содержит правильный текст?  ✔
  → markDiscussionCommentAsAnswer ✅
  → реакция 🎉 на комментарий
```

→ Файлы: [`galaxy-brain-create-questions.yml`](.github/workflows/galaxy-brain-create-questions.yml) · [`galaxy-brain-auto-accept.yml`](.github/workflows/galaxy-brain-auto-accept.yml)

<details>
<summary><b>Настройка Galaxy Brain для своего форка</b></summary>

<br>

Нужен `BOT_TOKEN` — PAT аккаунта, от которого создаются вопросы (только автор вопроса может принять ответ).

1. **Создай PAT:** GitHub → Settings → Developer settings → Personal access tokens → Fine-grained
   - Repository access: это репо
   - Разрешения: `Discussions: Read and write`
2. **Добавь секрет:** Settings → Secrets and variables → Actions → New repository secret → `BOT_TOKEN`
3. **Включи Discussions:** Settings → Features → ✅ Discussions
4. **Создай категорию Q&A** в настройках Discussions

После этого Action будет создавать вопросы ежедневно. Или запусти вручную:
**Actions → Galaxy Brain create questions → Run workflow**

> ⚠️ Galaxy Brain не работает в `github.com/orgs/community/discussions` (отключено в феврале 2024), но отлично работает в обычных репо с Discussions.

</details>

---

## ❓ FAQ

<details>
<summary>Ачивки приходят не сразу — это нормально?</summary>

Да. GitHub обновляет ачивки с задержкой от нескольких минут до нескольких часов. Иногда нужно перезагрузить страницу профиля.

</details>

<details>
<summary>Нужен платный GitHub?</summary>

Нет. Все ачивки доступны на бесплатном аккаунте. Единственное условие — репо должно быть публичным.

</details>

<details>
<summary>PR автоматически смёрджат — мейнтейнер не нужен?</summary>

Для Pull Shark — да, GitHub Action мёрджит PR в `contributors/` автоматически без участия мейнтейнера.

</details>

<details>
<summary>Можно фармить на приватном репо?</summary>

Нет. GitHub считает ачивки только для публичных репозиториев.

</details>

<details>
<summary>Galaxy Brain не засчитывается</summary>

Убедись что:

- Ты отвечаешь в категории **Q&A** (не в General/Ideas/etc.)
- Ты не автор вопроса (нельзя принять свой же ответ)
- В репо включены Discussions и настроен `BOT_TOKEN`

</details>

<details>
<summary>Авто-мёрдж PR не работает в моём форке</summary>

Скорее всего включён branch protection с обязательным ревью. Отключи его:

**Settings → Branches → Branch protection rules** → удали правило для `main` или сними галочку **Require a pull request before merging**.

Также убедись что в **Settings → General → Pull Requests** включена опция **Allow auto-merge**.

</details>

<details>
<summary>Лейбл quickdraw не создаётся при открытии issue</summary>

Лейбл нужно создать вручную один раз:
**Actions → Setup — create labels → Run workflow**

</details>

---

<div align="center">

**Понравился проект? Поставь ⭐ — это помогает другим найти репо и получить ачивки!**

[![Star this repo](https://img.shields.io/badge/⭐_Поставить_звезду-yellow?style=for-the-badge&logo=github&logoColor=black)](../../)

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer" width="100%"/>

</div>
