# MonoSharp
Mono External Library for C#

Based on [Reahly's](https://github.com/reahly) popular [Mono External Library for C++](https://github.com/reahly/mono-external-lib)

Example Usage:
```csharp
var hardSettings = Mono.GetStaticFieldDataOfClass("Assembly-CSharp", "EFTHardSettings");
```

You may need to tweak this to suit your needs, and provide your own `Read<T>` function :)
