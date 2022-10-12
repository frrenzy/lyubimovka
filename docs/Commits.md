# Commits

Настоятельно рекомендую коммитить маленькими частями по сделанным мини-фичам
> Пример:\
> Вы делаете блок курсов и реализовываете для нее сам блок и карточки-элементы. Сначала закоммитьте изменения, которые относятся к обертке, а потом сделайте отдельный коммит на изменения в карточках

---
## Commit message

Коммиты пишем в стиле [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/#summary)

Также у нас прикручен ClickUp к Гитхабу, так что перед сообщением вставляйте еще айдишник задачки и, если нужно, статус. Доступные татусы можно в самой таске кликапа посмотреть.
[Дока кликапа](https://help.clickup.com/hc/en-us/articles/6305771568791-GitHub)

> Примеры:
> * #111111[ready] feat(analytics page): added new graphs for drivers segment
> * build(image plugin): added plugin for image compression
> * fix: fixed window reload bug

---
## Git flow

Есть статические ветки: `master` и `development`\
Для других веток есть 2 типа названий:
 * `feature/*` - фича-ветки
 * `hotfix/*` - ветка для срочных фиксов

Новые feature-ветки откалываются от и мерджатся в `development`
Новые hotfix-ветки откалываются от и мерджатся в `master`

MR на hotfix не нуждается в аппруве
MR на фичу нуждается в аппруве хотя бы 1 человека



