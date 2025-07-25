# Multimodal_LLMs
Làm trên kaggle 
Dự án 1: Image Captioning cơ bản (Sinh mô tả từ ảnh)

Sử dụng mô hình có sẵn như BLIP hoặc LLaVA

Mục tiêu:
Nhập vào một ảnh → mô hình sinh ra mô tả bằng tiếng Việt hoặc tiếng Anh.

Công cụ:
Python + transformers + torch

Mô hình: BLIP (Salesforce) hoặc blip-image-captioning-base từ Hugging Face

Dataset: MS-COCO (hoặc dùng ảnh tùy chọn)

Output:
Web app nhỏ bằng Streamlit: Chọn ảnh → hiển thị caption mô tả

<!-- 🎯 Dự án 2: Visual Question Answering (VQA)
✅ Kết hợp hiểu ảnh và xử lý câu hỏi văn bản
⚙️ Áp dụng mô hình đa phương thức như LLaVA, MiniGPT-4

✅ Mục tiêu:
Nhập vào: ảnh + câu hỏi

Mô hình trả lời đúng dựa trên nội dung ảnh

🧰 Công cụ:
Mô hình: LLaVA hoặc MiniGPT-4

Streamlit hoặc Gradio giao diện người dùng

📦 Output:
Giao diện cho người dùng upload ảnh + nhập câu hỏi → hiển thị câu trả lời

🎯 Dự án 3: Contrastive Image-Text Search (Tìm ảnh theo văn bản hoặc ngược lại)
✅ Áp dụng contrastive learning + embedding
⚙️ Gần với CLIP (OpenAI)

✅ Mục tiêu:
Nhập vào đoạn mô tả → tìm ra ảnh phù hợp nhất (hoặc ngược lại)

So khớp ảnh – caption bằng độ tương đồng vector (cosine similarity)

🧰 Công cụ:
Mô hình: CLIP (openai/clip-vit-base-patch32 từ Hugging Face)

Dataset: COCO nhỏ hoặc ảnh tự thu thập

Giao diện tìm kiếm bằng Gradio

📦 Output:
Tìm kiếm ảnh bằng mô tả ngắn (“mèo trên bàn”) → hiển thị ảnh phù hợp -->
