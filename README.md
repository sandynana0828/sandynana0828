<div align="center">

<img src="./assets/avatar-round.png" width="172" alt="Portrait" />

<br/><br/>

<h1>Sandy</h1>

<p><strong>Backend &amp; systems engineer.</strong><br/>
Small, dependable services — proven by running them, not by describing them.</p>

<p>
<a href="https://github.com/sandynana0828/reference-implementations">Reference implementations</a> ·
<a href="https://github.com/sandynana0828?tab=repositories">Repositories</a>
</p>

</div>

---

## How I work

| Principle | What it means in practice |
|---|---|
| **Runnable first** | Every project ships with the exact commands and their unedited output. |
| **Constraints in the database** | Integer cents, partial unique indexes for soft deletes, CHECK constraints, rollback-tested transactions. |
| **Honest scope** | Standard library when a dependency isn't needed — plus an explicit list of what is *not* implemented. |

## Selected work

| Repository | What it is | Verification |
|---|---|---|
| [reference-implementations](https://github.com/sandynana0828/reference-implementations) | Dictionary & tag center plus a PostgreSQL ledger reference service | 21 unit tests, 19 HTTP assertions, live `psql` output |
| [chess-ai](https://github.com/sandynana0828/chess-ai) | Full FIDE-rules chess engine in pure Python: α–β search, quiescence, PST eval | perft suite in the repo |
| [mini-search-engine](https://github.com/sandynana0828/mini-search-engine) | Crawler → inverted index → BM25 ranking → snippets | built-in self-test |
| [sqlite-task-queue](https://github.com/sandynana0828/sqlite-task-queue) | Durable queue with atomic claims, leases, backoff and dead-letter | concurrency test in the repo |

Most of them run with `python <file>` — no install step.

## Verification, not adjectives

- [taxonomy-service/VERIFICATION.txt](https://github.com/sandynana0828/reference-implementations/blob/main/taxonomy-service/VERIFICATION.txt) — 21 tests, an end-to-end demo with a fault-injected rollback, and 19 HTTP status checks, saved as raw output
- [postgres-ledger/VERIFICATION.txt](https://github.com/sandynana0828/reference-implementations/blob/main/postgres-ledger/VERIFICATION.txt) — PostgreSQL 16.15 DDL/DML output: cents `CHECK`, `jsonb`, partial unique index

## Stack

`Python` · `PostgreSQL 16` · `SQLAlchemy` · `FastAPI` · `SQLite` · `Git`

---

<sub>All published examples use fictional data. No client or company names appear here.</sub>
