# 第2次練習-練習-PC2
>
>學號：109111117 
><br />
>姓名：潘耿劭 
><br />
>作業撰寫時間：70 (mins，包含程式撰寫時間)
><br />
>最後撰寫文件日期：2022/9/26
>

本份文件包含以下主題：(至少需下面兩項，若是有多者可以自行新增)
- [x]說明內容
- [x]個人認為完成作業須具備觀念

## 說明程式與內容

假設一個溫度計名稱為i_In的攝氏度初始值為66377 利用雙精準浮點數double設置名為d_Ou初始值-999 利用華氏攝氏轉換公式F=(9/5)*C+32計算溫度


```csharp
namespace _111_1PC1
{
	public partial class Test : System.Web.UI.Page
    {
        protected void Page_Load(object sender, EventArgs e)
        {
            int i_In = 66377;
            double d_Ou = -999;
            double d_Tmp = (double)i_In;
            d_Ou = (d_Tmp * 9 / 5) + 32;
            Response.Write(d_Ou);
        }
    }
}
```

若要於內文中標示部分.aspx檔，則使用以下標籤` ```html 程式碼 ``` `，
下段程式碼則為使用後結果：

```html
<%@ Page Language="C#" AutoEventWireup="true" ...>

<!DOCTYPE html>

<html xmlns="http://www.w3.org/1999/xhtml">
<head runat="server">
<meta http-equiv="Content-Type" content="text/html; charset=utf-8"/>
    <title></title>
</head>
<body>
    <form id="form1" runat="server">
        <div>
        </div>
    </form>
</body>
</html>
```


## 個人認為完成作業須具備觀念

此項作業需要稍微了解溫度轉換公式，還有名字定義的用法，名稱千萬不能放錯地方，以免程式執行發生錯誤。
