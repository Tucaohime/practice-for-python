# practice-for-python
practice code
# a program for counting date

def voi():
    
    chat=[]
    
    date=input("请输入日期，顺序为年，月，日按/分开：")
    
    chat=date.split("/")
    
    
    month=['一月','二月','三月','四月','五月','六月','七月','八月','九月','十月','十一月','十二月']
    
    i=int(chat[1])
    if i<=12:
        print(chat[0],month[i-1],chat[2])
    
    else:
        print("数据错误")
voi()
