```

BenchmarkDotNet v0.13.12, Ubuntu 24.04.3 LTS (Noble Numbat)
AMD EPYC 7763, 1 CPU, 2 logical cores and 1 physical core
.NET SDK 9.0.305
  [Host]     : .NET 8.0.21 (8.0.2125.47513), X64 RyuJIT AVX2
  DefaultJob : .NET 8.0.21 (8.0.2125.47513), X64 RyuJIT AVX2


```
| Method            | Mean     | Error    | StdDev   | Gen0   | Allocated |
|------------------ |---------:|---------:|---------:|-------:|----------:|
| ComputeBestMove_X | 25.10 μs | 0.208 μs | 0.162 μs | 1.4343 |  23.57 KB |
| ComputeBestMove_O | 25.23 μs | 0.101 μs | 0.094 μs | 1.4343 |  23.48 KB |
