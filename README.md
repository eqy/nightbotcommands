!commands edit !iq Your IQ is $(eval state=`$(userid )`; state ^= state << 13; state ^= state >> 17; state ^= state << 5; state = state % 1000; state) -cd=5

!commands add !landosim Landowner555: $(eval max=Math.random()*10 + 1; txt=""; for(i=0;i<max;i++){txt = txt + "botez ";} txt) -cd=5

!commands edit !landosim Landowner555: $(eval choice=Math.round(Math.random()*3); options=["botez", "protoss is hard", "im good at 2v2", "sausageEmote"]; options[choice]) -cd=5

!commands add !viewers $(eval var v = parseInt($(twitch gypsy93 "{{viewers}}")); var res = "Uh you need to just have 75 average viewers and you don't have that"; if (v % 69 == 0) {var fac = Math.floor(v/69); res = "69 x " + fac + " viewers nice"; } else if (v >= 150) {res = "MORE THAN 150 POG"; } else if (v > 100) {res = "MORE THAN 100 HOLY MOLY"; } else if (v >= 75) { res = "MORE THAN 75 HOLY SHIT GIVE THIS MAN PARTNER NOW"; } else if (v > 50) { res = "more than 50 plz no bully"; } res)
