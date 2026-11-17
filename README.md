I am a Staff Software Engineer at [Yandex Cloud](https://yandex.cloud) and a Rust enthusiast.

I contribute to [Apache Arrow](https://arrow.apache.org/).

I work on [Yandex Data Transfer](https://yandex.cloud/en/services/data-transfer) / [Transferia](https://github.com/transferia/transferia), building systems for database replication and batch and streaming data ingestion. My work includes CDC, distributed snapshots, data transformations, and parsers based on formal grammars and finite-state machines. I implemented real-time PostgreSQL → ClickHouse replication and exactly-once snapshot delivery to ClickHouse.

I speak about [change data capture](https://www.youtube.com/watch?v=-1yuwfe7b6I), [schema registries](https://smartdataconf.ru/archive/2024/talks/20005463-schema-registry-ultimate-guide/), and [lakehouse ingestion](https://yandex.cloud/ru-kz/events/1463).

Previously, I worked on Logfeller, a system similar to [Netflix's Psyberg](https://netflixtechblog.com/1-streamlining-membership-data-engineering-at-netflix-with-psyberg-f68830617dd1), connecting Logbroker (Yandex's Kafka-like platform) to [YTsaurus](https://ytsaurus.tech) (Yandex's storage and MapReduce platform).

At [Doctor Web](https://www.drweb.com), an antivirus vendor, I started in the virus lab as a malware analyst and reverse engineer, then built:

- Search engines: binary-content search and nearest-neighbor search using Levenshtein distance.
- Malware detection: a pattern recognition engine implementing my method based on n-gram nearest neighbors.
- dr_yara: a distributed system for [YARA](https://github.com/VirusTotal/yara) scanning and automated analysis with Python scripting, processing 3–4 TB/day. Its output was indexed for binary-content search across tens of petabytes.
- Workflow scheduler: a high-performance C++ engine for executing DAGs, with task dispatch and execution timeouts.

I studied Information Systems and Technologies at [ITMO University](https://itmo.ru). For my graduation thesis, I built a C++ search engine for binary data. It entered production, replacing hours-long scans of clean files with sub-second queries for antivirus signature validation.
