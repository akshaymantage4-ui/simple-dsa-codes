num=4567
list=[]
while num!=0:
   nums=num%10
   list.append(nums)
   num=num//10
  

list.reverse()
for i in list:
    print(i)
  
