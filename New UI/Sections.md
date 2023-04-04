---
label: "Sections"
icon: columns
---

# Section Elements

## `section_tbl:new_toggle()`

### Usage

```lua
section_tbl:new_toggle({
    name = "name", 
    risky = false, 
    state = false, 
    flag = "flag",
    callback = function(v) 

    end
})
```

---

## `section_tbl:new_slider()`

### Usage

```lua
section_tbl:new_slider({
    name = "name",
    min = 0,
    max = 100,
	default = 16,
	float = 0.1,
	callback = function(v)
		
	end
})
```

---

## `section_tbl:new_button()`

### Usage

```lua
section_tbl:new_button({
	name = "name",
    (optional) confirm = true,
	callback = function()
		
	end
})
```

---

## `section_tbl:new_seperator()`

### Usage

```lua
section_tbl:new_seperator({name = "name"})
```

---

## `section_tbl:new_keybind()`

### Usage

```lua
section_tbl:new_keybind({
	name = "keybind",
	flag = "flag",
	default = Enum.KeyCode.End,
	(optional) mode = "Toggle",
    (optional) ignore = true,
	callback = function()
		library:Close()
	end,
})