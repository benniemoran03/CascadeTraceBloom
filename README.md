# CascadeTraceBloom

CascadeTraceBloom filters high-velocity logs using a cascade of bloom filters, catching known patterns and flagging unseen or rare traces.

## Features
- Multi-stage bloom filter chain.
- Pluggable pattern definitions.
- Fast false-positive rejection.
- Works with Kafka, files, or stdin streams.

## Usage
```bash
git clone https://github.com/your-org/CascadeTraceBloom.git
cd CascadeTraceBloom
python cascade/stream_processor.py logs/service.log
