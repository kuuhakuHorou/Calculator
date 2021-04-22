# Calculator
**注意**:這是一個**整數**的計算機，所以**不會**有浮點數(小數)。

## 說明:
這是一個簡易的計算機，能夠算四則運算、取餘數(%)、次方(^)、階層(!)、排列組合(c,p)、絕對值(|)。在其中也能使用括號(只有小的)，就像一般的算式一樣!  
| 運算子 | 說明 | 範例 | 輸出 |
| :-: | :-: | :-: | :-: |
| + | 加法 | 5+6 | 11 |
| - | 減法 | 9-5 | 4 |
| * | 乘法 | 2*9 | 18 |
| / | 除法 | 15/5 | 3 |
| % | 取餘數 | 9%2 | 1 |
| ^ | 次方 | 2^3 | 8 |
| e | 科學記號 | 5e4 | 50000 |
| ! | 階層 | 5! | 120 |
| c | 組合 | 5c2 | 10 |
| p | 排列 | 5p2 | 20 |
| ( ) | 優先運算 | 5*(1+2) | 15 |

還有絕對值"||"，ex: |-5| = 5

對了是真的可以輸入算式，就像"8+5*(8+4)/2"一樣!  
![算式範例](https://cdn.discordapp.com/attachments/834440816050831390/834440992555008051/2021-04-21_22-49-37.jpg "範例")

還可以使用"*ans*"取得上次的運算結果，或者是"*exit*"離開計算機，還有"*clear*"清理畫面。

不過要小心的是，不小心**輸入錯誤**的話就會跳出**錯誤訊息**喔!  

這裡有個[線上的編輯器](https://replit.com/@kuuhakuHorou/Calculator "replit.com")，可以用線上試試，不用下載。

## Bug report
有發現的bug需要把輸入的運算式一起回報，這樣找起來才會更快。

### 已知Bug
* 無法驗證空的絕對值，ex: ||+5
* 過多的絕對值且沒括號會導致錯誤結果，ex: ||-8|+|-9||
* 不會再超抽stack(運算時)，但也會導致運算錯誤，ex: ||-8|+|-9||

# Change Log
1. 1.0.5 update (2021/4/22 14:27)
   * 修正前面有空白後面接正負有錯誤的情況
1. 1.0.4 update (2021/4/22 00:10)
   * 修正跳過的判斷
1. 1.0.3 update (2021/4/21 23:55)
   * 更換清除無用的括號算法
   * 修正使用負號的結果
1. 1.0.2 update (2021/4/20 23:50)
   * 修正對於空括號的判斷
   * 修正階層數字過大的問題
1. 1.0.1 update (2021/4/20 19:30)
   * 修正絕對值的判斷標準
1. 1.0.0 update (2021/4/19 22:50)
   * 計算機完成!
