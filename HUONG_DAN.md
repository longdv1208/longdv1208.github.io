# Repo `longdv1208.github.io` — trang gốc + app-ads.txt

Thư mục này là NGUỒN của repo GitHub `longdv1208.github.io` (khác repo
`homeway-legal`). GitHub Pages phục vụ nó ở gốc tên miền:

- https://longdv1208.github.io/            → `index.html` (trang nhà phát triển)
- https://longdv1208.github.io/app-ads.txt → AdMob xác minh (BẮT BUỘC ở gốc tên miền)

`.nojekyll`: tắt Jekyll để GitHub phục vụ file nguyên văn.

## Đẩy lên lần đầu
```
cd site-root
git init -b main
git add .
git commit -m "Trang gốc + app-ads.txt"
git remote add origin https://github.com/longdv1208/longdv1208.github.io.git
git push -u origin main
```
(Tạo repo rỗng, công khai, tên ĐÚNG `longdv1208.github.io` trên GitHub trước.)

Settings → Pages → Source: *Deploy from a branch*, Branch `main` / `(root)`.

## Sau đó
- App Store Connect & Google Play Console: ô **Developer website / Marketing URL**
  = `https://longdv1208.github.io`.
- AdMob → Apps → **app-ads.txt**: chờ 1–2 ngày để thành "Verified".
- File này (`HUONG_DAN.md`) cũng được đẩy lên — vô hại; muốn ẩn thì xoá trước khi push.
