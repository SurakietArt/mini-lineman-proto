# mini-lineman-proto

Shared `.proto` contracts for the mini-lineman system. One contract source; services pin a
version by git tag.

Status: **skeleton only.** No contracts yet — protos start inside the `mini-lineman` repo and
move here in Phase 2, once the cross-repo pain is felt.

## Toolchain

Pinned by ADR 0001: `protoc` v36.2, `protoc-gen-go` v1.36.12, `protoc-gen-go-grpc` v1.6.2.
This repo owns its own toolchain image because codegen is specific to it.
