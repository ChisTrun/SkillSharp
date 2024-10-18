# SkillSharp

# Dự án Tổng - Quản lý các Repository con bằng Git Submodules

## Giới thiệu

Đây là repository tổng, nơi tập trung các repository con phục vụ cho các phần khác nhau của dự án. Chúng tôi sử dụng Git submodules để quản lý các repository con này, giúp duy trì cấu trúc gọn gàng và dễ dàng quản lý.

## Cách thức hoạt động

Thay vì chứa toàn bộ mã nguồn trong một repository duy nhất,chúng ta chia nhỏ dự án thành các phần độc lập được quản lý qua các repository con. Điều này giúp dễ dàng phát triển, bảo trì và cập nhật riêng lẻ từng phần mà không làm ảnh hưởng tới các phần khác.

Các submodules sẽ được thêm vào trong repository này, mỗi submodule tương ứng với một phần của dự án.

## Cài đặt

Để clone dự án và tất cả các submodules, sử dụng lệnh sau:

```bash
git clone --recurse-submodules <url-repo-chinh>

```bash
git submodule add <repository-url> <path-to-folder> 
