[subkt](../../index.md) / [myaa.subkt.tasks](../index.md) / [org.gradle.api.provider.MapProperty](./index.md)

### Extensions for org.gradle.api.provider.MapProperty

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `operator fun <K, V> `[`MapProperty`](https://docs.gradle.org/current/javadoc/org/gradle/api/provider/MapProperty.html)`<`[`K`](invoke.md#K)`, `[`V`](invoke.md#V)`>.invoke(vararg pairs: `[`Pair`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)`<`[`K`](invoke.md#K)`, `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`>): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Adds all specified key/value pairs to the map property.`operator fun <K, V> `[`MapProperty`](https://docs.gradle.org/current/javadoc/org/gradle/api/provider/MapProperty.html)`<`[`K`](invoke.md#K)`, `[`V`](invoke.md#V)`>.invoke(map: `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`K`](invoke.md#K)`, `[`V`](invoke.md#V)`>): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Adds all items in the specified map to the map property.`operator fun <K, V> `[`MapProperty`](https://docs.gradle.org/current/javadoc/org/gradle/api/provider/MapProperty.html)`<`[`K`](invoke.md#K)`, `[`V`](invoke.md#V)`>.invoke(map: `[`Provider`](https://docs.gradle.org/current/javadoc/org/gradle/api/provider/Provider.html)`<out `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`K`](invoke.md#K)`, `[`V`](invoke.md#V)`>>): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Adds the items of the output of the given [Provider](https://docs.gradle.org/current/javadoc/org/gradle/api/provider/Provider.html) to the map property, evaluated lazily.`operator fun <K, V> `[`MapProperty`](https://docs.gradle.org/current/javadoc/org/gradle/api/provider/MapProperty.html)`<`[`K`](invoke.md#K)`, `[`V`](invoke.md#V)`>.invoke(call: () -> `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`K`](invoke.md#K)`, `[`V`](invoke.md#V)`>): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Adds the items of the output of the given closure to the map property, evaluated lazily. |