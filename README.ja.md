# Ingedish — ING・ED・ISH

> **That’s not English.**  
> **Correct. It’s Ingedish.**
>
> **「それEnglishじゃないよ」**  
> **「その通り。Ingedishだよ」**

**Ingedish v0.1**

[English](./README.md)

---

## Ingedishとは？

**Ingedish** は、Englishの単語やmorpheme（形態素）をもとにしたlanguage game（言葉遊び）です。

通常のEnglishでは付けないような単語にも、prefix（接頭辞）やsuffix（接尾辞）を比較的自由に付けて遊びます。

たとえば：

```text
why
→ whying

because
→ becausing

between
→ betweened

everything
→ everythinging

love
→ loving
→ lovinged
→ lovingedish
```

これらは、普通のEnglishとして文法的に正しい必要はありません。

元の単語、付けられたaffix、その順序、syntax（構文）、context（文脈）を見て、

> 「たぶんこういう意味じゃない？」

と読み手がdecodeできれば、それでIngedishとして機能しています。

Ingedishの中心にある考え方は：

> **Understandability > grammaticality.**  
> **文法的正しさより、理解できること。**

もっと短く言えば：

> **If you understood it, it worked.**  
> **意味が分かったなら、それは機能した。**

IngedishはEnglishを置き換えるための提案ではありません。

また、現時点では完全な文法を持つconstructed language（人工言語）を目指しているわけでもありません。

Englishのmorphologyを伸ばしたり、曲げたり、積み重ねたり、ときには壊したりしながら、それでも意味が残るかを楽しむlanguage gameです。

---

## ING・ED・ISH

名前そのものが：

```text
ING + ED + ISH
= INGEDISH
```

になっています。

そして同時に、`English` の綴りをちょっと間違えたようにも見えます。

`-ing`、`-ed`、`-ish` はIngedishで特に使いやすいsuffixですが、v0.1では厳密なformal definitionを与えません。

基本的には、Englishですでに感じられるニュアンスをそのまま借ります。

### `-ing`

おおまかには、単語に **-ing / 現在分詞っぽい性質** を与えます。

```text
why
→ whying

with
→ withing

everything
→ everythinging
```

`whying` なら、「なぜ？」と問うこと、考えること、あるいは *whyする* こと。

`withing` なら、誰かと一緒にいること。

`everythinging` なら、`everything` を行為・過程・状態のように扱うこと。

そのくらいの感覚です。

### `-ed`

おおまかには、単語に **-ed / 過去・完了・結果状態っぽい性質** を与えます。

```text
between
→ betweened

nothing
→ nothinged

loving
→ lovinged
```

contextによって、

「そうなった」  
「そういう状態が成立した」  
「そういう結果状態になった」

といった読み方が生まれることがあります。

ただし、

> `-ed = 受動`

と一つの意味に固定するものではありません。

### `-ish`

おおまかには、単語を**形容詞っぽくしつつ、意味を少し弱めたり、曖昧にしたりする**働きをします。

```text
lovinged
→ lovingedish
```

たとえば：

```text
kind of lovinged
sort of lovinged
lovinged-like
seemingly lovinged
```

つまり、

```text
lovingedっぽい
lovingedみたい
なんとなくlovinged
```

くらいの感じです。

正確な解釈はcontextに任せます。

---

## Affixはoperatorのように振る舞う

Ingedishでは、新しく付けたaffixが、それまでにできた意味へ作用していく、と考えることができます。

```text
love
→ loving
→ lovinged
→ lovingedish
```

概念的には：

```text
ISH(ED(ING(love)))
```

のように考えることもできます。

ただし、これはIngedishを考えるための便利な見方にすぎません。

Ingedishを厳密な型付きsemantic systemにすることが目的ではありません。

大事なのは単純に：

> **順番によって意味が変わりうる。**

ということです。

---

## Words are suffixable

Standard Englishでは、単語の品詞によって「どのsuffixを付けられるか」がかなり制限されます。

Ingedishでは、その制限をsuggestionくらいに扱います。

```text
why → whying
because → becausing
if → ifing
what → whating
with → withing
everything → everythinging
```

