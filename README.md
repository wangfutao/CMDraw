# CMDraw
CMDraw
Example:
draw rectangle center (300,200) width 400 height 200 fill #f5f5f5 linewidth 1 linecolor #00f rotate 25;

draw polygon 
 center (300,200) 
 radius 80 
 sides 5
 concavity 0.5
 rotate 25
 fill #00f 
 linecolor #00f;

draw line from (76,206) to (524,195) linecolor blue;

draw circle center (800,200) radius 80 fill #00f linecolor #00f;

draw slice 
 center (630,400) 
 radius 80 
 start 0 end 90 
 fill blue 
 linecolor blue;

draw slice 
 center (625,400) 
 radius 80 
 start -90 end 0 
 fill blue 
 linecolor blue;

draw slice 
 center (625,405) 
 radius 80 
 start -180 end -90
 fill blue 
 linecolor blue;

draw slice 
 center (630,405) 
 radius 80 
 start 90 end 180
 fill blue 
 linecolor blue;

draw text center (830,420) text 不听话 size 30 linecolor blue
 fill red font 等线;
