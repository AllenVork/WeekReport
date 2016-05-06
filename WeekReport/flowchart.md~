# 在此处输入标题

标签（空格分隔）： flowchart

---

```flow
st=>start: Start|past:>http://www.google.com[blank]
e=>end: End:>http://www.google.com
op1=>operation: My Operation|past
op2=>operation: Stuff|current
sub1=>subroutine: My Subroutine|invalid
cond=>condition: Yes 
or No?|approved:>http://www.baidu.com
c2=>condition: Good idea|rejected
io=>inputoutput: catch something...|request

st->op1(right)->cond
cond(yes, right)->c2
cond(no)->sub1(left)->op1
c2(yes)->io->e
c2(no)->op2->e
```

<<<<<<< HEAD
graph LR    

    A-->B
    
    
 %% Subgraph example    
 
 graph TB 
 
         subgraph one
         a1-->a2
         end
         subgraph two
         b1-->b2
         end
         subgraph three
         c1-->c2
         end
         c1-->a2
         
         
=======

<table>
<tr><th>Code</th><th>Rendered diagram</th></tr>
<tr><td>
<pre>
<code>
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
<code>
</pre>
</td>
<td>
<img src='http://www.sveido.com/mermaid/img/ex1.png' alt='Example 1'>
</td>
</tr>
<tr>
<td>
<pre>
<code>
sequenceDiagram
    participant Alice
    participant Bob
    Alice->>John: Hello John, how are you?
    loop Healthcheck
        John->>John: Fight against hypochondria
    end
    Note right of John: Rational thoughts &lt;br/>prevail...
    John-->>Alice: Great!
    John->>Bob: How about you?
    Bob-->>John: Jolly good!
</code>
</pre>
</td>
<td>
<img src='http://www.sveido.com/mermaid/img/seq1.png' alt='Example 2'>
</td>
</tr>
</table>
>>>>>>> 测试table语法
