# Maze Game - Epic Game

## Giới thiệu dự án

Dự án "Maze Game" là sản phẩm giữa kỳ lập trình Windows được phát triển bởi nhóm Epic Game. Đây là một game giải đố mê cung với cơ chế điều khiển, xử lý va chạm và trạng thái người chơi.

## Công nghệ sử dụng

- **Ngôn ngữ lập trình**: C/C++
- **Hệ điều hành mục tiêu**: Windows
- **Thư viện đồ họa**: Win32 API / GDI hoặc tương tự (nếu áp dụng)
- **Môi trường phát triển**: Visual Studio hoặc Dev C++

## Đóng góp chính của dự án

- Xây dựng được logic di chuyển trong mê cung và điều khiển người chơi chính xác.
- Thiết kế hệ thống bản đồ mê cung, quản lý trạng thái trò chơi và cập nhật giao diện đồ họa.
- Triển khai xử lý va chạm giữa người chơi và tường mê cung.
- Cải thiện trải nghiệm người dùng bằng điều khiển bàn phím mượt mà và phản hồi trực quan.
- Tổ chức bài toán thành các module rõ ràng để dễ bảo trì, mở rộng và sửa lỗi.

## Cấu trúc bài toán

- **Điều khiển người chơi**: Xử lý sự kiện bàn phím để di chuyển nhân vật.
- **Mê cung**: Lưu trữ bản đồ, kiểm tra vùng đi được và tường chắn.
- **Hiển thị**: Vẽ giao diện game lên cửa sổ Windows.
- **Trạng thái game**: Quản lý điểm, thời gian, và điều kiện chiến thắng/thua.

## Hướng phát triển tiếp theo

- Mở rộng nhiều cấp độ với độ khó tăng dần.
- Thêm menu chính, bảng xếp hạng và âm thanh.
- Tối ưu hiệu suất vẽ đồ họa và quản lý các đối tượng trong game.
- Chuyển sang engine game nhẹ hoặc thư viện đồ họa cao cấp hơn nếu cần.

## Hướng dẫn chạy

1. Mở Visual Studio hoặc Dev C++.
2. Tải toàn bộ thư mục dự án `LTWin_EpicGame_MazeGame` vào môi trường phát triển.
3. Mở file dự án hoặc giải pháp (.sln/.vcxproj) nếu có.
4. Biên dịch (Build) dự án trên cấu hình `Debug` hoặc `Release`.
5. Chạy chương trình (Start/Run) để mở cửa sổ game trên Windows.

> Nếu dự án chưa có file giải pháp, mở file nguồn chính (`main.cpp`, `MazeGame.cpp`, hoặc tương tự), tạo một project C/C++ mới và thêm các file nguồn vào project.

## Thành viên nhóm

- Trần Quốc Khánh
- Hà Thái Khánh
- Nguyễn Thành Trung
- Hứa Thiên Trường
- Hoàng Tấn Dũng
