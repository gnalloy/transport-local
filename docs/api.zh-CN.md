# API 参考

[English](api.md) | [文档索引](README.zh-CN.md)

本清单由本仓库 package 的 `go doc -short` 生成，用于快速查看公共面。精确语义以源码和测试为准。

## 包

### `gnalloy.org/transport-local`

包名：`local`

```text
var ErrAddressInUse = errors.New("gnalloy/transport/local: address already in use") ...
type AllocatorFactory func(loop *transport.EventLoop) (buffer.Allocator, error)
type Config struct{ ... }
    func DefaultConfig() Config
type Server struct{ ... }
type Transport struct{ ... }
    func NewTransport(cfg Config) *Transport
```
