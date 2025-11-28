```

BenchmarkDotNet v0.13.12, Ubuntu 24.04.3 LTS (Noble Numbat)
AMD EPYC 7763, 1 CPU, 2 logical cores and 1 physical core
.NET SDK 10.0.100
  [Host]     : .NET 8.0.22 (8.0.2225.52707), X64 RyuJIT AVX2
  DefaultJob : .NET 8.0.22 (8.0.2225.52707), X64 RyuJIT AVX2


```
| Method            | Mean     | Error    | StdDev   | Gen0   | Allocated |
|------------------ |---------:|---------:|---------:|-------:|----------:|
| ComputeBestMove_X | 24.87 μs | 0.189 μs | 0.158 μs | 1.4343 |  23.57 KB |
| ComputeBestMove_O | 24.96 μs | 0.153 μs | 0.135 μs | 1.4343 |  23.48 KB |