前置詞を行為っぽくしてもいい。

疑問詞をprocessっぽくしてもいい。

名詞をpredicateっぽくしてもいい。

変でも構いません。

> **Strange is allowed.**

---

## Parts of speech are suggestions

Ingedishedされた単語は、必ずしも一つの固定された品詞を持つ必要はありません。

たとえば：

> **I am whying you.**

> **My whying never stops.**

> **That’s a very whying cat.**

同じ `whying` が、異なるsyntax上の役割を持ちながらも、`why` に関係する意味の核を残しています。

同様に：

> **I everythinging you.**

と：

> **This is my everythinging.**

では、同じ `everythinging` が違う役割をしています。

現在のIngedishを説明するなら：

> **Morphology builds meaning. Syntax gives it a job.**  
> **Morphologyが意味を作り、syntaxがその場での役割を与える。**

という表現が近そうです。

---

## Prefixとscope

Ingedishでは：

```text
un-
re-
over-
under-
```

などのprefixも使えます。

たとえば：

```text
unlovinged
```

は自然には：

```text
un + (love + ing + ed)
```

のように読めるかもしれません。

ただし、contextによって別のまとまり方が意味を持つなら、それも禁止しません。

意図したまとまりを見せたい場合は、hyphenを使えます。

```text
un-lovinged
unlove-ing-ed
re-un-I-ed
```

Hyphenは任意です。

> **Ambiguity is playable.**  
> **曖昧さも遊べる。**

---

## Spelling is flexible

Ingedishでは、一つのspelling conventionを強制しません。

たとえば：

```text
hope + ing
```

なら：

```text
hoping
hopeing
hope-ing
```

のような書き方が考えられます。

`hoping` はstandard Englishの綴りとして読みやすい。

`hopeing` は元の `hope` を視覚的に残します。

`hope-ing` はmorpheme boundaryを明示します。

一つの目安は：

> **Spelling is flexible. Morphemes should remain recoverable.**  
> **綴りは自由。ただし、元のmorphemeを復元できること。**

目的はrandomなspelling mistakeではありません。

読み手が、

> 「ああ、これにこれを付けたのか」

とdecodeできることが重要です。

> “You spelled it wrong.”  
> 「綴り間違ってるよ」

と言われたら：

> **“No. I Ingedished it.”**  
> **「違う。Ingedishしたんだ。」**

---

## Existing EnglishもIngedishできる

すでにEnglishに存在する単語だからといって、それ以上Ingedishしてはいけないわけではありません。

```text
everything
→ everythinging
```

また、毎回etymologyを調べたり、歴史的に正しいmorpheme boundaryを探したりする必要もありません。

遊べそうな構造が見えるなら、遊んで構いません。

---

## Comprehensibility

Ingedishの表現は、単純に：

```text
正しい
間違い
```

だけで分ける必要はありません。

すぐ分かるものもあります。

少し曖昧なものもあります。

考えればdecodeできるものもあります。

完全に意味不明になるものもあります。

たとえば：

> **My whying never stops.**

は比較的すぐ理解できます。

一方：

> **I sleepingedish you.**

はかなりinterpretation costが高いですが、contextによっては何らかの意味を作ることができます。

morphologyが深くなれば、一般にdecodeするための努力も増えていきます。

ただし、数値的な境界を作る必要はありません。

Ingedishは自由ですが、デタラメである必要はありません。

読み手がdecodeするための手掛かりが、どこかに残っていることが大切です。

---

## `-ness`

Ingedishではsyntaxによってnounっぽい役割を持たせられるため、名詞として使うためだけに `-ness` が必須なわけではありません。

> **My whying never stops.**

では、`whying` 自体を行為やconceptとして読むことができます。

一方：

```text
lovingedish
→ lovingedishness
```

とすると、

`lovingedish` である状態、性質、conditionをconceptとして扱いやすくなります。

`-ness` は便利ですが、必須ではありません。

---

## Repetition

Affixを繰り返しても構いません。

```text
lovingedish
lovingedishish
lovingedishishish
```

Ingedishでは、反復回数にformalな意味を定義しません。

