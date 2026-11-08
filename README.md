# 1. Bình luận nên ưu tiên đọc trên GitHub Issues

Ưu tiên các bình luận có nhiều reaction tích cực như Thumbs Up (👍), Hearts (❤️), Hooray (🎉). Số reaction cao nghĩa là nhiều người cùng gặp lỗi đã thử cách đó và xác nhận dùng được, nên đáng tin hơn một bình luận không ai phản hồi.

Ngoài ra nên chú ý:

Bình luận của maintainer (người bảo trì dự án) hoặc người có nhãn Member/Collaborator, vì họ hiểu rõ nguyên nhân lỗi nhất. Trong ảnh đề bài, maintainer đã xác nhận đây là regression của bản v0.15.2.
Bình luận được nhiều người trả lời lại kiểu "cách này chạy được trên máy mình".
Bình luận nêu rõ phiên bản, hệ điều hành và các bước làm, khớp với môi trường của mình.

Lời khuyên "xóa đi cài lại" không có reaction hay bằng chứng thì chỉ nên coi là phương án thử sau cùng.

# 2. Workaround là gì và vì sao không nên chờ bản chính thức

Workaround là giải pháp tạm thời để vượt qua lỗi và tiếp tục làm việc mà chưa sửa tận gốc lỗi trong mã nguồn. Trong trường hợp này, ví dụ phổ biến là quay về bản cũ ổn định (cài lại v0.14.0, hoặc ghim phiên bản bằng pip install ten-thu-vien==0.14.0), hoặc dùng một đoạn mã vá, một biến cấu hình mà cộng đồng đã kiểm chứng.

Không nên chờ bản cập nhật chính thức vì:

Issue vẫn ở trạng thái OPEN, không biết khi nào bản sửa lỗi được phát hành, có thể vài ngày hoặc vài tuần.
Công việc, bài tập hoặc dự án đang chạy sẽ bị trễ tiến độ nếu ngồi chờ.
Workaround cho phép làm tiếp ngay, và khi có bản vá chính thức chỉ cần nâng cấp lại.

Lưu ý khi dùng workaround: ghi chú rằng đây là giải pháp tạm, kiểm tra kỹ đoạn mã của người lạ trước khi chạy, và theo dõi issue để cập nhật khi có bản sửa.