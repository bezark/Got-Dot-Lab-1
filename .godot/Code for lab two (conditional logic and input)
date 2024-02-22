extends Sprite2D

@export var booleanVariable = true

@export var speed =5.
# Called when the node enters the scene tree for the first time.
func _ready():
	pass


# Called every frame. 'delta' is the elapsed time since the previous frame.
func _process(delta):
	if Input.is_key_pressed(KEY_D):
		position.x += speed
	if Input.is_key_pressed(KEY_A):
		position.x += -speed
	if Input.is_key_pressed(KEY_W):
		position.y += -speed
	if Input.is_key_pressed(KEY_S):
		position.y += speed