contextによって：

- さらに曖昧
- さらに「っぽい」
- 強調
- ためらい
- 遊び

などを感じても構いません。

たとえば：

```text
lol
loool
looooool
```

のようなexpressiveな反復に近いものです。

> **Some things do not need to be grammarized.**

---

## Some things are better left unwhyinged.

Ingedishを代表する表現の一つです。

> **Some things are better left unwhyinged.**

おおよその意味は：

> **物事には、「なぜ？」と問わないままにしておいたほうがいいものもある。**

です。

この文が理解しやすい理由の一つは：

> *Some things are better left ...*

という既知のEnglish syntaxが足場になっていることです。

読み手は、見たことのない `unwhyinged` の意味を、周囲のsyntaxからdecodeできます。

> **English syntax can act as scaffolding for unfamiliar morphology.**

既知のsyntaxが、未知のmorphologyを支える。

これはIngedishの重要な性質の一つです。

---

## I everythinging you.

もう一つの代表的な表現です。

> **I everythinging you.**

`everythinged` は、正確には何を意味するのでしょうか。

Love?

Want?

Give everything to?

Do everything for?

Make someone your everything?

その全部かもしれません。

どれでもないかもしれません。

この曖昧さは、失敗ではなく表現そのものの一部です。

読み手が必ず一つのdictionary definitionへ到達する必要はありません。

ときには：

> **If you understood it, it worked.**

で十分です。

---

## Ingedish Poetry

> After I happenedinged to look at you,  
> I became lovingedish of you.
>
> There was no meaning in  
> ifing, whying, becausing,  
> or even whating.
>
> I started un-I-ing for you.
>
> **I everythinging you.**

これはIngedish grammarの模範解答ではありません。

Ingedishを使うと何ができるか、その一例です。

---

## Open Question: Tense and Aspect

Tenseとaspectは、**Ingedish v0.1では意図的にOpen Questionのまま**です。

たとえば、過去をword内部へさらに積み重ねるべきでしょうか？

```text
happeningeded
```

それとも、普通のEnglish syntaxに時制を担当してもらうべきでしょうか？

```text
is happeninged
was happeninged
has been happeninged
might be happeninged
```

どちらの方法にも面白いinterpretationと問題があります。

今の段階で無理に一つのruleを作るより：

> **Tense and aspect remain experimental.**

としておきます。

> **Some things are better left unwhyinged.**

---

## Ingedishではないもの

IngedishはEnglishを置き換えるための提案ではありません。

現時点では、完全なgrammarを持つconstructed languageでもありません。

そして、単なるrandomなbroken Englishでもありません。

Ingedishの面白さは：

> **どこまで壊してもdecodeできるのか**

というところにあります。

Englishが読み手にexpectationを与える。

Ingedishがそのexpectationを伸ばしたり、曲げたり、壊したりする。

そして読み手が、残った手掛かりから意味をdecodeする。

すぐ分かることもあります。

少し考えることもあります。

完全に失敗することもあります。

どれも面白い結果です。

---

## Ingedish v0.1 Declaration

> **Words are suffixable.**  
> **単語にはsuffixできる。**
>
> **Parts of speech are suggestions.**  
> **品詞はsuggestionである。**
>
> **Affixes behave like operators.**  
> **Affixはoperatorのように振る舞う。**
>
> **Affixes mean in the order they happen.**  
> **Affixは作用した順番に意味を重ねる。**
>
> **Spelling is flexible.**  
> **綴りはflexibleである。**
>
> **Hyphens are optional.**  
> **Hyphenは任意である。**
>
> **Ambiguity is playable.**  
> **曖昧さも遊べる。**
>
> **If you understood it, it worked.**  
> **意味が分かったなら、それは機能した。**

そして何より：

> # Stop grammarizing. Start suffixing.

---

> **That’s not English.**  
> **Correct. It’s Ingedish.**

**Ingedish v0.1**

## License

このリポジトリ内のドキュメントおよびオリジナル素材は、特に記載がない限り **CC BY-NC 4.0** のもとで公開されています。

Ingedishは、遊ぶためのlanguage gameです。