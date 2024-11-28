# boy kilo endeksi 

a=float(input("lütfen kilonuzu giriniz:"))
b=float(input("lütfen boyunuzu giriniz:"))

x=(a)/(b**2)
print(x)
if(x<18.5):
    print("çok zayıfsınız.")
elif(18.5<x<24.5):
    print("sğlıklısınız." )
elif(25<x<29):
    print("şişmansınız.")
elif(x>29):
    print("ölmek üzeresiniz.")








# enerji dönüşüm 
y=input("c mi f mi ?:")

if(y=="f"):
    b=float(input("kaç derece:"))
    a=(b-32)/1.8
    print(a)
    print("c derecesinden ortamın sıcaklığı. {}".format(a))

elif(y=="c"):
    v=float(input("kaç derece:"))
    c=(v*1.8)+32
    print(c)
    print("f derecesinden ortamın sıcaklığı. {}".format(c))


# not hesaplama 

x1=int(input("lütfen türkçe notunuzu girin: "))
x2=int(input("lütfen matematik notunuzu girin: "))
x3=int(input("lütfen tarih notunuzu girin: "))
x4=int(input("lütfen ingilizce notunuzu girin: "))
x5=int(input("lütfen fizik notunuzu girin: "))

a=((x1*5)+(x2*6)+(x3*2)+(x4*4)+(x5*4))/(5+6+2+4+4)
print(a)
if(a>85):
    print("takdir kazandınız.")
elif(85>a>70):
    print("teşekkür kazandınız.")
else:
    print("hiçbir belge alamadınız.")




