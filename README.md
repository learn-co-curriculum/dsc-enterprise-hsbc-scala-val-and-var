
## `val` and `var`

### `val`

* `val` is called a value
* It is immutable, therefore unchangeable
* No reassignment
* Since Scala is mostly a functional language, and immutability is preferred, using `val` is absolutely preferred


```scala
val a = 10
```




    a: Int = 10
    



### Reassignment of `val`

A reassignment is out of the question with a `val`. Try it.


```scala
val a = 10
a = 19 //error: reassignment to val
```


    <console>:27: error: reassignment to val

           a = 19 //error: reassignment to val

             ^

    


### `var`


* Called a variable
* It is mutable, therefore changeable
* Reassignable
* Used sparingly, or not at all
* Usually kept from being changed from the outside


```scala
var a = 10
a = 19
println(19)
```


    Intitializing Scala interpreter ...



    Spark Web UI available at http://32c6e00c8fb3:4041
    SparkContext available as 'sc' (version = 2.4.3, master = local[*], app id = local-1562105228608)
    SparkSession available as 'spark'
    


    19
    




    a: Int = 19
    a: Int = 19
    


