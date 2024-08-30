---
layout: default
title: 適用済製品差替
parent: 製品登録
grand_parent: ベース図面の登録
nav_order: 3
has_children: false
---

# 適用済のベース図面を差し替える
### ベース図面の差替を行った後に、どの製品を差し替え対象とするか選択して登録します。

<br>

{: .warning }
この機能は同じ図面名称、図面番号のベース図面が複数ある場合のみ使用できます。  
適用済製品差替機能を使うには、先に[ベース図面の複製]({% link docs/drawing-registration/reproduction-drawing/index.md%})を行ってください。

1. [品質管理システム]トップ画面から「ベース図面」を選択します。

    <table><tr><td>
    <img src="../../../../assets/images/drawing-registration/registration-product/replacing-product/1.png" width="60%">
    </td></tr></table>

2. [ベース図面一覧]画面で製品登録したいベース図面の「詳細」をクリックします。

    <table><tr><td>
    <img src="../../../../assets/images/drawing-registration/registration-product/replacing-product/2.png" width="85%">
    </td></tr></table>

3. 「製品」をクリックするとポップアップが表示されます。

    <table><tr><td>
    <img src="../../../../assets/images/drawing-registration/registration-product/replacing-product/3.png" width="90%">
    </td></tr></table>

4. 3パターンの製品登録方法が表示されます。「適用済製品差替」をクリックします。

    <table><tr><td>
    <img src="../../../../assets/images/drawing-registration/registration-product/replacing-product/4.png" width="50%">
    </td></tr></table>

5. [適用済製品一覧]に、同じ図面名称、図面番号のベース図面が登録されている製品の一覧が表示されます。  
    [適用済製品一覧]から、ベース図面を差し替えたい製品を選んで✔️をつけます。

    <table><tr><td>
    <img src="../../../../assets/images/drawing-registration/registration-product/replacing-product/5.png" width="100%">
    </td></tr></table>

    - **検索**  
    [適用済製品一覧]を階数などの検索条件で絞り込むことが可能です。

    <table><tr><td>
    <img src="../../../../assets/images/drawing-registration/registration-product/replacing-product/6.png" width="90%">
    </td></tr></table>

6. 「差替」をクリックで、✔️をつけた製品が登録対象の一覧に表示されます。  

    <table><tr><td>
    <img src="../../../../assets/images/drawing-registration/registration-product/replacing-product/7.png" width="100%">
    </td></tr></table>

    {: .warning } 
    製品情報はこの画面上では変更できません。変更は[製品情報の変更]({% link docs/product-registration/edit-product/index.md%})を参考に行ってください。

    - **ステータス**  
    2パターンのステータスがあります。  

    <table><tr><td>
    <img src="../../../../assets/images/drawing-registration/registration-product/replacing-product/8.png" width="100%">
    </td></tr></table>

    | ステータス | 登録可否 | 詳細                                         | 
    | ---------- | -------- | -------------------------------------------- | 
    | <span style="color: blue; ">更新</span>     | ○ | 既存の製品にベース図面を適用する           | 
    | <span style="color: red; ">重複</span>      | × | 登録対象一覧に同じ製品番号のデータが複数ある | 

    - **削除**  
    右端までスクロールすると「×」があるので、このボタンから削除が可能です。  
    全ての一覧を削除したい場合は、一度前画面に戻ることでリセットされます。

    <table><tr><td>
    <img src="../../../../assets/images/drawing-registration/registration-product/replacing-product/9.png" width="75%">
    </td></tr></table>

7. 差し替えたい製品を一覧に追加したら、「登録」をクリックでベース図面を適用する製品の登録が完了します。 

    <table><tr><td>
    <img src="../../../../assets/images/drawing-registration/registration-product/replacing-product/10.png" width="100%">
    </td></tr></table>

    {: .warning }  
    登録対象の一覧に<span style="color: red; ">[重複]</span>ステータスのデータがある場合は登録できません。