Tests and Coverage
================
15 March, 2023 20:13:04

- <a href="#coverage" id="toc-coverage">Coverage</a>
- <a href="#unit-tests" id="toc-unit-tests">Unit Tests</a>

This output is created by
[covrpage](https://github.com/yonicd/covrpage).

## Coverage

Coverage summary is created using the
[covr](https://github.com/r-lib/covr) package.

| Object                          | Coverage (%) |
|:--------------------------------|:------------:|
| AquaBEHER2                      |    66.67     |
| [R/hello.R](../R/hello.R)       |     0.00     |
| [R/hello2.R](../R/hello2.R)     |     0.00     |
| [R/fun-demo.R](../R/fun-demo.R) |    100.00    |

<br>

## Unit Tests

Unit Test summary is created using the
[testthat](https://github.com/r-lib/testthat) package.

| file                                            |   n |  time | error | failed | skipped | warning |
|:------------------------------------------------|----:|------:|------:|-------:|--------:|--------:|
| [test-AquaBEHER2.R](testthat/test-AquaBEHER2.R) |   1 | 0.053 |     0 |      0 |       0 |       0 |
| [test-demo.R](testthat/test-demo.R)             |   5 | 0.047 |     0 |      0 |       0 |       0 |

<details closed>
<summary>
Show Detailed Test Results
</summary>

| file                                               | context    | test                 | status |   n |  time |
|:---------------------------------------------------|:-----------|:---------------------|:-------|----:|------:|
| [test-AquaBEHER2.R](testthat/test-AquaBEHER2.R#L2) | AquaBEHER2 | multiplication works | PASS   |   1 | 0.053 |
| [test-demo.R](testthat/test-demo.R#L4)             | demo       | Test demo            | PASS   |   5 | 0.047 |

</details>
<details>
<summary>
Session Info
</summary>

| Field    | Value                        |
|:---------|:-----------------------------|
| Version  | R version 4.2.2 (2022-10-31) |
| Platform | x86_64-pc-linux-gnu (64-bit) |
| Running  | Kali GNU/Linux Rolling       |
| Language | en_US                        |
| Timezone | Africa/Addis_Ababa           |

| Package  | Version |
|:---------|:--------|
| testthat | 3.1.6   |
| covr     | 3.6.1   |
| covrpage | 0.2     |

</details>
<!--- Final Status : pass --->
