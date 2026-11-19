- [ ]  Tokio Learning~. Finish It's Major Help Examples.
- [x]  Improve BridgeWise's software performance of Drawing the CrossBeams.
- [ ]   Rustlings: Finish this project. It's is late to finish it now. Quick!
- [ ]  Reading the 1~2 Chapter of the book: RustForRustaceans.
- [ ]  Reading the 1~2 Chapter of the book: Compter System: A Programmer's Persepective.
- [x]  Reading the 1~2 Chapter of the book: A Phisolophy of Software Design. Learnign  MIT Course # 6.1040: Software Design(https://61040.github.io/fa26/)




# Today's Six Most Important Jobs-20261102
- [x]  检查 edge-lens 当前代码，写下已能运行的功能（45 分钟）
- [x]  确定本周唯一要打通的真实 Runtime 场景（30 分钟）
- [ ]  完成这个场景的最小实现，至少记录一次实际运行结果（3 小时）
- [ ]  只学习实现过程中必需的 Tokio API（1 小时）
- [ ]  整理一版英文简历和项目描述（1.5 小时）
- [ ]  复盘：记录实际投入、技术障碍及下一步（30 分钟）

- [ ] Edge-lens：完成 Rust CLI → API → PostgreSQL 的完整流程
- [ ] Edge-lens：加入 Tokio 并发、限流、超时及错误处理
- [ ] Edge-lens：增加测试、性能基准、部署与文档
- [ ] WebCAD：整理现有功能与模块，识别一个主要痛点
- [ ] WebCAD：使用 AI 辅助进行一次小范围重构和性能优化
- [ ] WebCAD：完成回归测试，产生可体验的构建版本


## HyCAD Job 001 — Remote Access完成记录
日期：2026-11-02
目标：让 HyCAD 可以被外部电脑远程访问。
方案：Cloudflare Quick Tunnel + HTTP/2。
结果：其他电脑访问成功，图纸能够正常加载。
问题：QUIC 通道下 WASM 请求反复中断。
解决：强制使用 HTTP/2。
限制：临时 URL、需要本机保持运行、尚无正式访问控制。
结论：公网演示能力已验证，暂不进行正式服务器迁移。
