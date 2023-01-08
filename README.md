# 409.-Longest-Palindrome
409. En Uzun Palindrom
Palindrom, tersten okunuşu da aynı olan cümle demektir.<br>
Küçük veya büyük harflerden oluşan bir s dizesi verildiğinde, bu harflerle oluşturulabilecek en uzun palindromun uzunluğunu döndürün.
Harfler büyük / küçük harfe duyarlıdır, örneğin "Aa" burada palindrom olarak kabul edilmez.<br>

Örnek olarak:
Input: s = "abccccdd"
Output: 7
Explanation: One longest palindrome that can be built is "dccaccd", whose length is 7.<br>

Bunun için hangi harflerden çift sayıda var ona bakabiliriz**(Dictionary)**ve sonuçta uzunluk döndüreceğimiz için bir sayaç da tanımlamalıyız.

