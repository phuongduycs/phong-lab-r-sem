# Phòng Lab R–SEM

**Người phát triển: Nguyễn Bình Phương Duy**

Nền tảng tự học phân tích dữ liệu khảo sát bằng R cho sinh viên, từ cài đặt R đến viết chương kết quả, trọng tâm mô hình cấu trúc tuyến tính (SEM).

**Mở Phòng Lab:** trang web của kho này (GitHub Pages), hoặc tải `index.html` về và mở bằng Chrome/Edge.

## Nội dung: 20 bài

| Giai đoạn | Bài |
|---|---|
| 1. Nền tảng R | 1. Cài R, RStudio · 2. Ngôn ngữ R · 3. Nhập dữ liệu |
| 2. Pilot, làm sạch và mô tả | 4. Pilot test bảng hỏi (CVI, khảo sát thử) · 5. Làm sạch · 6. Mô tả, ggplot2 · 7. Kiểm định, hồi quy |
| 3. Thang đo | 8. Cronbach's alpha, omega · 9. EFA |
| 4. Nhánh A: CB-SEM (lavaan) | 10. CFA, WLSMV, CMB · 11. SEM · 12. Trung gian bootstrap · 13. Đa nhóm, bất biến, điều tiết |
| 5. Nhánh B: PLS-SEM (seminr) | 14. Đo lường kết quả · 15. Đo lường cấu tạo · 16. Cấu trúc, PLSpredict · 17. Trung gian, điều tiết · 18. Bậc cao, MICOM, MGA, IPMA · 19. Kiểm tra độ vững |
| 6. Báo cáo | 20. PLSc (cSEM), so sánh ba cách ước lượng, viết chương kết quả |

Công cụ: dựng mô hình sinh mã lavaan/seminr/cSEM, đọc kết quả lavaan và seminr, cỡ mẫu (căn bậc hai nghịch đảo, công suất RMSEA), bảng ngưỡng có nguồn, từ điển lỗi, sổ tay gói, thuật ngữ Anh–Việt, R chạy trực tiếp trên trình duyệt (webR).

## Dữ liệu

Bốn tệp CSV trong kho là **dữ liệu mô phỏng** bằng R (khảo sát ý định mua hàng qua livestream), có cài sẵn lỗi để luyện làm sạch. Không phải dữ liệu thật, chỉ dùng để học.

| Tệp | Nội dung |
|---|---|
| `khao_sat_tho.csv` | 438 phiếu chưa làm sạch (Bài 5) |
| `khao_sat_sach.csv` | 411 phiếu đã làm sạch (từ Bài 6) |
| `pilot_chuyen_gia.csv` | 6 chuyên gia chấm 19 câu nháp (Bài 4) |
| `pilot_khao_sat.csv` | 40 phiếu khảo sát thử (Bài 4) |

Kết quả mẫu trong các bài chạy bằng R 4.6.0 với lavaan 0.7-3, semTools 0.5-9, seminr 2.4.2, cSEM 0.6.1, psych 2.6.3.

## Giấy phép

CC BY-NC 4.0: được chia sẻ, chỉnh sửa cho mục đích phi thương mại, ghi tên tác giả Nguyễn Bình Phương Duy. Xem `LICENSE`.
