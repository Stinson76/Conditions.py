# Cedestinson Ductan
temp=int(input("Please enter the current temperature"))
if temp<0 or temp< 32:
    print("Stay inside")
else:
    if temp<=32 or temp<50:
        print("Wear a heavy coat")
    else:
        if temp<=50 or temp<70:
            print("Wear a jacket")
        else:
            if temp<=70 or temp<90:
                print("Short sleeves are fine")
            else:
                if temp<=90 or temp<110:
                    print("Wear shorts")
                else:
                    if temp<=110 or temp<130:
                        print("We are doom, this is the end")
                    else:
                        if temp<=130 or temp<999:
                            print("We are doom, this is Armaguedon")
                        exit()
