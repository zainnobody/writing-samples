---
title: StepModel
permalink: /kit/healthstack.kit.task.base/-step-model/index.html

---
//[kit](/kit.html)/[healthstack.kit.task.base](../index.html)/[StepModel](index.html)



# StepModel



[androidJvm]\
abstract class [StepModel](index.html)(val id: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val title: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val drawableId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)?)

A data object for [Step](../-step/index.html).



It has properties representing Step's state such as title, selectedValue etc.



And it also has functions calculating Step's result.



It is passed to composable function of [View](../-view/index.html) as parameter.



Then, View renders UI using Model's data.



## Constructors


| | |
|---|---|
| [StepModel](-step-model.html) | [androidJvm]<br>fun [StepModel](-step-model.html)(id: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), title: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), drawableId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)?) |


## Properties


| Name | Summary |
|---|---|
| [drawableId](drawable-id.html) | [androidJvm]<br>val [drawableId](drawable-id.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)?<br>a representative image for UI |
| [id](id.html) | [androidJvm]<br>val [id](id.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>id |
| [title](title.html) | [androidJvm]<br>val [title](title.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>a title of UI |


## Inheritors


| Name |
|---|
| [ImageArticleModel](../-image-article-model/index.html) |
| [ConsentTextModel](../../healthstack.kit.task.onboarding.model/-consent-text-model/index.html) |
| [EligibilityIntroModel](../../healthstack.kit.task.onboarding.model/-eligibility-intro-model/index.html) |
| [EligibilityResultModel](../../healthstack.kit.task.onboarding.model/-eligibility-result-model/index.html) |
| [IntroModel](../../healthstack.kit.task.onboarding.model/-intro-model/index.html) |
| [RegistrationCompletedModel](../../healthstack.kit.task.signup.model/-registration-completed-model/index.html) |
| [SignUpModel](../../healthstack.kit.task.signup.model/-sign-up-model/index.html) |
| [SurveyModel](../../healthstack.kit.task.survey.model/-survey-model/index.html) |

