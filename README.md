# [BTTH] Cẩm nang sử dụng AI hiệu quả cho tân sinh viên

## Phần 1: Cách AI đoán từ
- AI không suy nghĩ mà hoạt động dựa trên xác suất thống kê để dự đoán từ tiếp theo
## Phần 2: 3 cách nhận diện ảo giác của AI.
- Đối chiếu, kiểm tra số liệu với tài liệu chuẩn
- Yêu cầu AI trình bày các bước lập luận
- Đưa tài liệu gốc vào prompt để Ai bám sát
## Phần 3: Cấu trúc prompt mẫu tối ưu bằng khung CREATE.
- C - Context (Bối cảnh & Vai trò): Bạn là giảng viên lập trình.
- R - Request (Yêu cầu cốt lõi): Hãy tìm lỗi và sửa đoạn code Python bị lỗi vòng lặp dưới đây.
- E - Explanation (Giải thích & Ràng buộc)): Đưa ra lỗi thực tế của sinh viên.
- A - Action (Các bước hành động): Phân tích nguyên nhân, giải thích chi tiết cách khắc phục.
- T - Tone (Giọng điệu văn phong): Ân cần, từ ngữ đơn giản, dễ hiểu với sinh viên năm nhất 
- E - Extras (Định dạng đầu ra & Bổ sung): Chia rõ khối nguồn và kèm theo lời khuyên thực tế

## Yêu cầu đầu ra
- Sơ đồ các bước xâu chuỗi prompt
    - Giải thích bản chất LLM
    - Liệt kê cách chống ảo giác
    - hiết kế mẫu Prompt khung CREATE]
- Prompt 1:
    - Đóng vai giảng viên CNTT, giải thích ngắn gọn cách LLM dự đoán từ và giới hạn Context Window cho tân sinh viên dưới dạng gạch đầu dòng.
- Prompt 2:
    - Dựa trên kiến thức trên, hãy liệt kê 3 cách thực tế giúp sinh viên nhận diện và phòng tránh hiện tượng ảo giác (Hallucination) của AI khi viết code.
- Prompt 3:
    - Hãy thiết kế một mẫu prompt chuẩn theo khung CREATE (Context, Request, Explanation, Action, Tone, Extras) để hướng dẫn sinh viên nhờ AI fix lỗi code Python an toàn.

