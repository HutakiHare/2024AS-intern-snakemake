# BinderHub Snakemake 使用 mock-up

## 前言
[Depositar](https://data.depositar.io/)為得讓所儲存的資料集達成FAIR data(Findable, Accessible, Interoperable, Reusable)，引進了[BinderHub](https://binderhub.readthedocs.io/en/latest/)來讓資料得以在內部進行運作驗證(interoperable)，而Snakemake的加入則是為了省去複雜的資料驗證程序，並讓資料更新可以只重新執行需要的部分，降低資源使用，而"省去複雜的資料驗證程序"的部分則可以彈性使用，讓使用者也可以以自己的資料去驗證實驗結果(Reusable)。

這份文件簡單的介紹了Snakemake的使用方式並模擬加入BinderHub

```{tableofcontents}
```