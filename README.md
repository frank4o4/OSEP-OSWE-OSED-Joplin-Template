# OSEP-Joplin-Template
OSEP Joplin Template I used for my exam




## Remove Joplin Title from export

Under Options go to Custom Stylesheet for rendered Markdown and click Button

![joplin_options.png](:/joplin_options)


Now paste the following
```
@media print { .exported-note-title { display: none !important; } }
```

**Note:** After saving the style sheet you will have to close Joplin and reopen for function to take affect.