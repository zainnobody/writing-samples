---
title: HealthStackBackendAdapter
permalink: /healthstack-adapter/healthstack.backend.integration.adapter/-health-stack-backend-adapter/index.html

---
//[healthstack-adapter](/healthstack-adapter.html)/[healthstack.backend.integration.adapter](../index.html)/[HealthStackBackendAdapter](index.html)



# HealthStackBackendAdapter



[androidJvm]\
class [HealthStackBackendAdapter](index.html)(networkClient: [HealthStackBackendAPI](../-health-stack-backend-a-p-i/index.html), projectId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) : BackendFacade



## Constructors


| | |
|---|---|
| [HealthStackBackendAdapter](-health-stack-backend-adapter.html) | [androidJvm]<br>fun [HealthStackBackendAdapter](-health-stack-backend-adapter.html)(networkClient: [HealthStackBackendAPI](../-health-stack-backend-a-p-i/index.html), projectId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) |


## Types


| Name | Summary |
|---|---|
| [Companion](-companion/index.html) | [androidJvm]<br>object [Companion](-companion/index.html) |


## Functions


| Name | Summary |
|---|---|
| [getTasks](get-tasks.html) | [androidJvm]<br>open suspend override fun [getTasks](get-tasks.html)(idToken: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), lastSyncTime: [LocalDateTime](https://developer.android.com/reference/kotlin/java/time/LocalDateTime.html), endTime: [LocalDateTime](https://developer.android.com/reference/kotlin/java/time/LocalDateTime.html)): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;TaskSpec&gt; |
| [registerUser](register-user.html) | [androidJvm]<br>open suspend override fun [registerUser](register-user.html)(idToken: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), user: User) |
| [sync](sync.html) | [androidJvm]<br>open suspend override fun [sync](sync.html)(idToken: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), healthData: HealthData) |
| [uploadTaskResult](upload-task-result.html) | [androidJvm]<br>open suspend override fun [uploadTaskResult](upload-task-result.html)(idToken: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), result: TaskResult) |

