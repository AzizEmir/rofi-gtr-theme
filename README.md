# Rofi GT-R Theme

![Theme View](https://github.com/user-attachments/assets/eb54d517-5ff4-4adf-9ea5-a8743ba3077e)


## .config/rofi/config.rasi
```
configuration {
	modi:				"drun";
	font:				"Rubik 10";
	display-drun: 			"";
	drun-display-format:            "{name}";
	sidebar-mode: 			false;
}

@theme "/dev/null"

* {
	bg:				#061115;
	fg:				#d9d7d6;
	button:				#0b151a;

	background-color:		@bg;
	text-color:			@fg;
}

window {
	transparency:                   "real";
	width:			    	70%;
}

prompt { enabled: false; }

entry {
    placeholder: "GT-R    🤩";
    placeholder-color: @fg;
    expand: true;
    background-color: rgba(0,0,0,0.2);
    padding: 1.5%;
    border-radius: 8px;
}

inputbar {
	children: 			[ prompt, entry ];
	background-image:               url("img/nissangtr.png");
	expand:                         false;
	border-radius:                  0px 0 8px 8px;
	padding:                        140px 30px 30px 1000px;
}

listview {
	columns:                        1;
	lines:	                        4;
	cycle:                          false;
	dynamic:                        true;
	layout:                         vertical;
	padding:			30px 300px 30px 30px;
}

mainbox { children: [ inputbar, listview ]; }

element {
	orientation:                    vertical;
	padding:                        1.5% 0% 1.5% 0%;
	border-radius:			8px;
}

element-text {
	expand:                         true;
	vertical-align:                 0.5;
	margin:                         0.5% 3% 0% 3%;
	background-color: 		inherit;
	text-color:       		inherit;
}

element selected {
	background-color:               @button;
	border-radius:                  8px;
}
```


## .config/rofi/img/nissangtr.png

![nissan-gtr](https://github.com/user-attachments/assets/9938f91f-9c0a-4fbe-8b23-7b542ea13e3d)


## Desktop Wallpaper

![](https://r4.wallpaperflare.com/wallpaper/570/157/243/edc-graphics-nissan-200sx-nissan-jdm-wallpaper-a9c0c8fde1fa9dfbe647382f1031d63d.jpg)

