# travel
**Задача**: travel-bot:  планировщик правдивый с местами, ссылками
**Решение**: 1) распарсил статьи travel сайтов. пример статьи: https://travel.yandex.ru/journal/manzherok-prichiny-poehat-na-kurort-zimoy/, собрал в all-articles.json
2) Построил RAG, код во вложении.
**Недостатки**: 
1)gpt3 довольно глупая, например, путает Вологду с Волгоградом. 
2)расходуются платные токены.
**Next steps** - проверить иные open source модели, улучшить prompt, иные модели для эмбеддингов. Довесить агентами, докрутить self-consistency, cot/tot
