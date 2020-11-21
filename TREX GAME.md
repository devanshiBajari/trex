# TREX GAME

## invisible ground

-  //creat invisibal ground
    invisibleGround=createSprite(300,190,600,10);
    invisibleGround. visible=false;

``` devnashi
 //creat invisibal ground
  invisibleGround=createSprite(300,190,600,10);
  invisibleGround.visible=false;
```

- Re-cycling the ground

  ``` code
   if (ground.x < 0) {
      ground.x = ground.width / 2;
    }
  ```

