# URL Shortener Notes

- Considered ZooKeeper for ID generation but overkill for v1.
- Base62 math: 62^7 = ~3.5T IDs, enough for years.
- Q: How to handle expired URLs? Maybe TTL in Redis.