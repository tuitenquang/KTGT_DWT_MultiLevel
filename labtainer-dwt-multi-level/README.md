# Labtainer DWT Multi-Level Labs

Thu muc nay chua 5 file IModule `.tar` cho Labtainers ve chu de giau tin anh tren mien tan so bang multi-level Haar DWT.

## Danh sach lab

- `dwtml-1-basics.tar`: phan ra va tai tao anh voi DWT nhieu muc.
- `dwtml-2-embed.tar`: nhung va trich thong diep trong subband DWT.
- `dwtml-3-robust.tar`: so sanh do ben cua cac subband sau nhieu/luong tu hoa.
- `dwtml-4-capacity.tar`: do capacity, payload size va PSNR.
- `dwtml-5-adaptive.tar`: giau tin nhieu muc co khoa.

## Cach import trong VM Labtainer

Chay truc tiep cac URL GitHub sau trong VM Labtainer:

```bash
imodule https://raw.githubusercontent.com/tuitenquang/KTGT_DWT_MultiLevel/1b9e04d/labtainer-dwt-multi-level/dwtml-1-basics.tar
imodule https://raw.githubusercontent.com/tuitenquang/KTGT_DWT_MultiLevel/1b9e04d/labtainer-dwt-multi-level/dwtml-2-embed.tar
imodule https://raw.githubusercontent.com/tuitenquang/KTGT_DWT_MultiLevel/1b9e04d/labtainer-dwt-multi-level/dwtml-3-robust.tar
imodule https://raw.githubusercontent.com/tuitenquang/KTGT_DWT_MultiLevel/1b9e04d/labtainer-dwt-multi-level/dwtml-4-capacity.tar
imodule https://raw.githubusercontent.com/tuitenquang/KTGT_DWT_MultiLevel/1b9e04d/labtainer-dwt-multi-level/dwtml-5-adaptive.tar
```

Sau do chay tung lab:

```bash
rebuild -L -f -b dwtml-1-basics
labtainer dwtml-1-basics

rebuild -L -f -b dwtml-2-embed
labtainer dwtml-2-embed

rebuild -L -f -b dwtml-3-robust
labtainer dwtml-3-robust

rebuild -L -f -b dwtml-4-capacity
labtainer dwtml-4-capacity

rebuild -L -f -b dwtml-5-adaptive
labtainer dwtml-5-adaptive
```

Giai thich: cac lab nay la lab tu tao, chua co Docker image public tren DockerHub. Lenh `rebuild -L -f -b <ten-lab>` build image local tu Dockerfile cua lab va khong query DockerHub. Sau khi build thanh cong, dung `labtainer <ten-lab>` de chay lab. Neu muon build va chay ngay trong mot lenh, co the bo `-b`. Cac URL o tren dung commit `1b9e04d` da test thanh cong de tranh cache cua GitHub raw tren nhanh `main`.

Khi terminal lab mo ra, sinh vien se duoc yeu cau nhap ma sinh vien. Sau khi lam xong cac lenh bat buoc trong bai, chay lenh sau tu terminal host de tu kiem tra:

```bash
checkwork
```

Moi tieu chi hoan thanh se hien `Y`. Neu tieu chi nao khong co `Y`, sinh vien can quay lai chay dung buoc tuong ung trong bai lab.
