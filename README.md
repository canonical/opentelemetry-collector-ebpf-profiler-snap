<h1 align="center">
  <img src="https://github.com/user-attachments/assets/977000e9-0f8c-466d-8388-719b2877c425" alt="[Project]" width=50%>
  <br />
  OpenTelemetry Collector eBPF Profiler
</h1>



<p align="center"><b>This is the snap for <a href="https://github.com/open-telemetry/opentelemetry-ebpf-profiler">OpenTelemetry eBPF Profiler</a></b>, <i>An OpenTelemetry Collector distribution that is made specifically to be used as a whole-system, cross-language profiler for Linux via eBPF.
</p>



<p align="center">Published for <img src="https://raw.githubusercontent.com/anythingcodes/slack-emoji-for-techies/gh-pages/emoji/tux.png" align="top" width="24" /> with 💝 by The Canonical Observability Team</p>

## Install

    sudo snap install opentelemetry-collector-ebpf-profiler

([Don't have snapd installed?](https://snapcraft.io/docs/core/install))



## Configuration

Once installed, a default configuration file will be created at `/snap/opentelemetry-collector-ebpf-profiler/etc/config.yaml`. The snap will try to use all configuration files under the `/etc/otelcol-ebpf-profiler/config.d` folder, in alphabetical order. If none is present, it will use the default config file.

To write a configuration file to suit you needs, consult the [official documentation](https://opentelemetry.io/docs/collector/).
