# Mindmap vai trò QA/QC 2026+


```mermaid
mindmap
  root((Vai trò QA/QC 2026+))
    Nhóm vai trò chính
      Manual QA Tester
        Viết test case
        Kiểm thử thăm dò
        Kiểm thử hồi quy
        Ghi nhận bug
      Automation QA Engineer
        Tự động hóa UI
        Tự động hóa API
        Tích hợp test vào CI/CD
        Chuẩn bị test data
      QC Engineer
        Kiểm tra sản phẩm
        Ghi nhận lỗi thực tế
        Kiểm tra tiêu chí chấp nhận
        Thu thập bằng chứng kiểm thử
      QA Analyst
        Rà soát yêu cầu
        Phân tích rủi ro
        Lập kế hoạch kiểm thử
        Cải tiến quy trình chất lượng
      QA Lead / Test Manager
        Xây dựng chiến lược test
        Điều phối nhóm
        Kiểm soát chất lượng trước release
        Báo cáo metrics
    Hoạt động kiểm thử
      Phân tích yêu cầu
      Thiết kế test case
      Thực thi kiểm thử
      Báo cáo lỗi
      Retest
      Regression test
      Viết test summary report
    QA/QC kết hợp AI
      Tạo bản nháp test case
      Gợi ý edge case
      Tóm tắt yêu cầu
      Tạo test data
      Hỗ trợ viết script automation
      Phân tích log và lỗi test
      Rà soát bug report cho rõ ràng
    Kỹ năng cần có
      Kiến thức ISTQB Foundation
      Bug lifecycle
      API testing
      SQL cơ bản
      Công cụ automation
      Git và CI/CD
      Giao tiếp
      Tư duy sản phẩm
      Kỹ năng prompt với AI
    Tác động của AI
      AI có thể thay thế một phần
        Viết nháp checklist lặp lại
        Tạo test case cơ bản
        Tóm tắt log đơn giản
      AI có thể hỗ trợ
        Brainstorm test case
        Giải thích defect
        Viết boilerplate automation
        Làm rõ requirement
      AI chưa thể thay thế hoàn toàn
        Quan sát thiết bị thật
        Phán đoán theo domain
        Kết luận pass/fail cuối cùng
        Trách nhiệm đạo đức
        Giao tiếp với stakeholder
    Lộ trình nghề nghiệp
      Junior QA
      QA Engineer
      Automation QA
      Senior QA
      QA Lead
      Quality Engineering Manager
    Deliverables chính
      Test plan
      Test cases
      Checklist
      Bug report
      Test evidence
      Test summary report
      AI audit report
```

## 3 lỗi AI thường tạo ra và phần đã chỉnh sửa

| STT | Lỗi trong mindmap AI tạo | Vì sao sai/chưa đủ | Phần chỉnh sửa của sinh viên |
|---|---|---|---|
| 1 | Gộp QA và QC như cùng một vai trò. | QA thiên về phòng ngừa lỗi, quy trình và kế hoạch chất lượng; QC thiên về kiểm tra sản phẩm/kết quả đầu ra. | Tách riêng nhóm việc của QA Analyst/QA Lead và QC Engineer. |
| 2 | Diễn đạt như kiểm thử chỉ bắt đầu sau khi code xong. | Theo tư duy kiểm thử hiện đại, testing có thể bắt đầu từ giai đoạn review requirement, phân tích rủi ro và thiết kế test. | Bổ sung các nhánh phân tích yêu cầu, risk analysis và test planning trước test execution. |
| 3 | Cho rằng AI có thể thay thế hoàn toàn QA/QC engineer. | AI hỗ trợ tốt việc viết nháp, tóm tắt và gợi ý, nhưng không thể tự quan sát thiết bị thật, chịu trách nhiệm chất lượng hoặc đưa kết luận cuối cùng thay con người. | Đưa AI vào nhóm “hỗ trợ”, còn quan sát thực tế, phán đoán domain và verdict cuối cùng vẫn thuộc về QA/QC. |

## Ghi chú ngắn

Mindmap này thể hiện vai trò QA/QC không chỉ là chạy test, mà còn gồm phân tích yêu cầu, thiết kế kiểm thử, báo cáo lỗi, phối hợp với nhóm phát triển và ra quyết định chất lượng. AI có thể giúp tăng tốc các phần việc lặp lại hoặc tạo bản nháp, nhưng người kiểm thử vẫn phải kiểm chứng, thực thi trên sản phẩm thật, thu thập bằng chứng và chịu trách nhiệm với kết luận cuối cùng.
