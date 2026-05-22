# Labtainer DWT Multi-Level Labs

Thu muc nay chua 5 file IModule `.tar` cho Labtainers ve chu de giau tin anh tren mien tan so bang multi-level Haar DWT.

## Danh sach lab

- `dwtml-1-basics.tar`: phan ra va tai tao anh voi DWT nhieu muc.
- `dwtml-2-embed.tar`: nhung va trich thong diep trong subband DWT.
- `dwtml-3-robust.tar`: so sanh do ben cua cac subband sau nhieu/luong tu hoa.
- `dwtml-4-capacity.tar`: do capacity, payload size va PSNR.
- `dwtml-5-adaptive.tar`: giau tin nhieu muc co khoa.

## Cach import trong VM Labtainer

Copy cac file `.tar` vao VM, vi du `/home/student/imodules/`, roi chay:

```bash
imodule file:///home/student/imodules/dwtml-1-basics.tar
imodule file:///home/student/imodules/dwtml-2-embed.tar
imodule file:///home/student/imodules/dwtml-3-robust.tar
imodule file:///home/student/imodules/dwtml-4-capacity.tar
imodule file:///home/student/imodules/dwtml-5-adaptive.tar
```

Sau do chay tung lab:

```bash
labtainer dwtml-1-basics
labtainer dwtml-2-embed
labtainer dwtml-3-robust
labtainer dwtml-4-capacity
labtainer dwtml-5-adaptive
```
