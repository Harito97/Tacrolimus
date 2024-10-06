## Thông tin chi tiết về 4 nghiên cứu

Dưới đây là thông tin chi tiết về 4 nghiên cứu:

**Nghiên cứu 1: Tacrolimus_UseANN.pdf**

*   **Số lượng bệnh nhân:** 31 bệnh nhân ghép gan
*   **Thông tin đầu vào:**
    *   Thông tin nhân khẩu học: Tuổi, giới tính
    *   Chỉ số cơ thể: Cân nặng
    *   Thời gian sau phẫu thuật (POD)
    *   Các chỉ số sinh hóa: ALT, AST, GGT, TBIL, ALB, GLB, SCr, HCT
    *   Liều dùng tacrolimus hàng ngày
    *   Sử dụng đồng thời caspofungin hoặc Wuzhi capsule
    *   Kiểu gen CYP3A5 của người nhận và người hiến tạng
*   **Kết quả đầu ra mong muốn:** Nồng độ đáy của tacrolimus (C0) sau khi uống
*   **Phương pháp được sử dụng:** Mạng nơ-ron nhân tạo (ANN) với 3 lớp ẩn và giải thích Shapley Additive (SHAP)
*   **Kết luận về phương pháp tốt nhất:** Nghiên cứu không so sánh trực tiếp ANN với các phương pháp khác. Tuy nhiên, kết quả cho thấy mô hình ANN có độ chính xác cao trong việc dự đoán nồng độ C0 của tacrolimus.
*   **Kết luận khác:**
    *   Liều dùng tacrolimus hàng ngày, POD, kiểu gen CYP3A5 (của cả người nhận và người hiến tạng), tuổi của người nhận, GGT và việc sử dụng đồng thời caspofungin là những yếu tố có ảnh hưởng lớn nhất đến nồng độ C0 của tacrolimus.
    *   Nồng độ C0 của tacrolimus tăng khi liều dùng hàng ngày vượt quá 3 mg và khi cả người nhận và người hiến tạng đều có kiểu gen CYP3A5\*3\*3.
    *   Nồng độ C0 giảm khi tuổi của người nhận lớn hơn 48.
    *   Việc sử dụng đồng thời caspofungin hoặc Wuzhi capsule làm tăng nồng độ C0 của tacrolimus.

**Nghiên cứu 2: Tacrolimus_UseML1.pdf**

*   **Số lượng bệnh nhân:** 1045 bệnh nhân ghép thận (838 bệnh nhân trong nhóm huấn luyện và 207 bệnh nhân trong nhóm xác thực)
*   **Thông tin đầu vào:**
    *   Thông tin nhân khẩu học: Tuổi, giới tính
    *   Chỉ số cơ thể: Chiều cao, cân nặng
    *   Các chỉ số sinh hóa: Hemoglobin, số lượng bạch cầu, creatinine huyết thanh, bilirubin toàn phần, albumin
    *   Bệnh lý nền: Cao huyết áp, tiểu đường
    *   Loại người hiến tạng (còn sống hay không)
    *   Các biến chứng sau ghép tạng: Thiếu máu, suy tim
    *   Sử dụng đồng thời các loại thuốc khác: Thuốc chẹn kênh canxi, metoprolol, omeprazole, furosemide, thuốc ức chế men chuyển angiotensin (ACEI) hoặc thuốc đối kháng thụ thể angiotensin II (ARA), cephalosporin
    *   Nhiễm trùng
    *   Kiểu gen CYP3A5
*   **Kết quả đầu ra mong muốn:** Liều tacrolimus ổn định (TSD)
*   **Phương pháp được sử dụng:** Hồi quy tuyến tính bội (MLR), mạng nơ-ron nhân tạo (ANN), cây hồi quy (RT), hồi quy spline thích nghi đa biến (MARS), cây hồi quy tăng cường (BRT), hồi quy vectơ hỗ trợ (SVR), hồi quy rừng ngẫu nhiên (RFR), hồi quy lasso (LAR), và cây hồi quy cộng Bayesian (BART)
*   **Kết luận về phương pháp tốt nhất:** Cây hồi quy (RT) cho hiệu suất tốt nhất trong cả hai nhóm huấn luyện và xác thực.
*   **Kết luận khác:**
    *   Cao huyết áp, tiểu đường, sử dụng omeprazole và kiểu gen CYP3A5 có liên quan đáng kể đến TSD.
    *   Kiểu gen CYP3A5\*3 GG là yếu tố ảnh hưởng đáng kể nhất.

