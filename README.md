## Mục tiêu 

Trình bày toàn bộ quy trình xây dựng chatbot nội bộ.

So sánh hiệu quả giữa phương pháp tìm kiếm truyền thống (keyword-based) và phương pháp embedding hiện đại.

Thực hành triển khai mô hình thực tế với công cụ như Langchain, Chroma, và OpenAI Embedding API.

## Các bước triển khai

### 1. Ý tưởng cơ bản: Keyword Matching
   
Khởi đầu với cách tiếp cận truyền thống: tìm kiếm và trích xuất thông tin theo từ khóa.

Sử dụng Despseek làm mô hình LLM.

Cơ chế hoạt động tương tự như chatbot rule-based.

### 2. Nâng cấp với Vector Embedding
   
Giới thiệu khái niệm semantic search thông qua việc chuyển đổi văn bản thành vector số học trong không gian nhiều chiều.

🔍 Một số mô hình embedding tiêu biểu:

Word2Vec	2013	[Link PDF](https://arxiv.org/pdf/1301.3781)

BERT	2018	[Link PDF](https://arxiv.org/pdf/1810.04805)

OpenAI Embedding	2024	[OpenAI Docs](https://platform.openai.com/docs/guides/embeddings)

### 3. Sử dụng Framework: Langchain

Trang chủ: https://www.langchain.com

Hỗ trợ tạo pipeline để tích hợp LLM + retriever + prompt templates nhanh chóng.

Tích hợp tốt với nhiều vector stores, bao gồm Chroma, FAISS, Pinecone, v.v.

### 4. Vector Store: ChromaDB

Trang chủ: https://www.trychroma.com

Dễ sử dụng, cài đặt nhanh, phù hợp với dự án nhỏ & vừa.

Hỗ trợ persist dữ liệu vector, metadata và document chunks.

Đây là dự án test: có bất kỳ vấn đề liên quan vui lòng liên hệ: nnghoa6@gmail.com. Xin cảm ơn
