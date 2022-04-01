# BEM
- Là tiêu chuẩn đặt tên class khi viết CSS

## Ý nghĩa
- viết tắt của: Block Element Modifier
- Block: Khối
- Element: Thành phần trong khối
- Modifier: Bổ sung ý nghĩa cho `Block` hoặc `Element`

## tại sao phải dùng BEM?
- Mỗi người đặt một kiểu
- Member đặt class trùng nhau, CSS đè lên nhau

## Cú pháp
- .block
- .block__element

- .block--modifier
- .block__element--modifier

## Tính ứng dụng
- Xây dựng layour website
- Xây dựng thành phần trên website

## Ưu điểm
- Tính rõ ràng
- Tái sử dụng dễ dàng
- GIúp cả team làm việc với nhau dễ dàng
- TÍnh module, không lo CSS của class này ảnh hưởng lên CSS của class khác

## nhược điểm
- Tên Class dài
- Một số người cho là xấu

## Khi nào dùng BEM là PHÙ HỢP?
- Dự án nhiều members
- Dự án lơn, số lượng pages nhiều hoặc số lượng các thành phần trên giao diện nhiều

## Thực hành
- Làm button
    - Enabled: Pointer, hover effect
    - Disabled: Arrow, no effect
- Làm message
- Làm 1 thành phần trên website