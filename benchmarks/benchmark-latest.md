```

BenchmarkDotNet v0.13.12, Ubuntu 24.04.3 LTS (Noble Numbat)
Intel Xeon Platinum 8370C CPU 2.80GHz, 1 CPU, 2 logical cores and 1 physical core
.NET SDK 9.0.305
  [Host]     : .NET 8.0.21 (8.0.2125.47513), X64 RyuJIT AVX-512F+CD+BW+DQ+VL+VBMI
  DefaultJob : .NET 8.0.21 (8.0.2125.47513), X64 RyuJIT AVX-512F+CD+BW+DQ+VL+VBMI


```
| Method            | Mean     | Error    | StdDev   | Gen0   | Allocated |
|------------------ |---------:|---------:|---------:|-------:|----------:|
| ComputeBestMove_X | 22.99 μs | 0.303 μs | 0.268 μs | 0.9460 |  23.57 KB |
| ComputeBestMove_O | 23.04 μs | 0.104 μs | 0.092 μs | 0.9460 |  23.48 KB |
