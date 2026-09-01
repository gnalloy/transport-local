# API Reference

[简体中文](api.zh-CN.md) | [Docs Index](README.md)

This inventory is generated from `go doc -short` for the packages in this repository. It is a quick public-surface map; source files and tests remain the authority for exact semantics.

## Packages

### `gnalloy.org/transport-local`

Package name: `local`

```text
var ErrAddressInUse = errors.New("gnalloy/transport/local: address already in use") ...
type AllocatorFactory func(loop *transport.EventLoop) (buffer.Allocator, error)
type Config struct{ ... }
    func DefaultConfig() Config
type Server struct{ ... }
type Transport struct{ ... }
    func NewTransport(cfg Config) *Transport
```
