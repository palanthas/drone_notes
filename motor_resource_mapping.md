# Layout on Joshua Bardwell Flight Controller

## Motor Order
```
4 2
 X
3 1
```
## Motor resource mapping:
```
4>A03  2>B08

3>A02  1>B01 
```

Type 'resource' to view current resource mapping.

Resource mapping commands:
```
resource MOTOR 1 B01
resource MOTOR 2 B08
resource MOTOR 3 A02
resource MOTOR 4 A03
save
```
