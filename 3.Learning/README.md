<h3>Learning</h3>
<p>1. launchMode</p>

```php 
  A set launchMode
  standard:
    stack: A->B->C => C to B: A->B->A
    GotoB: A(onCreate->onStart->onResume->onPause)->B(onCreate->onStart->onResume)->A(onStop)
    GotoA: B(onPause)->A(onCreate->onStart->onResume)->B(onStop)
    
  singleTop: A在最上面時 不會創新的B
    stack: //
    GotoB: //
    GotoA: //
  
  singleTask: 回到Ａ會清除A上面到所有activty
    stack: A->B->C => B to A: A
    GotoB: //
    GotoA: B(onPause)->A(onRestart->onStart->onNewIntent "獲取新的restart intent"->onResume)->B(onStop->onDestroy)
    
  singleInstance:
   
```

<p>2. GridView vs GridLayout</p>

```php  
 兩個都是網格佈局,差別在於GridView像recycleview 無限長度
```

<p>3.onDraw->invalidate vs postInvalidate</p>

```php  
 invalidate: 刷新整個view
 postInvalidate: 在子線程 刷新整個view
```
