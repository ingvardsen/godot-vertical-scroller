# How to make a basic vertical scroller in GoDot

### Based on the tutorial 

https://www.asmaloney.com/2021/02/code/vertical-scrolling-parallax-backgrounds-in-godot/

When developing in Godot 4, there is an updated annotation syntax using leading ```@``` like this:
```
@export var speed: int = 220

@onready var _collision_x_extents: int = get_node("CollisionShape2D").shape.extents.x
@onready var _screen_size: Vector2 = get_viewport_rect().size
...