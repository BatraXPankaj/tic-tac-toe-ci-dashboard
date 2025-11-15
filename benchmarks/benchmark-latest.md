```

BenchmarkDotNet v0.13.12, Ubuntu 24.04.3 LTS (Noble Numbat)
AMD EPYC 7763, 1 CPU, 2 logical cores and 1 physical core
.NET SDK 10.0.100
  [Host]     : .NET 8.0.22 (8.0.2225.52707), X64 RyuJIT AVX2
  DefaultJob : .NET 8.0.22 (8.0.2225.52707), X64 RyuJIT AVX2


```
| Method            | Mean     | Error    | StdDev   | Gen0   | Allocated |
|------------------ |---------:|---------:|---------:|-------:|----------:|
| ComputeBestMove_X | 25.28 μs | 0.142 μs | 0.111 μs | 1.4343 |  23.57 KB |
| ComputeBestMove_O | 24.86 μs | 0.173 μs | 0.162 μs | 1.4343 |  23.48 KB |
