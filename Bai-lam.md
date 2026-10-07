# Đọc lại Burndown Chart Sprint đặt xe ghép

## Phần 1 - Phân tích

Đường lý tưởng bắt đầu ở 40 Story Points và giảm 4 điểm mỗi ngày: **ngày 0: 40; ngày 1: 36; ngày 2: 32; ngày 3: 28; ngày 4: 24; ngày 5: 20; ngày 6: 16; ngày 7: 12; ngày 8: 8; ngày 9: 4; ngày 10: 0**.

| Nhận định | Đúng/Sai | Dẫn chứng số liệu (so với đường lý tưởng tại ngày cụ thể) | Cách hiểu đúng |
|---|---|---|---|
| N1. Trục dọc thể hiện số giờ làm việc đội đã dùng | Sai | Đề bài ghi khối lượng còn lại theo Story Points; ví dụ ngày 0 còn 40 SP và ngày 10 còn 20 SP. | Trục Y thể hiện khối lượng công việc **còn lại** (Story Points), không phải số giờ đã dùng. |
| N2. Đường lý tưởng giảm đều 4 điểm mỗi ngày và chạm 0 vào ngày 10 | Đúng | Tổng 40 SP trong 10 ngày: ngày 1 là 36 SP, ngày 5 là 20 SP, ngày 10 là 0 SP. | Đường lý tưởng giảm tuyến tính 4 SP mỗi ngày và kết thúc ở 0 vào ngày cuối Sprint. |
| N3. Từ ngày 2 đến ngày 5, đường thực tế đi ngang, chứng tỏ đội đang làm việc rất ổn định | Sai | Thực tế giữ ở 36 SP trong các ngày 2–5, trong khi lý tưởng giảm từ 32 SP (ngày 2) xuống 20 SP (ngày 5); độ trễ tăng từ 4 lên 16 SP. | Đường ngang cho thấy lượng công việc còn lại không giảm; đây là dấu hiệu cần kiểm tra tiến độ và tìm trở ngại, không phải bằng chứng đội đang tiến triển ổn định. |
| N4. Suốt Sprint, đường thực tế luôn nằm dưới đường lý tưởng nên đội nhanh hơn kế hoạch | Sai | Ngày 1: thực tế 38 SP so với lý tưởng 36 SP; ngày 5: 36 so với 20; ngày 10: 20 so với 0. Thực tế bằng lý tưởng ở ngày 0 và cao hơn lý tưởng ở mọi ngày 1–10. | Đội chậm hơn kế hoạch từ ngày 1 và kết thúc Sprint còn 20 SP, nên chưa hoàn thành toàn bộ 40 SP đã cam kết. |

## Phần 2 - Vá lỗi

- **Hiện tượng bị chặn/không giảm khối lượng còn lại (ngày 2–5):** Developers nêu trở ngại và cập nhật công việc trong Daily Scrum; Scrum Master Lan cùng đội điều tra nguyên nhân và gỡ trở ngại ngay khi đường thực tế bắt đầu đi ngang (nhận thấy ở ngày 3), không chờ đến cuối Sprint.
- **Tiến độ chậm hơn kế hoạch (từ ngày 1, tiếp diễn đến cuối Sprint):** Developers và Scrum Master đối chiếu burndown với đường lý tưởng mỗi ngày, rà soát kế hoạch và dự báo phần việc còn lại; Lan phối hợp Product Owner Đức để thảo luận điều chỉnh phạm vi nếu cần mà không hạ tiêu chuẩn chất lượng, bắt đầu ngay từ ngày 1 khi thực tế còn 38 SP so với mức lý tưởng 36 SP.

