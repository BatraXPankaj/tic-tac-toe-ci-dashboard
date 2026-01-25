```

BenchmarkDotNet v0.13.12, Ubuntu 24.04.3 LTS (Noble Numbat)
AMD EPYC 7763, 1 CPU, 2 logical cores and 1 physical core
.NET SDK 10.0.102
  [Host]     : .NET 8.0.23 (8.0.2325.60607), X64 RyuJIT AVX2
  DefaultJob : .NET 8.0.23 (8.0.2325.60607), X64 RyuJIT AVX2


```
| Method            | Mean     | Error    | StdDev   | Gen0   | Allocated |
|------------------ |---------:|---------:|---------:|-------:|----------:|
| ComputeBestMove_X | 24.92 μs | 0.199 μs | 0.186 μs | 1.4343 |  23.57 KB |
| ComputeBestMove_O | 24.77 μs | 0.166 μs | 0.148 μs | 1.4343 |  23.48 KB |
