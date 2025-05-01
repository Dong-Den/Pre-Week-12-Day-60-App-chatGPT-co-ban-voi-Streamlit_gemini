# ChatGPT Demo App

Ứng dụng đơn giản sử dụng Streamlit để tương tác với các model GPT-4o và GPT-4o-mini của OpenAI.

## Tính năng

- Giao diện chat thân thiện
- Lựa chọn giữa mô hình GPT-4o và GPT-4o-mini
- Nhập OpenAI API key an toàn
- Lưu lịch sử trò chuyện trong phiên làm việc
- Xóa lịch sử trò chuyện dễ dàng

## Cài đặt

1. Cài đặt các thư viện cần thiết:

```bash
pip install -r requirements.txt
```

2. Chạy ứng dụng:

```bash
streamlit run app.py
```

## Cách sử dụng

1. Nhập OpenAI API key của bạn vào khung bên sidebar
2. Chọn model mong muốn (GPT-4o hoặc GPT-4o-mini)
3. Nhập tin nhắn vào khung chat ở phía dưới
4. Nhấn Enter để gửi tin nhắn và nhận phản hồi từ GPT

## Lưu ý

- Bạn cần có OpenAI API key để sử dụng ứng dụng này
- API key của bạn được nhập dưới dạng mật khẩu và không được lưu trữ đâu cả
- GPT-4o là mô hình mạnh nhất nhưng có thể chậm hơn và tốn token hơn
- GPT-4o-mini là phiên bản nhỏ hơn, nhanh hơn và ít tốn kém hơn 