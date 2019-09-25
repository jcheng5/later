# fiery

<details>

* Version: 1.1.1
* Source code: https://github.com/cran/fiery
* URL: https://github.com/thomasp85/fiery
* BugReports: https://github.com/thomasp85/fiery/issues
* Date/Publication: 2018-10-22 10:00:04 UTC
* Number of recursive dependencies: 40

Run `revdep_details(,"fiery")` for more info

</details>

## Newly broken

*   checking tests ...
    ```
     ERROR
    Running the tests in ‘tests/testthat.R’ failed.
    Last 13 lines of output:
      > library(testthat)
      > library(fiery)
      > 
      > test_check("fiery")
      warning: Cannot stop server from within a non-blocking event cycle from NULL
      ── 1. Failure: life cycle events get fired (@test-Fire.R#188)  ─────────────────
      `{ ... }` did not produce any messages.
      
      
      ══ testthat results  ═══════════════════════════════════════════════════════════
      [ OK: 259 | SKIPPED: 0 | WARNINGS: 2 | FAILED: 1 ]
      1. Failure: life cycle events get fired (@test-Fire.R#188) 
      
      Error: testthat unit tests failed
      Execution halted
    ```

# pool

<details>

* Version: 0.1.4.2
* Source code: https://github.com/cran/pool
* URL: https://github.com/rstudio/pool
* BugReports: https://github.com/rstudio/pool/issues
* Date/Publication: 2019-01-07 20:20:02 UTC
* Number of recursive dependencies: 37

Run `revdep_details(,"pool")` for more info

</details>

## Newly broken

*   checking tests ...
    ```
     ERROR
    Running the tests in ‘tests/testthat.R’ failed.
    Last 13 lines of output:
      > library(DBI)
      > library(pool)
      > 
      > test_check("pool")
      Warning in value[[3L]](cond) :
        Object of class MockPooledObj could not be destroyed properly, but was successfully removed from pool. Error message: Destruction failed...
      ── 1. Failure: destroyObject: throws if onDestroy fails (@test-create-destroy.R#
      `{ ... }` did not produce any warnings.
      
      ══ testthat results  ═══════════════════════════════════════════════════════════
      [ OK: 234 | SKIPPED: 0 | WARNINGS: 0 | FAILED: 1 ]
      1. Failure: destroyObject: throws if onDestroy fails (@test-create-destroy.R#31) 
      
      Error: testthat unit tests failed
      Execution halted
    ```

