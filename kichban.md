# Kịch bản thuyết trình

## 1. Giới thiệu đề tài

- Bối cảnh
- Khó khăn

## 2. Giải pháp

- Tóm tắt giải pháp
- Công nghệ sử dụng:
  - Mô hình ngôn ngữ lớn: **gpt-4o-mini**
  - Mô hình nhúng: **text-embedding-3-large**
  - Cơ sở dữ liệu: **MongoDB Atlas**
    - Lưu văn bản và vector embedding
    - Cơ chế indexing trên văn bản (**text** index) và trên vector (vector index)
- Hoạt động:
  - Thu thập tài liệu văn bản pháp luật từ dataset:
    - Xử lý phân loại các văn bản liên quan đến chủ đề (tổng hợp từ các website, báo chí, diễn đàn, ...)
    - Nhúng văn bản của toàn bộ các tài liệu thành vector và lưu vào cơ sở dữ liệu:
      
      ![Tài liệu được lưu trên CSDL](/Document.png "Tài liệu được lưu trên CSDL")
    - Tổng quan cơ chế hoạt động của giải pháp:
      
      ![Tài liệu được lưu trên CSDL](/RAG_Advance-General.drawio.png "Tổng quan")
      ![Tài liệu được lưu trên CSDL](/RAG_Advance-Routing.drawio.png "Tổng quan")
      ![Tài liệu được lưu trên CSDL](/RAG_Advance-Chat.drawio.png "Tổng quan")
      ![Tài liệu được lưu trên CSDL](/RAG_Advance-HyDE.drawio.png "Tổng quan")
      ![Tài liệu được lưu trên CSDL](/RAG_Advance-Hybrid.drawio.png "Tổng quan")
      ![Tài liệu được lưu trên CSDL](/RAG_Advance-Generator.drawio.png "Tổng quan")
