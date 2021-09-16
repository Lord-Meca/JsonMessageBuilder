## JsonMessageBuilder

## What is it ?

It's a java "utility" class that will allow you to make json messages (clickable for example) much easier.

## Example

```java
p.spigot().sendMessage(new JsonMessageBuilder("")
                    .setText("§fGit§8Hub §7: §5LORD-MECA")
                    .setHoverEvent(new HoverEvent(HoverEvent.Action.SHOW_TEXT, new ComponentBuilder("§7§oClique ici .").create()))
                    .setClickEvent(new ClickEvent(ClickEvent.Action.OPEN_URL, "https://github.com/Lord-Meca/"))
                    .build());
```

## Rendering in game

![JsonMessageBuilder_Image_1](https://user-images.githubusercontent.com/82266404/133652690-cb2e4c3c-939f-4c7a-8858-873304f911a9.png)
![JsonMessageBuilder_Image_2](https://user-images.githubusercontent.com/82266404/133652696-08550a27-4bb2-4cc9-bad5-38ddb2c99d47.png)
![JsonMessageBuilder_Image_3](https://user-images.githubusercontent.com/82266404/133652701-861a5a76-2958-4995-94ab-58c02047d730.png)
