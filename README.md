# fish
z=50 x=70 c=5 v=50 d=150 def setup():     size(600,600) def draw():     global z,x,c,v,d     background(255)     ellipse(z,300,300,300)     strokeWeight(10)     point(c,250)     point(x,250)     line(v,300,d,300)     z +=1     x +=1     c +=1     v +=1     d +=1
