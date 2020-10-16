!commands edit !iq Your IQ is $(eval state=`$(userid )`; state ^= state << 13; state ^= state >> 17; state ^= state << 5; state = state % 1000; state) -cd=5

!commands add !landosim Landowner555: $(eval max=Math.random()*10 + 1; txt=""; for(i=0;i<max;i++){txt = txt + "botez ";} txt) -cd=5

!commands edit !landosim Landowner555: $(eval choice=Math.round(Math.random()*3); options=["botez", "protoss is hard", "im good at 2v2", "sausageEmote"]; options[choice]) -cd=5

!commands add !viewers $(eval var v = parseInt($(twitch gypsy93 "{{viewers}}")); var res = "Uh you need to just have 75 average viewers and you don't have that"; if (v > 75) {res = "MORE THAN 75 VIEWERS HOLY SHIT GIVE THIS MAN PARTNER NOW";} res)
