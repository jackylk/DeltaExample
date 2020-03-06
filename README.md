# DeltaExample

An example to test Databricks delta.

### Example test setup

In a 4-core hyperthreaded laptop

Target table: 200000 rows

Each update batch: update 9000 rows, insert 1000 rows, delete 1000 rows

### Test result

start CDC example using delta solution
generating target table...done! 16.02 s
applying change batch1...done! 9.44 s
applying change batch2...done! 7.44 s
applying change batch3...done! 7.22 s
applying change batch4...done! 7.56 s
applying change batch5...done! 8.35 s
applying change batch6...done! 5.85 s
applying change batch7...done! 5.72 s
applying change batch8...done! 5.73 s
applying change batch9...done! 6.85 s
applying change batch10...done! 6.26 s
total update takes 70.42 s
total query takes 1.38 s

