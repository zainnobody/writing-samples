---
title: CallbackCollection
permalink: /kit/healthstack.kit.task.base/-callback-collection/index.html

---
//[kit](/kit.html)/[healthstack.kit.task.base](../index.html)/[CallbackCollection](index.html)



# CallbackCollection



[androidJvm]\
open class [CallbackCollection](index.html)

A object holding callback functions.



Callbacks are defined in [Task](../-task/index.html), and then sent to [Step](../-step/index.html) and [View](../-view/index.html).



Step and View can access or change properties of Task using provided callback functions.



## Constructors


| | |
|---|---|
| [CallbackCollection](-callback-collection.html) | [androidJvm]<br>fun [CallbackCollection](-callback-collection.html)() |


## Functions


| Name | Summary |
|---|---|
| [getEligibility](get-eligibility.html) | [androidJvm]<br>open fun [getEligibility](get-eligibility.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [next](next.html) | [androidJvm]<br>open fun [next](next.html)() |
| [prev](prev.html) | [androidJvm]<br>open fun [prev](prev.html)() |
| [setEligibility](set-eligibility.html) | [androidJvm]<br>open fun [setEligibility](set-eligibility.html)(value: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)) |

