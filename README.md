# CSC13003 — HW01: QA/QC Jobs, Software Defects and Physical Product Testing

Repository lưu trữ toàn bộ artifact của bài tập cá nhân **HW01-AI** thuộc môn **CSC13003 — Kiểm thử phần mềm**.

| Thông tin | Giá trị |
|---|---|
| Sinh viên | Tống Dương Thái Hòa |
| MSSV | 23120262 |
| Lớp | Software Testing — CQ2023/3 |
| Bài tập | HW01-AI |
| Repository | https://github.com/henry-banana/software-testing-hw01-qa-qc-jobs |

## Phạm vi bài làm

1. **Thị trường việc làm QA/QC 2026+:** tổng hợp 10 tin tuyển dụng trong phạm vi 60 ngày, kèm mô tả công việc, kỹ năng, thông tin lương, ảnh chụp và phân tích tác động của AI.
2. **Lỗi phần mềm giai đoạn 2022–2026:** phân tích 20 sự cố phần mềm công khai, bao gồm các trường hợp liên quan đến AI/LLM và phần kiểm toán hiện tượng bịa đặt hoặc thiên lệch của AI.
3. **Kiểm thử sản phẩm vật lý:** thiết kế 15 ca kiểm thử cho quạt đứng, ghi nhận kết quả PASS và cung cấp 5 video minh chứng thực thi.

## Danh mục artifact

| Artifact | Nội dung |
|---|---|
| [Report.md](Report.md) | Báo cáo chính: nghiên cứu việc làm, 20 lỗi phần mềm, kiểm thử sản phẩm, AI critique, disclosure và tự đánh giá. |
| [Test_Cases_Checklist_Test_Summary.xlsx](Test_Cases_Checklist_Test_Summary.xlsx) | Test cases, checklist thực thi và test summary của sản phẩm vật lý. |
| [Video_Links.md](Video_Links.md) | Liên kết 5 video thực thi các ca kiểm thử đã chọn. |
| [QAQC_Role_Mindmap.md](QAQC_Role_Mindmap.md) / [QAQC_Role_Mindmap.png](QAQC_Role_Mindmap.png) | Mindmap vai trò QA/QC ở dạng Markdown và PNG. |
| [Job_Posting_Screenshots](Job_Posting_Screenshots/) | 10 ảnh chụp tin tuyển dụng dùng làm bằng chứng cho Requirement 1. |
| [Device_Evidence](Device_Evidence/) | Ảnh thiết bị, nhãn thông tin và thẻ sinh viên trong cùng khung hình theo yêu cầu. |
| [Appendix_A_Prompt_Log.md](Appendix_A_Prompt_Log.md) | Nhật ký prompt AI có timestamp. |
| [[AI-02] AI Audit Report](<[AI-02] - FIT@HCMUS - AI Audit Report.md>) | Báo cáo kiểm toán các artifact có AI hỗ trợ. |
| [[AI-03] AI Disclosure Form](<[AI-03] - FIT@HCMUS - AI Disclosure Form.md>) | Biểu mẫu khai báo việc sử dụng AI. |
| [[AI-05] AI Privacy Checklist](<[AI-05] - FIT@HCMUS - AI Privacy Checklist.md>) | Checklist quyền riêng tư và sử dụng AI có trách nhiệm. |
| [Git_Commit_Log.txt](Git_Commit_Log.txt) | Lịch sử commit đầy đủ theo định dạng `git log --graph --stat`. |

Ba biểu mẫu AI có cả bản Markdown và bản PDF đã ký trong thư mục gốc.

## Cấu trúc repository

```text
software-testing-hw01-qa-qc-jobs/
├── Report.md
├── Test_Cases_Checklist_Test_Summary.xlsx
├── Video_Links.md
├── QAQC_Role_Mindmap.md
├── QAQC_Role_Mindmap.png
├── Job_Posting_Screenshots/
├── Device_Evidence/
├── Appendix_A_Prompt_Log.md
├── [AI-02] - FIT@HCMUS - AI Audit Report.md/.pdf
├── [AI-03] - FIT@HCMUS - AI Disclosure Form.md/.pdf
├── [AI-05] - FIT@HCMUS - AI Privacy Checklist.md/.pdf
├── Git_Commit_Log.txt
└── README.md
```

## Cách kiểm tra bài làm

- Đọc [Report.md](Report.md) để xem nội dung báo cáo và bảng tự đánh giá.
- Mở workbook Excel để kiểm tra chi tiết test cases, checklist và kết quả thực thi.
- Đối chiếu video trong [Video_Links.md](Video_Links.md) với test case tương ứng trong workbook và báo cáo.
- Kiểm tra ảnh nguồn trong hai thư mục bằng chứng và đối chiếu với các tham chiếu trong báo cáo.
- Xem lịch sử phiên bản bằng `git log --graph --stat` hoặc [Git_Commit_Log.txt](Git_Commit_Log.txt).

Repository này là hồ sơ bài tập học thuật; không yêu cầu cài đặt hoặc chạy phần mềm.
