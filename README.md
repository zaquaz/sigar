# System Information Gatherer And Reporter. 

Fork of hyperic/sigar with some fixes.

## Fixed:

* sigfaulted logger, [#28](https://github.com/hyperic/sigar/pull/28)([commit](https://github.com/kostya/sigar/commit/c2a1af))
* bug undefined symbol: sigar_skip_token, [#60](https://github.com/hyperic/sigar/pull/60)([commit](https://github.com/kostya/sigar/commit/dfe8fe))
* bug detection boot_time on linux (now it works like gnu ps, and fix some issues with process start_time) ([commit](https://github.com/kostya/sigar/commit/660259))
* FreeBSD: don't use v_cache_min/max [#68](https://github.com/hyperic/sigar/pull/68)([commit](https://github.com/kostya/sigar/commit/800076db97bcacb1ba90805d740b4f9a5a1d3cca))


## Installation:

    $ gem install kostya-sigar
