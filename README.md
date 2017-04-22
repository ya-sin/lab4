1. What encoded identifiers are used for the functions?
ans:types of its parameters
  (000000000040070d T _Z7averageif
   00000000004006cd T _Z7averagePdRd
  )
2.What is the output of the following program? Why?
ans:
  1 8
  4 8
  4 8
  8 8
我們是在64位元作業系統環境下操作，所以實際完整記憶體位置的表達，必須為64位元，
也就是指標變數若要儲存記憶體位址，也就必須使用8個bytes來儲存。
得知任何一種資料型態的指標變數在64位元作業系統的環境下都將佔用8個bytes，因為指
標變數存放的是記憶體位址。
