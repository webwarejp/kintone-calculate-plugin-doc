# サポート関数（カテゴリ別）

<details><summary>日付と時刻の関数</summary><div>

| 関数                                                 | 説明              |
|:----------------------------------------------------|:-----------------|
| [DATE 関数](date-time.md#user-content-date-関数)     | 特定の日付を表す シリアル値を返します。|
| [DATESTRING 関数](date-time.md##DATESTRING)          | シリアル値を日付の文字列に変換します。|
| [DATEVALUE 関数](date-time.md#DATEVALUE)             | 文字列として格納された日付をシリアル値に変換します。| 
| [DAY 関数](date-time.md#DAY)                         | 日付の日情報を返します。|
| [DAYS 関数](date-time.md#DAYS)                       | 2 つの日付間の日数を返します。|
| [DAYS360 関数](date-time.md#DAYS360)                 | 一部の会計計算に使用される 1 年 360 日の計算方式に基づいて、2 つの日付の間の日数を返します。|
| [EDATE 関数](date-time.md#EDATE)                     | 開始日から起算して、指定された月数だけ前または後の日付に対応するシリアル値を返します。|
| [EOMONTH 関数](date-time.md#EOMONTH)                 | 開始日から起算して、指定された月数だけ前または後の月の最終日に対応するシリアル値を返します。|
| [HOUR 関数](date-time.md#HOUR)                       | 時刻から時間の値を返します。|
| [ISODATESTRING 関数](date-time.md#ISODATESTRING)     | シリアル値を ISO 8601 の UTC 日付書式に変換します。|
| [ISOWEEKNUM 関数](date-time.md#ISOWEEKNUM)           | 指定された日付のその年における ISO 週番号を返します。|
| [MINUTE 関数](date-time.md#MINUTE)                   | 時刻の分を返します。 |
| [MONTH 関数](date-time.md#MONTH)                     | 日付の月を返します。|
| [NETWORKDAYS 関数](date-time.md#NETWORKDAYS)         | 開始日から終了日までの期間に含まれる稼動日の日数を返します。| 
| [NETWORKDAYSINTL 関数](date-time.md#NETWORKDAYSINTL) | 週末の曜日とその日数を示すパラメーターを使用して、2 つの日付の間の稼働日数を返します。|
| [NOW 関数](date-time.md#NOW)                         | 現在を表すシリアル値を返します。|
| [SECOND 関数](date-time.md#SECOND)                   | 時刻の秒を返します。|
| [TIME 関数](date-time.md#TIME)                       | 指定した時刻に対応するシリアル値を返します。|
| [TIMESTRING 関数](date-time.md#TIMESTRING)           | シリアル値を時刻の文字列に変換します。|
| [TIMEVALUE 関数](date-time.md#TIMEVALUE)             | 文字列で表された時刻をシリアル値に変換します。|
| [TODAY 関数](date-time.md#TODAY)                     | 現在の日付に対応するシリアル値を返します。|
| [WEEKDAY 関数](date-time.md#WEEKDAY)                 | 日付に対応する曜日を返します。|
| [WEEKNUM 関数](date-time.md#WEEKNUM)                 | 特定の日付が第何週目に当たるかを返します。|
| [WORKDAY 関数](date-time.md#WORKDAY)                 | 開始日から起算して、指定された稼動日数だけ前または後の日付に対応するシリアル値を返します。|
| [WORKDAYINTL 関数](date-time.md#WORKDAYINTL)         | 週末パラメーターを使用して、開始日から起算して指定した稼働日数だけ前または後の日付のシリアル値を返します。|
| [YEAR 関数](date-time.md#YEAR)                       | 日付に対応する年を返します。|
| [YEARFRAC 関数](date-time.md#YEARFRAC)               | 2 つの日付間の期間の数値で表される年の比率を計算します。|

</div></details>

<details><summary>情報関数</summary><div>

| 関数                                                 | 説明              |
|:----------------------------------------------------|:-----------------|
| [ISBLANK 関数](information.md#ISBLANK)              |テストの対象の値が空のとき TRUE を返します。|
| [ISERROR 関数](information.md#ISERROR)              |テストの対象の値がエラーを示す値のとき TRUE を返します。|
| [ISEVEN 関数](information.md#ISEVEN)                |テストの対象の値が偶数のとき TRUE を返します。|
| [ISODD 関数](information.md#ISODD)                  |テストの対象の値が奇数のとき TRUE を返します。|

</div></details>

<details><summary>論理関数</summary><div>

| 関数                                                 | 説明              |
|:----------------------------------------------------|:-----------------|
| [AND 関数](logical.md#AND)                           | すべての引数が TRUE のときに TRUE を返します。|
| [FALSE 関数](logical.md#FALSE)                       | 論理値 FALSE を返します。|
| [IF 関数](logical.md#IF)                             | 値または数式が条件を満たしているかどうかを判定します。|
| [IFERROR 関数](logical.md#IFERROR)                   | 数式の結果がエラーの場合は指定した値を返し、それ以外の場合は数式の結果を返します。|
| [NOT 関数](logical.md#NOT)                           | 引数の論理値を反転させます。|
| [OR 関数](logical.md#OR)                             | いずれかの引数が TRUE のときに TRUE を返します。|
| [SWITCH 関数](logical.md#SWITCH)                     | 式に対して値の一覧を評価し、最初に一致する値に対応する結果を返します。|
| [TRUE 関数](logical.md#TRUE)                         | 論理値 TRUE を返します。 |
| [XOR 関数](logical.md#XOR)                           | すべての引数の排他的論理和を返します。|

</div></details>

<details><summary>検索/行列関数</summary><div>

| 関数                                                 | 説明              |
|:----------------------------------------------------|:-----------------|
| [CHOOSE 関数](lookup-matrix.md#CHOOSE)               | 引数リストの値の中から特定の値を 1 つ選択します。|
| [INDEX 関数](lookup-matrix.md#INDEX)                 | 行番号で指定される配列の要素の値を返します。|
| [ROWS 関数](lookup-matrix.md#ROWS)                   | 配列の行数を返します。|

</div></details>

<details><summary>数学関数</summary><div>

| 関数                                                 | 説明              |
|:----------------------------------------------------|:-----------------|
| [ABS 関数](math-trig.md#ABS)                         | 数値の絶対値を返します。|
| [CEILING 関数](math-trig.md#CEILING)                 | 指定された基準値の倍数のうち、最も近い値に数値を切り上げます。|
| [CEILINGMATH 関数](math-trig.md#CEILINGMATH)         | 数値を最も近い整数、または基準値の倍数で最も近い数に切り上げます。|
| [CEILINGPRECISE 関数](math-trig.md#CEILINGPRECISE)   | 数値を最も近い整数、または基準値の倍数で最も近い数に切り上げます。|
| [EVEN 関数](math-trig.md#EVEN)                       | 指定した数値を最も近い偶数に切り上げた数値を返します。|
| [FACT 関数](math-trig.md#FACT)                       | 数値の階乗を返します。|
| [FACTDOUBLE 関数](math-trig.md#FACTDOUBLE)           | 数値の二重階乗を返します。|
| [FLOOR 関数](math-trig.md#FLOOR)                     | 数値を指定された桁数で切り捨てます。|
| [FLOORMATH 関数](math-trig.md#FLOORMATH)             | 指定された基準値の倍数のうち、最も近い値に数値を切り捨てます。|
| [FLOOPRECISE 関数](math-trig.md#FLOOPRECISE)         | 指定された基準値の倍数のうち、最も近い値に数値を切り捨てます。|
| [INT 関数](math-trig.md#INT)                         | 指定された数値を最も近い整数に切り捨てます。|
| [ISOCEILING 関数](math-trig.md#ISOCEILING)           | 数値を最も近い整数、または基準値の倍数で最も近い数に切り上げます。|
| [MOD 関数](math-trig.md#MOD)                         | 数値を除数で割ったときの剰余を返します。 |
| [MROUND 関数](math-trig.md#MROUND)                   | 指定された値の倍数になるように丸められた数値を返します。|
| [ODD 関数](math-trig.md#ODD)                         | 数値を切り上げて、最も近い奇数にします。|
| [POWER 関数](math-trig.md#POWER)                     | 数値のべき乗を返します。|
| [PRODUCT 関数](math-trig.md#PRODUCT)                 | 引数として指定されたすべての数値を積算し、その積を返します。|
| [QUOTIENT 関数](math-trig.md#QUOTIENT)               | 除算の商の整数部を返します。|
| [ROUND 関数](math-trig.md#ROUND)                     | 数値を四捨五入して指定された桁数にします。|
| [ROUNDDOWN 関数](math-trig.md#ROUNDDOWN)             | 数値を指定された桁数で切り捨てます。|
| [ROUNDUP 関数](math-trig.md#ROUNDUP)                 | 数値を指定された桁数に切り上げます。|
| [SQRT 関数](math-trig.md#SQRT)                       | 正の平方根を返します。|
| [SUM 関数](math-trig.md#SUM)                         | 引数を合計します。|
| [SUMIF 関数](math-trig.md#SUMIF)                     | 指定した条件を満たす範囲内の値を合計します。|
| [SUMIFS 関数](math-trig.md#SUMIFS)                   | 複数の検索条件に一致するすべての引数を合計します。|
| [TRUNC 関数](math-trig.md#TRUNC)                     | 数値の小数部を切り捨てて、整数または指定した桁数に変換します。|

</div></details>

<details><summary>統計関数</summary><div>

| 関数                                                 | 説明              |
|:----------------------------------------------------|:-----------------|
| [AVEDEV 関数](stastical.md#AVEDEV)                   | データ全体の平均値に対するそれぞれのデータの絶対偏差の平均を返します。|
| [AVERAGE 関数](stastical.md#AVERAGE)                 | 引数の平均 (算術平均) を返します。|
| [AVERAGEA 関数](stastical.md#AVERAGEA)               | 数値、文字列、および論理値を含む引数の平均値を返します。|
| [AVERAGEIF 関数](stastical.md#AVERAGEIF)             | 範囲内の条件に一致するすべての値の平均値 (算術平均) を返します。|
| [AVERAGEIFS 関数](stastical.md#AVERAGEIFS)           | 複数の範囲内の条件に一致するすべての値の平均値 (算術平均) を返します。|
| [COUNT 関数](stastical.md#COUNT)                     | 引数リストの各項目に含まれる数値の個数を返します。|
| [COUNTA 関数](stastical.md#COUNTA)                   | 範囲に含まれる空白ではない引数リストに含まれる数値の個数を返します。|
| [COUNTBLANK 関数](stastical.md#COUNTBLANK)           | 指定された範囲に含まれる空白フィールドの個数を返します。|
| [COUNTIF 関数](stastical.md#COUNTIF)                 | 1 つの検索条件に一致する範囲内のフィールドの個数を返します。|
| [COUNTIFS 関数](stastical.md#COUNTIFS)               | 複数の検索条件に一致する範囲内のフィールドの個数を返します。|
| [LARGE 関数](stastical.md#LARGE)                     | 指定されたデータの中で k 番目に大きなデータを返します。|
| [MAX 関数](stastical.md#MAX)                         | 一連の引数のうち、最大の数値を返します。|
| [MAXIFS 関数](stastical.md#MAXIFS)                   | 条件セットで指定されたデータの中の最大値を返します。|
| [MODE.SNGL 関数](stastical.md#MODE.SNGL)             | 引数リストに含まれる数値データの中で、最も頻繁に出現する値 (モード) を返します。|
| [MODE.MULT 関数](stastical.md#MODE.MULT)             | 引数リストに含まれる数値データの中で、最も頻繁に出現する値 (モード) を配列で返します。|
| [MEDIAN 関数](stastical.md#MEDIAN)                   | 引数リストに含まれる数値のメジアン (中央値) を返します。|
| [MIN 関数](stastical.md#MIN)                         | 一連の引数のうち、最小の数値を返します。|
| [MINIFS 関数](stastical.md#MINIFS)                   | 条件セットで指定されたデータの中の最小値を返します。|
| [PERCENTILEEXC 関数](stastical.md#PERCENTILEEXC)     | 特定の範囲に含まれるデータの第 k 百分位数に当たる値を返します (k は 0 より大きく 1 より小さい値)。|
| [PERCENTILEINC 関数](stastical.md#PERCENTILEINC)     | 特定の範囲に含まれるデータの第 k 百分位数に当たる値を返します。|
| [PERCENTRANKEXC 関数](stastical.md#PERCENTRANKEXC)   | 配列内での値の順位を百分率 (0 より大きく 1 より小さい) で返します。|
| [PERCENTRANKINC 関数](stastical.md#PERCENTRANKINC)   | 配列内での値の順位を百分率 (0 ～ 1、0 および 1 を含む) で返します。|
| [QUARTILEEXC 関数](stastical.md#QUARTILEEXC)         | 0 ～ 1 の間 (0 および 1 を除く) の百分率の値に基づいて、データの配列の四分位数を返します。|
| [QUARTILEINC 関数](stastical.md#QUARTILEINC)         | 0 ～ 1 の間 (0 および 1 を含む) の百分率の値に基づいて、データの配列の四分位数を返します。|
| [RANK.AVG 関数](stastical.md#RANK.AVG)               | 数値のリストの中で、指定した数値の序列を返します。|
| [RANK.EQ 関数](stastical.md#RANK.EQ)                 | 数値のリストの中で、指定した数値の序列を返します。|
| [SMALL 関数](stastical.md#SMALL)                     | 指定されたデータの中で、k 番目に小さなデータを返します。 |
| [STDEV.P 関数](stastical.md#STDEV.P)                 | 引数を母集団全体と見なし、母集団の標準偏差を返します。|
| [STDEV.S 関数](stastical.md#STDEV.S)                 | 引数を正規母集団の標本と見なし、標本に基づいて母集団の標準偏差の推定値を返します。|
| [TRIMMEAN 関数](stastical.md#TRIMMEAN)               | データの中間項の平均を返します。|
| [VAR.P 関数](stastical.md#VAR.P)                     | 引数を母集団全体と見なし、母集団の分散 (標本分散) を返します。|
| [VAR.S 関数](stastical.md#VAR.S)                     | 標本に基づいて母集団の分散の推定値 (不偏分散) を返します。|

</div></details>

<details><summary>文字列関数</summary><div>

| 関数                                                 | 説明              |
|:----------------------------------------------------|:-----------------|
| [CHAR 関数](text.md#CHAR)                            | 数値で指定された文字を返します。|
| [CODE 関数](text.md#CODE)                            | テキスト文字列内の先頭文字の数値コードを返します。|
| [CONCAT 関数](text.md#CONCAT)                        | 複数の文字列を結合して 1 つの文字列にまとめます。|
| [CONCATENATE 関数](text.md#CONCATENATE)              | 複数の文字列を結合して 1 つの文字列にまとめます。|
| [DOLLAR 関数](text.md#DOLLAR)                        | 数値を四捨五入し、通貨書式を設定した文字列に変換します。|
| [EXACT 関数](text.md#EXACT)                          | 2 つの文字列が等しいかどうかを判定します。|
| [FIND 関数](text.md#FIND)                            | 指定された文字列を他の文字列の中で検索します。|
| [FIXED 関数](text.md#FIXED)                          | 数値を四捨五入し、書式設定した文字列に変換します。|
| [LEFT 関数](text.md#LEFT)                            | 文字列の先頭から指定された数の文字を返します。|
| [LEN 関数](text.md#LEN)                              | 文字列の文字数を返します。|
| [LOWER 関数](text.md#LOWER)                          | 文字列に含まれる英大文字をすべて小文字に変換します。|
| [MID 関数](text.md#MID)                              | 文字列の指定された位置から指定された文字数の文字を返します。|
| [PROPER 関数](text.md#PROPER)                        | 文字列に含まれる英単語の先頭文字だけを大文字に変換します。|
| [REPLACE 関数](text.md#REPLACE)                      | 文字列中の指定された数の文字を他の文字に置き換えます。|
| [REPT 関数](text.md#REPT)                            | 文字列を指定された回数だけ繰り返して表示します。|
| [RIGHT 関数](text.md#RIGHT)                          | 文字列の末尾 (右端) から指定された文字数の文字を返します。|
| [SEARCH 関数](text.md#SEARCH)                        | 指定された文字列を他の文字列の中で検索します。大文字と小文字は区別されません。|
| [SUBSTITUTE 関数](text.md#SUBSTITUTE)                | 文字列中の指定された文字を他の文字に置き換えます。|
| [TEXTJOIN 関数](text.md#TEXTJOIN)                    | 複数の範囲や文字列からのテキストを結合し、結合する各テキスト値の間に指定した区切り記号を挿入します。|
| [TRIM 関数](text.md#TRIM)                            | 文字列から余分なスペースを削除します。|
| [UPPER 関数](text.md#UPPER)                          | 文字列を大文字に変換します。|
| [YEN 関数](text.md#YEN)                              | 数値を四捨五入し、通貨書式を設定した文字列に変換します。|

</div></details>

<details><summary>その他の関数</summary><div>

| 関数                                                 | 説明              |
|:----------------------------------------------------|:-----------------|
| [UNIQUE 関数](miscellaneous.md#UNIQUE)               | 重複しない値を抽出します。|
| [NULL 関数](miscellaneous.md#NULL)                   | NULL を返します。|

</div></details>