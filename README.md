# Project Name
Performance Test K6

This is a example project, showing the use of K6 in performance tests.

## Running the Tests

To run some test, use the following command:

```bash
k6 run filename.js
```

To run some test in cloud, use:

```bash
k6 cloud filename.js
```

To run some test locally, but with results on cloud, use:
```bash
k6 run --out cloud filename.js
```