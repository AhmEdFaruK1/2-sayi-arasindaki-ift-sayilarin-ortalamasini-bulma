# 2-sayi-arasindaki-ift-sayilarin-ortalamasini-bulma
fonksiyona istediğiniz 2 sayı girin...

    g=0
    f=0
    def çiftlerin_ortalaması(x,y):
        global g
        for i in range(x+1,y):
           if i%2 == 0:
             g+=1
             global f
             f+=i
             
        if g==0 :
            print("bu iki sayı arasında çift sayı bulunmamaktadır")
        print(f/g)
    çiftlerin_ortalaması(4,9)    
