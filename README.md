b = 0

while b != 5:
    
    b = int(input("приветствие 1; калькулятор 2; обратный отсчет 3; сумма чисел 4; выход 5"))

    
    if b==1:
        name = input("ввдите имя")
        print ("привет", name)
    
    elif b==2:
        h = int(input("1 - умножение;2 - деление;3 - сложение;4 - вычитание")) 
        if h==1:
            
            x =  int(input("введите множетиль"))
            y = int(input("введите множетель"))
            z = x*y
            print ("ответ:",z)
       
        elif h==2:
               
             x = int(input("введите делимое"))
             y = int(input("введите делитель"))
             z = x/y
             print ("ответ:",z) 
        elif h==3: 
             x = int(input("введите число"))
             y = int(input("введите число"))
             z = x+y
             print ("ответ:",z) 
        elif h==4:
             x = int(input("введите число"))
             y = int(input("введите вычитаемое число"))
             z = x-y
             print ("ответ:",z) 
          
        elif h==5:
             x = int(input("введите число которое хотите возвести в квадрат"))
             z = x*x
             print ("ответ",z)
        else:
              print ("выбери другой вариант")


    elif b==3:
     s = int(input("введите число от которого хотите отсчитать"))
     while s > 0:
         print (s)
         s -=1
     
    elif b==4:
        
        s = int(input("введите число"))
        summa = s
        while s > 0:
            s -= 1
            summa += s
        print ("сумма от вашего числа до 1 =", summa)
    
                   
         
    elif b==5:
        print ("spasibo")
    
    
    
    
    else:
        print ("ошибка")    


