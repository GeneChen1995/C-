# C_language_practise
### **題目: 找到總和為偶數的最大相鄰數(Find the largest adjacent number whose sum is even)**
➢ 題目描述:給你一個圓上的的N個數字，由數組A描述。找到總和為偶數的相鄰最大總數。一個元素只能屬於一對。
  寫一個函數:
  func(A,len)
  給定一個由N個整數組成的數組A，返回總和為偶數的相鄰最大數量。
  例子:
  1.給定A = [4,2,5,8,7,3,7]，函數應該返回2。我們可以找到兩個偶數對:(A[0],A[1])和(A[4],A[5])。選擇兩隊的另一種方式是(A[0],A[1])和(A[5],A[6])。
  
  <img src="https://github.com/GeneChen1996/C_language_practice_questions/blob/main/%E9%A1%8C%E7%9B%AE1%E7%A4%BA%E6%84%8F%E5%9C%96_1.JPG" width="50%" height="50%"/><br/>
  
  2.給定A = [14,21,16,35,22]，該函數應該返回1。只有一對符合條件(A[0],A[4])。
  
  <img src="https://github.com/GeneChen1996/C_language_practice_questions/blob/main/%E9%A1%8C%E7%9B%AE1%E7%A4%BA%E6%84%8F%E5%9C%96_2.JPG" width="25%" height="25%"/><br/>
  
  
  3.給定A = [5,5,5,5,5,5]，該函數應該返回3。有三對符合條件(A[0],A[1]),(A[2],A[3]),(A[4],A[5])。
  
  <img src="https://github.com/GeneChen1996/C_language_practice_questions/blob/main/%E9%A1%8C%E7%9B%AE1%E7%A4%BA%E6%84%8F%E5%9C%96_3.JPG" width="25%" height="25%"/><br/>
  
