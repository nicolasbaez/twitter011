# twitter011
#つぶやきProcessing int i,w=512;float y[]=new float[w];float d[]=new float[w];void setup(){size(512,512);for(i=0;i&lt;w;i++){d[i]=1;}}void draw(){clear();noFill();for(i=0;i&lt;w;i++){stroke(255,0,y[i]);y[i]-=d[i];circle(i+random(2),y[i],d[i]);if(y[i]&lt;0){y[i]=w;d[i]=random(1,8);}}}
