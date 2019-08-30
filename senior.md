# $$

### scope
 以 $$ 為優先
 - consultant : case by case
 - 大公司的 develop


### 常見問題
 - 效能問題
 - 架構/套件老舊 -> 如何 migration smooth 
 - 維持 code base / code quality
     - diff review / code review 能力 => 不要merge有可能有問題的 code, 才能沒有 Technical Debt
 - crash rate : 99. 999
     - 打點分析 / 插數據 : 分析問題、思路分析、驗證問題假設
     - 某些版本對某些 API 可能有相容問題
 
 
### 特質 / 行為
 - 邏輯思考能力 / 思路清晰
 - 抽絲剝繭能力高 (不是設 Breakpoint 可以解的小問題)
 - 溝通能力強
 - 知道如何做 diff(code) review 找 邏輯問題/效能問題 ，不是 naming issue, coding style
 - 架構上可以提出建議，分析優缺及原因 
 - you know directing :
    知道現在最重要的事情是甚麼，把它做好。而不是交代一件事做一件單方向接受。
    
    - 比如說，可以自己思考 code base 有那些問題，是不是要當下處理(為什麼?)，
    - 如果是有很大 impact，懂得和 stackholder 溝通拿資源(&時間)想法辦做好 / 解決，因為有很大 impact，所以花時間處理後也可以獲得很大效益 
       -  OOM (out of memory) : top crash percentage 有多少比例要處理? 95%? 99.5?? 99.9995%，處理難易度如何? 
       -  可以找到 critical point 去快速改善效率(&品質) /  降低 crash Rate

 - 上述 *特質 / 行為* 可以透過 interview / coding test / system desing (large scrop practice) 分析，找最佳解 + 實作
 
### bad things
 - 基礎指令 multi-branch / rebase 
 - be predictive , 否則容易被　block
 - masking the problem  
     - 只是找方法補起問題 -> 直接在該處掩蓋問題
     - 不找 root cause 從根本解決 
 - 不知道/不能講清楚  專案 detail(邏輯) , big picture,
 - 過於線性處理單一，而不是從 high level 思考問題。

27:08




















#### other product think
    -  other things