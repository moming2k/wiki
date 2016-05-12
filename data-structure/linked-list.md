Linked List
===========

Linked List ，鏈結串列，它是藉由指標去得到下一筆資料的記憶體位址，然後一筆資料接著一筆下去。跟陣列比起來，它在插入和刪除資料時，就顯得簡單許多。但結構上也確實比陣列複雜了許多。

搜尋時間複雜度是 O(N)。在知道記憶體位址的時候，插入與刪除的時間複雜度是 O(1)。不知道記憶體位址就必需先搜尋。沒有索引值，所以沒辦法實作 Binary Search 。

優點：

* 新修刪除資料，只要改指標內容就可以簡單完成
* 資料要多要少都是可以動態調整的

缺點：

* 結構複雜
* 找資料的時候需一筆一筆找，沒辦法像陣列一樣隨機存取。

Definition
----------

* *head* 指標，整個串列只會有一個，指向所有節點的開頭
* *tail* 指標，整個串列只會有一個，指向最後一個節點
* *next* 指標，每一個節點都會有一個，指向下一個節點
* *back* 指標，在雙向鏈結裡，每一個節點都會有一個，指向前一個節點

Singly Linked List
------------------

單向鏈結串列

Doubly Linked List
------------------

雙向鏈結串列

Circular List
-------------

環狀串列是原本單向連結的最後一個節點指標，指向 head 節點，把圖畫出來就很像一個環，固稱環狀鏈結

環狀串列的特點是：

* 通常需要在一開始就決定大小，也通常不會調整大小。
* 通常會實做 tail ，不然每次要新增資料都必須 foreach 過一次。
* 從任一節點就可以追蹤所有節點，所以 head 在哪都無所謂。