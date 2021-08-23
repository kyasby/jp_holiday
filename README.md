# Japnese Holiday
日付が含まれるデータフレームを入れると，祝日フラグを与えてデータフレームを返します。

引数には以下を指定してください。

- 第一引数 => データフレーム
- 第二引数 => データフレーム内の，日付が入っているカラム名
- 第三引数 => 新しく作られる祝日フラグのカラム名

を入れてください。

＊第三引数はデフォルト値が`holiday`です。

```python

from jp_holiday import jp_holiday

df_with_holiday = jp_holiday.is_holidy(df, "date", "is_holiday")

```
