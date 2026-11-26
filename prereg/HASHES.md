# dLLM-Sim pre-registered predictions: SHA-256 of the frozen prediction files

Each file was written and made read-only before the corresponding measurements were run (registration times below are from the experiment log). This public commit was made on 2026-11-26; predictions registered after that date are committed here before their runs, so the commit timestamp is the public registration time. Only hashes are published; the files are available for artifact evaluation.

| file | sha256 | study | registered (UTC, from the experiment log) |
|---|---|---|---|
| s6_v1.json | `45a4436ab90389bf76d01ceb91d4140f1a6f00d4997ba94dd4beb08f9513950b` | serving-knob selection | 2026-11-24 |
| m3_v1.json | `9d54f13e7506b8c0ee1d190d08584bba099b916ee99ec96d14c920fe159145b0` | expert-parallel layout (MoRI vs allgather-RS) | 2026-11-25 04:50 |
| pd_v1.json | `0d74fdeb7818cfcf8e56b711f1d73a906899a02f04c9a3b86ce931c5903e4669` | prefill/decode disaggregation (1P1D, 2P2D) | 2026-11-25 18:41 |
| lc_v1.json | `939b26a83f081400da804fdfa74a8a668b08d631bf0ed5e43950191e61b30c0f` | long static contexts 256K-1M | 2026-11-26 ~10:58 |
| lc_v2_posthoc.json | `78bb50a1419f7d1dc520bf9ec8891dfed59f6cafd5d029a46f1b2577a9898cad` | long-context post-hoc v2 (held-out sizes) | 2026-11-26 12:25 |
