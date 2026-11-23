---
title: Appsheet Column
layout: default
nav_order: 3
---

# `type`, `key` and `label` columns

![alt text](img/paste-1795402994991.png)

# Room enum

![alt text](img/paste-1795403022900.png)

# `booking_time` column

```
NOW()
```

![alt text](img/paste-1795403046923.png)

# `start_time` and `end_time` columns

```
NOW() + "001:00:00"
```

- `start_time`
  ![alt text](img/paste-1795403092438.png)

- `end_time`
  ![alt text](img/paste-1795403111787.png)

# Data validation for `end_time` column

```
[end_time] > [start_time]
```

![alt text](img/paste-1795403230182.png)

# `calendar_display` Virtual column

```
CONCATENATE([room], " - " , [name], " - ", [purpose])
```

![alt text](img/paste-1795403156737.png)
