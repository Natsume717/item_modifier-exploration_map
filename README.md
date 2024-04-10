# item_modifier-exploration_map
item_modifierの1項目であるexploration_mapに関するサンプルになります。

~詳しくはブログ記事『[]()』を参考にしてください。~<br>
現在執筆中

<h3>概要</h3>
白紙の地図に対して適用させることで、指示した建造物の場所を示す地図に変更させることが出来ます。

<h3>使い方</h3>
データパック導入後、ワールドに入ることで白紙の地図が20個もらえます。<br>
この地図を持って、以下のコマンドを実行することで、村の位置を示す地図に変更することが可能です。

```copy
/item modify entity @s weapon.mainhand sample:exploration_map
```

---

lootコマンドでルートテーブルから地図を付与させる場合でも、exploration_mapを適用させることは可能です。<br>
それを体験できるコマンドは、以下の通り。

```copy
/loot give @s loot sample:exploration_map
```

※本データパックでは、村を探すようにしており、その位置には赤いバツ印になるようにしています。
