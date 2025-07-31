[Prometheus text-based exposition format](https://prometheus.io/docs/instrumenting/exposition_formats/#basic-info) in Sublime syntax.

## Usage

### Used with bat

If you use [bat](https://github.com/sharkdp/bat) as a pager, you can add the syntax support for it:

```bash
cd $(bat --config-dir)/syntaxes
git clone https://github.com/belltoy/prom-sublime-syntax.git
bat cache --build
```
