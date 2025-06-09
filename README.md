# Dự Án Dự Báo Giá Cổ Phiếu

## Mô Tả
Dự án này sử dụng các chỉ số kỹ thuật và các mô hình học máy như OLS (Ordinary Least Squares), LSTM (Long Short-Term Memory), và TimeGPT để dự báo giá cổ phiếu trong tương lai. Các chỉ số kỹ thuật như MA (Moving Average), RSI (Relative Strength Index), MACD (Moving Average Convergence Divergence), StochRSI, Ichimoku Cloud, CCI (Commodity Channel Index), MFI (Money Flow Index), và ADX/DMI được tính toán và sử dụng làm đặc trưng cho các mô hình dự báo.

## Các Chỉ Số Kỹ Thuật
Dự án sử dụng các chỉ số kỹ thuật phổ biến để phân tích thị trường chứng khoán:
- **MA (Moving Average)**: Đường trung bình động.
- **RSI (Relative Strength Index)**: Chỉ số sức mạnh tương đối.
- **MACD (Moving Average Convergence Divergence)**: Sự hội tụ/phân kỳ của đường trung bình động.

Các chỉ số này giúp phân tích sức mạnh và xu hướng của thị trường cổ phiếu.

## Các Mô Hình Dự Báo

1. **OLS (Ordinary Least Squares)**:
   - OLS được sử dụng để tìm mối quan hệ tuyến tính giữa các chỉ số kỹ thuật và giá cổ phiếu. Đây là một mô hình đơn giản nhưng hiệu quả để bắt đầu phân tích dữ liệu.

2. **LSTM (Long Short-Term Memory)**:
   - LSTM là một loại mạng nơ-ron hồi tiếp (RNN) được sử dụng để dự báo chuỗi thời gian. Mô hình này có thể học được các mối quan hệ dài hạn trong dữ liệu, giúp dự báo giá cổ phiếu dựa trên các dữ liệu quá khứ.

3. **TimeGPT**:
   - TimeGPT là một mô hình tiên tiến sử dụng GPT để dự báo chuỗi thời gian. Mô hình này có khả năng học các mẫu và mối quan hệ phức tạp trong dữ liệu tài chính và đưa ra dự báo chính xác về giá cổ phiếu.


