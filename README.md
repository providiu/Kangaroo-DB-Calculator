## DB Calculator

Interactive browser tool for planning tame phase database generation.

Open `calculator.html` in any browser — no server needed.

### Features

- Estimate RAM (hash table), output file sizes, and generation time
- Compare quality against the default DB 75 baseline
- Calculate extend partitions and solve time for any target key size
- Side-by-side comparison table across common DB configurations
- Auto-generated commands with click-to-copy

### Parameters

| Input | Description |
|-------|------------|
| Range | Bit range for the database (e.g. 76-77) |
| Quality | Density relative to DB 75 default |
| Global bits | Distinguished point mask size (-g) |
| Workers/Batch | Parallelism settings (-w, -b) |
| Speed | Your measured generation speed in M steps/s |
| Extend bits | Target key size for solve time estimation |

### Usage

1. Enter your system parameters (workers, speed from a test run)
2. Adjust range and quality to fit your available RAM
3. Check the extend section for estimated solve times
4. Copy the generated command and run it
