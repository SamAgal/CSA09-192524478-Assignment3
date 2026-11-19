# CSA09 - Java Programming: Assignment 3 (CO3 & CO4)

- **Student Name:** J. Sam Agal
- **Register Number:** 192524478
- **Course:** CSA09 — Java Programming (SIMATS Engineering)
- **Repository:** https://github.com/SamAgal/CSA09-192524478-Assignment3
- **Java Target:** Java 17+ / 21 (`javac` / `java`)

## Repository Structure
- `Q1/BankATMSimulation.java` & `output.txt` — ATM withdrawal failure classification (`Checked` vs `Unchecked`), multi-catch blocks, and guaranteed `finally` cleanup.
- `Q2/StorageDemo.java` & `output.txt` — Custom exception hierarchy (`ExamException`, `SubmissionStorageException`) with exception chaining (`TODO 1` completed) across Controller, Service, and Storage layers.
- `Q3/DailySalesReport.java` & `output.txt` — Resource leak debugging (`try-catch-finally` vs `try-with-resources`) with handle leak counts.
- `Q4/AnswerScriptScanner.java` & `output.txt` — Parallel answer-script scanning comparing `extends Thread` vs `implements Runnable`, lifecycle states, `join()`, and daemon behavior.
- `Q5/SeatBooking.java` & `output.txt` — Cinema seat booking race condition reproduction and atomic fix (`TODO 1` completed) with `synchronized` method, block, and `AtomicBoolean` analysis.
- `Q6/TokenCounter.java` & `output.txt` — Bounded mess token producer-consumer (`put()`/`take()` with `wait()`/`notifyAll()`, `TODO 1` & `TODO 2` completed) and deadlock-free hostel wallet transfers via lock ordering.
- `Q7/SemesterResultProcessor.java` & `output.txt` — Fault-tolerant concurrent semester result processor (`ExecutorService`, `Callable`, `Future`, `ConcurrentHashMap`, `AtomicInteger`) handling missing/corrupt files across 1, 2, 4, and 8 threads.
- `evidence_q5_concurrency.png`, `evidence_q3_q6_resources_threads.png`, & `evidence_q7_threadpool_scaling.png` — Experimental evidence charts.

## Compile & Run Instructions
```bash
javac Q1/BankATMSimulation.java && java -cp Q1 BankATMSimulation
javac Q2/StorageDemo.java && java -cp Q2 StorageDemo
javac Q3/DailySalesReport.java && java -cp Q3 DailySalesReport
javac Q4/AnswerScriptScanner.java && java -cp Q4 AnswerScriptScanner
javac Q5/SeatBooking.java && java -cp Q5 SeatBooking
javac Q6/TokenCounter.java && java -cp Q6 TokenCounter
javac Q7/SemesterResultProcessor.java && java -cp Q7 SemesterResultProcessor
```
