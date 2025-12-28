# Hệ Thống Quản Lý Ký Túc Xá

## Giới thiệu
Hệ thống Quản Lý Ký Túc Xá là một ứng dụng Windows Forms được phát triển bằng C# và SQL Server, giúp tự động hóa và quản lý hiệu quả các hoạt động của ký túc xá. Hệ thống cung cấp các công cụ quản lý toàn diện cho ban quản lý ký túc xá, nhân viên và sinh viên.

## Tính năng chính

### 1. Quản lý Sinh viên
- Thêm, sửa, xóa thông tin sinh viên
- Quản lý thông tin cá nhân (họ tên, ngày sinh, giới tính, email, địa chỉ)
- Theo dõi việc phân phòng
- Quản lý chính sách ưu tiên

### 2. Quản lý Phòng & Khu
- Phân chia và quản lý khu phòng (Thêm, sửa, xem thông tin)
- Quản lý các loại phòng và thông tin chi tiết
- Theo dõi tình trạng phòng (trống/đã có người ở)
- Quản lý giá phòng

### 3. Quản lý Hợp đồng
- Tạo và quản lý hợp đồng ký túc xá
- Theo dõi thời hạn hợp đồng
- Quản lý gia hạn hợp đồng

### 4. Quản lý Hóa đơn
- Tạo và quản lý hóa đơn thanh toán
- Theo dõi các khoản phí phát sinh (điện, nước, v.v.)
- Quản lý lịch sử thanh toán

### 5. Quản lý Nhân viên
- Quản lý thông tin nhân viên
- Phân quyền người dùng
- Theo dõi công việc của nhân viên

### 6. Hệ thống Đăng nhập và Phân quyền
- Xác thực người dùng
- Phân quyền theo vai trò (sinh viên, nhân viên, quản lý)
- Bảo mật thông tin tài khoản

## Cài đặt

1. Clone repository:
```bash
git clone https://github.com/duy-debug/dormitory_management_system.git
```

2. Cài đặt SQL Server và tạo database:
- Tạo database mới tên "QLKTX"
- Chạy script SQL trong thư mục `Db/65.CNTT-1_Nhom2_QLKTX.sql` để tạo bảng và dữ liệu mẫu.

3. Cấu hình connection string:
- Mở file `DatabaseHelper.cs`
- Cập nhật connection string phù hợp với cấu hình SQL Server của bạn.

4. Build và chạy project:
- Mở solution `QuanLyKyTucXa.sln` trong Visual Studio
- Build solution
- Chạy ứng dụng

## Cấu trúc project

```
QuanLyKyTucXa/
├── UI/                    # Giao diện người dùng (Forms)
├── Models/               # Các model dữ liệu
├── Db/                   # Xử lý database và script SQL
├── Resources/            # Tài nguyên (hình ảnh, icons)
├── Properties/           # Cấu hình project
└── bin/ obj/             # Thư mục build
```

## Công nghệ sử dụng

- Ngôn ngữ: C#
- Framework: .NET Framework (Windows Forms)
- Database: SQL Server
- Thư viện: ADO.NET

## Đội ngũ phát triển

- Trần Mai Ngọc Duy (Leader)
- Trần Minh Hoàng
- Nguyễn Lê Thùy Linh
- Ngô Văn Lực

## Đóng góp

Mọi đóng góp đều được hoan nghênh! Vui lòng tạo issue hoặc pull request để đóng góp.

## Lời cảm ơn

Cảm ơn tất cả thành viên đã nỗ lực hoàn thành dự án này.
