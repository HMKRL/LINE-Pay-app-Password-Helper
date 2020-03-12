# LINE Pay app tasker password helper

本 Tasker profile 適用於 LINE Pay 獨立APP

請把`LINE_Pay.prf.xml`用文字編輯器打開

並依照以下對照方式改成自己的密碼(目前會輸入123456)

假設密碼第M位數(從1開始算)為N，請把檔案中所有的 `numberMView` 改為 `numberNView`

例如密碼是`987654`，

就把所有`number1View`改成`number9View`

把所有`number2View`改成`number8View`

以此類推

注意所有`numberXView`都有兩個！

