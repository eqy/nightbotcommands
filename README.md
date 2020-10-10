!commands edit !iq Your IQ is $(eval state=`$(userid )`; state ^= state << 13; state ^= state >> 17; state ^= state << 5; state = state % 1000; state) -cd=5

!commands add !landosim Landowner555: $(eval max=Math.random()*10 + 1; txt=""; for(i=0;i<max;i++){txt = txt + "botez ";} txt) -cd=5

!commands edit !landosim Landowner555: $(eval choice=Math.round(Math.random()*3); options=["botez", "protoss is hard", "im good at 2v2", "sausageEmote"]; options[choice]) -cd=5