**Nghiên cứu 3: Tacrolimus_UseML2.pdf**

*   **Số lượng bệnh nhân:** 443 bệnh nhân ghép gan (355 bệnh nhân trong nhóm huấn luyện và 88 bệnh nhân trong nhóm xác thực)
*   **Thông tin đầu vào:**
    *   Liều dùng tacrolimus hai lần mỗi ngày (lên đến 14 ngày sau phẫu thuật)
    *   Nồng độ tacrolimus trong máu toàn phần
    *   Thông tin nhân khẩu học: Tuổi, giới tính
    *   Chỉ số cơ thể: Chiều cao, cân nặng
    *   Điểm MELD (Model for End-Stage Liver Disease)
    *   Loại người hiến tạng
    *   Chỉ định ghép gan
    *   Các thuốc ức chế miễn dịch khác được sử dụng
    *   Các kết quả xét nghiệm máu: ALT, AST, bilirubin toàn phần, INR, albumin, creatinine, hematocrit
*   **Kết quả đầu ra mong muốn:** Nồng độ tacrolimus
*   **Phương pháp được sử dụng:** Mô hình bộ nhớ dài hạn (LSTM), cây hồi quy tăng cường (GBRT), hồi quy tuyến tính (LR), và mô hình dược động học quần thể (popPK)
*   **Kết luận về phương pháp tốt nhất:** LSTM cho thấy hiệu suất vượt trội so với GBRT, LR, và popPK trong cả hai nhóm xác thực nội bộ và bên ngoài.
*   **Kết luận khác:**
    *   Các mô hình học máy có thể dự đoán nồng độ tacrolimus ở bệnh nhân ghép gan với độ chính xác cao hơn so với các mô hình truyền thống.
    *   Việc sử dụng liều lượng dựa trên khuyến nghị của mô hình LSTM giúp đạt được nồng độ điều trị mục tiêu thường xuyên hơn.
    *   Bệnh nhân được điều trị với liều lượng nằm ngoài phạm vi khuyến nghị của mô hình có thời gian nằm ICU dài hơn trung bình 2.5 ngày.

**Nghiên cứu 4: Tacromilus_UseML3_GhepThan.pdf**

*   **Số lượng bệnh nhân:** Nghiên cứu không đề cập rõ ràng số lượng bệnh nhân tham gia.
*   **Thông tin đầu vào:**
    *   Thông tin nhân khẩu học: Tuổi, giới tính
    *   Chỉ số cơ thể: Chiều cao, cân nặng
    *   Thời gian sau phẫu thuật
    *   Các kết quả xét nghiệm máu: creatinine, urê
    *   Liều dùng cyclosporine A hàng ngày
    *   Nồng độ cyclosporine A
    *   Kiểu gen MDR1 (ABCB1)
    *   Sử dụng đồng thời các loại thuốc khác: Thuốc chẹn kênh canxi, thuốc ức chế men chuyển, thuốc chẹn thụ thể angiotensin
*   **Kết quả đầu ra mong muốn:** Nồng độ cyclosporine A
*   **Phương pháp được sử dụng:** Hồi quy tuyến tính (LR), máy vectơ hỗ trợ (SVR), rừng ngẫu nhiên (Random Forest), XGBoost, LightGBM, CatBoost, mạng nơ-ron nhân tạo (ANN) và mô hình dược động học quần thể (popPK)
*   **Kết luận về phương pháp tốt nhất:** ANN cho thấy hiệu suất tốt nhất trong số các mô hình học máy được so sánh, với giá trị R2 cao nhất (0.75) và sai số dự đoán trung bình thấp nhất (-0.039).
*   **Kết luận khác:**
    *   Kiểu gen MDR1, liều dùng cyclosporine A hàng ngày, và việc sử dụng đồng thời các loại thuốc khác là những yếu tố quan trọng ảnh hưởng đến nồng độ cyclosporine A.

**Lưu ý:**

*  Thông tin về nồng độ thuốc tối thiểu cần duy trì và thời gian giữa các lần dùng thuốc không được đề cập trong các nghiên cứu này.
*  Mặc dù các mô hình học máy cho thấy tiềm năng trong việc dự đoán nồng độ thuốc và hỗ trợ cá thể hóa điều trị, việc theo dõi nồng độ thuốc trong máu vẫn rất cần thiết trong thực hành lâm sàng. 
