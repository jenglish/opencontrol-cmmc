# CMMC controls

[CMMC] controls in [OpenControl] format for use with [Compliance Masonry] and [ssptool]

## Usage

To import this data into a OpenControl project add the following
your `opencontrol.yaml` file:

```yaml
dependencies:
  standards:
    - url: https://github.com/jenglish/opencontrol-cmmc
      revision: master
```

[CMMC]: https://www.acq.osd.mil/cmmc/
[OpenControl]: https://open-control.org/
[Compliance Masonry]: https://github.com/opencontrol/compliance-masonry
[ssptool]: https://github.com/jenglish/ssptool
