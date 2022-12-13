# 092wb_wubiLex
wubilex092版的码表

```
//【092】判断微软五笔候选窗显示状态，显示则执行花括号中的语句,按0选10重（前提设置最大候选数为9）
["0"] = function(){
    if( winex.msCandidate.isVisible() ){
        key.press("OEM_PLUS", "SPACE");
    }
    else key.send("0");
};
```
