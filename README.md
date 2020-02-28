## How does lint find unused resources in multi-module project??

#### Setup

```
         +-----------+         
      +- |    app    |---+     
      |  +-----------+   |     
      |                  |     
+-------------+  +------------+
|  feature A  |  | feature B  |
+-------------+  +------------+
   |                       |   
   |                       |   
   |     +-----------+     |   
   +---- | toolkit   |-----+   
         +-----------+
```

