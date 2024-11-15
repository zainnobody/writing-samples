---
title: healthstack.kit.task.onboarding.model
permalink: /kit/healthstack.kit.task.onboarding.model/index.html

---
//[kit](/kit.html)/[healthstack.kit.task.onboarding.model](index.html)



# Package healthstack.kit.task.onboarding.model



## Types


| Name | Summary |
|---|---|
| [ConsentTextModel](-consent-text-model/index.html) | [androidJvm]<br>class [ConsentTextModel](-consent-text-model/index.html)(val id: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val title: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val subTitle: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val description: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val checkBoxTexts: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)&gt;, val drawableId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)? = null) : [StepModel](../healthstack.kit.task.base/-step-model/index.html) |
| [EligibilityCheckerModel](-eligibility-checker-model/index.html) | [androidJvm]<br>open class [EligibilityCheckerModel](-eligibility-checker-model/index.html)(val id: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val title: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val drawableId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)? = null) : [SurveyModel](../healthstack.kit.task.survey.model/-survey-model/index.html) |
| [EligibilityIntroModel](-eligibility-intro-model/index.html) | [androidJvm]<br>open class [EligibilityIntroModel](-eligibility-intro-model/index.html)(val id: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val title: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val description: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val drawableId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)? = null, val conditions: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[EligibilityIntroModel.EligibilityCondition](-eligibility-intro-model/-eligibility-condition/index.html)&gt;, val viewType: [EligibilityIntroModel.ViewType](-eligibility-intro-model/-view-type/index.html)) : [StepModel](../healthstack.kit.task.base/-step-model/index.html) |
| [EligibilityResultModel](-eligibility-result-model/index.html) | [androidJvm]<br>class [EligibilityResultModel](-eligibility-result-model/index.html)(val id: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val title: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val drawableId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)? = null, val successModel: [ImageArticleModel](../healthstack.kit.task.base/-image-article-model/index.html), val failModel: [ImageArticleModel](../healthstack.kit.task.base/-image-article-model/index.html)) : [StepModel](../healthstack.kit.task.base/-step-model/index.html) |
| [IntroModel](-intro-model/index.html) | [androidJvm]<br>open class [IntroModel](-intro-model/index.html)(val id: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val title: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val drawableId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)? = R.drawable.sample_image_alpha4, val logoDrawableId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)? = null, val summaries: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[Pair](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)&lt;[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)&gt;&gt;? = null, val sections: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[IntroModel.IntroSection](-intro-model/-intro-section/index.html)&gt;) : [StepModel](../healthstack.kit.task.base/-step-model/index.html) |

