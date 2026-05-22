# Labtainer DWT Multi-Level Labs

Thu muc nay chua 5 file IModule `.tar` cho Labtainers ve chu de giau tin anh tren mien tan so bang multi-level Haar DWT.

## Danh sach lab

- `dwtml-1-basics.tar`: phan ra va tai tao anh voi DWT nhieu muc. Huong dan: [`docx/dwtml-1-basics.docx`](docx/dwtml-1-basics.docx)
- `dwtml-2-embed.tar`: nhung va trich thong diep trong subband DWT. Huong dan: [`docx/dwtml-2-embed.docx`](docx/dwtml-2-embed.docx)
- `dwtml-3-robust.tar`: so sanh do ben cua cac subband sau nhieu/luong tu hoa. Huong dan: [`docx/dwtml-3-robust.docx`](docx/dwtml-3-robust.docx)
- `dwtml-4-capacity.tar`: do capacity, payload size va PSNR. Huong dan: [`docx/dwtml-4-capacity.docx`](docx/dwtml-4-capacity.docx)
- `dwtml-5-adaptive.tar`: giau tin nhieu muc co khoa. Huong dan: [`docx/dwtml-5-adaptive.docx`](docx/dwtml-5-adaptive.docx)

## File huong dan DOCX

Moi file `.docx` trong thu muc `docx/` da gom du:

- URL `imodule` truc tiep tu GitHub.
- Lenh khoi dong lab.
- Buoc nhap ma sinh vien khi bat dau.
- Cac task can chay trong container.
- Bang tieu chi `checkwork` va cach sua khi mot tieu chi chua hien `Y`.

## Cach import trong VM Labtainer

Chay truc tiep cac URL GitHub sau trong VM Labtainer:

```bash
imodule https://raw.githubusercontent.com/tuitenquang/KTGT_DWT_MultiLevel/main/labtainer-dwt-multi-level/dwtml-1-basics.tar
imodule https://raw.githubusercontent.com/tuitenquang/KTGT_DWT_MultiLevel/main/labtainer-dwt-multi-level/dwtml-2-embed.tar
imodule https://raw.githubusercontent.com/tuitenquang/KTGT_DWT_MultiLevel/main/labtainer-dwt-multi-level/dwtml-3-robust.tar
imodule https://raw.githubusercontent.com/tuitenquang/KTGT_DWT_MultiLevel/main/labtainer-dwt-multi-level/dwtml-4-capacity.tar
imodule https://raw.githubusercontent.com/tuitenquang/KTGT_DWT_MultiLevel/main/labtainer-dwt-multi-level/dwtml-5-adaptive.tar
```

Sau do chay tung lab:

```bash
labtainer dwtml-1-basics
labtainer dwtml-2-embed
labtainer dwtml-3-robust
labtainer dwtml-4-capacity
labtainer dwtml-5-adaptive
```

Khi terminal lab mo ra, sinh vien se duoc yeu cau nhap ma sinh vien. Sau khi lam xong cac lenh bat buoc trong bai, chay lenh sau tu terminal host de tu kiem tra:

```bash
checkwork
```

Moi tieu chi hoan thanh se hien `Y`. Neu tieu chi nao khong co `Y`, sinh vien can quay lai chay dung buoc tuong ung trong bai lab.
