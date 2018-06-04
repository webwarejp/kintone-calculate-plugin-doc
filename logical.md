# カテゴリ: 論理関数

### AND 関数

すべての引数が TRUE と評価された場合は TRUE を返し、1 つ以上の引数が FALSE と評価された場合は FALSE を返します。

### 書式

    AND(論理式 1, [論理式 2], ...)

| 引数       | 説明         |
|:-----------|:------------|
|論理式 1     | 必須。TRUE または FALSE に評価できるテスト対象の 1 つ目の条件。|
|論理式 2, ...| 省略可能。TRUE または FALSE に評価できるテスト対象のその他の条件。|

## FALSE 関数

論理値 FALSE を返します。

### 書式

    FALSE()

引数はありません。

## IF 関数

IF 関数を使うと、条件が TRUE または FALSE の場合に、それぞれ別の値を返すことができます。

### 書式

    IF(論理式, 論理式がTRUEの場合の値, [論理式がFALSEの場合の値])

| 引数                | 説明         |
|:-------------------|:------------|
|論理式               |必須。テストする条件|
|論理式がTRUEの場合の値|必須。論理式の結果がTRUEの場合に返す値|
|論理式がFALSEの場合の値|省略可能。論理式の結果がFALSEの場合に返す値|

## IFERROR 関数

数式の結果がエラーの場合は指定した値を返し、それ以外の場合は数式の結果を返します。

### 書式

    IFERROR(値, エラーの場合の値)

| 引数                | 説明         |
|:-------------------|:------------|
|値                  |必須。エラーかどうかをチェックする引数です。|
|エラーの場合の値      |必須。第一引数の値がエラーと評価された場合に返す値です。|

* 評価されるエラーの種類は #N/A、#VALUE!、#REF!、#DIV/0!、#NUM!、#NAME? または #NULL! があります。
* 値が NaN、 Infinity の場合もエラーと評価されます。

## NOT 関数

引数の論理値を反転させます。

### 書式

    NOT(論理式)

| 引数       | 説明         |
|:-----------|:------------|
|論理式     | 必須。TRUE または FALSE のどちらかに評価できる値または式を指定します。|

## OR 関数

いずれかの引数が TRUE と評価された場合は TRUE を返し、すべての引数が FALSE と評価された場合は FALSE を返します。

### 書式

    OR(論理式 1, [論理式 2], ...)

 引数       | 説明         |
|:-----------|:------------|
|論理式 1     | 必須。TRUE または FALSE に評価できるテスト対象の 1 つ目の条件。|
|論理式 2, ...| 省略可能。TRUE または FALSE に評価できるテスト対象のその他の条件。|

## SWITCH 関数

(式と呼ばれる) 1 つの値に対して値の一覧を評価し、最初に一致する値に対応する結果を返します。いずれにも一致しない場合は、任意指定の既定値が返されます。

### 書式

    SWITCH(式, 値 1, 結果 1, [既定値または 値 2, 結果 2],…)

 引数       | 説明         |
|:-----------|:------------|
|式          | 必須。値 1、値 2 ... に対して比較される値です。|
|値 1        | 必須。式に対して比較される最初の値です。|
|結果 1      | 必須。式と値 1 が一致したときに返される値です。|
|[値 2, 結果 2]... | 省略可能。式に対して比較される値と式と値が一致したときに返される値をセットで指定します。|
|既定値      |一致する項目が見つからなかった場合に返される値です。式を除いた引数の数が奇数だった場合、最後の引数を既定値とします。|

## TRUE 関数

論理値 TRUE を返します。 

### 書式

    TRUE()

引数はありません。

## XOR 関数

すべての引数の排他的論理和を返します。

### 書式

    XOR(論理式 1, [論理式 2],…)

 引数       | 説明         |
|:-----------|:------------|
|論理式 1     | 必須。TRUE または FALSE に評価できるテスト対象の 1 つ目の条件。|
|論理式 2, ...| 省略可能。TRUE または FALSE に評価できるテスト対象のその他の条件。|
