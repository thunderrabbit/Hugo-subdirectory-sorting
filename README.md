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
    
    
From https://gohugo.io/templates/lists/

I decided to just move `quests/slow-down` pages to `books/slow-down`.
This way, any future book will be sorted in the same way, by title, 
not that books are sorted by title normally, but that's what I will do this time.
