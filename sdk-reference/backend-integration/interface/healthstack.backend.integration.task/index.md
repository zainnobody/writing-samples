---
title: healthstack.backend.integration.task
permalink: /interface/healthstack.backend.integration.task/index.html

---
//[interface](/bi_interface.html)/[healthstack.backend.integration.task](index.html)



# Package healthstack.backend.integration.task



## Types


| Name | Summary |
|---|---|
| [ChoiceProperties](-choice-properties/index.html) | [androidJvm]<br>class [ChoiceProperties](-choice-properties/index.html)(val tag: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val options: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[Option](-option/index.html)&gt;) : [ItemProperties](-item-properties/index.html)<br>Item properties for the choice question. |
| [Contents](-contents/index.html) | [androidJvm]<br>data class [Contents](-contents/index.html)(val type: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val title: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val explanation: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, val itemProperties: [ItemProperties](-item-properties/index.html), val required: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))<br>Stores the information of the contents received from backend. |
| [Item](-item/index.html) | [androidJvm]<br>data class [Item](-item/index.html)(val name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val type: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val contents: [Contents](-contents/index.html), val sequence: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>Stores the information of the item received from backend. |
| [ItemProperties](-item-properties/index.html) | [androidJvm]<br>open class [ItemProperties](-item-properties/index.html)(val tag: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html))<br>System distinguishes the UI component based on the tag. |
| [ItemResult](-item-result/index.html) | [androidJvm]<br>data class [ItemResult](-item-result/index.html)(val itemName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val result: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html))<br>Data Transfer Object for uploading the result of each item. |
| [Option](-option/index.html) | [androidJvm]<br>data class [Option](-option/index.html)(val value: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html))<br>Stores the option. |
| [PropertyDeserializer](-property-deserializer/index.html) | [androidJvm]<br>class [PropertyDeserializer](-property-deserializer/index.html) : JsonDeserializer&lt;[ItemProperties](-item-properties/index.html)&gt; |
| [ScaleProperties](-scale-properties/index.html) | [androidJvm]<br>class [ScaleProperties](-scale-properties/index.html)(val tag: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val low: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), val high: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), val lowLabel: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, val highLabel: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?) : [ItemProperties](-item-properties/index.html)<br>Item properties for the scale question. |
| [TaskClient](-task-client/index.html) | [androidJvm]<br>interface [TaskClient](-task-client/index.html)<br>Interface for get task from the backend and upload result to the backend. |
| [TaskResult](-task-result/index.html) | [androidJvm]<br>data class [TaskResult](-task-result/index.html)(val userId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val taskId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val revisionId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), val startedAt: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val submittedAt: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val itemResults: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[ItemResult](-item-result/index.html)&gt;)<br>Data Transfer Object for uploading the result of the task. |
| [TaskSpec](-task-spec/index.html) | [androidJvm]<br>data class [TaskSpec](-task-spec/index.html)(val revisionId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), val taskId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val title: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val description: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val schedule: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val startTime: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val endTime: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val validTime: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html), val items: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[Item](-item/index.html)&gt;)<br>Stores the information of the task received from backend. |

