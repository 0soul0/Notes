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
