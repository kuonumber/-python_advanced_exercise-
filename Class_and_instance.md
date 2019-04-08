# class and instance

```python=
class People:

    count = 0

    def __init__(self, name, age):
        self.name = name
        self.age = age

    def print_profile(self):
        print('Name:', self.name, 'Age:', self.age)


jimmy = People('Jimmy', '30')

jimmy.print_profile()

        
```

> Name: Jimmy Age: 32

物件導向程式設計(Object-oriented programming):  
看到這幾個字其實會讓人昏頭...   
首先，物件是什麼，物件導向又是什麼，這是我剛開始心中的疑惑。  
還記得課堂上老師講了一句很玄的話：「凡事皆物件」。  
白話就是每個東西都是物件，在此不想討論對錯，總之對我覺得沒有理解上的幫助。  

class 是個滿通用的程式關鍵字，中文就是類別。  
簡略的說，語意當中被用來幫助人們歸類的都可以用來定義class。  
比如說，動物類、植物類、人類等等。  

