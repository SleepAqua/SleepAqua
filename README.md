# Louis Tian

Data engineer. Nearly three years building the market-data platform behind a Shanghai
quant asset manager, then independent consulting for private quant clients. Moving to
the Netherlands and looking for sponsored data engineering work.

Most of what I write is about the unglamorous half of data: getting it in, knowing it is
correct, and knowing when it is late. A wrong number before the open is a trading loss,
not a bad chart.

## Selected work

| Repo | What it is |
|---|---|
| [data-quality-gate](https://github.com/SleepAqua/data-quality-gate) | Stops a daily pipeline when a symbol goes stale, a day disappears, a column is renamed or rows duplicate. Exits non-zero so CI gates on it. |
| [tick-rollup](https://github.com/SleepAqua/tick-rollup) | Streams a trade CSV into OHLCV bars, with hard session boundaries and two documented late-tick modes. Measured at ~260k ticks/s on this machine. |
| [rag_im](https://github.com/SleepAqua/rag_im) | Snapshots government visa pages, diffs them section by section, answers questions with citations. Local-first, no API key. |
| [mahjong-mc](https://github.com/SleepAqua/mahjong-mc) | Plays millions of Japanese Mahjong hands to compare strategies. Pure Python, no dependencies, 114 tests. |
| [GapFiller](https://github.com/SleepAqua/GapFiller) | Monte Carlo Yahtzee: hundreds of thousands of games per strategy, reported with standard errors instead of opinions. |
| [PacePulse](https://github.com/SleepAqua/PacePulse) | Offline-first HIIT and strength timer, shipped as a web app and an Android wrapper. |

## What I work with

Python, SQL and Bash; Spark, PySpark, Hive and HDFS; Airflow for orchestration;
pandas and NumPy for analysis; dbt (certified, and putting it to work); LlamaIndex and
ChromaDB for retrieval work. HDF5 and Parquet are where the data actually lives.

## Elsewhere

Email: louis.xiaxu.tian@gmail.com · [LinkedIn](https://linkedin.com/in/xiaxu-tian)
