# Metal probe binaries

Precompiled macOS arm64 host, Metal library and frozen binary inputs. Experimental source is maintained separately.

CI verifies SHA256, runs the supplied binaries on macos-15 and uploads measurements. It does not compile or fetch experimental source. Pushes run a 128-query smoke check; manual runs select the pilot or a full matrix.

Binaries omit debug information and embedded source, but can still be reverse engineered. No physical GPU core or cache-level identity is implied.
