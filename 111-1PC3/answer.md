# 第3次練習-練習-PC3
>
>學號：109111101 
><br />
>姓名：邱韋翔
><br />
>作業撰寫時間：10 (mins，包含程式撰寫時間)
><br />
>最後撰寫文件日期：2022/09/20
>

本份文件包含以下主題：(至少需下面兩項，若是有多者可以自行新增)
- [x]說明內容
- [x]個人認為完成作業須具備觀念

## 說明程式與內容

根據題目要求，建立變數`int Clothes`、`int i_Hat`、`int i_Pants`，並放入對應的數字
題目最後要求算總和，所以在建立一個變數來存取總和`int i_Sum`，根據對應的變數與價
格相乘在加總，最後在輸出用來存取總和的變數，下段程式碼為使用後的結果：

```csharp
protected void Page_Load(object sender, EventArgs e)
{
       int i_Clothes = 7;
       int i_Hat = 8;
       int i_Pants = 9;
       int i_Sum = 0;
       i_Sum = (i_Clothes * 300) + (i_Hat * 350) + (i_Pants * 400);
       Response.Write(i_Sum);
}
```

## 個人認為完成作業須具備觀念

這次作業需了解

