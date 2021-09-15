## JsonMessageBuilder

## Qu'est-ce qu'est ?

C'est une classe java "utilitaire" qui va vous permettre de faire des messages json (cliquable par exemple) beaucoup plus facilement.

## Exemples

```java
p.spigot().sendMessage(new JsonMessageBuilder("")
                    .setText("§fGit§8Hub §7: §5LORD-MECA")
                    .setHoverEvent(new HoverEvent(HoverEvent.Action.SHOW_TEXT, new ComponentBuilder("§7§oClique ici .").create()))
                    .setClickEvent(new ClickEvent(ClickEvent.Action.OPEN_URL, "https://github.com/Lord-Meca/"))
                    .build());
```

## Rendu en jeu

![JsonMessageBuilder_Image_1](https://user-images.githubusercontent.com/82266404/133485202-9eac2763-b1ab-4ebf-b2e5-073c68eda70a.png)

![JsonMessageBuilder_Image_2](https://user-images.githubusercontent.com/82266404/133485223-2cdd8b7f-e100-4202-a1b0-5d1fbac1a5a9.png)

![image_2021-09-15_195832](https://user-images.githubusercontent.com/82266404/133485234-bb82d78f-faa3-41b7-9fc6-a728705f7c78.png)

