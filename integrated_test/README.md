# 目標 Target

優化點擊率，events資料集為隱性評分資料，我會示範用hold-one-out evaluation(只用每個使用者最後一個點擊行為當作測試集之 evaluation)。由於events.csv資料量相當大，我隨機抽取一成的使用者和物品，以及只有 _view_ 的event至另一個檔案 __events_small.csv__ ，範例解答中會使用這個檔案以加快速度。

Maximize Click-through-rate (CTR). The events dataset contains implicit ratings. I will demonstrate how to use hold-one-out for test set evaluation. Since event.csv is too large, a small portion of data was sampled to another file __events_small.csv__ . Specifically, 10% of the users and items are randomly sampled, and events other than _view_ are filtered out. All the examples in this repo will be using this data instead of __events.csv__ in order for faster computation and demonstration.
