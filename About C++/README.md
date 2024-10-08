# Modern Cpp 在追求什麼?

來到 Modern Cpp，Cpp 已經不僅僅是個有物件導向的 C 了，其還追求 type-safe, metaprograming 與 static/compile time error 等議題，並包含了如 functional language 的特性進來，已經與以往的 Cpp 長的完全不一樣了。 \

如果要我講個我認為 Modern C++ 最重要的東西出來，我會選 RAII 與 move，在 modern C++ 前你會在 code 裡面發現許多的 new/delete 與複製，這代表我們時常需要手動確保我們資源的生命週期，而 RAII 與 move 幫助我們做了這件事，而且做得很好，但也因此 C++ 的核心觀念有些改動。 \

這種例子在近代 C++ 內很多，然後在眾多改動中我覺得這個是最重要的改動，且其他大部分的改動其實都是語法糖，不過 spec 會對這個語法糖進行類似「語意」上的定義，或說某些條件，有點像在自己定義出新的概念，並繼續在此概念上疊上新的概念，但本質上整個都是語法糖，也因此語意在 C++ 內是個很重要的因素，但我有看見許多人並不清楚他在使用的語意為何，又或說「味道」更為精確。 \

# C++ standard

## C++ 11
RAII \
std::move \
smart pointer \
...\

## C++ 14
std::make_unique<T> \
Lambda capture initializers: [capture_var = expression](parameters) { /* body */ } \
... \

## C++ 17
std::optional \
...\


