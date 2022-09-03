# Default OpenOS editing tool changed to adjust colors

Sometimes I use the standard OpenOS editing tool. But I never liked the black background color. 
Therefore, I slightly modified this program, so that now the colors are easily adjusted in the /etc/edit.cfg file

![image](https://user-images.githubusercontent.com/33802666/188271585-5004229c-8410-4426-af4a-c2d5412271cf.png)

# Installaction 
Just copy and run this command with OpenOS installed
```
wget -f https://raw.githubusercontent.com/Smok1e/oc-openos-colored-edit/main/edit.lua /bin/edit.lua
```

# Change colors
To change color settings, edit file /etc/edit.cfg and add (or modify)
```
colors = {
  background = [your background color],
  foreground = [your foreground color]
}
```
at the end of file.

Default values are 0x161616 for background and 0xFFFFFF for foreground.

![image](https://user-images.githubusercontent.com/33802666/188272643-e1124913-cfb3-4d0b-b4d2-58a813b46f14.png)

![image](https://user-images.githubusercontent.com/33802666/188272827-f49704d6-7f56-4899-8e9e-326416e4297d.png)
