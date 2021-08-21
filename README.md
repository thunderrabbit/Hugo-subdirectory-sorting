I want most lists to be sorted by date.  However, I want posts in `content/quests/slow-down` to be sorted by Title.

    content/blog               ＜ーー  sorted by date
    content/journal            ＜ーー  sorted by date
    content/quests/            ＜ーー  sorted by date
    content/quests/slow-down   ＜ーー  I want to sort by title

Most lists use this template

    themes/purehugo/layouts/_default/list.html

`content/quests/` uses this template:

    themes/purehugo-augmentation/layouts/quests/list.html

`content/quests/slow-down` does NOT use this template:

    themes/purehugo-augmentation/layouts/quests/slow-down/list.html
