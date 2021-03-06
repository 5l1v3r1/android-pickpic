[pickapp](../../../index.md) / [com.lovoo.android.pickapp.adapter](../../index.md) / [SelectionAdapter](../index.md) / [ViewHolder](./index.md)

# ViewHolder

`class ViewHolder : ViewHolder` [(source)](https://github.com/lovoo/android-pickpic/blob/master/pickapp/src/main/kotlin/com/lovoo/android/pickapp/adapter/SelectionAdapter.kt#L92)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `ViewHolder(view: View, imageEngine: ImageEngine)` |

### Properties

| Name | Summary |
|---|---|
| [size](size.md) | `val size: MutableLiveData<`[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`>` |

### Functions

| Name | Summary |
|---|---|
| [bind](bind.md) | `fun bind(uri: Uri?, isSelected: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`, onClickListener: ((View, Uri) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`)?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |

### Companion Object Functions

| Name | Summary |
|---|---|
| [create](create.md) | `fun create(parent: ViewGroup, imageEngine: ImageEngine): `[`SelectionAdapter.ViewHolder`](./index.md) |
